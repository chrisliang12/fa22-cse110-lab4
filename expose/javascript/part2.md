# Q1
Line 12 will print 3 in the console. This is because `i` is declared with `var` which has a function scope. Thus, it can be accessed after the for loop.

# Q2
Line 13 will print 150 which is the value of `discountedPrice` because in the last iteration the discountedPrice is re-declared as 300 * 0.5.

# Q3
Line 14 will print 150 because line 14 will only print the value of `finalPrice` in the last iteration in for loop, 

# Q4
The function will return a array which stores corresponding discount value of the `prices` element.

# Q5
Line 12 will cause an error because now `i` is declared using `let` and we are trying to use its value outside of its scope.

# Q6
Line 13 will also cause an error because `discountedPrice` only exists in the scope of the for loop and we are trying to reference its value outside of the scope.

# Q7
Line 14 will print 150, which is the value calculated in the last iteration of the for loop.

# Q8
The function will return a array which stores corresponding discount value of the `prices` element.

# Q9
Line 12 will cause an error because now `i` is declared using `let` and we are trying to use its value outside of its scope.

# Q10
Line 12 will print 3 since `princes`'s length is 3

# Q11
The function will return a array which stores corresponding discount value of the `prices` element. Even though we are using `const` to declare `discountedPrice` but we do not redeclare the variable. Instead, we initialize a new variable in every iteration of the for loop so it is valid.