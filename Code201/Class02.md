# Foundations of Software Development: Class 01

* Class notes for Code 201 with code fellows

## Class 02 - April 24, 2023

### *Reading 2: HTML Text, CSS Introduction, and Basic JavaScript Instructions*

#### HTML & CSS

* Chapter 2: Text (pgs 40-61)

When creating a web page, you add tags known as markup to the contents of the web page. These tags provide extra meaning and allow browsers to show users the appropriate structure for the page.

> * Structural markup - the elements that you can use to describe the structure of the page like headings and paragraphs
> * Semantic markup - provides extra information; some semantic markup causes visual effects in webpages but the tags aren't used for styling, they are used to speak with the webpage, which in turn may render in a specific way.

* Chapter 10: Introducing CSS (pgs 226-245)

CSS allows you to create rules that specify how the content of an element should appear, letting you control the way that each individual element, and the contents in it, is presented. A CSS rule contains two parts: a selector and a declaration. 

> * Selectors indicate which element the rule applies to. The same rule can apply to more than one element if you separate the element names with commas.
> * Declarations indicate how the elements referred to in the selector should be styled. It is split into two parts, a property and a value and are separated by a colon. 

>> Declarations sit inside curly brackets and is made up of a property and a value. Properties indicate the aspects of the element you want to change and values specify the settings you want to use for the chosen properties.

CSS can be used externally and internally within a web page. To use it externally, you used the link element with the href attribute(which specifies the path to the CSS file); the type attribute (specifies the type of document being linked to); and the rel attribute (which specifies the relationship between the HTML file and what's being linked to it. "stylesheet" is used when linking to a CSS file)
Internal CSS can be done using the style element with the type attribute to indicate that the styles are specified in CSS.



#### JavaScript

* Chapter 2: Basic JavaScript Instructions (pgs 53-84)

To use JavaScript with a web page, you use the <script> tag. You can use it by itself in an HTML document or you can use the script tag to link to a separate js file. Using this tag only speaks to the browser and the code cant be seen by the user on the web page. 
A script is a series of instructions that a computer can follow one-by-one, with each step being known as a statement. Statements end with a semicolon.
> Statements are instructions that the computer should follow and they can be organized into code blocks (using curly brackets {}), with each one being separated by a new line. 

Organization is key to keeping code useful for revisting. Comments should be used when writing code to explain what the code does, which makes it easier to read and understand. Use // for a single line comment, and /* */ for multiple lines of comments.

A script will have to temporarily store the bits of information it needs to do its job, this can be done using variables. Variable can be used to remember values even if they are changing. Variables are declared by first announcing it, using var, and then giving it a name. Keep in mind when naming that JavaScript is very case sensitive. Then you tell the variable what information you would like for it to store for you, called assigning a variable, with an assignment operator(like the equal sign =).

Java Script distinguishes between different data types like numbers, strings (basically anything including letters and other characters), and true or false data types known as Booleans.



* Chapter 4: Decisions and Loops (pgs 145-162)