# Regex Tutorial

Regular expressions, often abbreviated as regex or regexp, are powerful tools for pattern matching and text manipulation. They provide a concise and flexible syntax for describing search patterns within strings of text. Regular expressions are widely used in various programming languages, text editors, and command-line tools for tasks such as data validation, text parsing, and string manipulation.

At their core, regular expressions consist of a sequence of characters and metacharacters that define a search pattern. These patterns can match specific sequences of characters, such as digits, letters, or symbols, as well as more complex patterns involving repetition, alternation, and grouping.

## Summary


In this regex tutorial, we will explore a specific regex pattern used in JavaScript for matching character escapes. The regex pattern allows for identifying and matching special characters within a string, enabling precise text manipulation and validation in full stack application development. By delving into the components of this regex pattern, you will gain a deeper understanding of how character escapes can be effectively utilized in your coding projects. Let's unravel the power of character escapes in regex!

## Table of Contents

- [Anchors](#Anchor)
- [Quantifiers](#Quantifiers)
- [OR Operator](#OR-Operator)
- [Character Classes](#Character-Classes)
- [Flags](#Flags)
- [Grouping and Capturing](#Grouping-and-Capturing)
- [Bracket Expression](#Bracket-Expression)
- [Greedy and Lazy Match](#Greedy-and-Lazy-Match)
- [Boundaries](#Boundaries)
- [Back-references](#Back-references)
- [Look-ahead and Look-behind](#Look-aheadandLook-behind)
- [Author](#Author)
##  Anchor (^)

Anchors in regular expressions are used to specify the position of a match within the text. The two most common anchors are:

^ (caret): Matches the start of a line.

$ (dollar sign): Matches the end of a line.


#### Example:
```md
const regex = /^Hello/;
```

## Quantifiers:

Quantifiers specify how many instances of a character or group should be matched. Some common quantifiers include:



- *: Matches zero or more occurrences.

- +: Matches one or more occurrences.

- ?: Matches zero or one occurrence.

- {n}: Matches exactly n occurrences.

- {n,}: Matches n or more occurrences.

- {n,m}: Matches between n and m occurrences.


#### Example:

```md
const regex = /a+/;

This regex will match one or more occurrences of the character 'a'.
```

## OR Operator:

The OR operator in regular expressions is denoted by | (pipe) and is used to match either of two patterns.

#### Example:

```md
const regex = /apple|orange/;

This regex will match either "apple" or "orange".
```

## Character Classes:

Character classes allow you to match a set of characters. They are enclosed in square brackets [].

#### Example:

```md
const regex = /[aeiou]/;

This regex will match any vowel character.
```

## Flags:

Flags in regular expressions are optional parameters that control how the pattern matching is performed. Some common flags include:



- i: Case-insensitive matching.

- g: Global matching (matches all occurrences).

- m: Multi-line matching.


#### Example:

```md
const regex = /hello/gi;

This regex will match "hello" in a case-insensitive manner and globally.
```

## Grouping and Capturing:

Grouping in regex is done using parentheses (). It allows you to group parts of a pattern together.

#### Example:

```md
const regex = /(apple|orange) juice/;
```

## Bracket Expressions:

Bracket expressions are used to specify a set of characters to match within square brackets [].

#### Example:

```md
const regex = /[0-9]/;
```
This regex will match any digit from 0 to 9.

## Greedy and Lazy Match:

Greedy matching tries to match as much as possible, while lazy matching matches as little as possible. Greedy quantifiers are denoted by *, +, ?, and {}, while lazy quantifiers are denoted by *?, +?, ??, and {n,m}?.


## Boundaries:

Boundaries in regex help to match patterns at specific positions in the text, such as word boundaries \b or non-word boundaries \B.

- \b (Word Boundary): Matches a word boundary, such as the start or end of a word.

- \B (Non-Word Boundary): Matches a position that is not a word boundary.


## Back-references:

Back-references allow you to refer back to captured groups in the regex pattern. They are denoted by \1, \2, etc.


## Look-ahead and Look-behind:

Look-ahead and look-behind assertions are used to check if a pattern is followed or preceded by another pattern without including it in the match. Look-ahead is denoted by (?=...), while look-behind is denoted by (?<=...).

- Positive Look-ahead ((?=...)): Matches a pattern only if it is followed by another pattern.

- Negative Look-ahead ((?!...)): Matches a pattern only if it is not followed by another pattern.

- Positive Look-behind ((?<=...)): Matches a pattern only if it is preceded by another pattern.

- Negative Look-behind ((?<!...)): Matches a pattern only if it is not preceded by another pattern.


## Author

This tutorial was written by Nimo Shirille. I am passionate about programming and enjoys sharing knowledge with others. If you have any questions or feedback about this tutorial, feel free to reach out to me via github.

Github link: [Nimo20](https://github.com/Nimo20)