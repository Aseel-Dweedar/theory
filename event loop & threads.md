- **What is the difference between multi thread and single thread ? programming languages examples !** (IntraSoft interview)

  programs that works on one operation at a time called single thread - line by line - but when a program can run multiple operations at the same time so called multi thread .. js is an example of single thread programming language and java and python is multi thread programming language.

  https://www.youtube.com/watch?v=jOupHNvDIq8&t=243s


- **What is the event loop ?**

  javascript uses it to loop through the programme , execute the sync operations and store all the async operations in a table to be executed later .. so when the program finishes executing all sync tasks it will execute task from async table starting from the order as priority then the time if it have specific time to be run at ..

  https://www.youtube.com/watch?v=8zKuNo4ay8E

- **Explain the JavaScript event loop. and How the node handles two requests at the same time while its single threaded?**

  javascript implementation for it's programs depends on passing through operations and executing them as sync operations , when pumping into async operation/function , it overrides it to the next sync operation an so on, until the whole call stack is executed, while the skipped async operations get implemented when the event fires(ex: click button) or a request received-(or response),the data gets passed to the callback function that will handle it, that helps not to hang all operations till async functions gets implemented - thats also called none-blocking because async operations won't prevent other sync ones ..

  https://www.youtube.com/watch?v=8zKuNo4ay8E