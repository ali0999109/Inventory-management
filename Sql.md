##The Inventory-management system has multiple SQL injection vulnerabilities 

## Affected version: 
Inventory-Management System - 1.0

## Software:
https://code-projects.org/inventory-management-in-php-with-source-code/

## Vulnerability File:
/Inventory-Management/model/viewProduct.php

## Description:

SQLmap has identified multiple SQL injection vulnerabilities in the `id` parameter of the inventory management system. By intercepting the request using Burp Suite and copying it to a file, you can swiftly analyze and pinpoint the SQL injection issues within the `id` parameter when selecting the "view products" option.

POC

### First click on the green "Actions" button & intercept the request with burpsuite
![image](https://github.com/user-attachments/assets/661277ec-105c-4076-9f41-b58ad7710d2c)

---------------------------------------------------------------------------------------------
### Copy the request to a file
![image](https://github.com/user-attachments/assets/9d82de33-ed08-494d-b025-a9bdb4541412)


--------------------------------------------------------------------------------------------
### Use SQLmap to find the SQL injections in the Id parameter

![image](https://github.com/user-attachments/assets/4e04e299-cba5-4efb-bfd4-63654b467c68)


