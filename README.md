![main](https://github.com/Mustafa-Essam223/Infra-repo/assets/40956565/24bf6d3a-cbec-444d-b191-59669f1a6a0e)

# Final-Task 
### Jenkins & backend-application deployment on eks cluster  

### Create infrastructure using terraform with its all associations and dependencies and network
```
terraform init 
terraform plan 
terraform apply 
```
### access the public ec2 via console connect
### Using Jumb-Host instance (public ec2) to access the private cluster
```
aws eks --region us-east-1 update-kubeconfig --name eks-cluster
```
### apply k8s files inside the cluster to deploy jenkins, then use its loadbalancer dns name to access it 
```
a3837d023a56a4fb4baaf358bdcbda20-1904527929.us-east-1.elb.amazonaws.com
```
### finally u can access my application through loadbalancer dns name
```
a726579675a4a482386dc99ef892329f-f903a97250a7e2cd.elb.us-east-1.amazonaws.com
```
