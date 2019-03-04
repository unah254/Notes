# keywords
- let: Block in which the variable is declared: it's usually used in a for loop for incrementing the iterator
- const: Block in which the variable is declared(it's constant, never going to receive a new value)

- The variables assigned using `const` are read-only which means that once they are initialized using `const`, they cannot be reassigned.

# Rules of Thumb:
- Don’t use var, because let and const is more specific
- Default to const, because it cannot be re-assigned or re-declared
- Use let when you want to re-assign the variable in future
- Always prefer using let over var and const over let

# Operators

1. Binary Operators -Comprises of:
   - arithmetic operators i.e (+,−,∗,/) e.g `console.log("2 + 3 = " + (2 + 3))`
   - Assignent operators i.e (=, +=, -=,*=)
   - Logical operators (&&, ||, !)

# Arrow Functions

![](relative/path/to/arrowfunc.png?raw=true "Title")

# Exports and Imports

![](relative/path/to/exportsimports.png?raw=true "Title")

![](relative/path/to/defaultnamedexport.png?raw=true "Title")

# Classes

- Can have both methods(functions attached to classes) and properties(variables attached to classes)
- More of like better way of constructor usage
- Inheritance i.e class grace extends unah<br>
  When using Inheritence, a keyword `super` is used which simply executes the parent constructor<br>

# Spread and rest Operator
- spread is used to split up array objects.
- Rest is used to merge a list of functional arguments.

e.g 
```
        const numbers = [1,2,3,4];
        const newNumbers = [ ...numbers, 5];
        console.log(newNumbers);
```

![](relative/path/to/operators.png?raw=true "Title")


# Destructuring

- Allows you to pull out single elements or object properties and allows you to store them in variables.

![](relative/path/to/Destructuring.png?raw=true "Title")

# Reference and primitive Types

- Primitive types are the numbers, strings and values
```
   const number = 1;
   const num2 = number;
```
- Reference types are objects and arrays
```
const person = {
    name='grace'
};
const secondPerson = person;
person.name = 'unah';
```

# Array Functions
- map is a built in array method 
- They take a function as an input, which is executed on each element in the array.

```
const number = [ 1,2,3];
const doubleNumber = number.map((num) => {
     return num*2
});
console.log(doubleNumber);
