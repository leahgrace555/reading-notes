# Class 3 Reading Notes

## Lists

There are a couple different types of lists you can use in HTML.

**Ordered Lists** are created with the `<ol>` tag and have `<li>` tags nested inside them. 
- By default, ordered lists will be indented and have numbers before each list item. 

**Unordered lists** are created with the `<ul>` tag and also have list items nested inside them
- By default, unordered lists will also be indented and have bullet points before each list item

**Definition lists** are created with the `<dl>` tag. 
- The term being defined will be contained by a `<dt>` tag and the definition goes inside a `<dd>` tag.

**Nested lists** are created by putting a second list inside an `<li>` to create a sub lists. 
- By default, browsers will indent nested lists even further


## The Box Model

CSS treats each HTML element as if it lives inside its own box. The spacing between boxes in controlled by changing the padding, margin and border for each element. 
Box dimensions can be changed by specifying pixels, percentages or ems.
- Pixels specify a fixed heigh and width
- Percentages specify height and width relative to the browers window
- Ems specify height and width relative to the text contained in it. 
- Designers are more commonly using percentage and ems now to accomodate design across multiple devices

When browser windows are too small to contain the specified box dimensions, designers can use the **overflow** property to tell the browser what to do with the content
- Using **hidden** will hide any content that doesn't fit
-Using **scroll** will add a scroll bar to the box so the user can scroll to see the missing content. 

## Switch Statements

**Switch statements** are used to indicate possible values, or 'cases' for a variable, and runs a different code block based on the value of that variable

For example, to display a different message based on what level a user is, one could use a switch statement like this:
````
var msg;
var level = 2;

switch (level) {
case 1:
  msg = 'Good luck with the first test';
  break;
  
 case 2:
  msg = 'Keep going!;
  break;
  
 }
 ````
 
 Switch statements are useful for evaluating multiple conditions, where if else statements are better for fewer options. 
 
 ## Type Coercion
 
 Javascript has the ability to convert data types behind the scenes. Since the data type can be changed without specifying, JavaScript is said to have "weak typing".
 Type coercion can lead to unexpected values in your code, therefore it is better practice to use strict operators that check data type matching as well. 
 
 ## Short circuit values
 
 Logical operators are processed left to right. It is important to remember that once they have a result, they return the value that stopped the processing. 
 
 ## Loops
 
Loops check a condition and if that condition returns true, it will run a block of code, repeating until the condition returns false

**For Loops:** These run for a specified number of times.

**While Loops:** These run as long as the condition is true.

**Do While Loops:** These are similar to while loops, but will always run the code block inside the curly brackets at least once.
