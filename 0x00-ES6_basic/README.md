# 0x00-ES6_basic

This directory contains JavaScript exercises to help understand and apply basic concepts of ES6 (ECMAScript 2015). ES6 introduced several new features and improvements to the JavaScript language, making it more efficient and expressive. The goal of this directory is to strengthen your understanding of these concepts through practical coding tasks.

---

## Table of Contents
- [Overview](#overview)
- [Directory Structure](#directory-structure)
- [File Descriptions](#file-descriptions)
- [General Requirements](#general-requirements)
- [Testing](#testing)

---

## Overview

The files in this directory cover essential ES6 topics, including:
- Constants and block-scoping
- Arrow functions
- Default parameters
- Rest and spread operators
- Template literals (string interpolation)
- Loops and iterators
- Object-oriented enhancements (methods for creating and iterating over objects)

Each file is named according to the topic it covers and contains a single task or function that demonstrates the ES6 feature in focus.

---

## Directory Structure

```plaintext
0x00-ES6_basic/
├── .eslintrc.cjs
├── 0-constants.js
├── 1-block-scoped.js
├── 2-arrow.js
├── 3-default-parameter.js
├── 4-rest-parameter.js
├── 5-spread-operator.js
├── 6-string-interpolation.js
├── 7-getBudgetObject.js
├── 8-getBudgetCurrentYear.js
├── 9-getFullBudget.js
├── 10-loops.js
├── 11-createEmployeesObject.js
├── 12-createReportObject.js
├── 100-createIteratorObject.js
├── 101-iterateThroughObject.js
└── tests/
    └── (Test files for each JavaScript file, with corresponding unit tests)
```

---

## File Descriptions

### Configuration
- **.eslintrc.cjs**: ESLint configuration file to enforce coding standards. This file is in CommonJS format and specifies rules for linting JavaScript ES6 code, helping maintain clean and consistent code throughout the project.

### ES6 Basic Files
1. **0-constants.js**: Demonstrates the use of constants (`const`) in JavaScript. This file explains how to declare constant values and emphasizes that constants cannot be reassigned.

2. **1-block-scoped.js**: Introduces `let` and `const` for block-scoped variable declarations. This file shows how block-scoping works within loops, conditionals, and other code blocks.

3. **2-arrow.js**: Covers arrow functions, which offer a shorter syntax for function expressions. This file explores arrow function syntax, implicit return, and how `this` behaves differently compared to traditional functions.

4. **3-default-parameter.js**: Demonstrates the use of default function parameters, allowing parameters to have default values if none are provided.

5. **4-rest-parameter.js**: Explains the rest parameter syntax (`...args`), which allows functions to accept an indefinite number of arguments as an array.

6. **5-spread-operator.js**: Shows how to use the spread operator (`...`) to expand elements of an iterable (like arrays) into individual elements, and also to create shallow copies of objects or arrays.

7. **6-string-interpolation.js**: Covers template literals for string interpolation, allowing embedding expressions inside strings using backticks (` `` `) and `${}` syntax.

8. **7-getBudgetObject.js**: Contains a function that returns a budget object using concise ES6 object syntax.

9. **8-getBudgetCurrentYear.js**: Demonstrates dynamic property names in object literals, allowing the creation of keys based on variables.

10. **9-getFullBudget.js**: Shows how to combine multiple objects using the spread operator. This file illustrates merging objects and creating new structures from existing ones.

11. **10-loops.js**: Explains various ES6 looping methods, such as `for...of` and `for...in`, and their appropriate use cases.

12. **11-createEmployeesObject.js**: Defines a function to create an `employees` object. This example uses concise method syntax and shows the creation of structured data objects.

13. **12-createReportObject.js**: Contains a function that builds a report object, demonstrating the nesting of objects and usage of concise syntax.

14. **100-createIteratorObject.js**: Introduces custom iterators by creating an object with a `[Symbol.iterator]` method. This example shows how to manually define an iterator to control iteration behavior.

15. **101-iterateThroughObject.js**: Uses the iterator created in `100-createIteratorObject.js` to iterate over an object’s properties. This example highlights the interaction of custom iterators with looping constructs.

---

## General Requirements

- **JavaScript Version**: ES6 (ECMAScript 2015)
- **Coding Style**: This project follows JavaScript coding best practices enforced by `.eslintrc.cjs` for linting.
- **Testing Framework**: Files are tested using unit tests (located in the `tests` directory) to verify correctness.

---

## Testing

The `tests/` directory contains unit tests for each of the JavaScript files. To ensure that your functions work as expected, run the tests after making changes. Here’s how to do it:

1. **Install dependencies**: Make sure to install any necessary packages, including a testing framework like `Jest` or `Mocha`.

   ```bash
   npm install
   ```

2. **Run tests**: Execute the tests by running:

   ```bash
   npm test
   ```

   Each test file corresponds to a JavaScript file in the main directory and checks for correct function behavior and edge cases.

---

Happy coding! This project will strengthen your understanding of ES6 basics and help you apply modern JavaScript features in real-world scenarios.
