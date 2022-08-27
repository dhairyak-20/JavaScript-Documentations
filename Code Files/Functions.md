# Functions
Functions are one of the fundamental building blocks in JavaScript.

* A function is a JavaScript procedure—a set of statements that performs a task or calculates a value.
* A JavaScript function is a block of code designed to perform a particular task.
* A JavaScript function is executed when “something” invokes it (calls it).
---
## Syntax:
```javascript
function name(parameter1, parameter2, parameter3) {
    code to be executed
}
```

* Function parameters are listed inside the parentheses () in the function definition.
* Function arguments are the values received by the function when it is invoked.
* Inside the function, the arguments (the parameters) behave as local variables.
---
## Function Invocation:
The code inside the function will execute when “something” invokes (calls) the function:
* When an event occurs (when a user clicks a button)
* When it is invoked (called) from JavaScript code
* Automatically (self invoked)
---
## Function Return:
When JavaScript reaches a return statement, the function will stop executing. If the function was invoked from a statement, JavaScript will “return” to execute the code after the invoking statement. Functions often compute a return value. The return value is “returned” back to the “caller”:

```javascript
var x = myFunction(4, 3);    // Function is called, return value will end up in x

function myFunction(a, b) {
    return a * b;            // Function returns the product of a and b
}
```

#### Output:
```
12
```
#### Example 2:
```javascript
/*Q1) write a function to add 2 numbers and print the result */
			function addNumber(a , b)
			{
				
				var total = a+b;
				return total;
			}
			var output = addNumber(4,2); // function call
			document.write("<h1>The total is : "+output+"</h1>");
```
#### Output:
```
The total is : 6
```
