# ES6 Overview 
# ES6 Syntax and Feature Overview
##  ES6, introduced many changes to JavaScript. Here is an overview of some of the most common features and syntactical differences, with comparisons to ES5 where applicable.
## Legend :  Here is a key of most identifier names used throughout this reference.

- [x]  Variable: x
- [x] Object: obj
- [x] Array: arr
- [x] Function: func
- [x] Parameter, method: a, b, c
- [x] String: str

## Variable declaration : ES6 introduced the let keyword, which allows for block-scoped variables which cannot be hoisted or redeclared.
# React 

## Handling Events
### Handling events with React elements is very similar to handling events on DOM elements. 
### --> There are some syntax differences:

1.  React events are named using camelCase, rather than lowercase.

2. With JSX you pass a function as the event handler, rather than a string.
## State and Lifecycle
###   the concept of state and lifecycle in a React component. You  
### Converting a Function to a Class
### convert a function component like Clock to a class in five steps:

1. Create an ES6 class, with the same name, that extends React.Component.
2. Add a single empty method to it called render().
3. Move the body of the function into the render() method.
4. Replace props with this.props in the render() body.
5. Delete the remaining empty function declaration.



## Adding Lifecycle Methods to a Class
### In applications with many components, it’s very important to free up resources taken by the components when they are destroyed.

### set up a timer whenever the Clock is rendered to the DOM for the first time. This is called “mounting” in React.

### clear that timer whenever the DOM produced by the Clock is removed. This is called “unmounting” in React.

### declare special methods on the component class to run some code when a component mounts and unmounts.
# Create a Next.js App

##  To build a complete web application with React from scratch, there are many important details you need to consider:

1. Code has to be bundled using a bundler like webpack and transformed using a compiler like Babel.
2. You need to do production optimizations such as code splitting.
3. You might want to statically pre-render some pages for performance and SEO. 
4. You might also want to use server-side rendering or client-side rendering.
5. You might have to write some server-side code to connect your React app to your data store.
6. A framework can solve these problems. 
### Next.js: The React Framework
### --> Enter Next.js, the React Framework. Next.js provides a solution to all of the above problems. But more importantly, it puts you and your team in the pit of success when building React applications.

