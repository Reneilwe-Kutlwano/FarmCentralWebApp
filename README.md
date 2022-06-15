# FarmCentralWebApp
#### ============TABLE OF CONTENTS===============

1. Feedback and implementation from task 1
2. Overview.
3. Features of the project.
4. Development dependencies.
5. Technology + software required.
6. Running of the project.
7. Contributors and sources.

#### =================FEEDBACK AND IMPLEMENTATION FROM TASK 1========================
In task 1 according to the feedback I had recieved there was a bit of an issue with regards the referencing for the document as well as thorough definition and clarity of certain design and architecture patterns based on the application to be developed. In order to not repeat the same mistakes again, I made sure to reference every block of code using code attribution, to clearly demonstrate where the code is coming from and how I have adapted the code according to my projects needs. For this particular project I have decided to implement a an ASP.NET Framework which is a family of MVC so that I can create the static user pages and link them to other non-static pages for the application.

#### =================OVERVIEW===================
This is an interactive farmer products application in which the employees have access to specific pages that they are allowed to control and the users have their own specific pages that they are allowed to control. This means that this application consists of a multi-user login page as well as add, update and delete functions for certain pages. This application provides a seamless way in which farmers can manage the products that they are supplying to the brick-and-mortar store. Farmers are able to update their passwords once they have been provided login details by the employees for security purposes, the farmers are then able to add products that they are selling as well as update and delete products that they may not want to sell, all loaded on their login session. The employees are able to add, delete and update farmers that wish to be a part of this store as well as view the products that each farmer sells by filtering through the grid view displayed. 

All of the information will get store internally through an SQL database.
The motivation behind this application is to try an create a seamless way in order for employees and farmers can manage their own details. Often at times users are restricted to manage their own data, so to create an application that can allow user to have such options is definitely worthwhile.

#### ============FEATURES OF THE PROJECT==============
This project includes the following:

1. A static home page with footers that load certain menu items depending on the type of user logged in (admin/ user).
2. An employee login page linked to the database.
3. A farmer login page linked to the database.
4. A farmer management page where the employee can add, update and delete farmers into the database.
5. A products supplied page that illustrates all of the products supplied by each farmer that can be filtered by type of product, product ID and farmer username.
6. A farmers profile page in which the farmers will be able to update their passwords once they have been supplied login details. (The passwords are being hashed and then stored into the database after hashing).
7. A farmers products page where the farmers can add, update and delete products from their profile. (Farmers are able to add images to their profile which are stored as image links in the databse)
8. User data validation through try-catch and if-else statements
9. Bootstrap, Css, JavaScript, fontawesome and datatables libraries were added to the project.
10. SQL database added through a connection string to the project.

#### ============DEVELOPMENT DEPENDENCIES=============
1. Microsoft.NETCore.App
2. ADO.NET connected layer.
3. Visual studio 2019/2022.
4. Visual studio ASP.NET Framework
5. SQL server management studio 2019.

#### ===========TECHNOLOGY + SOFTWARE REQUIRED==========
1. A laptop that supports windows10 and microsoft with atleast 4GB of RAM space.
2. Not supported on: 
   Linux 
   MS-DOS (IBM PC DOS) 
   Windows 3.1 
   Windows NT 3.51 
   Windows 9x 
   Windows NT 4.0.
3. Microsoft visual studio 2019 version 16.9.4./ Microsoft visual studio 2022 version 17.2.
4. Microsoft.NET framework version 4.8.04084..
5. ASP.NET Framework.
6. SQL server management studio 2019.

