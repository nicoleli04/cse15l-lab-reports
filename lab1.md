Lab Report 1
============
This is a tutorial showing how to log into a course-specific account on ieng6


**Installing/Accessing VScode**
---

> Since my computer already had VScode installed from taking CSE8B last quarter, I did not need to install VScode. But you are probably not as fortunate as I am, so I will explain how to install VScode.




> This is if you have downloaded VScode and how you can access VScode from your laptop.

1) Find VScode on your laptop using the search bar
![Image](Screenshot 2023-04-09 181742.png)

2) Open VScode

3) You should end up with something like this (or you know if you were working on a PA from another cs class you probably see VScode with the PA starter code opened):
![Image](Screenshot 2023-04-05 152740.png)




**Remotely Connecting**
---
1) Install Git

> I already have Git installed. But since this is a tutorial for beginners sadly I tell you how to install Git. 

2) Open a terminal on VScode (make sure it uses git bash) and type in `ssh [your usename]@ieng6.ucsd.edu`, your username should be from your course specific account and it should be in the form of cs15lsp23zz. Please make sure you don't put zz in, zz represents your specific letters. For example, my username is cs15lsp23pv.

![Image](Screenshot 2023-04-10 093315.png)

3) You will receive a message like this: 
`⤇ ssh cs15lwi23zz@ieng6.ucsd.edu
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])? `

respond `yes`. 
Don't worry no harm will be done by pressing yes

4) Enter your password 
> note that the terminal will not show you typing anything while you are entering in the password. When I was trying to enter my password in I thought I wasn't typing anything because nothing showed up on the terminal so I had to re-enter my password many times, you can probably see from the next screenshot that has all my failed login requests.

5) You should have something like this:

![Image](Screenshot 2023-04-05 153535.png)


Congratulations! Your terminal is now connected to a computer in the CSE basement!


**Trying Some Commands**
---
1) Try running some of these commands on the terminal
> `cd ~`
`cd`
`ls -lat`
`ls -a`
`ls /home/linux/ieng6/cs15lsp23/cs15lsp23zz`
`cp /home/linux/ieng6/cs15lsp23/public/hello.txt ~/`
`cat /home/linux/ieng6/cs15lsp23/public/hello.txt`

2) Here are some commands that I tried out

![Image](Screenshot 2023-04-09 184307.png)


3) Think about what the commands do. This is the perfect time to review what you learned from the lectures. This was really helpful for me because I realized that I actually didn't remember what any of the commands do. But now I do! And I will explain some of these commands to you.

![Image](Screenshot 2023-04-05 155024.png)

I tried to print the the contents of the file hello.txt. It printed No such file or directory because the file hello.txt does not exist.


YAY! You have reached the end of this tutorial! Congratulations on getting through the first lab in CSE15L. You are one step closer to achieving your goals :)
