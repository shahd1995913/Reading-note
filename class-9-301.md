# Functional Programming Concepts
## What is functional programming?

### Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data 

## What is a pure function and how do we know if something is a pure function?

### It returns the same result if given the same arguments (it is also referred as deterministic)
### It does not cause any observable side effects

## What are the benefits of a pure function?

1. The code’s definitely easier to test.
2.  We don’t need to mock anything.
3.  So we can unit test pure functions with different contexts:
### Given a parameter A → expect the function to return value B
### Given a parameter C → expect the function to return value D
## What is immutability?
### Unchanging over time or unable to be changed.
### When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

## What is Referential transparency?

### pure functions + immutable data = referential transparency
###  if a function consistently yields the same result for the same input, it is referentially transparent.