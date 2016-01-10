TRUSS CLEARFIX 
author: 
        "name": "Joseph McDonald - McDonald Media Production"
        "email": "joemcdonald@ymail.com"
=======
Truss Quick Float, helper classes that pulls the float to the right or left.


### Operation:
------
**1. Stylesheet For Truss Quick Float.
Either use the truss-quickfloat.css stylesheet or add the CSS Truss Quick Float code in your own stylesheet.

**2. HTML file
In the HTML <head> 
Put in the link to the truss-quickfloat.css stylesheet file or your own css stylesheet that contains the CSS truss quick float helper classes.
Specify the class names - class="tfloat-right" and / or class="tfloat-left"- in you HTML container. 
See the html example below.
-->	 
```html
<head>
<!-- Truss Quick Float stylesheet --> 
<link href="css/truss-quickfloat.css"  rel="stylesheet" type="text/css" media="all">
</head>

<body>
<div class="tclearfix">				                  <!--   clears the floats    -->
  <div class="tfloat-left">..Float to the left..</div>
  <div class="tfloat-right">..Float to the right..</div>
</div>
/body>
````html

**3. CSS file
Include the stylesheet "truss-quickfloat.css" file in the css folder or put the code in your own css stylesheet file. 

**4. You should not feel constrained by the way I have built the initial code. 
If you disagree with how something that has been done, feel free to revise it for the needs of your particular site.
````
````