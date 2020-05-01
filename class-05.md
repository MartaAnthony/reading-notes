## HTML Images; CSS Color & Text

### HTML Images

Images should:
- be relevant 
- convey information 
- convey the right mood  
- be instantly recognizable    
- fit the color palette   

Keep images in a separate folder.   

`<img>` no closing tag

*Attributes:*  
* Src
* Alt
* Title
* Height
* Width

*Placement*:     
- before a paragraph  
- inside the start of a paragraph        
- in the middle of the paragraph
(you would use CSS for that)    

3 rules for creating images:     
- Save images in the right format
- Save images at the right size
- Measure images in pixels

**jpg** - color picture, photos   
**gif** and **png** - few colors, fat colors (logos, illustrations)    

The image should be saved at the same width and height that you want them to appear on the page.     

Resolution of the screen - number of pixels represented on the screen.     

For print, images should be saved at resolution of 300 dpi.    
For web, it is irrelevant.     

Vector images are resolution-independent.   
SVG format - Scalable Vector Graphics   

`<figure>` contains an image and its caption    
`<figcaption>` an image caption   

### CSS Color

Color 
Background-color.  

The color of every pixel on the screen is expressed in terms of a mix of red, green, and blue.    

Reducing the contrast a little bit improves readability.    

Opacity value of 0.0 to 1.0   

Hue - color, 0 to 360.  
Saturation - amount of grey in a color, percentage.  
Lightness / luminosity - amount of white or black in a color, percentage.   

*Hsl property*  
*Hsla* - hue, saturation, lightness, transparency(alpha - 0 to 1.0).    

### Text

*Typeface:*
- Serif  
- San-serif    
- Monospace   
- Cursive    
- Fantasy   

**Font stack** - you can specify more than one typeface an create an order of preference.     

Font-family   
Font-size   

The default size of a browser is 16 pixels     

[16 px is preferred]

Font-weight: bold or normal   
Font-style: italic, normal, oblique   
Text-transform: uppercase, lowercase, capitalize  
Text-decoration: none, unerline, overline. Line-through, blink  
Line-height - leading, vertical space between lines of text  
Letter-spacing.\  
(kerning - space between each letter)    
Word-spacing  
Text-align: left, right, center, justify  
vertical-align: baseline, sub, super, top, text-top, middle, bottom, text-bottom   
Text-indent 
Text-shadow   

*Styling links*:     
`:link`   
`:visited`    
`:hover`   
`:active`  
`:focus`   


