# SPRING-BOOT-DAY 7 - eXERCISE

# Problem Statement

Develop a **RESTful Product Management API** using **Spring Boot and Maven**.

The application should manage product information with the following fields:

* Product ID
* Product Name
* Product Price
* Product Category
* Product Quantity

The REST API must provide the following operations:

1. Create a new product.
2. Retrieve all products.
3. Retrieve a product by ID.
4. Update an existing product.
5. Delete a product.

The application should follow a layered architecture using **Controller, Service, and Repository** components. Implement the REST endpoints using appropriate HTTP methods and return suitable HTTP status codes for successful and unsuccessful operations.

The completed API must be tested using **Postman** for all CRUD operations.

## Expected REST Endpoints

| HTTP Method | Endpoint             | Operation              |
| ----------- | -------------------- | ---------------------- |
| GET         | `/api/products`      | Retrieve all products  |
| GET         | `/api/products/{id}` | Retrieve product by ID |
| POST        | `/api/products`      | Create product         |
| PUT         | `/api/products/{id}` | Update product         |
| DELETE      | `/api/products/{id}` | Delete product         |

**Deliverable:** A working Spring Boot Product Management REST API with all the above endpoints implemented and tested successfully using Postman.
