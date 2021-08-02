# React: Component Lifecycle Events:

**What are component lifecycle events?**

React lets you define components as classes or functions. The methods that you are able to use on these are called lifecycle events. These methods can be called during the lifecycle of a component, and they allow you to update the UI and application states.

![react lifecycle](https://miro.medium.com/max/2000/0*0saPKFiTUk6W3FYp)

### Mounting

When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase. Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting.

### Updating

Anytime a component is updated or state changes then it is rerendered. These lifecycle events happen during updating in this order.

### Unmounting

The final phase of the lifecycle if called when a component is being removed from the DOM. componentWillUnmount is the only lifecycle event during this phase.

--------------------------------------------------

### Rebuilt with React

React-Bootstrap replaces the Bootstrap JavaScript. Each component has been built from scratch as a true React component, without unneeded dependencies like jQuery.

As one of the oldest React libraries, React-Bootstrap has evolved and grown alongside React, making it an excellent choice as your UI foundation.

--------------------------------------------------
1. What types of things can you pass in the props?
 in React allows us to pass values from a parent component down to a child component. The values can be any data type, from strings to functions,

 2. What is the big difference between props and state?
 Basically, the difference is that state is something like attributes in OOP : it's something local to a class (component), used to better describe it. Props are like parameters - they are passed to a component from the caller of a component (the parent) : as if you called a function with certain parameters

3. When do we re-render our application?
React components automatically re-render whenever there is a change in their state or props. A simple update of the state, from anywhere in the code, causes all the User Interface (UI) elements to be re-rendered automatically. However, there may be cases where the render() method depends on some other data.

4. What are some examples of things that we could store in state?
When React was first introduced, we were presented with local state. The important thing to know about local state is that when a state value changes, it triggers a re-render.