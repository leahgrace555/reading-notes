# Understanding the Problem Domain

Why is this so hard?
  - It's signinifacntly harder to work towards a goal if you don't entirely understand what that goal is
  - People struggle with learning more than one thing at a time. If you're trying to understand the problem domain while simultaneous learning new concepts to solve it, the progrramming will be much harder
  
  Solutions?
  - Make the problem domain easier: Narrow down your goal to a specific task, breaking it up so the outcome you want to acheive is clearer
  - Understand the problem domain better: Talk clearly with the clien/project leader/ etc.. make sure you actually understand what you are making **before** you start coding. Remember, it's not wasting time 'chatting' if it's going to help you fulfill the goal faster.
  
  # Object Literals
  
  Object group together a set of variables and functions to create a model
  - Inside objects: variables are known as properties and functions are known as methods
  
  Example: Think of an object like a hotel
  ````
  var hotel = {
  name: 'Quay',
  rooms: 40,
  booked: 25,
  gym: true,
  roomTypes: ['twin','double','suite'],
  
  checkAvailability: function() {
    return this.rooms - this.booked;
    }
   }
   ````
   In this example, name, rooms, booked, gym and roomtype are keys, and Quay, 40, 25, true and the array are values. The checkAvailability function is a method.
   
   Accessing an object: 
   - Dot Notation: var hotelName = hotel.name; (nameOfObject.property/method
   
   # Document Object Model
   
   DOM = API (application programmign interface)
   
   ## DOM Trees:
   
   A DOM tree is a model of a webpage that the browser creates when it loads. When scipts access and update a file, they are update the DOM tree, the the source HTML file. DOM trees consist of four types of nodes. Nodes are each objects with methods and properties.
   1. The document node
   2. Element node
   3. Attribute node
   4. Text nodes
   
   
   
   ## Working with the DOM Tree:
   
   1. Access the elements:
   - getElementbyID() / querySelector()
   - getElementsByClassName() / TagName / querySelectorAll()
   - parentNode / previousSibling / nextSibling
   
   ## Adding and Removing HTML Content:
   Example: changing a list item:
   1. Use innerHTML 
   2. To add content, store as a string in a variable, select the element whose text you want to replace, set the element's innerHTML to be the new string
   3. Removing content: set innerHTMl to an empty string
   
   ## DOM manipulation method:
   - can be slower and require more code, but also safer than using innerHTML
   - allows you to create and remove nodes are directly remove form the DOM tree
   
   **[Back to Main Page](README.md)**
   
