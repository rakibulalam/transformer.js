# transformer.js

**Description:** Its image slider plugin based on jQuery

 * jQuery image slider Plugin
 * Copyright (c) 2011 http://cameopix.com/
 * Version: 1.0.11 (22-07-2011)
 * Dual licensed under the MIT and GPL licenses:
 * http://www.opensource.org/licenses/mit-license.php
 * http://www.gnu.org/licenses/gpl.html
 * Requires: jQuery v1.2.6 or later
 
# Demo :

![alt tag](https://github.com/rakibulalam/puzzle.js/blob/master/snapshot.jpg)

http://cameopix.com/puzzle/
# Documentation
#JS
```javascript
$(document).ready(function(){
   $('#gellery').transformer({
			__Effects:new Array('Optimus','Ironhide','Scorponok','Megatron','Starscream','Jazz'),	
			__Columns:7,
			__Rows:3,
			__Speed:10000,
			__Title_Height:100,
			__Title_Width:0,
		});
)};
```
#CSS
```CSS
#ImageSlider
		{
		height:380px;
		width:800px;
		text-align:left;
		}
	#gellery
		{
		height:380px;
		width:800px;
		text-align:left;
		position:absolute;	
		}
	 #ImageSlider #loader
		{
		background:url(bannerimage/loading_animated.gif) no-repeat;
		height:65px;
		width:65px;
		margin-top:150px;
		margin-left:355px;
		position:absolute;
		z-index:400;
		}
	#gellery DIV
		{ 
		position:absolute; 
		overflow:hidden;
		height:428px;
		width:981px;
		text-align:left;
		display:none;
		}
	#gellery IMG
		{
		position:absolute;
		height:380px;
		width:800px;
		text-align:left;
		}
```
#Html
```HTML
  <div id="ImageSlider">
    	<div id="gellery">
    		<div><img  src="bannerimage/harrypotter.jpg"><p>Title</p></div>
    		<div><img src="bannerimage/inception.jpg"><p>Title</p></div>
    		<div><img src="bannerimage/transformer.jpg"><p>Title</p></div>											
    	</div>
  </div>
```
