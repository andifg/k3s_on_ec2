# K3s Setup on EC2 with terraform
***

## Prerequisites
Configure the AWS CLI environment variables:
```
export AWS_ACCESS_KEY_ID=<>
export AWS_SECRET_ACCESS_KEY=<>
export AWS_DEFAULT_REGION=<>
```


## Usage
Use this repo to setup a kubernetes cluster on a ec2 instance with terraform and K3s

Setup of Ec2 instance:
```
terraform plan
terraform apply
```
Installation of Kubernetes Cluster:

Adapt ./k3s/k3sup_setup.sh and enter ip adress of ec2 instance and path to your ssh key
´´´
./k3s/k3sup_setup.sh
```
