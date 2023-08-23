# Title (Matching an Email Address-Regex Tutorial)

In this tutorial, I will explain how to match an email address using regex using the expression /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/. This can be helpful for validating email addresses in a form or for searching for email addresses in a document or with apps/programs like Node or MongoDB.

## Summary

A regular expression (regex) is a sequence of characters that define a search pattern. It is commonly used for "find" or "find and replace" operations on strings, or for input validation. It is a technique developed in theoretical computer science and formal language theory.

I will be walking through the following regex, explaining what each component does.

/^([a-z0-9_.-]+)@([\da-z.-]+).([a-z.]{2,6})$/

This regex makes sure that the given string matches the template for an email address.

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

Regex uses the two anchors ^ and $.

^ denotes that the string's opening character must be the next line of code.

$ indicates that the previous line of code must come after the string.

A given string must precisely fulfill every one of the stated requirements in order to fit our regular expression because it contains both.

Despite how constricting this may sound, you will see how quantifiers, grouping, and bracket expressions allow for a wide variety of flexibility with the given string.

### Quantifiers

Quantifiers in this regex includes the + operator, which will connect the users email name + email service + .com. Another quantifier for this regex includes {2,6}, which will allow a match range of 2-6 characters for the character set of [a-z\.].

### OR Operator

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
