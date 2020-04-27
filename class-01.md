## Structure

HTML is made up of **elements**, which are made up of two **tags**. Tags are the containers of information that lies in between. **Attributes** provide additional information about the contents of an element, and are made up of a **name** and a **value**.

\<body> what’s inside the browser window.   
\<head> information about the page.  
\<title> on the tab of the page. 

## Extra Markup

\<!DOCTYPE html> HTML version.  
\<! - -   - - > comment.  

**Id attribute** - to identify that element from other elements on the page; global attribute (can be used on any element).   
**Class attribute** - to identify several elements as being different from the other elements. 

**Block elements** start on a new line in the browser window: \<h1>, \<p>, \<ul>, \<li>.   
**Inline elements** continue on the same line: \<a>, \<b>, \<em>, \<img>. 

\<div> - to group a set of elements together in one block-level box. 
\<span> - acts like an inline element of \<div>. 

\<iframe> - inline frame, a window inside a page where you can see another page; for example to embed a Google Map. 

Iframe attributes:  
- src   
- height   
- width   
- scrolling (not supported in HTML5)   
- frame border (not supported in HTML5)   
- seamless   

\<meta> - information about the page.   
meta attributes:   
- description 
- keywords (no longer has any effect)  
- robots  
- author  
- pragma  
- expires   

**Escape characters**   
&copy  copyright symbol   
&lt  left angled bracket  
More - p. 194 and http://htmlandcssbook.com/extras/html-escape-codes/

## HTML5 Layout

Instead of \<div> with ids and classes -> \<nav>, \<aside>, \<article>, \<header>, \<footer>, \<section>, \<hgroup>, \<figure> - help describe the structure of the page.  

## Process Design

Understand target audience   
Motivations and goals   
Key information they need   
How often will they visit    

Create a site map - structure of a site.  
Card sorting - technique used to  decide what information should go on each page.  
Wireframes - sketch of the key information that needs to go on each page.  
Visual hierarchy - focus on key messages and guide attention.  
Grouping related content into blocks or chunks - makes the page look simpler and easier to navigate.  
Similarity - associating certain style with specific type of content.  

## ABC of programming

**Script** - a series of instructions that a computer can follow to achieve a goal

*Writing a script*: 
- Define a goal 
- Design the script 
- Code each step 

Solving problems **programmatically** - following series of instructions

*Flowcharts*:
- Event  
- Generic step   
- Input or output  
- Decision   

**Objects** can have:    
- **Properties**  
- **Events**      
- **Methods**   

Each property has a name and a value.

Events can trigger a specific section of the code.

Method represent how people interact with an object. They can contain a lot of instructions that represent a task.

Events can trigger methods, and methods can retrieve or update an object’s properties.

Web browsers - programs built using objects

**Interpreter** - part of the browser that takes instructions (in JavaScript) and translates them into instructions the browser can use to achieve the tasks you want it to perform.

**Progressive enhancement:**   
- HTML - content layer     
- CSS - presentation layer    
- JavaScript - behavior layer     
-> each should be stored in a separate file

