# Domain modeling
 - An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an **object-oriented** model.
 - Domain modeling is the process of creating a conceptual model for a specific problem.

 # Table
  - A table represents information in a grid format. (Tv schedules, sports results)
## Elements of the table structure.
 1) The table element is used to create a table. The contents of the table are written out row by row.
 2) tr: You indicate the start of each row using the opening tr tag.
 3) td: Each cell of a table is represented using a td element.

 # Functions, Methods, and Objects
  - An object is typically created on the first line of code. Then, the syntax for adding or removing any properties and methods from that object is the same.
  - The key word **this** is most commonly used inside functions and objects. Where the function is declared alters what that means. It also always refers only to one object, typically the one in which the function operates.
  - When a function is define **inside** of an object, it becomes a method. In a method, it refers to containing object.
  - If a named function has been defined in global scope, and it is then used as a method of an object, this refers to the object it is contained within.
  - In JS, data is represented using name/value pairs. To organize you data, you can use an array or object to group a set of related values. In arrays and objects the name is also known as a *key*
  - If you want to access items via a property name or key, use an object. If the order of the items is important, use an array.
  - Arrays are actually a special type of object. They hold a related set of key/value pairs. The key for each value is its index number.
  - Whenever you have a value that is a string, you can use the properties and methods of the String object on that value. 
  - In JS there are six data types:
    1. String '.'
    2. Number 4
    3. Boolean | |
    4. Undefined (Has been declared, but has no value to it)
    5. Null (No value)
    6. Ojbect

 - JS has several built-in objects such as: String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts.