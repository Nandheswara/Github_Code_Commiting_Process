Github First Time Code Comitting to the Repository Process

Note : Remove the Double quotes its only for identification only.

1. To Intialized a Git to give the below command
	"git init"

2. To add the all files in your folder give the below command
	"git add ."

3. To check the status of the what are the files added give the below command
	"git status"

4. To commit the files with message give the below command
	"git commit -m "Message what ever you can give here""

5. To create a branch for your code give the below code
	"git branch -M master"

6. To check the current branch give the below command
	"git branch"

7. To add the files to the repository give the below command
	"git remote add origin https://github.com/Nandheswara/Carry_Bag_AEM_Project.git"

8. To push the files local to cloud system give the below command
	"git push -u origin master"

__________________________________________________________________________________________

Commiting to the Repository

1. To clone the Repository using the below command
	"git clone -b master https://github.com/Nandheswara/Carry_Bag_AEM_Project.git"

2. To change the Directory using this below command
	"cd Directory name"

3. To Create a Branch using the below command
	"git branch -M stage"
		(OR)
   To Checkout the Branch using the below command
	"git checkout prod"

4. To Check what is the current branch using the below command
	"git branch"

5. To pull the code from the origin using the below command
	"git pull origin master" 

6. To fetch the repository using below command
	"git fetch"

7. Add the Modification in local cloned Repository folder.

8. To check the status of the files whether added or not using the below command
	"git status"

9. To Commit the files Using some message using this below command
	"git commit -m "Add the Message you want to show""

10. To Push the Local code to the remote Repository using the below command
	"git push origin prod"
	
__________________________________________________________________________________________

SSH Public and private Key Generation Process

1. To Generate a SSH Key give the below command
	"ssh-keygen -t ed25519 -C "YOUR_EMAIL_ADDRESS""

2. Enter the file name you want to save the file

3. You can also need to set password means we can give otherwise we can give it empty.

4. Now your SSH key will be generated.

5. To View the SSH key give the below command
	"type FILE_NAME"

Note : Both files are saved in same name only only different is public key file name comes with FILE_NAME.pub and private key comes with only FILE_NAME

__________________________________________________________________________________________

To Start Ngrok go to the Ngrok exe folder and open cmd use the below command
	"ngrok.exe http 8080"
