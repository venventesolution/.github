Project setup
-------------
# Required Softwares

Intellij community edition </br>
Install Jdk 17 or any new versions </br>
Install Docker desktop for windows

How to Clone the repo
---------------------
Before cloning the repo need to add your computer ssh key to github
- Open the command prompt and run the below command.
<b<i>ssh-keygen -t ed25519 -C "<email_id>@gmail.com" </i></b>
- It will ask below question 
Enter file in which to save the key
- Press enter key
- It will ask below question type any password
Enter passphrase (empty for no passphrase):
You need to reenter password again
- Navigate to windows /user/ folder there you can find the .ssh folder
- Open the file which has .pub file copy the content inside the file.

- Go to github profile on browser and select the Settings
- Select the SSH and GPG keys
- CLick the  Add New SSH button, add the any title and paste the ssh key in key section.
- Try to open the command prompt (make sure you open the particular directory where you can save project files)
- Try to run the below command to clone the repo
  </br><b>git clone git@github.com:venventesolution/his-service.git </b>
  </br> if you See DONE then your SSH key is uploaded successfully. 

How to run the application
-------------------------
- Run the docker desktop.
- Go the the outpatient directory.
- Run the "docker-compose up"
  
Download git
https://git-scm.com/downloads/win
