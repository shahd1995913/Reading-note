
# Component-Based Architecture

## 1.  What is a component?

- [x]  A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.
- [x]  A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities. It has an obviously defined interface and conforms to a recommended behavior common to all components within an architecture. 
- [x] A software component can be defined as a unit of composition with a contractually specified interface and explicit context dependencies only. That is, a software component can be deployed independently and is subject to composition by third parties.

## 2. What are the charactistics of a component?

1. Reusability

 * Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.

2. Replaceable
*  Components may be freely substituted with other similar components.

3. Not context specific 
 * Components are designed to operate in different environments and contexts.

4. Extensible
*  A component can be extended from existing components to provide new behavior.

5. Encapsulated 
* A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.

6. Independent 
* Components are designed to have minimal dependencies on other components.



## 3. What are the advantages of using component based architecture?

1. [x] Ease of deployment
2. [x] Reduced cost 
3. [x] Ease of development 
4. [x] Reusable
5. [x] Modification of technical complexity
6. [x] Reliability 
7. [x] System maintenance and evolution


# What is “Props” and how to use it in React?



## 1. What is props short for?

**“Props” is a special keyword in React, which stands for properties and is being used for passing data from one component to another. Furthermore, props data is read-only, which means that data coming from the parent should not be changed by child components.**


## 2. How are props used in React?

* Firstly, define an attribute and its value(data)
* Then pass it to child component(s) by using Props
* Finally, render the Props Data

## 3. What is the flow of props?
* data with props are being passed in a uni-directional flow.
* (one way from parent to child)