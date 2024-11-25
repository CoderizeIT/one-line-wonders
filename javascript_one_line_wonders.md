
# JavaScript One-Line Wonders

A collection of 50 JavaScript one-liners to solve common problems and for fun!

```javascript
// 1. Reverse a string
str.split('').reverse().join('');

// 2. Generate a random number between 1 and 100
Math.floor(Math.random() * 100) + 1;

// 3. Capitalize the first letter of a string
str.charAt(0).toUpperCase() + str.slice(1);

// 4. Check if an array contains a value
arr.includes(value);

// 5. Get the current timestamp
Date.now();

// 6. Filter out falsy values from an array
arr.filter(Boolean);

// 7. Remove duplicates from an array
[...new Set(arr)];

// 8. Find the maximum value in an array
Math.max(...arr);

// 9. Sort an array numerically
arr.sort((a, b) => a - b);

// 10. Get a random element from an array
arr[Math.floor(Math.random() * arr.length)];

// 11. Convert a string to uppercase
str.toUpperCase();

// 12. Convert a string to lowercase
str.toLowerCase();

// 13. Find the length of a string
str.length;

// 14. Check if a number is even
num % 2 === 0;

// 15. Merge two arrays
[...arr1, ...arr2];

// 16. Get unique values from an array of objects
arr.map(item => item.key).filter((v, i, a) => a.indexOf(v) === i);

// 17. Flatten a nested array
arr.flat(Infinity);

// 18. Sum of an array of numbers
arr.reduce((sum, num) => sum + num, 0);

// 19. Check if a string is a palindrome
str === str.split('').reverse().join('');

// 20. Create an array of numbers from 1 to 100
Array.from({ length: 100 }, (_, i) => i + 1);

// 21. Get the last element of an array
arr[arr.length - 1];

// 22. Clone an array
[...arr];

// 23. Find the first truthy value in an array
arr.find(Boolean);

// 24. Replace all occurrences of a string
str.split('old').join('new');

// 25. Get the keys of an object
Object.keys(obj);

// 26. Get the values of an object
Object.values(obj);

// 27. Get the entries of an object
Object.entries(obj);

// 28. Check if an object is empty
Object.keys(obj).length === 0;

// 29. Convert a string to an array of characters
[...str];

// 30. Generate a random hex color
`#${Math.floor(Math.random() * 16777215).toString(16).padStart(6, '0')}`;

// 31. Shuffle an array
arr.sort(() => Math.random() - 0.5);

// 32. Repeat a string n times
str.repeat(n);

// 33. Count the occurrences of a value in an array
arr.reduce((acc, val) => (val === target ? acc + 1 : acc), 0);

// 34. Check if all elements in an array are equal
arr.every(val => val === arr[0]);

// 35. Get the intersection of two arrays
arr1.filter(val => arr2.includes(val));

// 36. Check if a year is a leap year
year % 4 === 0 && (year % 100 !== 0 || year % 400 === 0);

// 37. Delay execution by a certain number of milliseconds
await new Promise(resolve => setTimeout(resolve, ms));

// 38. Find the index of the maximum value in an array
arr.indexOf(Math.max(...arr));

// 39. Convert an object to a query string
new URLSearchParams(obj).toString();

// 40. Parse a query string into an object
Object.fromEntries(new URLSearchParams(queryString));

// 41. Generate a UUID (v4)
([1e7]+-1e3+-4e3+-8e3+-1e11).replace(/[018]/g, c =>
  (c ^ (crypto.getRandomValues(new Uint8Array(1))[0] & (15 >> (c / 4)))).toString(16)
);

// 42. Capitalize every word in a string
str.replace(/\w/g, char => char.toUpperCase());

// 43. Get the current date in YYYY-MM-DD format
new Date().toISOString().split('T')[0];

// 44. Convert a JSON string to an object
JSON.parse(jsonString);

// 45. Convert an object to a JSON string
JSON.stringify(obj);

// 46. Generate a random boolean
Math.random() < 0.5;

// 47. Get the difference of two arrays
arr1.filter(val => !arr2.includes(val));

// 48. Count the words in a string
str.split(/\s+/).filter(Boolean).length;

// 49. Truncate a string to n characters
str.length > n ? `${str.slice(0, n)}...` : str;

// 50. Check if a number is prime
num > 1 && Array.from({ length: Math.sqrt(num) }, (_, i) => i + 2).every(i => num % i !== 0);
```
