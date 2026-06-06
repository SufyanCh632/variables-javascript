# variables-javascript# JavaScript Variables and Data Types

## Introduction

This project demonstrates the use of JavaScript variables, arithmetic operations, strings, template literals, Boolean values, and console output.

## Source Code

```javascript
var eng = 85;
let math = 70;

const phy = 65;

eng = 85 + 5;
math = 70 - 5;

console.log(eng);
console.log(math);
console.log(phy);

var stdName = "Ahmed";

var mulString = `
I love Pakistan
My army is our great
Imran Khan is our Leader
Lets play soccer`;

var fName = "Ahmed";
var lName = "Khan";

console.log(stdName);
console.log(mulString);
console.log(fName + " " + lName);

var win = true;
console.log(win);
```

## Concepts Covered

### 1. Variable Declaration

JavaScript provides three ways to declare variables:

#### `var`

```javascript
var eng = 85;
```

#### `let`

```javascript
let math = 70;
```

#### `const`

```javascript
const phy = 65;
```

### 2. Arithmetic Operations

```javascript
eng = 85 + 5;
math = 70 - 5;
```

Results:

* English Marks = 90
* Math Marks = 65

### 3. String Variables

```javascript
var stdName = "Ahmed";
```

Stores a text value.

### 4. Template Literals

```javascript
var mulString = `
I love Pakistan
My army is our great
Imran Khan is our Leader
Lets play soccer`;
```

Template literals use backticks (`) and allow multi-line strings.

### 5. String Concatenation

```javascript
var fName = "Ahmed";
var lName = "Khan";

console.log(fName + " " + lName);
```

Output:

```text
Ahmed Khan
```

### 6. Boolean Data Type

```javascript
var win = true;
console.log(win);
```

Boolean values can be either:

* `true`
* `false`

## Program Output

```text
90
65
65
Ahmed

I love Pakistan
My army is our great
Imran Khan is our Leader
Lets play soccer

Ahmed Khan
true
```

## Data Types Used

| Variable  | Data Type |
| --------- | --------- |
| eng       | Number    |
| math      | Number    |
| phy       | Number    |
| stdName   | String    |
| mulString | String    |
| fName     | String    |
| lName     | String    |
| win       | Boolean   |

## Learning Outcomes

By completing this example, you will learn:

* How to declare variables using `var`, `let`, and `const`
* How to perform arithmetic operations
* How to display output using `console.log()`
* How to work with strings and template literals
* How to concatenate strings
* How to use Boolean values in JavaScript

## Author

Muhammad Suffiyan Rafi
Computer Science Student | JavaScript Learner
