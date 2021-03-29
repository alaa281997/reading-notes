# Read class 3
## Lists
I starting reading about list there is three type of list 
first ordered list s are lists where each item in the list is
numbered. <ol>
Unordered lists are lists that begin with a bullet point
(rather than characters that indicate order).<ul>
Definition lists are made up of a set of terms along with the
definitions for each of those terms.
<dl>
The definition list is created with
the <dl> element and usually
consists of a series of terms and
their definitions.
<dt>
This is used to contain the term
being defined (the definition
term).
<dd>
This is used to contain the
definition


Nested list:
You can put a second list inside
an <li> element to create a sublist or nested list.

## Boxes
Box Dimensions (width, height) By default a box is sized just big enough to hold its contents.
 To set your own dimensions for a box you can use the height and width
div.box {
height: 300px;
width: 300px;
background-color: #bbbbaa;}
p {
height: 75%;
width: 75%;
background-color: #0088dd;}

overflow

The overflow property tells the
browser what to do if the content
contained within a box is larger
than the box itself. It can have
one of two values:
hidden
This property simply hides any
extra content that does not fit in
the box.
scroll
This property adds a scrollbar to
the box so that users can scroll
to see the missing content

Border: Every box has a border (even if
it is not visible or is specified to
be 0 pixels wide). The border
separates the edge of one box
from another.
 Margin: Margins sit outside the edge
of the border. You can set the
width of a margin to create a
gap between the borders of two
adjacent boxes.
- margin-top
- margin-right
- margin-bottom
- margin-left
Padding: Padding is the space between
the border of a box and any
content contained within it.
Adding padding can increase the
readability of its contents.
- padding-top
- padding-right
- padding-bottom
- padding-left

Border Style
- solid
- dotted
- dashed
- double
- groove
- ridge
- inset
- outset
- hidden/none

Border Color
- border-top-color
- border-right-color
- border-bottom-color
- border-left-color

Change Inline/Block
- inline
- block 
- inline-block
- none

Hiding Boxes
- hidden
- visible

border-image
p.one {
-moz-border-image: url("images/dots.gif")
 11 11 11 11 stretch;
-webkit-border-image: url("images/dots.gif")
 11 11 11 11 stretch;
border-image: url("images/dots.gif")
 11 11 11 11 stretch;}

box-shadow
- Horizontal offset
- Vertical offset
- Blur distance
- Spread of shadow

border-radius
- border-top-right-radius
- border-bottom-right-radius
- border-bottom-left-radius
- border-top-left-radius


## ARRAYS
An array is a special type of variable. It doesn't
just store one value; it stores a list of values. 
You create an array and give it
a name just like you would any
other variable (using the var
keyword followed by the name of
the array).
The values are assigned to the
array inside a pair of square
brackets, and each value is
separated by a comma. The
values in the array do not need
to be the same data type, so you
can store a string, a number and
a Boolean all in the same array

USING IF ... ELSE
STATEMENTS 
Here you can see that an
if ... e 1 se statement allows you
to provide two sets of code:
1. one set if the condition
evaluates to true
2. another set if the condition is
false 

SWITCH STATEMENTS 
A switch statement starts with a
variable called the switch value.
Each case indicates a possible
value for this variable and the
code that should run if the
variable matches that value. 

Loops:
Loops check a condition. If it returns true, acode block will run. then the condition will be checked 
again and if it still returns true, the code block will run again, it repeats until the condition returns
false.
Loops type:
- For
- while 
- Do while
