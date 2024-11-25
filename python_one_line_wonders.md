
# Python One-Line Wonders

A collection of 50 Python one-liners to solve common problems and for fun!

```python
# 1. Reverse a string
s[::-1]

# 2. Check if a number is even
num % 2 == 0

# 3. Generate a random password
''.join(random.choices(string.ascii_letters + string.digits, k=12))

# 4. Swap two variables
a, b = b, a

# 5. List comprehension for squares of numbers
[x**2 for x in range(10)]

# 6. Read a file into a list
lines = open('file.txt').readlines()

# 7. Check for palindrome
s == s[::-1]

# 8. Count occurrences of a word in a string
s.lower().count('word')

# 9. Flatten a nested list
flat = [item for sublist in nested_list for item in sublist]

# 10. Create a dictionary from two lists
dict(zip(keys, values))

# 11. Find the maximum value in a list
max(lst)

# 12. Find the minimum value in a list
min(lst)

# 13. Calculate the sum of a list
sum(lst)

# 14. Check if a string contains only digits
s.isdigit()

# 15. Get the current date and time
datetime.now()

# 16. Generate a random integer between 1 and 100
random.randint(1, 100)

# 17. Find the length of a list or string
len(obj)

# 18. Check if an element exists in a list
element in lst

# 19. Create a list of even numbers
[x for x in range(10) if x % 2 == 0]

# 20. Remove duplicates from a list
list(set(lst))

# 21. Sort a list
sorted(lst)

# 22. Join a list of strings with commas
','.join(lst)

# 23. Get the unique characters in a string
set(s)

# 24. Create a list of tuples from two lists
list(zip(lst1, lst2))

# 25. Find the factorial of a number
math.factorial(n)

# 26. Calculate the square root of a number
math.sqrt(n)

# 27. Check if a number is a power of 2
n > 0 and (n & (n - 1)) == 0

# 28. Find the GCD of two numbers
math.gcd(a, b)

# 29. Convert a list of strings to uppercase
[s.upper() for s in lst]

# 30. Get the ASCII value of a character
ord(c)

# 31. Get the character from an ASCII value
chr(n)

# 32. Filter out None values from a list
[x for x in lst if x is not None]

# 33. Generate a list of random numbers
[random.randint(1, 100) for _ in range(10)]

# 34. Get the index of the maximum value in a list
lst.index(max(lst))

# 35. Convert a string to a list of characters
list(s)

# 36. Find the difference between two sets
set1 - set2

# 37. Find the intersection of two sets
set1 & set2

# 38. Find the union of two sets
set1 | set2

# 39. Capitalize the first letter of a string
s.capitalize()

# 40. Count the occurrences of a character in a string
s.count('char')

# 41. Check if a string starts with a prefix
s.startswith(prefix)

# 42. Check if a string ends with a suffix
s.endswith(suffix)

# 43. Repeat a string n times
s * n

# 44. Create a dictionary with default values
dict.fromkeys(keys, default_value)

# 45. Convert a list of tuples into a dictionary
dict(lst_of_tuples)

# 46. Filter even numbers from a list
list(filter(lambda x: x % 2 == 0, lst))

# 47. Check if a year is a leap year
year % 4 == 0 and (year % 100 != 0 or year % 400 == 0)

# 48. Reverse a list
lst[::-1]

# 49. Find the number of words in a string
len(s.split())

# 50. Get a random element from a list
random.choice(lst)
```
