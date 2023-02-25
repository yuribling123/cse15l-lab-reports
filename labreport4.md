# Lab Report 4

* **STEP 1: Setup Delete any existing forks of the repository you have on your account**  
  * We use this command to delete the whole directoy: `rm -r /home/linux/ieng6/cs15lwi23/cs15lwi23aha/lab7`
  * The console will ask for permission to delete files, enter Y for all of them.
    <img width="898" alt="image" src="https://user-images.githubusercontent.com/122572429/221313582-c7c17607-8795-45b9-ab2c-89d6ceae916d.png"> 
---   
* **STEP 2: Setup Fork the repository** 
  * On the Git Hub page for this repository, click "Fork" and "Create Fork" to fork your own copy of repository. 
    <img width="158" alt="image" src="https://user-images.githubusercontent.com/122572429/221315762-2ca50220-3f8c-4c9a-bca1-77f1e49c7688.png">
---
* **STEP 3: The real deal Start the timer!**
  * Start the timer on your IPhone. 
  
--- 

* **STEP 4: Log into ieng6**
  * Press `<Ctrl>`+`<R>` to search command history. Enter "ssh" to find the right command. Press `<Enter>` to log in.
    <img width="308" alt="image" src="https://user-images.githubusercontent.com/122572429/221320833-d6477158-546a-408f-88c0-c4f3e77cf0a1.png">  
 
--- 

* **STEP 5: Clone your fork of the repository from your Github account** 
  * Type in this command  ` git clone git@github.com:yuribling123/lab7.git`
---
* **STEP 6: Run the tests, demonstrating that they fail**
  * `ls` to list current fliles and directoies
  * ` cd ./lab7/` to change directory
  *  Press `<Ctrl>`+`<R>` and enter "javac" to pull up the compile command in history and then press `<Enter>` to run the command 
    <img width="531" alt="image" src="https://user-images.githubusercontent.com/122572429/221322065-6ec548e8-31f8-40b7-9d18-b186e9057fbe.png">  
    
  * Press `<Ctrl>` + `<R>` and enter "java " to pull up the run command in history and then press `<Enter>` to run the command 
    <img width="737" alt="image" src="https://user-images.githubusercontent.com/122572429/221322231-0299ef6b-7f01-4fea-b8f9-3616431010f6.png">
    <img width="521" alt="image" src="https://user-images.githubusercontent.com/122572429/221323512-5ff06aff-f5ec-4888-966e-7c60adf49263.png">

---
* **STEP 7: Edit the code file to fix the failing test**
  * Enter nano to edit file: `nano ListExamples.java` When typing "List", press `<Tab>` to get to "ListExamples"
  * Move curser to the place that causes error: change "index1" to "index2"
    <img width="879" alt="image" src="https://user-images.githubusercontent.com/122572429/221324393-f98bb61d-88f7-464c-8114-0fc8838d7f06.png"> 
 
  * Save the edit by pressing `<Ctrl>` + `<O>`, the press `<Enter>` to confirm the filename 
  * Press `<Ctrl>` + `<X>` to exit

---
* **STEP 8: Run the tests, demonstrating that they now succeed**
  * Recompile the file: `javac ListExamples.java` . when typing "List", press `<Tab>` to get to "ListExamples"
  * Rerun the Junit Test using the shortcut: `<Ctrl>` + `<R>` and search for "javac "
    <img width="773" alt="image" src="https://user-images.githubusercontent.com/122572429/221324922-d6934cf0-1352-429a-bbac-c73e3e60ba33.png">
---
* **STEP 9: Commit and push the resulting change to your Github account (you can pick any commit message!)**
  * Add the edited file into list: `git add ListExamples.java`; use the shortcut `<Tab>` when typing filename
  * Commit the changes: `git commit -m "Updated" `
  * Push to the origin depository : `git push`  
  
    <img width="390" alt="image" src="https://user-images.githubusercontent.com/122572429/221325572-9f0d8cb3-aab8-43bd-95d0-9d60ce58b7e2.png">

---
**Done !**  

  <img width="541" alt="image" src="https://user-images.githubusercontent.com/122572429/221325779-e0949ea4-9d6b-45a8-86f4-dd1b82a3f5fc.png">


