## State and props

**Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount?**
The constructor is the first method that is called in the lifecycle of a React component. It initializes the component's state and props. Then, the render method is called, which returns a description of the UI that should be rendered. Finally, the componentDidMount method is called, which signals that the component has been mounted and is now ready to interact with the DOM and other components. So, in the diagram, the constructor happens first, followed by render and then componentDidMount.

**What is the very first thing to happen in the lifecycle of React?**
The very first thing to happen in the lifecycle of a React component is the constructor method. It is called when a component is created and initializes its state and props.

**Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates**
constructor

render

componentDidMount

React Updates

componentWillUnmount

**What does componentDidMount do?**
The componentDidMount method is called after a component has been mounted in the DOM. It is used to perform any setup that requires interaction with the browser environment, such as fetching data from an external API or initializing third-party libraries. It is also a good place to add event listeners or start animations. The componentDidMount method is only called once during the lifecycle of a component.

## Things I would like to know more about