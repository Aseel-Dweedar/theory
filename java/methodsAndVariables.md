- **What are the access modifiers? And what does each one of them mean?**

  access modifiers in Java helps to restrict the scope of a class, constructor, variable, method, or data member.

  types of access modifiers available in java:

  **Default – No keyword required**

  **Private**

  **Protected**

  **Public**

  ![Access-Modifiers](../img/Access-Modifiers-in-Java.png)

- **What is ‘this’ pointer?**

  is a reference variable that refers to the current object of a method or a constructor.

- **What is the default access modifier in a class?**

  When no access modifier is specified for a class, method, or data member – It is said to be having the default access modifier by default.

- **what is final?**

  1. Java final variable : If you make any variable as final, you cannot change the value of final variable(It will be constant).

  2. Java final method : If you make any method as final, you cannot override it.

  3. Java final class: If you make any class as final, you cannot extend it.

- **Can static method use nonstatic members?**

  No

- **What is the purpose of static methods and variables?**

  invoke the class without using instance.

- **What is the difference between JDK, JRE, and JVM?**

  - JDK (Java Development Kit) : used for making applets and Java applications.
  - JRE (Java Runtime Environment): if you want to run Java program you need JRE.
  - JVM (Java Virtual Machine) : engine that provides a runtime environment to drive the Java Code or applications. It converts Java bytecode into machine language.

- **What is an association? and What is aggregation? What is composition?**

  - **Association** is a connection or relationship between two separate classes.

  - **Aggregation** in Java is a special kind of association. It represents the Has-A relationship between classes. Java Aggregation allows only one-to-one relationships.

  - **Composition** is another form of aggregation which is considered as the restricted form of Association. the entities are completely dependent on each other. Composition allows for one-to-many relationships between objects.
