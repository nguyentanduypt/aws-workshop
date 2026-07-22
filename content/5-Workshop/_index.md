---
title: "Workshop"
date: 2024-01-01
weight: 5
chapter: false
pre: " <b> 5. </b> "
---

# Secure Hybrid Access to S3 using VPC Endpoints

# Building Cost-Optimized Network Infrastructure and CI/CD for Fashion E-commerce Platform

#### Overview

**AWS VPC Endpoints and PrivateLink** provide secure, private connectivity directly from resources within your VPC (such as Spring Boot backend servers in Private Subnets) to AWS services without traversing the Public Internet, completely eliminating expensive NAT Gateway charges.

In this Workshop section, you will learn how to set up and configure a Multi-AZ network infrastructure, optimizing data transmission paths for the **Fashion E-commerce Platform**:

- **Gateway Endpoint** - Used to route traffic from your VPC to **Amazon S3** (for product image storage) using private IP addresses via route tables.
- **Interface Endpoint** - Used for CI/CD services (such as AWS CodeDeploy) to securely automate source code deployment into backend servers located within Private Subnets.

#### Content

1. [Introduction](5.1-Workshop-overview)
2. [Prerequisites](5.2-Prerequiste/)
3. [Network Infrastructure Optimization](5.3-S3-vpc/)
4. [Backend & Data Layer Setup](5.4-S3-onprem/)
5. [Automated CI/CD](5.5-Policy/)
6. [Cost Optimization & Monitoring](5.6-Cleanup/)
