


# React Docs - Forms

## What is a ‘Controlled Component’?

- [x] An input form element whose value is controlled by React.


- [x] In React, mutable state is typically kept in the state property of components, and only updated with setState().


- [x] React component that renders a form also controls what happens in that form on subsequent user input.


## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
- [x] store the users responses

## How do we target what the user is entering if we have an event handler on an input field?
- [x] When you need to handle multiple controlled input elements, you can add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.



# The Conditional (Ternary) Operator Explained
##  Why would we use a ternary operator?

- [x] The condition is what you’re actually testing. The result of your condition should be true or false or at least coerce to either boolean value.
- [x] A ? separates our conditional from our true value. Anything between the ? and the : is what is executed if the condition evaluates to true.
- [x] Finally a : colon. If your condition evaluates to false, any code after the colon is executed.

## Rewrite the following statement using a ternary statement:
 ## if(x===y){ console.log(true); } else { console.log(false); }
# solution below 



## x = ((x===y) ? console.log(true) : console.log(false))
