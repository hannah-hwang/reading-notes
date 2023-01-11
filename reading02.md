# Read: Class 02 State and Props

## React Lifecycle

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
\
Based of the diagram, 'componentDidMount' will happen first.
\
2. What is the very first thing to happen in the lifecycle of React?
\
The very first thing to happen in the React lifecycle is the *mounting* phase, where an instance of a component is being created and inserted into the DOM.
\
3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
\
constructor -> render -> React Updates -> componentDidMount -> componentWillUnmount
\
4. What does componentDidMount do?
\
The componentDidMount method will load anything using a network request and connect to APIs.
\

## React State vs. Props

1. What types of things can you pass in the props?
\
In a prop, you can pass arguments to a functions into a component.
\
2. What is the big difference between props and state?
\
In props, you pass into a component and is handled outside the component, while a state is handled inside the component.
\
3. When do we re-render our application?
\
We re-render our application when we want to update the state our application
\
4. What are some examples of things that we could store in state?
\
Some examples of what we could store in state are information needed to continually update the state, such as possible user input, or inside a form.
