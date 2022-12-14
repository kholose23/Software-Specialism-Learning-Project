# Software-Specialism-Learning-Project
Final Project Framework

This is a Restaurant Booking Project.  This project was implemented with using Java Spring Boot, that could be linked to a front-end to make an API to call restaurant booking database. It uses CRUD functionalities to keep information updated.  Project is split up into two parts, which is a Booking Table and Customer Table and they have OneToMany and relationship and visaversa.  These system is easy to use and reliable which in turn increase productivity and increases the turnover.  The README provides an overview and how it run on spring boot application.

Below id the table contents
**
Table One:
Customer's Id for Booking reference
Customer's name
Customer's email
Customer's password
Customer's username
Customer's name

Table Two:
Booking 's records by Id for Customers
Date
Time
Type of Booking (mechilin, prime time or Basic)
Customer's Id

Below is the ERD Diagram for the Database Tables

![Project table](https://user-images.githubusercontent.com/112514094/198720511-9af1cafc-b33f-4cfa-b031-76ecee2132ab.png)


Project Structure![Screenshot 2022-10-28 185058](https://user-images.githubusercontent.com/112514094/198723201-d693bfef-d167-4bc6-b56b-1bba8c31654c.png)
Below is the CRUD Functionalities

![postman output](https://user-images.githubusercontent.com/112514094/198723923-6847c272-e1c0-4c57-a3da-8e0fb1e8e531.png)
![postman output1](https://user-images.githubusercontent.com/112514094/198724312-ed573d48-2c60-44fd-bffd-1c98c43197a1.png)

Below are the images from MYSQL Database

Bel![customer table](https://user-images.githubusercontent.com/112514094/198724863-3c72bacb-0544-4ff4-ad80-666d9e2403ed.png)

![Booking table](https://user-images.githubusercontent.com/112514094/198724825-763b27ae-8275-4279-960f-4d788426d186.png)
Executing on Spring Boot:
Since this is a Spring Boot application it uses a TomCat server.
The port number used is 8080, so make sure that port remains free.
Once you have opened the project, you can right click and there two was to run it:
Run as Java Application
Run as Spring Boot App
After this you can run the CRUD operations using something like Postman as shown above.


