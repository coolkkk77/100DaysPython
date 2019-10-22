# Day 1: Installing Python
**Completion Date:**
10/04/2019
**Learned:** 
How to install Python and clone a project from GitHub to Pycharm
# Day 2: Printing in Python
**Completion Date:** 
10/08/2019
**Learned:** 
How to use print function. How to position text and integers and set specific length.
https://pyformat.info/
# Day 3: Operators
**Completion Date:** 
10/08/2019
**Learned:** 
How to do numeric calculation. How to use quotes to quote a string, how to make string start a newine with `\n`, how to tab in a string with `\t`. And also how to use true and false operators.
# Day 4: Variables & Variable Types
**Completion Date:** 
10/10/2019
**Learned:** 
Python is case sensitive. Numbers cannot be the first character to name as a variable. Learned how to create a variable. Variables can be used to do calculation i.e. 1+1 = 2. No need to declare type of variables because Python knows. And same variable can be overwritten so the type will change.
For example:
var = 3
var = str(var) - This turns var to a string.
type(var)

# Day 5: String Formatting
**Completion Date:** 
10/13/2019
**Learned:** 
Formating characters to upper, lower cases. Use {} as a string replacement and formatting the position and width. {Position:Width}
Tryncating a long string by using a number after a period. print("{:.5}".format(cheers.capitalize()))

# Day 6: Lists
**Completion Date:** 
10/15/2019
**Learned:** 
1. There are two ways to creat a list. Using text =[], by using square bracket or text=list(), by placing characters in the bracket.
For example, text = 'Hello' will be list(text) and the output is ['h', 'e', 'l', 'l', 'o']
Use .sort() to sort the list.
luggage = [1, 3, 5, 2, 4]
luggage.sort()
2. If we want to reverse the list, just use .sort(reverse=True)
3. Variables build from a list are the same object as original list, so if original list changes, the new variables will change too.
In order to create a new version, a function need to be used. For example, luggage = [1, 3, 5, 2, 4], then we need to create a new version by using luggage_sorted = list(luggage)
4. Simply use + to combine two lists. Or use .extend() to combine.
5. Sorted() gives a new list of sorted character while list.sort() will change the entire original list.
6. Using .append() to add additional items to a list.
7. Using .count() to count the frequency of an item in a list. 
quote = list("YOGURT! I hate Yogurt! Even with strawberries!")
print(quote.count("r"))
8. Using .insert(index, item) to add a new item to the list at a specific position.
9. Using .pop(i) to remove and return the final element, or from a specific index i.
10. .remove(i) method eliminates a specific item (i) from the list.
11. .reverse() method reverses the order of the items in the list.
12. A list can be cleared by using the .clear() method.
13. Items in a list can be changed. 
luggage = [2, 2, 3, 4, 5]
luggage[0] = 1
print(luggage)
14. Python can conduct transformations to a list while declaring a new list.
sample = list(range(1,13))
times_12 = [i * 12 for i in sample]
print(times_12)

# Day 7: Ranges
**Completion Date:** 
10/18/2019
**Learned:** 
Range starts with index 0 and ends with declare value, so if a range of 10, it will be 0-9. You don't have to start with index 0 as well.
Range function is range(start, stop, step). Step is the interval between start and stop.
If the step is negative, then the range values are produced in reverse, which higher number will start first.

# Day 8: Tuples
**Completion Date:** 
10/18/2019
**Learned:** 
A.Tuples are immutable. Need to create a new tuble in order to change an item in tuple. Items in tuple cannot be deleted but can delte the whold tuple by using 'del'.
B. Two ways to create a tuple:
1. Use comma sepratated list: theme = "East", "Bound", "Down"
2. Use a list of comma separated list of items in parentheses: good = ("Bandit", "Frog", "Snowman")

C. List in a tuple can be modified.
movie_list = ("Smokey and the Bandit", 1977, "Hal Needham", ["Burt Reynolds", "Sally Field", "Jerry Reed"])
title, year, director, cast = movie_list
cast.append("Jackie Gleason")---- Add Jackie Gleason to the movie_list

