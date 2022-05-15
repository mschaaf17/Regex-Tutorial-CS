# Regex Tutorial
 
This tutorial is a brief summary of regex components.
Matching an email
/^([a-z0-9_\.-]+)@([a-z0-9_\.-]+)\.([a-z\.]{2,6})$/

 
 
## Summary
 
A regex is a piece of code that looks for a specific outcome. This is to verify the users input is what is expected such as an email, or phone number. The regex I will review is Matching an email
/^([a-x0-9_\.-]+)([a-z0-9_\.-]+)\.([a-z\.]{2,6})$/ to match an email.
 
 
## Table of Contents
 
- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Author](#author)
 
## Regex Components
 
### Anchors
Anchors start and end the regex. The beginning of the regex will have a ^ and the end will have $. The example regex above displays each of these anchors at the beginning and end of the regex inside the //. The \ is used to escape a special character.
 
 
### Quantifiers
Defines the number of times a character, pattern, or group appears in a match. In the regex above, {2. 6} specifies that there needs to be between 2 and 6 characters in that position.
 
 
### Character Classes
Character sets are a way to match different characters in a single position. You must put what you want to match in square brackets.  Users can match any items in the brackets. In the regex above the user can match an email with any letter because a-z has a hyphen indicating any letter of the alphabet, same goes for numbers.
 
### Flags
Checks for matches. You can do a global flag that will search for all the matches in your text that matches the regex. Multiline ^ and $ match the start/end of the line. Insensitive where case insensitive match. Unicode to match with full unicode. Single line means dot matches new line.
 
### Grouping and Capturing
Can use parentheses to group what you are capturing. In the example above, each set of parentheses are for a different component in the email. Example: (maddy0317)@(gmail).(com)
 
### Bracket Expressions
Used for matching characters. Typically by using square brackets or parentheses. Any characters defined in square brackets allow the user to use the characters specified for that position. For this regex the user can type any lowercase letter, number, and specified special characters that are inside the square brackets.
 
 
### Greedy and Lazy Match
The + and {} are greedy operators so they can match more than one of what is specified. The + indicates there can be one or more of the characters in the [] used for the email.
 
 
 
## Author
 
My name is Madison Schaaf. I am working towards becoming a full stack developer. Check out my GitHub.
[mschaaf17](https://github.com/mschaaf17)