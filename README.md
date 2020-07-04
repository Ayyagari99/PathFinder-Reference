# PathFinder-Reference (Samajhne kelie!)


 JQUERY BASICS: PEHLE YE PADHLENA!
The jQuery syntax is tailor-made for selecting HTML elements and performing some action on the element(s).
Basic syntax is: $(selector).action()
EXAMPLE:
$(this).hide() - hides the current element.
To prevent any jQuery code from running before the document is finished loading (is ready):
$(function(){
  // jQuery methods go here...
});
You can select all <p> elements on a page like this:
$("p")
To find an element with a specific id, write a hash character, followed by the id of the HTML element:
$("#test")
To find elements with a specific class, write a period character, followed by the name of the class:
$(".test")
To assign a click event to all paragraphs on a page, you can do this:
$("p").click();
The next step is to define what should happen when the event fires.
$("p").click(function(){
   //blajblah
});
The mousedown() method attaches an event handler function to an HTML element.
The function is executed, when the left, middle or right mouse button is pressed down, while the mouse is over the HTML element:
Example
$("#p1").mousedown(function(){
  alert("Mouse down over p1!");
});
The mouseup() method attaches an event handler function to an HTML element.
The function is executed, when the left, middle or right mouse button is released, while the mouse is over the HTML element:
Example
$("#p1").mouseup(function(){
  alert("Mouse up over p1!");
});
With jQuery, you can hide and show HTML elements with the hide() and show() methods:
Example
$("#hide").click(function(){
  $("p").hide();
});
$("#show").click(function(){
  $("p").show();
});

