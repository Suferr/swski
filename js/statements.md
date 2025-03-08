# Statements

### Statements

JavaScript statements are individual instructions executed by the browser:

```javascript
let x, y, z;    // Statement 1
x = 5;          // Statement 2
y = 6;          // Statement 3
z = x + y;      // Statement 4
```

### JavaScript Programs

A JavaScript program is a sequence of statements executed in order. These instructions are executed by the web browser.

### Semicolons

Semicolons separate JavaScript statements. They're optional but highly recommended:

```javascript
let a, b, c;  // Declare 3 variables
a = 5;        // Assign value to a
b = 6;        // Assign value to b
c = a + b;    // Assign sum to c
```

Multiple statements on one line are allowed with semicolons:

```javascript
a = 5; b = 6; c = a + b;
```

### White Space

JavaScript ignores extra spaces. Use white space for readability:

```javascript
let person = "Hege";
let person="Hege";
```

### Line Breaks

Avoid long lines (over 80 characters). Break lines after operators for better readability:

```javascript
document.getElementById("demo").innerHTML = 
"Hello Dolly!";
```

### Code Blocks

Statements can be grouped in code blocks inside curly braces `{...}`:

```javascript
function myFunction() {
  document.getElementById("demo1").innerHTML = "Hello Dolly!";
  document.getElementById("demo2").innerHTML = "How are you?";
}
```

### JavaScript Keywords

Keywords are used to define actions in JavaScript. Some common ones are:

| Keyword    | Description                      |
| ---------- | -------------------------------- |
| `var`      | Declares a variable              |
| `let`      | Declares a block variable        |
| `const`    | Declares a block constant        |
| `if`       | Conditional statement            |
| `switch`   | Selects between multiple cases   |
| `for`      | Loops over a block of statements |
| `function` | Declares a function              |
| `return`   | Exits a function                 |
| `try`      | Implements error handling        |

\


