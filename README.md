# Spring Boot CRUD using MongoDB
Demo project for Spring Boot with MongoDB

# Verify CRUD Operations
Use a tool like Postman to test the endpoints.

## Create a Product:

- URL: http://localhost:8080/products
- Method: POST
- Body:

```json
{
  "name": "Product 1",
  "description": "Description for product 1",
  "price": 100.0
}
```

## Get All Products:

- URL: http://localhost:8080/products
- Method: GET

## Get a Product by ID:

URL: http://localhost:8080/products/{id}
Method: GET

## Update a Product:
- URL: http://localhost:8080/products/{id}
- Method: PUT
- Body:
 ```json
{
  "name": "Updated Product",
  "description": "Updated description",
  "price": 150.0
}
```

## Delete a Product:
- URL: http://localhost:8080/products/{id}
- Method: DELETE

You should see the correct responses and verify that the data is stored, retrieved, updated, and deleted from MongoDB.
