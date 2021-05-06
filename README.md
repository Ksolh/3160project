
# 3160 Project

## Group 10: Alazar Shimbir, Kareem Solh, Mihret Tadesse, Naomi Verma, Simreab Ketema


## Introduction

   In this project, our group has been given a database to analyze and enhance to include a rating system for restaurants and delivery drivers. Doing this will increase the safety of campuses and give the university a better understanding of who is entering the premises based on background checks, verified license numbers and ratings. To start off this project, we have divided each section up into manageable parts. The first is a Use Case diagram that helps represent the interactions between each user with the system like the driver and student with delivery, location and order. The second are Business Rules that specify the rules that must take place during these interactions with the drivers, students and faculty. Finally, an enhanced EERD diagram will be used to help specify the relationship between entities. This is useful when applying all the business rules that are defined for customers and various entities. All this put together will be useful for creating a fully functional rating system to improve deliveries and increase safety on campuses. 


## Use Case for Rating System

![use case](https://user-images.githubusercontent.com/77816981/113527200-be8eff00-958a-11eb-9638-a6b51c34f7c9.png)


## Business Rules
*	Customers (Students & faculty) will have an account using their name, email, phone number and can be assigned a username and password. 
    *   User must have a verified address with google maps, with optional drop off or food delivery locations. 
*	Driver must be verified with us, with a background check and must be students at the university. 
*	A delivery is tied to one person and can only be at one location (one restaurant) 
*	All deliveries will have a $5 fee tied to the total, with a tip that is added after the delivery. 
*	After deliveries rating are required by the user who ordered. 1-5 rating for the driver and a separate 1-5 rating for the restaurant. 
    *   All rating will be visible before any orders are taken
*	All restaurants must be approved and approached by the company before any deliveries can be taken. 
*	Credit and Debit cards are verified by the bank before any orders are taken. A small reservation fee is charged in case of cancellation. 
    *   Orders that are cancelled will not affect the ratings of drivers or restaurants.


## EERD
The database design have 11 tabels with diffrent entities. And each entity has its own attributes, and a relationship between them. The diagram below shows the fully norrmalized data.

![EERD Diagram](https://user-images.githubusercontent.com/79599152/113529940-d2d6fa00-9592-11eb-9262-9bf123e1538b.png)



## MySQL Queries
[SQL Dump File](https://github.com/Ksolh/3160project/blob/main/campus_eats_dump_file.sql)

## Stored Procedure
One stored procedure thats is going to be necessary for this project is adding a rating system to the database.

[Stored procedure for rating ](https://github.com/Ksolh/3160project/blob/main/Stored%20procedures/add_rating.sql)
Stored procedure named 'add_rating' calculates the rating of the driver.

![MySQLWorkbench_ti6vYNBI9y](https://user-images.githubusercontent.com/71343779/117223433-a4d81600-addb-11eb-891b-718442c13cd0.png)

This calls the stored procedure

![MySQLWorkbench_wyoch8ogEs](https://user-images.githubusercontent.com/71343779/117223480-c20ce480-addb-11eb-9d92-d1b1b2e6d2c8.png)


## Indexes and views
One view that we tried to create was where people can see the driver quality. This can be done by using multiple quieries to find the best rating and then output if the driver is good or bad and do the same thing for the resturant quality.

## MySQL dump


## Project Video
