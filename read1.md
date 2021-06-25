# Read:01 Java Basics

### Language Basics
*Variables*
The Java programming language defines the following kinds of variables:

- Instance Variables (Non-Static Fields) Technically speaking, objects store their individual 
  states in "non-static fields", that is, fields declared without the static keyword. Non-static fields are also known as instance variables because their values are unique to each instance of a class (to each object, in other words); the currentSpeed of one bicycle is independent from the currentSpeed of another.

 - Class Variables (Static Fields) A class variable is any field declared with the static 
   modifier; this tells the compiler that there is exactly one copy of this variable in existence, regardless of how many times the class has been instantiated. A field defining the number of gears for a particular kind of bicycle could be marked as static since conceptually the same number of gears will apply to all instances. The code static int numGears = 6; would create such a static field. Additionally, the keyword final could be added to indicate that the number of gears will never change.

- Local Variables Similar to how an object stores its state in fields, a method will often store 
  its temporary state in local variables. The syntax for declaring a local variable is similar to declaring a field (for example, int count = 0;). There is no special keyword designating a variable as local; that determination comes entirely from the location in which the variable is declared — which is between the opening and closing braces of a method. As such, local variables are only visible to the methods in which they are declared; they are not accessible from the rest of the class.

- Parameters You've already seen examples of parameters, both in the Bicycle class and in the 
  main method of the "Hello World!" application. Recall that the signature for the main method is public static void main(String[] args). Here, the args variable is the parameter to this method. The important thing to remember is that parameters are always classified as "variables" not "fields". This applies to other parameter-accepting constructs as well (such as constructors and exception handlers) that you'll learn about later in the tutorial.


*Naming*

Every programming language has its own set of rules and conventions for the kinds of names that you're allowed to use, and the Java programming language is no different. The rules and conventions for naming your variables can be summarized as follows:

- Variable names are case-sensitive. A variable's name can be any legal identifier — an 
  unlimited-length sequence of Unicode letters and digits, beginning with a letter, the dollar sign "$", or the underscore character "_". The convention, however, is to always begin your variable names with a letter, not "$" or "_". Additionally, the dollar sign character, by convention, is never used at all. You may find some situations where auto-generated names will contain the dollar sign, but your variable names should always avoid using it. A similar convention exists for the underscore character; while it's technically legal to begin your variable's name with "_", this practice is discouraged. White space is not permitted.

- Subsequent characters may be letters, digits, dollar signs, or underscore characters. 
  Conventions (and common sense) apply to this rule as well. When choosing a name for your variables, use full words instead of cryptic abbreviations. Doing so will make your code easier to read and understand. In many cases it will also make your code self-documenting; fields named cadence, speed, and gear, for example, are much more intuitive than abbreviated versions, such as s, c, and g. Also keep in mind that the name you choose must not be a keyword or reserved word.

- If the name you choose consists of only one word, spell that word in all lowercase letters. If 
  it consists of more than one word, capitalize the first letter of each subsequent word. The names gearRatio and currentGear are prime examples of this convention. If your variable stores a constant value, such as static final int NUM_GEARS = 6, the convention changes slightly, capitalizing every letter and separating subsequent words with the underscore character. By convention, the underscore character is never used elsewhere.


*Operators*
| Operators   | Precedence                                       |
| ----------- | -----------                                      |
| postfix     | expr++ expr--                                    |
| unary       | ++expr --expr +expr -expr ~ !                    |
| multiplicative| * / %                                          |
| additive    | + -                                              |
| shift       | << >> >>>                                        |
| relational  | < > <= >= instanceof                             |
| equality    | 	== !=                                        |
| bitwise AND | &                                                |
| bitwise exclusive OR | ^                                       |
| bitwise inclusive OR | |                                       |
| logical AND | &&                                               |
| logical OR  | ||                                               |
| ternary     | ? :                                              |
| assignment  | = += -= *= /= %= &= ^= |= <<= >>= >>>=           |



*Expressions*
An expression is a construct made up of variables, operators, and method invocations, which are constructed according to the syntax of the language, that evaluates to a single value. You've already seen examples of expressions, illustrated in bold below:

int cadence = 0;
anArray[0] = 100;
System.out.println("Element 1 at index 0: " + anArray[0]);

int result = 1 + 2; // result is now 3
if (value1 == value2) 
    System.out.println("value1 == value2");
	


*Blocks*
A block is a group of zero or more statements between balanced braces and can be used anywhere a single statement is allowed. The following example, BlockDemo, illustrates the use of blocks:

class BlockDemo {
     public static void main(String[] args) {
          boolean condition = true;
          if (condition) { // begin block 1
               System.out.println("Condition is true.");
          } // end block one
          else { // begin block 2
               System.out.println("Condition is false.");
          } // end block 2
     }
}
	
	
*Control Flow Statements*
The statements inside your source files are generally executed from top to bottom, in the order that they appear. Control flow statements, however, break up the flow of execution by employing decision making, looping, and branching, enabling your program to conditionally execute particular blocks of code. This section describes the decision-making statements (if-then, if-then-else, switch), the looping statements (for, while, do-while), and the branching statements (break, continue, return) supported by the Java programming language.
	
	
	
	
*Java’s API*

- Visit docs.oracle.com/javase/8/docs/api/.
- Click the INDEX link at the top of the page to open the index
- In the P section, do a search for println to find the println entries.
- Pick one of the println entries.
- Click the link for the entry that you’ve chosen.
  

*Using the list of classes*

- Visit docs.oracle.com/javase/8/docs/api/.
- Find the page that documents the System class.
- On the documentation page for the System class, find the out variable.
- In the table’s out row, click the PrintStream link.
- On the documentation page for PrintStream, find println(String).
  
	
