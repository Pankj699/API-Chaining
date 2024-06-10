# API CRUD Validation

This repository contains Postman scripts for validating CRUD operations (Create, Read, Update, Delete) on a sample API provided by [Reqres](https://reqres.in/). The scripts are written using Postman, a popular API testing tool.

## Requirements

To use these scripts, you'll need:

- [Postman](https://www.postman.com/) installed on your machine.
- Basic knowledge of how to import and run Postman collections.

## Getting Started

1. Clone this repository to your local machine or download the ZIP file.
2. Import the Postman collection (`API_CRUD_Validation.postman_collection.json`) into your Postman application.
3. Run the collection to execute the API CRUD validation tests.

## Collection Structure

The collection contains four requests corresponding to CRUD operations:

1. **POST Request**: Create a new user.
2. **GET Request**: Retrieve user details by ID.
3. **PUT Request**: Update user details by ID.
4. **DELETE Request**: Delete a user by ID.

Each request includes pre-request scripts, test scripts, and request bodies where necessary. The tests validate various aspects of the API responses, including status codes, response times, response body contents, and more.

## Running the Tests

1. Open Postman and navigate to the imported collection.
2. Click on the collection and then click on the "Run" button.
3. Review the test results in the Postman interface.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.
