## Spring Boot Restful API 

It is a Spring Boot boilerplate for restful CRUD api. It uses Spring Boot database of h2 and 

JpaRepository. 

## How to test CRUD

1 C (Create):

at Postman, POST, url = http://localhost:8888/students

body:

{

"name": "John Smith",

"passportNumber": "s234567"

}


2 R (read):

at browser, open http://localhost:8888/students


3 U (Update):

at Postman, PUT, url = http://localhost:8888/students/1

body:

{

"name": "John Smith Updated",

"passportNumber": "u234567"

}


4 D (Delete):

at Postman, DELETE, url = http://localhost:8888/students/1
