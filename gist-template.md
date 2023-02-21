# Regex Tutorial

Here's a tutorial to explain how to read REGEX expressions a little bit like: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

## Summary

In the simplest way to put it a regex is a almost a secret language that specifies patterns in text; regex is shorthand for Regular Expression.

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

### Anchors
An anchor more or less lets you know where you are in the string. Examples of an anchor would be `^` and `$`
### Quantifiers
Quantifiers are something that alters something in a regex string, for example it might specify how many times a character shows up or a grouping of characters. and example would be like * which is often called a wildcard, but can be read as "exist once or more times."
### Grouping Constructs
Grouping constructs are a group of character types, or a subgroup of characters. Like `([a-z0-9_\.-]+)` in the example string is a grouping construct.
### Bracket Expressions
Bracket expressions are always inclosed in square brackets([]'s) that specify a set of single or multi character elements.
### Character Classes
A character class is what it sounds like, it shows a type of characters, like `a-z` is any character from a-z, or `0-9` can be seen as any singular digit, or you can also show any digit by the character class of `/d`.
### The OR Operator
The or operatior is similar to javascript it that it's shown with a pipe `|`
### Flags
A flag is something added on that changes how the expressions is read, like a flag of `i` would mean the character is insensitive to case, or `m` would mean that it could stretch multiple lines.
### Character Escapes
Sometimes if you're looking for characters that regex uses to mean other things you have to escape that character.