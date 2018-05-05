# FrontEndFromZeroToHero - Week 1

## The first test

2. The correct answear is c) because the To-Do Lists must be descriptive and as specific as possible. 
Of course, your schedule changes sometimes and then you can update these lists.

3. The correct answear is b) After two hours of studying it is recommended to take a break for 10 - 20 minutes.

4.  In this exercise exists some code witch is duplicate. When your code is growing in length, it is recomanded to eliminate duplicates and to organise your lines of code in functions or blocks.
Below, you can see an improvement for myCompany();
```javascript
 function getSalary(salary, hoursOfWork) {
    return (salary + 100)/hoursOfWork;
 }
 
 function myCompany() {
    let hoursOfWork = 30;
    let totalMoney = 2000;
    let firstEmployee;
    let secondEmployee;
    
    //calculate salary for each employee
    firstEmployee = getSalary(totalMoney, houseOfWork);
    secondEmployee = getSalary(totalMoney, houseOfWork);
}
```
