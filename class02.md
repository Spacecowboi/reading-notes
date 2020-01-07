### On text
 - HTML has six levels of headings (for example, <h1><h2<h3> etc)
 - For <p>, a browser will show each paragraph on a new line with some space between it and any following paragraphs.
 - <b> for **bold**
 - <i> for *italics*
 - <strong> for when you need to lift heavy code. Haha, just kidding. It means that the element is important.
 - <blockquote> used for long quotes that take up an entire paragraph. You still use <p> just so theres no confusion.
 - <q> is used for shorter quotes that sit within the paragraph. Many people avoid using this because Internet Explorer = bad
 - <dfn> this is the first time you explain something new in a document. Otherwise known as the "defining instance" of said something. It is used to indicate the defining instance of a new term.
 - HTML elements are used to describe the elements of the page

 ## On CSS and its importance to web development
 - The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.
 - The <link> element can be used in an HTLM document to tell the browser to find the CSS file used to style the page.
 - <style> includes CSS rules within an HTML page

 # SELECTORS
  - There are a ton of different selectors used for different things, so here we will list out which they are and their appropriate tags
   1. Universal selector = * {}
   2. Type selector = h1, h2, h3 {}
   3. Class selector = .note {} p.note{}
   4. ID selector = #introduction {}
   5. Child selector = {boy}{girl} haha just kidding, its actually li>a {}
   6. Descendant selector = p a {}
   7. Adjacent Sibling selector = <<BOY>> nope, gotcha again, its h1+p {}
   8. General sibling selector = I have run out of jokes, so its h1~p {}

 ### Wrapping up CSS
 - Rules are made up of selectors and declarations
 - Different types of sectors allow you to target your rules at different elements
 - CSS rules usually appear in a separate document, although they can appear within an HTML page

 # Basic JS instructions
  - A script is a series of instructions that a computer can follow one-by-one. Each individual statement or step is known as a **statement**
  - Statements always end with a semicolon.
  - Try to write comments to explain what your code does. They help make your code easier to read and understand.
  - A script will have to temporarily store the bits of information it needs to do its job. It does this in variables.
  - There are three types of data types: Numeric (0.78), String 'Hi', and boolean "true"
  - Giving a variable a name can be difficult. So here are some rules to follow to help:
    1. Must begin with a letter, dollar sign, or underscore
    2. You cannot use keywords or reserved words.
    3. All variables are case sensitive, try and keep it lowercase chief.
    4. Use a name that describes the kind of information that the variable stores. Meaning, make it related to the content.
    5. If your variable is more than one word, use a capital letter fofr the first letter of every word *after* the first word.
  - An arrary is a special type of variable. It doesnt just store one value; it stores ALL the values.
  - An expression evaluates into a single value. Generally, there are two types of expressions: Those that assign a value to a variable, and those that use two or more values to return a single 
  - Expressions rely on **operators**; they allow programmers to create a single value from one or more values.
  - Scripts contain very precise instructions. Remember, computers dont do naything you dont tell them to do.
  