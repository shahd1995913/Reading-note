# Assets, Metadata, and CSS

## Metadata
### What if we wanted to modify the metadata of the page, such as the title HTML tag ?
### --> title is part of the head HTML tag, so let's dive into how we can modify the head tag in a Next.js page.

## Writing and Importing CSS
### Next.js has built-in support for CSS and Sass which allows you to import .css and .scss files.

### Using popular CSS libraries like Tailwind CSS is also supported.

###  Next.js’s built-in support for CSS Modules and Sass.

# Create a Next.js App
## To build a complete web application with React from scratch,
## there are many important details you need to consider:

1. Code has to be bundled using a bundler like webpack and transformed using a compiler like Babel.
2. need to do production optimizations such as code splitting.
3.  might want to statically pre-render some pages for performance and SEO. 
4.  might also want to use server-side rendering or client-side rendering.
5.  might have to write some server-side code to connect your React app to your data store.
### A framework can solve these problems. But such a framework must have the right level of abstraction — otherwise it won’t be very useful. 
### It also needs to have great "Developer Experience", ensuring you and your team have an amazing experience while writing code.

## Next.js: The React Framework
### the React Framework. Next.js provides a solution to all of the above problems. 
## Create a Next.js app
- [x]  To create a Next.js app, open terminal, cd into the directory you’d like to create the app in.
- [x]    npx create-next-app nextjs-blog --use-npm --example "https://github.com/vercel/next-learn/tree/master/basics/learn-starter"
## Run the development server
- [x]  have a new directory called nextjs-blog
- [x]  cd nextjs-blog
 - [x]  npm run dev
 ## Welcome to Next.js
 - [x] You should see a page like this when you access http://localhost:3000. 
  - [x] This is the starter template page which shows some helpful information about Next.js.
# React context caveats
## Why it is not possible to update the value that React context passes down?

### While it is possible to combine React context with a hook like useReducer and create a makeshift state management library without any third-party library, it is generally not recommended for performance reasons.
### The issue with this approach lies in the way that React context triggers a re-render.
- [x] This may not be a performance issue in smaller apps with few state values that are not updated very often (such as theme data). - - [x]  But it is a problem if you will be performing many state updates in an application with a lot of components in your component tree.

## This information from those links :
### 1. [NextJs](https://nextjs.org/learn/basics/getting-started) 
### 2. [The React](https://www.freecodecamp.org/news/react-context-for-beginners/) 