# Do While Loop
Do While Loop is similar to while loop with only difference that it checks for condition after executing the statements, and therefore is an example of Exit Control Loop.  The do/while statement creates a loop that executes a block of code once, before checking if the condition is true, then it will repeat the loop as long as the condition is true.

**The do/while statement is used when you want to run a loop at least one time, no matter what.**

## Syntax:
```javascript
do
{
    statements..
}
while (condition);
```
* Do while loop starts with the execution of the statement. There is no checking of any condition for the first time.
* After the execution of the statements, and update of the variable value, the condition is checked for true or false value. If it is evaluated to true, next iteration of loop starts.
* When the condition becomes false, the loop terminates which marks the end of its life cycle.
* It is important to note that the do-while loop will execute its statements atleast once before any condition is checked, and therefore is an example of exit control loop.

### Example
```javascript
<script type = "text/javaScript"> 
// JavaScript program to illustrate do-while loop 
  
    var x = 21; 
  
    do 
    { 
        // The line while be printer even 
        // if the condition is false 
        document.write("Value of x:" + x + "<br />"); 
  
        x++; 
    } while (x < 20); 
  
< /script>
```

### Output:
```
Value of x: 21
```
