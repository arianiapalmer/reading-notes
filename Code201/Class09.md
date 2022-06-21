# Foundations of Software Development: Class 09

* Class notes for Code 201 with code fellows, starting June 06, 2022 ending July 01, 2022

## Class 09 - June 16, 2022

### *Reading 9: Forms And Event*

#### HTML Forms

HTML forms are important in web development because it is one of the main ways for a user to interact with a web page. 
When designing a web page, some key things to keep in mind when it comes to user experience are how the user will want to fill out the form, putting yourself in their place and building off of what they would expect to fill in first or last; grouping fields that belong together; branching forms and only asking a user for what is necessary. Finally, planning for localization is good, what environment will the web page be in with the user - will it be on compatible to an iphone user in norway the way it would be to a nintendo user in UAE.
Five form elements and their uses

* label - a formal way of defining a label for form widget, which makes a sit more accesible
* input - used to creative interactive controls for forms in order to collect data from the user
* textarea - represents a multi-line plain text editing control
* button - allows a user to submit their data to the web page, or even just perform a programmable action
* fieldset - allows a developer to create a group of widgets (controls and labels) that share the same purpose

#### Introduction To Events

If I were to explain events to a non technical friend I would explain them as an alarm almost. The way you would set an alarm to wake up and you know that when the alarm goes off that you need to get and brush your teeth.
You need to provide the name and handler arguments when using the addEventListener() method.
The target within the event object is useful in providing extra features to the event the element occurred upon.
The difference between event bubbling and event capturing is 
