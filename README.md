# Paint-WebApplication

- Designed a Drawing and Painting web-based application using OOP concepts and Design Patterns. 
- Implemented the following functionalities for the user on all the shapes : 
  - Draw, Color ,Resize, Move, Copy and Delete using web canvas API.
  - Undo or Redo any action performed. Save the drawings in JSON formats and import them later.

- Back-end with java spring-boot. 

- Front-end with Vue.js and canvas.

- Objective : Applying principles of oop and design patterns.
- We are team of 4.


## Class Diagram



![image](https://user-images.githubusercontent.com/61321123/168187229-3aac24f5-4650-42eb-8ac8-62862667332b.png)





## How we have applied the required design patterns

 1. We used Shape Factory design pattern: Service Class is the shape factory for shapes to generate shapes and to make any operation on shapes(delete, copy…).

 2. We used singleton design pattern: to do only one object of service class .

 3. We wanted to use prototype design pattern on shapes to make copy of them.

But that causes a problem in frontend; it makes (flicker problem).

So, we made a copy of our shapes in the frontend to be more efficient for the user.


## Screenshots of the Web Application

![image](https://user-images.githubusercontent.com/61321123/168187941-ac5a338c-8126-40ab-8d0f-46df7e8a22df.png)

![image](https://user-images.githubusercontent.com/61321123/168187964-b174dee5-4230-4e86-a365-fe74b36bc405.png)



## The steps required to run the application :-

1. Install Vuetify.

2. Install Axios.

3. Run Back-end first so it runs on port 8080

4. Then Run Front-end so it runs on port 8081

*for more information about the program -like the UML, how we have applied design patterns and Snapshots of the program- you can check the pdf file "Web Based Drawing Program".*
https://github.com/MohamedIbrahim99/Paint-WebApplication/blob/main/Web%20Based%20Drawing%20Program.pdf
