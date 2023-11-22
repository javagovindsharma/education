# education

Create REST Services for an Education Site where you can do the Following Activities
1- Create Courses Restful Web Service [API] Where you can do the Following [ add-Course ,
get-Courses , update-Course , delete-Course ]
2- Create Restful Web Service for Student Where you can do the Following Activities
a. Register Student to the website providing his details which include

                                - Full name in English and Arabic
                                - Email address
                                - Telephone number
                                - Address

b. Consume Courses Web service to get List of Courses and Create an Restful
Endpoint for This to view the List of Courses
c. Create Restful service to Allocate Student  With Selected Course save it to DB
d. Create Restful service to Get all Students with selected Courses
e. Create Restful service to Update Courses for one Student
f. Create Restful service to delete one Student
g. Implement Swagger , Spring Profiles (Dev-Test-Prod) ,  Exception Handling

Use the Following Technologies While Creating this Task
Using spring boot / Spring , maven, hibernate , jpa , h2 / MySQL Database , JWT Authetication

src
|-- main
|   |-- java
|   |   |-- com.example.educationsite
|   |       |-- controller
|   |       |   |-- CourseController.java
|   |       |   |-- StudentController.java
|   |       |-- model
|   |       |   |-- Course.java
|   |       |   |-- Student.java
|   |       |-- repository
|   |       |   |-- CourseRepository.java
|   |       |   |-- StudentRepository.java
|   |       |-- service
|   |       |   |-- CourseService.java
|   |       |   |-- StudentService.java
|   |       |-- EducationSiteApplication.java
|   |-- resources
|       |-- application.properties
|-- test
