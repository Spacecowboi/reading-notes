# Forms
 - Html borrows the concept of a form to refer to different elemetns that allow you to collect information from different visitors to your site.
 - There are several methods (controls) you can use to collect information from visitors to your site. Some of those include:
    1. Adding text
    2. Making choices
    3. Submitting Forms

 - A user fills in a form and then presses a button to submit information to the server.
 - A for mmay have several form controls, each gathering different information. The server needs to know which piece of inputted data corresponds with which form element.
 
 ## Lists, Tables and Forms
  - List markers can be given different appearances using the list-style type and list-style image properties.
  - Forms are easier to use if the form controls are vertically aligned using CSS
  - Forms benefit fomr styles that make them feel more interactive.

  # Events
   - Events are *fired* or *raised*
   - Events *trigger* a function or a script
   - An *Event* can be anything the user does on the web browser and triggers a code response, where the code will then respond to the users input. An event could be a mouse click, a hover, typing, just about anything.
   - *Event Handling* is what happens when an action takes place and triggers code in JS. Three things take place when this happens.
    1. Selecting the element node the script needs to respond to. (selecting element)
    2. Indicating **which** event on the selected node will trigger the response.(specifiying event)
    3. Declaring the code that needs to run when the event is triggered. (call code).
    - Event listeners are a more recent invention to handling events. They are able to handle more than one function at a time but cannot run on older browsers.
    - The flow of events in HTML only matters when your code has event handlers on an element *and* one of its ancestor or descendant elements.
    - When an event occurs, the **event** object tells you information about the event along with the element that it happened on.
    - Event delegation can help with how the event is handled. Delegation helps with new elements, solves limitations with the "this." keyword, and simplifies your code.
    - The event object has methods that change: the default behavior of an element and how the elements ancestors respond to the event.
    

