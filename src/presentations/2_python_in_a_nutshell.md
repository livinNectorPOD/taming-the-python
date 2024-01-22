---
marp: true
paginate: true
headingDivider: 2
footer: Programming in Python, IITM Online BS Degree in Data Science
---
# Python In a NutShell (PINS) :snake: :peanuts:

# Hello World
```python
print("Hello World 🌏, I am Python \N{snake}")
name = input("Your name? ") # when this appears type something
print(f"Hello {name}")
print("வணக்கம்", name)
print(f"नमस्ते {name}")
```
- Python book Lesson [**1.1**](https://bsc-iitm.github.io/python-textbook/chapter-1/lesson-1.1/#emojis) - Prompt(input), Output, and emojis
- [List of emojis](https://unicode.org/emoji/charts/full-emoji-list.html)
- Ask AI
  > Print hello world with emojis

# Things in Python
* Literals - values
* Variables - value holders
* Datatype - type of value
* Functions - does something with the value 
* Objects - includes built in data types, functions, instances of user defined classes
* Libraries/ Modules - Things in other files


# Data Types

## Normal Numbers (integers) 
- Eg. `1, 3244, 1_000_000` - `int`
- Python Book Lesson [**1.1**](https://bsc-iitm.github.io/python-textbook/chapter-1/lesson-1.1/#literals-and-variables)
- Ask AI
>**Things you can do with python integers, different operators, big num underscore, ways to input and printing it, order of evaluation of complex expressions, with examples.**

## Numbers with a decimal point (floating point numbers) - `float`
- Eg. `1.3`, `1342.24215`, `3.2e-23`, `float('nan')`, `float('inf')`
- Python Book Lesson [**1.2**](https://bsc-iitm.github.io/python-textbook/chapter-1/lesson-1.2/), [**1.3**](https://bsc-iitm.github.io/python-textbook/chapter-1/lesson-1.3/)
- Ask AI
> **Things you can do with python floating, ways to input and printing it, with examples.**

## Text (string) - `str`
- Eg. `"Hello World"`, `'hello'`, `"Hello " 'world'`

```python
multiline_str = ''''This is a multiline String.
This will come in next line'''
```
- Python Book Lesson [**1.5**](https://bsc-iitm.github.io/python-textbook/chapter-1/lesson-1.5/), [**1.6**](https://bsc-iitm.github.io/python-textbook/chapter-1/lesson-1.5/)
- Ask AI
> **Things you can do with python strings, concatenation, tricks with slicing, and formatting, string functions, case change, spliting, joining, and others with examples**

## Boolean (True/False) - `bool`
  - Eg. `True`, `False`
  - Python Book Lesson [**1.3**](https://bsc-iitm.github.io/python-textbook/chapter-1/lesson-1.3/#boolean-expressions)
  - Ask AI
  >**Explain the relationship between conditionals, logical expressions and boolean variables in python, where to use it use cases, with examples.**  

  >**Give examples on how boolean type is useful along various other data structures in python**

## None - just None and nothing else - `None`
  >**None, NoneType, and places where you could find None in python and places where you could use it with examples**
## List - Ordered items - `list`
  - Eg. `[1, "Hello", 2.34, (3,4,4), [2,3,[1,2]]]`
  - 
  - Ask AI
  >**Things I can do with Lists in python a cheatsheet and usecase examples**
  >**Contrast the difference between sorted(L) and L.sort(), and explain how one can sort with key and reverse with examples**

## Tuple - Ordered items that you cannot modify - `tuple`
  - Python Book Lesson [**5.6**](https://bsc-iitm.github.io/python-textbook/chapter-5/lesson-5.6/)
  - Ask AI
    >**Usecases of tuples with examples**

## Set - unique items - `set`
  - Python Book Lesson [**6.5**](https://bsc-iitm.github.io/python-textbook/chapter-6/lesson-6.5/)
  - Ask AI
  >**Give examples of set operations and examples of algorithms that uses sets**

  >**Discuss what are the datatypes that could be added to set**
  
## Dictionary - Key(like a word) - value(like the meaning of the word) pair - `dict`
  - Python Book Lesson [6.3](https://bsc-iitm.github.io/python-textbook/chapter-6/lesson-6.3/) and [6.4](https://bsc-iitm.github.io/python-textbook/chapter-6/lesson-6.4/)
  - Ask AI
  >**Things I can do with Dictionary in python a cheatsheet, ways of creating, iterating and modifying.**

## Type Conversion
  - Type of anything can be checked using `type()` fucntion.
  - Most of the python types are convertible to an other type. Eg., `int(5.6)` , `str(546)`, `float("53.2")`
  - Colection like types can be converted to any other collection like type. Eg., `set([1,2,2,3])`, `list((1,2,3))`, `dict([("a",1), ("b",2)])`
  - **Anything** can be converted to string. Eg., `str(print)`, `str(int)`
  - Also anything can be printed because anything can be converted into string.

## More on Datatypes To ask AI
>**Common things that can be done with all collection like datatypes (str, list, tuple, set, dict,etc.) in python**
>**Explain debugging and How to use functions such as print, id, type to debug a python code with examples**

>**Compare and contrast List, tuple, set, dictionary, in a table format and the types of items it can hold, and give examples**

>**List out the mutable and immutable types, explain what is mutability with examples on each type, also give examples of functions that modifies an object, and returns new objects**

## More on Datatypes To ask AI

>**Explain the mechanism of slicing in python with visual representation with index, what happens when you dont mention a value in a slice and different usecases of slicing in performing simple tasks with examples**


>**Explain common errors in python, how they occur and how to correct them with examples**

- You can use AI to get sample problems and usecase examples.
>**Demonstrate and explain a simple algorithm that uses [concept] in python**

- You can use AI to get the common types of errors and errors related to a data structure.




# Control structures

## Conditionals

### if , if ... else, if ... elif... else, nested if else ....
  - **Ask AI**
  >**Give me various ways of using if, else and elif from simple to complex usecases using examples**
  
## Loops

### `for` - does the same thing for every item in a collection of items

>**explain how range function in python works, and how we can use for loop effectively without range with examples**
>**examples of using enumerate, to write a more readable code, contrast it with examples of not using it.**
---
### `while` - repeats until some condition is true

>**Give examples of algorthms where a while loop is preferred over a for loop in python**
>**Compare and contrast the item based and condition based nature of for and while loops in python respectively with examples**
---
### `break` and `continue` inside a loop

>**Explain usecases of break and continue from simple to nested loops using sample algorithms**
>**Simple algorithms that use break and continue with examples**


## Functions (first step to **DRY**(Do not Repeat Yourself))
  - Python Textbook Lesson [**4.1**](https://bsc-iitm.github.io/python-textbook/chapter-4/lesson-4.1/)
  - use `snake_case` for function names
  - Ask AI

  
## Objects (A more organized way to **DRY**)
 - Some thing that is made by putting together the data types and functions.
 - Has attributes (some property or parameter or state of the object)
 - Has methods (an objects own functions)
 - use `PascalCase` for class names.

## Modules / Libraries (items from a different file)
  - Python book lesson [2.4](https://bsc-iitm.github.io/python-textbook/chapter-2/lesson-2.4/#library)
  - You can import variables, functions, classes, objects from other files
  - Ask AI
  >**Explain different ways importing in python with examples**
  >**Write your own simple python module to explain me differnt ways of importing**

## File Handling(reading and writing files)
- Python book Chapter [7](https://bsc-iitm.github.io/python-textbook/chapter-7/lesson-7.1/)
- Ask AI
  > Compare file handling using open and close functions with file handling using the with ... open context manager syntax with examples and why using context manager is prefered over the other.

  > Give me a sample program that reads a file line by line and converts to uppercase and write it into another file.
## Error Handling(what to do if an error occurs)

# Note on naming things in python
- Name the variables of collections (`list`, `set`) with plural words like `students`, `words`, `lines` etc.
- Name the functions with imperative words(commands) like ,`do_something()`, `convert()`, `make_that()`, `compute_this()`,  etc
- Name boolean functions using assumption statements like `is_black()`, `is_valid()`, `has_this_property()`
```python
if is_valid(a):
  do_something()
else:
  print("a is not valid")
```
- Name classes with names of entities in pascal case like `Student`, `Car`, `Item`, etc.

# Intermideate(Writing pythonic code)

These things makes your lives easier, and helps you write pythoinic code.

* inbuilt functions
  * map, filter, zip, enumerate
  * min, max, sorted, reverse, all, any
* comprehensions
* lambda function

