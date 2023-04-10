Lab Report 1
============
This is a tutorial showing how to log into a course-specific account on ieng6
-----

**Installing/Accessing VScode**
---

> Since my computer already had VScode installed from taking CSE8B last quarter, I did not need to install VScode.

1. Find VScode on your laptop using the search bar
![Image](Screenshot 2023-04-09 181742.png)

2. Open VScode

3. You should end up with something like this:
![Image](Screenshot 2023-04-05 152740.png)




**Remotely Connecting**
---
1. Install Git

> I already have Git installed. 

2. Open a terminal on VScode (make sure it uses git bash) and type in `ssh [your usename]@ieng6.ucsd.edu`, your username should be from your course specific account and it should be in the form of cs15lsp23zz.

![Image](Screenshot 2023-04-05 152740.png)

3. You will receive a message like this: 
⤇ ssh cs15lwi23zz@ieng6.ucsd.edu
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])? 

respond `yes`.

3. Enter your password 
> note that the terminal will not show you typing anything while you are entering in the password.

4. You should have something like this:

![Image](Screenshot 2023-04-05 153535.png)


Congratulations! Your terminal is now connected to a computer in the CSE basement!


**Trying Some Commands**
---
1. Try running some of these commands on the terminal
> cd ~
cd
ls -lat
ls -a
ls /home/linux/ieng6/cs15lsp23/cs15lsp23zz
cp /home/linux/ieng6/cs15lsp23/public/hello.txt ~/
cat /home/linux/ieng6/cs15lsp23/public/hello.txt

2. Here are some commands that I tried out

![Image](Screenshot 2023-04-05 152740.png)
