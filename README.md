# variables-javascript
# JavaScript Variables Example

## Overview

This project demonstrates the use of JavaScript variables using `var`, `let`, and `const`. It also shows:

* Updating variable values
* Printing output to the console
* Working with strings
* Using template literals for multi-line text
* Concatenating strings

## Code

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
```

## Explanation

### Numeric Variables

```javascript
var eng = 85;
let math = 70;
const phy = 65;
```

* `eng` stores English marks.
* `math` stores Mathematics marks.
* `phy` stores Physics marks and cannot be reassigned because it is declared with `const`.

### Updating Values

```javascript
eng = 85 + 5;
math = 70 - 5;
```

Results:

* `eng = 90`
* `math = 65`

### Displaying Values

```javascript
console.log(eng);
console.log(math);
console.log(phy);
```

Output:

```text
90
65
65
```

### String Variables

```javascript
var stdName = "Ahmed";
```

Stores the student's name.

### Multi-Line String

```javascript
var mulString = `
I love Pakistan
My army is our great
Imran Khan is our Leader
Lets play soccer`;
```

Uses a template literal (backticks) to store text across multiple lines.

### String Concatenation

```javascript
var fName = "Ahmed";
var lName = "Khan";

console.log(fName + " " + lName);
```

Output:

```text
Ahmed Khan
```

## Complete Output

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
```

## Learning Objectives

After completing this example, you will understand:

* `var`, `let`, and `const`
* Variable reassignment
* Console output
* Template literals
* String concatenation
* Basic JavaScript syntax

```
```
