## **Proposal for Software Engineering**

# Car Park Management System

Professor: Mohammad Reza Ghaeli

Group 5

Winter 2021

**Project Name**

Car Park Management System

**Group 5 Members**

- Jacky Lam
- Soheila Hosseini
- Golazin Abolfathi
- York Bosco Li

**Project Scope:**

The &quot;Car Parking Management System&quot; is a program used to manage parking lots, provide users with virtual tickets and allow easy oversight by management. The hope with this project is for clients to minimize staff onsite while allowing the administrators to ensure maximum profits from their sites. For the target audience we will be marketing this software towards parking lot management companies.

The importance of our project is in organizing and managing the cars and parking lots. Number of cars around the world are increasing continuously; however, the number of parking lots are limited. Due to this, car owners or drivers are not able to find the perfect parking lot.

**Software Toolset:**

The project is written in Javausing IntelliJ IDE. Mongodb is used for creating the database.

**Business Scenario**

Consider a big company that owns several car park lots. We will create a database for management and ticketing of these car parking lots. The application contains a main page, payment page and an administration page. In the main page, users can choose to enter a new parking session, extend a current stay, or access the administration page.

In the &quot;new parking&quot; page the user may enter the parking space, enter the vehicle&#39;s license plate, choose the duration of stay and proceed to pay.

In the &quot;extend&quot; page users may enter their current Stall Number and select the amount of time they wish to extend their stay by and proceed to pay. The payment is done on the payment page.

In the administration page, the admin can check the parking space, the number of empty slots and occupied spaces.

**Database Requirements**

There are two tables in the database, parking lots table and transaction table.

Parking Lot Table contains column: Stall Number(Key), License Plate, Arrival Time, Exit Time, Status

Transaction Table: TransactionTableId(Key), Date, tickets sold, amount earned, fines given, total earned.
