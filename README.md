# The Spread Operator

## To use this Repository:
To run this file in Gitpod, use the command `node the-spread-operator.js` in the terminal.

    node the-spread-operator.js

## Terminal Output: 

    First array: [ 1, 2, 3, 4 ]
    Second array: [ 1, 2, 3, 4 ]
    ------------------------------------------
    Third array: [ 4, 5, 6 ]
    Fourth array: [ 4, 5, 6, 7 ]
    ------------------------------------------
    First object: { a: 1, b: 2, c: 3 }
    Second object: { a: 1, b: 2, c: 3, d: 4 }
    Third object: { a: 1, b: 5, c: 3 }
    ------------------------------------------
    Fifth array: [ 1, 2, 3, 4, { a: 1, b: 2, c: 3 }, 4, 5, 6, 'x', 'y', 'z' ]

## Result Summary

- The first set of results show how copying an array without the spread operator creates a reference to the original array, while copying an array with the spread operator creates a new, separate array with the same values.

- The second set of results show how copying an object without the spread operator creates a reference to the original object, while copying an object with the spread operator creates a new, separate object with the same properties and values.

- The third set of results demonstrate how to copy an object and make changes to it while creating a new object. It is not showing how to copy only part of an object or array. To copy only part of an object or array, you would need to use array/object destructuring and create a new object/array with only the desired properties/elements.

- The fourth set shows an example of copying elements from multiple arrays and objects into a new array using the spread operator. In this case, it shows how to copy elements from arr1, obj1, and arr3 into arr5. The result is a new array arr5 that contains the elements of arr1, a copy of obj1, the elements of arr3, and string values "x", "y", "z".