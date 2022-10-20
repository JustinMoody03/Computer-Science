# Regex Tutorial

What is a regex?  A regex is short for regular expression, a combination of charecters that specify a search pattern in text.  

## Summary

I will be explaing what the regex /(?/d{3}[-.)](/d{3})[-.]/d{4} is and how it works.  This regex is used to find a phone number.

## Table of Contents

- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)


## Regex Components

### Quantifiers 
Quantifiers used in our phone number regex are the question mark? and curly braces{}.  The question mark? quantifier means 0 or 1, meaning charecters. This is because sometimes a phone number will have a 1 at the start, while other times it does not.  The curly braces{} are used to set a max and minimum.  If you have a 3 inside curly braces{}, then in order for the regex to be true there has to be three charecters in whatever it's searching for, in this case a phone number.

### Character Classes
Charecter classes are charecters between   square braces[] that appear on the screen the same way they do ebtween the brackets.  There can be multiple things between the brackets, like so: 
[-.)]
This makes it so all, or just one of the charecters within the brackets has to be there in order for the regex to be true.

Another class used in our regex is /d.  /d is a metacharecter that means any number 0-9.  Thats why when followed the curly brace{} quantifier with a three between the braces, it finds a 3 digit long number for us. 

## Author

Turotial created by Justin Moody, a full stack web development student and the Michigan State Coding Bootcamp.
Student Github: https://github.com/JustinMoody03
