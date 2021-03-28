## Read class 2
Chapter 2
Headings in HTML has six "levels" of headings: h1 is used for main headings h2 is used for subheadings
Browsers display the contents of headings at different sizes.
Paragraphs To create a paragraph, surround the words that make up the paragraph with an opening p
tag and closing p tag.
Bold & Italic 
Superscript The sup element is used to contain characters that should be superscript such as the suffixes of dates or
mathematical concepts like raising a number to a power such as 22
 Subscrip The sub element is used to contain characters that should be subscript. It is commonly
used with foot notes or chemicalformulas such as H20.

### br 
As you have already seen, the browser will automatically show each new paragraph or heading
on a new line. But if you wanted to add a line break inside the middle of a paragraph you can
use the line break tag br.

### hr
To create a break between themes — such as a change of topic in a book or a new scene
in a play — you can add a horizontal rule between sections using the hr  tag.

### strong
The use of the strong element indicates that its content has strong importance.
For example, the words contained in this element might be said with strong emphasis.

### em
The em element indicates emphasis that subtly changes the meaning of a sentence.
By default browsers will show the contents of an em element in italic

## CSS
CSS allows you to create rules that control the
way that each individual box (and the contents
of that box) is presented.

### link
chapter-10/using-external-css.html HTML
The link tag element can be used in an HTML document to tell the
browser where to find the CSS file used to style the page. 

### style
You can also include CSS rules within an HTML page by placing them inside a style element,
which usually sits inside the head element of the page

### STATEMENTS
A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement.
Statements should end with a semicolon.

### comments /*  */
They help make your code easier to read and understand.
This can help you and others who read your code.

### variable 
A script will have to temporarily store the bits of information it
needs to do its job. It can store this data in variables.

### DATA TYPES 
 - NUMERIC DATA TYPE 
 - STRING DATA TYPE 
 - BOOLEAN DATA TYPE 

### ARRAYS
An array is a special type of variable. It doesn't
just store one value; it stores a list of values. 

### ARITHMETI  OPERATORS

| operators    |Sym|
| ---------    |---|
|Addition      | + |
|Subtraction   | - |
|Division      | / |
|Multiplication| * |
|Incrment      | ++|
|Decrement     | --|
|Modulus       | &&|

#### logical operators
allow you to compare the resuts of more than one comparison operator
(("Hello" == "Hello") && (2 >= 5))

 #### &&/AND this operator tests more than one condition
 - T && T = TRUE
 - T && F = FALSE
 - F && T = FALSE
 - F && F = FALSE

#### ||/OR this operator tests at least one conditions
 - T || T = TRUE
 - T || F = TRUE
 - F || T = TRUE
 - F || F = FALSE

#### !/NOT this operator takes a single boolean value and invertsit
 - !true = false
 - !false = true

#### loops 
loops check a condition if it returns true a code block will run 
then the condition will be checked again and if it still returns true,
the code block will run again it repeats until the condition returns false there are three common types of loops:
- for = a condition usually a counter.
- while = if the condition is true it will keep run
- do while = it will always run the statments at least once even if the condition evaluates to false

- for loop 
 - for (Initialization; condition ; update )

- while loop 
 - while (i<5){
    This loop will continue to run
    for as long as the condition in
     the parentheses is true. T
    }
