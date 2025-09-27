# 🛠️ Array Base Reshape

![GitHub Repo Stars](https://img.shields.io/github/stars/Kimba26/array-base-reshape?style=social) ![GitHub License](https://img.shields.io/github/license/Kimba26/array-base-reshape)

Welcome to the **Array Base Reshape** repository! This project allows you to reshape a nested array into another nested array with a desired shape. Whether you're working on data manipulation, transformation, or just need to structure your arrays better, this tool is designed to help you achieve that with ease.

## 🚀 Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

## 📖 Introduction

In the world of programming, arrays are fundamental. They help store and manage collections of data efficiently. However, there are times when the structure of your data needs to change. The **Array Base Reshape** library simplifies this process. It provides a straightforward way to reshape nested arrays, making your data more usable for various applications.

## 🌟 Features

- **Simple Reshaping**: Easily transform nested arrays into your desired structure.
- **Flexible Input**: Accepts various array formats and structures.
- **Lightweight**: Minimal overhead ensures fast performance.
- **Node.js Compatible**: Works seamlessly with Node.js applications.

## 📥 Installation

To get started with **Array Base Reshape**, you can install it via npm. Open your terminal and run:

```bash
npm install array-base-reshape
```

For more information about releases, visit the [Releases](https://github.com/Kimba26/array-base-reshape/releases) section.

## 🛠️ Usage

Using the **Array Base Reshape** library is straightforward. Here’s how you can reshape your nested arrays:

1. **Import the Library**:
   ```javascript
   const reshape = require('array-base-reshape');
   ```

2. **Define Your Nested Array**:
   ```javascript
   const nestedArray = [
       [1, 2, 3],
       [4, 5, 6],
       [7, 8, 9]
   ];
   ```

3. **Reshape the Array**:
   ```javascript
   const reshapedArray = reshape(nestedArray, [3, 3]);
   console.log(reshapedArray);
   ```

## 📊 Examples

Here are some examples to demonstrate how to use the library effectively.

### Example 1: Basic Reshape

```javascript
const reshape = require('array-base-reshape');

const inputArray = [
    [1, 2],
    [3, 4]
];

const newShape = [4];
const outputArray = reshape(inputArray, newShape);
console.log(outputArray); // [1, 2, 3, 4]
```

### Example 2: Reshape to a Different Dimension

```javascript
const reshape = require('array-base-reshape');

const inputArray = [
    [1, 2, 3],
    [4, 5, 6]
];

const newShape = [2, 3];
const outputArray = reshape(inputArray, newShape);
console.log(outputArray); // [[1, 2, 3], [4, 5, 6]]
```

### Example 3: Flattening an Array

```javascript
const reshape = require('array-base-reshape');

const inputArray = [
    [1, 2],
    [3, 4],
    [5, 6]
];

const newShape = [6];
const outputArray = reshape(inputArray, newShape);
console.log(outputArray); // [1, 2, 3, 4, 5, 6]
```

## 🤝 Contributing

We welcome contributions to the **Array Base Reshape** project! If you have ideas for improvements or find bugs, please feel free to submit an issue or a pull request.

### Steps to Contribute

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Test your changes.
5. Submit a pull request.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## 📞 Support

If you have any questions or need assistance, feel free to open an issue on GitHub. You can also check the [Releases](https://github.com/Kimba26/array-base-reshape/releases) section for updates and downloads.

Thank you for checking out **Array Base Reshape**! We hope this library helps you manage your nested arrays effectively.