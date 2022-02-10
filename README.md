# REGEX Tutorial

In your journey of becomming a developer you will often utilize a REGEX within your algorithms. In this documentation we will discuss REGEX in the use of a Matching Email expression. A Regular Expression is commonly refered to as a REGEX amongst developers. 
A Regular expression utilizes a combination of patterns to recognize charecters. 

## Summary
The REGEX we will be discussing within this GIST is a Matching Email expression. We will deconstruct this following statement : /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/.  
We will identify all aspects which make up a Regular Expression such as Anchors, Quantifiers, Grouping Constructs and Charecter Escapes.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components
Below is the REGEX components:
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Anchors
When taking a first look at the REGEX expression you would assume the slash (/) is the anchor but make no mistake that is the delimeter. 
The Anchor is identified to be the Caret key (^).

### Quantifiers
For understanding the Quantifier of a REGEX statement refer to the root word being Quantity.  
A Quanitifier represents the amount of instances a character, group, or character class will be present within the client input.

To identify the Quantifiers within the espression think of Quantity. 
[9] {2,6} 

i.e

To learn more about Quantifiers head to :
https://docs.microsoft.com/en-us/dotnet/standard/base-types/quantifiers-in-regular-expressions

### Grouping Constructs
Grouping Construct outlines the subexpressions with a REGEX. 
Each Grouping Construct is identified by the use of Parenthesis ().


### Bracket Expressions
Bracket Expression is a bracket which has a list of charecters within.
Each Backet Expression is identified by the use of Brackets [].

### Character Classes
Charecter Classes defines the charecters within a string.

### The OR Operator

### Flags

### Character Escapes

## Author
Ava Williams
