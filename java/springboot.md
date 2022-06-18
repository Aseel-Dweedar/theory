- **what is the design pattern that is used with spring boot apps?**

    MVC.

- **if you have more than one import to a Repository in your controller, how can you handle what to use?** (Diversity group interview)

    using qualifier annotation.

    - **what is the qualifier annotation?**

        annotation provides additional information to @Autowired annotation while resolving bean dependency. If more than one bean of the same type is available in the container, we need to tell container explicitly which bean we want to inject

        [Spring Boot Bean Annotations](https://javatechonline.com/spring-boot-bean-annotations-with-examples)

- **what is the difference between using Angular or thymeleaf with spring boot?** (Diversity group & IntraSoft interviews)

  The most important difference is reusability of back-end services. when you use thymeleaf, you are returning string fragments/pages into client side, while if you use angular, you can return objects (json response) into client side, so that can be used by different clients. **thymeleaf** is conceder as server side rendering, while **Angular** is a single web page rendering.