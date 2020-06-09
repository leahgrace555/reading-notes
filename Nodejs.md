# Read 06: Node.js

## What is Node.js?
- Node is a javascript runtime program that allows us to execute javascript on our computers
- It can be installed from the official website's download page

## Using Node:
- Console logs in node can be sent direct;y to your terminal or node's build in console module
- Node has a built-in compatability tablet that allows you to use the most modern/updated versions of javascript

## npm:
- This is a javascript package manager
- Short for 'node package manager'
- Allows you to globally install packages using 
````
npm install (packagename)
//without parens
````
- Install packages locally using npm init commant in the terminal

## The package.json file:
- What is this?
- This contains a list of dependencies
- Havign this file allows devs anywhere to clone your project and install the necessary packages

## Node.js can run JavaScript on a server
- node is single threaded and event driven
- when a request comes in, the server starts processing it
- is a blocking i/o operation is encountered, node will register a callback, process the i/o then use the callback to continue the original operation

## Limitations:
- Incorrect error handling can lead to crashing the entire process
- CPU intensive operations should be handed off to worker threads

**[back to main page](README.md)**
