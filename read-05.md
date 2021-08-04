# Putting it all together

### 1.How would you break a mock into a component heirarchy?

1. Break The UI Into A Component Hierarchy
The first thing you’ll want to do is to draw boxes around every component (and subcomponent) in the mock and give them all names. If you’re working with a designer, they may have already done this, so go talk to them! Their Photoshop layer names may end up being the names of your React components!
But how do you know what should be its own component? Use single responsibility principle , a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.


2. Thinking in React
React is, in our opinion, the premier way to build big, fast Web apps with JavaScript. It has scaled very well for Facebook and Instagram.
One of the many great parts of React is how it makes you think about apps as you build them. In this document, we’ll walk you through the thought process of building a searchable product data table using React.

3. Identify The Minimal (but complete) Representation Of UI
To make your UI interactive, you need to be able to trigger changes to your underlying data model. React achieves this with state .
The key here is DRY: Don’t Repeat Yourself . Figure out the absolute minimal representation of the state your application needs and compute everything else you need on-demand. For example, if you’re building a TODO list, keep an array of the TODO items around; don’t keep a separate state variable for the count. Instead, when you want to render the TODO count, take the length of the TODO items array.

4. Identify Where Your State Should Live.
See the Pen Thinking In React: Step 4 on CodePen .
OK, so we’ve identified what the minimal set of app state is. Next, we need to identify which component mutates, or owns , this state.
Remember: React is all about one-way data flow down the component hierarchy. It may not be immediately clear which component should own what state.


### 2.What is the single responsibility principle and how does it apply to components?

The single-responsibility principle (SRP) is a computer-programming principle that states that every module, class or function in a computer program should have responsibility over a single part of that program's functionality, and it should encapsulate that part.

### 3.What does it mean to build a ‘static’ version of your application?

What is a Static App? Static applications and websites render in the user's browser without the need for server side processing, this means that all the rendering of HTML, CSS, and JavaScript is done on the client side, rather then relying on server side technologies

### 4.Once you have a static application, what do you need to add?
i need to deploy it.

### 5.What are the three questions you can ask to determine if something is state?
1. Is it passed in from a parent via props? If so, it probably isn’t state.

2. Does it remain unchanged over time? If so, it probably isn’t state.
3. Can you compute it based on any other state or props in your component? If so, it isn’t state.


