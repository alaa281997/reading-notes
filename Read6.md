# Read class 5
I start learing about object
> Objects: group together a set of variables and functions to create a model 
> of a something you would recognize from the real world. In an object,
> variables and functions take on new names.


#### Literal notation is the easiest and most popular way to create objects
> var hotel = {
> properties
> method
> }

#### Document Object Model :
> The Document Object Model (DOM) specifies how browsers should create a model of an HTML
> page and how JavaScript can access and update the contents of a web page while it is in the browser window. 


#### THE DOM TREE 
> IS A MODEL OF A WEB PAGE As a browser loads a web page, it creates a model of that page.
> The model is called a DOM tree, and it is stored in the browsers' memory. It consists of four main types of nodes. 

#### DOCUMENT NODE
> Above, you can see the HTML code for a shopping list, and on the right hand page is its DOM tree.
> Every element, attribute, and piece of text in the HTML is represented by its own DOM node. 

#### ELEMENT NODES
> HTML elements describe the structure of an HTML page. (The <h l > - <h6> elements describe what 
> parts are headings; the <p> tags indicate where paragraphs of text start and finish; and so on.) 

#### Individual elements:
> getElemenyById() and querySelector() can both search an entire document and return  individual elements
> get El ementByi d () allows you to select a single element node by specifying the value of its id attribute

#### SELECTING AN ELEMENT 
> FROM A NODELIST  There are two ways to select an element from a Nodelist: The item() method and array syntax. Both require the index number of the element you want. 

> querySe 1 ector() returns the first element node that matches the CSS-style selector. querySe 1ectorA11 () returns a
> Nodelist of all of the matches. 

#### TRAVERSING THE DOM 
> When you have an element node, you can select another element in relation to it using these five
> properties. This is known as traversing the DOM. 

#### WHITESPACE NODES 
> Traversing the DOM can be difficult because some browsers add a text node whenever they 
> come across whitespace between elements.

#### ACCESS & UPDATE A TEXT
> NODE WITH NODEVALUE When you select a text node, you can retrieve or amend the content of it 
> using the node Va 1 ue property. 

#### ACCESS & UPDATE TEXT & MARKUP WITH INNERHTML
> Using the i nnerHTML property, you can access and amend the contents of an element, including any child elements. 

#### ADDING ELEMENTS USING DOM MANIPULATION
> DOM manipulation offers another technique to add new content to a page (rather than i nnerHTML).

#### REMOVING ELEMENTS VIA 
- STORE THE ELEMENT TO BE REMOVED IN A VARIABLE
- STORE THE PARENT OF THAT ELEMENT IN A VARIABLE 
- REMOVE THE ELEMENT FROM ITS CONTA INING ELEMENT 