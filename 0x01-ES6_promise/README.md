# 0x01-ES6_promise

Welcome to the **0x01-ES6_promise** directory! This repository is dedicated to mastering Promises in JavaScript using ES6 (ECMAScript 2015) features. Promises are a fundamental part of asynchronous programming in JavaScript, enabling more readable and manageable code when dealing with asynchronous operations such as API calls, file I/O, and more.

---

## Table of Contents
- [Overview](#overview)
- [Directory Structure](#directory-structure)
- [File Descriptions](#file-descriptions)
- [General Requirements](#general-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

This directory contains a series of JavaScript exercises and examples focused on Promises and asynchronous programming in ES6. Each file addresses a specific aspect or use case of Promises, helping you build a comprehensive understanding of how to implement and manage asynchronous operations effectively.

---

## Directory Structure

```plaintext
0x01-ES6_promise/
├── .eslintrc.cjs
├── 0-promise.js
├── 1-promise.js
├── 2-then.js
├── 3-all.js
├── 4-user-promise.js
├── 5-photo-reject.js
├── 6-final-user.js
├── 7-load_balancer.js
├── 8-try.js
├── 9-try.js
├── 100-await.js
├── utils.js
├── tests/
│   ├── 0-promise.test.js
│   ├── 1-promise.test.js
│   ├── 2-then.test.js
│   ├── 3-all.test.js
│   ├── 4-user-promise.test.js
│   ├── 5-photo-reject.test.js
│   ├── 6-final-user.test.js
│   ├── 7-load_balancer.test.js
│   ├── 8-try.test.js
│   ├── 9-try.test.js
│   ├── 100-await.test.js
│   └── utils.test.js
└── README.md
```

---

## File Descriptions

### Configuration
- **.eslintrc.cjs**: ESLint configuration file in CommonJS format. It enforces coding standards and best practices for JavaScript ES6 code, ensuring consistency and quality throughout the project.

### ES6 Promise Files
1. **0-promise.js**
   - **Description**: Introduction to Promises. This file demonstrates the basic structure of a Promise, including how to create a new Promise and handle its resolution and rejection.
   - **Key Concepts**: Promise constructor, `resolve`, `reject`.

2. **1-promise.js**
   - **Description**: Creating and chaining Promises. This example shows how to chain multiple `.then()` handlers to perform sequential asynchronous operations.
   - **Key Concepts**: Promise chaining, asynchronous flow control.

3. **2-then.js**
   - **Description**: Advanced usage of `.then()`. This file explores how to handle returned values and errors within `.then()` methods.
   - **Key Concepts**: Return values in `.then()`, error propagation.

4. **3-all.js**
   - **Description**: Using `Promise.all` to handle multiple Promises concurrently. This example illustrates how to wait for all Promises to resolve before proceeding.
   - **Key Concepts**: `Promise.all`, concurrent execution.

5. **4-user-promise.js**
   - **Description**: Fetching user data with Promises. This file contains a function that returns a Promise to simulate fetching user information from an API.
   - **Key Concepts**: Simulating API calls, handling asynchronous data.

6. **5-photo-reject.js**
   - **Description**: Handling Promise rejections. This example demonstrates how to properly reject a Promise and handle the rejection using `.catch()`.
   - **Key Concepts**: Promise rejection, error handling.

7. **6-final-user.js**
   - **Description**: Finalizing user data retrieval. This file builds upon previous examples to fetch and process user data, ensuring all Promises are resolved before finalizing.
   - **Key Concepts**: Chained Promises, data processing.

8. **7-load_balancer.js**
   - **Description**: Implementing a simple load balancer with Promises. This example shows how to distribute requests across multiple servers using Promises to manage asynchronous operations.
   - **Key Concepts**: Load balancing, asynchronous request handling.

9. **8-try.js**
   - **Description**: Attempting asynchronous operations with retry logic. This file demonstrates how to implement retry mechanisms using Promises.
   - **Key Concepts**: Retry logic, robust asynchronous operations.

10. **9-try.js**
    - **Description**: Further exploration of retry mechanisms. This example enhances the retry logic to handle more complex scenarios and edge cases.
    - **Key Concepts**: Enhanced retry strategies, edge case handling.

11. **100-await.js**
    - **Description**: Introduction to `async/await`. This file converts Promises into `async` functions using the `await` keyword for cleaner and more readable asynchronous code.
    - **Key Concepts**: `async/await` syntax, converting Promises to async functions.

12. **utils.js**
    - **Description**: Utility functions for Promises. This file contains helper functions that support the main Promise examples, such as simulating delays and generating random outcomes.
    - **Key Concepts**: Helper functions, utility methods for Promises.

### Tests
- **tests/**: Contains unit tests for each JavaScript file using a testing framework like `Jest` or `Mocha`. Each test file is named corresponding to its source file (e.g., `0-promise.test.js` for `0-promise.js`) and ensures that all functions behave as expected, including handling of edge cases and error conditions.

---

## General Requirements

- **JavaScript Version**: ES6 (ECMAScript 2015)
- **Coding Style**: Adheres to JavaScript best practices enforced by `.eslintrc.cjs`.
- **Testing Framework**: Uses `Jest` for writing and running unit tests.
- **Dependencies**: Managed via `npm`. Ensure all dependencies are installed before running the scripts or tests.

---

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your_username/0x01-ES6_promise.git
   cd 0x01-ES6_promise
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

   This will install all necessary packages, including the testing framework and any other dependencies specified in `package.json`.

---

## Usage

Each JavaScript file contains functions or examples that demonstrate specific Promise-related concepts. You can run these scripts directly using Node.js or integrate them into your own projects.

### Running a Script

Navigate to the desired file's directory and execute it with Node.js. For example:

```bash
node 0-promise.js
```

This will run the `0-promise.js` script and display its output in the console.

### Example

To see how `4-user-promise.js` works:

```bash
node 4-user-promise.js
```

This will simulate fetching user data and display the result or handle any errors accordingly.

---

## Testing

The `tests/` directory contains comprehensive unit tests for each JavaScript file. Running these tests ensures that all functions behave as expected and helps catch any regressions or bugs.

### Running Tests

1. **Ensure Dependencies are Installed**
   Make sure you have installed all dependencies as described in the [Installation](#installation) section.

2. **Execute Tests**
   ```bash
   npm test
   ```

   This command will run all tests in the `tests/` directory using the configured testing framework. You should see output indicating the number of tests passed or failed.

### Writing Tests

Each test file corresponds to a source file and follows a consistent naming convention (e.g., `0-promise.test.js` for `0-promise.js`). Tests are written to cover:

- **Functionality**: Ensuring functions perform as intended.
- **Edge Cases**: Handling unexpected or extreme inputs gracefully.
- **Error Handling**: Properly rejecting Promises and handling errors.

Feel free to add more tests as you enhance or modify the existing scripts.

---

## Contributing

Contributions to this directory are highly encouraged! Whether you're adding new Promise examples, improving existing ones, or enhancing documentation and tests, your input helps make this project better.

### How to Contribute

1. **Fork the Repository**
   Click the "Fork" button at the top right of the repository page to create a personal copy of the repository.

2. **Clone Your Fork**
   ```bash
   git clone https://github.com/your_username/0x01-ES6_promise.git
   cd 0x01-ES6_promise
   ```

3. **Create a New Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

4. **Make Your Changes**
   Add new files, modify existing ones, or update documentation as needed.

5. **Run Tests**
   Ensure all tests pass before committing your changes.
   ```bash
   npm test
   ```

6. **Commit Your Changes**
   ```bash
   git add .
   git commit -m "Description of your changes"
   ```

7. **Push to Your Fork**
   ```bash
   git push origin feature/your-feature-name
   ```

8. **Create a Pull Request**
   Navigate to the original repository and create a pull request from your fork's branch. Provide a clear description of your changes and the rationale behind them.

### Code of Conduct

Please adhere to the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/) to ensure a welcoming and respectful environment for all contributors.

---

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this code, provided you include the original license and attribution.

---

**Happy Coding!**  
Mastering Promises in ES6 paves the way for writing efficient and maintainable asynchronous JavaScript. Dive in, experiment with the examples, and build your expertise!

```
