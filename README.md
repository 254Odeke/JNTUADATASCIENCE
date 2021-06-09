# JNTUADATASCIENCE

## Recorded Sessions [Link](https://docs.google.com/spreadsheets/d/1A7VKQQ1u7MiTd6D38txwhca7kd_jtifWrZSSRyQGMCQ/edit?usp=sharing)

## Markdown Cheat Sheet [Link](https://www.markdownguide.org/cheat-sheet/)

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
