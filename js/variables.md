# Variables

Variables in JavaScript act as containers to store data values. You can declare variables in different ways:

#### 1. Automatically

Variables can be declared automatically when first used:

```javascript
x = 5;
y = 6;
z = x + y;
```

In this case, `x` stores `5`, `y` stores `6`, and `z` stores the sum `11`.

#### 2. Using `var`

The `var` keyword was the standard for declaring variables in JavaScript until 2015:

```javascript
var x = 5;
var y = 6;
var z = x + y;
```

#### 3. Using `let`

The `let` keyword, introduced in 2015, allows you to declare variables that can be reassigned:

```javascript
let x = 5;
let y = 6;
let z = x + y;
```

#### 4. Using `const`

The `const` keyword is used for variables that should not change after their initial assignment:

```javascript
const x = 5;
const y = 6;
const z = x + y;
```

#### Mixed Example

```javascript
const price1 = 5;
const price2 = 6;
let total = price1 + price2; // total can be changed
```

In this example, `price1` and `price2` are constants, while `total` can be modified.

#### When to Use `var`, `let`, or `const`

* Always declare variables for clarity.
* Use `const` if the value should remain constant or if the type (e.g., Arrays or Objects) shouldn't change.
* Use `let` only if you can't use `const`.
* Avoid using `var` unless you must support old browsers.

***

#### Variables in Algebra

Just like algebra, JavaScript variables hold values and are used in expressions:

```javascript
let x = 5;
let y = 6;
let z = x + y; // 11
```

#### JavaScript Identifiers (Names)

JavaScript variable names are called identifiers and must follow these rules:

* Can contain letters, digits, underscores, and dollar signs (`_` and `$`).
* Must start with a letter, underscore, or dollar sign.
* Cannot start with a digit.
* Are case-sensitive.

#### Assignment Operator (`=`)

In JavaScript, the equal sign (`=`) is the **assignment** operator, not the equality operator. For example:

```javascript
x = x + 5; // This works in JavaScript and assigns the value of `x + 5` back to `x`
```

***

#### JavaScript Data Types

JavaScript can handle various types of data, but two main types are **numbers** and **strings**:

* Numbers are written without quotes: `let pi = 3.14;`
* Strings are written with quotes: `let person = "John Doe";`

#### Declaring a Variable

You can declare variables using `var`, `let`, or `const`:

```javascript
let carName = "Volvo";
```

If a variable is declared without an initial value, it will have the value `undefined`:

```javascript
let carName;
```

#### Re-Declaring Variables

* **With `var`**: Re-declaring a variable does not erase its value:

```javascript
var carName = "Volvo";
var carName;
```

* **With `let` and `const`**: You cannot re-declare variables declared with `let` or `const`.

```javascript
let carName = "Volvo";
let carName;  // This will throw an error
```

#### Arithmetic with Variables

JavaScript allows arithmetic operations with variables, similar to algebra:

```javascript
let x = 5 + 2 + 3;  // Result: 10
let y = "John" + " " + "Doe";  // String concatenation: "John Doe"
```

You can also add numbers stored as strings:

```javascript
let x = "5" + 2 + 3;  // Result: "523" (Concatenation)
let y = 2 + 3 + "5";  // Result: "55" (Concatenation)
```

#### JavaScript Dollar Sign (`$`) and Underscore (`_`)

* `$` is valid in variable names, though it's often used in libraries like jQuery:

```javascript
let $ = "Hello World";
```

* `_` is also valid and sometimes used for private variables:

```javascript
let _lastName = "Johnson";
```

Both `$` and `_` can be used in identifiers, though they have specific conventions in certain JavaScript practices.
