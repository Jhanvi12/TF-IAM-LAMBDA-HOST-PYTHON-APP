# TF-IAM-LAMBDA-HOST-PYTHON-APP
By using Terraform, we were able to automate the deployment of Python code to an AWS Lambda function.The process involved creating the necessary IAM roles and policies, uploading the Python code as a ZIP file, and defining the AWS Lambda function resource block with the appropriate configuration. After executing the Terraform plan and Terraform apply commands, we were able to validate the deployment using the AWS Lambda console. This streamlined and automated approach to AWS Lambda function management allows for increased efficiency and scalability in the development process.
# Process Involved/Learnt about
```
1.Terraform script to create AWS Lambda function
2.Configure AWS Provider with Access Key Credentials
3.Create Terraform variables.tf and output.tf file
4.Create main.tf and add IAM Role
5.Add IAM Policy
6.Attach IAM Policy to IAM Role
7.Write the Python Application
8.Create a ZIP of the Python Application
9.Add aws_lambda_function Function
10.Run and Execute Terraform main.tf
11.Verify the Lambda Function From AWS Console
12.Clean Up-Using terraform destroy
``` 

