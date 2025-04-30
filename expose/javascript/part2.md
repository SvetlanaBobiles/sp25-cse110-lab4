# Part 2

1. The code will return 3 because in the for loop, for the "i" variable it used "var" so it's scope is within the function. Since the prices list length is 3, the for loop ran 3 times so i = 3 so the console printed 3.

2. The code will return 150 because for the variable "discounted price", it used the keyword "var" so it was able to be printed outside the for loop. It's 150 because by the end of the for loop it was on the last index of the prices list, which was 300 and the discounted price would be 150.

3. The code will return 150 because the variable, "final price" used "var" and the console log was within the function. Final price is the same value as discounted price bc the purpose of final price is to round incase the discounted price was a decimal, which in this case it was not.

4. In terms of console nothing was printed. But the function would return a list that took the parameters, and applied the discount to the prices list. The function would return [50, 100, 150].

5. At line 12 it returned an error because "i" is not defined. It's not defined because by replacing "var" with "let", the variable "i" only exists within the for loop. So by trying to access it on line 12 to print, it caused an error.

6. At line 13 it caused an error because "discountedPrice" was not defined. It's not defined bc it used "let" and was initially defined within the for loop, and line 13 is outside of that scope.

7. At line 14 it will return 150. Printing the final price works because "finalPrice" was initialized in the beginning of the function and is within the same scope as line 14 (it wasn't defined in another block).

8. Nothing was printed but the function would return [50,100,150]. Despite not being able to access "i" and "discounted price", it still returned the same result as before when using var because the function returned the variable "discounted", which was initialized in the beginning of the function and is within the same scope as line 16.

9. At line 11 it will cause an error because "i" was defined with "let" and it was within a for loop, so by line 11 when it's trying to access it, the variable "i" does not exist anymore bc it's not within the same scope anymore.

10. At line 12 it will return 3 because "length" was defined with "const" at the beginning of the function and is within the same scope as line 12 so it was able to access the variable to print.

11. It will not print anything but the function would return [50, 100, 150]. Despite the variable "discounted" being a "const", for an array if values are being added to it via push, it is possible to bypass the const's immutability.

12. A) student.name
    <br>
    B\) student['Grad Year']
    <br>
    C) student.greeting();
    <br>
    D) student['Favorite Teacher'].name
    <br>
    E) student.courseLoad[0]

13. A) It returned '32' because '3' is a string so instead of + meaning to add the numbers it just concatenated 3 and 2.
    <br>
    B) It returned 1 because even tho '3' is a string it saw the -, so it turned it into a number and subtracted 2 from 3.
    <br>
    C) It returned 3 bc the number 3 + null(which is essentially nothing) would still be 3.
    <br>
    D) It returned '3null' because '3' is a string so it processed null as a string instead and concatenated 3 and null.
    <br>
    E) It returned 4 because true = 1 and 1 + 3 = 4.
    <br>
    F) It returned 0 because false = 0 and null is nothing so it equals 0.
    <br>
    G) It returned '3undefined' bc '3' is a string so it concatenated it with undefined 
    <br>
    H) It returned NaN because of the - operator so it automatically thought of a numeric subtraction but you can't subtract with undefined.

14. A) It returned true because it converted '2' into a number, and 2 is greater then 1 so it returned true
    <br>
    B) It returned false because '2' and '12' are both strings so it doesn't convert it into numbers, but compares it lexicographically.
    <br>
    C) It returns true because it turned '2' into a number and 2 == 2 is true.
    <br>
    D) It returns false because the === operator compares value and type, and 2 is a number while '2' is a string so it's false.
    <br>
    E) It returns false because true = 1 and 1 does not equal 2.
    <br>
    F) It returns true because boolean(2) is the same type as true.

15. The difference between the == and === operators is that == does weak type casting, so 2 == '2' would return true bc it converts the '2' to a number. But 2 === '2' would return false because it considers the type as well while comparing, and 2 is a number and '2' is a string.

16. JavaScript File: [file](part2-question16.js)
17. The result would be [2,4,6] because when calling the function modifyArray, the parameters given was an array [1,2,3] and the function doSomething. In line 4, it's within a for loop that repeats for each element in the array, and it calls the function that was taken as a parameter which in this case is doSomething. The function "doSomething" basically doubles the num, and line 4 uses doSomething for each element. Then it pushes it into the new array and returns the doubled array.
18. JavaScript File: [file](part2-question18.js)
19. The output is in the order 1, 4, 3, 2.
