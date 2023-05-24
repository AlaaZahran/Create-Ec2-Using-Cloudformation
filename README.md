
# Create-Ec2-Using-Cloudformation

![image](https://github.com/AlaaZahran/create-ec2-using-cloudformation/assets/46306526/23dfbc5c-ca3a-44f0-a432-8cb402c274d9)
 

# Description

This CloudFormation template creates an EC2 instance with a VPC, private and public subnets, and a security group to allow SSH. The template uses the following resources:

1- VPC

2- Public subnet

3- Private subnet

4- Internet gateway

5- VPC gateway attachment

6- Public route table

7- Security group

8- EC2 instance


# Prerequisites
Before you begin, you will need the following:

An AWS account

# Deployment

To use this template, follow these steps:

1- Open the AWS CloudFormation console.

2- Click "Create Stack" to create a new stack.

3- Select "Template is ready" and "Upload a template file" and upload the CloudFormation template file.

4- Enter a stack name and other required parameters.

5- Click "Create stack" to launch the stack.

6- Wait for the stack creation to complete. Once the stack is created, you should see an EC2 instance running in your AWS account.

# Accessing the EC2 Instance
To access the EC2 instance, you can use SSH with the key pair specified in the KeyName parameter.

```
ssh -i alaa-ec2.pem ec2@ec2_ip
```


