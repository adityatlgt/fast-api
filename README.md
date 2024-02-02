# fast-e-commerce
# About:
 It is an ecommerce app created using python(fast-api).


## Requirements:
Requirments are available in requirements.txt file

# Installation
#####   Install the requirements.
##### Start the app using:
    uvicorn main:app 

## API Endpoints
    /token (POST): Provides a bearer token for authentication.
    /user_data (POST): Provides user data.
    /users/ (GET): Retrieves a list of users.
    /business/{id} (PUT): Updates business data.
    /user_register/ (POST): Registers a new user.
    /uploadfile/profile (POST): Uploads a profile image.
    /uploadfile/product/{id} (POST): Uploads a product image.
    /products/ (POST): Adds a new product.
    /products/{id} (DELETE): Deletes a product.
    /products/{id} (PUT): Updates a product.
    /products (GET): Retrieves a list of products.
    /products/{id} (GET): Retrieves details of a specific product.
    Authentication

## Authentication used:
    Token Authentication
