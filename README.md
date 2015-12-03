# jSlideAccordion
A Plugin for Jquery the generates a nice smooth Accordion with some options

## Usage

$([selector]).createSlide(options)

The options Container can contain the following options
 * onlyOneOpen => true/false defines if multiple containers can be opened at the same time (default => true)
 * slidetime => the jqSlidetime (default = 400)
 * groupclass => Name of the class that the onlyOneOpen Option checks against (default="sliderAdded")
 * subcontainer => the selector of the collapsible container (default='p')
 * startOpened => true/false if the first entry should be opened or not (default=false)
 
 Example with defaults:
 ```javascript
 {
     onlyOneOpen: true, 
     slidetime: 400, 
     groupclass: 'sliderAdded', 
     subcontainer: 'p',  
     startOpened: false
 }
```
