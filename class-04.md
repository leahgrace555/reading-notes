# Class 4 Reading Notes

## Links 

Links are created using the `<a>` with an `href="link.url"` attribute. The link can be to other sites using the absolute URL, or to other pages within the same site file by specifying its file path. Using this method is called a **relative URL**.

- You can create a mail link using `<a href = "mailto:email@example.com"> email or text goes here <a/>`
- To open links in a new window, use the **target** attribute. Example: ` <a href="link.com" target="_blank"> link text goes here </a> ` This will open the link in a new browser window. 
- Link to a specific part of the same page using IDs. Assign an ID to the element you want to link to. Example: `<a href="#top"> back to top </a> ` If an element such as your H1 in the header has been assigned an ID of 'top'.

## Layout: Things to Remember
- Block level elements start on a new line. these are the main building blocks of page layout
- Inline elements flow in between surrounding text
- CSS has three positioing schemes, **Normal Flow, Relative Positioning**, and **Absolute Positioning**
- In normal flow, every block level element starts on a new line
- Relative positioning moves an element from the position it would be in normal flow. This does nnot affect the surrounding elements. 
- Absolute positioning positions an element in relation to its containing element. 
- Boxes can sometime overlap. If you want to specify which elements appear close to the front, use a ***z-index***. The higher the z-index, the closer an element is to the front. 
- **Floats** take an element out of the normal flow and position it to the right or left of the **containing element**. 
- Screens now come in all shapes and sizes. Designers are challenged because they must take into account how a web page will look one something as large as a 27inch iMac as well as a tiny iPhone SE. 

Fixed width layouts:
- Do not change with the size of the browser window
- Designated using px values
- While the designer has much more control over the look, it is not really optimized for mobile viewing
-Large screen with high resolution can make these kind of pages appear very small

Liquid Layouts:
- Will stretch and contract as the user changes the browser size
- Usually designed using percentages

## Functions

Functions are a series of statements grouped together to perform a task.
- Statements in functions ar enot automatically executed when a page loads. Functions need to be called in order to run
- The steps that the function needs to perform in order are packaged in code blocks

Declaring a function:
````
function functionName() {
  ..block of code to execute..();
 }
 ````
 
 Calling a function:
 ````
 functionName()
 ````
 
 delcaring functions that need input:
 ````
 function needInfo(info1,info2) {
    return info1*info2;
  }
  ````
  
 calling a function that needs input:
 ````
 needInfo(info1,info2);
 ````

## Article 6 - Pair Programming

Pair programming involves a driver and a navigator
- The driver is the one physically writing code at the computer
- The navigator helps guide the driver by providing 'big picture' guidance

Benefits of pair programming
- Help develop the 4 fundamental skills of learning a language (reading writing speaking and listening)
- Pair programming is more efficient (may take longer but produces higher quality code)
- Engages collaboration and encouragess asking for help
- Fosters social skills and learning from other students
- Prepares for a possible job interview test and work environment readiness. 

**[Back to Home Page](README.md)
