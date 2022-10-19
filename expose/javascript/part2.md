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

# Q12
### A
```javascript
student.name
```
### B
```javascript
student["Grad Year"]
```
### C
```javascript
student.greeting()
```
### D
```javascript
student["Favorite Teacher"].name
```
### E
```javascript
student.courseLoad[0]
```

# Q13
### A
`"32"`, since integers map to their exact string representation
### B
`1`, since `"3"` maps to its integer value

### C
3, `null` can be converted to `Number` and its value is 0

### D
`"3null"`, 

### E
4, true maps to 1

### F
0, false maps to 0 and null maps to 0 as a number


### G
3undefined, `undefined` maps to the string 'undefined'

### H
NaN, `undefined` is not a number

# Q14
### A
true, '2' maps to 2

### B
true, '2' maps to 2 and '12' maps to 12

### C
true, == will not compare the type

### D
false, === will compare the data type

### E
false, `true` will be converted to number which is 1, clearly 1 != 2

### F
true, since `Boolean(2)` is true. Note that only `Boolean(0)` is false

# Q15
`==` will first attempts to convert the operands to the same data type and then do the comparison.

`===` always considers operands of different types to be diffenrent.

# Q16
see [part2-question16.js](part2-question16.js)

# Q17
