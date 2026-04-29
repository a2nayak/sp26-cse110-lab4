
Question 1:
Line 9 prints `values added:  20`.

Question 2: 
Line 13 prints `final result:  20`.

Question 3:
You should not use `var`, since it is not scoped to the block it is defined in.
This can lead to variable name collisions, making debugging more difficult.
In essentially all cases, using `let` is preferred, since it makes variable scoping explicit from the code structure. 

Question 4:
Line 9 prints `values added:  20`.

Question 5:
The code at line 13 returns an error, namely `ReferenceError: result is not defined`.
This is because using the `let` keyword scopes `result` to the first if-statement block, and so it is not defined at the outermost scope of the function.

Question 6:
Nothing is printed, since the code at line 7 returns a `TypeError: Assignment to constant variable.`
This is because `result` was declared `const`, which means that reassigning to it by executing `result = num1 + num2;` is not permitted.
After this error, the code immediately returns from the function, which prevents line 9 from being executed.

Question 7:
Nothing is printed. As described in question 6, the code has a `TypeError` from a reassignment to a `const` variable at line 9. After this error, the code immediately returns from the function, which prevents line 13 from being executed.

