

# Steps to Deploy the Infrastructure

## 1️⃣ Initialize Terraform  
   ```sh
   terraform init   # Ensure Terraform is initialized
   
2️⃣ Validate the Configuration
terraform validate   # Check for syntax errors

3️⃣ Plan the Changes
terraform plan -out=tfplan   # Preview the changes before applying

4️⃣Apply the Configuration:
terraform apply tfplan   # Deploy the infrastructure

5️⃣Verify the Deployment:
terraform output public_ip   # Retrieve the public IP of the instance
curl http://<public-ip>   # Test Apache server response

6️⃣Destroy the Infrastructure (Optional):
terraform destroy   # Remove all created resources

This guide ensures a smooth Terraform deployment!



