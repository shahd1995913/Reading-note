# Python Scope & the LEGB Rule: Resolving Names in Your Code
##  Several programming languages take advantage of scope for avoiding name collisions and unpredictable behaviors. 
## two general scopes:

### 1. Global scope: 
- The names that you define in this scope are available to all your code.

### 2. Local scope: 
- The names that you define in this scope are only available or visible to the code within the scope.
## Python Scope vs Namespace
### -  In Python, the concept of scope is closely related to the concept of the namespace.
### -  a Python scope determines where in your program a name is visible.
### -  Python scopes are implemented as dictionaries that map names to objects. 
### -  These dictionaries are commonly called namespaces. 
### -  These are the concrete mechanisms that Python uses to store names.
### -  They’re stored in a special attribute called .__dict__.

### -  Names at the top level of a module are stored in the module’s namespace.
### -  In other words, they’re stored in the module’s .__dict__ attribute. 
## Using the LEGB Rule for Python Scope
###  1.   Python resolves names using the so-called LEGB rule, which is named after the Python scope for names. 
### 2. The letters in LEGB stand for Local, Enclosing, Global, and Built-in.

### 1.1 Local (or function) :
-  scope is the code block or body of any Python function or lambda expression. 
- This Python scope contains the names that you define inside the function. 
- These names will only be visible from the code of the function. 

### 1.2 Enclosing (or nonlocal) :
- scope is a special scope that only exists for nested functions.
-  If the local scope is an inner or nested function, then the enclosing scope is the scope of the outer or enclosing function. 
- This scope contains the names that you define in the enclosing function. 

### 1.3 Global (or module) :
-  scope is the top-most scope in a Python program, script, or module.
-  This Python scope contains all of the names that you define at the top level of a program or a module. 
- Names in this Python scope are visible from everywhere in your code.

### 1.4 Built-in scope :
- is a special Python scope that’s created or loaded whenever you run a script or open an interactive session.
-  This scope contains names such as keywords, functions, exceptions, and other attributes that are built into Python.
-  Names in this Python scope are also available from everywhere in your code.
