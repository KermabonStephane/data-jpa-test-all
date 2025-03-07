# data-jpa-test-all
This project contains a set of DataJpaTest examples. All examples are based on the same prod code.

<!-- TOC -->
* [data-jpa-test-all](#data-jpa-test-all)
  * [Prod code](#prod-code)
  * [List of examples](#list-of-examples)
    * [Simple example](#simple-example)
    * [Auto-create example](#auto-create-example)
    * [Liquibase example](#liquibase-example)
    * [Flyway example](#flyway-example)
    * [Zonky example](#zonky-example)
  * [List of future examples](#list-of-future-examples)
<!-- TOC -->

## Prod code
For all examples we have an entity ; `Employee`, a JPA repository ; `EmployeeRepository` and a service that use this repository ; `EmployeeService`.
This service have just one method that return the list of employee on the database.

## List of examples
* A simple test with DataJpaTest.
* A test with DataJpaTest that use liquibase.
* A test with DataJpaTest that use the hibernate `create-drop` feature to create the test database.
* A test with DataJpaTest that use flyway.
* A test with DataJpaTest that use Zonky (on postgres database).

### Simple example
This example is the simplest one, it use the default configuration of DataJpaTest.

### Auto-create example
This example use the hibernate `create-drop` feature to create the test database.

### Liquibase example
This example use the liquibase feature to create the test database.

### Flyway example
This example use the flyway feature to create the test database.

### Zonky example
This example use the Zonky feature to create the test database.

## List of future examples
In the future I add:

* A test with DataJpaTest that use test container (on postgresql)
* A test with hql query

