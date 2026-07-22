---
title: "Các bước chuẩn bị"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 5.2. </b> "
---

#### IAM permissions

Thêm chính sách quyền IAM tùy chỉnh sau vào tài khoản AWS của bạn để phục vụ việc tự tay triển khai và quản lý hạ tầng cho workshop Fashion E-commerce Platform.

```
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "VisualEditor0",
            "Effect": "Allow",
            "Action": [
                "ec2:CreateVpc",
                "ec2:DeleteVpc",
                "ec2:DescribeVpcs",
                "ec2:ModifyVpcAttribute",
                "ec2:CreateSubnet",
                "ec2:DeleteSubnet",
                "ec2:DescribeSubnets",
                "ec2:CreateRouteTable",
                "ec2:DeleteRouteTable",
                "ec2:DescribeRouteTables",
                "ec2:AssociateRouteTable",
                "ec2:CreateInternetGateway",
                "ec2:DeleteInternetGateway",
                "ec2:AttachInternetGateway",
                "ec2:DetachInternetGateway",
                "ec2:CreateSecurityGroup",
                "ec2:DeleteSecurityGroup",
                "ec2:DescribeSecurityGroups",
                "ec2:AuthorizeSecurityGroupIngress",
                "ec2:AuthorizeSecurityGroupEgress",
                "ec2:RunInstances",
                "ec2:StopInstances",
                "ec2:TerminateInstances",
                "ec2:DescribeInstances",
                "rds:CreateDBInstance",
                "rds:DeleteDBInstance",
                "rds:DescribeDBInstances",
                "rds:CreateDBSubnetGroup",
                "elasticache:CreateCacheCluster",
                "elasticache:DeleteCacheCluster",
                "elasticache:DescribeCacheClusters",
                "s3:CreateBucket",
                "s3:DeleteBucket",
                "s3:PutObject",
                "s3:GetObject",
                "s3:ListBucket",
                "ec2:CreateVpcEndpoint",
                "ec2:DeleteVpcEndpoints",
                "ec2:DescribeVpcEndpoints",
                "codedeploy:*",
                "logs:CreateLogGroup",
                "logs:PutRetentionPolicy",
                "iam:PassRole"
            ],
            "Resource": "*"
        }
    ]
}

```

#### Khởi tạo tài nguyên bằng CloudFormation

Trong lab này, chúng ta sẽ dùng N.Virginia region (us-east-1).

Để chuẩn bị cho môi trường làm workshop, chúng ta deploy CloudFormation template sau (click link): [PrivateLinkWorkshop ](https://us-east-1.console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/quickcreate?templateURL=https://s3.us-east-1.amazonaws.com/reinvent-endpoints-builders-session/Nested.yaml&stackName=PLCloudSetup). Để nguyên các lựa chọn mặc định.

![create stack](/images/5-Workshop/5.2-Prerequisite/create-stack1.png)

- Lựa chọn 2 mục acknowledgement
- Chọn Create stack

![create stack](/images/5-Workshop/5.2-Prerequisite/create-stack2.png)

Quá trình triển khai CloudFormation cần khoảng 15 phút để hoàn thành.

![complete](/images/5-Workshop/5.2-Prerequisite/complete.png)

- 2 VPCs đã được tạo

![vpcs](/images/5-Workshop/5.2-Prerequisite/vpcs.png)

- 3 EC2s đã được tạo

![EC2](/images/5-Workshop/5.2-Prerequisite/ec2.png)
