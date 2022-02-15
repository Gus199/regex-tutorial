# Complex Password Strength Regex Tutorial

This tutorial will help explain how the Complex Password Strength regular expression functions by breaking down each part of the expression and describing what it does.

# Summary 
 
 A regex, which is short for regular expression, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input and each component of a regex has a unique responsibility to perform said validation.

  * In this walkthrough we'll be covering aspects of the Complex Password Strength regex which includes checking for: 1 lowercase letter, 1 uppercase letter, 1 number, 1 special character and be at least 8 characters long

The regex looks like this:

* ``` /(?=(.*[0-9]))(?=.*[\!@#$%^&*()\\[\]{}\-_+=~`|:;"'<>,./?])(?=.*[a-z])(?=(.*[A-Z]))(?=(.*)).{8,}/ ```

# Table of Contents 
 

