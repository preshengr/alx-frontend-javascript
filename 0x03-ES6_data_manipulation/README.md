# 0x03-ES6_data_manipulation

This directory, **0x03-ES6_data_manipulation**, contains JavaScript files focusing on data manipulation techniques using ES6 (ECMAScript 2015) syntax. The files in this directory cover various ES6 features and functions for working with arrays, sets, maps, and typed arrays, all of which help in processing and transforming data efficiently.

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

This directory covers key ES6 data manipulation concepts, including:
- Filtering, mapping, and reducing arrays
- Working with sets and maps for efficient data handling
- Using typed arrays for optimized memory usage
- Applying weak collections for specialized use cases

These scripts illustrate how ES6 enhances JavaScript’s ability to manage and manipulate data, leading to cleaner and more performant code.

---

## Directory Structure

```plaintext
0x03-ES6_data_manipulation/
├── .eslintrc.cjs
├── 0-get_list_students.js
├── 1-get_list_student_ids.js
├── 2-get_students_by_loc.js
├── 3-get_ids_sum.js
├── 4-update_grade_by_city.js
├── 5-typed_arrays.js
├── 6-set.js
├── 7-has_array_values.js
├── 8-clean_set.js
├── 9-groceries_list.js
├── 10-update_uniq_items.js
├── 100-weak.js
├── tests/
│   ├── 0-get_list_students.test.js
│   ├── 1-get_list_student_ids.test.js
│   ├── 2-get_students_by_loc.test.js
│   ├── 3-get_ids_sum.test.js
│   ├── 4-update_grade_by_city.test.js
│   ├── 5-typed_arrays.test.js
│   ├── 6-set.test.js
│   ├── 7-has_array_values.test.js
│   ├── 8-clean_set.test.js
│   ├── 9-groceries_list.test.js
│   ├── 10-update_uniq_items.test.js
│   └── 100-weak.test.js
└── README.md
```

---

## File Descriptions

### Configuration
- **.eslintrc.cjs**: ESLint configuration file to enforce coding standards and best practices in JavaScript ES6.

### Data Manipulation Files

1. **0-get_list_students.js**
   - **Description**: Defines an array of student objects with sample data. This file provides a base dataset for further data manipulation tasks.
   - **Key Concepts**: Array creation, object structure.

2. **1-get_list_student_ids.js**
   - **Description**: Contains a function that takes an array of students and returns an array of their IDs.
   - **Key Concepts**: Array mapping, filtering null/undefined values.

3. **2-get_students_by_loc.js**
   - **Description**: Defines a function that filters students by location.
   - **Key Concepts**: Array filtering, property comparison.

4. **3-get_ids_sum.js**
   - **Description**: Contains a function that calculates the sum of all student IDs using `Array.reduce()`.
   - **Key Concepts**: Array reduction, aggregating data.

5. **4-update_grade_by_city.js**
   - **Description**: A function that updates students' grades based on their city.
   - **Key Concepts**: Array mapping and filtering, data mutation.

6. **5-typed_arrays.js**
   - **Description**: Introduces typed arrays to work with raw binary data.
   - **Key Concepts**: Working with `Uint8Array`, memory efficiency.

7. **6-set.js**
   - **Description**: Demonstrates the use of the `Set` data structure to handle unique values.
   - **Key Concepts**: Sets, uniqueness enforcement.

8. **7-has_array_values.js**
   - **Description**: Implements a function to check if specific values exist in an array using `Set`.
   - **Key Concepts**: Set membership, array lookup optimization.

9. **8-clean_set.js**
   - **Description**: A utility function to create a clean string from a set by joining its elements with a separator.
   - **Key Concepts**: Set manipulation, string manipulation.

10. **9-groceries_list.js**
    - **Description**: Defines a map structure representing grocery items and their quantities.
    - **Key Concepts**: Map data structure, key-value mapping.

11. **10-update_uniq_items.js**
    - **Description**: Updates the quantities of unique grocery items in a map.
    - **Key Concepts**: Map manipulation, conditional updates.

12. **100-weak.js**
    - **Description**: Demonstrates the use of `WeakMap` and `WeakSet` for managing weakly held objects.
    - **Key Concepts**: Memory management, garbage collection.

### Tests
- **tests/**: This directory contains unit tests for each JavaScript file to ensure correct implementation of functions. Each test file corresponds to its source file (e.g., `0-get_list_students.test.js` for `0-get_list_students.js`).

---

## General Requirements

- **JavaScript Version**: ES6 (ECMAScript 2015)
- **Coding Style**: Consistent with best practices enforced by `.eslintrc.cjs`
- **Testing Framework**: Uses `Jest` for unit testing
- **Dependencies**: Managed via `npm`; install necessary dependencies before running scripts or tests

---

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your_username/0x03-ES6_data_manipulation.git
   cd 0x03-ES6_data_manipulation
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

   This installs all required packages, including the testing framework.

---

## Usage

Each file can be run with Node.js to explore ES6 data manipulation concepts. Functions provided in each file can be used to manage and manipulate data.

### Running a Script

To run any of the files, navigate to the directory and use the Node.js command:

```bash
node 0-get_list_students.js
```

This example will execute the `0-get_list_students.js` script, displaying its output.

### Example

To see how `3-get_ids_sum.js` works:

```bash
node 3-get_ids_sum.js
```

This will execute the file and calculate the sum of IDs for a sample list of students.

---

## Testing

The `tests/` directory contains unit tests for all JavaScript files, verifying correct functionality of each function and ensuring data manipulation is accurate.

### Running Tests

1. **Ensure Dependencies are Installed**: Make sure all dependencies are installed (as per the [Installation](#installation) section).

2. **Run Tests**:
   ```bash
   npm test
   ```

   This command will execute all tests in the `tests/` directory. Each test checks the functionality, handling of edge cases, and expected outputs.

### Writing Tests

Each test file has a corresponding source file. Tests ensure:
- **Functionality**: Each function behaves as expected.
- **Data Accuracy**: Functions produce correct data outputs.
- **Edge Cases**: Handles extreme or unexpected inputs.
- **Error Handling**: Functions respond appropriately to errors or incorrect input types.

Additional tests can be added to cover new functions or specific use cases.

---

## Contributing

Contributions are welcome! Whether you’re adding new features, fixing bugs, or improving documentation, your contributions help improve this project.

### How to Contribute

1. **Fork the Repository**
   Click on "Fork" at the top of the repository to create a copy.

2. **Clone Your Fork**
   ```bash
   git clone https://github.com/your_username/0x03-ES6_data_manipulation.git
   cd 0x03-ES6_data_manipulation
   ```

3. **Create a New Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

4. **Make Changes**: Modify or add files as needed.

5. **Run Tests**
   ```bash
   npm test
   ```

   Ensure all tests pass before committing.

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
   Go to the original repository and open a pull request from your forked branch. Include a description of your changes.

### Code of Conduct

Follow the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/) to ensure a respectful and inclusive environment for all contributors.

---

## License

This project is licensed under the [MIT License](LICENSE), allowing you to use, modify, and distribute the code with attribution to the original author.

---

**Enjoy Exploring ES6 Data Manipulation!**  
These examples demonstrate powerful ES6 tools for efficient data processing. Use and adapt them in your own projects to manage data with greater ease and flexibility.
