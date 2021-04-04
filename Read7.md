# Read class 7

### Table
> A table represents information in a grid format.
Examples of tables include financial reports, TV
schedules, and sports results.

> The <table> element is used to create a table. The contents 
>of the table are written out row by row.

> You indicate the start of each row using the opening <tr> tag.
 (The tr stands for table row.) 

 > <td>
Each cell of a table is represented using a <td> element. (The td stands for 
table data.)

> The <th> element is used just like the <td> element but its
purpose is to represent the  heading for either a column or a row. (The th stands for table heading.) 

- <thead> The headings of the table should sit inside the <thead> element.
- <tbody> The body should sit inside the
- <tbody> element.
- <tfoot> The footer belongs inside the <tfoot> element.

### Objects

>CREATING MANY OBJECTS:
Sometimes you will want several objects to represent similar things.
Object constructors can use a function as a template for creating objects.
First, create the template with the object's properties and methods. 

> CREATING OBJECTS USING CONSTRUCTOR SYNTAX 
> On the right, an empty object called hote 1 is created using the
constructor function. Once it has been created, three properties and a method are
then assigned to the object. (If the object already had any of these properties,this would overwrite the values in those properties.)
To access a property of this object, you can use dot notation,
just as you can with any object. For example, to get the hotel's name you could use:
hotel .name 

> CREATE & ACCESS OBJECTS CONSTRUCTOR NOTATION 
> To get a better idea of why you might want to create multiple
objects on the same page, here is an example that shows room
availability in two hotels. First, a constructor function
defines a template for the hotels. Next, two different instances
of this type of hotel object are created. The first represents
a hotel called Quay and the second a hotel called Park. 

> ADDING AND REMOVING PROPERTIES 
Once you have created an object (using literal or constructor
notation), you can add new properties to it.
You do this using the dot notation that you saw for adding
properties to objects on pl03. In this example, you can see that
an instance of the hotel object is created using an object literal.
Immediately after this, the hotel object is given two
extra properties that show the facilities (whether or not it has
a gym and/or a pool). These properties are given values that
are Booleans (true or false). 

> STORING DATA
In JavaScript, data is represented using name/value pairs.
To organize your data, you can use an array or object to group a set of
related values. In arrays and objects the name is also known as a key. 

> THE BROWSER OBJECT MODEL:
THE WINDOW OBJECT The window object represents the current
browser window or tab. It is the topmost object in the Browser Object Model, and it contains other objects that tell you about the browser.

>GLOBAL OBJECTS: STRING OBJECT
Whenever you have a value that is a string, you can use the properties
and methods of the String object on that value. This example stores the
phrase "Home sweet home " in a variable. 

>DATA TYPES REVISITED
In JavaScript there are six data types:
Five of them are described as simple (or primitive) data types.
The sixth is the object (and is referred to as a complex data type)

- String
- Number
- Boolean
- Undefined
- Null 
- object
  
  