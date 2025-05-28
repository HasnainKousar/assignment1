                     Cheatsheet for Linux and Git commands  
1. ls : ls is a linux command used to list files and directories.  
Ex: username:~/assignment1$ ls  
This will list all the files and directories in "assignment1" directory  

2. cd : cd is a linux command used to change directories.  
Ex: username:~/assignments$ cd assignment1  
This will change the current directory to assignment1  

3. pdw : a linux command to print out the current working directory.  
Ex: username:~/assignment1$ pdw  
This will show the current working  directory along with it's pathway: /home/username/assignment1  

4. mkdir : a linux command to create a new directory.  
Ex:  username:~/assignments$ mkdir assignment1  
This will create a new directory called "assignment1" in the assignments directory  

5. touch : a linux command to create an empty file in the current directory.  
Ex:  username:~/assignment1$ touch readme.md  
This will create a new file "readme.md" in the assignment1 directory  

6. rm : a linux command to remove files and directories.  
Ex:  username:~/assignment1$ rm readme.md  
This will remove the readme.md file from the assignment1 directory  

7. mv : linux command to move/rename files and directories.  
Ex:   username:~/assignment1$ mv readme.md file.txt  
This will rename the readme.md file to the new name 'file.txt'  

8. cat : a linux command used to view the content of a file.  
Ex:  username:~/assignment1$ cat readme.md  
This will show the content of the readme.md file  

9. git init : a git command to initialize the current directory as a Git repository.  
Ex: username:~/assignment1$ git init  
This will initialize assignment1 as a Git repository  

10. git clone : a git command to clone/retrieve an entire repo from a hosted location such as Github.  
Ex. username:~$ git clone url  
This will clone the entire repo from the hosted location given by the url  

11. git checkout -b "name" : a git command to create a new branch and switch to it.  
Ex: username:~/assignment1$ git checkout -b branch1  
This will create a new branch called branch1 and switch to it  

12. git remote add origin < url > : a git command to allow you to connect your local repo to a remote repo hosted on a platform such as Github.  
Ex. username:~/assignment1$ git remote add origin < url >  
This will connect your local repo to a remote repo  

13. git push : a git command to push/upload the content from your local repo to the remote repo.  
Ex: username:~/assignment1$ git push origin main  
This will push changes from your main branch on local repo to the main branch on remote repo  

14. git add : git command to add a file in it's current status to the next commit.  
Ex: username:~/assignment1$ git add readme.md  
This will add the readme.md file in it's current form with all the changes to the next commit 
