Javascript Array Search
=========================

This is a simple set of javascript / html & CSS files that will allow the user to search for values stored in a javascript array.

--------------------------------------------------------------------------------

Note: This script requires jquery.

###Setup:

Insert the html, css and javascript into your project in a way that fits with you workflow. 

In the javascript you will see the jsarray variable. This is the array that will be searched. You can build this by writing a custom function if it needs to be dynamic or just hardcoding in a set of values if it doesn't.

If you wish to create an array of integers instead of strings you will want to un-comment line 18:

//var current_value_int = +jQuery('#postcode-input-field').val();

and use the current_value_int variable as the first parameter in the inArray function below on line 22:

if(jQuery.inArray(current_value_int, jsarray) > -1 ){

--------------------------------------------------------------------------------------

[Demo Here](http://trent001.github.io/Javascript-Array-Search/)