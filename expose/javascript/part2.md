1. 3 will be printed in the console because the i variable is a var so it is accessible outside the for loop block.
2. 150 will be printed in the console because the discountedPrice variable is a var so it is accessible outside the for loop block.
3. 150 will be printed in the console because the finalPrice variable is a var so it is accessible outside the for loop block.
4. The function will return [ 50, 100, 150 ] because the for loop pushes finalPrice of each element in our array to the discounted array. 
5. Error will occur because i is not defined. Since our i variable is defined with let, it is only accessible within the scope of the for loop.
6. Error will occur because discountedPrice is not defined. Since our discountedPrice variable is defined with let and initialized in the for loop, it is only accessible within the scope of the for loop.
7. 150 will be printed in the console because finalPrice is initialized within the same block as our console.log thus the finalPrice variable is within scope.
8.  The function will return [ 50, 100, 150 ] because discounted is defined within the same block as our return in the function. Thus the return call has access to the discounted variable and is able to return the correct values.
9.  Error will occur because i is not defined. Again, i is accessible only within the scope of the for loop because we initialize it in the for loop and thus it is out of scope. 
10. 3 will be printed the console. This is because we store the length of the original array being passed in and store this as a const. So this variable cannot change and simply retains the value of the original array. This is also initialized within the scope of the function so we have access to print to the console.
11. The function will return [ 50, 100, 150 ] because although the array is defined as a const, this only means we cannot reassign it. We are still able to push new elements to the array and thus we get the correct return output.
12. JSON
    1.  student["name"]
    2.  student["Grad Year"]
    3.  student["greeting"]()
    4.  student["Favorite Teacher"]["name"]
    5.  student["courseLoad"][0]
13. Arithmetic
    1.  32 because integers map to their exact string representation and the 2 is read as a string
    2.  1 because since we are subtracting, '3' is mapped to the integer value 3 and 2 is subtracted from the integer value.
    3.  3 because null is mapped to the intger value 0 since we are doing integer addition.
    4.  3null because null is mapped to the string value 'null' since we are performing concatenation on the string '3'
    5.  4 because true is mapped to the integer value 1 and we perform integer addition with 1 and 3
    6.  0 because false is mapped to the integer value 0 and null is mapped to the integer value 0, thus 0 + 0 = 0
    7.  3undefined because undefined is mapped to the string value 'undefined' and we perform concatenation
    8.  error since we are subtracting, undefined is not mapped the string value and there is no valid integer to subtract from 3
14. Comparison
    1.  true because '2' is mapped to the integer value of 2 and 2 > 1 
    2.  false because both are mapped to their strings value and are compared alphanumerically. Since the first char in '12' is 1 we compare '1' and '2' and thus '1' should be less than '2'
    3.  true because we are doing regular equality and '2' is mapped to integer value
    4.  false because we are doing strict equality and 2 is an integer and '2' is a string.
    5.  false because true maps to 1 and is not the same as 2
    6.  true because every value of Boolean() with an integer except for 0 is going to evaluate as true. Thus we compare true === true which is true.
15. == compares for regular equality and converts operrands of different types to compare their values. === is a strict comparison and does not convert any types and simply compares exact equality.
16. See part2-question16.js
17. The result will be [ 2, 4, 6 ] because we call the modifyArray with the parameters of array = [1,2,3] and callback = the function doSomething. We create a new array and look though our array input pushing the output of doSomething on each element of the array into the newArr. doSoemthing multiples the num by 2 and returns the value. Thus, we multiply each element by 2 and push these to our new array returning the final array.
18. See part2-question18.js
19. 1 4 3 2