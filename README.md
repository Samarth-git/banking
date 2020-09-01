This is a simple Web Project which can perform CURD operations on database with the help of JDBC.
Frontend is created in HTML and CSS with JSP for dynanmic content of page and JavaScript for form validation.

1. Pull the code from repo.
2. Import project folder to workspace of IDE
3. ADD Jar files (mysql-connector-java-8.0.21.jar),(servlet-api.jar),(jsp-api-2.1.jar)
4. Create a table in MYSQL Database
   CREATE TABLE  "NEWACCOUNT" 
   (	"ACCOUNTNO" NUMBER, PRIMARY KEY, AUTO INCREMENT
	"USERNAME" VARCHAR2(4000), 
	"PASSWORD" VARCHAR2(4000), 
	"REPASSWORD" VARCHAR2(4000), 
	"AMOUNT" NUMBER, 
	"ADDRESS" VARCHAR2(4000), 
	"PHONE" NUMBER)
5. Create Apache Tomcat local server to run project.
