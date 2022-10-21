# Regex tutorial

## Summary

Regular Expressions, or regex for short, are a character squence that determins a searching patern for text. They are often used in text to find, or even find and replace. They are also useful to validate inputs. Conceptually regular expressions have been around since the 1950's, but they began being used on Unix platforms in the 80's.

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

## Regex Components

### Anchors
^ beginning of string or line  
$ end of string  
\A start of string  
\Z end of string  
\b word boundary  
\< start of word  
\> end of word  

### Quantifiers
* 0 or more
+ 1 or more
? 0 or 1 optional
{3} Exactly 3
{3,} 3 or more
{2,5} 2,3,4, or 5

### OR Operator
| or..

### Character Classes
\c control character
\s whitespace
\S not whitespace
\d digit [0-9]
\D not digit [^0-9]
\w word [A-Za-z0-9]
\w not word [^A-Za-z0-9]

### Flags (might also be know as modifiers)
//g global match
//i case insensitive
//m multiple line
//x allow comments and whitespace
//e evaluate replacement
//U ungreedy pattern

### Grouping and Capturing
. any character except newline (\n)
(a|b) a or b
(...) group
(?:...) passive (non-capturing) group
[abc] single character (a or b or c)
[^abc] single character (not a or b or c)
[a-q] single character range (a or b ...or q)
[A-Z] single character range (A or B ...or Z)
[0-9] single digit from 0 to 9

### Bracket Expressions
[] chars to match go inside. hyphens define ranges

### Greedy and Lazy Match
Greedy: as many as possible
Lazy: as few as possible

### Boundaries
\b word boundary

### Back-references
[-/] matches same text as previous

### Look-ahead and Look-behind
?= lookahead assertion
?<= lookbehind assertion

## Author

Matt Hendricks https://github.com/hale-bopp97
