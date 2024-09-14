﻿# ProjectSpringBoot-JobPortal


 Here is the Project

 FrontEnd uses -  REACT

 BackEnd uses  -  SpringBoot
/////////////////////////////////////////////////////////////////////////

 NOTE
 ----
 1 you can use any of the spring backend application controller

 2 It use Postgre sql as you can see in application.properties

 3 you can perform GET, POST, DELETE, and PUT both in REACT UI or testing tool like POSTMAN

 4 All path links are spectified at Controller.class in Spring Application at Annotations which are ahead of methods.


  Understanding thr Spring Boot REST API Controllers
  -------------------------------------------------
 1 REST Controllers in Spring Boot are the components that handle HTTP requests and generate responses for a RESTful web service.

 2 They are defined using the @RestController annotation, which is a specialized version of the @Controller annotation combined with @ResponseBody.

 3 This setup allows the controller to handle REST API requests such as GET, POST, DELETE, and PUT, and return the response directly to the client without rendering a view.



 Prequistics:
 -------------
 1 Java Development Kit (JDK)

 2 Integrated Development Environment (IDE)

 3 Maven or Gradle

 4 Hiberante

 4 Spring Boot



 TO RUN THE FRONTEND
 ---------------------

 --> Defautly in cloned application , you did get any node modules.so to install them simply use command:
     /// npm install ////

 -->And to run app , use the following command on console:
    /// npm start



Defaulty it loads the  5 OBjects of JobPost
--------------------------------------------


<!-- new JobPost(1, "Java Developer", "Must have good experience in core Java and advanced Java", 2,
                        List.of("Java", "Javascript", "Python")),
                new JobPost(2, "Frontend Developer", "Experience in building responsive web applications using React",
                        3, List.of("HTML", "CSS", "JavaScript", "React")),
                new JobPost(3, "Data Scientist", "Strong background in machine learning and data analysis", 4,
                        List.of("Python", "Machine Learning", "Data Analysis")),
                new JobPost(4, "Network Engineer", "Design and implement computer networks for efficient data communication", 5,
                        List.of("Networking", "Cisco", "Routing", "Switching")),
                new JobPost(5, "Mobile App Developer", "Experience in mobile app development for iOS and Android",
                        3, List.of("iOS Development", "Android Development", "Mobile App")) -->

///////////////////////////////////////////////////////////

** Make sure that To install Postgre sql in your machine
 the most relevant tools for it is ***PGADMIN///////
//////////////////
** you can download it here Link-https://www.postgresql.org/download/
    
