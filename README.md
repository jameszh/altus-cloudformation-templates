# AWS Cloudformation Template for Generic VPC

---

## Objective

---
This create a general AWS VPC with the following Resources

1. VPC in 3 AZs in a region
1. 2 Subnets in each AZ, one for public subnet and one for private subnet
1. Nat Gateway, choices of one for each AZ or one for all the AZs
1. Bastion host (Amazon Linux)

### Launching

<a href="https://console.aws.amazon.com/cloudformation/home?#/stacks/new?&templateURL=https://s3.amazonaws.com/us-east-1-iac-865942846496/generic-vpc-stack/vpc-3by2-v2.yaml
" target="_blank"><img src="https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png"></a>

<a href="https://console.aws.amazon.com/cloudformation/designer/home?region=us-east-1&templateURL=https://s3.amazonaws.com/us-east-1-iac-865942846496/generic-vpc-stack/vpc-3by2-v2.yaml" target="_blank">
<img src="https://s3.amazonaws.com/us-east-1-iac-865942846496/generic-vpc-stack/designer.jpg" width:100% alt="View in Designer"></a>

