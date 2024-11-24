# Section 8 : Advanced Cascading Style Sheets
## Lesson 48 : CSS Display

```<span></span>``` Has a different value for the display property.  
These are some of the values for ```display: ;``` as pertains to the span.
 - ```block``` : Element takes up the full width of the browser window.
 - ```inline``` : They default to the width of their content and cannot be changed.
 - ```inline-block``` : Each element sits to the right so as long as there is browser window.
 - ```none``` : Effectively hides the span.

## Lesson 49 : CSS Float

Wrapping text using float and clear. Apply ```img {float left;}``` and the text will flow around the side of the image, looking more like print layout.

Unset the float property requires somethin like ```footer {clear: left;}``` so that it flows beneath the image and occupies the full width.

NOTE : float isnt used so much since there are newer, better ways to accomplish the same effect. Using Flexbox, Grid, Bootstrap.

## Lesson 50 : Responsive Websites

Note how modern web displays properly across all devices... This is accomplished in a couple ways, such as:  
 - ```Media Queries``` Uses ```@media (key: value) {CSS}``` to tell the browser to look in the subsequent curly braces for the styling to be applied.  
 - ```CSS Grid``` Create a grid container and additional divs that live inside that container to create the type of layout you wish.  
 Apply ```.c {display: grid;}``` to the top level container. Define columns and rows in CSS with ```grid-template```.  
 - ```Flexbox``` Similar to CSS Grid, but used more to create rows or columns. Apply ```.c {display: flex;}``` to the top level container.  
 - ```Bootstrap```: An external framework. built on top of flexbox.  

## Lesson 51 : Media Queries

Adding breakpoints to define responsive layouts.
Uses ```@media (max-width: 600px) {CSS}``` in CSS to denote any device that has a browser window of less than 600 pixels, to use the inline styling. Multiple break points can be added with the ```and``` keyword, separating breakpoints.  
Media queries can set the style for ```@media screen``` and ```@media print```.  

## Lesson 52 : PROJECT : Web Design Agency

Simple website for a web design agency.  

## Lesson 53 : Pep Talk : Dealing with Procrastination

Studies say procratination is a bit like an addiction. Do not feed the beast. Reward yourself *after* some amount of time. Work for a period, then take a short break.
