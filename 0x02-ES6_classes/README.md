# 0x02-ES6_classes

This directory, **0x02-ES6_classes**, contains JavaScript files that demonstrate object-oriented programming concepts in ES6 (ECMAScript 2015) using classes. ES6 classes introduce a more structured syntax for creating objects and managing inheritance in JavaScript, providing a cleaner approach to object-oriented programming (OOP).

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

This directory introduces ES6 classes and covers a range of topics including:
- Defining classes and constructors
- Instance and static methods
- Inheritance and method overriding
- Encapsulation and private fields
- Class extensions and polymorphism

These files provide a foundation in using ES6 classes to design objects and manage object relationships, enabling more maintainable and modular JavaScript code.

---

## Directory Structure

```plaintext
0x02-ES6_classes/
├── .eslintrc.cjs
├── 0-classroom.js
├── 1-make_classrooms.js
├── 2-hbtn_course.js
├── 3-currency.js
├── 4-pricing.js
├── 5-building.js
├── 6-sky_high.js
├── 7-airport.js
├── 8-hbtn_class.js
├── 9-hoisting.js
├── 10-car.js
├── 100-evcar.js
├── tests/
│   ├── 0-classroom.test.js
│   ├── 1-make_classrooms.test.js
│   ├── 2-hbtn_course.test.js
│   ├── 3-currency.test.js
│   ├── 4-pricing.test.js
│   ├── 5-building.test.js
│   ├── 6-sky_high.test.js
│   ├── 7-airport.test.js
│   ├── 8-hbtn_class.test.js
│   ├── 9-hoisting.test.js
│   ├── 10-car.test.js
│   └── 100-evcar.test.js
└── README.md
```

---

## File Descriptions

### Configuration
- **.eslintrc.cjs**: ESLint configuration file (in CommonJS format) enforcing code standards and best practices for ES6. This ensures consistent code quality across all files.

### Class Files
1. **0-classroom.js**
   - **Description**: This file defines a simple `Classroom` class that demonstrates basic class properties and methods.
   - **Key Concepts**: Defining a class, using constructor functions.

2. **1-make_classrooms.js**
   - **Description**: Contains a function that creates multiple instances of the `Classroom` class, demonstrating instantiation of multiple objects.
   - **Key Concepts**: Object creation, class instantiation.

3. **2-hbtn_course.js**
   - **Description**: Defines a `HolbertonCourse` class that includes properties such as `name`, `length`, and `students`. This example demonstrates the use of properties with setter and getter methods.
   - **Key Concepts**: Getters and setters, data encapsulation.

4. **3-currency.js**
   - **Description**: This file introduces a `Currency` class that represents different currencies. It includes properties like `code` and `name`.
   - **Key Concepts**: Constructor properties, encapsulating data.

5. **4-pricing.js**
   - **Description**: Defines a `Pricing` class, utilizing the `Currency` class. This example demonstrates composition, where one class uses instances of another class as part of its functionality.
   - **Key Concepts**: Class composition, dependency relationships.

6. **5-building.js**
   - **Description**: Contains an abstract `Building` class with a `sqft` property and an abstract method `evacuationWarningMessage`. This demonstrates abstract classes and methods in ES6.
   - **Key Concepts**: Abstract classes, method overriding.

7. **6-sky_high.js**
   - **Description**: Defines a `SkyHighBuilding` class that extends the `Building` class, adding additional properties and implementing the abstract method.
   - **Key Concepts**: Class inheritance, method extension.

8. **7-airport.js**
   - **Description**: Introduces an `Airport` class with properties for an airport’s name and code. It also includes a custom `toString` method.
   - **Key Concepts**: Method overriding, custom `toString`.

9. **8-hbtn_class.js**
   - **Description**: Defines a `HolbertonClass` class with private fields. This example explores using private fields to control access to class data.
   - **Key Concepts**: Private fields, data hiding.

10. **9-hoisting.js**
    - **Description**: Demonstrates hoisting behavior with classes. This file shows how class declarations are hoisted differently from function declarations.
    - **Key Concepts**: Hoisting, class declaration behavior.

