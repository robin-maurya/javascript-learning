# Day 01 - JavaScript Introduction

## 📚 Topics Covered

- What is JavaScript?
- Hello World Program
- console.log()
- Variables
- Data Types
- Comments
- Console Methods

---

# What is JavaScript?

JavaScript is a high-level, interpreted, and dynamically typed programming language used to create interactive and dynamic web applications.

JavaScript runs in:

- Web Browsers (Chrome, Firefox, Edge)
- Node.js (Server-side)

---

# Features of JavaScript

- Lightweight
- Interpreted Language
- Dynamic Typing
- Object-Oriented
- Event-Driven
- Cross-Platform
- Asynchronous Programming Support

---

# Hello World

The first JavaScript program is generally written using `console.log()`.

Example:

```javascript
console.log("Hello, World!");
```

Output

```
Hello, World!
```

---

# console.log()

`console.log()` is used to display information in the browser console or terminal.

Example

```javascript
console.log("Learning JavaScript");
```

---

# Variables

Variables are used to store data.

Example

```javascript
let name = "Robin";
```

---

# Variable Naming Rules

- Variable names should start with a letter, `_`, or `$`.
- Cannot start with a number.
- Cannot use reserved keywords.
- JavaScript is case-sensitive.

Valid Examples

```javascript
let firstName;
let userAge;
let employeeSalary;
let _total;
let $price;
```

Invalid Examples

```javascript
let 1name;
let first-name;
let let;
```

---

# Data Types

## Primitive Data Types

- String
- Number
- Boolean
- Undefined
- Null
- BigInt
- Symbol

Example

```javascript
let name = "Robin";
let age = 25;
let isDeveloper = true;
let city;
let salary = null;
```

---

# typeof Operator

The `typeof` operator is used to check the data type of a value.

Example

```javascript
console.log(typeof "Robin"); // string
console.log(typeof 25);      // number
console.log(typeof true);    // boolean
```

---

# Comments

Comments are ignored by the JavaScript engine.

Single Line

```javascript
// This is a comment
```

Multi Line

```javascript
/*
This is
a multi-line comment
*/
```

---

# Console Methods

- console.log()
- console.info()
- console.warn()
- console.error()
- console.table()

---

# Best Practices

- Use meaningful variable names.
- Follow camelCase naming convention.
- Write clean and readable code.
- Add comments only when necessary.
- Use `let` and `const` instead of `var` (we'll study this in the next topic).

---

# Summary

Today we learned:

- JavaScript Introduction
- Hello World
- Variables
- Data Types
- Comments
- Console Methods