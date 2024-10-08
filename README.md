# Vyzon

Vyzon is a modern programming language inspired by the elegance of Python, the flexibility of JavaScript, and the expressiveness of Ruby. It is designed with a primary focus on readability and simplicity while maintaining powerful functionality.
 
## Usage

To use Vyzon locally, follow these steps:

1. **Clone the repository** to your local machine using Git:
   `
   git clone https://github.com/Amanot-001/Vyzon.git
   `
2. **Change your current directory** to the cloned repository: ` cd Vyzon `
 
4. **Create a new Vyzon file** with your code in the main directory. Name the file with a .Vyzon extension, for example, yourfile.Vyzon.
  
6. To **run your Vyzon code**, execute the following command in your terminal: ` node run.js `

# Documentation


## Variable Declarations

In Vyzon, variables are declared using the `let` keyword. By default, when you declare a variable using `let`, it is initialized with a value of 0. For example:

```
let a;  // Variable 'a' is declared and initialized with the default value of 0
let b = 1;  // Variable 'b' is declared and initialized with the value 1
let c = 'Hello, World!';
```

## Data Types

Vyzon supports various data types, including `strings`, `numbers`, `true`, `false`, and `null`, to represent a wide range of values. 
For example:

```
let a = 'Hello, World!';
let b = 10;
let c = 10 + (10 * 3) + a;
let d = "Ok!";
let e = null;
let f = true;
let g = false;
```

## Build-ins
### Console Output
In Vyzon, you can print to the console using the `write()` function. 
Here are some examples:

```
let a = 'Anything';
write(a); 
write("abc");
write("write anything: ", a);
```
### String Operations

Vyzon provides string manipulation capabilities:

* **`.length` Property**: To find the length of a string, use the .length property. For example:
```
let a = 'abcd';
write(a.length); // This will print the length of the string.
```
* **String Indexing**: You can access individual characters within a string using square brackets. For instance:

``` 
let a = 'abcd';
write(a[0]); // This will print the first character 'a'.
```
## Conditionals

Vyzon supports conditional statements for decision-making in your code. You can use the `if`, `elif`, and `else` statements to execute different blocks of code based on specific conditions. Here's an example:

```
let x = 10;

if (x > 15) {
  write("x is greater than 15");
} elif (x > 5) {
  write("x is greater than 5 but not greater than 15");
} else {
  write("x is not greater than 5");
}
```

## Loops 

 Vyzon supports various loop types to suit your needs. You can use `for`, `while`, and `do while` loops to control the flow of your Vyzon programs by repeating code as needed.

 ``` 
write("Using the for loop:");
for (let i=0; i<10; i+=1) {
  write("Current value of i: ", i);
}

write("Using the while loop:");
let j = 0;
while (j < 5) {
  write("Current value of j: ", j);
  j = j + 1;
}

write("Using the do-while loop:");
let k = 0;
do {
  write("Current value of k: ", k);
  k = k + 1;
} while (k < 5);
```

## Functions

You can declare functions in Vyzon using the `def` keyword, followed by the function name and parameters enclosed in parentheses. The function body is defined in a block. To call a function, use its name followed by parentheses, passing any required arguments.

```
def greet(name) {
  write("Hello, " + name + "!");
}

greet("Yash"); // Calls the greet function with "Alice" as an argument.
```

## Operators 

* **Logical Operators:** 
  - The logical operators are the same as in other programming languages. Ex: `&&,||,!`
* **Relational operators:** 
  - The relational operators are the same as in other programming languages. Ex: `<, >, <=, >=, ==, !=`
* **Arithmetic operators:**
  - The arithmetic operators are the same as in other programming languages. Ex: `+, -, *, /, %, ^`
* **Assignment operators:**
  - Assignment operators are the same as in other programming languages. Ex: `=, +=, -=, *=, /=`

## Rules

1. Every statement in Vyzon should end with a semicolon `(;)` to indicate the termination of the statement.
2. Variable names in Vyzon should not start with a number.
3. All functions in Vyzon should be declared above their function calls.
