# Read class 2

### React
>React lets you define components as classes or functions. The   
 methods that you are able to use on these are called lifecycle events. These methods can be called during the lifecycle of a component, and they allow you to update the UI and application states.

### Mounting
> When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase. Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting. 

### Updating
> Updating
  Anytime a component is updated or state changes then it is rerendered. These lifecycle events happen during updating in this order.

### Unmounting
> The final phase of the lifecycle if called when a component is     being removed from the DOM. componentWillUnmount is the only    lifecycle event during this phase.

### constructor()
>The constructor for a React component is called before it is
 mounted.If the component is a subclass you should call super(props)or the props will be undefined. constructors can be used to assign state using this.state or to bind event handle methods to an instance. Let’s take a look at some example code.

### static getDerivedStateFromProps()
> This method exists for rare cases where the state relies on c   changes in props over time.
### render()
> Render is the only required method in a class component. It will   examine this.props and this.state when called. The render function should not modify the component state because it would cause a lot of bugs by changing the state every time it rerenders.

### componentDidMount()
> This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here.and use to connect to the YouTube API and get videos when the components is rendered. 

### getSnapshotBeforeUpdate()
> This is another rarely used method that allows you to capture a picture of the DOM to check it before actually changing anything on the DOM.
### componentDidUpdate()
> This method is useful for performing network requests after a  change has occurred. 

### componentWillUnmount()
> This method allows you to clean up the DOM and netwrok requests/ subscriptions.

### Questions
Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
use to connect to the YouTube API and get videos when the components is rendered

What is the very first thing to happen in the lifecycle of React?
Mounting

Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates?
constructor > render > componentDidMount >componentWillUnmount

What does componentDidMount do?
This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here.and use to connect to the YouTube API and get videos when the components is rendered.


What types of things can you pass in the props?
props as arguments to a function when you create a component inside of react and you want to render it you are going to pass it the props that you want to give it

What is the big difference between props and state?
state is handle  inside of a component and you can updated it but props is handle outside of a component and must be updated outside
When do we re-render our application?
When you need to rerender and update your application based what user has done (changes)
What are some examples of things that we could store in state?
when you want passing title and description down 