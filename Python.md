# Enriching Your Python Classes With Dunder (Magic, Special) Methods

## What Python’s “magic methods” are and how you would use them to make a simple account class more Pythonic.
## What Are Dunder Methods?
### In Python, special methods are a set of predefined methods you can use to enrich your classes. 
### They are easy to recognize because they start and end with double underscores, for example __init__ or __str__.
### As it quickly became tiresome to say under-under-method-under-under Pythonistas adopted the term “dunder methods”, a short form of “double under.”
- [x] These “dunders” or “special methods” in Python are also sometimes called “magic methods.”'
- [x]  But using this terminology can make them seem more complicated than they really are—at the end of the day there’s nothing “magical” about them.
- [x]  You should treat these methods like a normal language feature.
# Special Methods and the Python Data Model
## This elegant design is known as the Python data model and lets developers tap into rich language features like sequences, iteration, operator overloading, attribute access, etc.

## Enriching a Simple Account Class
## enrich a simple Python class with various dunder methods to unlock the following language features:

- [x] Initialization of new objects
- [x] Object representation
- [x] Enable iteration
- [x] Operator overloading (comparison)
- [x] Operator overloading (addition)
- [x] Method invocation
- [x] Context manager support (with statement)
# Python Iterators
## Python Iterators That Iterate Forever
- [x]  a class that demonstrates the bare-bones iterator protocol in Python.
- [x]  so far we’ve only implemented iterators that kept on iterating forever.
- [x] Clearly, infinite repetition isn’t the main use case for iterators in Python. 
- [x]   BoundedRepeater : want it to stop after a predefined number of repetitions.
- [x]  iterators provide a sequence interface to Python objects that’s memory efficient and considered Pythonic. Behold the beauty of the for-in loop!
- [x]  To support iteration an object needs to implement the iterator protocol by providing the __iter__ and __next__ dunder methods.
- [x] Class-based iterators are only one way to write iterable objects in Python. Also consider generators and generator expressions.