# Foundations of Software Development: Class 07

* Class notes for Code 201 with code fellows, starting June 06, 2022 ending July 01, 2022

## Class 07 - June 14, 2022

### *Reading 7: HTML Tables; JS Constructor Functions*

#### Domain Modeling

Domain modeling is necessary to help developers keep track of all of the moving pieces of their code, allowing them to add or remove actions easily. It helps a developer understand exactly what is expected and how to accomplish each each task.
 
#### HTML Table Basics

Tables should not be used for page layouts because it makes it less accessible for visually impaired users using screenreaders, it makes code harder to read since table layouts are already complex on their own, and tables are not automatically responsive and require extra styling since their size are dependent on the content size. 
Three different semantic HTML elements used in an HTML table

* tr - table row: used for assigning a table row, allowing code to be cleaner
* td - table data: used for assigning data to a table, which when used with td, makes code cleaner
* th - table heading: used for assigning a header to a table row allowing data to stand out, which makes it easier to find 

#### Introducing Constructors

A constructor is a function using the new keyword, allows you to create new objects and eliminate repetitive code.
.this used in objects literals refers to whatever property in that specific object that has already been defined, but when used in a constructor it binds to the new object

#### Object Prototypes Using a Constructor

Prototypes are like 
