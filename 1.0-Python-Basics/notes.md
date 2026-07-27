# Syntax And Semantics


Syntax refers to the set of rules that defines the combination of symbols that are considered to be correctly structured programs in a language. In simpler terms, syntax is about the correct arrangement of words and symbols in a code.


Semantics refers to the meaning and interpretation of the symbols, characters, and commands in a language. It is about what the code is supposed to do when it runs.


## Basic Rules of Syntax
### Case Sensitivity
### Indentation 
Indentation in Python is used to define the structure and hierarchy of code. Unlike many other programing languages that use braces {} to delimit blocks of code, Python uses indentation to determine grouping of statements. Thias means that all the statements within a block must be indented at the same level.  
(Python uses identation to define blocks of code. Consistent uses of spaces (commonly 4) or a tab is required)

### Understanding Semantics
In python the kernell automatically assigns the data type to the variable when it is entered and hence the variabele need not to be specified at every turn. 


# Variables
Variables are fundamental elements in programing language used to store data that can be referenced and manipulated in a program. In Python, variables are created when you assign a value to them, and they do not need explicit direction to reserve memory space. The decleration happens automatically when you assign a value to them. 
E.g:a=100

### Naming Conventions
1) Variables Name should be descriptive
2) They must start with a letter or an '_', and can contain letter numbers and underscore within them.
3) Variables name are case sensitive

Valid Varable name e.g: first_name, last_name;etc
Invalid Variable name e.g: 2age,first-name,@name;etc


### Understanding Variable Types
Python is dynamically typed and hence the type of variable is determined at runtime.
 
 ### Dynamic Typing
 Python allows the type of variable to change as the program executes


 # Data Types
Data types are a classification of data which tells the compiler or interpreter how the programmer intends to use the data.
They determine the types of operations that can be performed on data the values that the data can take and the amount of memory needed to store the data.

## Importance of Data types in Programming
1) Data types ensure that the data is stored in an efficient way
2) They help in performing correct operations on data
3) Proper use of data types can prevent errors and bugs in an program 
4) Memory Management


# Operators
## Logical Operators
And: when both the operators are bollean true then only we get true otherwise we will get false
Or: will return true even if one is bollean true among the two only returns false when both statements are false
Not: it is inverse of any bollean variable i.e if any bollean variable is assigned true adding not makes the final result false
