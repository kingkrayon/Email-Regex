# Email Regex

Thsi regex turtorial provides a breakdown of what makes up the regex for Matching an email. Regex in general is good for extracting information from any text. 

This is the regex that we will be breaking down : /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Our Regex Componets

###  Our Anchors are ^, $

### Quantifiers
These would be our brackets in this regex. They match to anything thats contaied within them. In this specific regex they are used before the @symbol and after. they inculde such a wide range for finding/matching to find any iteration of an eamil, 

### OR Operator

### Character Classes
The Character classes are the parts of the expression that read as "\da-z, or \.". the "." determines that it will match any single character besides trhe newline character. 

### Flags

### Grouping and Capturing
