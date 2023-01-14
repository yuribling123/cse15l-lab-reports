# Week 1 Lab Report
---
## Installing VScode 
* Download Java [Link](https://download.oracle.com/java/17/latest/jdk-17_windows-x64_bin.exe)
* Set JDK Path
     1) Go to System Properties---*Environment Vairables*
     2) Edit *Path* under *Environment Variables* 
     3) Click on **New** and paste the path to bin folder under Java folder on your computer under the *Java Path Folder*
     
    ![Image](https://i.imgur.com/eLxSK3r.jpeg) 
    
* Download VScode and follow its instruction to install on the computer [Link](https://code.visualstudio.com)
---
## Remotely Connecting
* Install Git  [Link](https://gitforwindows.org/)
* Inside VScode, open the search bar (*ctrl+shift+p*)
     1) **Select Default Terminal Profile** and choose **Git Bash**
     2) Open a new Git Bash Terminal
     ![Image](https://i.imgur.com/ykedbfE.jpg) 
     3) Put in command ```ssh cs15lwi23aha@ieng6.ucsd.edu```
     4) Type in password for your account and successfully log in as shown below
     ![Image]( https://i.imgur.com/ktP3PGZ.jpg) 
---
## Trying Commands
Here is a list of commands you can use: 
```
* cd ~      #Change the current direcotory to given path with short cut  
* cd        #Change the current direcotory to given path  
* ls -lat   #List the folders and files in given path sorted by dates
* ls -a     #Lists all files including those begin with.
* ls <directory> where <directory> is /home/linux/ieng6/cs15lwi23/cs15lwi23abc, where the abc is one of the other group members’ username  #List files and folders of given path 
* cp /home/linux/ieng6/cs15lwi23/public/hello.txt ~/    #Copy Source file to destination file or Directory
* cat /home/linux/ieng6/cs15lwi23/public/hello.txt         #Prints the content of the file for given path
``` 
* Command: `ls -lat` 
        1)  **Note:** Prints out the list of sorted by dates in current path
![Image](https://i.imgur.com/B92zjul.jpg) 

