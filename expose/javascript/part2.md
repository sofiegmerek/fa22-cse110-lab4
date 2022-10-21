1. At line 12 the number 3 would be printed to the console because thats the value of i, as that's the length of the prices array.
2. At line 13 the discounted price will be output to the console which is (300*(1-0.5)) = 300*0.5 = 150, so it would print "150". This is the last value discounted price is set to.
3. At line 14 whats printed is the final value of finalPrice which is 150*100/100= 150, so it would print "150" to the console.
4. The function will return an array of all the final prices of the items, so it would be [50, 100, 150];
5. This would return an error because i is not declared in that block, so we cannot print i as it does not exist.
6. This would also cause an error because we did not declare discountedPrice in that block so it does not exist outside of the block so we cannot print it.
7. Since finalPrice was declared outside the block we can print it, and it would print the moost recent final price which is "150"
8. The function will return an array of all the final prices of the items so it would return [50, 100, 150];
9. This would print the value of i to the console which would be 3 at the end of the iterations.
10. This would print the length of the prices, or 3.
11. This function will return an empty array, as we cannot modify a const variable.
12. 
    A. student.name
    b. "Grad Year" in student or student["Grad Year"]
    c. student.greeting()
    d. student["Favorite Teacher"].name
    e. student.courseLoad[0]

13. 
a. The result is '32' this is because 2 is converted into a string and concatenated with 3, addition can be seen as concatenation.
b. The result is 1, this is because 3 is converted into an int and 3-2 is 1. 
c. The result is 3, null does not add a value as null becomes 0, 3+-=3
d.The result is '3null' this is because 3 is a string and null is converted into a string and concatenated to 3.
e. The result is 4, because true is converted to 1 as an int and 1+3 = 4
f. The result is 0, because fasle is converted to 0 as an int and null is also converted to 0 so 0+0 = 0
g. The result is the string '3undefined' this is because 3 is a string, undefined is also treated as a string and concatenated to 3.
h. The result is NaN, because 3 and undefined are converted to ints, and since undefined becomes NaN, it doesnt matter what you add the result is always NaN.

14. 
a. The result is true because 2 is converted into the int form and 2 > 1
b. The result is false because 2 and 12 are strings and the first character for 2 is 2 and 2 is greater than the first character for 12, 1.
c. This is true, the right side is converted to an int and 2 does equal 2.
d. This is false because === does not do conversions and just compares and the string 2 is not the same as the int 2.
e. This is false becasue true is converted to 1 as an int and 1 is not the same as 2.
f. This is true because Boolean(2) converts 2 into true as it is not 0, so true is the same as true.

15. The == operator checks for equality between values and can do the type conversion, while the ==== operator cchecks strict equality, so if they are different types they are not converted and it returns false;

17. In the function the result would be [2, 4, 6]. This function takes in an array and a callback function as a parameter, the array is [1, 2, 3], we then iterate through the array and push onto a new array the result of the callback function on that object, and our callback function doubles the value given and returns that, so we have an array in the end with all the original values doubled.

19. The output of the code is 1 being printed to the console first, 2 being printed to the console every 1 second, 3 being logged to the console every millisecond, and 4 being printed to the console and then repeating.