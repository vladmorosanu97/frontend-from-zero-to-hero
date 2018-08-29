# FrontEndFromZeroToHero - Week 1

## The first test

1. Next, you will use github to post your answers for this quiz. The steps are simple:

    * You need to create a workspace on your account. This is a link: **https://github.com/new**.
    
    * Open your folder in your computer where you are working for this project. This folder should be called "Front-End" or something like that. Remember, one folder for one dream! ;)
    
    * Now, right click, open git bash and type `` git init `` . This comand means that you will create a local workspace in your computer. 
    
    * You need to create a connection between your local workspace and github.
    
    Type `` git remote add origin https://github.com/yourAccount/yourRepositoryName.git `` and you'll replace ``yourAccount`` and `` yourReporitoryName`` with your credentials.
    
    * There will be 8 weeks and to mantain all things clean, we'll create one folder for each week. Below, you can create a new folder by typing ``mkdir week-1`` (you can you can put any name) and ``cd week-1``. 
    
    * Now, you can create manually a new file text or any other type or you can create a file using this terminal typing ``cd. > fileName``. In this file you must write your answers. 

2. The best way to be productive and accomplish everything you set out to do is to create your own **To-Do Lists**. What kind of spin do you think is the most correct?  
    
    * a)
        * 10:20 AM: Clean the house.
        * 3:40 PM: Go out.
        * 11:30 PM: Go to bed.
        
    * b) 
        * Clean the desk and make the bed.
        * Walk the dog and go to the market.
        * Make a to-do list for next day and go to bed early.
        
    * c)
        * 10:00 AM: Clean the desk and make the bed.
        * 3:40 PM: Walk the dog and go to the market.
        * 11:30 PM: Make a to-do list for next day and go to bed early.
   
3. After a few hours of studying it is recommended to take a break for 10 - 20 minutes. After how much time do you think you should take the break?
    * a) after 30 minutes;
    * b) after 2 hours;
    * c) after 6 hours.
    
4. What is wrong with the code below? Can you improve it? If you don't have any knowledge about basic JavaScript, don't worry! You will learn more about this language soon. This exercise is optional. 
 
    ```javascript
    function myCompany() {
       let hoursOfWork = 30;
       let totalMoney = 2000;
       let firstEmployee;
       let secondEmployee;

       //calculate salary for each employee
       firstEmployee = (totalMoney + 100)/hoursOfWork;
       secondEmployee = (totalMoney + 100)/hoursOfWork;
   }
   ```
5. Naming conventions is very important for writing a clean code because the other programmers will not spend too much time trying to understand what were you thinking. In this exercise, you need to improve the code in such a way that other people can read it more easily. Hint: try understanding first what does this code do. 
   ```javascript
           for(i=0;i<10;i++) {
       d = d +i;
     }
   ```    

6. There is only one more step. To synchronise your local data in your online repository you need to do the following: 

    * ``cd ..`` to be in the main folder where you created the local repository
    * ``git add *`` to add files in new commit
    * ``git commit -m "Your optional comment about this commit"`` . This command will create a new local commit with your files.
    * ``git push origin master`` for upload you local commit on github.
       
    If you want to learn more about github and git, there is a useful article about this powerful technology: 
    * [Learn the workings of Git, not just the commands](https://www.ibm.com/developerworks/library/d-learn-workings-git)
