1. How do you create an array in JavaScript?
let arr = [1, 2, 3];
2. How do you access the first element of an array?
arr[0];
3. How do you access the last element of an array?
arr[arr.length - 1];
4. How do you add an element to the end of an array?
arr.push(element);
5. How do you remove the last element from an array?
arr.pop();
6. How do you add an element to the beginning of an array?
arr.unshift(element);
7. How do you remove the first element from an array?
arr.shift();
8. How do you find the length of an array?
arr.length;
9. How do you check if a value exists in an array?
arr.includes(value);
10. How do you find the index of an element in an array?
arr.indexOf(element);
11. How do you find the last index of an element in an array?
arr.lastIndexOf(element);
12. How do you convert an array to a string?
arr.join(', ');
13. How do you merge two arrays?
arr1.concat(arr2);
14. How do you create a copy of an array?
arr.slice(); or [...arr];
15. How do you sort an array?
arr.sort();
16. How do you reverse the order of elements in an array?
arr.reverse();
17. How do you remove elements from an array?
arr.splice(start, deleteCount);
18. How do you add elements to an array at a specific index?
arr.splice(index, 0, element1, element2);
19. How do you find the sum of all elements in an array?
arr.reduce((sum, current) => sum + current, 0);
20. How do you create a new array with the results of calling a function on every element?
arr.map(element => element * 2);
21. How do you filter elements from an array based on a condition?
arr.filter(element => element > 5);
22. How do you check if all elements in an array satisfy a condition?
arr.every(element => element > 5);
23. How do you check if at least one element in an array satisfies a condition?
arr.some(element => element > 5);
24. How do you loop through an array?
arr.forEach(element => { /* code */ });
25. How do you find the maximum value in an array?
Math.max(...arr);
26. How do you find the minimum value in an array?
Math.min(...arr);
27. How do you flatten a nested array?
arr.flat();
28. How do you remove duplicate elements from an array?
[...new Set(arr)];
29. How do you find the intersection of two arrays?
arr1.filter(value => arr2.includes(value));
30. How do you find the difference between two arrays?
arr1.filter(value => !arr2.includes(value));
31. How do you remove falsy values from an array?
arr.filter(Boolean);
32. How do you create an array of a specific length and fill it with a specific value?
Array(length).fill(value);
33. How do you generate an array of numbers from 1 to n?
[...Array(n).keys()].map(i => i + 1);
34. How do you find the average of all elements in an array?
arr.reduce((sum, current) => sum + current, 0) / arr.length;
35. How do you find the unique values in an array?
[...new Set(arr)];
36. How do you merge and remove duplicates from two arrays?
[...new Set([...arr1, ...arr2])];
37. How do you check if two arrays are equal?
JSON.stringify(arr1) === JSON.stringify(arr2);
38. How do you get a random element from an array?
arr[Math.floor(Math.random() * arr.length)];
39. How do you shuffle an array?
arr.sort(() => Math.random() - 0.5);
40. How do you remove a specific element from an array?
arr.splice(arr.indexOf(element), 1);
41. How do you find the common elements in multiple arrays?
arrays.reduce((a, b) => a.filter(c => b.includes(c)));
42. How do you create an array from a string?
str.split(', ');
43. How do you check if an array is empty?
arr.length === 0;
44. How do you convert a number to an array of its digits?
Array.from(String(number), Number);
45. How do you sum up values of a specific property in an array of objects?
arr.reduce((sum, obj) => sum + obj.property, 0);
46. How do you find the index of an object in an array based on a property value?
arr.findIndex(obj => obj.property === value);
47. How do you check if an array contains an object with a specific property value?
arr.some(obj => obj.property === value);
48. How do you extract values of a specific property from an array of objects?
arr.map(obj => obj.property);
49. How do you sort an array of objects by a property value?
arr.sort((a, b) => a.property - b.property);
50. How do you remove all non-numeric values from an array?
arr.filter(item => typeof item === 'number');
