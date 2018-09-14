# Module 1: Introduction to Data Science

## Python Fundamentals

### Data Science

* Intersection of hacking skills, math / stats, and substantive expertise
* skepticism, experimentation, simulation, and replication to answer questions
* you need to be able to communicate what you're talking about as well
* Deeper description (Donoho)
  * Data Exploration and Preparation
  * Data Representation and transformation
  * Computing with Data
  * Data Modeling (predictive and generative modeling)
  * Data Visualization and Presentation
  * Science about Data Science (meta data science. Understanding what works and doesn't)

### The Coursera Jupyter Notebook System

* Live python quizzes during the videos is pretty cool.

### Python Functions

Most of this is going to be happening in Jupyter so I probably won't be taking very many notes.

Python is high-level and interpreted. That means that it's designed to be read by humans, and it's not compiled - it executes as a script. It's also dynamically typed, which means that you can assign whatever you want to any variable.

#### Differences with Python functions.
1. You don't have to set a return type.
2. You don't have to use a return statement at all (returns None).
3. You can have default values for parameters.

You can also assign a function to a variable

### Python Types and Sequences

Dealing with the basic Python types. Doing a bit of text analysis.

Unpacking = you can assign multiple values through using tuples.

### Python More on Strings

* UTF is better than ASCII. Python uses unicode by default.
* Dynamic typing makes casting kind of confusing.
* Built in string formatting is very powerful.

### Demo: Reading and Writing CSV Files

Went through a demo about reading a CSV and performing some simple calculations

### Python Dates and Times

`time` and `datetime` modules are key.

### Advanced Python Objects, `map()`

Functions play a big role in Python, but you can also create objects and approach things with OOP. We won't be using Objects very often, because we're doing a lot of things through Jupyter.

Classes are named using CamelCase.

Objects in Python don't have private or protected items. (What about \_\_something?)

Functional programming - explicitly declare all parameters which could change through execution of a function. Described as "side-effect free". Python isn't purely functional, but you can do functional programming with Python. Think more heavily about chaining operations together. This means you'll see parameters of functions being functions themselves.

`map()`: map(function, iterable...)

### Advanced Python Lambda and List Comprehensions

Lambdas are Python's way of creating anonymous functions. Basically, you don't want to go through the trouble of creating a named function.

```
my_function = lambda a, b, c: a + b
my_function(1,2,3)
```

Much more limited than large function definitions, but they're good for data cleaning and quick function definitions.

Sequences are structures that we can iterate over. Python lets you create in an abbreviated fashion using list comprehension.

### Demo: The Numerical Python Library (NumPy)
