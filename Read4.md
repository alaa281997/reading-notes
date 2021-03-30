# class 4 reading
### Writing link 
Links are created using the <a> element. Users can click on anything
between the opening <a> tag and the closing </a> tag. You specify
which page you want to link to using the href attribute.

# <a> chapter-04/linking-to-other-sites.html HTML
    Links are created using the <a>
    element which has an attribute
    called href. The value of the
    href attribute is the page that
    you want people to go to when
    they click on the link.

> Relative URLs can be used when linking to pages within your own
 website. They provide a shorthand way of telling the browser where to
 find your files

#### mailto: chapter-04/email-links.html HTML
    To create a link that starts up
    the user's email program and
    addresses an email to a specified
    email address, you use the <a>
    element. However, this time the
    value of the href attribute starts
    with mailto: and is followed by
    the email address you want the
    email to be sent to.

# target
    If you want a link to open in a
    new window, you can use the
    target attribute on the opening
    <a> tag. The value of this
    attribute should be _blank.


# layouts
#### Building Blocks
    CSS treats each HTML element as if it is in its
    own box. This box will either be a block-level
    box or an inline box.

> CSS has the following positioning schemes that allow you to control
the layout of a page: normal flow, relative positioning, and absolute
positioning. You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property.

> In normal flow, each block-level element sits on top of the next
one. Since this is the default way in which browsers treat
HTML elements, you do not need a CSS property to indicate
that elements should appear in normal flow, but the syntax 

> Relative positioning moves an element in relation to where it would have been in normal flow

> When the position property is given a value of absolute,
the box is taken out of normal flow and no longer affects the
position of other elements on the page. (They act like it is not
there.) 

> It positions the element in relation to the browser window.
Therefore, when a user scrolls down the page, it stays in the
exact same place. It is a good idea to try this example in your
browser to see the effect. To control where the fixed
position box appears in relation to the browser window, the box
offset properties are used. In this example, the heading
has been positioned to the top left hand corner of the browser
window. When the user scrolls down the page, the paragraphs
disappear behind the heading.


> The <p> elements are in normal
flow and ignore the space that the <h1> element would have
taken up. Therefore, the margin-top property has
been used to push the first <p> element below where the fixed
position <h1> element is sitting.

### Result
h1 {
position: fixed;
top: 0px;
left: 50px;
padding: 10px;
margin: 0px;
width: 100%;
background-color: #efefef;}
p.example {
margin-top: 100px;}


#### CSS

<body>
<h1>The Evolution of the Bicycle</h1>
<p class="example">In 1817 Baron von Drais
 invented a walking machine that would help him
 get around the royal gardens faster...</p>
</body>
HTML chapter-15/position-fixed.html

The float property allows you to take an element in normal
flow and place it as far to the left or right of the containing
element as possible.

A lot of layouts place boxes next to each other. The float
property is commonly used to achieve this.

> The clear property allows you to say that no element (within
the same containing element) should touch the left or righthand sides of a box. It can take
the following values:
- left
- right
- both 
- none

Traditionally, developers got around this problem by adding
an extra element after the last floated box (inside the
containing element). A CSS rule would be applied to this
additional element setting the clear property to have a value
of both. But this meant that an extra element was added to the
HTML just to fix the height of the containing element.

Multi column Layouts  Many web pages use multiple
columns in their design. This is achieved by using a <div>
element to represent each column. The following three CSS
properties are used to position the columns next to each other:
- width
 This sets the width of the columns.
- float
This positions the columns next to each other.
- margin
This creates a gap between the columns.

### Screen Resolution
  Resolution refers to the number of dots a screen shows per inch. Some
  devices have a higher resolution than desktop computers and most
  operating systems allow users to adjust the resolution of their screens

### Page Sizes
  Because screen sizes and display resolutions vary so much, web
  designers often try to create pages of around 960-1000 pixels wide
  (since most users will be able to see designs this wide on their screens).

> Fixed width layout designs do not change size as the
user increases or decreases the size of their browser window.
Measurements tend to be given in pixels.

> Liquid layout designs stretch and contract as the user increases
or decreases the size of their browser window. They tend to use percentages.

> The liquid layout uses percentages to specify the width of each box so that the design
will stretch to fit the size of the screen.

> Layout Grids
Composition in any visual art (such as design, painting, or photography)
is the placement or arrangement of visual elements — how they are
organized on a page. Many designers use a grid structure to help them
position items on a page, and the same is true for web designers.


> Browsers require very detailed instructions about what
  we want them to do. Therefore, complex scripts can run
  to hundreds (even thousands) of lines. Programmers use
  functions, methods, and objects to organize their code.
  This chapter is divided into three sections that introduce: 
  FUNCTIONS & OBJECTS BUILT-IN.

> METHODS OBJECTS
  Functions consist of a In Chapter 1 you saw that The browser comes with
  series of statements programmers use objects a set of objects that act
  that have been grouped to create models of the like a toolkit for creating
  together because they world using data, and that interactive web pages.
  perform a specific task. objects are made up of This section introduces
  A method is the same as a properties and methods. you to a number of built-in
  function, except methods In this section, you learn objects, which you will
  are created inside (and are how to create your own then see used throughout
  part of) an object. objects using JavaScript. the rest of the book.

> WHAT IS A FUNCTION?
  Functions let you group a series of statements together to perform a
  specific task. If different parts of a script repeat the same task, you can
  reuse the function (rather than repeating the same set of statements). 

> HOW MEMORY & VARIABLES WORK
  Global variables use more memory. The browser has to remember them
  for as long as the web page using them is loaded. Local variables are only
  remembered during the period of time that a function is being executed. 
