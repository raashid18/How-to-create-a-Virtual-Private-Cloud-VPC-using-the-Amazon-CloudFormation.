# How-to-create-a-Virtual-Private-Cloud-VPC-using-the-Amazon-CloudFormation.
Creating a Virtual Private Cloud (VPC), Subnets, Internet Gateway and Route Table using the Amazon CloudFormation.

![CloudFormation](https://user-images.githubusercontent.com/67089791/205579076-83d0cd57-a56b-41c9-b19f-e3b8f44517aa.png)


First of all create a file called vpc.yaml in your local code editor and copy the content of file vpc.yaml from this repository.

Introduction to CloudFormation.
1. Log in to the AWS management console.
2. Search for the CloudFormation. Enter into the CloudFormation dashboard. Click on create stack.
3. Fill the prerequisite for preparing template. Choose the option “template is ready”.
4. Specify the template and upload a template file vpc.yaml.
5. I have already created a template where creation of VPC, subnet, IGW all are mentioned.
6. Specify the stack details like stack name, and analyze the parameters.
7. Inside the parameter section all things will be mentioned which is configured inside the template.
8. After that click on Next.
9. Configure the stack options, you can give the tags but it is optional. Step 10:- After that leave all the configuration by default.
10. Now you have to configure the advanced, notification, stack creation option.
11. After configuring all the thing just review all the settings and click submit.
12. The process of creating the VPC stack is started.
13. Now open the AWS management console in new tab and search for VPC. Step 15:- Go inside the VPC dashboard and check the VPC and subnet is created or not.
14. Come back to the cloud formation dashboard and check for the completion of creation of stack.
15. All steps is completed, now you can delete the all VPC and subnet by a single click from the CloudFormation dashboard.
 
