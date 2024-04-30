# Part 2

1. At line 12, the code will print prices.length, since i is incremented to prices.length and the loop ends, but i is still a valid variable until the function returns.
2. At line 13, the code will print the discounted price of the last item in the prices array, which should equal 150.
3. At line 14, the code will print the final price of the last item in the prices array.
4. This function returns an array of the final prices after applying discounts to initial prices and rounding them to get a final price. This array is called discounted, which is appended to after each iteration of each loop.
5. An error is thrown because i no longer exists outside of the loop block because it was declared with let, which gives the variable block-scope
6. An error is thrown because discountedPrice no longer exists outside of the loop block because it was declared with let, which gives the variable block-scope
7. At line 14, the code will print the final price of the last item in the prices array.
8. The function will throw a reference error because discounted is block-scope and cannot be returned
9. An error is thrown in the loop block when attempting to push an element into the const array, which is immutable
10. An error is thrown in the loop block when attempting to push an element into the const array, which is immutable
11. An error is thrown in the loop block when attempting to push an element into the const array, which is immutable
12. Data Types
    1. student.name
    2. student['Grad Year']
    3. student.greeting()
    4. student['Favorite Teacher'].name
    5. student.courseLoad[0]
13. Arithmetic
    1. '3' + 2 returns '32' because int 2 is converted to string '2' and concatenated with '3'
    2. '3' - 2 returns 1 because string '3' is converted to int 3 and subtracted by 2
    3. 3 + null returns 3 because null is converted to int 0 and added to 3
    4. true + 3 returns 4 because true is converted to int 1 and added to 3
    5. false + null returns 0 because false is converted to int 0 and null is converted to int 0 and they're added together
    6. '3' + undefined returns '3undefined' because undefined is converted to a string 'undefined' and concatenated to '3'
    7. '3' - undefined returns NaN because '3' is converted to a number but undefined cannot be converted into a number, so it results in 'NaN' which means 'Not A Number'
14. Comparison
    1. '2' > 1 returns true because '2' is converted to the int 2, which then evaluates the comparison to true.
    2. '2' < '12' evaluates to false because the strings are compared character by character, and by lexicographical comparison the '2' is greater than '1'
    3. 2 == '2' returns true because '2' is converted to a number and 2 == 2
    4. true == 2 returns false because true is converted to int 1 which does not equal 2
    5. true === Boolean(2) returns true because Boolean(2) evaluates to true, since it is a non-zero number
15. == performs type coercion while === checks if the type AND value of the two values are equal
17. When modifyArray([1,2,3], callback) is called, a new constant array is created. In each iteration of the for loop, the code attempts to push doSomething(array[i]) into newArr, which is the element in array[i] multiplied by 2. Then the function returns the new array, which should be [2, 4, 6].
19. The function will print 1, 4, 3, 2, since there is a one second delay printing 2 and the next lines are run asyncrhonously with there being a slight delay in printing 3.