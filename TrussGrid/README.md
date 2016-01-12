TRUSS GRID TEMPLATE 
author: 
        "name": "Joseph McDonald - McDonald Media Production"
        "email": "joemcdonald@ymail.com"
=======
A grid template that shows grids for 4 different column variations: 16, 12, 6, 4. 
And 6 different major breakpoints for each:
   Large Desktop Layout - 1200px to 1920px,  
   Tablet Landscape and Desktop Layout - 960px to 1199px, 
   Tablet Portrait Layout - 768px to 959px, 
   Mobile Landscape Layout - 480px to 767px,   
   Mobile Portrait Layout - 422px to 479px,
   Small Portrait Layout - 250px to 421px

### Operation:
------
**1. Use the Truss-Grid.html as a starting point. 
The Truss-Grid.css contains the grid dimentions as percentages.  
Besure the CSS files (normalize.css and Truss-Grid.css) are in the html. 
To use these files, simply include the css files in the `<head>` of the HTML page.
```html
<head>
	<link  href="css/normalize.css" rel="stylesheet" type="text/css" media="all">
	<link href="css/Truss-Grid.css" rel="stylesheet" type="text/css" media="all">
</head>
````html
**2. Run the Truss-Grid.html file inorder to view the different variations of columns and the breakpoints when the browser is resized.  
Modify the HTML file and choose the matching <div> 'trussGridContainer' classes that you need. 
Remove the remaining html <div> 'trussGridContainer' classes that you don't need. 
Remove the html <div> 'row' classes that you don't need. 
**3. It is not necessary to modify the CSS file. 
However you may, if desired remove any layouts that don't pertain to your site. 
By removing the layout code according to the breakpoints & columns blocks of code, that you don't need.
**4. These styles do not automatically make up a finished site design. 
They are simply a starting point, ideally for rapid prototyping or as a basis for creating your own designs. 
You should not feel constrained by the way I have built the initial code. 
If you disagree with how something has been done, feel free to revise it for the needs of your particular site.
````
````