
## HTML Links

`<a>`   
`<a href=‘http://www.imdb.com">IMDB</a>`

**Absolute URLS** - starts with a domain name   
**Relative URLs** - domain doesn’t need to be specified; link to other pages of the same site  

**Directories** - folders on a website with code for different pages 
**Root folder** - top-level folder

`Index.html` - main homepage of a site

`mailto:` - starts up a user’s email program and addresses an email to a specified email address  
`<a href=“mailto: jon@example.org"Email Jon</a>`   

`Target=“_blank”` - opening links in a new window  

Linking to a specific part of the same page - `<a href=“#id>Top</a>`   

## CSS Layouts

CSS treats each HTML element as if it is in its own box. This box will either be a **block-level** box or an **inline** box.   

**Containing element** - if one block-level element sits inside another block-level element.   

*Positioning schemes*    
- Normal flow - every block-level element appears on a new line.  
- Relative positioning - one elements is shifted, the other ones stay in normal flow.  
- Absolute positioning - positions the element in relation to its containing element (in scrolling).  
- Fixed positioning - positions the element in relation to the browser window.  
- Floating elements - taking the element out of normal flow and position it to the far left or right of a containing box, the element becomes a block-level element around which other content can flow.   

## Functions, methods and objects

**Functions** - a series of statements that have been grouped together because they perform a specific task. You can reuse the function.   
**Methods** - same as functions, but created inside an object     

Functions can store the information to use later. Asking the function to perform a task is **calling the function**.    
**Parameters** - pieces of information passed to a function. Parameters work like variables.   
**Return a value** - an answer provided by running a function.   
**Function declaration** - giving it a name and writing the statement needed to achieve a task inside the curly braces.   
`Function sayHello() {  
Document.write(‘Hello!’);  
}`  

Calling the function: `sayHello();`

You can call the function before declaring it.     
When you call a function, you specify the values it should use in the parenthesis. The values are called **arguments**.       

Some functions return information to the code. They can also return more than one value using an array.    

**Anonymous function** - function with no name    

IIFE - Immediately Invoked Function Expressions   
- used for code that only needs to run once within a task   

*Variable scope*   
- local scope (function-level scope) - when a variable is created inside a function and can only be used in that function   
- global scope - when the variable is created outside the function and can be used anywhere; they take up more memory   

## Pair programming 
- two programmers sharing one workstation, Navigator and Driver



