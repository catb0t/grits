# Grits #
Grits is a dynamic, interpreted (and semi-esoteric) programming language created by Davie Janeway in 2009.

---


## Language Specification ##

### Overview ###
The Grits interpreter reads source files line-by-line. This means there is no support for multi-line expressions of any kind. All Grits constructs begin and end on the same line.

### Whitespace ###
For the most part, whitespace is ignored by the interpreter. However, certain constructs are whitespace sensitive. For instance, expressions within a Function (see functions) are separated by whitespace (Although, this is liable to change before Grits v1.0), meaning that they have to be written in a specific manner.
Empty lines are ignored.

### Comments ###
Grits does not support multi-line or inline comments. A line enclosed by triple dots is considered to be a comment.

Example:
```
...This is a comment...
```

### Variables ###

### Functions ###