11. **10-car.js**
    - **Description**: Contains a `Car` class with properties for the brand and model of a car. Demonstrates basic class structure with multiple properties.
    - **Key Concepts**: Multiple class properties, constructor usage.

12. **100-evcar.js**
    - **Description**: Defines an `EVCar` class that extends the `Car` class, representing electric vehicles with additional properties for battery range.
    - **Key Concepts**: Class inheritance, extending functionality.

### Tests
- **tests/**: This directory contains unit tests for each JavaScript file, ensuring that all classes and methods work as expected. Each test file corresponds to its source file, following a naming convention (e.g., `0-classroom.test.js` for `0-classroom.js`).

---

## General Requirements

- **JavaScript Version**: ES6 (ECMAScript 2015)
- **Coding Style**: Conforms to JavaScript best practices enforced by `.eslintrc.cjs`.
- **Testing Framework**: Uses `Jest` for unit testing.
- **Dependencies**: Managed via `npm`. Install all necessary dependencies before running scripts or tests.

---

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your_username/0x02-ES6_classes.git
   cd 0x02-ES6_classes
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

   This installs all required packages, including the testing framework.

---

## Usage

Each JavaScript file contains classes or functions that illustrate specific OOP concepts using ES6 classes. You can run each script directly with Node.js or integrate these classes into other projects.

### Running a Script

To execute a script, navigate to its directory and run it using Node.js:

```bash
node 0-classroom.js
```

This command will run the `0-classroom.js` file and display its output.

### Example

To see how `6-sky_high.js` works:

```bash
node 6-sky_high.js
```

This will demonstrate the use of inheritance and abstract classes.

---

## Testing

The `tests/` directory contains unit tests for each file to ensure that all classes and methods behave correctly.

### Running Tests

1. **Install Dependencies**: Make sure all dependencies are installed (as per the [Installation](#installation) section).

2. **Run Tests**:
   ```bash
   npm test
   ```

   This will execute all test files in the `tests/` directory. Each test checks class behavior, including methods, inheritance, and error handling.

### Writing Tests

Each test file corresponds to a source file (e.g., `0-classroom.test.js` for `0-classroom.js`). Tests cover the following:

- **Class Functionality**: Ensures each class functions as expected.
- **Inheritance and Overriding**: Verifies that subclasses properly inherit and override methods.
- **Edge Cases**: Checks for unexpected or extreme inputs.
- **Error Handling**: Ensures classes throw expected errors when used incorrectly.

You can add additional tests as needed to cover new functionality or edge cases.

---

## Contributing

We welcome contributions to this directory! Whether you’re adding new classes, improving existing ones, or enhancing documentation and tests, your input helps improve this project.

### How to Contribute

1. **Fork the Repository**
   Click on "Fork" at the top right of the repository to create your own copy.

2. **Clone Your Fork**
   ```bash
   git clone https://github.com/your_username/0x02-ES6_classes.git
   cd 0x02-ES6_classes
   ```

3. **Create a New Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

4. **Make Changes**
   Modify or add files as needed.

5. **Run Tests**
   Make sure all tests pass before committing:
   ```bash
   npm test
   ```

6. **Commit Changes**
   ```bash
   git add .
   git commit -m "Description of your changes"
   ```

7. **Push to Your Fork**
   ```bash
   git push origin feature/your-feature-name
   ```

8. **Create a Pull Request**
   Go

 to the original repository and create a pull request from your forked branch. Include a description of your changes.

### Code of Conduct

Please follow the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/) to ensure a welcoming environment for all contributors.

---

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this code with attribution to the original author.

---

### Additional Notes:

- **ESLint**: Make sure `.eslintrc.cjs` is set up according to your code standards. Proper linting is essential to maintaining code quality.
- **Testing Framework**: Adapt instructions if using a different framework. Configure any necessary files or commands as needed.
- **Private Fields**: Be aware of class-private fields (`#`) as they might not be supported in all JavaScript environments.
