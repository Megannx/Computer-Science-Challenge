# Computer Science Debrief

In this Debrief, I will be explaining the key components of what Computer Science is, what it does, and how it is beneficial to the programming community. We will be discussing how it's beneficial whether that's through a career, schooling, or self-improvements. 

## Summary

This tutorial will describe the fundamental components of regex, including how they can be used to match specific patterns in strings. The prime example of a regex pattern we will discuss is for validating a date in the format MM/DD/YYYY:

/^(0[1-9]|1[0-2])\/(0[1-9]|[12][0-9]|3[01])\/(19|20)\d{2}$/

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

Anchors are used to match positions within a string rather than actual characters. There are two main anchors:

    ^ - Matches the start of a string.
    $ - Matches the end of a string.

### Quantifiers
Quantifiers define how many instances of a character, group, or character class must be present in the input for a match. Common quantifiers include:

    * - Matches 0 or more occurrences.
    + - Matches 1 or more occurrences.
    ? - Matches 0 or 1 occurrence.
    {n} - Matches exactly n occurrences.
    {n,} - Matches n or more occurrences.
    {n,m} - Matches between n and m occurrence
### Grouping Constructs
Grouping allows for parts of a regex to be treated as a single unit. This can be useful for applying quantifiers to part of a pattern or for capturing parts of the match.

    () - Captures the group, enabling backreferences and extracting sub-matches.
    (?:) - Non-capturing group, which does not create backreferences.
### Bracket Expressions
Bracket expressions, also known as character sets, allow you to match one character from a defined set of characters.

    [abc] - Matches either "a", "b", or "c".
    [a-z] - Matches any lowercase letter from "a" to "z".

### Character Classes
Character classes are predefined sets of characters that represent commonly used groups.

    \d - Matches any digit.
    \w - Matches any word character.
    \s - Matches any whitespace character (spaces, tabs, etc.).
### The OR Operator
The OR operator (|) is used to match either the pattern on the left or the pattern on the right.

    pattern1|pattern2 - Matches either "pattern1" or "pattern2."
### Flags
Flags modify the behavior of the entire regex. They are usually added after the closing delimiter of the pattern.

    i - Case-insensitive matching.
    g - Global search (finds all matches instead than stopping after the first match).
    m - Multiline mode.

### Character Escapes
Character escapes allow special characters to be treated as literal characters or to represent non-printable characters.

    \. - Matches a literal dot.
    \\ - Matches a literal backslash.
    \n - Matches a newline character.
## Author

I, Megan White, am a Full-Stack Coding Bootcamp student, with a passion for programming. I enjoy solving new and challenging problems everyday. You can view my projects/work on Github via https://github.com/Megannx
