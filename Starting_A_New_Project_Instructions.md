# Read Me File to start a program (This shows up bold):
	Example: Fun_With_Functions_Project

1. Start Eclipse
2. Change the workspace to our flash drive
	:File>Switch Workspace 
3. Start a new project: Fun_With_Functions_Project
	: File> New > Project
		: Use default runtime environment,
			then click finish
4. Add a new class with our new
	project selected: Fun_With_Functions
	: File > New > Class
		: Name it, select the public static 
				void main option an and Finish.

Now begin Git and Git Hub
1. Open the command prompt.
	:Start > search for cmd> Hit Enter.

2. Go to your project folder
	:E to change to flashdrive 
	: dir to list the director
	:E:\>cd Workspace to change to the correct workspace.
	:E:\Workspace>cd Fun_With_Functions_Project
	:E:\Workspace\Fun_With_Functions_Project
		you should be able to see the src and bin folders.

:E:\Workspace\Fun_With_Functions_Project>dir
 Volume in drive E is STORE N GO
 Volume Serial Number is 0012-D687

 Directory of E:\Workspace\Fun_With_Functions_Project

10/26/2015  09:11 AM    <DIR>          .
10/26/2015  09:11 AM    <DIR>          ..
10/26/2015  09:11 AM               402 .project
10/26/2015  09:11 AM    <DIR>          src
10/26/2015  09:11 AM    <DIR>          bin
10/26/2015  09:11 AM               232 .classpath
               2 File(s)            634 bytes
               4 Dir(s)   3,622,264,832 bytes free

3. git init to begin a new local repository.
:E:\Workspace\Fun_With_Functions_Project>git init
Initialized empty Git repository in E:/Workspace/Fun_With_Functions_Project/.git
/

4. git add . to add my materials
E:\Workspace\Fun_With_Functions_Project>git add .

5. git config our user name and email
E:\Workspace\Fun_With_Functions_Project>git config user.name "kylielent"

E:\Workspace\Fun_With_Functions_Project>git config user.email "lentk@student.swo
su."


6. Start a browser of choice
7. Go to Github: https://github.com/
8. Log into your personal account: https://github.com/login
9. Add a new repository
	: Name it, and make it public, but do not initliaze our folder with a read me file. 
		That initilization makes your life harder. 
	: Press "Create Repository"
10. Follow the online instructions on how to 
	..or push an existing repository  from the command line

:git remote add origin https://github.com/kylielent/Fun_With_Functions.git
:git push -u origin master

So go back to the command prompt, and then do the first line, after pressing enter
	do the second.

// Below is the first line. IT works without problem
:E:\Workspace\Fun_With_Functions_Project>git remote add origin https://github.com
/kylielent/Fun_With_Functions.git

//Below is the second line. Now that it had problems. 
E:\Workspace\Fun_With_Functions_Project>git push -u origin master
error: src refspec master does not match any.
error: failed to push some refs to 'https://github.com/kylielent/Fun_With_Functi
ons.git'

//But i wanted to test how unhappy this was, so i tried to keep moving.
E:\Workspace\Fun_With_Functions_Project>git add .

//So i just stayed after it, note that add and commit did not complain.
//These are 
E:\Workspace\Fun_With_Functions_Project>git commit -m "First commit"
[master (root-commit) 867a713] First commit
 5 files changed, 92 insertions(+)
 create mode 100644 .classpath
 create mode 100644 .project
 create mode 100644 Starting_A_New_Project_Instructions.md
 create mode 100644 bin/Fun_With_Functions.class
 create mode 100644 src/Fun_With_Functions.java

E:\Workspace\Fun_With_Functions_Project>git push
warning: push.default is unset; its implicit value has changed in
Git 2.0 from 'matching' to 'simple'. To squelch this message
and maintain the traditional behavior, use:

  git config --global push.default matching

To squelch this message and adopt the new behavior now, use:

  git config --global push.default simple

When push.default is set to 'matching', git will push local branches
to the remote branches that already exist with the same name.

Since Git 2.0, Git defaults to the more conservative 'simple'
behavior, which only pushes the current branch to the corresponding
remote branch that 'git pull' uses to update the current branch.

See 'git help config' and search for 'push.default' for further information.
(the 'simple' mode was introduced in Git 1.7.11. Use the similar mode
'current' instead of 'simple' if you sometimes use older versions of Git)

fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master


//Now we try the new command
E:\Workspace\Fun_With_Functions_Project> git push --set-upstream origin master
Username for 'https://github.com': kylielent
Password for 'https://kylielent@github.com':
Counting objects: 9, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (9/9), done.
Writing objects: 100% (9/9), 1.93 KiB | 0 bytes/s, done.
Total 9 (delta 0), reused 0 (delta 0)
To https://github.com/kylielent/Fun_With_Functions.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.

//all is well
E:\Workspace\Fun_With_Functions_Project>







































