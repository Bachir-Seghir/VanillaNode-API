# Vanilla Node.js API

This repository contains a simple Node.js API that is built entirely using vanilla Node.js without relying on any external frameworks. This allows for a lightweight and minimalistic approach to building server-side applications.

## Features

- **Lightweight**: The API is built using only the core modules provided by Node.js, keeping the codebase minimal and easy to understand.
- **HTTP Server**: The API creates an HTTP server that listens for incoming requests.
- **Routing**: The API handles different routes and HTTP methods, allowing for the implementation of various endpoints.
- **Request Handling**: Incoming requests are parsed and handled within the API using native Node.js functions.
- **JSON Responses**: The API responds with JSON data, making it easy to consume by clients.
- **Error Handling**: Basic error handling is implemented to handle any unforeseen issues and return appropriate error responses.

## Prerequisites

To run this API locally, ensure that you have the following installed:

- Node.js: [Official Installation Guide](https://nodejs.org)

## Getting Started

1. Clone this repository to your local machine using the following command:

   ```bash
   git clone https://github.com/your-username/VanillaNode-API.git
   ```

2. Navigate to the project directory:

   ```bash
   cd VanillaNode-API
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the server:

   ```bash
   npm start
   ```

5. The API should now be running locally at `http://localhost:5000`. You can test it using an API client such as [Postman](https://www.postman.com) or by making requests using tools like `curl` or your preferred browser.

## Usage

The API currently supports the following endpoints:

- `GET /products`: Retrieves a list of products.
- `POST /products`: Creates a new product.
- `GET /products/:id`: Retrieves a specific product by ID.
- `PUT /products/:id`: Updates a specific product by ID.
- `DELETE /products/:id`: Deletes a specific product by ID.

## Contributing

Contributions to this project are welcome. Feel free to open issues and submit pull requests to address any bugs, add new features, or improve the documentation.

1. Fork the repository.
2. Create your branch: `git checkout -b feature/my-feature`.
3. Commit your changes: `git commit -am 'Add new feature'`.
4. Push to the branch: `git push origin feature/my-feature`.
5. Open a pull request.


## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

This API was developed as a learning exercise and is inspired by the simplicity of vanilla Node.js development. Thank to the Node.js community for providing excellent documentation and resources.
