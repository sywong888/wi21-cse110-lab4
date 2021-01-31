**DevTools - Debugging**  
What was the bug? The variable result is of the wrong type. Result is a string that concatenates the value of num1 with the value of num2 (rather than adding the numbers). Instead, result needs to be a number.  

How would you fix it? I would fix the bug by converting num1 and num2 into a number (rather than a string) using Number(). This fix causes the variable result to now be of type number. I added a screenshot of my change to calculateSum() in the part3 directory.

**DevTools - Network Tab**  
1. citylots.json
2. part2.js  
3. 11.7 MB
4. 191 ms
5. Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/88.0.4324.96 Safari/537.36
6. Apache
7. Tue, 26 Jan 2021 22:14:13 GMT
8. application/json
9. fetchData