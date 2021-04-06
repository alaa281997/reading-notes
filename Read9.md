# Read class 9

*Form Controls*
>There are several types of form controls that
you can use to collect information from visitors
to your site.

*why use Form*
>The best known form on the web is probably
the search box that sits right in the middle of
Google's homepage.

>A form may have several form controls, each
gathering different information. The server
needs to know which piece of inputted data
corresponds with which form element.

><form>
Form controls live inside a <form> element. This element
should always carry the action attribute and will usually have a
method and id attribute too.

><input>
The <input> element is used to create several different form
controls. The value of the type attribute determines what kind
of input they will be creating.

><input>
type="password" When the type attribute has
a value of password it creates a text box that acts just like a
single-line text input, except the characters are blocked out.
They are hidden in this way so that if someone is looking over
the user's shoulder, they cannot see sensitive data such as passwords

> <textarea>
The <textarea> element is used to create a mutli-line
text input. Unlike other input elements this is not an empty
element. It should therefore have an opening and a closing tag

> <button>
The <button> element was introduced to allow users more
control over how their buttons appear, and to allow other
elements to appear inside the button.
This means that you can combine text and images
between the opening <button> tag and closing </button> tag.

><label>
When introducing form controls, the code was kept simple by
indicating the purpose of each one in text next to it. However,
each form control should have its own <label> element as this
makes the form accessible tovision-impaired users.

><fieldset>
You can group related form
controls together inside the <fieldset> element. This is
particularly helpful for longer forms.


>list-style-type 
The list-style-type property
allows you to control the shape
or style of a bullet point (also
known as a marker).
It can be used on rules that
apply to the <ol>, <ul>, and <li>
elements.

>list-img
You can specify an image to act as a bullet point using the
list-style-image property. The value starts with the letters
url and is followed by a pair of parentheses. Inside the
parentheses, the path to the image is given inside double
quotes.

>outside
The marker sits to the left of the
block of text. (This is the default behaviour if this property is not
used.)
>inside
The marker sits inside the box of text (which is indented).
In the example shown, the width
of the list has been limited to 150 pixels. This ensures that the text
wraps onto a new line so you can see how the value of inside sits
the bullet inside the first line of text. 

> Table propeties
- width to set the width of the
table
- padding to set the space
between the border of each table
cell and its content
- text-transform to convert the
content of the table headers to
uppercase
- letter-spacing, font-size
to add additional styling to the
content of the table headers
- border-top, border-bottom
to set borders above and below
the table headers
- text-align to align the writing
to the left of some table cells and
to the right of the others
- background-color to change
the background color of the
alternating table rows
- :hover to highlight a table row
when a user's mouse goes over it

*show*
This shows the borders of any
empty cells.
*hide*
This hides the borders of any
empty cells.
*inherit*
If you have one table nested inside another, the inherit
value instructs the table cells to
obey the rules of the containing
table.
In the first table on the left, you can see that the border of the
empty cell is showing. In the second table, it is hidden.

# EVENTS
EVENT DESCRIPTION 
load W eb page has finished loading 
unload Web page is unloading (usually because a new page was requested) 
error Browser encounters a JavaScript error or an asset doesn't exist 
resize Browser window has been resized 
scroll User has scrolled up or down the page 
KEYBOARD EVENTS Occur when a user interacts with the keyboard (see also input event) 
EVENT DESCRIPTION 
keydown User first presses a key (repeats while key is depressed) 
keyup User releases a key 
keypress Character is being inserted (repeats while key is depressed) 
MOUSE EVENTS Occur when a user interacts with a mouse. trackpad, or touchscreen 
EVENT DESCRIPTION 
click User presses and releases a button over the same element 
dbl click User presses and releases a button twice over the same element 
moused own User presses a mouse button while over an element 
mouseup User releases a mouse button while over an element 
mousemove User moves the mouse (not on a touchscreen) 
mouseover User moves the mouse over an element (not on a touchscreen) 
mouseout User moves the mouse off an element (not on a touchscreen)

>TRADITIONAL DOM  EVENT HANDLERS 
All modern browsers understand this way of creating an event handler, 
but you can only attach one function to each event handler. 

USING DOM EVENT HANDLERS 
- If you use a named function  when the event fires on your 
chosen DOM node, write that function first. (You could also 
use an anonymous function.)
- The DOM element node is stored in a variable. Here the text 
input (whose id attribute has a value of username) is placed into 
a variable called e 1 Username
- On the last line of the code  sample above, the event handler 
e 1 Username. onb 1 ur indicates  that the code is waiting for the 
b 1 ur event to fire on the element  stored in the variable called 
e 1 Username. 

> EVENT LISTENERS 
Event listeners are a more recent approach to handling events. 
They can deal with more than one function at a time 
but they are not supported in older browsers.

>EVENT DELEGATION 
Creating event listeners for a lot of elements 
can slow down a page, but event flow allows 
you to listen for an event on a parent element. 