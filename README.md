# greeting-service

This project demonstrates how to create a very lightweight 
(and basic) microservice in Java by using the 
[Rapidoid library](https://www.rapidoid.org/).

## Requirements

* JDK 8 or higher
* Apache Maven

## Running It

Run the following from the root directory of this project:

```bash
$ mvn clean compile exec:java
```

This will start the service, making it accessible at port 9999.
You may then use an HTTP client, such as `curl`, to access it. 
The project currently contains a single endpoint, which expects 
a `name` parameter, so you would access it as follows:

```bash
$ http://localhost:9999/get-spanish-greeting?name=Tom
```

