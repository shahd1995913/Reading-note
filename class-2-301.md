
# State and Lifecycle




## Converting a Function to a Class
### You can convert a function component like Clock to a class in five steps:

- [x]  Create an ES6 class, with the same name, that extends React.Component.
- [x]  Add a single empty method to it called render().
- [x] Move the body of the function into the render() method.
- [x]  Replace props with this.props in the render() body.
- [x] Delete the remaining empty function declaration.

##  React: Component Lifecycle Events

*  React lets you define components as classes or functions. The methods that you are able to use on these are called lifecycle events. 
* These methods can be called during the lifecycle of a component, and they allow you to update the UI and application states.





##  What are the three phases of the component lifecycle?

1. [x] Mounting
2. [x] Updating
3. [x] Unmounting



##  What are the 3 phases of the component lifecycle explanations ?

## 1. Mounting
* When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase. Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting.
## 2. Updating
* Anytime a component is updated or state changes then it is rerendered. These lifecycle events happen during updating in this order.


## 3. Unmounting
* The final phase of the lifecycle if called when a component is being removed from the DOM. componentWillUnmount is the only lifecycle event during this phase.**

