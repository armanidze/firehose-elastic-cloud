# Kinesis Firehose to Elastic Cloud deployment

* Kinesis Firehose to Elastic Cloud is one of few options for send data elastic deployment

# Usage elastic-create-deployment service:
Cloud formation templates contain main.yml template.

# Input parameters for creating cloudformation stack.
Stack name: Enter name of stack.

DeploymentName: Enter name of elastic deployment.

Elastic Cloud ID: Elastic Cloud Id string from Elastic Deployment managment console

Elastic Secret key: password for elastic user from Elastic Deployment managment console

Region: Choose region from list.

Input parameters for creating AWS EC2 instance with elastic agent
VPC ID: Select your VPC.

Public subnet 1(2) ID: Select subnets for Auto Scaling Group.

Allowed EC2 external access CIDR: Enter allowed CIDR block for external SSH access to the EC2s.

Key pair name: Select name of an existing public/private key pair.
