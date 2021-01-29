1. The value of variable i will be written to the console because it is declared with "var" and so is global-scoped. Using the args in q4, i will be 3.
2. The value of variable discountedPrice will be written to the console because it is declared with "var" and so is global-scoped. Using the args in q4, i will be 150.
3. The value of variable finalPrice will be written to the console because it is declared with "var" and so is global-scoped. Using the args in q4, i will be 150.
4. The function will return the discounted array containing \[50,100,150\]. There are no errors with variable scope as all variables are declared with "var" and thus are global-scoped. The for loop runs and adds all the discounted prices to the discounted array, and the function returns the discounted array.  
5. An error will occur because the i variable is declared with "let" in the for loop and is only accessible within the scope of the for loop.
6. An error will occur because the discountedPrice variable is declared with "let" in the for loop and is only accessible within the scope of the for loop.
7. The value of variable finalPrice will be written to the console because finalPrice is declared with "let" in the same code block as line 11. Using the args in q8, finalPrice will be 150.
8. The function will return an error, at line 11, because the i variable is only accessible within the scope of the for loop.
9. An error will occur because the i variable is declared with "let" in the for loop and is only accessible within the scope of the for loop.
10. An error will occur because the discountedPrice variable is declared with "const" in the for loop and is only accessible within the scope of the for loop.
11. The value of variable finalPrice will be written to the console because finalPrice is declared with "const" in the same code block as line 11. Using the args in q12 and assuming each finalPrice assignment is successful, finalPrice will be 150.
12. The function will return an error, at line 7, because we cannot reassign a value to a "const" variable.
13. 
    - A. student.name
    - B. student\['Grad Year'\]
    - C. student.greeting()
    - D. student\['Favorite Teacher'\].name
    - E. student.courseLoad\[0\]
14.
    - A. \'32\' because the values are converted to strings '3' and '2' and then concatenated.
    - B. 1 because the values are converted to numbers 3 and 2 and then subtracted.
    - C. 3 because the values are converted to numbers, with null becoming 0, and then added.
    - D. \'3null\' because the values are converted to strings '3' and 'null' and then concatenated.
    - E. 4 because the values are converted to numbers, with true becoming 1, and then added.
    - F. 0 because the values are converted to numbers, with false becoming 0 and null becoming 0, and then added.
    - G. '3undefined' because the values are converted to strings '3' and 'undefined' and then concatenated.
    - H. NaN because the values are converted to numbers, with undefined becoming NaN, and so subtracting the two returns NaN.
15. 
    - A. true because 2 is converted to a number and 2 is greater than 1.
    - B. false because the strings are compared in lexicographic order and the first character of '2' is not less than the first character of '12'.
    - C. true because 2 is converted to a number and 2 equals 2.
    - D. false because 2, a number, and '2', a string, are not of the same type.
    - E. false because true is converted to a number and 1 does not equal 2.
    - F. true because Boolean(2) returns true, so they are of equal value and type.
16. == converts the values to the same type and then checks if they are equal while === strictly checks if the two are of both equal value and equal type.
17. "How are you?" gets printed. Looking at the first if statement, 2 == true returns false, so we move to the else if statement, where 2 is boolean converted to true, so we run the code in that block.
18. 
19. newArr will be \[6,8,10\]. For i=0, we call doSomething(1, function()), which returns function(1+2). So function(3) returns 3 times 2 which is 6. Then we add 6 to newArr. For i=1, we call doSomething(2, function()), which returns function(2+2). So function(4) returns 4 times 2 which is 8. Then we add 8 to newArr. For i=2, we call doSomething(3, function()), which returns function(3+2). So function(5) returns 5 times 2 which is 10. So we add 10 to newArr. Then i=4 and the for loop ends, and so we return newArr.
20. 
21. 1, 4, 3, 2
