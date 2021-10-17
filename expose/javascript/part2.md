1. It will print 3 to the console since i was defined using var and that is the last value.
2. It will print 150 to the console since discountedPrice was defined using var and that is the last value.
3. It will print 150 to the console since finalPrice was defined using var and that is the last value.
4. It returns an array, [50, 100, 150], which is the prices with a 50% discount.
5. ReferenceError: i is not defined, since we defined i using let in the loop initalization, which keeps its scope to the loop.
6. ReferenceError: discountedPrice is not defined, since we defined discountedPrice using let in the loop, which keeps its scope to the loop.
7. It will print 150 to the console anyways since finalPrice was initially defined outside of the loop and that is the last value.
8. It returns an array, [50, 100, 150], which is the prices with a 50% discount.
9. ReferenceError: i is not defined, since we defined i using let in the loop initalization, which keeps its scope to the loop.
10. It will print 3 to the console since we are just printing the value.
11. TypeError: Assignment to constant variable, since on line 7 we try to change the value of const discountedPrice.
12. 
    A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. 
    A. '32', since + converts operands to strings and concatenates them if one of them is a string
    B. 1, since - converts operands to numbers
    C. 3, since null is coverted to 0
    D. 3null, since + converts operands to strings and concatenates them if one of them is a string
    E. 4, since true is converted to 1
    F. 0, since false and null are both coverted to 0s.
    G. 3undefined, since + converts operands to strings and concatenates them if one of them is a string
    H. NaN, since undefined is converted to NaN.
14. 
    A. true, since strings are converted to numbers when being compared with a number
    B. false, since strings are compared left to right and 2 > 1
    C. true, since strings are converted to numbers when being compared with a number
    D. false, since === also checks type
    E. false, since true is 1 when converted
    F. true, since any number that is not 0 is true as an argument to Boolean()
15. == checks value only, === checks both value and type

17. It will return the array [2, 4, 6], since we call doSomething, which was passed as a callback, to multiply each value in the original array by 2. 

19. 
1
4
3
2
