# Notes on HTML reading

### Elements that structure a page
 - Tags act like containers. They tell you something about the information that lies between their opening and closing tags.
   - An example would be <body></body>
   - This tag indicates that anything between it and the closing </body> tag should be shown inside the main browser window.

### Attributes tell us about Elements
 - Attributes provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts: a name and a value, separated by an equals sign.
  <p lang="en-us">Peanuts</p>

### Extra Markup 
 1. DOCTYPES tell browsers which version of HTML you are using.
 2. The <div> nad <span> elements allow you to group block-level and inline elements together.
 3. The <meta> tag allows you to supply all kinds of information about your web page.
 4. The id and class attributes allow you to identify particular elements.

### New HTML notes 
 - The <header> and <footer> elements are essentially the top and bottom sections of the website
 - A header or footer can be used for an individual <article> or <section> within the page.
 - <nav> is used to contain the major navigational blocks on the site. (how you move within the site)
 - <article> is a container for any part of a page that can stand alone
 - <aside> has two purposes:
   1. If it is used inside an <article>, it contains information that is related to the article but not essential to its meaning
   2. If it is used outside of the <article> element, it is a container for content that is for the entire page.
 - HTLM5 elements indicate the purpose of different parts of a web page and help describe its structure.
 - Older browsers that do not understand HTLM5 elements need to be told which elements are block-level elements.

### ABC of programming
 - **Javascript is best kept in its own JS file. Pretty much text files but with .js**
 - *the <script> element is used to tell the browser to load the JS file.
 