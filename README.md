# data-jpa-test-all
This project contains a set of DataJpaTest examples. All examples are based on the same prod code.

## Prod code
For all examples we have an entity ; Employee, a JPA repository ; EmployeeRepository and a service that use this repository ; EmployeeService.
This service have just one method that return the list of employee on the database.

## List of examples:
* A simple test with DataJpaTest.
* A test with DataJpaTest that use liquibase.
* A test with DataJpaTest that use the hibernate `create-drop` feature to create the test database.

## List of examples: 
In the futur I add:

* A test with DataJpaTest that use flyway (in progress).
* A test with DataJpaTest that use test container (on postgresql)
* A test with DataJpaTest that use Zonky.
