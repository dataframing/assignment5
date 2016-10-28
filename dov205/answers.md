
## Questions

**Describe the changes you made to make the game work with Python 3.**

The following change was made:

```
File: adventure.py
Line: 37
From:
	line = raw_input('> ')
To:
	line = input('> ')
Reason:
	The raw_input() builtin function from Python 2 was deprecated 
	in favor of input() in Python 3.
```

**Describe three main techniques that the author used to structure the program.**



**Has the author used meaningful names? Give some examples of meaningful names used and what you think they mean. Give some examples of where the author has not used meaningful names.**

**Do the functions used in the code do one thing? Give some examples of functions that only do one thing. Give some examples of functions that do more than one thing.**

**Do any of the functions cause side effects? If so, which ones?**

**Can you find any repeated code that could be made into a function?**

**Does the program use exception handling? Can you find any input that causes the program to terminate abnormally? Hint: run the program from the terminal prompt. The invalid input may not be normal text.**

**Do any of the classes have responsibility over more than one piece of functionality. If so, which ones?**

**Are all the classes cohesive? List any that aren’t.**

**Describe the author’s approach to commenting the code. Provide examples of good and bad comments that have been used in the code.**

**Provide an example of where vertical formatting has been used to make the code clearer.**

**Run the tests provided with the program. Do they pass or fail? Do you consider the tests meet the F.I.R.S.T. criteria? Provide details of why they do or do not meet the criteria.**