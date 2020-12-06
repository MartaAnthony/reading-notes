## TDD
from [*In Tests we Trust - TDD with Python*](https://code.likeagirl.io/in-tests-we-trust-tdd-with-python-af69f47e6932)

**TDD** - test-driven technology

- think about tests first   
- what is the smaller test that we can do against a function  
- the test name needs to be descriptive   
- separate tests folder from the production folder  

**Structure convention AAA** - Arrange, Act, and Assert    
**Arrange** - organize the data.    
**Act** - execute the code.   
**Assert** - check if the result is what you expected.   

**The Cycle**
1. Write a unit test and let it fail.   
2. Write the feature and make the test pass.  
3. Refactor the code.  

Think about software design first, and the code will be more reliable. 

## Recursion
from [*Recursion* at GeeksForGeeks](https://www.geeksforgeeks.org/recursion/)

**Recursion** - process in which a function calls itself directly or indirectly.  

In the recursive program, the solution to the base case is provided and solution for the bigger problem is expressed in terms of smaller problems.   
If the base case is not reached or not defined, the stack overflow may arise.   

**Direct recursion** - calls the same function, `fun`     
**Indirect recursion** - calls another function, `fun_new`    

The recursive program has greater space requirements than iterative program as all functions will remain in the stack until the base case is reached. It also has greater time requirements because of function calls and returns overhead.


