## Lists

- ordered lists \<ol> followed by \<li>, use numbers 
- unordered lists \<ul> followed by \<li>, use bullets 
- definition lists \<d1>, followed by \<dt> (the definition term) and \<dd> (the definition) 

*Nested lists* - you can put a second list inside an \<li> element.

## Boxes

CSS treats each HTML element as if it lives in its own box.  

Properties:  

*Width and height* - pixels, percentages and ems    
*Min-width, max-width*      
*Min-height, max-height*   

*Overflow* - tells the browser what to do when the content is larger than the box itself 
- hidden 
- scroll 

*Border* - separates the edge of one box from another.     
*Margin* - sits outside the edge of the border, you can create a gap between the borders of two adjacent boxes.    
*Padding* - space between the border of a box and any content contained within it. It can increase readability.     

*Border width*
- Thin 
- Medium 
- Thick  

*Border style* 
- Solid 
- Dotted  
- Dashed  
- Double   
- Groove 
- Ridge  
- Inset  
- Outset 
- hidden/none 

* Border color 

border: width style color;  
Border: 3px dotted blue;  

Centering content    
Text-align: center;  

*Display* - allows to turn an inline element into a block level element or vice versa  
- Inline  
- Block  
- Inline-block   
- none 

*Visibility*:   
- Hidden  
- visible  

*Border-image*    
*Box-shadow*    
*Border radius*    

## Decisions and loops   

**Switch statement** - starts with a variable called **switch value**. Each case indicates a possible value for this variable and the code it should run if the variable matches that value. At the end of each case is a break keyword.  

*Type coercion* - Javascript can convert data types behind the scenes to complete the operation  
*Weak typing* - the data type for a value can change  

**NaN (not a number)** - counted as a number   

**Falsy values** are treated as if they are false, can also be treated as a number 0    
**Truthy values** are treated as if they are true, can also be treated as a number 1 

**Unary operator** - returns a result with just one operand

**Loops** 
- For - if you need to run a code a specific number of times 
- While 
- Do While  

Initialization create a variable and set it to a 0, it’s called I and acts as a counter.    
Var I = 0;   
Condition - the loop should continue to run until the counter reaches a specified number.     
I <10;  
Update - every time the loop has run the statements in the curly braces, it adds one to the counter.   
i++. 



