# Part 1
The bug lay in the fact that the values being put into the input boxes were interpreted as strings instead of numbers. So, that meant that they would be concatenated as strings instead of added like numbers. To fix this, I put `parseFloat` to make sure that the strings were converted to numbers.
# Part 2
1. `citylots.json`
2. `part2.js`
3. 11.7 MB
4. 71 ms
5. Chrome/87.0.4280.141
6. Apache
7. Tue, 26 Jan 2021 22:14:13 GMT
8. application/json
9. `fetchData()` in `part2.js`