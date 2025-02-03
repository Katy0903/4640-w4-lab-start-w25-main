# 4640-w4-lab-start-w25
See lab instructions on D2L for details

## AWS EC2 Web Server Setup with Terraform and Cloud-Config

### General Setup

**Set up AWS EC2 instance with Terraform**:
1. Clone the init folder to the linux environment
2. Update the cloud-config ymal file with installing packages and ssh key information.
3. Edit the main.tf file with correct information.
4. Run terraform command like terrafrom init and terraform apply.
5. Use SSH key for secure connection.

### SSH Key Pair Creation

To create a new SSH key pair in my Linux environment, I run this command:

```bash
ssh-keygen -t ed25519 -f ~/.ssh/bcitkey2 -C "bcitkey2_ubuntu"
```

### Terraform Setup Instructions



**Initialize Terraform:**

```bash
terraform init
```
**Format Terraform files:**
```bash
terraform fmt
```
**Plan the infrastructure:**
```bash
terraform plan
```
**Apply the configuration to create the resources:**
```bash
terraform apply
```