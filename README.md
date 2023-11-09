
# Table of Contents
- [Project Title](#project-title)
- [Project Description](#project-description)
- [Featured](#featured)
- [Setup](#setup)
- [Project Status](#project-status)
- [Room for Improvement](#room-for-improvement)
- [Contact](#contact)
## Project Title 

- Online sales website  
- This project is my result after learning C# language and MVC model.
- It has many different management functions, and is also integrated with online payment functions.


## Project Description

- This project made by use knowledge of MVC, C#, HTML, CSS languages
- Use Visual Studio 2022
- Use Microsoft SQL Server Management Studio 2019
- Bootstrap v3.4.1
- Use CKFinder and CKEditor
- Use the management template here: https://github.com/ColorlibHQ/AdminLTE/releases/tag/v3.2.0
- Use user interface here: https://themewagon.com/themes/free-bootstrap-ecommerce-website-template-coloshop/


## Featured
- Category management
- Grant user permissions
- Account management
- Product Management
- Advertising management
- Order management
- News management
- Article management
- Pay online via VN Pay
## Setup
- Clone repository using the github link or you can download the zip file.
- After opening the project, delete all Migration files.
- Open file Web.config and in part ``` <connectionStrings>  <add name="DefaultConnection" connectionString="Data Source=DESKTOP-D1HSOQO\SQLEXPRESS;Initial Catalog=WebBanHangOnline01;Integrated Security=True; MultipleActiveResultSets=True" providerName="System.Data.SqlClient" /> </connectionStrings> ``` you need to change ```connectionString``` by your SQL server and ```Initial Catalog``` by the name you want.
- Open the Package Manager Console interface and type the command:```add-migration NewDatabase```.
- Continue typing the command line: ```update-Database Verbose```.
- If there are some errors, type more command lines: ```Update-Package EntityFramework -Version 6.4.4``` in Package Manager Console.
- Now the project is ready, let's rebuild and test it.
## Project Status
- Project is: in progress 
-  There is some things that I need to improve.
## Room for Improvement
- Build a customer profile page
- Add code to delete and edit accounts
- Add product review function
- Add product favorites function
## Contact
Created by @dangnghiemhong - Nice to meet you!
