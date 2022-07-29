# Intermediate Software Development: Class 02

* Class notes for Code 301 with code fellows, starting July 16, 2022 ending September 17, 2022

## Class 2 - July 18, 2022

### *Reading 2: State and Props*

#### [React lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

- Render occurs before componentDidMount

What is the very first thing to happen in the lifecycle of React?

- The very first thing to happen in the lifecycle of React is Mounting in which the constructor is called first.

Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

- constructor
- render
- componentDidMount
- componentWillUnmount
- react updates

What does componentDidMount do?

- componentDidMount creates a space for loading or initializing DOM nodes after a component is mounted.

#### [React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

What types of things can you pass in the props?

- You can pass any data type in props

What is the big difference between props and state?

- props are passed into a component from outside, and state is handled inside the component

When do we re-render our application?

- We re-render our application when the state changes after user interaction.

What are some examples of things that we could store in state?

- You can store the values of user input in state
