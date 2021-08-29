# State and Props 

[React lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’? render happens first.
- What is the very first thing to happen in the lifecycle of React? When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase the first thing happens is Constructor.
- Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates : constructor,render,componentDidMount,componentWillMount,React Updates.
- What does componentDidMount do?
This method is a good place to set up any subscriptions,we use componentDidMount() to connect to the YouTube API and get videos when the components is rendered.


[React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)


- What types of things can you pass in the props? in React allows us to pass values from a parent component down to a child component. The values can be any data type, from strings to functions, objects, etc.
- What is the big difference between props and state? The key difference between props and state is that state is internal and controlled by the component itself while props are external and controlled by whatever renders the component
- When do we re-render our application?
React components automatically re-render whenever there is a change in their state or props. A simple update of the state, from anywhere in the code, causes all the User Interface (UI) elements to be re-rendered automatically. However, there may be cases where the render() method depends on some other data.
- What are some examples of things that we could store in state? UI data that you could store in local state would be the currently selected tab from a list of options.

## Things I want to know more about
- [React Bootstrap](https://react-bootstrap.github.io/)  
- [Netlify](https://www.netlify.com/)  
- [React Docs - State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)  
- [React Docs - handling events](https://reactjs.org/docs/handling-events.html)  
- [React Tutorial through ‘Developer Tools’](https://reactjs.org/tutorial/tutorial.html)
