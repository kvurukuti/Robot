# BQaaF Infrastructure as a code
A brief description of what this project does and what we are going to do?  Here we are going to perform three tasks .

1. Build Infrastructure as code using Terraform.
2. Running shell script for creating roles in multiple gcp projects taking project Id's as input from the .csv file and attaching that roles to one serviceaccount.
3. Running shell script for creating logsinks in multiple gcp projects taking project Id's as inputs form the .csv file and attaching that logsink to Bigquery Dataset to route the logs.


## Uploading  automation directory to the GCP Cloud Shell using browser.

we have two sub-directories present inside the automation folder for terraform and shell scripting.

1. login to the gcp console and open the cloud Shell.
2. Click on upload button to upload the folder as shown in below imagse.

![1](https://user-images.githubusercontent.com/96725131/231144587-6d551c07-71d3-4b87-a410-b69f7e656238.PNG)

3. click on upload and select the folder to upload,choose the destination directory where our automation folder should upload.
![2](https://user-images.githubusercontent.com/96725131/231145136-0e015a97-875f-4c70-8693-f970e415f1f4.PNG)

4. lets check wheather the automation folder is uploaded or not in the cloud shell using ls command.

![3](https://user-images.githubusercontent.com/96725131/231145154-65a6e95d-e4ea-46fc-a943-77c444267ca3.PNG)

## Confirmation

Once if automation directory is successfully uploaded in to the cloud shell. we have two sub-directories inside the auotmation directory i,e.
1. Infra(Terraform)
2. Scripting

## Process

step:1 
First we are going to run terraform scripts to build the Infrastructure , terraform form scripts will be present inside the automation folder with folder name called Infra.

step:2
After the successfully infra creation we are going to adding-roles.sh file to create role in multiple gcp projects.

adding-roles.sh file will be present inside the scripting folder


step:3
Finally we are going to run logsink.sh file to create logsink and attach to the dataset.

logsink.sh file will be present inside the scripting folder
