Description:
This project is used to add students' data using a csv file.
It uses:
1) Spring MVC
2) JDBC
3) Maven
4) Commons-fileupload
5) PostgreSQL DB


Steps:
1. import project
2. change java runtime and server runtime
2. update project (download maven dependencies)
3. change upload directory in AddUserServiceImpl.java and AddUserDaoImpl.java
4. change database details in AddUserDaoImpl.java
5. Encoding type of csv file has to be changed to Utf-8  before uploading
	to do that:
   open csv file in notepad and save as--> change encoding type from ansi to UTF-8

Problems:

1) have to change encoding format b4 every upload

