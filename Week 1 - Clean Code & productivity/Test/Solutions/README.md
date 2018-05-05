# FrontEndFromZeroToHero - Week 1

## The first test

2. The correct answer is c) because the To-Do Lists must be descriptive and as specific as possible. 
Of course, your schedule might change from time to time, so there’s no problem in updating them.

3. The correct answer is b) After two hours of studying it is recommended to take a break for 10 - 20 minutes.

4.  In this exercise you can see that some part of the code is duplicated. When your code is growing in length, it is recommanded to eliminate duplicates and to organise your lines of code in functions or blocks.
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

5. This exercise can be solved in multiple ways. Below, you can see one example of a solution:

```javascript
  let sum = 0; // 
  for(index = 0; index < 10; index++) {
    sum += index; // this variable calculates the sum of the first ten numbers and it’s a good idea to rename it “sum” 
  }
``` 
