these are javaScript variable.

In JavaScript, a variable is a container for storing data values. It allows you to label data with a
descriptive name so that your code can be more readable and maintainable. Variables can store different 
types of data, such as numbers, strings, arrays, objects, and more. variables are declared using three keywords: var, let, and const.

Var;
var is function-scoped. Variables declared with var are hoisted to the top of their enclosing function or global context.

let:

let is block-scoped. It is similar to var but has better scoping rules, which help avoid common bugs.

const:

const is also block-scoped. Variables declared with const are read-only
and cannot be reassigned after their initial value is set. However, the 
contents of objects or arrays declared with const can still be modified.

Variable Naming Rules;

Case-sensitive: Variable names are case-sensitive (myVar and myvar are different).
Start with a letter, underscore (_), or dollar sign ($): Variable names cannot start with a number.
No reserved words: Variable names cannot be JavaScript reserved keywords (like var, function, if, etc.).
