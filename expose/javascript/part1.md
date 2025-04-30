# Part 1

1. 20

2. 20

3. You should not use var because var only has function scope, which means it can be accessed anywhere inside the function so it ignores typical block codes like if, and for statements. So by using var it can lead to more variable name conflicts and scoping issues.

4. 20

5. The code will return an error because by changing result to let instead of var, the variable only exists within the if statement so by line 13 the variable wasn't defined anymore.

6. The code will return an error bc line 7 attempted to change the value of result despite it being a const, so it caused an error.

7. Same as above, nothing was printed bc it caused a type error.