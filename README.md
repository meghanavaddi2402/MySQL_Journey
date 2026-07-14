DAY - 1

Full Stack Development
===================
Full Stack ----> Frontend + Backend

Frontend
-------------
Frontend is a visual and interactive layer of a website or application that the users directly see and interact with through webserver or mobile app

It is also called client side because it runs on user device(browser/mobile)

Responsibility of Frontend
----------------------------------
1. Display web pages and user interface(UI)
2. Accepts user input(forms, buttons, search boxes)
3. Validates user input before sending it to server
4. Calls backend API to fetch or send data
5. Displays the response received from backend
6. Provides animations and interactive effects
By prepare frontend layer we are using some technologies like HTML, CSS, js, Bootstrap


Backend
------------
Backend is server side part of application, user cannot see it directly , but it performs all the business logic, security, data processing, and database operations

It acts as the brain of application

Responsibility of Backend
----------------------------------
1. Process client requests
2 .Implement business logic
3. Connect with database
4. Performs crud operations
5. Encrypts passwords and authorize users
6. Generate reports
7. Returns response to the frontend
we have some languages to built backend like java, .net, php, c, ++

Application Programming Interface(API)
----------------------------------------------
API is set of rules and protocols that allows 2 different applications or systems to communicate and exchange data without exposing their internal implementation

Advantages of API's
------------------------
1. Enables communication between different systems
2. Promotes code reusability
3. Platform independent
4. Faster application development
5. Supports integration with 3rd party services
6. Improves scalability
7. Easy to maintain


Storage Areas
------------------
As part of applications we need to store data like customer info, billing info, call info....etc. To store this data we require some storage areas

There are 2 types of storage areas such as :-
1.Temporary Storage Areas
---------------------------------
This are memory areas where data will be stored temporally
Example :- All JVM memory areas (like heap, method, stackarea, pc, registers, native method stack). Once the JVM is shutdown all memory aea will be cleared automatically
2. Permanent Storage Areas
----------------------------------
It is also know as persistence storage areas, where data will be stored permanently
Example :- File system, Databases, Data warehouse....etc.

File Management System
---------------------------------
A file management system is a system where data is stored in files on the operating system, each application program must handle its own storage data. Reterival and updating file system can be provided by the local operating system.

File Systems are best suitable for less amount of information.

Example :- A library management storing books in separate text files like book.txt, members.txt....etc.

Limitations of File Management System
--------------------------------------------------
1. Data Redundancy - Same data stored in multiple files
2. Data Inconsistency - Updated in one file but not reflected in other
3. Poor Data Security - No proper access control
4. Difficult Data Retrieval - Searching requires custom progress
5. Integrity Issues - No constraints(Example :- roll number uniqueness)
6. Scalability Issues - Hard to manage as data grows

Database Management System(DBMS)
----------------------------------------------
A DBMS is a collection of programs that enables user to create, manage and manipulate database

Advantages
---------------
1. We can store huge amount of information in databases.
2. Query Language support is available for ever database and hence we perform database operations easily.
3. To access data in database compulsory username and password must be required hence data is secured.
4. inside database data will be stored in form of tables. While developing database schemas, database admin follows various normalization techniques and we can implement various constraints like unique key, primary key, foreign key....etc. which prevents data duplication, hence there is no chance of data inconsistency problems.

Limitations
---------------
1. Database cannot store huge amount of information(like terabytes)
2. Database can provide support for only structured data(tabular data or relational data) and cannot provide support for unstructured or semi-structured data(like photos, videos)

To overcome these problems we should go fro some advanced databases like data warehouse, big data.....etc.

