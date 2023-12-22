# Regex Email Finder

Email Matching Regex 

## Summary

Here is my interpretation of a regex for finding or matching an email. If you want to find emails within a document or within code or a database this regex is a perfect tool to locate and make changes easily and quickly. 

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Regex Components

### Anchors

The ^ symbol is an anchor for the regex and it tells the user or machine that this is where the string starts. The $ symbol is an anchor and tells where the the string ends. 

### Quantifiers

The + symbol is an quantifier and it means that there can be a match of one or more of the preceding token (there are two instances of this quantifier). The other quantifier is the {2,6}, which means there needs to be a match between 2 and 6 for the preceding token.

### Character Classes

The \d is a character class and in our expression it needs to match any digit between 0-9. 

### Grouping and Capturing

The paranthensis () symbol help us group or capture the different aspects of this regex. There are 3 groupings: ([a-z0-9_\.-]+), ([\da-z\.-]+), and ([a-z\.]{2,6}). In our example the first grouping is the user's email/name. The second grouping is the email provider's info. The third grouping is the domain name. 

### Bracket Expressions

These symbols [] make up bracket expressions and it helps us represent the characters that we want to match. There are 3 bracket expressions in this regex: [a-z0-9_\.-], [\da-z\.-], and [a-z\.]. The first bracket expression requires that it can only have lowercase letters between a-z and any digit between 0-9 and it can contain a dash, underscore or a period. the second bracket expression requires that the it can only contain lowercase letters betwee a-z and it can contian a dash or a period. The last one requires that it can only contain lowercase letters between a-z and can contain a preiod. 

### Greedy and Lazy Match

This regex is greedy becaus it uses the + quantifier twice and the {} quantifier once. 

## Author

Thanks for this opportunity. 
Madison Reynolds

Here is a link to my GitHub account: https://github.com/mradison?tab=repositories

