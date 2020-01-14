# What is an object?
 - **Objects** group together a set of variables and functions to create a model of something you would recognize from the real world. In an object, variables and functions take on new names.
 - If a variable is part of an object, it is called a **property**
 - If a function is part of an object, it is called a **method**
    - methods represent tasks that are associated with the object.
- Similar to variables and functions, properties and methods have a name and a value (var book) for example would be the name of the object and pages: number would be a property. 
- Separating keys from values requires the use of a colon

# The DOM (Document Object Model)
 - Specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.
 - Accessing and updating the DOM tree involves two steps:
  1) Locate the node (HTML) that represents the element you want to work with.
  2) Use its text content, child elements, and attributes.
 - The terms *elements* and *element nodes* are used interchangeable, but when people say the DOM is working with an element, it is actually working with a node that *represents* that element.
 - In older browsers, implementation of the DOM is inconsistent.
 - Browsers offer tools for viewing the DOM tree.
 ### Nodelists###
 - When a DOM method can return more than one element, it returns a NodeList(even if it only only finds one matching element).
 - A NodeList is a collection of element nodes. Each node is given an index number (starts at a value of zero, like an array). The oder in which the element nodes are stored in a NodeList is the same order that they appeared in the HTML page.
 -A live NodeList will update at the same time that the script updates the page.
 - A static NodeList will not update once the script updates the page.
