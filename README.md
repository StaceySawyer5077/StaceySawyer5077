## Hi there 👋

Welcome to my GitHub repository—a collection of infrastructure-as-code (IaC) projects built with Terraform to automate and manage AWS cloud infrastructure. As a cloud engineer, I specialize in creating scalable, reproducible, and secure infrastructure using Terraform’s declarative syntax, with a strong focus on multi-cloud readiness and seamless CI/CD integration.

This repository showcases real-world examples of how to define, provision, and manage AWS resources—such as VPCs, EC2 instances, S3 buckets, IAM roles, RDS databases, and Lambda functions—using Terraform modules and reusable configurations. Each project is structured to follow best practices in code organization, variable management, remote state handling (via S3 and DynamoDB), and environment separation for dev, staging, and production.

A key emphasis is on multi-cloud environments and infrastructure portability. While AWS is the primary provider in these projects, many configurations are designed with a provider-agnostic mindset, enabling extensibility to platforms like Azure or Google Cloud. This includes examples of using provider aliases, workspaces, and conditional logic to support hybrid cloud strategies or gradual cloud migrations.

CI/CD plays a critical role in infrastructure automation, and this repository includes workflows for integrating Terraform with tools like GitHub Actions and GitLab CI. These pipelines enable automated formatting, linting (terraform fmt and tflint), plan previews, and secure apply steps with manual approvals—ensuring reliable and auditable infrastructure changes throughout the deployment lifecycle.

Whether you're managing production infrastructure, spinning up cloud-native services, or experimenting with scalable architectures, this repository provides the foundational templates and practices needed to succeed with Terraform and AWS.

