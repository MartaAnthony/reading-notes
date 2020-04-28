# HTML Text, CSS Introduction, and Basic JavaScript Instructions


## HTML Text

Headings \<h1>, \<h2>, \<h3>, \<h4>, \<h5>, \<h6>   
Paragraphs \<p>   
Bold \<b>  
Italic \<i>   
Superscript \<sup>  2 to the second power  
Subscript \<sub> h2o   
Line breaks \<br />   
Horizontal rule \<hr />   
Strong \<strong>   
Emphasis \<em>   
Longer quote \<blockquote>   
Short quote within the paragraph \<q>   
Abbreviation \<abbr>   
Citation \<cite>     
Definition \<dfn>   
Contact details of the author \<address>    
Inserted content \<ins>   
Deleted content \<del>  
No longer relevant \<s>   

When to use bold versus strong
When to use italic versus emphasis

## Links

Links allow to move around on the web.

Example:   
\<a href=“http://www.imdb.com">IMDB</a>  

**URL** - Uniform Resource Locator  
* **absolute URL** - starts with domain name for the site and can be followed by the path to the specific page
* **relative URL** - no domain name is necessary, before they link to a page within the same website

Email links.   
*Mailto:* 
\<a href=“mailto:jon@example.org">Email Jon</a>  

*target=“_blank”* - opens a link in a new window
\<a href=“http://www.imdb.com" target=“-blank”>

To link to a specific part of the same page, you can use **id attributes**.

## Basic Javascript Instructions

**Statement** - individual instruction or step, ends with a semicolon, each starts on a new line. 
Statements can be organized into code blocks, they are then surrounded by *curly braces*.  
JavaScript is case sensitive.

**Comments** - make your code easy to read and understand.   
Multi-line \/* */  
Single-line \//

**Variable** 
You can store bits of information script needs to do its job in a variable. The data stored in a variable can change each time a script runs.  
*Declaring the variable* - creating the variable and giving it a name.  
var quantity;   
*Assigning a value to the variable* - telling the variable what information you would like it to store.  
quantity = 3;  

Data types:
* Numeric data type - 0.75  
* String data type - ‘Hi, Ivy!’   
* Boolean data type - true or false  

To use quotes inside of a string, use *escape symbols*.   

Booleans are used when the code can take more than one path.   

Naming variables:   
- must begin with a letter, dollar sign, or an underscore
- can’t start with a number
- can’t use a dash (-) or a period (.)
- can’t use keywords or reserved words, like var, null, abstract, boolean, if, for, else
- use a name that describes the kind of information that the variable stores
- if using more than one word, use a capital letter for the the first letter after the first word

**Array** - special type of variable, storing a list of values. Each item in an array is automatically given a number called an index. The numbering starts at zero.   

**Expression** - evaluates into a single value. 
* Expressions that assign value to a variable, var color = ‘beige’;
* Expressions that use two or more values to return a single value, var area = 3 * 2;   

**Operators** - allow to create a single value from one or more values. 
* Assignment   
* Arithmetic 
* String 
* Comparison 
* Logical 

## Decision and Loops

**Evaluations** - you can analyze values in your scripts to determine whether or not they match expected results. 
**Decisions** - using evaluations, you can decide which path your script should go down.   
**Loops** - when you want to perform the same set of steps repeatedly.  

*Evaluating condition* - testing or checking of a condition. 
* \== is equal to 
* \=== strict equal to 
* \!= is not equal to  
* \!== strict not equal to 
* \> greater than 
* \< less than   
* \>= greater than or equal to 
* \<= less than or equal to  

**Operand** - placed on each side of the operator, can be values or variables, can be a whole expression. 

Logical operators"
* && logical AND
* || logical OR
* ! Logical NOT

**If statements** - if the condition evaluates to true, the code bloc is executed.  
**if…else statements** - if it resolves to true the first code block is executed, if it resolves to false the second block is run
