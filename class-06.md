## Object Literals

**Object** - groups together a set of variables and functions to create model of something you would recognize from the real world.   
**Property**- variable that is a part of an object.   
**Method** - function that is a part of an object.   

You access the properties or methods of an object using dot notation.     
-> `var hotelName = hotel.name`

## Document object model

**DOM** - specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.   
DOM tree (DOM model) is made of objects.

DOM = **API** - Application Programming Interface     
User interfaces let humans interact with programs. 

DOM tree consists of 4 main types of nodes:     
- document node   
- Element nodes  
- Attribute nodes   
- Text nodes  

**DOM queries** - methods that find elements in the DOM tree. When you need to work with an element more than once, you should use a variable to store the results of this query.
You can store the location of the element within the DOM tree in a variable. 

**NodeList** - collection of nodes   
Each node is given an index number.     
NodeLists are not arrays, they are collections.       
NodeLists can be live or static.    
You can loop through each node in the collection and apply the same statements to each. 

Traversing the DOM:    
- parentNode    
- previousSibling     
- nextSibling   
- firstChild  
- lastChild    

*Most browsers treat whitespace between elements as a text node, which can cause problems.*

How to access / update element content.   
`nodeValue` - access text from node   
`innerHTML` - gets.sets text & markup *(security issues)*  
`textContent` - gets/sets text only  
`innerText` - gets/sets text only *(doesn’t work in Firefox)*

Adding elements using DOM manipulation.     
`createElement()`  
`createTextNode()`   
`appendChild()`  

**XSS** - Cross-Site Scripting attacks - attacker placing malicious code into a site
