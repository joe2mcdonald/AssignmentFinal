Three Tier Fixed Navigation Bar
=======
A three tier fixed-position top navigation bar that remains visible while the user scrolls the page. 

### Setup:
------
**1. Include CSS files (normalize.css and style.css) 		
	<link  href="css/normalize.css" rel="stylesheet" type="text/css" media="all">
	<link href="css/style.css" rel="stylesheet" type="text/css" media="all">

**2. Include HTML Navigation Bar (modify to your needs)**
````html
Change the anchor tag description for the item and include any necessary href links.
Class: right, left, down are for the direction of arrow image. 	
Class last is for the operation of left flyout.	
When adding list items to navbar besure to include any required classes. 	
Removing list items should not need any modification to css. 

<nav id="navBarId">
	<ul>
		<li><a  class=" down" href="index.html">Menu1</a>
			<ul>	
				<li><a class="right" href="#" >Menu11</a>
					<ul>
						<li><a href="#">Menu111</a></li>
						<li><a href="#">Menu112</a></li>
						<li><a href="#">Menu113</a></li>
						<li><a href="#">Menu114</a></li>
					</ul>
				</li>
			</ul>
		  </li>
		<li><a  class=" down" href="#">Menu2</a>
			<ul>
				<li><a href="#">Menu21</a></li>
				<li><a href="#">Menu22</a></li>
				<li><a href="#">Menu23</a></li>
				<li><a  class="right" href="#">Menu24</a>
					<ul>
						<li><a href="#">Menu241</a></li>
						<li><a href="#">Menu242</a></li>
					</ul>
				</li>
				<li><a href="#">Menu25</a></li>
				<li><a href="#">Menu26</a></li>
				<li><a href="#">Menu27</a></li>
			</ul>
		</li>
		<li><a class=" down" href="#">Menu3</a>
			<ul>
				<li><a class="right" href="#">Menu31</a>
					<ul>
						<li><a href="#">Menu311</a></li>
						<li><a href="#">Menu312</a></li>
						<li><a href="#">Menu313</a></li>
						<li><a href="#">Menu314</a></li>
					</ul>
				</li>
				<li><a  class="right"  href="#">Menu32</a>
					<ul>
						<li><a href="#">Menu321</a></li>
						<li><a href="#">Menu322</a></li>
						<li><a href="#">Menu323</a></li>
						<li><a href="#">Menu324</a></li>
					</ul>
				</li>
				<li><a class="right" href="#" >Menu33</a>
					<ul>
						<li><a href="#">Menu331</a></li>
						<li><a href="#">Menu332</a></li>
						<li><a href="#">Menu333</a></li>
						<li><a href="#">Menu334</a></li>
					</ul>
				</li>
				<li><a href="#">Menu34</a></li>
				<li><a href="#">Menu35</a></li>
				<li><a href="#">Menu36</a></li>
			</ul>

		</li>
		<li class="last"><a class="down" href="#">Menu4</a>
			<ul>
				<li><a href="#">Menu41</a></li>
				<li><a href="#">Menu42</a></li>
				<li><a  href="#" class="left">Menu43</a>
					<ul>
						<li><a href="#">Menu431</a></li>
						<li><a href="#">Menu432</a></li>
						<li><a href="#">Menu433</a></li>
						<li><a href="#">Menu434</a></li>
						<li><a href="#">Menu435</a></li>
					</ul>
				</li>
				<li><a href="#">Menu44</a></li>
			</ul>
		</li>
	</ul>
</nav>			

````

**3. Include Optional Embedded CSS (modify to your needs), see table below.
````CSS
/*  CAN CHANGE THE DEFAULT ITEM COLORS */		
/*  SETS ALL LIST ITEM COLOR  */		
	#navBarId ul li a {
		background: #888888;
		border-top: 2px solid #999999;
		border-right: 2px solid #333333;
		border-bottom: 2px solid #333333;
		border-left: 2px solid #999999;	
		}
		
/*  SETS HOVER OR FOCUS ITEM COLOR  */		
	#navBarId ul li a:hover,
	#navBarId ul li a:focus {
		background: #aaaaaa;
		border-top: 2px solid #777777;
		border-right: 2px solid #cccccc;
		border-bottom: 2px solid #cccccc;
		border-left: 2px solid  #777777;
}

| Option      |    Desciption                                                                       | Type         | Default            | :-------------|:------------------------------------------------------------------------------------|:-------------|--------------------|  
| background  | Background color, image, repeat, attachment and position values.                    | String (hex) | #888888 and #aaaaaa|
|border-'side'| Border width, style and color values for a specific side: top, right, bottom, left.	| String       |                    |
````
````