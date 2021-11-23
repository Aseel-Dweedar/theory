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

| session               | cookie                          |
| --------------------- | ------------------------------- |
| more secure           | less secure                     |
| stored at server side | stored at client browser        |
| unlimited             | limited for the site by browser |
| store any data type   | store as keyvalue(string)       |
|                       | changed stored and turned       |
|                       | off from the browser            |
