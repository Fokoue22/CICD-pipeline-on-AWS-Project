# CI/CD pipeline on AWS Project1
## Tasks 1 - Set up a code repository on CodeCommit and clone it on your local. You need to setup GitCredentials in your AWS IAM.
## Use those credentials in your local and then clone the repository from CodeCommit

### Open aws console and search for CodeCommit and Click on Create repository

![Alt text](image.png)

### Your repository will be created here
 
![Alt text](image-1.png)
  
### Now go to IAM and select the current user

![Alt text](image-1.png)

### Click on Generate credentials

![Alt text](image-1.png)

### Now copy the clone command of your repo and paste it in your file system

![Alt text](image-1.png)

Here, we have successfully cloned our repository.

## Task 2 - Add a new file from local and commit to your local branch

### Open the local system, Create a new file called tasks.txt then Execute the below commands

```
git add .
git commit -m "message"

```
![Alt text](image-1.png)

### Push the local changes to CodeCommit repository.

Using the following command, push the changes from your local to the CodeCommit repository.

```
git push origin master

```
![Alt text](image-1.png)

### Verify that the files are pushed into the CodeCommit repository.

In the CodeCommit Repository > Repositories > Code.

![Alt text](image-1.png)

And yay! You have pushed your local files to the CodeCommit Repository.

## Author
FOKOUE THOMAS