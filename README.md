# Today's Menu - Infrastructure
Cloud infrastructure for the Today's Menu Project

### Description
Utilizing GitHub Actions, ArgoCD, and AWS ECR, I've architected a seamless CI/CD pipeline. By leveraging AWS EKS, deployments are not only containerized but also ensure scalability, resilience, and optimal performance.



### Architecture

img

- **GitHub Actions**: For Continuous Integration and Continuous Deployment.
- **ArgoCD**: Ensuring declarative, GitOps continuous delivery.
- **AWS ECR**: Docker container registry to store and manage Docker images.
- **AWS EKS**: Managed Kubernetes Service, providing a robust platform for deploying, managing, and scaling containerized applications.
- **Terraform** : Utilized for defining and provisioning the entire infrastructure stack declaratively using code.




### Prerequisites
- AWS CLI installed and configured.
- Terraform


### Setup
```
$ git clone

```



### Deployment
```
$ terraform init 
$ terraform plan
$ terraform apply
```


### Usage with Argo CD
1. Configure Argo CD with your EKS cluster.
2. Sync your applications using Argo CD UI or the CLI:


### Cleaning Up
```
$ terraform destroy
```


### Contributors
[Younghwan Kim](https://github.com/royroyee)


### License
- MIT
