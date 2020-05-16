## JS Debugging

To find the source of an error, it helps to understand in what order scripts are processed. Some tasks cannot complete until another statement or function has been run.

**Execution context**    
- global context    
- function context   
- eval context   

**Variable scope**:     
- global scope   
- function-level scope     

**The stack** - The JavaScript interpreter processes one line of code at a time. When a statement needs data from another function, it stacks the new function on top of the current task.   

**Error objects**    
`SyntaxError` - incorrect use of the rules of the language.    
`ReferenceError` - caused by a variable that is not declared or is out of scope.    
`EvalError` - incorrect use of aval() function.   
`URIError` - incorrect use of URI function.   
`TypeError` - trying to use an object  or method that does not exist.   
`RangeError` - if you call a function using numbers outside of its accept range.    

**Debugging workflow**
- Breakpoints   
- Break down parts of the code to test smaller pieces of functionality    
- Check the number of parameters for a function, or the number of items in an array    

Use browser dev tools.       

`Console.log()`   

**Breakpoints** - you can pause the execution of a script on any line using breakpoints.    

**Stepping through code** - if you set multiple breakpoints, you can step through them one by one to see where values change and a a problem might occur.    

*Try, catch, finally*   

Debugging tips:    
- try another browser   
- write numbers to the console   
- remove parts of the code  
- explain the code   
- google it   
