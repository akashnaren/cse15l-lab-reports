# CSE 15L Lab Report  
*Akash Premkumar*
*PID: A16822598*
---
## Lab Report 4: Utilizing Terminal Controls
---
Objective: Discuss about Github, speeding up work using keyboard with terminal, and ssh. Overall make command line operations efficient. 
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

**Steps 4-9 are important and of focus for the lab.** 

Before I get into the steps, I want to state that I deleted any existing forks of the repository I have on my account. Here are some images in order to display this process. The main gist is that once you enter a repository on Github Website, you travel to the settings of the repository and stay on General and scroll down to see this delete option.:

![Image](lab4(1).png)

After this step I went ahead and deleted lab7 specifically on the repository. So then I went ahead and created a new fork for lab7 which will be discussed in later components of the lab. 

![Image](lab4(2).png)

---
**Step 4: Log into ieng6**

For logging into ieng6, I pressed `Ctrl+R` to get the prompt to write the name of the command. Now I want to disclose that I generated a SSH Key for ieng6 which allowed me to bypass the password typing after I put the intial ssh command. 

![Image](lab4(3).png)

Keys Used: `ssh<enter>`

The provided output represents a successful SSH connection made by a user named cs15lwi23ahg to the remote server ieng6.ucsd.edu. I also went ahead and made sure that I generated SSH Keys for Github which bypasses the password prompt. I was able to ensure that I could finally clone using a SSH link alongside the standard url.

---
**Step 5: Clone your fork of the repository from your Github account**

I used `Ctrl+R` to get the prompt line to write the name of the command. This all occured while on the remote computer. 

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
Keys Used: `<Ctrlv><Ctrlw>return<enter><up><up><right><right><right><right><right><right>
<right><delete>2<Ctrlo><enter>`

Here is a screenshot of this step:


![Image](lab4(9).png)



Once I was able to access the editor in nano, I then had to use `Ctrl+V` which allowed me to access the next screen then I used `Ctrl + W` then `return`. Now after all this so far, I went ahead up 2 arrowkeys up + 7 arrowkeys right. I then pressed `delete` and inputted 2 as part of the code. Now to make sure that I save and exit the nano, I used `Ctrl+O` - `enter` - `Ctrl + x`. 

 ---
**Step 8: Run the tests, demonstrating that they now succeed**
Now for this step, since we have been able to make sure that the code is fixed we have to re run the tests on the fixed code. The result that we should hopefully see is `OK (2 tests)`

Keys Used = `<up><up><enter>` for compiling and then `<up><up><up><enter>` to run the code. This meant that I had to go 2 Arrowkeys up and then 3 arrowkeys up to the run the code. 

Here is a screenshot of this step:


![Image](lab4(10).png)



 ---
**Step 9: Commit and push the resulting change to your Github account (you can pick any commit message!)**

Now has the come the final step where we will want to commit the changes we have to our github account. This ensures that our code is fully updated and there is no loss of information when saving the code on the file. 

To satisfy this step, the keys that I pressed are `git<space>add<space>L<tab>.j<tab><enter>` which allowed me to have changes to the local repository. I also wanted to make sure as I mentioned before that there was no loss of failure of saving information. 

To make sure, I used `git<space>status<enter>`

Here is a screenshot of this step:


![Image](lab4(11).png)



Color is important and in this case green indicates that the file has been modified. In this case, `ListExample.java` has been successfully modified. 

I lastly want to make sure that the changes have been commited and the keys I used are `<Ctrlr>git<space>co<enter>`



![Image](lab4(12).png)


![Image](lab4(13).png)



I then also want to push my edits and in order to this, the keys that I used are `<Ctrlr>git<space>p<enter>`.

All of the keys used have alowed git to push changes to the repository linked to my github account. 



![Image](lab4(14).png)


![Image](lab4(15).png)



---

This is the end of the lab. 

I hope this was a infiormative lab report that discusses why it is important that command line operations improve the efficiency and speed at which tasks can be completed in relation to github and within the terminal. 
