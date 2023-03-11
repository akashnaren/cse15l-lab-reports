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
Now before I get into the steps and the main components I need for this lab report, I would like to first display the steps that were used.

The Steps Are:
1. Setup Delete any existing forks of the repository you have on your account
2. Setup Fork the repository
3. The real deal Start the timer!
4. Log into ieng6
5. Clone your fork of the repository from your Github account
6. Run the tests, demonstrating that they fail
7. Edit the code file to fix the failing test
8. Run the tests, demonstrating that they now succeed
9. Commit and push the resulting change to your Github account (you can pick any commit message!)

Before I get into the steps, I want to state that I deleted any existing forks of the repository I have on my account. Here are some images in order to display this process. The main gist is that once you enter a repository on Github Website, you travel to the settings of the repository and stay on General and scroll down to see this delete option.:


![Image](lab4(1).png)



Following this action, I went ahead and removed lab7 from the repository. So I went ahead and started working on lab7's new fork, which will be covered in following lab components.


![Image](lab4(2).png)


---
**Step 4: Log into ieng6**

I used the keyboard shortcut "Ctrl+R" to open the command prompt when logging into ieng6. Now I want to be clear that after entering the initial ssh command, I created an SSH Key for ieng6 that allowed me to skip typing the password.


![Image](lab4(3).png)


Keys Used: `ssh<enter>`

The displayed output shows that a user going by the name of cs15lwi23ahg successfully established an SSH connection to the remote server ieng6.ucsd.edu. In order to avoid the password prompt, I made sure to produce SSH Keys for Github as well. With the use of an SSH link in addition to the regular url, I was able to make sure that I could eventually clone.

---
**Step 5: Clone your fork of the repository from your Github account**

To open the prompt line and type the command name, I used the keyboard shortcut "Ctrl+R". All of this took place on the remote computer.

The command that we need for this step would be `Git clone <ssh link>`. In this case, the ssh link is `git@github.com:invisiblecuteman/lab7.git` so the overall command would be `Git clone git@github.com:invisiblecuteman/lab7.git`.

Here is a screenshot:
![Image](lab4(4).png)

The keys I used are: `git<space>cl<enter>`

Here is a screenshot of the process:


![Image](lab4(5).png)

---
**Step 6: Run the tests, demonstrating that they fail**

Now for this step, I want to compile which is `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` then `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore` to run the code. 

To show this in a numbered form, my steps were:
1. Pressed `Ctrl+R` again to get the prompt to write the name of the command on the remote computer
2. Keys Used: `javac<enter>`
3. Compiling of program
4. `Ctrl+R` again
5. Keys Used: `java<space><enter>`
6. Run tests
 
Here is a screenshot of step(3),(6):


![Image](lab4(6).png)


![Image](lab4(7).png)


![Image](lab4(8).png)


 ---
**Step 7: Edit the code file to fix the failing test**

Keys Used: `nan<tab>L<tab>.j<tab>`

Within nano editor, the next step taken was utilized with = 
Keys Used: `nan<tab>L<tab>.j<tab>`

Here is a screenshot of this step:


![Image](lab4(9).png)



Once I was able to enter the nano editor, I had to press "Ctrl+V" to move to the next screen, then "Ctrl + W" and "return" to exit. After having read all of this up to this point, I moved up 2 arrowkeys up and 7 arrowkeys right. I then selected "delete" and entered the number 2 into the code. I used "Ctrl+O" - "enter" - "Ctrl + x" to ensure that I saved and closed the nano.

 ---
**Step 8: Run the tests, demonstrating that they now succeed**
Now for this step, since we have been able to make sure that the code is fixed we have to re run the tests on the fixed code. The result that we should hopefully see is `OK (2 tests)`

Keys Used = `<up><up><enter>` for compiling and then `<up><up><up><enter>` to run the code. This meant that I had to go 2 Arrowkeys up and then 3 arrowkeys up to the run the code. 

Here is a screenshot of this step:


![Image](lab4(10).png)



 ---
**Step 9: Commit and push the resulting change to your Github account (you can pick any commit message!)**

This is the last step, and we should now update our github account with the changes we've made. This ensures that when the code is saved to the file, it is fully updated and that no data is lost.

To accomplish this action, I pressed the keys "git" and "space" and "add" and "space" and "L". Thanks to tab>enter>', I was able to modify the local repository. In addition, as I've already mentioned, I wanted to be sure that no data was lost or saved improperly.


To make sure, I used `git<space>status<enter>`

Here is a screenshot of this step:


![Image](lab4(11).png)

Because color matters, green in this example denotes that the file has been updated. In this instance, the modification to "ListExample.java" was successful.`<Ctrlr>git<space>co<enter>`

Last but not least, I want to confirm that the changes have been saved. The keys I used are `<Ctrlr>git<space>co<enter>`



![Image](lab4(12).png)


![Image](lab4(13).png)



I then wish to push my edits, and to do this, I pressed the keys `<Ctrlr>git<space>p<enter>`.

With each key used, git was able to publish updates to the repository connected to my github account.



![Image](lab4(14).png)


![Image](lab4(15).png)



---


I hope this was a interesting report that discusses the aspect of using bash to speed up the process of all the lab tasks while also increasing the use of keyboard commands to speed up processes. 
