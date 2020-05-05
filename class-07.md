# Class 7 reading notes:

## Domain Modeling
definition: process of creating a conceptual model in code for a specific problem.

Define constructor function:
- initialize and define properties across many objects at once

````
var EpicFailVideo = function(epicRating, hasAnimals) {
  this.epicRating = epicRating;
  this.hasAnimals = hasAnimals;
}

var parkourFail = new EpicFailVideo(7, false);
var corgiFail = new EpicFailVideo(4, true);

console.log(parkourFail);
console.log(corgiFail);
````

## HTML tables:

`<table>` : used to create a table
`<tr>` : used to indicate the start of a table row
`<td>` : represents a cell containing table data
`<th>` : represents the table heading for a column or row
`colspan` : an attribute that can be added to table data to make is span multiple columns
`rowspan` : can be added to table data to make it span multiple rows

## Functions, Methods, Objects:

Constructor notation: used to create many objects:
````
function Hotel(name,rooms,booked) {
  this.name = name;
  this.rooms = rooms;
  this.booked = booked;
  this.checkAvailability = function() {
  return this.rooms - this.booked;
  }
}
````
to create instances:


````
var newHotel = new Hotel('quay',40,25);
````

Accessing objects in constructor notation:
- after you create instances of an object, you cna access their properties using the same dot notation as other objects
- you can also add and remove properties using dot notation

## This

`This` is a keyword commonly used in fucntions and objects. It refers to the object in which a fucntion operates. 

## Arrays are objects:
- arrays hold a set of key value pairs
- the key for each value is its index number
- arrays and objects can be combined to create complex data structures

## Browsers have built in objects
- Window object
- Document object
- Global objects (strings, numbers, decimal, math).

**[Back to Main Page](README.md)**