#### ============RUNNING OF THE PROJECT===================
1. Download the zipped folder(FarmCentral_ST10122290.zip)
2. In the file explorer unzip the zipped file by extracting it.
3. Open the unzipped file.
4. Click the FarmCentral_ST10122290 file to open it.
5. Open the folder that says FarmCentral_ST10122290.Sln.
6. Visual studio 2019/ 2022 will open now.
7. Once the project is open in visual studio go to server explorer on the left hand side, under data connections click on the data connection called     farmCentralDBConnectionString (FarmCentral_ST10122290) to open the connection. There should be a green plug next to the connection to illustrate it is connected.
8. Go to the homePage.aspx and click the green button called start on the visual studio toolbar to run the program. (PLEASE NOTE THAT THE HOME MASTER PAGE IS A STATIC PAGE THAT LINKS ALL OF THE OTHER PAGES, THIS PAGE WILL NOT RUN ALONE WHEN PRESSED)
9. The application will now start in your web broswer which should be set to IIS Express (GoogleChrome).
10. In the homePage.aspx you should see a home page with top menu bars and a green footer wil nothing on the top footer (THIS INDICATES NO ONE IS LOGGED IN).
11. Click on the Farmer Login on the menu bar. (YOU SHOULD BE REDIRECTED TO A FARMER LOGIN PAGE). Enter the dummy data provided.
12. Once logged in you will be redirected to the homePage.aspx again, this time the menu bar at the top will display a logout and the footer will display Farmer Profile and Farmer Products.
13. Click on the Farmer Profile. (YOU SHOULD BE REDIRECTED TO THE FARMER PROFILE PAGE). Enter the dummy data and click the green tick to populate user information.
14. By the new password box type in a new password and click update.
15. Your passoword is now updated. (YOU MAY THEN LOG OUT AND LOGIN WITH YOUR NEW PASSWORD)
16. Once logged in with the new password press the Farmer Products link on the bottom footer. (YOU SHOULD BE REDIRECTED TO THE FARMER PRODUCTS PAGE).
17. In the farmer products page. Enter the dummy data and click either add, update or delete. (IF THE USER HAS NO PRODUCTS IN THE DATABASE THE DATA GRIVIEW WILL BE EMPTY)
18. Logout from the farmer profile and log into the employee profile (DATA FOR THIS PROFILE IS PROVIDED).
19. Click the Farmer management link on the bottom footer. (YOU SHOULD BE REDIRECTED TO THE FARMER MANAGEMENT PAGE).
20. Enter the dummy data and click add, update or delete. (BASED ON THE BUTTON YOU HAVE CLICKED NEW DATA WILL DISPLAY ON THE GIRDVIEW).
21. Click the Products supplied link on the bottom footer. (YOU SHOULD BE REDIRECTED TO THE PRODUCTS SUPPLIED PAGE).
22. In this page you should be able to see all the products added to the database and also be able to filter through them by searching in the search bar on the gridview.

#### =============CONTRIBUTORS + SOURCES===================
1. Reneilwe-Kutlwano Motlhabi.
2. Troelsen, A. and Japikse, P. 2017. Pro C# 7 with .NET and .NET Core. 8th ed. Minnesota and Ohio: Andrew and Philip.

3. Sakpal, T. 2020. User profile module of E-library Management website in ASP.NET with C# programming and MS Sql Database. SimpleSnippets, 18 February 2022. [Online]. Available at :https://simplesnippets.tech/user-profile-module-of-e-library-management-website-in-asp-net-with-c-programming-ms-sql-database/ [Accessed 15 June 2022].

4. Sakpal, T. 2020. Dynamic web application development using ASP.NET wil C# programming - Online library management system. SimpleSnippets, 11 July 2020. [Online]. Available at: https://www.youtube.com/watch?v=8_eMgS6UszY&list=PLIY8eNdw5tW_ZQawyxK0Dd1cZXwcNFWn8 [Accessed 15 June 2022].

5. https://getbootstrap.com/docs/4.3/components/buttons/ BOOTSTRAP.COM https://getbootstrap.com/
6. https://getbootstrap.com/docs/4.3/content/tables/ BOOTSTRAP.COM https://getbootstrap.com/
7. https://datatables.net/ datatables.net
