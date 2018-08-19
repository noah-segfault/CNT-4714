The folder should be kept in the same exact directory strcutre and placed inside the Tomcat webapps folder. I ran the webapp on Tomcat 9.0.

Objectives: To incorporate many of the techniques you’ve learned so far this semester into a distributed three-tier web-based application 
which uses servlets running on a Tomcat server to access and maintain a persistent MySQL database using JDBC.


Input Specification: The suppliers/part/jobs/shipments database that is created/populated by the script project4dbscript.sql, is the back-end to this application.
All other input comes from the front-end client submitted to the application server based servlet entered as either queries or updates to this database. 
The set of commands that you are to execute against this database are included in the project4commands.sql file available on the course homework page. 
I do not expect your front-end to execute the script. You’ll need to execute the commands in this script one at a time in your application (copy and paste!). 
I’ve put them into a script file for convenience and so that you can run the script in the MySQL Workbench if you’d like to compare/see the result sets for each user command.



Output Specification: All output is generated by the servlet and should appear in the user’s browser as a text/html page presented to the user.
IMPORTANT: Be sure to re-run the project4 database creation/population script before you begin creating your screen shots for submission. 
By doing so you will ensure that the database is in its initial state so that all update operations will produce the values we are expecting to see in your result outputs.