# Complex Lucky Recipe Generator
This is a small app that returns a random recipe depending on wether not you get a random yes or no from the website. A yes = free random recipe, a no = a next time try again. Try your luck!


![alt tag](http://i66.tinypic.com/n2j0bl.jpg)

## How It's Made:

**Tech used:** HTML, CSS, JavaScript, API

I made this by using two APIs. One from a yes or no radomized API site and another from theMealDB.com to produces random recipes depending on a yes or no response from the first API. In order to match up a recipe appearing dependent on the first API a conditional statement needed to be made where it would match a yes or no to the property within the JSON file. I "hid" the recipe if a no was returned with display: none; and it made it reappear with targetting the element with a style object modification,


## Lessons Learned:

Through building this project, I learned how APIs work. I learned about JSON and how JSON is basically a giant array that holds a bunch of objects with key-value pairs you can access using a combination of dot notation or optional brackets to select which index you need from the JSON array. To loop through the array to select multiple elements of key-value pairs sometimes it is necessary to loop through them with a forEach loop. I learn how to append newly created elements with the appendChild method to add to the DOM to make new elements appear in my HTML.
