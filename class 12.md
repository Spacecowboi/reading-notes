# Creating a chart
 - Having to use the *canvas* element.
 - The id attribute isn't specific to the canvas element but is one of the global html attributes that can be applied to any HTML element.
 - The canvas element can be styled just like any normal imag, but the rules don't actually affect the drawing on canvas.
 - The canvas element creates a fixed-size drawing surface that exposes one or more *rendering contexts* which are used to create and manipulate the content shown. 
 - The canvas is initially blank. To display something, a script first needs to access the rendering context and draw on it. The canvas element has a method called get Context() used to obtain the rendering context and its drawing functions.
 - The default sizing for a chart is a height of 300px and a width of 150px.

 # Drawing shapes in canvas
  - *Paths* are a list of poitns, connected by segments of lines that can be different shapes, curved or not, of different colors, etc.
    1. Create path beginPath()
    2. Call methods which specify lines to be drawn.
    3. This step is optional. call closePath()

  - Straight lines use the lineTo() method
  - Arcs and circles use the arc() or arcTo() methods

  