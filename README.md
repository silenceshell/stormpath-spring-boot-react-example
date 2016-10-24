# React App with Spring Boot

This is the code developed in the tutorial on creating a React App using Spring Boot.

### Requirements

- Maven
- JDK 7

### Configuration

First you need to edit `application.properties` and put in your Stormpath application keys.

Also to enable deletion you need to either delete the `void delete()` method in `EmployeeRepository.java`
or replace 'ROLE_ADMIN' with the URL of the Stormpath Group you are using to authorize.

### Running

To build and start the server simply type

```sh
$ mvn spring-boot:run
```

from the root directory.

### Using

Browse to `localhost:8080` to see the application in action.

The database is in memeory so rebooting should reset the data.

### License
----

MIT
