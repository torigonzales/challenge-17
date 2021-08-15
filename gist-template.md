# REGEX Tutorial 

REGEX- "Regular Expressions"- Regular expressions are patterns used to match character combinations in strings. In JavaScript, regular expressions are also objects. These patterns are used with the exec() and test() methods of RegExp, and with the match(), matchAll(), replace(), replaceAll(), search(), and split() methods of String. 

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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

- Matching fixed strings
- Matching Special Characters
- Macthing Character Sets 
- Specifying Groups and Fields
- Specifying Alternatives 
- Matching INformation from a Table
- Captuiring Multiple Lines 
- Managing the scope of Analysis 


### Anchors

- Anchors belong to the family of regex tokens that don't match any characters, but that assert something about the string or the matching process. Anchors assert that the engine's current position in the string matches a well-determined location: for instance, the beginning of the string, or the end of a line.

### Quantifiers

- Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found.


### OR Operator

- The regular expression operators are used for matching patterns in searches and for replacements in substitution operations. The m operator is used for matching patterns, and the s operator is used when substituting one pattern for another.

### Character Classes

- The character class is the most basic regex concept after a literal match. It makes one small sequence of characters match a larger set of characters. For example, [A-Z] could stand for any uppercase letter in the English alphabet, and \d could mean any digit. Character classes apply to both POSIX levels.


### Flags

- The flag s means dot all. ... By default, the dot character in a regular expression matches everything, but newline characters. To get it to match newline characters as well, we are given the s flag.

### Grouping and Capturing

- They capture the text matched by the regex inside them into a numbered group that can be reused with a numbered backreference. They allow you to apply regex operators to the entire grouped regex.

### Bracket Expressions

- A bracket expression (an expression enclosed in square brackets, "[]" ) is an RE that shall match a specific set of single characters, and may match a specific set of multi-character collating elements, based on the non-empty set of list expressions contained in the bracket expression.

### Greedy and Lazy Match

- 'Greedy' means match longest possible string. 'Lazy' means match shortest possible string. For example, the greedy h. +l matches 'hell' in 'hello' but the lazy h.

### Boundaries

- A word boundary, in most regex dialects, is a position between \w and \W (non-word char), or at the beginning or end of a string if it begins or ends (respectively) with a word character ( [0-9A-Za-z_] ).

### Back-references

- A backreference in a regular expression identifies a previously matched group and looks for exactly the same text again. A simple example of the use of backreferences is when you wish to look for adjacent, repeated words in some text. The first part of the match could use a pattern that extracts a single word.

### Look-ahead and Look-behind

- Positive Look-Ahead: In this type the regex engine searches for a particular element which may be a character or characters or a group after the item matched. If that particular element is present then the regex declares the match as a match otherwise it simply rejects that match. 

- Negative Look- Ahead: In this type of lookahead the regex engine searches for a particular element which may be a character or characters or a group after the item matched. If that particular element is not present then the regex declares the match as a match otherwise it simply rejects that match. 

- Positive Look- Behind: Lookbehind has the same effect, but works backwards. It tells the regex engine to temporarily step backwards in the string, to check if the text inside the lookbehind can be matched there.

- Negative Look- Behind: The negative lookahead construct is the pair of parentheses, with the opening parenthesis followed by a question mark and an exclamation point. Inside the lookahead, we have the trivial regex u. Positive lookahead works just the same.

## Author

<a href="https://github.com/torigonzales/challenge-17">GitHub Repo</a>

