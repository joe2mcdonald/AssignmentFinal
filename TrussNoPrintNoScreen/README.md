TRUSS NO-PRINT NO-SCREEN 
author: 
        "name": "Joseph McDonald - McDonald Media Production"
        "email": "joemcdonald@ymail.com"
=======
Truss No-Print No-Screen prevents the element that the class is attached to from being sent to the printer. 

### Operation:
------
**1. Create A Stylesheet For Print.
This will allow you to create custom CSS classes applied only at the time of print.

**2. HTML file
In the HTML <head> (see "truss-noprint-screen.html" file)
Put in the structure stylesheet file that controls the layout of the page and formatting of the content, with the media attribute set to "all".
Put the link to the print style sheet, with the media attribute set to "print" & "screen" , at the end of the list of stylesheets. 
-->	 

```html
<head>
<!-- Main stylesheet on top of the list of stylesheets - media="all" -->   
<link href="css/main-stylesheet-on-top-example.css" rel="stylesheet" type="text/css" media="all" >

<!-- Print only stylesheet, on bottom of the list of style sheets --> 
<link href="css/truss-noprint-noscreen.css"  rel="stylesheet" type="text/css" media="screen, print">
</head>
````html

**3. CSS file
Include the stylesheet "truss-noprint-noscreen.css" file in the css folder. 

**4. You should not feel constrained by the way I have built the initial code. 
If you disagree with how something that has been done, feel free to revise it for the needs of your particular site.
````
````