# Read class 9


#### Questions
- What is functional programming?
Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.


- What is a pure function and how do we know if something is a pure function?
 The first fundamental concept we learn when we want to understand functional programming is pure functions.

- What are the benefits of a pure function?
  It returns the same result if given the same arguments (it is also referred as deterministic).& It does not cause any observable side effects.

- What are the benefits of a pure function?
The code’s definitely easier to test. We don’t need to mock anything.

- What is immutability?
 Unchanging over time or unable to be changed.

- What is Referential transparency?
Basically, if a function consistently yields the same result for the same input, it is referentially transparent.
pure functions + immutable data = referential transparency


#### Questions

- What is a module?
Node.js has a set of built-in modules which you can use without any further installation.
- What does the word ‘require’ do?
 the easiest way to include modules that exist in separate files
- How do we bring another module into the file the we are working in? 
  require()
  
- What do we have to do to make a module available?
 by exports