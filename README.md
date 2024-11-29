# Tasks Management API with Tags.

## Pre-Requisites

-       IntelliJ
-       Java JDK 21
-       Maven v3.4.0
-       PostgreSQL

## Setting up Database

Use the following links to install PostgreSQL Database Engine [PostgesSQL Installation](https://www.guru99.com/download-install-postgresql.html)

After successful installation Create database named <strong>tasks <strong>
for database creation steps use this link
[Database creation](https://www.tutorialsteacher.com/postgresql/create-database)

## Steps

1. Start IntelliJ and Click on File>New>Project from Version Control
   ![version contron](/images/selectfile.png)
2. Paste the following Repository URL:
   Click on Clone Project.
   ![clone](/images/clone.png)

3. Once the project has been successfully cloned, Navigate to the project folder.
   Right Click on pom.xml > Click Maven>Sync Project.
   ![sync project](/images/Syncpom.png)
4. Find application.properties file under the src folder>resources and add your postgreSQL DB_USERNAME & PASSWORD
   ![aplication properties](/images/editapplicationpropertise.png)
5. Open the TaskmanagementApplication.java and click run the project.
   ![run](/images/runtheproject.png)
   Once the project successfully run, go to http://localhost:8080/swagger-ui/index.html on your browser. You can now interact with the API endpoints as shown:
