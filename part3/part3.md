### DevTools - Debugging

What was the bug?

The bug was that num1 and num2 were both strings, so result was being evaluated as a string rather than a number. 

How would you fix it?

To fix it, I changed the initalization of *result* in calculateSum() to be
```let result = parseInt(num1) + parseInt(num2)``` 

### DevTools - Network Tab

1. citylots.json
2. part2.js
3. 11.7 MB
4. 1.50 s
5. Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/88.0.4324.104 Safari/537.36
6. !!!
7. Tue, 26 Jan 2021 22:14:13 GMT
8. application/json
9. fetchData
