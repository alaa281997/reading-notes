#### Read class 4
#### ternary
>Controlled Components
In HTML, form elements such as <input>, <textarea>, and <select> typically maintain their own state and update it 
based on user input. In React, mutable state is typically kept in the state property of components, and only updated 
with setState().

>We can combine the two by making the React state be the “single source of truth”. Then the React component that 
renders a form also controls what happens in that form on subsequent user input.
 An input form element whose value is controlled by React in this way is called a “controlled component”.


>Handling Multiple Inputs
When you need to handle multiple controlled input elements, you can add a name attribute to each element and let the
 handler function choose what to do based on the value of event.target.name.

#### Questions

-  What is a ‘Controlled Component’?
 An input form element whose value is controlled by React 

- Should we wait to store the users responses from the form into state when they submit the form OR should we update the  state with their responses as soon as they enter them? Why.
 on every keystroke to update the React state, the displayed value will update as the user types

- How do we target what the user is entering if we have an event handler on an input field?
event handler for every way your data can change and pipe all of the input state through a React component.

#### Questions 

- ternary operator to change the value & we can nest   ternary   operators to test multiple conditions

- x===y ? true : false
  
