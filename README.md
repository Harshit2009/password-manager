# password-manager
1.	Introduction
1.1	Purpose 
The purpose of this project is to create a web application that would store the username and passwords of people in an encrypted manner so that even the admin of the website may not be able to have a look into user’s passwords.
Feature of autofill of username and password will be implemented in later stages of this project.
1.2	Intended Audience and Reading Suggestions
This web application basically targets all those people who have multiple passwords for their different applications and who like to store those passwords in a safe environment.
1.3	Project Scope
The objective of this project is to create a web application which would help users to store their passwords in a safe and encrypted manner. It also aims to help to help users to ease and just remember a single password so that they can access all other of their passwords. 
Also it aims to help users to automatically fill out the username and passwords of users.
2.	Overall Description
2.1	Product Perspective
The main aim of this project is enhance the security of user’s username and passwords of different applications.
2.2	Product Features
The main features of this project are – 
a.	User login
b.	Password Saving
c.	Profile editing and deleting
d.	Passwords updating and deleting
2.3	User Classes and Characteristics
Generally, the users are classified in two categories – 
a.	Admin
b.	Users
Admin – Responsible for all the maintenance and security of all the passwords.
Users – Can use the application to store their various usernames and passwords. 
2.4	Operating Environment
Software Requirements – 

•	OS: Windows 7 and above
•	Python 3.7.1
•	Django 3.1.5
•	Mysql
2.5	Design and Implementation Constraints
Input design – 
a.	Input to front end of system is designed.
b.	User needs to use their username for logging in
Control design – 
a.	Registration is mandatory before logging in.
2.6	User Documentation
In this web application we have created a simple user interface so that user can easily interact with the web application.
2.7	Assumptions and Dependencies
There are many dependencies and assumptions associated with this web application. They are:
a.	Every user is expected to remember their master passwords.
3.	System Features
Password Management System is a system in which a login system is used to authenticate the user and provide them a secured platform to store their usernames and passwords. The system allows the user to store their usernames and passwords integrated with security. This project has a web based interface that will user use to store their usernames and passwords.
3.1	User Login
3.1.1	Description and Priority
A user is asked to log in before he van access his passwords and in case he is a new user he needs to register before logging in.
3.1.2	Functional Requirements
REQ-1: User must remember his password and username	
REQ-2: User’s password will be a master password for his access to all passwords.	
3.2	Profile Editing and Deletion
3.2.1	Description and Priority
A user can update and delete his account. He can change his current master password.
3.2.2	Functional Requirements
		REQ-1: User must do to this thing only in case when it is most necessary.
3.3	Password Addition
3.3.1	Description and Priority
A user can add their passwords of their different applications and store their username and passwords.

3.2.2	Functional Requirements
		REQ-1: User must give suitable links to their website whose password is to stored.
		REQ-2: User must give appropriate password hints. 
		REQ-3: User should remember his master password.
4.	External Interface Requirements
4.1	User Interfaces
The interface between user and the system include many provisions from where they can access the whole system. It has following features:

a.	User login
b.	Password Saving
c.	Profile editing and deleting
d.	Passwords updating and deleting
 
5.	Other Nonfunctional Requirements
5.1	Performance Requirements
The performance of the system lies in the way it is handled. Every user must be given proper guidance regarding how to use the system. The other factor which affects the performance is the absence of any of the suggested requirements.
5.2	Safety Requirements
To ensure the safety of the system, perform regular monitoring of the system so as to trace the proper working of the system. An administrator should be there to ensure the safety of the system. He has to be trained to handle extreme error cases.
5.3	Security Requirements
Any unauthorized user should be prevented from accessing the system.
5.4	Software Quality Attributes
a.	Planned approach towards working: - The working in the system will be well planned and organized.

b.	Accuracy: - The level of accuracy in the proposed system will be higher. All operation would be done


c.	Reliability: - The reliability of the proposed system will be high due to the above stated reasons. The reason for the increased reliability of the system is that now there would be proper storage of information.

d.	No Redundancy: - In the proposed system utmost care would be that no information is repeated anywhere, in storage or otherwise. This would assure economic use of storage space and consistency in the data stored
6.	Other Requirements
The registration of new users requires the following personal details:
•	First Name
•	Last Name
•	Email

