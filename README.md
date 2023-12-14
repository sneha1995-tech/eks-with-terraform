# eks-with-terraform
create EKS cluster with terraform:

Steps:
1. As pre-requisites we need to create below AWS resources:
   VPC
   subnet
   AZ
2. create a security group and below component
   security group
   roles
   policy
3. create cluster policy for both master and worker nodes.
4. create master node and worker nodes with terraform.

once we are done with configuration file creation execute below command to run the configuration files:

1. terraform init : it will initiliaze the required providers
2. terraform validate : it will check if any syntax errors
3. terraform plan : it will create plan for us
4. terraform apply: it will create actual resources in AWs env.

