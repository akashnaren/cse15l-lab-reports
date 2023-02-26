# CSE 15L Lab Report  
*Akash Premkumar*
*PID: A16822598*
---
## Lab Report 4: Utilizing Terminal Controls
---
Objective: Discuss about github, speeding up work using keyboard with terminal, and ssh. 
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

**Step 4: Log into ieng6**

For logging into ieng6, I had to manually type in `ssh cs15lwi23ahg@ieng6.ucsd.edu`. Now I want to disclose that I 
generated a SSH Key for ieng6 which allowed me to bypass the password typing after I put the intial ssh command. 

![Image](http://url/a.png)

The provided output represents a successful SSH connection made by a user named cs15lwi23ahg to the remote server ieng6.ucsd.edu. This command had also auto `enter`. I also went ahead and made sure that I generated SSH Keys for Github. After doing all these prerequisite steps, I was able to ensure that I could finally clone using a SSH link alongside the standard url. I believe for this step since we are mainly recreating how it would be in the competition setting. 

---
**Step 5: Clone your fork of the repository from your Github account**

Now, before this step I did have an existing repository of lab7 that I went ahead and deleted. I recommend that anyone who does this lab to make sure to go into Github and ensure that there is no existence before continuing on past Step 5.

The command that we need for this step would be `Git clone <ssh link>`. In this case, the ssh link is `git@github.com:invisiblecuteman/lab7.git` so the overall command typed manually would be `Git clone git@github.com:invisiblecuteman/lab7.git`. I had to also type this in manually. The way I did it was type in `Git clone` and then at the end used `Command-C` and then `Command-V` to add `git@github.com:invisiblecuteman/lab7.git`. I then 
`enter`.

Here is a screenshot:
![Image](http://url/a.png)

---
**Step 6: Run the tests, demonstrating that they fail**

Now for this step, I had to first change my directory into lab 7. To do this I manually typed `cd l...` and then hit `tab` which autofilled it to ` cd lab7`. To do so I went ahead and copied the entire command via a double click and dragging across the content I wanted to select from the lab write-up which is `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` then using the command `Command-C`. Once I was within the terminal,  I used `Command-V`. After that I went ahead and hit `enter`. I repeated this process with `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore`. So I first would double click and then drag across the content that I would want and used `Command-C`. Once I was within the terminal,  I used `Command-V`. Then I hit `enter` where it then went to a new line. 

Here is a screenshot of this step:
![Image](http://url/a.png)
 

