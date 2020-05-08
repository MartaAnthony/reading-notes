## CSS Layout

Each element is a box:   
- block-level box   
or   
- inline box  

Positioning schemes:    
- normal flow, `position: static;`
- relative positioning, `position: relative;`
- absolute positioning, `position: absolute;`
- fixed positioning, `position: fixed;`
- floating elements, `float`

When you move any element from normal flow, boxes can overlap. The **z-index** property allows to control which box appears on top.   

`Z-index` - stacking content   

`Clear` - allows to say that no element should touch the left or right-hand sides of a box    

Layouts:     
- fixed width layouts - don’t change size as the user increases or decreases the size of their browser window   
- liquid layouts - stretch and contract as the user increases or decreases the size of their browser window   

960 pixel grid -> widely used by web designers    

**CSS framework** - the code for common tasks, such as creating layout grids, styling forms, creating printer-friendly versions of pages, etc
960.gs.   
