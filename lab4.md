# CSE 15L Lab Report  
*Akash Premkumar*
*PID: A16822598*
---
## Lab Report 4: Utilizing Terminal Controls
---
Objective: Discuss about github, speeding up work using keyboard with terminal, and ssh. Overall make command line operations efficient. 
---
Now before I get into the steps and the main components I need for this lab report, I would like to first display the steps that 
were used and the ones of focus. 

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

Steps 4-9 are important and of focus for the lab. 

Now I will list each steps as parts just for the sake of logical flow. 

---
Before I get into the steps, I want to state that I deleted any existing forks of the repository I have on my account.
After this step I went ahead and deleted lab7 specifically on the repository. So then I went ahead and created a new fork for lab7. 

**Step 4: Log into ieng6**

For logging into ieng6, I pressed `Ctrl+R` to get the prompt to write the name of the command. Now I want to disclose that I generated a SSH Key for ieng6 which allowed me to bypass the password typing after I put the intial ssh command. 

![Image](http://url/a.png)

The provided output represents a successful SSH connection made by a user named cs15lwi23ahg to the remote server ieng6.ucsd.edu. This command had also auto `enter`. I also went ahead and made sure that I generated SSH Keys for Github. After doing all these prerequisite steps, I was able to ensure that I could finally clone using a SSH link alongside the standard url. I believe for this step since we are mainly recreating how it would be in the competition setting. 

---
**Step 5: Clone your fork of the repository from your Github account**

I used `Ctrl+R` to get the prompt line to write the name of the command. This all occured while on the remote computer. 

Here is a screenshot:
![Image](http://url/a.png)

The keys I used are: `git<space>cl<enter>`

The command that we need for this step would be `Git clone <ssh link>`. In this case, the ssh link is `git@github.com:invisiblecuteman/lab7.git` so the overall command would be `Git clone git@github.com:invisiblecuteman/lab7.git`.

Here is a screenshot:
![Image](http://url/a.png)

---
**Step 6: Run the tests, demonstrating that they fail**

Now for this step, I had to first change my directory into lab 7. To do this I manually typed `cd l...` and then hit `tab` which autofilled it to ` cd lab7`. To do so I went ahead and copied the entire command via a double click and dragging across the content I wanted to select from the lab write-up which is `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` then using the command `Command-C`. Once I was within the terminal,  I used `Command-V`. After that I went ahead and hit `enter`. I repeated this process with `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore`. So I first would double click and then drag across the content that I would want and used `Command-C`. Once I was within the terminal,  I used `Command-V`. Then I hit `enter` where it then went to a new line. 

To show this in a bulleted form, my steps were:
1. Pressed `Ctrl+R` again to get the prompt to write the name of the command on the remote computer
2. KeyPressed `javac<enter>`
3. Compiling of program
4. `Ctrl+R` again
5. KeyPressed `java<space><enter>`
6. Running tests
 
Here is a screenshot of this step:
![Image](http://url/a.png)
 ---
**Step 7: Edit the code file to fix the failing test**

Keys Used: `nan<tab>L<tab>.j<tab>`
After entering the nano editor
KeyPressed: `<Ctrlv><Ctrlw>return<enter><up><up><right><right><right><right><right><right>
<right><delete>2<Ctrlo><enter>`

Here is a screenshot of this step:
![Image](http://url/a.png)

Once I was able to access the editor in nano, I then had to use `Ctrl+R` which allowed me to access the next screen then I used `Ctrl + W` then `return`. Now after all this so far, I went ahead up 2 arrowkeys up + 7 arrowkeys right. I then pressed `delete` and entered 2. Now to make sure that I save and exit the nano, I used `Ctrl+O` - `enter` - `Ctrl + x`. 

 ---
**Step 8: Run the tests, demonstrating that they now succeed**
Now for this step, since we have been able to make sure that the code is fixed we have to re run the tests on the fixed code. The result that we should hopefully see is `OK (2 tests)`

Keys Used = `<up><up><enter>` for compiling and then `<up><up><up><enter>` to run the code. This meant that I had to go 2 Arrowkeys up and then 3 arrowkeys up to the run the code. 

Here is a screenshot of this step:
![Image](http://url/a.png)



 ---
**Step 9: Commit and push the resulting change to your Github account (you can pick any commit message!)**

Now has the come the final step where we will want to commit the changes we have to our github account. This ensures that our code is fully updated and there is no loss of information when saving the code on the file. 

To satisfy this step, the keys that I pressed are `git<space>add<space>L<tab>.j<tab><enter>` which allowed me to have changes to the local repository. I also wanted to make sure as I mentioned before that there was no loss of failure of saving information. 

To make sure, I used `git<space>status<enter>`

Here is a screenshot of this step:
![Image](http://url/a.png)

Color is important and in this case green indicates that the file has been modified. In this case, `ListExample.java` has been successfully modified. 

I lastly want to make sure that the changes have been commited and the keys I used are `<Ctrlr>git<space>co<enter>`

![Image](http://url/a.png)
![Image](http://url/a.png)

I then also want to push my edits and in order to this, the keys that I used are `<Ctrlr>git<space>p<enter>`.

All of the keys used have alowed git to push changes to the repository linked to my github account. 

![Image](http://url/a.png)
![Image](http://url/a.png)

---

This is the end of the lab. 

I hope this was a infiormative labv report that discusses why it is important that command line operations improve the efficiency and speed at which tasks can be completed in relation to github and within the terminal. 
