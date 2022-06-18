- **What is Database transaction?** (IntraSoft interview )

  A transaction, in the context of a database, is a logical unit that is independently executed for data retrieval or updates

  you want to treat as "a whole." It has to either happen in full or not at all.

  A classical example is transferring money from one bank account to another. To do that you have first to withdraw the amount from the source account, and then deposit it to the destination account. The operation has to succeed in full. If you stop halfway, the money will be lost, and that is Very Bad.

  In modern databases transactions also do some other things - like ensure that you can't access data that another person has written halfway. But the basic idea is the same - transactions are there to ensure, that no matter what happens, the data you work with will be in a sensible state. They guarantee that there will NOT be a situation where money is withdrawn from one account, but not deposited to another.

- **What is the difference between a MySQL statement and transition?**

  A statement is a single operation, applies to a single row in a table or vast numbers of rows in multiple tables.

  A transaction groups multiple consecutive statements in a single atomic unit.

- **What is Database Indexing?**

  https://stackoverflow.com/questions/1108/how-does-database-indexing-work

  https://www.youtube.com/watch?v=zDzu6vka0rQ

- **What ORMs did you use? how are they useful?**

  "mongoose .. example" , **Object-relational mapping (ORM)** is a layer that converts our data between Database and object-oriented entities using object-oriented programming (OOP) language.

- **is postgres secure more than mongodb and why?**

  Yes, NoSQL databases are relatively new and are not preferred for highly secure applications.

- **what is the difference between postgres and mysql?**

  |                      | PostgreSQL                                                                                                                   | MySQL                                        |
  | -------------------- | ---------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------- |
  | Architecture         | Object relational;multiprocess                                                                                               | Relational; single process                   |
  | Data types supported | Numeric, date/time, character, boolean, enumerated, geometric, network address, JSON, XML, HSTORE, arrays, ranges, composite | Numeric, date/time, character, spatial, JSON |
  | Performance | Suited for applications with high volume of both reads and writes | Suitable for applications with high volume of reads |