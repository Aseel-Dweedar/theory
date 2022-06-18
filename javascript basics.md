## Basics

- [JS Engine EXPOSED](https://www.youtube.com/watch?v=2WJL19wDH68)
- [How JavaScript Code is executed](https://www.youtube.com/watch?v=iLWTnMzWtj4)
- [How JavaScript Works](https://www.youtube.com/watch?v=ZvbzSrg0afE)
- [Hoisting](https://www.youtube.com/watch?v=Fnlnw8uY6jo&t=524s)
- [let & const](youtube.com/watch?v=BNC6slYCj50)
- [undefined vs not defined](https://www.youtube.com/watch?v=B7iF6G3EyIk)
- [How functions work in JS](https://www.youtube.com/watch?v=gSDncyuGw0s&t=594s)
- [Asynchronous JavaScript & EVENT LOOP](https://www.youtube.com/watch?v=8zKuNo4ay8E&t=1s)
- [Callback Functions](https://www.youtube.com/watch?v=btj35dh3_U8&t=112s)
- [Higher-Order Functions](https://www.youtube.com/watch?v=HkWxvB1RJq0&t=1164s)
- [The Scope Chain & Lexical Environment](https://www.youtube.com/watch?v=uH-tVP8MUs8)
- [Closures](https://www.youtube.com/watch?v=qikxEIxsXco)

==================================================

  **---> [JavaScript Tips](/img/js%20tips/JS-Tips.md)**

==================================================

- **Is JavaScript a functional language? What does it mean for a language to be “functional”?**

  to be able to build functions inside it based on **lambda-calculus**, which is done by declarations or impressions

==================================================

- **Give a brief analogy explaining how computer memory works to a beginning programmer.**

  using a connecting bus between the cpu and the different types of memory to allow data to be fetched or stored at memory units ....

==================================================

- **javascript is multi or single threaded language?**

  [single threaded](./event%20loop%20%26%20threads.md)
  
==================================================

- **What’s a “declarative” language?**

  any other language than imperative .. which depends on declaring operations without describing how the program should accomplish them.

==================================================

- **Benefits of using arrow functions?** (MyKloud interview)

  1. Arrow syntax automatically binds this to the surrounding code's context. (Auto binding)
  2. The syntax allows an implicit return when there is no body block.
  3. resulting in shorter and simpler code in some cases

==================================================

- **What is the differences btw synch and async?**

  Synchronous = happens at the same time. Asynchronous = doesn't happen at the same time.

==================================================

- **How are promises used?**

  promises used to handle asynchronous operations in JavaScript. This lets asynchronous methods return values like synchronous methods: instead of immediately returning the final value, the asynchronous method returns a promise to supply the value at some point in the future.

==================================================

- **what is the difference between null and undefined javascript?**

  **Null**: It is one of the primitive values of JavaScript representation of no value. `let testVar;`

  **Undefined**: It means the value does not exist in the compiler. It is the global object . `let testVar = null;`

==================================================

- **what is closures?**

  Global variables can be made local (private) with closures. a closure gives you access to an outer function’s scope from an inner function.

==================================================

- **what is the difference between let and var?**

  var is function scoped and let is block scoped.

==================================================

- **how to copy array to another?**

  1. using spread operator -->  `arr1 = [ ...arr1 , ...arr2]`
  2. loop and push.
  3. push all ---> `arr1.push(...arr2)`
  4. using concat. 'google it'.

==================================================

- **what is prototype??**

  JavaScript objects inherit features from one another.
