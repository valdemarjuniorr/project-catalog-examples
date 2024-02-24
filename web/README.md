# Basic Spring Web Application

## Description

This project contains a web service that will accept `HTTP GET` requests at http://localhost:8080/products.
It will respond with a JSON representation of a products, as the following listing shows:

```json
{
  "id": 1,
  "description": "Product 1"
}
```

## Features
- Java 21
- Spring Boot 3.2.3

## How to start

Run the command:

```bash
$ make start
```
or with you want to use native images:

```bash
$ make start-native
```

## How to use
After starting the application, you can use the following command to test the application:

```bash
$ curl http://localhost:8080/products
```
