# CSE 15L Lab Report  
*Akash Premkumar*
*PID: A16822598*
---
## Lab Report 5: Doing a task differently
---
Objective: how could you have done the task very quickly by writing a bash script (even if that was against the rules)
---
During lab week 7, this was one of my favorite lab weeks. I found it to be very fun when it came to the competition aspect of the lab. When I tried to complete the task of demonstrating that the tests failed - Run the tests, demonstrating that they fail - and other steps, it took me a while to just complete the baseline tasks. I then had come to the portion where we had to compete within our group to see who the fastest person was at completing the tasks. I didn't do well at all but I was happy for Ruben to compete for the team. The compeition aspect came mext where Ruben was competing against others. One person was able to finish within 25 seconds or something and we realized it was the bash script process that allowed them to win. 

In this lab report, I will be discussing the process that I took differently in re-doing this aspect of the lab via the bash script. When I didn't use a bash script during the lab hours, the exact same task took longer in the 5-10min range. 

---
**Step 1: Log into ieng6**

I used the keyboard shortcut "Ctrl+R" to open the command prompt when logging into ieng6. Now I want to be clear that after entering the initial ssh command, I created an SSH Key for ieng6 that allowed me to skip typing the password.


![Image](lab4(3).png)


The displayed output shows that a user going by the name of cs15lwi23ahg successfully established an SSH connection to the remote server ieng6.ucsd.edu. In order to avoid the password prompt, I made sure to produce SSH Keys for Github as well. With the use of an SSH link in addition to the regular url, I was able to make sure that I could eventually clone.

---

**Step 2: Utilize nano to process and run bash script. Run the tests, demonstrating that they fail**

Now for this step, I want to compile which is `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` then `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore` to run the code. 

Here is a screenshot:


![Image](lab5(1).png)


![Image](lab4(8).png)


 ---
**Step 3: Edit the code file to fix the failing test**

Within nano editor, I went ahead and inputted nano lab7/ListExamples.java that allows me to now go and fix the code. 

Here is a screenshot of this step:


![Image](lab4(9).png)



Once I was able to enter the nano editor, I had to press "Ctrl+V" to move to the next screen, then "Ctrl + W" and "return" to exit. After having read all of this up to this point, I moved up 2 arrowkeys up and 7 arrowkeys right. I then selected "delete" and entered the number 2 into the code. I used "Ctrl+O" - "enter" - "Ctrl + x" to ensure that I saved and closed the nano.

 ---
**Step 4: Run the tests, demonstrating that they now succeed via bash script**


Now for this step, since we have been able to make sure that the code is fixed we have to re run the tests on the fixed code. The result that we should hopefully see is `OK (2 tests)`

The goal here is to make sure that another bash script is created. 

Here is a screenshot of this step:

![Image](lab5(2).png)

![Image](lab4(10).png)


 ---
**Step 5: Commit and push the resulting change to your Github account (you can pick any commit message!)**

This is the last step, and we should now update our github account with the changes we've made. This ensures that when the code is saved to the file, it is fully updated and that no data is lost.


Here is a screenshot of this step:


![Image](lab4(11).png)


![Image](lab5(3).png)


---


I hope this was a interesting report that discusses the aspect of using bash to speed up the process of all the lab tasks while also increasing the use of keyboard commands to speed up processes. 
