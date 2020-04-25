# Terraform_Kubernetes_EKS_AWS
How to provision Kubernetes cluster in AWS EKS using Terraform.
This repository was created based on Hashicorp Terraform documentation.

Requirements: 
> I'm using Mac OS X 10.15.4

- AWS Account
- AWS CLI
```
  $ brew install awscli
  $ aws configure
```
- AWS IAM Authenticator
```
  $ brew install aws-iam-authenticator
```
- Kubectl
```
  $ brew install kubernetes-cli
```
- Wget
```
  $ brew install wget
```

Setting up the environment

```
$ git clone https://github.com/gb8may/terraform_kubernetes_eks_aws.git
$ cd terraform_kubernetes_eks_aws
```
Initializing the workspace
```
$ terraform init
```
Creating the cluster
```
$ terraform apply
```
