- **Mention some aggregation functions in mongo, and what they do?**

  Aggregation operations process data records and return computed results. Aggregation operations group values from multiple documents together, and can perform a variety of operations on the grouped data to return a single result.

- **what is Views in mongodb?**

  A queryable object whose contents are defined by an aggregation pipeline on other collections or views.

- **.what is the importance of the schema feature in mongoose?**

  defines the structure of the documents in your collection.

- **how to make a relations in mongodb?**

  1-  relate with a specifics field on other schema

  ```javascript
  const catSchema = new mongoose.Schema({
    name: String,
    breed: String,
    description: String,
    user: {
        type: mongoose.Schema.Types.ObjectId,
        ref: "user",
    },
    // won't be effected by user document
  });
  ```

  2- using virtual filed.

  ```javascript
  const userSchema = new mongoose.Schema({
        username: String,
        password: String,
        email: String,
    },
    {
        toJSON: { virtuals: true },
        toObject: { virtuals: true },
    }
  );
  userSchema.virtual("cats", {
      ref: "cat",
      localField: "_id",
      foreignField: "user",
  });

  // virtual view from cat schema, the changes on the cat document will effect here
  ```