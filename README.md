# Udacity-Crate-VPC

#### Ronny Morel ronny.morel07@gmail.com

# PROJECT SPECIFICATION:

## Project Introduction

You will create an EC2 Instance based on Amazon Linux AMI that you can connect via SSH. While provisioning the instance. The Web service will update from post to a S3 Bucket 

Once the instance is running, create an IAM role with admin access to your account. Then, attach the role to your EC2. In this case, the CLI tool will pick up the credentials from the role and won’t need hard-coded credentials.

## Exercise objectives

By the end of this exercise, you will be able to:

Launch a secure EC2 instance

- Create IAM role with admin privileges
- Attach the IAM role to the EC2 instance created earlier
- Create a S3 Bucket with your application files
- Connect to your EC2 instance via SSH
- Use CLI tool in the EC2 instance
- Browse your application