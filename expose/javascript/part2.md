1. The number *3* is printed to the console. This is because *var i* was declared in the loop and the loop ended once the condition *i < prices.length* was met, which was when *i = 3*.
2. The number *150* is printed to the console. This is because the last value that was set for *discountedPrice* was _300 * (1-0.5) = 150_.
3. The number *150.00* is printed to the console. This is because the last value that was set for *finalPrice* was *150* after the rounding operations.
4. The function returns *[50, 100, 150]* since the function takes the origianl input "prices" of *[100, 200, 300]* and discounts them at a rate of *0.5*.
5. The code will cause an error since *i* is declared within the for loop block with *let*, making it unaccessible outside of that block.
6. The code will cause an error since similarly to the previous question, *discountedPrice* was declared within the for loop block with *let*, making it unaccessible outside of that block.
7. The number *150* is printed to the console. This is because *finalPrice* was declared at line 4, making its scope the whole function even if it was declared with *let*, allowing the variable to be used within the for loop block and outside of it as well.
8. The function returns *[50, 100, 150]* since the function takes the origianl input "prices" of *[100, 200, 300]* and discounts them at a rate of *0.5*. The variables declared in the for loop block are only used within the for loop, so no declaration errors are caused by this code.
9. The code will cause an error since *i* is declared within the for loop block with *let*, making it unaccessible outside of that block.
10. The number *3* will be printed to the console. This is because the *const length* was declared and set to *prices.length* which is equal to 3 at the beggining of the function.
11. The function returns *[50, 100, 150]* since the function works as intended. Although *discounted* was set with *const*, the array is still mutable, allowing values to be added with ".push()".
12. Notations:
    - student.name
    - student["Grad Year"]
    - student.greeting()
    - student["Favorite Teacher"].name
    - student.courseLoad[0]
13. Arithmetic
    - '3' + 2 = '32'
    - '3' - 2 = 1
    - 3 + null = 3
    - '3' + null = '3null'
    - true + 3 = 4
    - false + null = 0
    - '3' + undefined = '3undefined'
    - '3' - undefined = NaN
14. Comparison
    - '2' > 1 --> true
    - '2' < '12' --> false
    - 2 == '2' --> true
    - 2 === '2' --> false 
    - true == 2 --> false
    - true === Boolean(2) --> true
15. == operator compares two values loosly, meaning that if the two values are different data types, it attemps to convert one into the other's data type to compare. === operator compares twoo values stricly, without conversion, meaning if two values are different datatypes, such as 2 and '2', they are not equal.
16. ['Code'](part2-question16.js)
17. The function will return the array *[2, 4, 6]*. When the function runs its loop, for each iteration, doSomething function is called that doubles the value passed as a parameter, doubling each value of the array.
18. ['Code'](part2-question18.js)
19. Output: 1 4 3 2   1 and 4 are printed to the console first since they are synchronous, even if a setTimeout with a time of 0 is run before it. Then 3 with a timeout of 0 seconds and 2 with a timeout of 1 second are printed next.