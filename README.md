# Photo
Marie's Photography Website

This website is an ongoing personal project to use my coding to promote my hobby as a photographer.  
The files require a working web application server and I have directions below to setup my xampp server if necessary.
The contact page (contact.php) is the most interesting page and includes a form that submits user information
to a submit page (contactSubmit.php) and inserts the data into a sql table.  A temporary link is at the bottom of the
Submit page to see previous entries made by users.  Please enjoy this website and I thank you for your time and interest.

***

If you have a working web application server and a SQL database, you can use the PhotographySite/PhotographySiteDump.sql 
to setup the necessary database for the contact page to work properly.  From there, you can tour the site beginning
with the index page.

***

If you do not have a working web application server, I have provided my xampp server to quickly install.  
Please use these steps:

1. Run the setup_xampp.bat to initialize the setup for the apache server.
2. Ensure nothing is using port 80 on your machine.  
   Common culprits are skype and the World Wide Web Publishing Service
3. Run the xampp-control.exe and click start for the Apache and MySql servers.
   If you get an error message, ensure that steps 1 and 2 have been executed.
4. If you do not receive any error messages, you are good to go!
5. In a browser, go to localhost/PhotographySite, you should be automatically directed to the index.php
6. Enjoy my website!
