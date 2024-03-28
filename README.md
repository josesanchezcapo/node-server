# Simple Node.js HTTP Server

This is a simple Node.js HTTP server that responds with "Hello World!" to incoming requests.

**Note:** This code is an example taken from [nodejs.org](https://nodejs.org/).

## Installation

1. Clone the repository or download the source code.

2. Install Node.js if you haven't already. You can download it from [here](https://nodejs.org/).

3. Navigate to the project directory in your terminal.

4. Install dependencies by running the following command:

    ```
    npm install
    ```

## Usage

To start the server, run the following command in your terminal:


Once the server is running, open a web browser and navigate to `http://localhost:3000`. You should see a "Hello World!" message displayed in plain text.

## Code Explanation

The `server.js` file contains the code for the HTTP server. Here's a breakdown of the code:

- Importing necessary modules:
  - The `createServer` function is imported from the Node.js `http` module.

- Creating an HTTP server:
  - An HTTP server is created using the `createServer` function. 
  - The server responds to incoming requests with a "Hello World!" message.

- Starting the server:
  - The server is started and made to listen on port 3000 of the localhost (`127.0.0.1`).
  - A message is logged to the console indicating that the server is listening.

