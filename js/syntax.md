# Syntax

### Creating and Using Variables

Variables are created with `var`, `let`, or `const`:

```javascript
var x;
let y;
```

Values are assigned to variables using `=`:

```javascript
x = 5;
y = 6;
let z = x + y;
```

### JavaScript Values

There are two types of values in JavaScript:

* **Literals** (fixed values):
  * Numbers: `10.50`, `1001`
  * Strings: `"John Doe"`, `'John Doe'`
* **Variables** (variable values):
  * `let x = 5;`

### JavaScript Operators

JavaScript uses operators to perform computations:

*   Arithmetic: `+`, `-`, `*`, `/`

    ```javascript
    (5 + 6) * 10
    ```
*   Assignment: `=`

    ```javascript
    let x = 5;
    ```

### JavaScript Expressions

An expression is a combination of values, variables, and operators that results in a value:

```javascript
5 * 10  // Evaluates to 50
```

```javascript
"John" + " " + "Doe"  // Evaluates to "John Doe"
```

### JavaScript Keywords

Keywords identify actions, like variable declarations:

*   `let`:

    ```javascript
    let x = 5;
    ```
*   `var`:

    ```javascript
    var y = 10;
    ```

### JavaScript Comments

Comments are ignored by the browser:

*   Single-line:

    ```javascript
    // This is a comment
    ```
*   Multi-line:

    ```javascript
    /* This is a 
       multi-line comment */
    ```

### JavaScript Identifiers

Identifiers name variables, functions, and other entities. They must start with:

* A letter (`A-Z`, `a-z`), `$`, or `_`
* The rest can include letters, digits, `$`, or `_`

JavaScript is **case sensitive**:

```javascript
let lastName = "Doe";
let lastname = "Peterson";
```

### JavaScript and Camel Case

Camel case is commonly used for variable names:

* **Lower Camel Case**: `firstName`, `lastName`
* **Upper Camel Case** (Pascal Case): `FirstName`, `LastName`

### JavaScript Character Set

JavaScript uses the **Unicode character set**, which supports almost all characters globally.
