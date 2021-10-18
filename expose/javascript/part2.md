1. 3, because it is a var so everywhere has access and it is the index for the loop, which stops incrementing at the length of the array
2. 150, because it is a var so everywhere has access and it is equal to the last value of the array * the discount
3. 150, because it is a var so everywhere has access and it is equal to the final value of the arrays price
4. The discounted array is returned, which contains all of the final prices of the original array multiplied by the discount
5. Error because using let in the for loop means anything outside of the for loop won't have access to that scope
6. Error because using let in the for loop means anything outside of the for loop won't have access to that scope
7. 150, because the let was declared at the function level, which this print stil has access to
8. The discounted array is returned, which contains all of the final prices of the original array multiplied by the discount
9. Error because using let in the for loop means anything outside of the for loop won't have access to that scope
10. 3, because it is the length of the array that is submitted as the first parameter
11. The discounted array is returned, which contains all of the final prices of the original array multiplied by the discount.  Even though discounted was declared
as a const type, you can still push values into the array, you just can't reassign
12. A. student.name
12. B. student["Grad Year"]
12. C. student.greeting()
12. D. student["Favorite Teacher"].name
12. E. student.courseLoad[0]
13. A. 32, because the 2 is converted to a string due to concatenation
13. B. 1, because the 3 gets converted to an int
13. C. 3, because the null gets converted to 0
13. D. 3null, because the null gets converted to "null"
13. E. 4, because the true becomes a 1
13. F. 0, because false and null both are 0
13. G. 3undefined, because the undefined gets converted to "undefined"
13. H. NaN, because undefined can't be converted to an int
14. A. true, because '2' becomes 2
14. B. true, because '2' becomes 2 and '12' becomes 12
14. C. true, because '2' becomes 2
14. D. false, because it is a deep equal, which checks for typing as well
14. E. false, because 2 and true don't equal
14. F. true, because 2 is converted to a true using the Boolean operation
15. == is a soft equals, which doesn't care for typing and will allow for more leniency, like converting 2 to '2' or vice versa.  Meanwhile, 
the three = checks for the type of the object.
16. coded in file
17. The result will be [2, 4, 6].  The first function simply calls the callback function on each element of the array and stores it.  The callback doubles the value
that is passed in, so 1 becomes 2, 2 becomes 4, and 3 becomes 6.
18. coded in file
19. 1 4 2 3, because 2 and 3 are timed out
