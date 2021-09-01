

# React Docs - thinking in React

## How would you break a mock into a component heirarchy?
- [x] One such technique is the single responsibility principle, that is, a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.



## What is the single responsibility principle and how does it apply to components?
- [x]   component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

## What does it mean to build a ‘static’ version of your application?
- [x] a static version requires a lot of typing and no thinking, and adding interactivity requires a lot of thinking and not a lot of typing
- [x] To build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props. props are a way of passing data from parent to child.

## Once you have a static application, what do you need to add?
- [x] If you make a change to your underlying data model and call ReactDOM.render() again, the UI will be updated. You can see how your UI is updated and where to make changes

## What are the three questions you can ask to determine if something is state?
- [x] The search text the user has entered
- [x] The value of the checkbox


## How can you identify where state needs to live?
- [x] It conceptually makes sense for the filter text and checked value to live in FilterableProductTable