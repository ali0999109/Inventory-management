##The Inventory-management system has a Cross-Site Scripting vulnerability

## Affected version: 
Inventory-Management System - 1.0

## Software:
https://code-projects.org/inventory-management-in-php-with-source-code/

## Vulnerability File:
/Inventory-Management/view/registration.php

## Description:
Submitting a simple <script>alert(3)</script> xss payload in the your name section leads to a reflected xss vulnerability after logging into the account and also when clicking on Myinventory,Products & users..

POC


![image](https://github.com/user-attachments/assets/72863d23-e321-4b5f-a4b3-3db517808962)


-------------------------------------------------------------------------------------



![image](https://github.com/user-attachments/assets/c07cfb1b-0093-48d0-b8e3-199cde166de2)


-----------------------------------------------------------------------------------------

![image](https://github.com/user-attachments/assets/f37a1d51-1ed2-46f8-9830-c9c3267715e0)



-----------------------------------------------------------------------------------------

![image](https://github.com/user-attachments/assets/e7167b93-a104-4627-9132-509087eb5250)



------------------------------------------------------------------------------------------

![image](https://github.com/user-attachments/assets/9f2f94c9-ca48-4898-b3a9-55c97426a04d)



