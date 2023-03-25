# Regex how to match and email tutorial



## Summary

What do you do if you need to make sure that users emails are active. You validate it with a regular expression? One way to validate them is by using regular expressions.



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
- [Cheat Sheet](#cheatsheet)

## Regex Components
^\S+@\S+$
### Anchors
They are used to match positions and not characters. ^ are used to match. 123 to find 1 it would look like this ^1.
### Quantifiers
This regular expression uses the quantifier "+", which matches one or more occurrences of the previous character or group of characters. In this case, it matches one or more times the user's email name, followed by the email service, and ending with ".com".

The quantifier "{2,6}", which matches a range of 2 to 6 characters from the character set of lowercase letters and the period symbol "[a-z.]". This means that the email name and email service must contain at least two characters and no more than six characters from the set of lowercase letters and periods.
### OR Operator

### Character Classes
The character class "\d", which matches a single digit from 0 to 9. This means that it will only match a single digit, such as "0", "1", "2", ..., "9", but not multiple digits such as "11" or "123".

To match multiple digits, you can use quantifiers such as "+", "*", or "{n,m}" after the "\d" character class to specify the minimum and maximum number of times it should match. For example, "\d+" would match one or more digits, such as "11" or "123", while "\d{2,4}" would match a sequence of 2 to 4 digits, such as "1234" or "567".
### Flags
Flags are used to change how regular expression are interpreted or executed. They are added to the end of a regex.
### Grouping and Capturing

### Bracket Expressions
Bracket Expressions uses character sets to define the allowed characters in an email address. The first character set, "[a-z0-9_.-]", matches any lowercase letter a-z, any digit 0-9, and the characters "_", "-", and ".". This character set is case sensitive. 

Another way to look at it is Bracket Expressions looking for email addresses that contain only lowercase letters, digits, and certain special characters such as "_", "-", and ".". It allows a mixture of letters and digits in the email address, but it does not allow uppercase letters.

### Greedy and Lazy Match
greedy matching attempts to match as much as possible, without preventing the overall match to be successful. Lazy matching attempts to match as little as possible, without preventing the overall match to be successful. In other words they do the opposite of each other.
### Boundaries
Boundaries are used to show the start or end of both words and lines. Using a boundary will give you the ability to match patterns found in the start or end of word and strings. A list of boundary symbols with be listed in the cheatsheet section at the bottom of the page.
### Back-references

### Look-ahead and Look-behind
Lookahead and lookbehind are special constructs in regex that lets some check if a pattern exists ahead or behind the current position, without actually including those characters in the match. They are called "lookaround" because they look ahead or behind to see if a match is possible, without actually consuming any characters in the string.
 A benefit of using lookaround is that it enables you to create more complex regular expressions that would otherwise be difficult or impossible to express. Without lookaround, you might need to write a longer and more complicated regular expression to achieve the same result.

## CheatSheet
^ Carat, matches a term if the term appears at the beginning of a paragraph or a line.

$ Dollar sign, matches a term if the term appears at the end of a paragraph or a line.

\b Word boundary, matches the boundary between a word character.
\n Backslash and n, represents a line break.
\t Backslash and t, represents a tab.
* Asterisk, matches 0 or more characters in front of the asterisk.

source https://www.regular-expressions.info

### Author

Marvin is a game designer from the great state of Maryland. In his free time he enjoys playing sports and designing AI systems.Feel free to connect with him https://www.linkedin.com/in/marvinmaynard http://marvinmaynard.com/ https://github.com/lmmay0. 
