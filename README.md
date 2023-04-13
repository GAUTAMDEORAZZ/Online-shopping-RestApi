# Online Shopping API
This is a RESTful API for an online shopping website built using Java Spring Boot, Spring MVC, and Spring Data JPA. It allows users to browse products, add them to their cart, place orders, and view their order history.

This project is a collaborative effort of five members, and contributions are welcome!

# Table of Contents
#### 1.Installation

#### 2.Usage

#### 3.Endpoints

#### 4.Contributing

#### 5.Credits

#### 6.License

#### 7.Installation

To install the Online Shopping API, follow these steps:

Clone the repository: git clone https://github.com/GAUTAMDEORAZZ/online-shopping-RestApi.git
Install dependencies: mvn clean install
Start the server: mvn spring-boot:run
Access the API at http://localhost:8080
# Usage
To use the Online Shopping API, you can make HTTP requests to its endpoints using a tool like cURL or Postman. See the Endpoints section for a list of available endpoints and their functions.

## Endpoints
Here are the available endpoints and their functions:
### `/signup`
1.POST /signup: Creates a new user account with the given details

### `/login`
1.POST /login: Authenticates the user and returns an access token for subsequent requests

### `/logout`
1.POST /logout: Logs out the user by invalidating their access token


### `/products`
1.GET /products: Returns a list of all products in the database

2.GET /products/{id}: Returns the product with the specified ID

3.POST /products: Adds a new product to the database

4.PUT /products/{id}: Updates the product with the specified ID

5.DELETE /products/{id}: Deletes the product with the specified ID

### `/cart`
1.GET /cart: Returns the contents of the user's cart

2.POST /cart/{productId}: Adds the product with the specified ID to the user's cart

3.DELETE /cart/{productId}: Removes the product with the specified ID from the user's cart

4.DELETE /cart: Clears the user's cart


### `/orders`
1.GET /orders: Returns a list of all orders for the current user

2.GET /orders/{id}: Returns the order with the specified ID

3.POST /orders: Places a new order for the current user

4.PUT /orders/{id}: Updates the order with the specified ID

5.DELETE /orders/{id}: Cancels the order with the specified ID


## Contributing
Contributions are welcome! To contribute to the Online Shopping API, follow these steps:

## Fork the repository
1.Create a new branch : git checkout -b my-feature

2.Make changes and commit them: git commit -am 'Add new feature'

3.Push to the branch: git push origin my-feature

4.Submit a pull request

Please make sure your code adheres to the Java Code Conventions.

## Credits
The Online Shopping API was created by a team of five members as a collaborative project.

## License
The Online Shopping API is licensed under the MIT License.
