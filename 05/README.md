# Section 5 : Intro to Cascading Style Sheets
## Lesson 32 : Why CSS

Styling for your webpages. Separates the styling from the content.  

## Lesson 33 : Adding CSS

There are three methods for adding a style sheet to your HTML. Inline, Internal, and External.  

**Inline:** Exists within the ```<html>``` tag.  *Not recommended.*  
```<html style="background: blue>```  

**Internal:** Exists within the ```<head></head>``` and uses its own tag ```<style></style>``` - which all CSS resides inside. The selector comes before a set of curly braces, the CSS goes inside the curly braces.
```<style> html {background: blue;} </style>```  
Less than ideal for sites with multiple pages.

**External:** Exists as a separate file which contains the CSS. One entry per tag and a tag may have multiple styles. ```html {background: blue;}``` Include the CSS file name - usually ```styles.css``` in the HTML ```<head>``` section.  
```<link rel="stylesheet" href="./styles.css" />```  
 
## Lesson 34 : CSS Selectors

Selector is the part outside the curly braces that matches the HTML element.  
Selector {Property : Value}  ```h1 {color:blue}```  

A **class selector** is a bit different. Its selector begins with a ```.```
Classes can be added to html elements : ```<h2 class="red-text">```  
All class selectors style the same across HTML elements, if those elements have the same class attribute.

An **id selector** is similar. Its selector begins with a ```#``` However, id's are unique, whereas you can style multiple classes. As with classes, id's can be added to html elements : ```<h2 id="main">```  

The **attribute selector** is yet another selector that applies to an HTML element's attribute. If a ```<p >``` has an attribute, the CSS will style all elements that contain that attribute ```p[draggable]{color:red}```  
This can be taken further by selecting the value that you want the CSS to apply to. ```p[draggable=false]{color:red}```

The **universal selector** applies to all HTML elements and is denoted thusly. ```* {color:black}```

## Lesson 35 : PROJECT : Color Vocabulary

Oh. The same lesson from 100 Days of Python. I'll just recycle my code. :P

## Lesson 36 : TIPS : Dealing with Distractions

PEP TALK : Stay focused. 

## Lesson 37 : Join the Student Community

Plug for Discord server. Na. Thanks.
