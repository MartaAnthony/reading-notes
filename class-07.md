## HTML tables

**Table** - represents information in a grid format, where each block is referred to as a table cell.

`<table>`  
`<tr>` table row  
`<td>` table data 
`<th>` table heading 

`colspan` attribute - indicates how many columns the cell should run across  

`rowspan` attribute - indicates how many rows a cell should span down the table   

`<thead>`  headings of the table   
`<tbody>` the body  
`<tfoot>` the footer   

## Functions, methods, and objects

The **new** keyword and the object constructor create a blank object.

*`var hotel = new Object();`*

*`var hotel = {};`* - curly brackets create empty object

*`hotel.name = 'Park';`* - updating or adding value

*`delete hotel.name;`* - deleting a property

*`hotel.name = '';`* - clearing the value of the property

**Object constructors** can use a function as a template for creating objects.

*`var quayHotel = new Hotel ('Quay', 40, 25);`*

When a function is created at the top level of a script, then it is in the **global scope** or **global context**.

Storing data:
- variables
- arrays
- individual objects
- multiple objects

Arrays are types of objects. They hold a related set of key/value pairs, but the key for each value is its index number. 
Arrays can store objects, and objects can store arrays.

**Built-in objects** - toolkit for creating interactive web pages. Browsers come with a set  of these objects that represent things like the browser window. They contain functionality commonly needed by many scripts.
1. Browser object model
2. Document object model
3. Global Javascript objects

