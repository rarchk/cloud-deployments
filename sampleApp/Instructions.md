## Dependencies

1. Java 8
2. Maven 3.3+
3. MySQL 5.6+
4. Internet connection

	
## Run instructions

1. Configure the database connection data from Code/src/main/resources/application.properties
2. Go to the Code folder and run "mvn spring-boot:run".
3. Go to http://localhost:8080
4. (Optional) By default, the application stores the uploaded PDFs in <User_home>/upload directory. If you want to change this directory, you can use the -Dupload-dir=<path> system property.
5. (Optional) The PDFs for the predefined journals can be found in the PDFs folder. If you want to view the predefined journals, you should copy the contents of this folder to the upload folder defined in step 4.

	
## Authentication data
The system comes with 4 predefined user accounts. They are:
	
1. publishers:
	- username: publisher1 / password: publisher1
	- username: publisher2 / password: publisher2
2. public users:
	- username: user1 / password: user1
	- username: user2 / password: user2