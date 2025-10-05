#  DevOps-on-AWS
This repository contain CI/CD pipeline using CODEPIPELINE build for devop-april25

# COHORT_APRIL25
Setup a two stage CI/CD pipeline using CODEPIPELINE to automatically deploy a static website on AMAZON S3 Bucket. The website is will display a simple HTML webpage. 
![Alt text](images/CICD-pipeline-architecture.jpg)

<img width="467" alt="CICD-Pipeline" src="https://github.com/Fokoue22/DevOps-on-AWS/assets/117523566/c56ffc9b-4597-478c-916d-d84af770d079">


### The first step is to create and connect to your repo on git and push your html file e.g cohort-april25

![Alt text](images/push-git.png)

### Next step is to create a hosting S3 bucket and don't Block all public access
 
![Alt text](images/create-s3bucket.png)
  
### We need to enable Static website hosting and add our index.html and error.html(this is optional)

![Alt text](images/enable-static-website.png)

### Click on Generate credentials

![Alt text](credentails.png)

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
