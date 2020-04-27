# Introducing HTML

| Tag     |       Meaning/Use        |
|----------|-------------------------|
|` <h1>..<h6> `| Used to add headings. 1 is the largest, 6 is the smallest|
|` <p>  `    | Paragraph tag. Used to create paragraphs |
|` <b>  `    | Wrapping text with this will make it **bold**|
|` <i>  `    | Wrapping text in this will italicize it |
|` <sup> `   | Wrapping text in this will make it super script|
|` <sub> `   | Wrapping text in this will make it sub script. |
|` <br/> `   | Adds a line break in the middle of paragraphs. |
|` <hr/> `   | Add a Horizontal rule (line) across the page. Used to breaks up sections. |

The following elements are known as *semantic markup*. They do not affect the structure of your page, but can add extra information to the pages.

| Tag     |       Meaning/Use        |
|----------|-------------------------|
| ` <strong> `| Inticates that the content contained in it is important. By default, browsers will display this as bold. |
| ` <em> `   | Indicates emphasis that changes the meaning of the content. By default, browsers will display this is italics.|
| ` blockquote>` | Used to insert a block quote |
| ` <abbr> `  | A title can be added to spell out the full form of the acronym. |
| `<dfn>` | Used to indicate the defining instance of a term|
|` <cite> `| Used to indicate a source when citing a piece of work, such as a book or film. | 


# Introducing CSS

CSS stands for "Cascading Style Sheets". It works by applying styles, such as colors, fonts, sizes and other attributes, to selected HTML elements

## Syntax

The syntax of CSS is as follows:
````
p {
    font-family: Arial;
}
````
In this case, p is the **selector**, and the type inside the curly brackets is the **delcraration**. The selector tells CSS which HTML tag to apply the style to, and the declaration states what that style rule is. 

Declarations are also made up of a **property** and a **value**. Properties indicate the aspect fo the element you want to change, and values specify what to chnage it to. In the above example, "font-family" is the property and "Arial" is the value.  

## Internal VS External CSS

CSS can be applied both internally (between a style tag in the HTML document) or externally, by linking an external style sheet in the head section of your HTML document. It is best practice to use external style sheets because it creates consistency across all pages of a site if formatted correctly.

Link an external style sheet by doing the following:
````
<head>
    <title> This is the title of you webpage </title>
    <link href="name-of-css-document.CSS" type="text/css" rel="stylesheet" />
<head>
````
***NOTE*** that the link tag is a self-closing tag and is always inside the head element (not the header).

## How Rules Cascade

CSS files are read from top to bottom, so it is important to understand which rules will take precedence over others.
If two rules have identical selectors, the *last* rule will take precedence (meaning the one lowest on the style sheet). 
Specificity will also take precedence over other selectors. For example, if a rule is applied to a body tag, and a different rule is applied to the h1 inside the body, the rule applied to the h1 tag will take precende because it is more specific. 

# JavaScript

## Placing Script in the Page

JavaScript can be added between `<script>` tags, but it is better to use an external sheet and call functions on the page as needed.

Note: *JavaScript will run where it is found in the HTML*. When the browser comes across the `<script>`, it 'checks' if it needs to do anything (i.e. run a function). 

## Objectives and Methods

Script is a series of instructions that a computer can follow one-by-one. 

Each step is known as a **statement**

Things to note:
-JavaScript is ***case sensitive***
- Each statement should start on a new line and end with a semicolon
- Statements can be organize into code blocks with curly brackets. 

## Comments

Comments can be single line or multiline
- Add a single line comment with two forward slashes // --anything after the slashes on that line will be interpreted as a comment
- Add a multiline comment by surrounding the text with /* text goes here
and also here */

## Variables

Before you can use variables, you must declare that you want to use them them with a statement such as: ` var quantity; ` where "var" is the variable keyword and "quantity" is the variable name. Multi-word variables must be written in camelCase

Once you create a variable, you can assign it a value. For example, ` quantity = 3; ` is how we assign a value to the variable we created in the previous example.

There are three types of data

1. Numeric data consists of numbers
2. String data consists of letters and other characters
3. Boolean data can have one of two values, true or false

There are six rules you must always follow when naming variables:

1. Names must begin with a letter, dollar sign or underscone. Never a number. 
2. The name can contain letters, numbers, dollar sign or underscores. Do not use a dash or dot in a variable name
3. You cannot use keywords or reserved words
4. Variables are case sensitive
5. Use a name that describes the kind of information the variable stores
6. When using mutiple words in a variable, type in camelCase, or use underscores instead of spaces. 

## Arrays

Arrays are a set of values that are related to each other.This may be used in place of a long list of variables. 

example:

````
var colors;
colors = ['white','black','custom'];
````
Values in array are given an index, or number that can be used to reference. Note that **index values start at 0, not 1**



**[Back to Home Page](README.md)**
