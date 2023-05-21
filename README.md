# DestructingProject
# Programming Assignments

This repository contains solutions to several programming assignments. Each assignment focuses on a specific problem and provides a corresponding solution.

## Assignments

1. [Word Count Generator](#word-count-generator)
2. [Remove Duplicates](#remove-duplicates)
3. [Swap Values](#swap-values)
4. [Extract Elements](#extract-elements)
5. [Find Min and Max](#find-min-and-max)
6. [Nested Objects](#nested-objects)

## Word Count Generator

### Description

The `countOccurrences` function takes a large string of text as input and counts the occurrences of each word in the string. It returns a Map containing each word's count.

### Usage

```javascript
const text = "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed sed magna diam, consectetur at aliquam sit amet.";

const wordCount = countOccurrences(text);
console.log(wordCount);
Output
Map(11) {
  'Lorem' => 1,
  'ipsum' => 1,
  'dolor' => 1,
  'sit' => 2,
  'amet' => 2,
  'consectetur' => 2,
  'adipiscing' => 1,
  'elit' => 1,
  'Sed' => 1,
  'sed' => 1,
  'magna' => 1
}
Remove Duplicates
Description
The removeDuplicates function takes an array of numbers as input and efficiently removes all the duplicates, returning a new Set that contains only the unique elements.
Usage
const numbers = [1, 2, 3, 2, 4, 5, 1, 3];

const uniqueSet = removeDuplicates(numbers);
console.log([...uniqueSet]);
Output
[1, 2, 3, 4, 5]
Swap Values
Description
The swapValues function swaps the values of two variables without using a temporary variable. It takes two variables as input, destructures them into an array, swaps their positions within the array, and returns an array with the swapped values.

Usage
javascript
Copy code
let x = 5;
let y = 10;

const swappedValues = swapValues(x, y);
console.log(swappedValues);
Output
csharp
Copy code
[10, 5]
Extract Elements
Description
The extractElements function takes an array as input, destructures it into three variables representing the first, second, and last elements, and returns an array with these three values.

Usage
javascript
const numbers = [1, 2, 3, 4, 5];

const extractedArray = extractElements(numbers);
console.log(extractedArray);
Output
csharp
[1, 2, 5]
Find Min and Max
Description
The findMinMax function takes an array of numbers as input and uses the spread operator with the Math methods max() and min() to find the maximum and minimum values. It returns an object with two properties, max and min, representing the maximum and minimum values in the input array, respectively.

Usage
javascript
const numbers = [5, 2, 7, 1, 9];

const result = findMinMax(numbers);
console.log(result);
Output
arduino
Copy code
{ max: 9, min: 1 }
Nested Objects
Description
The extractProperties function takes an object representing a person as input and extracts the name and street properties from a nested object using object destructuring. It returns an object with these two properties.

Usage
javascript
const person = {
  name: "Mithun",
  age: 21,
  address: {
    street: "B8, Block B, Industrial Area.",
    city: "Sector 62, Noida",
    state: "Uttar Pradesh"
  }
};

const extractedProperties = extractProperties(person);
console.log(extractedProperties);
Output
css

{ name: "Mithun", street: "B8, Block B, Industrial Area." }
Feel free to explore each assignment and their respective code implementations. Happy coding!

sql

You can create a new README.md file in your Git repository and replace the content with the above sample README. Feel free to modify it according to your needs and add any additional information or instructions that you find necessary.



