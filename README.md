# ec2-insta-scheduler
EC2 is one of the most popular computing service in AWS. Numerouse EC2 are launched for DevOps and production purpose but keep on running idle. This incures significant cost of computing. ec2-insta-scheduler is simple but very robust automated service which stops idle EC2 instances outside work hours and restarts EC2 instances during work hours. I used AWS resources such as Cloudformation to automate the system,Cloudwatch which monitors EC2 states and invoke Lambda, Lambda Function, DynamoDB and others services.
