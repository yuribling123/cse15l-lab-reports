# Week 1 Lab Report
---

## Installing VScode 

- Download and install Java on your computer [Link](https://download.oracle.com/java/17/latest/jdk-17_windows-x64_bin.exe)
- Set JDK Path for your Java
    - Go to System Properties ---> *Environment Vairables*
     - Edit *Path* under *Environment Variables* 
     - Click on **New** and paste the path to bin folder in Java folder on your computer under the *Java Path Folder*
     
    ![Image]( https://i.ibb.co/LJRCgQ6/Screenshot-2023-01-25-181518.jpg)
    
* Download VScode and follow the instruction to install on your computer [Link](https://code.visualstudio.com)
* Install Git  [Link](https://gitforwindows.org/)
    - Inside VScode, open the search bar `ctrl+shift+p`
    - Type **Select Default Terminal Profile** and choose **Git Bash**

_________________


## Remotely Connecting


* Open a new **Git Bash Terminal**
     ![Image](https://i.imgur.com/ykedbfE.jpg) 
* Put in command ```ssh cs15lwi23aha@ieng6.ucsd.edu```
     - Type in password for your account to log in as shown below
     ![Image]( https://i.imgur.com/ktP3PGZ.jpg) 
     
_________________

## Trying Commands

Here is a list of commands you can use: 
```
* cd ~      #Change the current direcotory to given path with short cut  
* cd        #Change the current direcotory to given path  
* ls -lat   #List the folders and files in given path sorted by dates
* ls -a     #Lists all files including those begin with.
* ls <directory> where <directory> is /home/linux/ieng6/cs15lwi23/cs15lwi23abc, where the abc is one of the other group members’ username  #List files and folders of given path 
* cp /home/linux/ieng6/cs15lwi23/public/hello.txt ~/     #Copy Source file to destination file or Directory
* cat /home/linux/ieng6/cs15lwi23/public/hello.txt         #Prints the content of the file for given path 
```  

  
 **Example 1 :** Command `ls -lat` prints out the list of folders and files sorted by dates on **server computer**  
 

        
![Image](https://i.imgur.com/B92zjul.jpg)  


 **Example 2 :** Command `cat <path> ` prints out the content of the file in given path on server computer  
 
 

![Image](https://i.imgur.com/MsZ0c8J.jpg)  


**Example 3 :** **Commands on Local Computer** <br> 
  
 Use bash Command `cp with.txt cat.txt ` to create a new text file named *cat.txt* with the same content as *with.txt* in the same folder on local computer  

![Image](https://i.imgur.com/6u0LQAP.jpg)  




