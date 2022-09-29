# Email Validation 

A regular expression is a method of searching strings to ensure they contain certain things that are specified in the text of the regular expression. For this readme, I will be describing a regular expression to ensure a given string is an email.

## Summary

^[A-Z0-9+_.-]+@[A-Z0-9.-]+$
This is a regex expression that validates emails.

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

Components of the regex include the backslashes before various special characters which indicates that the special characters may be used on their own. The brackets ensure that everything in it is can be read individually. An alternative example would be b[aeiou]nk potentially reading 'bank' or 'bonk', or 'bunk' (Or any other of the non words created by that.). The parentheses ensure that certain parts must contain certain character combinations.

### Anchors

The opening ^ and closing $ are anchors. They indicate the start and end of the regular expression to be read. Ostensibly, ^ reads what is in front of it and $ reads what is behind it.

### Quantifiers

This regular expression does not contain any quantifiers, however their purpose would be to read a certain minimum or maximum of a given character in a string. It can be written with only a minimum, only a maximum, or both.

### OR Operator

Ordinarily an or operator would contain a | but there is none in this particular regex. They are used for the same purpose as | for javascript, indicating something can be looked for in place of something else. Its an or statement.

### Character Classes

Examples of character classes are A-Z0-9 there which indicate that everything in between those two values should be read. in this case all capitol letters and integers 0-9. 

### Flags

This regex does not contain any flags.

### Grouping and Capturing

While there is no grouping on this regex, grouping is when using parentheses to indicate that combinations of characters need to be considered.

### Bracket Expressions

The bracket expressions here work in tandem with the character classes to provide the ranges that can be made. Everything in a bracket is a bracket expression.

### Greedy and Lazy Match

This is a fairly lazy regex. There are not many specific requirements and it is very open to a large amount of possible searches.

### Boundaries

Boundaries are used to separate specific things that would want to be searched using expressions like /b. They would allow separation of entire words to search from the other expressions in a regular expression.

### Back-references

Back references are parts of a regular expressions that uses prior data captured by earlier parts of the regular expression. This partiulcar regex contains none.

### Look-ahead and Look-behind

Makes sure that only certain combinations of things are read. Like a crossword puzzle, it looks for specific first characters and then either looks ahead or behind to read characters surrounding and ensure those are expected as well.

## Author

My name is Nicholas Oettinger and I am an amateur developer just coming out of a bootcamp. I hope that my essay was informative and accurate!

https://github.com/Galdronis