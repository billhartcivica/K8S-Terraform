# K8S-Terraform
Terraform scripts for creating a Kubernetes cluster
****
terraform apply - builds infrastructure for all *.tf files in the current folder.
terraform apply -input=false -auto-approve - builds inf for all *.tf files without a 'yes' confirmation.
terraform destroy - tears down insf for all *.tf files in current folder.
****
To enable the scripts, the AWS Access Key and Secret Key must be added, as well as the PEM file used to access the host via SSH. Substitute the relevant fields for your project name and amend the host names to whatever you require.
