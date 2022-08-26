# While Loops

A while loop is a control flow statement that allows code to be executed repeatedly based on a given Boolean condition. The while loop can be thought of as a repeating if statement. Once the expression becomes false, the loop terminates.

**The while loop is primarily used when the number of iterations in not known in advanced and the iterations are based on some boolean condition.**

## Syntax:
```javascript
while (boolean condition)
{
   loop statements...
}
```
* While loop starts with the checking of condition. If it evaluated to true, then the loop body statements are executed otherwise first statement following the loop is executed. For this reason it is also called **Entry control loop.**
* Once the condition is evaluated to true, the statements in the loop body are executed. Normally the statements contain an update value for the variable being processed for the next iteration.
* When the condition becomes false, the loop terminates which marks the end of its life cycle.

### Example:
```javascript
<script type = "text/javaScript">
// JavaScript program to illustrate while loop 
  
    var x = 1; 
  
    // Exit when x becomes greater than 4 
    while (x <= 4) 
    { 
        document.write("Value of x:" + x + "<br />"); 
  
        // increment the value of x for 
        // next iteration 
        x++; 
    } 
  
< /script>
```

### Output:
```
Value of x:1
Value of x:2
Value of x:3
Value of x:4
```
