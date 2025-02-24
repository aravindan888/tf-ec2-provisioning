AWS EC2 Web Server Deployment with Terraform
sets up an AWS EC2 instance running a basic HTTP server (Apache). The instance is secured using a security group that allows inbound HTTP traffic on port 80.

Prerequisites
Before you begin, ensure you have:
- **Terraform** installed ([Install Guide](https://learn.hashicorp.com/tutorials/terraform/install-cli))
- **AWS CLI** installed and configured ([AWS CLI Setup](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html))
- An active AWS account
- An existing AWS key pair for SSH access

**NOTE**
Replace "your ami" with a valid Amazon Linux 2 AMI ID for your region. You can find the latest AMI IDs here.
Ensure the aws-keypair exists in your AWS account.