D. Tuple can be used to assign multiple variables at the same time.
movie = ("Smokey and the Bandit", 1977, "Hal Needham", ("Burt Reynolds", "Sally Field", "Jerry Reed"))
title, year, director, stars = movie
bandit, frog, snowman = stars
print("Title: {}\nYear: {}\nDirector: {}".format(title, year, director))
type(stars)
print("Stars: {}\nBandit: {}\nFrog: {}\nSnowman: {}".format(stars, bandit, frog, snowman))

# Day 9: Index and Slicing
**Completion Date:** 
10/22/2019
**Learned:** 
1. Specific items can be retrieved from a list by using slicing format [start:stop:step]. Start is inclusive but stop is exclusive.
2. Slicing can return items in sequence rather than just a single item.
quotes[2:5]
3. The step can be used to identify how many items to skip between returned values.
quotes[::2]
4. The step can also be used to reverse the order of the returned items.
quotes[::-1]
5. Slicing can be combined with indices to return a sequence from a specific item.
quotes[0][::2]- This will return the first index and by counting a step of 2.
6. Slicing doesn't only need to be applied to lists. It can also be used on variables..
wayne = "Toughest Guy in Letterkenny"
wayne[::-1]
7. New list can be created based on the slicing output.
exchange = quotes[2:5]
print(exchange)

# Day 10: If/Else
**Completion Date:** 

**Learned:** 

# Day 11: Augmented Assignments
**Completion Date:** 

**Learned:** 

# Day 12: For/While Loops
**Completion Date:** 

**Learned:** 

# Day 13: Continue/Break
**Completion Date:** 

**Learned:** 

# Day 14: Module 1 Challenge
**Completion Date:** 

**Learned:** 

# Day 15: Dictionaries
**Completion Date:** 

**Learned:** 

# Day 16: Sets
**Completion Date:** 

**Learned:** 

# Day 17: User Input
**Completion Date:** 

**Learned:** 

# Day 18: Packages
**Completion Date:** 

**Learned:** 

# Day 19: File Input/Output
**Completion Date:** 

**Learned:** 

# Day 20: Functions
**Completion Date:** 

**Learned:** 

# Day 21: Pytest
**Completion Date:** 

**Learned:** 

# Day 22: Recursive Functions
**Completion Date:** 

**Learned:** 

# Day 23: Lambdas
**Completion Date:** 

**Learned:** 

# Day 24: Object-Oriented Programming
**Completion Date:** 

**Learned:** 

# Day 25: List Comprehensions
**Completion Date:** 

**Learned:** 

# Day 26: Map, Filter, and Zip
**Completion Date:** 

**Learned:** 

# Day 27: Logging
**Completion Date:** 

**Learned:** 

# Day 28: Module 2 Challenge
**Completion Date:** 

**Learned:** 

# Day 29: File Manipulations
**Completion Date:** 

**Learned:** 

# Day 30: File Search
**Completion Date:** 

**Learned:** 

# Day 31: CSV Manipulations
**Completion Date:** 

**Learned:** 

# Day 32: Excel Manipulations
**Completion Date:** 

**Learned:** 

# Day 33: PDF Manipulations
**Completion Date:** 

**Learned:** 

# Day 34: PowerPoint Manipulations
**Completion Date:** 

**Learned:** 

# Day 35: Task Scheduler
**Completion Date:** 

**Learned:** 

# Day 36: Email/SMS Notifications
**Completion Date:** 

**Learned:** 

# Day 37: Mouse/Keyboard Manipulations
**Completion Date:** 

**Learned:** 

# Day 38: API Integration
**Completion Date:** 

**Learned:** 

# Day 39: Web Scraping
**Completion Date:** 

**Learned:** 

# Day 40: Image Manipulations
**Completion Date:** 

**Learned:** 

# Day 41: Creating a Chatbot
**Completion Date:** 

**Learned:** 

# Day 42: Module 3 Challenge
**Completion Date:** 

**Learned:** 

# Day 43: _Topic_
**Completion Date:** 

**Learned:** 

# Day 44: _Topic_
**Completion Date:** 

**Learned:** 

# Day 45: _Topic_
**Completion Date:** 

**Learned:** 

# Day 46: _Topic_
**Completion Date:** 

