- **whats the difference between compiler and interpreter ?**

|                          interpriter                           |                       compiler                       |
| :------------------------------------------------------------: | :--------------------------------------------------: |
|                take the statment and excute it                 |  takes the whole code and analyze it then excute it  |
|          faster in analyzeing but slower at excuting           |   slower at analyzing code and faster in excuting    |
|                        easier to debug                         |                   harder to debug                    |
| it takes a statment by a statment and stop at any bug it finds | it scans the whole code then sends the error message |

<br>

<hr>
<hr>

<br>

- **What’s the difference between encryption and hashing?**

- **What’s the difference between encoding, obfuscation, minification, and compression?**

  https://auth0.com/blog/how-secure-are-encryption-hashing-encoding-and-obfuscation/

|           hashing            | encryption                  |
| :--------------------------: | :-------------------------- |
| one way - can't be de-hashed | two ways - can be decrypted |

<br>

<hr>
<hr>

<br>

- **What’s the difference between a socket and a port?** [from this link](https://searchnetworking.techtarget.com/answer/What-is-the-difference-between-a-port-and-a-socket)

|                                 socket                                 | port                                                              |
| :--------------------------------------------------------------------: | :---------------------------------------------------------------- |
|                     one end point of a connection                      | logical connection method two end points communicate with         |
|               means of plugging the application layer in               | operate at the Transport layer of the OSI                         |
|              determined by an IP address and port number               | 16-bit integer                                                    |
| two-way communication link between two programs running on the network | identify a specific process to which a message is to be forwarded |

<br>

<hr>
<hr>

<br>

**What is the difference between primary key and unique constraints?**

Ans: Primary key cannot have NULL value, the unique constraints can have NULL values. There is only one primary key in a table, but there can be multiple unique constrains.

| primary key      | unique constraints       |
| ---------------- | ------------------------ |
| can't be null    | can be null              |
| one in the table | can be many in the table |

<br>

<hr>
<hr>

<br>

**What is the difference between having and where clause?**

| HAVING clause                                                                             | WHERE clause                       |
| ----------------------------------------------------------------------------------------- | ---------------------------------- |
| used to specify a condition for a group or an aggregate function used in select statement | selects before grouping            |
| selects rows after grouping                                                               | cannot contain aggregate functions |

<br>

<hr>
<hr>

<br>

**what is the difference between session and cookie ?**

- A session is used to temporarily store the information on the server to be used across multiple pages of the website.

- A cookie is a small text file that is stored on the user's computer.

[Local Storage & Session Storage](https://www.youtube.com/watch?v=MOd5cTJ6kaA)

| session               | cookie                          |Local Storage|
| --------------------- | ------------------------------- |----|
| more secure           | less secure                     ||
| stored at server side | stored at client browser        |stored at client browser|
| Data is gone when you close the browser tab | Has different expiration dates (both the server or client can set up expiration date) |Has no expiration date|
| store any data type   | store as keyvalue(string)       |store as keyvalue(string)|
| Has no SSL support   | Has SSL Support       |Has no SSL support|
| 5-10 mb limit   | 4kb limit       |5 mb limit |
| Data are not transferred on each HTTP request   |Data are transferred on each HTTP request      |Data are not transferred on each HTTP request |
| The client  can only read local storage   |Both clients and servers can read and write the cookies      |The client  can only read local storage |

<br>

<hr>
<hr>

<br>

- **What is the difference between sql and NoSql?**

| SQL                               | NoSql                                                       |
| --------------------------------- | ----------------------------------------------------------- |
| vertically scalable               | horizontally scalable secure                                |
| table-based stores                | stored at document, key-value, graph, or wide-column stores |
| better for multi-row transactions | better for unstructured data like documents or JSON         |

<br>

<hr>
<hr>

<br>

- **What is the difference between functional component and class component? / React**

| functional component                                                                    | class component                                                                         |
| --------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| plain JavaScript function that accepts props as an argument and returns a React element | extend from React. Component and create a render function which returns a React element |
| no render method                                                                        | must have the `render()` method returning HTML                                          |
| React lifecycle methods (for example, componentDidMount) cannot be used                 | React lifecycle methods can be used inside                                              |
| Hooks can be easily used                                                                | It requires different syntax inside a class component to implement hooks                |
| Constructors are not used                                                               | Constructor are used as it needs to store state                                         |
