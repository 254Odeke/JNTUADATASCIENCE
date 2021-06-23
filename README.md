# JNTUADATASCIENCE

## Recorded Sessions [Link](https://docs.google.com/spreadsheets/d/1A7VKQQ1u7MiTd6D38txwhca7kd_jtifWrZSSRyQGMCQ/edit?usp=sharing)

## Markdown Cheat Sheet [Link](https://www.markdownguide.org/cheat-sheet/)
## Dataset [LINK](https://github.com/LavanyaPolamarasetty/Datasets)
## Day2 Agenda:
- Hello World...!
- Checking your python version 
- comments
- Variable  creation
    - A variable in programming is used to store the values/data
    - single variable assignment
    - Multi variable assignment
- Indentation
- **Data Types**
    - Text Type:	str
    - Numeric Types:	int, float, complex
    - Sequence Types:	list, tuple, range
    - Mapping Type:	dict
    - Set Types:	set, frozenset
    - Boolean Type:	bool

- Type Casting
- Dynamic Input Reading
- Operators

    A. Arithmetic Operators ( +,-,%,/,//,*)

    B. Assignment Operators ( =, +=, -=, *=, %=, /=, //=)

    C. Comparison operators ( ==, >=, <=, !=, >, < )

    D. Logical operators ( and, or, not )

    E. Bitwise Operators ( &, |, ~, ^, >>, <<)

    F. Identity Operators ( is , is not )

    G. Membership Operators ( in , not in )


# Day5 Agenda

### Strings
- Set of Characters
- Sequence of characters
- Strings are immutable
- any sequence of characters either with in single or double quotes
- A data type that stores a sequence of elements in character form.
- String Slicing
    - Indexing was only limited to accessing a single element, Slicing on the other hand is accessing a sequence of data inside the string.
- String Methods


# Day6 Agenda

***Data Structures***
- Data structures refer to the collection or group of data in a particular structure.

## List

Lists are the most commonly used data structure. Think of it as a sequence of data that is enclosed in square brackets and data are separated by a comma. Each of these data can be accessed by calling it's index value.

Lists are declared by just equating a variable to '[ ]' or list. We can use lists to hold an ordered sequence of values.

It holds different types of variables in the same list

Lists are mutable, their contents can change as more statements are interpreted.
 
### Methods

| Method Name | Use | Explanation |
|----|---|--|
| append | alist.append(item) | Adds a new item to the end of a list |
| insert	| alist.insert(i,item) |	Inserts an item at the ith position in a list |
|pop	|alist.pop()	|Removes and returns the last item in a list|
|sort|	alist.sort()|	Modifies a list to be sorted|
|reverse|	alist.reverse()|	Modifies a list to be in reverse order|
|del|	del alist[i]|	Deletes the item in the ith position|
|index|	alist.index(item)|	Returns the index of the first occurrence of item|
|count|	alist.count(item)|	Returns the number of occurrences of item|
|remove|	alist.remove(item)|	Removes the first occurrence of item|



# Day7 Agenda

- Set of key,value pair
- A dictionary is a collection which is unordered
- Changeable/ Mutable 
- Does not allow duplicates.
- In Dictionaries keys acts as a index to access values
- Dictionaries are written with curly brackets


| Method	| Description|
| --|--|
|clear()|	Removes all the elements from the dictionary|
|copy()|	Returns a copy of the dictionary|
|fromkeys()|	Returns a dictionary with the specified keys and value|
|get()|	Returns the value of the specified key|
|items()|	Returns a list containing a tuple for each key value pair|
|keys()|	Returns a list containing the dictionary's keys|
|pop()|	Removes the element with the specified key|
|popitem()|	Removes the last inserted key-value pair|
|setdefault()|	Returns the value of the specified key. If the key does not exist: insert the key, with the specified value|
|update()|	Updates the dictionary with the specified key-value pairs|
|values()|	Returns a list of all the values in the dictionary|


# Day9 Agenda
### Modules 

* a module is a piece of software that has a specific functionality
    - module makes the code easier to understand and use
* Module in python is simply a python file with .py extension
* The name of module will be the name of the file
* Some of the Modules in python:
    - math
    - random
    - Calendar
    - Collections
    - path
    - sys
    - pyttsx3
    - builtins
    - re 
    
### re
- it can also be called as re,regex
- A regular expression is a sequence of characters that match a pattern
- its a symbolic represtation
**Re Methods**
    - Match()
    - Search()
    - Findall()
   

|character | Usecase |
| -- | -- |
| ^ |        matches the begining|
| *  |       zero or more occurence|
 | +   |      one or more occurence|
| .    |     Matches any character except a newline.|
 | {}    |    range set|
| [a-zA-Z]|  alphbet range|
|[0-9]    | digits|
|$         | matches the ending|

##### regular expression Webiste [LINK](https://regex101.com/)
    
### Packages
* A package is a collection of modules




# Day Objectives

## OOP - Python
* What is Object Oriented Programming?

 *   To solve programming problem is by Creating Objects. This is known as OOPS
    Object Oriented Programming (OOP) allows decomposition of a problem into a number of units called objects
 *   Python, an Object Oriented programming (OOP), is a way of programming that focuses on using objects and classes to design and build applications.

* Why to Choose ObjectOriented Programming?

    * Python was designed with an object-oriented approach.

    * OOP offers the following advantages:
        Provides a clear program structure, which makes it easy to map real world problems and their solutions.
        Facilitates easy maintenance and modification of existing code.
     *  Imparts code reusability
      
***class***

  *  Combination of both attributes and methods
  *  A class is a way to take a grouping of functions and data and place them inside a container
    Ex: Building and Templates

* NOTE : Class attributes(variables) belong to the class itself they will be shared by all the instances.

*  Attributes are variables of a class that are shared between all of its instances


***object***

  *  An object is physical entity
  *  An object is an instance of a class. When class is defined, only the description for the object is defined. Therefore, no memory or storage is allocated.
  * Every Object contrains 2 Characteristics
      * State/Properties/Attributes
      * Behaviour


***method***

 * A name given to a function which is defined inside a class.They are used to define the behaviors of an object

#### Syntax for Class
```python
class ClassName:
    pass
ClassName()
```

# constructor
* Used for instantiating an object.In python *__init__*(self) Method called as a constructor
* It Works is to initialize(assign values) to the data members of a class when an object of a class is created.
* Types of constructors
    * Default constructor 
    * Parameterized constructor 

```Syntax of constructor declaration```

```python
class Person:
    def __init__(self): # defualt method for every class
```

## Python Inheritance

         * Inheritance enables us to define a class that takes all the functionality from a <br> 
           parent class and allows us to add more
         * It refers to defining a new class with little or no modification to an existing class
         * New class is called derived (or child) class 
         * One from which it inherits is called the base (or parent) class
![inheritence.jpg](inheritence.jpg)
#### The benefits of inheritance :
         * It provides re-usability of a code ("REUSE")
         * it allows us to add more features to a class without modifying it
         * It is transitive in nature
         * if class B inherits from another class A, then all the subclasses of B would automatically 
           inherit from class A.
                  

![Inheritance-Example-1024x512.png](attachment:Inheritance-Example-1024x512.png)


#### Advantages:
    * Application development time is less.
    * Application takes less memory.
    * Application execution time is less.

```Syntax```

```python 
    class superClass:
        body of super class
    class baseClass(superclass):
        body of the base class
```

# Types of Inheritence
- Single level Inheritence
- Multiple Inheritence
- Multi level Inheritence

## Single level Inheritence
- when a child class inherit from only one parent class, we called as single level inheritence

## Mutiple Inheritence
- More than one parent class but only one child class

## Multi level Inheritence
- having Grand Parent, parent and child relationship
