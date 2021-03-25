# Spring Boot Security

This is a simple Spring Boot Kafka Demo.

## Installation

Once you have checked out this repository, go to the base directory and build it using maven

```bash
maven clean install
```

## Running the application

Once the project is successfully built, you can run the following command:

```bash
java -jar .\target\springboot-security-1.jar
```

Before running this application you need a MySQL server running, you can update the configuration details in the properties file.

Below URL open the Login page

```bash
http://localhost:8080/
```
You might have to add data into the database, you can use the following password for any user that you create.
Admin123 >>> $10$o.7lMeS1yADFpxDb.TZepei5QUTtozbS7AWM1ehUw.G7Ih1pKwJdK

Also add following role into roles table > [1, ADMIN]

Below URL is accessable to users with ADMIN role only.

```bash
http://localhost:8080/admin/home
```