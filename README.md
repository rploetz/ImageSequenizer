ImageSequenizer.js
=======================

An object oriented way to create a PNG/JPG sequnce of images and animate them in order.  

Features:
* Sequences can loop

* Can auto start or start when you choose to start the animation

* Can create a unique ID attribute

* Set the FPS

* Create a callback function when the sequence has completed

Requires JQuery 1.8.2 Minimum

** How to use this library **

// create a new image sequenizer

var img = new ImageSequenizer(this.imageStartSequenceName , ".png", 140, false, true, 30, 'tag-name', function(){ console.log("callback!");});
 
// attach the created image tag to your DOM.

img.getElement().appendTo($('#foo'));