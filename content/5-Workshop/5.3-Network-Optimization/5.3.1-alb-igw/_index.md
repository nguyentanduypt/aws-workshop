---
title: "Create gateway endpoint"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 5.3.1 </b> "
---

1. Open the [Amazon VPC console](https://us-east-1.console.aws.amazon.com/vpc/home?region=us-east-1#Home:)
2. In the navigation pane, choose **Endpoints**, then click **Create Endpoint**:

{{% notice note %}}
You will see **6 existing VPC endpoints** that support **AWS Systems Manager (SSM)**. These endpoints were deployed automatically by the **CloudFormation Templates** for this workshop.
{{% /notice %}}

1. Open the [Amazon VPC console](https://ap-southeast-1.console.aws.amazon.com/vpc/home?region=ap-southeast-1#Home:) in the **Singapore (ap-southeast-1)** region.
2. In the navigation pane, choose **Endpoints**, then click **Create endpoint**:

{{% notice note %}}
You will see existing endpoints if any. For our manually configured **Fashion E-commerce Platform**, we will create a dedicated gateway endpoint for secure and free S3 data retrieval from private subnets.
{{% /notice %}}

![endpoint](/images/5-Workshop/5.3-Network-Optimization/5.3.1-alb-igw/endpoints.png)

3. In the Create endpoint console:

- Specify name of the endpoint: `fashion-s3-gwe`
- In service category, choose **AWS services**

![endpoint](/images/5-Workshop/5.3-Network-Optimization/5.3.1-alb-igw/create-s3-gwe1.png)

- In **Services**, type `s3` in the search box and choose the service with type **Gateway** (e.g., `com.amazonaws.ap-southeast-1.s3`)

![endpoint](/images/5-Workshop/5.3-Network-Optimization/5.3.1-alb-igw/services.png)

- For VPC, select `FashionEcommerce-VPC` from the drop-down.
- For **Configure route tables**, select the custom private route table (`FashionEcommerce-Private-RT`) that is associated with your private and database subnets.

![endpoint](/images/5-Workshop/5.3-Network-Optimization/5.3.1-alb-igw/vpc.png)

- **For Policy**, leave the default option, **Full Access**, to allow full access to the S3 bucket storing product images.

![endpoint](/images/5-Workshop/5.3-Network-Optimization/5.3.1-alb-igw/policy.png)

- Click **Create endpoint**, then close the success notification.

![endpoint](/images/5-Workshop/5.3-Network-Optimization/5.3.1-alb-igw/complete.png)
