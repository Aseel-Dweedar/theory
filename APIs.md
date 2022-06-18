- **what are the types of APIs** (Diversity group interview)

  1. Rest.
  2. Soap.
  3. GraphQl.

  - https://medium.com/better-practices/rest-soap-graphql-gesundheit-6544053f65cf

  - https://cyclr.com/blog/rest-vs-soap-vs-graphql-api-types

  ![graph-vs-rest](/img/graph-vs-rest.png)

- **Define Restful API’s - REST (Representational State Transfer)**

  webs and applications that implements REST API is called restful, REST is programming architectural style for designing webs and apps, since we have pre-agreed-on rules to be followed; client can interact with the server without the need to know the details of operations the back end implements, networking apps agrees on using HTTP requests, get, post, put, delete,... and so with specific rules of when to use it and the purpose of it and the expected result.

### **Group of sequential questions by Diversity group Co.**

***
- **If my server receive too many request how to handle that** 

  Deploy it in multi server and use the load balancer.

- **What is load balancer in server?**

  load balancer sits between client devices and backend servers, receiving and then distributing incoming requests to any available server capable of fulfilling them.

- **if we have more than one deployed server but there is a common STATIC data need to be fetched, how to handle fetch it once and use it on all of my server?**

  it should be one general server that handle get the data from database and use it in other server.

- **if there is a multi used almost static data should i re fetch it every time from the database?**

  No. we can cache these data using a local storage or some caching system like Rids. depends on the datatype.

- **what is Rids?**

  Fast, open source in-memory data store for use as a database, cache, message broker, and queue.

- **When do we clear oue cache?** (By Amazon also)

  - Your application is running slowly, so you want to check whether your Redis instance is the slow component.
  - You want to clear out a bunch of old data that's no longer relevant.
  - You're debugging a problem and want to see whether clearing Redis helps.

***