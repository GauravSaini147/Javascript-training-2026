# Javascript-training-2026
Summer training to extend web dev abilities

***date 25 june***
 
## JavaScript at a Glance
- **Programming language** → It’s a full-fledged language used to write logic and functionality.  
- **Web development** → Core technology of the web, alongside HTML and CSS.  
- **Client-side** → Runs directly in the browser to make pages interactive (though it can also run server-side via Node.js).  
- **Open-source** → The language specification (ECMAScript) and most of its ecosystem are community-driven and open.  
- **Dynamic typing** → Variables don’t need explicit type declarations; types can change at runtime.  
- **Interpreted** → Code is executed line by line by the browser’s JavaScript engine (like V8 in Chrome), rather than being compiled beforehand.  

---
## Why These Traits Matter
- **Dynamic typing** makes coding faster but can lead to runtime errors if not handled carefully.  
- **Interpreted execution** means you can test and run code instantly in the browser console.  
- **Client-side nature** allows real-time interactivity — think dropdown menus, animations, or live form validation.  
- **Open-source ecosystem** gives you access to countless libraries (React, Vue, Angular, etc.) to speed up development.  

---

 Quick Example
Here’s a snippet showing dynamic typing and client-side execution:

```javascript
let data = 42;       // number
console.log(data);   // prints 42

data = "Hello JS";   // now a string
console.log(data);   // prints "Hello JS"
```

The same variable `data` changes type at runtime — that’s dynamic typing in action.

**multiple outputs using `<br>` for line breaks**.

```html
<!DOCTYPE html>
<html>
<head>
  <title>JavaScript Multiple Outputs</title>
</head>
<body>
  <script>
    document.write("Hello, World!<br>");
    document.write("JavaScript is powerful.<br>");
    document.write("It runs in the browser.<br>");
    document.write("Dynamic typing makes it flexible.<br>");
    document.write("Interpreted execution means instant results.<br>");
  </script>
</body>
</html>
```

---

## Explanation
- `document.write()` → Outputs text directly to the webpage.  
- `"<br>"` → Inserts a line break, so each message appears on a new line.  
- This is a **classic beginner-friendly way** to show multiple outputs in JavaScript.  


JavaScript example using `const`** with multiple outputs separated by `<br>` line breaks:

```html
<!DOCTYPE html>
<html>
<head>
  <title>JavaScript Const Example</title>
</head>
<body>
  <script>
    const project = "Wildlife Conservation";
    const year = 2026;
    const language = "JavaScript";
    const type = "Dynamic, Interpreted";

    document.write("Project: " + project + "<br>");
    document.write("Year: " + year + "<br>");
    document.write("Language: " + language + "<br>");
    document.write("Type: " + type + "<br>");
  </script>
</body>
</html>
```

---

## Explanation
- `const` → Declares a constant variable (its value cannot be reassigned).  
- `document.write()` → Outputs text directly to the webpage.  
- `"<br>"` → Inserts a line break so each output appears on a new line.  


<!DOCTYPE html>
<html>
<head>
  <title>JavaScript Var Example</title>
</head>
<body>
  <script>
    var name = "Gaurav";
    var project = "Wildlife Conservation Project";
    var year = 2026;
    var language = "JavaScript";

    document.write("Name: " + name + "<br>");
    document.write("Project: " + project + "<br>");
    document.write("Year: " + year + "<br>");
    document.write("Language: " + language + "<br>");
  </script>
</body>
</html>
Explanation
var → Declares a variable with function scope (older style, before let and const).

Reassignment allowed → You can change the value of a var variable later.

document.write() + <br> → Outputs text to the page with line breaks.

Example of Reassignment with var
html
<script>
  var score = 50;
  document.write("Initial Score: " + score + "<br>");

  score = 90; // reassigned
  document.write("Updated Score: " + score + "<br>");
</script>
**Key difference:**

var → function-scoped, can be redeclared.

let → block-scoped, can be reassigned but not redeclared in the same scope.

const → block-scoped, cannot be reassigned or redeclared.

using alert() to show messages in popup dialog boxes:

html
<!DOCTYPE html>
<html>
<head>
  <title>JavaScript Alert Example</title>
</head>
<body>
  <script>
    // Single alert
    alert("Hello, World!");

    // Multiple alerts one after another
    alert("Welcome to JavaScript!");
    alert("This is an alert box.");
    alert("Alerts pause code execution until you click OK.");
  </script>
</body>
</html>


## Explanation
alert("message") → Displays a popup box with the given message and an OK button.

Alerts are modal → They stop the page until the user clicks OK.

Useful for quick debugging or notifications, but not recommended for polished user interfaces.


**JavaScript using `console.log()`** to output multiple values directly into the browser’s developer console:

```html
<!DOCTYPE html>
<html>
<head>
  <title>JavaScript Console Log Example</title>
</head>
<body>
  <script>
    // Using console.log for multiple outputs
    console.log("Hello, World!");
    console.log("JavaScript is powerful.");
    console.log("It runs in the browser.");
    console.log("Dynamic typing makes it flexible.");
    console.log("Interpreted execution means instant results.");

    // Example with variables
    let name = "Gaurav";
    let project = "Wildlife Conservation";
    let year = 2026;

    console.log("Name: " + name);
    console.log("Project: " + project);
    console.log("Year: " + year);
  </script>
</body>
</html>
```

---

##  Explanation
- **`console.log()`** → Prints output to the browser’s **developer console** (press `F12` or `Ctrl+Shift+I` → Console tab).  
- Unlike `document.write()` or `alert()`, this doesn’t interrupt the page or show popups — it’s mainly used for **debugging and development**.  
- You can log **strings, numbers, variables, arrays, objects**, and even styled text.  

---

###  Advanced Example: Logging Different Types
```javascript
console.log("String output");
console.log(12345);              // Number
console.log(true);               // Boolean
console.log([1, 2, 3]);          // Array
console.log({name: "Gaurav", year: 2026}); // Object
```

