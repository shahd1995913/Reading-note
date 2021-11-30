# Conditional Rendering
## 1.  In React, you can create distinct components that encapsulate behavior you need.
## 2.  Then, you can render only some of them, depending on the state of your application.

### Conditional rendering  in React works the same way conditions work in JavaScript.
###  Use JavaScript operators like if or the conditional operator to create elements representing the current state, and let React update the UI to match them.
# Lists and Keys
##  Given the code below, we use the map() function to take an array of numbers and double their values.
## ssign the new array returned by map() to the variable doubled and log it.
## Rendering Multiple Components , can build collections of elements and include them in JSX using curly braces {}.

# Keys
## Keys help React identify which items have changed, are added, or are removed. 
## Keys should be given to the elements inside the array to give the elements a stable identity.
# Forms
## HTML form elements work a bit differently from other DOM elements in React, because form elements naturally keep some internal state. 

### Controlled Components
- [x] In HTML, form elements such as input, textarea, and select typically maintain their own state and update it based on user input. - [x]  In React, mutable state is typically kept in the state property of components, and only updated with setState().
- [x]   can combine the two by making the React state be the “single source of truth”. 
- [x]  Then the React component that renders a form also controls what happens in that form on subsequent user input. 
- [x] An input form element whose value is controlled by React in this way is called a “controlled component”. 


# Lifting State Up
## Often, several components need to reflect the same changing data
##  Recommend lifting the shared state up to their closest common ancestor.
- [x] There should be a single “source of truth” for any data that changes in a React application. 
- [x]  Usually, the state is first added to the component that needs it for rendering. 
- [x] Then, if other components also need it, you can lift it up to their closest common ancestor.
- [x]  Instead of trying to sync the state between different components, you should rely on the top-down data flow.