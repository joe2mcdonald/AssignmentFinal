jQuery - back2TheTop()
=======
A simple customizable plugin for scrolling BACK 2 THE TOP of page.

### Setup:
------
**1. Include JS files (jQuery = 1.11.3 and back2TheTop.js)**
````html
<script src="js/jquery.1.11.3.min.js"></script>
<script src="js/jquery.back2TheTop.js"></script>
````

**2. Include CSS (modify to your needs)**
````css
#back2TheTopId {
	display: none;
	position: fixed;
	cursor: pointer;
	  
/* modify below css to your needs */
	width: 35px;
	height: 35px;
	bottom: 40px;
	right: 20px;
}
````


**3. Include HTML**
````html
 <div id="back2TheTopId"></div>
````

**4. Call method back2TheTop() on element**
````javascript
 $("#back2TheTopId").back2TheTop();
````

### Options:
------

| Option      | Value            | Desciption                         |
| :-----------|:-----------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------|
| shownAt    | Integer (px)     | Where scroll image should show based on scrollbar's vertical position. (higher the number, the longer it takes for scroll image to appear) `default: 150` |
| fadeSpeed   | Integer (ms)     | Control 'Fade' effect speed for scroll image. `default: 200` |
| scrollSpeed | Integer (ms)     | Control speed when animation scrolls up. `default: 200` |
| arrowImage  | String (image)   | Selects the Arrow Image. Image names: white, black, red, grey, green, round-blue, round-green, round-orange, round-grey, round-corner-grey, round-corner-black, round-broken-line. `default: round-broken-line` |

````javascript
$("#back2TheTopId").back2TheTop({
	shownAt: 150,
	fadeSpeed: 200,
	scrollSpeed: 200,
	arrowImage: 'round-broken-line'
});
	
````