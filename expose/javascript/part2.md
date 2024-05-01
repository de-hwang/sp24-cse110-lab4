1. Line 12 will print 3 because `i` breaks out of the loop when it equals 3.
2. Line 13 will print "150" because the last time that `discountedPrice` is changed is when the `0.5` discount is applied to `prices[2] = 300`.
3. Line 14 will print "150" because the last time that `finalPrice` is changed is when the calculation is applied to `discountedPrice = 150`.
4. The function will return the array `[50, 100, 150]`, as the loop will finish iterating after pushing the updates prices into the `discounted` array.
5. The code will cause an error at Line 12 because `i` is no longer defined. The code is attempting to print `i` outside of the block where it was defined, which was the for loop.
6. The code will cause an error at Line 13 because `discountedPrice` is no longer defined. The code is attempting to print `discountedPrice` outside of the block where it was defined, which was the for loop.
7. Line 14 will print "150" because the last instance in which `finalPrice` is changed is when the loop acts on `prices[2] = 300`. The code will not cause an error, as `finalPrice` is defined in the whole function block.
8. The function will return the array `[50, 100, 150]`, as the loop finishes iterating after pushing the discounted prices into the `discounted` array. The code will not cause an error, as `discounted` is defined in the whole function block.
9. The code will cause an error at Line 11 because `i` is no longer defined. The code is attempting to print `i` outside of the block where it was defined, which was the for loop.
10. Line 12 will print "3" because `length` is defined as the length of the `prices` parameter. In this case, `length = 3`, so `3` is printed.
11. The function will return the array `[50, 100, 150]`, as the loop finishes iterating after pushing the discounted prices into the `discounted` array. The code will not cause an error, as `discounted` is still defined as an array, so there is no invalid update.
12. <br>
    <ol type="A">
    <li><code>student.name</code></li>
    <li><code>student["Grad Year"]</code></li>
    <li><code>student.greeting()</code></li>
    <li><code>student["Favorite Teacher"].name</code></li>
    <li><code>student.courseLoad[0]</code></li>
    </ol>
13. <br>
    <ol type="A">
    <li><code>32</code> is outputted because <code>2</code> is converted to a string, and thus the two strings are concatenated.</li>
    <li><code>1</code> is outputted because "3" is converted to a number, and thus the two numbers are subtracted.</li>
    <li><code>3</code> is outputted because <code>null</code> is converted to <code>0</code>, and thus the two numbers are added.</li>
    <li><code>3null</code> is outputted because <code>null</code> is converted to a string, and thus the two strings are concatenated.</li>
    <li><code>4</code> is outputted because <code>true</code> is converted to <code>1</code>, and thus the two numbers are added.</li>
    <li><code>0</code> is outputted because <code>false</code> is converted to <code>0</code> and <code>null</code> is converted to <code>0</code>, and thus the two numbers are added.</li>
    <li><code>3undefined</code> is outputted because <code>undefined</code> is converted to a string, and thus the two strings are concatenated.</li>
    <li><code>NaN</code> is outputted because "3" is converted to a number, and thus the two numbers are subtracted. However, because <code>undefined</code> is not a valid number, <code>NaN</code> is outputted.</li>
    </ol>
14. <br>
    <ol type="A">
    <li><code>true</code> is outputted because "2" is converted to a number, and thus <code>2 > 1</code>.</li>
    <li><code>false</code> is outputted because "2" comes lexicographically after "12", and thus <code>"2" > "12"</code></li>
    <li><code>true</code> is outputted because "2" is converted to a number, and thus <code>2 == 2</code>.</li>
    <li><code>false</code> is outputted because the two values are not the same type, and thus <code>2 !== "2"</code>.</li>
    <li><code>false</code> is outputted because <code>true</code> is converted to <code>1</code>, and thus <code>1 != 2</code>.</li>
    <li><code>true</code> is outputted because <code>Boolean(2)</code> is converted to <code>true</code>, and thus the two values are the same type. Then, <code>true == true</code>, so <code>true === true</code>.</li>
    </ol>
15. The `==` operator checks two values for equality while also converting different types to the same type. The `===` operator checks if two values are strictly equal. That is, the types of both objects are first checked before the actual values are compared. So, `==` only compares values while `===` checks if the two sides are the same type and value.
16. On separate file.
17. The result of calling the function on the given arguments will be the array `[2, 4, 6]`. When the function is called, it iterates through each element in the argument array. For each element it iterates through, the `doSomething` function is called on it, doubling the value. Then, the new value is pushed into `newArr`. Once the loop is finished, `newArr` is returned.
18. On separate file.
19. `1 4 3 2` is outputted on separate lines.