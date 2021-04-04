Introduction

   In this project, our group has been given a database to analyze and enhance to include a rating system for restaurants and delivery drivers. Doing this will increase the safety of campuses and give the university a better understanding of who is entering the premises based on background checks, verified license numbers and ratings. To start off this project, we have divided each section up into manageable parts. The first is a Use Case diagram that helps represent the interactions between each user with the system like the driver and student with delivery, location and order. The second are Business Rules that specify the rules that must take place during these interactions with the drivers, students and faculty. Finally, an enhanced EERD diagram will be used to help specify the relationship between entities. This is useful when applying all the business rules that are defined for customers and various entities. All this put together will be useful for creating a fully functional rating system to improve deliveries and increase safety on campuses. 


**Business Rules**
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


**EERD**

The database design have 
![EERD Diagram](https://user-images.githubusercontent.com/79599152/113522836-cc845600-9571-11eb-81a2-747d0e67955e.png) 
