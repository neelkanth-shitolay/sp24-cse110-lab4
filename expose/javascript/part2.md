12. Accessing Properties and Methods of the 'student' Object

   a. `student.name`   
   b. `student['Grad Year']`  
   c. `student.greeting()`  
   d. `student['Favorite Teacher'].name`  
   e. `student.courseLoad[0]`  

13. Arithmetic

   a. `'3' + 2` - Output: '32', String concatenation.  
   b. `'3' - 2` - Output: 1, String converted to number, then subtraction.  
   c. `3 + null` - Output: 3,  null coerced to 0.  
   d. `'3' + null` - Output: '3null', null coerced to string 'null'.  
   e. `true + 3` - Output: 4, Boolean coerced to number (true -> 1).  
   f. `false + null` - Output: 0, Boolean coerced to number (false -> 0), null coerced to 0.  
   g. `'3' + undefined` - Output: '3undefined', undefined coerced to string 'undefined'.  
   h. `'3' - undefined` - Output: NaN, String cannot be subtracted from undefined, results in NaN.  

14. Comparison

   a. `'2' > 1` - Output: true, '2' is converted to a number (2) and compared with 1. 2 is greater than 1.  
   b. `'2' < '12'` - Output: false, Lexicographically, '2' is greater than '1', so '2' is not less than '12'.  
   c. `2 == '2'` - Output: true, Loose equality comparison, where '2' is coerced to a number before comparison.  
   d. `2 === '2'` - Output: false, Strict equality comparison, where types are not coerced. Number 2 is not equal to string '2'.  
   e. `true == 2` - Output: true, Loose equality comparison, where true is coerced to 1 before comparison.  
   f. `true === Boolean(2)` - Output: true, Strict equality comparison, both operands are of the same type and have the same value.  

15. The `==` operator in JavaScript does loose equality comparison, which allows type coercion when the two are different data types. However, the `===` operator performs strict equality comparison without type coercion, ensuring both value and type match.

16. [Link to part2-question16.js](part2-question16.js)


17. Calling `modifyArray([1, 2, 3], doSomething)` applies the `doSomething` function to each element of `[1, 2, 3]`. The `doSomething` function doubles each element. Therefore, the result is `[2, 4, 6]`.

18. [Link to part2-question18.js](part2-question18.js)

19. Output:  
    1  
    4  
    3  
    2   


