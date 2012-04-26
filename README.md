#Fullscreen Background - jQuery plugin


Fullscreen background is a small jQuery plugin that allows you to create fullscreen background.

[Article on Gaya Design](http://www.gayadesign.com/diy/jquery-plugin-fullscreen-background/)

[View the demo page](http://gayadesign.com/scripts/fullscreenbackground/)

---

##How to use:

1. Include jQuery on your webpage

2. Have the following structure in your HTML:

		<div class="content">
			Content goes here
		</div>
		<div id="background-image">
			<img src="path/to/img.jpg" alt="" width="800" height="600" />
		</div>

3. Then, in your CSS. Make sure the content is absolute and has a higher z-index than 1.

4. Add the following line you Javascript file:

		$("#background-image").fullscreenBackground();

5. DONE!

There are also a few options available:

`selector` (default: "img")<br />
The selector that will be used when digging through the element you're calling the function on.

`fillOnResize` (default: true)<br />
Set to true if the image has to resize to the screen if the screensize changes. I think most will leave this set to `true`.

`defaultCss` (default: true)<br />
Set to true if you want to add some standard CSS to the elements. If you are experiencing problems you can set this to false and do the CSS in your own stylesheet.