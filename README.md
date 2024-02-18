# MultiCloud-Data-Migration
**<h1>MultiCloud-Data-Migration </h1>**
<h2>Description</h2>
<h2>Deployment</h2>
Steps in Amazon Web Services (AWS)
Creating the terraform-en-1 user using the IAM service
Access the AWS console here and log in with your newly created account.
In the search bar, type IAM. In the Services section, click on IAM.
Click on Users and then Add users, enter the name terraform-en-1 and click Next to create a programmatic type user.
Creating the Access Key for the terraform-en-1 user using the IAM service
Access the terraform-en-1 user.
Click on Create access key.
Steps in Google Cloud Platform (GCP)
Preparing the environment to run Terraform
Access the Google Cloud Console here and log in with your newly created account.
Open the Cloud Shell.
Download the mission1.zip file in the Google Cloud shell using the wget command: wget https://tcb-public-events.s3.amazonaws.com/icp/mission1.zip.
Upload the key.csv file to the Cloud Shell using the browser.
Verify if the mission1.zip and key.csv files are in the folder in the Cloud Shell using the command below:
unzip mission1.zip
mv key.csv mission1/en
cd mission1/en
chmod +x *.sh
