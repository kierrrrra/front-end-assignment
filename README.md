##Front-End Position Assignment

###Task: Implement a page according to design

Mockups of design are in this repo, in .psd and jpeg formats.

As a data source, use JSONP from http://assets.airbnb.com/frontend/search_results.js. (thanks AirBnb for good example)
The JSONP callback is search_results.
Thumbnail Image, title, address and price are all in that JSONP. 

From here on, *“item”* is a box with rounded corners that has a background image and price on top of it.

####UI Interactions to implement:
* selecting of an item, what brings up the panel
* de-selecting of an item
* selecting of another item
* opening side menu upon clicking ‘hamburger’ (3 stripes on top left)
* closing of side menu
 
####Transition to implement:
* transition of the items up when item is selected
* transition of the info panel when item is selected
* transition of the info panel when item is de-selected
* transition of the info panel when another item is selected 
* transition of side menu from left side. Note that main content also shifts to right side, on half of the sidebar witdth
* transition of side menu into closed state

All transitions must be smooth on mobile device (Android/iOS) as well as desktop. Chrome is a browser of choice; no IE.

There is no vertical scrolling on the page; only horizontal scrolling is scrolling of items. Layout is oriented to be used on iPad screen (1024x768)

Stylesheet must be written with SASS

Font size and color can be loosely defined; but shadows must be sampled from designs.

####Plus points:
* (big one) Using AngularJS: one view and directive is enough
* Usage of promises
* Usage of Compass for border-radius, box-shadow and transition
* Hamburger icon is implemented not as an image or background image
* Media query to increase size of icons on mobile 
