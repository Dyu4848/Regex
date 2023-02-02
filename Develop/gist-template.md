# Regex Tutorial

Regex, or regular expression are patterns that are used to match character combinations in strings. It takes a combination of characters that creates a search pattern.

## Summary

/^#?([a-f0-9]{6}|[a-f0-9]{3})$/

This is the regex code that I will choose to be evaluating. It is used for matching a hex value and contains all of the different elements that I will be analyzing.

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

/`^`#?([a-f0-9]{6}|[a-f0-9]{3})`$`/

As inidicated in the expression above, the anchors in this code expression are `^` and `$`. Anchors are the part of regex that does not match any characters, but instead matches position. `^` is used to anchor the beginning of the string, while `$` is used to close it.

### Quantifiers

/^#`?`([a-f0-9]`{6}`|[a-f0-9]`{3}`)$/

As indicated in the expression above, the quantifiers in this expression are `?`, `{6}`, `{3}`. Quantifiers are used to specify how many times a character, must be included, in order for a match to be found. The `?` matches the previous token between zero and one times. The `{6}` indicates that the length of the characters or expressions matches exactly six times, while `{3}` indicates that the length of the character or expressions matches exactly three times.

### OR Operator

/^#?([a-f0-9]{6}`|`[a-f0-9]{3})$/

As indicated in the expression above, the OR operators in this expressions are `|`. The `|` is used to seperate the two sections in the expression, indicating that everything before or after it can be used. This means that the regex can either be six characters [a-f0-9]`{6}`, or three characters [a-f0-9]`{3}`.

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
