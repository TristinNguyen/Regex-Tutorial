## Hexcode Regex Tutorial

The purpose of this tutorial is to walk you through an example of a regex or regular expression and how it works to match your searches or queries. In this case we will be looking at a hex code example. 

## Summary
The regex that we will be looking at is "/^#?([a-f0-9]{6}|[a-f0-9]{3})$/"
This allows users to search up color hexcodes with some kind of robustness. The gist will go through each part of the regex and its function to the matching the user to the string they are looking for. It does a good job. 
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
Matching a Hex Value - "/^#?([a-f0-9]{6}|[a-f0-9]{3})$/"
### Anchors
"`^`"

This will highlight/match any string that starts with the pound symbol (#). Which in this case of Hex values will be most if not all hex values.

"`$`"

This will match any string that ends with ")"
**When "^ and $" are combined, which they are in this case it will match an exact string that starts with "#" and end with ")"
### Quantifiers
"`?`"

This will match a string that has "#" followed by either a 0 or "("

"`{6}`", "`{3}`"

This will match any strings that has # followed by any hex code that has [a-f0-9] up to 6 times or alternatively up to 3 times.
### OR Operator
In this regex there are no operators 
### Character Classes

In this rgex there are no character classes. But in other regex they show up as "\d, \w, and \s" in which they each have their own function.
Which are the following: "matches a single character that is a digit, matches a character that is a digit 0-9, and matches a character is a space or white space". In that order. 
### Flags
"`/all/`"

In this regex the entirety is encapsalated by the slashes, sometimes there are other characters to denote other functions such as "/i" for the whole expression to be case-insensitive but in this case there are none.
### Grouping and Capturing
"`([a-f0-9]{6}|[a-f0-9]{3})`"

This is grouping and capturing two sets of groups. The first being       "[a-f0-9]{6}" and the second being "[a-f0-9]{3}"
### Bracket Expressions
"`[a-f0-9]`"

This captures any string that has a value of a-f and a value of 0-9
### Greedy and Lazy Match
In this regex there are no greedy or lazy matches.
### Boundaries
In this regex there are no boundaries.
### Back-references
In this regex there are no back-references.
### Look-ahead and Look-behind
In this regex there are no look-aheads or look-behinds
## Author

Tristin is a beginner coder that has learned a lot from his current bootcamp and aspires to learn more. He wants to work in the tech industry in the near future. 
[Github Profile](https://github.com/TristinNguyen)

