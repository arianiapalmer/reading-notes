# Foundations of Software Development: Class 01

* Class notes for Code 201 with code fellows, starting June 06, 2022 ending July 01, 2022

## Class 01 - June 06, 2022

### *Reading 1: Introductory HTML and JavaScrip*

#### HTML

CH 1: Structure
HTML is used to create web pages that show text. Structuring is an important part of creating a web page because it allows you to place your text in an organized manner that benefits the intended user. Key points for learners is understanding tags, often called elements, which act as containers and tell you something about the information that lies between them; also opening tags can carry attributes, that require a name and value, which can tell you even more about the content of the element.

CH 8: Extra Markup

* DOCTYPES - at the beginning of an HTML page, doctype declarations tell a browser which version of HTML to use
* Comments - Add comments to your code using :  """<!-- -->""" text within this tag will not be visible in the user's browser. Comments are good making your code easier to understand when you lose your familiarity with it
* ID Attribute - the id attribute is used to uniquely identify an element from other elements on a web page. No two elements can have the same id attribute. Id attributes allow an element to be styled from any other instance of the same element on a web page
* Class Attribute - a way to uniquely identify several elements as being different from the others on a page. Its value should describe the class it belongs to
* Block Elements - elements that will always appear to start on a new line in the browser window. Block level elements are <h1>, <p>, <ul>, <li> 
* Inline Elements - elements that will always appear to continue on the same line as neighboring elements. Examples of these are <a>, <b>, <em>, and <img>
* Grouping Text & Elements in a Block - <div> element allows you to group a set of elements together in one block.
* Grouping Text & Elements Inline - <span> is used the same way as div but inline. It can contain a section of text to different it from the rest. Mainly used to control appearance of text inline
* Iframes - <iframe> short for inline frame, <iframe> can be used to cut a window into your page and insert whatever you need, like embedding google maps into a page
* """<meta>""" - lives inside the head element and contains information about the web page. Can tell search engines about your web page, does not have a closing tag, but usies attributes to carry the information

CH 17: HTML5 Layout
The new HTML5 elements indicate the purpose of different parts of a web page and help to describe its structure.
The new elements provide clearer code (compared with using multiple <div> elements).
Older browsers that do not understand HTML5 elements need to be told which elements are block-level elements.
To make HTML5 elements work in Internet Explorer 8 (and older versions of IE), extra JavaScript is needed, which is available free from Google

CH 18: Process & Design
It is important to understand your user audience when creating a web page. You should know who the site is for, why people will be visiting your site, what your visitors will be trying to achieve with your site, what information your visitors will be needing, and how often people will visit your site. Understanding this will give you a better understanding of how to map your site out into sections and pages. Drafting a website can start with a wireframe, which is a simple sketch of the key information that needs to go on each page of a site. The design of a site is about communication and visual hierarchy helps visitors understand what you're trying to tell them. Grouping and similarity can be used to help simplify the information you present.

#### JavaScript

JavaScript allows you to make webpages moe interactive by accessing and modifying the content and markup used ina web page while it is being viewed in the browser. It can make the web page feel interactive by reacting  to what a user does. JavaScript speaks to a website using a script, which is a series of instructions that the a computer can follow in order to achieve a goal.To write a script break down your goal into a series of taks and work out each step needed to complete that tasks, possibly using a flowchart.

To link a script to an html web page you would use the <script> tag with a link to js file. Placing a script tag does not change your html code nor can it be seen in the browser. 