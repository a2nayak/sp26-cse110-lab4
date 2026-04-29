
Question 1:
The code at line 12 will print `3`. 
For each element in `prices`, the variable `i` increments by 1. Then since `prices` contains 3 elements, the final value of `i` will be 3. Additionally, `i` uses the `var` keyword, so it will be accessible outside of the scope of the loop. Thus, running `console.log(i)` will print `3`.

Question 2:
The code at line 13 will print `150`. 
The last value assigned to `discountedPrice` was `300 * (1 - 0.5)`, which is `150`. Furthermore, `discountedPrice` uses the `var` keyword, so it is not scoped to the loop. 
Thus, running `console.log(discountedPrice)` will print `150`.

Question 3:
The code at line 14 will print `150`.
The last value assigned to `finalPrice` was `Math.round(discountedPrice * 100) / 100`, which is `150`.
Thus `console.log(finalPrice)` prints `150`.

Question 4:
This code returns the list `[50, 100, 150]`.
This is because each iteration of the loop multiplies the `i`th price in `prices` by `0.5` and appends the resulting value to `discounted`.
Since `prices = [100, 200, 300]`, we see that `discounted` becomes `[50, 100, 150]`, which is then returned.

Question 5:
This code returns an error, namely `ReferenceError: i is not defined`.
This is because `i` uses the `let` keyword, which scopes `i` to the loop. Then, it is not defined for the code that runs after the loop.    

Question 6:
This code returns an error, namely `ReferenceError: discountedPrice is not defined`. This is because `discountedPrice` uses the `let` keyword, which scopes `discountedPrice` to the loop. Then, it is not defined for the code that runs after the loop.

Question 7:
The code at line 14 will print `150`.
This is because `finalPrice` is scoped to the outer-most level of the function, and it was last assigned the value `300 * 0.5` inside the loop. Thus, `console.log(finalPrice)` prints `150`.

Question 8:
This code returns the list `[50, 100, 150]`. This is because each iteration of the loop multiplies the `i`th price in `prices` by `0.5` and appends the resulting value to `discounted`.
Since `prices = [100, 200, 300]`, we see that `discounted` becomes `[50, 100, 150]`, which is then returned.

Question 9:
The code returns a `ReferenceError: i is not defined`. This is because `i` uses the `let` keyword, which scopes `i` to the loop. Then, it is not defined for the code that runs after the loop.

Question 10:
The code at line 12 prints `3`. This is because
`prices.length` is initially `3`, and `length` cannot be reassigned to. Thus, `console.log(length)` prints `3`.

Question 11:
The function returns the list `[50, 100, 150]`. This is because each iteration of the loop multiplies the `i`th price in `prices` by `0.5` and appends the resulting value to `discounted`.
Since `prices = [100, 200, 300]`, we see that `discounted` becomes `[50, 100, 150]`, which is then returned.

Question 12:
A. `student.name`
B. `student['Grad Year']`
C. `student.greeting()`
D. `student['Favorite Teacher'].name`
E. `student.courseLoad[0]`

Question 13:
A. '32', because the expression converts 2 to a string, which is concatenated.
B. 1, because subtraction converts the '3' into the number 3
C. 3, because null is converted to 0
D. '3null', because null is converted to the string 'null'
E. 4, because `true` is converted to 1
F. 0, because both `false` and null are converted to 0
G. '3undefined', because `undefined` is converted to the string "undefined"
H. NaN, because subtraction converts `undefined` to NaN 

Question 14:
A. true, since '2' becomes the number 2, which is greater than 1
B. false, since string comparion uses lexicographical order
C. true, since '2' is converted to the number 2
D. false, since === uses strict equality, and 2 and '2' have different types
E. false, since true becomes converted to 1, which is not equal to 2
F. true, since `Boolean(2)` becomes converted to `true`

Question 15:
`==` is the loose equality symbol, and uses type coercion before comparing to convert both inputs to the same data type
`===` is the strict equality symbol, where both inputs must have both the same value and data type to return true

Question 17:
The result will be `[2, 4, 6]`.
This is because `modifyArray` returns a new array with the callback applied to each element. Since our callback doubles the input, we return the element-wise double of `[1, 2, 3]`, which is `[2, 4, 6]`.

Question 19:
The output is:
```
1
4
3
2
```