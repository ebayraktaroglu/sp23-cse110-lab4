1. Line 12 will print "3," the value of i when the loop ends.
2. Line 13 will print "150," the last discounted price calculated by the for loop.
3. Line 14 will print "150," which is the last final price calculated by the for loop.
4. The code will return a list of prices, prices that are the ones given to the function with the given discount applied to them. The list will be [50,100,150].
5. Line 12 will cause a ReferenceError, since i is only defined in the for loop, not outside it.
6. Line 13 will cause a ReferenceError, since discountedPrice is only defined in the for loop, not outside it.
7. Line 14 will print "150," which is the last final price calculated by the for loop. Even though the variable finalPrice is used in the for loop, it is defined outside it in the function, so finalPrice is defined in line 14.
8. The code will return a list of prices, prices that are the ones given to the function with the given discount applied to them. The list will be [50,100,150].
9. Line 11 gives a ReferenceError because i in only defined in the for loop, not outside it.
10. Line 12 will print "3," which is the length of the prices list when the function is called.
11. The code will return a list of prices, prices that are the ones given to the function with the given discount applied to them. The list will be [50,100,150].
12. Parts:
    - A. student.name
    - B. student['Grad Year']
    - C. student.greeting()
    - D. student['Favorite Teacher'].name
    - E. student.courseLoad[0]
13. Parts:
    - A. '32' because 2 is converted to the string '2' because the plus sign can indicate string concatenation.
    - B. 1 because the '3' gets converted to 3 because the negative sign doesn't do anything for strings.
    - C. '3' because null gets converted to 0.
    - D. '3null' because null gets converted to 'null' so it can be concatenated to '3'.
    - E. 4 because true gets converted to 1.
    - F. 0 because both false and null are converted to 0.
    - G. '3undefined' because undefined gets converted to 'undefined' to get concatenated with '3'.
    - H. NaN because '3' gets converted to 3 and undefined gets converted to NaN.
14. Parts:
    - A. true because '2' becomes 2.
    - B. false because '2' isn't lexographically smaller than '12'.
    - C. true because '2' becomes a 2
    - D. false because 2 isn't equal to '2' without doing type conversions.
    - E. false because true converts to 1 and 1 doesn't equal 2.
    - F. true because Boolean(2) becomes true.
 15. == tries to convert the two values into the same type, then does the comparison, while === does comparison without doing type conversion.
 17. The result will be [2,6,8]. The function modifyArray iterates through all the values in the array [1,2,3] and runs the function doSomething on each value and pushed them to the new array that will be returned. The function doSomething multiplies each value by 2.
