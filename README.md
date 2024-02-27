# project-catalog-examples

## Description

This repository contains examples of project catalogs for the Spring CLI.

## Features

- Java 21
- Spring Boot 3.2.2
- Spring CLI

## How to use

To use those templates is necessary to register the `project-catalog.yml` to the Sprint CLI project-catalog.
To do this, run the following command:

```bash
$ spring project-catalog add examples https://github.com/valdemarjuniorr/project-catalog-examples
```
It will add a project catalog named `examples` to the Spring CLI project-catalog list. To check if the project catalog `examples` was added, run the following command:

```bash
$ spring project-catalog list
```
You will see the following output:

```
┌────────┬───────────┬───────────────────────────────────────────────────────────┬────┐
│Name    │Description│URL                                                        │Tags│
├────────┼───────────┼───────────────────────────────────────────────────────────┼────┤
│examples│           │https://github.com/valdemarjuniorr/project-catalog-examples│[]  │
└────────┴───────────┴───────────────────────────────────────────────────────────┴────┘
```

### Create a new project
After adding those project templates, you will be able to create a new project. To do this, run the following command, for example to use `web` template:

```bash
spring boot new <PROJECT_NAME> web
```

## References
[Spring CLI example](https://github.com/valdemarjuniorr/springboot3-examples/tree/main/spring-cli-example)
