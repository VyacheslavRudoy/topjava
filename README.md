[![Codacy Badge](https://app.codacy.com/project/badge/Grade/63819748dd8e4abbbeedc48e0842355b)](https://www.codacy.com/gh/VyacheslavRudoy/topjava/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=VyacheslavRudoy/topjava&amp;utm_campaign=Badge_Grade)

Java Enterprise Online Project (topjava)
===============================
### Calories Management

#### This Java Enterprise project is a system that includes user registration and authorization capabilities. Depending on their role (USER, ADMIN), their access rights differ.
 The **ADMIN** has the ability to:
 - create users
 - edit users
 - delete user users.

  The **USER** can manage his profile and data (food) through the user interface (using AJAX) and through the REST API with basic authorization.
  
 - The system also provides filtering of the shopping list by date and time.
 
 - The color of the purchase records in the table will depend on whether the amount of calories per day exceeds the established norm, which the user can edit in his profile.
 
- All REST API operations are covered by JUnit tests using Spring MVC Rest and Spring Security Test.

#### Technologies:
Spring Security, Spring MVC, Spring Data JPA, Spring Security Test, Hibernate ORM, Hibernate Validator, SLF4J, Json Jackson, JSP, JSTL, Apache Tomcat, WebJars, DataTables, EHCACHE, PostgreSQL, HSQLDB, JUnit 5, Hamcrest, AssertJ, jQuery, jQuery plugins, Bootstrap.


#### Screenshot from user profile:
 ![image](https://github.com/VyacheslavRudoy/topjava/assets/97558285/8f850ae6-2821-4575-a072-2db4bdab90e6)

