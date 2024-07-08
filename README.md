# Airline-Management-System
## Abstract
Airline Management System (AMS) plays a crucial role in efficiently managing various aspects of airline operations, including reservations, ticketing, scheduling, fleet management, passenger services, and financial transactions. Previously the whole thing was done manually using file systems only at some gas stations and airports, But now a days we can book tickets and to record any details regarding to airlines we uses data bases. Our project is aimed at exposing the relevance and importance of Airline Reservation Systems. With this project, we aim to demonstrate the Create, Read, Update and Delete operations using MySQL database. This project shows the effectiveness of databases as the data loss is so less in them and the main advantage of this is if anything has been rescheduled then the data is automatically updates in the database by which the information is more transparent to every one and there will no miss communication. This abstract presents an overview of an effective database management system (DBMS) implementation for an airline management system.

## Keywords 
Airline, Entities, Attributes, Relationship, Flight Scheduling, Ticket System

## Introduction
Airline Reservation System aims to automate an Airline company's flight operations and ticketing/seat booking and confirmation system. The software is providing options for viewing different flights available within a different timing for a specific day. That provide customers within facility to able to book ticket smoothly. The customers can modify and able to cancel the ticket for any reason. That prepare within a role and policies. The software should provide option for checking availability of the tickets and it will help customers to get message if the ticket unavailable. That will be displayed into customers. The customers should be noted when the change has been made or any further change and also it improves the efficiency by automating repetitive tasks, reducing manual errors. These systems provide real-time access to critical information, enable online reservations and ticketing, facilitate efficient scheduling and resource allocation, and support seamless communication between various stakeholders, including passengers, airline staff, and ground handling agencies. The benefits of implementing an airline management system are manifold. It enables airlines to manage their fleet effectively, ensuring that aircraft are deployed efficiently, maintenance schedules are adhered to, and crew assignments are streamlined. Key performance indicators, financial metrics, and operational data can be derived from the system, empowering management to make informed decisions, identify trends, and formulate strategies for business growth and sustainability

## TABLE ENTRIES:
### LOGIN TABLE:

The login relation contains the fields like login id, role id, user name, password and the table were created and structure will be displayed.

### USER TABLE

The user relation contains the fields like user id, name, mobile, email, address and the table were created and structure will be displayed.

### ROLES TABLE:

The user relation contains the fields like role id, name, description and the table were structure will be displayed.

Relationship between the user table login table and roles table:

In the airline management system each user have roles which role they are playing and have login credentials for the users like id, user name and password.

### PASSENGER TABLE:
The passenger table contains the fields like id, mobile number, name, address, password and the table were created and structure will be displayed.

### AIRLINES BOOKING TABLE:

This table contains the information about passenger booking details at which date they are planning their journey. In this ab_id is the primary key and ab pass_id is the foreign key.

### Ticket table:

The ticket table contains the fields like id, description, date and the table were created and structure will be displayed.

Relationship between Airlines Booking and ticket:
Table entries:
Airlines Booking table:

This table contains the information about passenger booking details at which date they are planning their journey. In this ab_id is the primary key and ab pass_id is the foreign key.

##Conclusion
This DBMS project provides us a structured and organized approach to store, manage, and retrieve large volumes of data related to airlines operations, such as flights, passengers, bookings, and reservations. By using data bases we can reduce the loss as if any ticket or schedule was cancelled then it will immediately updates so the ticket can be sold again and we can reschedule another flight if any schedule changes. In future, These data bases are very useful in so many aspects such as data integrity by enforcing data constraints, such as referential integrity and data type validation, which helps to maintain consistent and accurate information. It also provides efficient data retrieval capabilities. By employing appropriate indexing techniques and query optimization strategies, the system can retrieve specific information quickly, even from large databases. It also provides many more futures such as data centralization, Scalability, Flexibility and most importantly security. So we can conclude that by using the databases the work is done simply and effectively.