**Learned:** 

# Day 47: _Topic_
**Completion Date:** 

**Learned:** 

# Day 48: _Topic_
**Completion Date:** 

**Learned:** 

# Day 49: _Topic_
**Completion Date:** 

**Learned:** 

# Day 50: _Topic_
**Completion Date:** 

**Learned:** 

# Day 51: _Topic_
**Completion Date:** 

**Learned:** 

# Day 52: _Topic_
**Completion Date:** 

**Learned:** 

# Day 53: _Topic_
**Completion Date:** 

**Learned:** 

# Day 54: _Topic_
**Completion Date:** 

**Learned:** 

# Day 55: _Topic_
**Completion Date:** 

**Learned:** 

# Day 56: Module 4 Challenge
**Completion Date:** 

**Learned:** 

# Day 57: _Topic_
**Completion Date:** 

**Learned:** 

# Day 58: _Topic_
**Completion Date:** 

**Learned:** 

# Day 59: _Topic_
**Completion Date:** 

**Learned:** 

# Day 60: _Topic_
**Completion Date:** 

**Learned:** 

# Day 61: _Topic_
**Completion Date:** 

**Learned:** 

# Day 62: _Topic_
**Completion Date:** 

**Learned:** 

# Day 63: _Topic_
**Completion Date:** 

**Learned:** 

# Day 64: _Topic_
**Completion Date:** 

**Learned:** 

# Day 65: _Topic_
**Completion Date:** 

**Learned:** 

# Day 66: _Topic_
**Completion Date:** 

**Learned:** 

# Day 67: _Topic_
**Completion Date:** 

**Learned:** 

# Day 68: _Topic_
**Completion Date:** 

**Learned:** 

# Day 69: _Topic_
**Completion Date:** 

**Learned:** 

# Day 70: Module 5 Challenge
**Completion Date:** 

**Learned:** 

# Day 71: _Topic_
**Completion Date:** 

**Learned:** 

# Day 72: _Topic_
**Completion Date:** 

**Learned:** 

# Day 73: _Topic_
**Completion Date:** 

**Learned:** 

# Day 74: _Topic_
**Completion Date:** 

**Learned:** 

# Day 75: _Topic_
**Completion Date:** 

**Learned:** 

# Day 76: _Topic_
**Completion Date:** 

**Learned:** 

# Day 77: _Topic_
**Completion Date:** 

**Learned:** 

# Day 78: _Topic_
**Completion Date:** 

**Learned:** 

# Day 79: _Topic_
**Completion Date:** 

**Learned:** 

# Day 80: _Topic_
**Completion Date:** 

**Learned:** 

# Day 81: _Topic_
**Completion Date:** 

**Learned:** 

# Day 82: _Topic_
**Completion Date:** 

**Learned:** 

# Day 83: _Topic_
**Completion Date:** 

**Learned:** 

# Day 84: Module 6 Challenge
**Completion Date:** 

**Learned:** 

# Day 85: _Topic_
**Completion Date:** 

**Learned:** 

# Day 86: _Topic_
**Completion Date:** 

**Learned:** 

# Day 87: _Topic_
**Completion Date:** 

**Learned:** 

# Day 88: _Topic_
**Completion Date:** 

**Learned:** 

# Day 89: _Topic_
**Completion Date:** 

**Learned:** 

# Day 90: _Topic_
**Completion Date:** 

**Learned:** 

# Day 91: _Topic_
**Completion Date:** 

**Learned:** 

# Day 92: _Topic_
**Completion Date:** 

**Learned:** 

# Day 93: _Topic_
**Completion Date:** 

**Learned:** 

# Day 94: _Topic_
**Completion Date:** 

**Learned:** 

# Day 95: _Topic_
**Completion Date:** 

**Learned:** 

# Day 96: _Topic_
**Completion Date:** 

**Learned:** 

# Day 97: _Topic_
**Completion Date:** 

**Learned:** 

# Day 98: Module 7 Challenge
**Completion Date:** 

**Learned:** 

# Day 99: Capstone
**Completion Date:** 

**Learned:** 

# Day 100: Capstone
**Completion Date:** 

**Learned:** 
