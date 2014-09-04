

Notes
--------------------------------------------------------


- raster - made of pixels

- vector - made of path and mathmathic formula, svg

- svg: scalable vector graphics
	- allows scalability on the web

- svg in responsive design: must delete the height and 		width for it to scale accordingly

- quirktools.com/screenfly, Adobe Shadow, Firebug, bradfrost.github

	- check responsiveness of site

- Adative-images.com
	- detects the visiotr's screen size and creates, caches, and delivers appropriate version of HTML images

- lte - lower than or equal, Explorer 8

- The picture element - officially proposed solution for delivering responsive inline raster images to the user

- viewport meta tag
	- is used in the head of the HTML page alongside media queries in the CSS to control the device's viewport size and scale. In its basic form, it will set the Smells Like Bakin' website up for cross-device compatibility. 

- http://gridulator.com/
	- a site that makes grids for you

- viewport sized typography
	- vw - viewport width, ... font-size: 1vw;
	- vh - viewport height
	- vmin - viewport min



Sites  
--------------------------------------------------------

- fittext.js

- lettering.js.com
	- adjust fonts according to screen size

- fitvids.js
	- creates a video that scales to screen

- styletile.es
	- create wire-frame for Photoshop 

- abookapart.com
	- mobile design first



Fluid Layout
---------------------------------------------------------

- fluid fondation
	- The key to a responsive website is building it on a fluid foundation. This defines our website layout in ratios and proportions rather than absolute values. Using the target ÷ context = result formula, we'll convert widths, margins, and padding from pixels to percentages. 

-Convert pixels to percentages formula 
	- target ÷ context = result

- Do not round up your percentages
	-  no matter how ugly or 	long the decimal is!

- Fixed websites
	-  have a set width and resizing the browser or viewing it on different devices won’t affect on the way the website looks.

- Fluid websites 
	- are built using percentages for widths. As a result, columns are relative to one another and the browser allowing it to scale up and down fluidly.

- Adaptive websites 
	introduce media queries to target specific device sizes, like smaller monitors, tablets, and mobile.

- Responsive websites 
	- are built on a fluid grid and use media queries to control the design and its content as it scales down or up with the browser or device.






HTML
---------------------------------------------------------

- viewport meta tag
	- <meta name="viewport" content="width=device-width, initial-scale = 1.0, user-scalable = no"> 

- svg, how to use it
	 <object data="img/love-at-first-bite.svg" type="image/svg+xml" alt="Love at First Bite">

- to use media query, include this in the head tag
	 <link rel="stylesheet" href="css/style.css" type="text/css" media="screen">


CSS
---------------------------------------------------------

media query
	@media screen and (max-width:705px){ .grid_1, .grid_2, .grid_3, .grid_4, .grid_5, .grid_6 { 
	  width: 100%; 
	  }
	.grid_2 img {
	    display: none;
	  }
  		-cause the grids to be 100%
  		-cause image to disappear











