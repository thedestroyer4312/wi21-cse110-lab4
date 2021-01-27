1. It will print the last value of the variable `i` from the for loop which is `i = prices.length`, the value that causes the for loop to terminate.
2. It will print the last discounted price that occurred in the loop, which is `prices[prices.length - 1] * (1 - discount)` because var persists outside of the for loop.
3. It will print the last final price because var persists outside of the for loop.
4. The function will return [50, 100, 150] because it iterates through each value of the prices array and applies the discount to it, which is 0.5 in this case.
5. There will be an error because `let`, so the line is referring to a variable that does not exist in that scope.
6. There will be an error because the statement is attemping to call a variable that is out of scope.
7. It will print the final value of `finalPrice` as it was modified in the for loop, as it is in scope.
8. It will return [50,100,150] because it iterates through each value and applies the discount, which works in this case as planned.
9. There will be an error because the `i` variable is out of scope of the statement.
10. There will be an error because the `discountedPrice` variable is out of scope and is also causing an error in the for loop.
11. Normally, it would print 0, but since it is trying to reassign `finalPrice` inside the for loop, there will be an error inside the for loop.
12. It will cause an error before it returns because the variable `finalPrice` cannot be modified in the for loop. Then, it will return an empty array.
13. 
    1. `student.name`
    2. `student['Grad Year']`
    3. `student.greeting()`
    4. `student['Favorite Teacher'].name`
    5. `student.courseLoad[0]`
14. 
    1. `'32'` because of string concatenation
    2. `1` because of string conversion to number
    3.  `3` because of conversion of `null` to `0`
    4.  `'3null'` because of conversion of `3` to string and `null` to `'null'`
    5.  `4` because of conversion of `true` to `1`
    6.  `0` because of numeric conversion for both to `0`
    7.  `'3undefined'` because of conversion of both to string
    8.  `NaN` because of attempted conversion from string to number resulted in invalid number.
15. 
    1. `true` because `'3'` is converted to number to evaluate the comparison, which is true.
    2. `false` because lexicographical comparison is performed on the two strings, no numeric conversion.
    3. `true` because `'2'` is converted from string to number to perform the comparison.
    4. `false` because you cannot compare a number and string to be equal under strict equality `===`
    5. `false` because `true` is converted to the number `1`
    6. `true` because `Boolean(2)` converts the number `2` to the boolean `true`
 16. The `==` operator allows for type conversions in comparison while the strict equality operator `===` does not.
 17. `'How are you?'` gets printed because the first statement `2 == true` evaluates to false since `true` is converted to the number `1` and `2 == 1` is clearly false. Then, in the second if statement, `2` is converted to the boolean `true` because it is nonzero. So, `'How are you?'` will be printed.
18. In `question18.js`
19. `[6, 8, 10]` would be the result. The function `modifyArray` iterates through each value of the array and applies the callback that adds 2 and then doubles the value. So, it would add 2 and double each of the values in the input `[1, 2, 3]`, which results in `[6, 8, 10]`.
20. First, `i` will be printed. Then, `4` will be printed, followed by `3` and `2`.