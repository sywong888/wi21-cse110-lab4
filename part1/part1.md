1. The console will print the value of i after the for loop finishes executing. The value it prints is the length of the prices array. Even though i was intialized inside the for loop, we can still access it outside the loop because it is a var.
   
2. The console prints the last discountedPrice calculated when the for loop executed. This is the value of the last element in the prices array with the discount taken into account. Even though discountedPrice was intialized inside the for loop, we can still access it outside the loop because it is a var.
   
3. The console prints the last finalPrice calculated when the for loop is executed. This value is the finalPrice of the last element in the prices array. We can access finalPrice after the for loop because it is a var that was initialized before the loop.
   
4. This call returns the array [ 50, 100, 150 ] because these are the finalPrices of each price in the prices array. For example, the first element of prices is 100, so in the for loop, the discountedPrice is calculated to be 50 and the finalPrice is calculated to be 50. Afterwards, 50 is pushed to the discounted array which is why 50 is the first element in the array that the function returns. The same process is repeated for the rest of the elemnts in prices.
   
5. Line 11 causes an error because it calls i outside of its scope. Since i is a let that is intialized inside the for loop, we cannot access i outside of the for loop.
   
6. Line 12 causes an error because it calls discountedPrice outside of its scope. Since discountedPrice is a let that is intialized inside the for loop, we cannot access it outside of the for loop.
   
7. Line 13 prints the value of finalPrice, after it has been changed inside the for loop. We are able to access finalPrice and print it outside of the for loop because finalPrice was initialized before and outside the for loop.
   
8. The function does not return anything because errors are thrown due to an error on lines 11 and 12. The errors prevent the rest of the function from running, so nothing is returned.
   
9.  Line 11 causes an error because it calls i outside of its scope. Since i is a let that is intialized inside the for loop, we cannot access i outside of the for loop.
    
10. Line 12 causes an error because it calls discountedPrice outside of its scope. Since discountedPrice is a let that is intialized inside the for loop, we cannot access it outside of the for loop.
    
11. Assuming line 7 does not throw an error, line 13 prints the last finalPrice that is calculated in the for loop. We can access discountedPrice after the for loop because it is a const that is intialized before and outside the for loop.
    
12. The function does not return anything because errors are thrown due to an error on lines 7, 11 and 12. The errors prevent the rest of the function from running, so nothing is returned.
    
13. A. student.name;  
    B. student['Grad Year'];  
    C. student.greeting();  
    D. student['Favorite Teacher'].name;  
    E. student.courseLoad[0];

14. A. This outputs 32 because this code converts 2 into a string and then concatenates '3' and '2'.
    
    B. This outputs 1 because the minus operator converts '3' into a number and 3-2=1.

    C. This outputs 3 because null converts into the number 0 and 3+0=3.

    D. This outputs 3null because the code causes to a string concatenation of '3' and 'null'.

    E. This outputs 4 because true converts to the number 1 and 1+3=4.

    F. This outputs 0 becuase false and null both convert to the number 0 and 0+0=0.

    G. This outputs 3undefined because the code leads to a string concatentation of '3' and 'undefined'.

    H. This outputs NaN because there was a conversion error. We cannot subtract undefined from a string.

15. A. This outputs true because '2' converts into a number a 2 which is greater than 1.
    
    B. This outputs false because when comparing strings Javascript uses lexicographical order. Lexicographically, '1' is before/less than '2', so the output is false.

    C. This outputs true because '2' converts into 2 and 2==2 is true.

    D. This outputs false because 2 is a number and '2' is a string. Since the === operator is being used and the items are of different types, the code outputs false.

    E. This outputs false because true converts to 1 and 1==2 is false.

    F. This outputs true because true and Boolean(2) are both of the same type (boolean). Also, Boolean(2)=true and true=true is true.

16. The === is a strict equality operator meaning that it checks the equality of two items by first making sure they are of the same type. If they are not of the same type, the operator returns false. On the other hand, the == operator attempts to convert the items being compared before comparing their values.
    
17. The first if statement is false because true converts to 1 and 2==1 is false. The next else if statement is true because Boolean(2) is true. Since the if else statement is true, the code inside the else statement runs and 'How are you?' is printed. The code inside the else statement does not run.  
    
19) The modifyArray() function is called and a new array called newArr is intialized. Then, using a for loop, for every element in the array, the doSomething function is called. Within doSomething(), 2 is added to the element. Then the element+2 is return to modifyArray() and element+2 is multiplied by 2 and that product is pushed into newArr. For example, the first element in array is 1 and 2(1+2)=6 so 6 is added to newArr. This process repeats for every element in the array. Therefore, the result is [6,8,10].  

21. The output of this code is:  
    1  
    4  
    3  
    2  
    This is because the printNums() function prints out 1. Then, the function will print 2 after a delay of 1000 milliseconds. Then, the function will print 3 after a delay of 0 milliseconds. Because setTimeout causes a delay, 4 is the second number printed, 3 is the third number printed, and 2 is fourth number printed.