# Awesome Terraform [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 455,028 | 🐛 62 | 📅 2026-04-02 <!-- omit in toc --> with stars

[![Link Checker](https://github.com/shuaibiyy/awesome-tf/actions/workflows/link-checker.yml/badge.svg)](https://github.com/shuaibiyy/awesome-tf/actions/workflows/link-checker.yml) ⭐ 6,344 | 🐛 6 | 📅 2026-04-13
[![Misspell Check](https://github.com/shuaibiyy/awesome-tf/actions/workflows/misspell.yml/badge.svg)](https://github.com/shuaibiyy/awesome-tf/actions/workflows/misspell.yml) ⭐ 6,344 | 🐛 6 | 📅 2026-04-13
[![Not Found Check](https://github.com/shuaibiyy/awesome-tf/actions/workflows/notfound.yml/badge.svg)](https://github.com/shuaibiyy/awesome-tf/actions/workflows/notfound.yml) ⭐ 6,344 | 🐛 6 | 📅 2026-04-13

> A curated list of resources on [HashiCorp's Terraform](https://www.terraform.io/).
> [<img src="https://raw.githubusercontent.com/shuaibiyy/awesome-terraform/master/terraform.svg" align="right" width="100">](https://terraform.io)
> Your [contributions](https://github.com/shuaibiyy/awesome-terraform/blob/master/contributing.md) ⭐ 6,344 | 🐛 6 | 📅 2026-04-13 are welcome!

Terraform enables you to safely and predictably create, change, and improve production infrastructure. It is an open source tool that codifies APIs into declarative configuration files that can be shared amongst team members, treated as code, edited, reviewed, and versioned.

## Contents <!-- omit in toc -->

* [Legend](#legend)
* [Official Resources](#official-resources)
* [Community](#community)
* [Books](#books)
* [Learning and Studying](#learning-and-studying)
* [Tutorials and Blog Posts](#tutorials-and-blog-posts)
  * [Beginner Guides](#beginner-guides)
  * [Writing Custom Providers](#writing-custom-providers)
  * [How-To](#how-to)
  * [Multi-Environment Configuration](#multi-environment-configuration)
  * [Azure](#azure)
  * [AWS](#aws)
  * [Google Cloud](#google-cloud)
  * [Miscellaneous](#miscellaneous)
* [Community Modules](#community-modules)
* [Self-Hosted Registries](#self-hosted-registries)
* [Managed Registries](#managed-registries)
* [Providers](#providers)
  * [Hashicorp supported providers](#hashicorp-supported-providers)
  * [Vendor supported providers](#vendor-supported-providers)
  * [Community providers](#community-providers)
* [Testing](#testing)
* [Tools](#tools)
  * [CI](#ci)
  * [IDE](#ide)
* [Libraries](#libraries)
* [Boilerplates](#boilerplates)
* [Self-hosted Terraform Platforms](#self-hosted-terraform-platforms)
* [Managed Terraform Platforms :heavy\_dollar\_sign:](#managed-terraform-platforms-heavy_dollar_sign)
* [Terraform Enterprise Tooling](#terraform-enterprise-tooling)
* [Videos](#videos)
* [Editor Plugins](#editor-plugins)
* [License](#license)

## Legend

* Not compatible with *terraform >= 0.12* :ghost:
* Abandoned :skull:
* Monetized :heavy\_dollar\_sign:

## Official Resources

* [Hashicorp Terraform Blog](https://www.hashicorp.com/en/blog/products/terraform)
* [Introduction to Terraform](https://developer.hashicorp.com/terraform/intro)
* [Terraform Documentation](https://developer.hashicorp.com/terraform/docs)
* [Terraform learn](https://developer.hashicorp.com/terraform/tutorials)

## Community

* [Terraform Bug Tracker](https://github.com/hashicorp/terraform/issues) ⭐ 48,133 | 🐛 1,891 | 🌐 Go | 📅 2026-04-13
* [The Claude Agent Skill for Terraform and OpenTofu - testing, modules, CI/CD, and production patterns](https://github.com/antonbabenko/terraform-skill) ⭐ 1,520 | 🐛 6 | 📅 2026-02-02 - Claude Code skill for Terraform and OpenTofu — testing, module design, CI/CD workflows, and production patterns.
* [Terragrunt Reference Architecture](https://github.com/antonbabenko/terragrunt-reference-architecture) ⭐ 380 | 🐛 1 | 🌐 HCL | 📅 2022-02-09 :skull:
* [Complete Terraform documentation as PDF files (Updated nightly)](https://github.com/antonbabenko/terraform-docs-as-pdf) ⭐ 209 | 🐛 6 | 🌐 Shell | 📅 2025-10-30 :skull:
* [Terraform AWS Modules](https://github.com/terraform-aws-modules) + [meta-configurations repository](https://github.com/terraform-aws-modules/meta) ⭐ 80 | 🐛 0 | 🌐 HCL | 📅 2022-04-28
* [Terraform PDF Doc](https://github.com/dohsimpson/terraform-doc-pdf) ⭐ 68 | 🐛 0 | 🌐 Python | 📅 2020-04-03 :skull:
* [awesome-terraform-compliance](https://github.com/antonbabenko/awesome-terraform-compliance) ⭐ 43 | 🐛 0 | 📅 2026-04-13 - Curated list of tools, frameworks, and resources for Terraform compliance and security.
* [weekly.tf - Terraform Weekly Newsletter](https://www.weekly.tf/) - Weekly newsletter covering Terraform news, open-source projects, announcements, and discussions.
* [Terraform Community Modules](https://github.com/terraform-community-modules)
* [Terraform Twitter Community](https://twitter.com/i/communities/1501688565884928007) <!-- markdown-link-check-disable-line -->
* [Terraform Discuss](https://discuss.hashicorp.com/c/terraform-core/27)
* [Terraform Provider/Module Registry](https://registry.terraform.io/)
* [Terraform Roadmap](https://roadmap.sh/terraform)
* Language-specific communities:
  * [Telegram (Ukrainian speak community)](https://t.me/terraform_ukraine)

## Books

* [Big Little Book On Terraform](https://www.amazon.com/Big-Little-Book-Terraform-Omos-ebook/dp/B07PWYPNX8/)
* [Bootstrapping Microservices with Docker, Kubernetes, and Terraform, Second Edition](https://www.manning.com/books/bootstrapping-microservices-second-edition)
* [Deep-Dive Terraform on Azure](https://link.springer.com/book/10.1007/978-1-4842-7328-9)
* [Getting Started with Terraform, 2nd ed.](https://www.amazon.com/Getting-Started-Terraform-production-infrastructure/dp/1788623533/)
* [HashiCorp Infrastructure Automation Certification Guide](https://www.amazon.com/HashiCorp-Infrastructure-Automation-Certification-Guide-ebook/dp/B092KM7LXC/)
* [IaC starting with Terraform (Korean)](https://product.kyobobook.co.kr/detail/S000202478097)
* [Infrastructure as Code](http://shop.oreilly.com/product/0636920039297.do)
* [Patterns and Practices for Infrastructure as Code: With examples in Python and Terraform](https://www.manning.com/books/infrastructure-as-code-patterns-and-practices)
* [Terraform Best Practices](https://www.terraform-best-practices.com/) - [open-source ebook](https://github.com/antonbabenko/terraform-best-practices) ⭐ 2,445 | 🐛 15 | 🌐 HCL | 📅 2026-03-20
* [Terraform Cookbook](https://www.amazon.com/Terraform-Cookbook-Efficiently-Infrastructure-platforms/dp/1800207557)
* [Terraform for Ops e-book](https://www.terraformforops.com)
* [Terraform in Action](https://www.manning.com/books/terraform-in-action)
* [Terraform in Depth](https://www.manning.com/books/terraform-in-depth)
* [Terraform: Up & Running, 3rd ed.](https://www.terraformupandrunning.com/)
* [The Terraform Book](https://terraformbook.com/)

## Learning and Studying

* Terraform Academy - (<https://www.terraformacademy.com>)
* [compliance.tf docs](https://compliance.tf/docs/) - Free Terraform implementations of SOC 2, PCI DSS, HIPAA, NIST 800-53, and 35+ other compliance controls — open reference for writing compliant infrastructure code.

## Tutorials and Blog Posts

### Beginner Guides

* [A Comprehensive Guide to Terraform](https://blog.gruntwork.io/a-comprehensive-guide-to-terraform-b3d32832baca) - Series of blog posts from the author of "Terraform: Up & Running" that guide the reader from beginning with Terraform to using it in the real world.
* [Using Terraform for Cloud Deployments - Part 1](https://dev.to/koenighotze/using-terraform-for-cloud-deployments---part-1) - Provisioning an EC2 instance.
* [Hello, world: The Fargate/Terraform tutorial I wish I had](https://section411.com/2019/07/hello-world/) - Blog post describing setting up an ECS Fargate cluster from scratch
* [Terraform Security Guide](https://sysdig.com/blog/terraform-security-best-practices/) - Blog post describing security best practices when working with Terraform
* [Building a SaaS API? Don't Forget Your Terraform Provider](https://www.speakeasyapi.dev/post/build-terraform-providers) - Why you should write a terraform provider
* [Complete Terraform Course in French (Free)](https://blog.stephane-robert.info/docs/infra-as-code/provisionnement/terraform/introduction/) – A comprehensive and free course in French to master Terraform, from beginner to advanced usage, with hands-on examples and best practices.

### Writing Custom Providers

* [Creating custom terraform providers](https://blog.pelo.tech/creating-custom-terraform-providers-341311823fa2) - Guide for creating custom providers.
* [Writing a Terraform provider](https://web.archive.org/web/20220516140659/http://blog.jfabre.net/2017/01/22/writing-terraform-provider/) - Guide for creating custom providers.
* [Writing Custom Providers](https://developer.hashicorp.com/terraform/plugin/sdkv2) - Official documentation for creating custom providers.
* [Terraform Provider Code generation](https://www.speakeasyapi.dev/docs/create-terraform) - Guide to generating a terraform provider from an OpenAPI specification (Vendor Supported)

### How-To

* [How To Write OPA for Terraform](https://www.scalr.com/blog/opa-series-part-1-open-policy-agent-and-terraform) - How to use Open Policy Agent to evaluate and enforce policy on your Terraform plans
* [Deploying Discourse with Terraform](https://www.hashicorp.com/en/blog/deploying-discourse-with-terraform) - Shows how Terraform can create a running instance of Discourse on DigitalOcean in one command.
* [Deploying Django to AWS ECS with Terraform](https://testdriven.io/blog/deploying-django-to-ecs-with-terraform/) - Looks at how to use Terraform to spin up the required AWS infrastructure for running a Django app on ECS.
* [Easily Deploy A Seneca Microservice to ECS with Wercker and Terraform: Part I](https://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-i/), [II](https://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-ii/) & [III](https://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-i/) - Illustrates how Terraform can be incorporated into a microservice deployment pipeline.
* [Terraform for a Highly Available VPN between AWS and Azure](https://web.archive.org/web/20210616132857/https://deployeveryday.com/2020/04/13/vpn-aws-azure-terraform.html) - Terraform code to deploy a highly available VPN between AWS and Azure.
* [Terraforming 1Password](https://blog.1password.com/terraforming-1password/) - How 1Password migrated from CloudFormation to Terraform.
* [Tutorial: How to Use Terraform to Deploy OpenStack Workloads](https://web.archive.org/web/20170611135511/http://www.stratoscale.com/blog/openstack/tutorial-how-to-use-terraform-to-deploy-openstack-workloads/) - Illustrates how easy it is to use the OpenStack Terraform provider to deploy a web server.
* [Zero Downtime Updates with HashiCorp Terraform](https://www.hashicorp.com/en/blog/zero-downtime-updates-with-terraform) - Ensuring zero downtime of your infrastructure.
* [Google Cloud Platform for 10$ a month using terraform](https://github.com/nufailtd/terraform-budget-gcp) ⭐ 48 | 🐛 0 | 🌐 HCL | 📅 2021-07-15 - Shows how to use terraform to create a secure Google Kubernetes Cluster, Google Cloud Run Services and other infrastructure elements for less than [10$](https://nufailtd.github.io/budget-gcp/) a month.
* [Infracost + Terraform + GitHub Actions = Automate Cloud Cost Management](https://medium.com/better-programming/infracost-terraform-github-actions-automate-cloud-cost-management-a62b329f2834) - How to use Infracost as the guardrail to manage cloud cost during Terraform development.
* [How To Wrap Your Terraform Provider for Pulumi](https://www.speakeasyapi.dev/post/pulumi-terraform-provider) - Making your terraform provider pulumi-ready

### Multi-Environment Configuration

* [Terraform Design Patterns: the Terrafile](https://bensnape.com/2016/01/14/terraform-design-patterns-the-terrafile/) - Managing Terraform modules and their versions within Terraform projects with Terrafile.
* [Terraform, VPC, and why you want a tfstate file per env](https://charity.wtf/2016/03/30/terraform-vpc-and-why-you-want-a-tfstate-file-per-env/) - Some gotchas surrounding using Terraform in large projects with multiple environments and how to avoid them.
* [Using Pipelines to Manage Environments with Infrastructure as Code](https://medium.com/@kief/https-medium-com-kief-using-pipelines-to-manage-environments-with-infrastructure-as-code-b37285a1cbf5) - Explains different approaches for building a pipeline to handle infrastructure changes moving from one environment to the next.

### Azure

* [Learning HashiCorp Terraform](https://web.archive.org/web/20201108000713/https://www.g10s.io/hashicorp-terraform/) - Guide for Azure.
* [New Terraform Azure Automation Resources](https://bgelens.nl/terraform-automation-resources/) - Azure Automation.
* [Terraforming Azure PaaS](https://devkimchi.com/2019/01/21/terraforming-azure-paas/) - Deploy PaaS Resources on Azure.

### AWS

* [AWS Lambda the Terraform Way](https://github.com/nsriram/lambda-the-terraform-way) ⭐ 1,264 | 🐛 1 | 🌐 Markdown | 📅 2021-05-08 - Understand AWS Lambda in-depth, beyond executing functions, using Terraform. Also includes guides for integration with S3, API Gateway, DynamoDB, Kinesis, SQS.
* [Managing AWS Lambda Functions with Terraform](https://spacelift.io/blog/terraform-aws-lambda) - What is AWS Lambda used for and how to use Terraform to manage AWS Lambda functions?

### Google Cloud

* [Managing infrastructure as code with Terraform, Cloud Build, and GitOps](https://cloud.google.com/docs/terraform/resource-management/managing-infrastructure-as-code) - Setup and manage infrastructure as code with Terraform, Cloud Build, and GitOps.
* [Getting started with Terraform on Google Cloud](https://cloud.google.com/docs/terraform/get-started-with-terraform) - Using Terraform to create a VM in Google Cloud and Starting a basic Python Flask server.
* [Managing Cloud Infrastructure with Terraform](https://www.cloudskillsboost.google/course_templates/746) - Deploy Kubernetes Load Balancer Service with Terraform, HTTPS Content-Based Load Balancer with Terraform, Modular Load Balancing with Terraform - Regional Load Balancer, Custom Providers with Terraform, Cloud SQL with Terraform, Building a VPN Between Google Cloud and AWS with Terraform.
* [Hashicorp Terraform Tutorials for Google Cloud](https://developer.hashicorp.com/terraform/tutorials/gcp-get-started) - Get started with Terraform on Google Cloud.
* [IAC - Terraform and Terragrunt on Google Cloud](https://www.academeez.com/courses/terraform) - Open source MIT Licensed course about creating infrastructure on Google Cloud using Terraform/OpenTofu and Terragrunt

### Miscellaneous

* [Sharing data between Terraform configurations](https://web.archive.org/web/20230927082422/https://jamesmckay.net/2016/09/sharing-data-between-terraform-configurations/) - Illustrates how to use remote state to share data between Terraform configurations.
* [The Segment AWS Stack](https://web.archive.org/web/20250322120753/https://segment.com/blog/the-segment-aws-stack/) - Shows the behind the scenes of the infrastructure powered by Terraform that solved [The Million Dollar Engineering Problem](https://segment.com/blog/the-million-dollar-eng-problem/) at [Segment](https://segment.com/).
* [Top 3 Terraform Testing Strategies for Ultra-Reliable Infrastructure-as-Code](https://www.contino.io/insights/top-3-terraform-testing-strategies-for-ultra-reliable-infrastructure-as-code)
* [Two Weeks with Terraform](https://charity.wtf/2016/02/23/two-weeks-with-terraform/) - Some hard-earned experience from using Terraform in the wild, and some operational wisdom.
* [Terraform: Beyond the Basics with AWS](https://aws.amazon.com/blogs/apn/terraform-beyond-the-basics-with-aws/) - Explanation of a demo using Terraform to provision a sample AWS architecture.
* [Terraform cost estimation](https://github.com/antonbabenko/terraform-cost-estimation) ⭐ 729 | 🐛 10 | 🌐 jq | 📅 2023-06-01 - Anonymized, free cost estimation from a Terraform plan (0.12+) or state file. Also available in the browser at [terraform-cost-estimation.com](https://terraform-cost-estimation.com).
* [How to Debug Terraform Projects: Tutorial](https://spacelift.io/blog/terraform-debug)

## Community Modules

For more Community Modules not listed here please see the [Terraform Module Registry](https://registry.terraform.io/).

* [terraform-aws-eks](https://github.com/terraform-aws-modules/terraform-aws-eks) ⭐ 4,922 | 🐛 12 | 🌐 HCL | 📅 2026-04-13 - Creates Elastic Kubernetes Service on AWS (very popular module).
* [terraform-aws-vpc](https://github.com/terraform-aws-modules/terraform-aws-vpc) ⭐ 3,220 | 🐛 26 | 🌐 HCL | 📅 2026-04-02 - Creates VPC resources on AWS (verified and very popular module).
* [segmentio/stack](https://github.com/segmentio/stack) ⚠️ Archived - Configures production infrastructure with AWS, Docker, and ECS. :skull:
* [typhoon](https://github.com/poseidon/typhoon) ⭐ 2,041 | 🐛 12 | 🌐 HCL | 📅 2026-03-30 - Minimal and free Kubernetes distribution with Terraform.
* [terraform-aws-secure-baseline](https://github.com/nozaq/terraform-aws-secure-baseline) ⭐ 1,196 | 🐛 31 | 🌐 HCL | 📅 2024-07-09 - Set up your AWS account with the secure baseline configuration based on CIS Amazon Web Services Foundations.
* [terraform-aws-lambda](https://github.com/terraform-aws-modules/terraform-aws-lambda) ⭐ 1,031 | 🐛 3 | 🌐 HCL | 📅 2026-03-26 - Terraform module, which builds dependencies and packages, and also creates AWS Lambda resources in countless combinations.
* [terraform-aws-rds](https://github.com/terraform-aws-modules/terraform-aws-rds) ⭐ 949 | 🐛 3 | 🌐 HCL | 📅 2026-03-27 - Creates RDS resources on AWS (verified module).
* [terraform-google-project-factory](https://github.com/terraform-google-modules/terraform-google-project-factory) ⭐ 943 | 🐛 17 | 🌐 HCL | 📅 2026-04-08 - Opinionated Google Cloud Platform project creation and configuration with Shared VPC, IAM, APIs, etc.
* [terraform-aws-ec2-instance](https://github.com/terraform-aws-modules/terraform-aws-ec2-instance) ⭐ 805 | 🐛 2 | 🌐 HCL | 📅 2026-03-26 - Creates EC2 instances on AWS.
* [terraform-kubestack](https://github.com/kbst/terraform-kubestack) ⭐ 708 | 🐛 21 | 🌐 HCL | 📅 2026-03-05 - Kubestack is a framework for Kubernetes platform engineering teams to define the entire cloud native stack in one Terraform code base and continuously evolve the platform safely through GitOps.
* [terraform-aws-ecs](https://github.com/terraform-aws-modules/terraform-aws-ecs) ⭐ 662 | 🐛 4 | 🌐 HCL | 📅 2026-03-18 - Creates AWS ECS resources on AWS.
* [terraform-aws-security-group](https://github.com/terraform-aws-modules/terraform-aws-security-group) ⭐ 590 | 🐛 3 | 🌐 HCL | 📅 2025-10-21 - Creates EC2-VPC security groups on AWS (verified module).
* [terraform-aws-s3-bucket](https://github.com/terraform-aws-modules/terraform-aws-s3-bucket) ⭐ 576 | 🐛 3 | 🌐 HCL | 📅 2026-04-02 - Creates S3 bucket resources on AWS.
* [terraform-aws-atlantis](https://github.com/terraform-aws-modules/terraform-aws-atlantis) ⭐ 551 | 🐛 1 | 🌐 HCL | 📅 2026-01-08 - Creates Terraform configurations for running [Atlantis](https://runatlantis.io) on AWS Fargate. Github, Gitlab, and BitBucket are supported.
* [terraform-aws-notify-slack](https://github.com/terraform-aws-modules/terraform-aws-notify-slack) ⭐ 493 | 🐛 1 | 🌐 Python | 📅 2026-03-11 - Creates SNS topic and Lambda function, which sends notifications to Slack.
* [terraform-aws-alb](https://github.com/terraform-aws-modules/terraform-aws-alb) ⭐ 463 | 🐛 0 | 🌐 HCL | 📅 2026-01-08 - Creates Application load-balancer on AWS (verified module).
* [terraform-aws-rds-aurora](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora) ⭐ 416 | 🐛 2 | 🌐 HCL | 📅 2026-03-18 - Creates RDS Aurora cluster resources on AWS (verified module).
* [terraform-nixos](https://github.com/nix-community/terraform-nixos) ⭐ 406 | 🐛 37 | 🌐 HCL | 📅 2024-08-04 - A set of Terraform modules that are designed to deploy NixOS.
* [terraform-aws-autoscaling](https://github.com/terraform-aws-modules/terraform-aws-autoscaling) ⭐ 311 | 🐛 0 | 🌐 HCL | 📅 2026-02-23 - Creates Auto-Scaling Groups and Launch Configurations (verified module).
* [terraform-aws-jenkins](https://github.com/cloudposse-archives/terraform-aws-jenkins) ⚠️ Archived - Build a Docker image with Jenkins, saves it to an ECR repo, and deploys it to Elastic Beanstalk running a Docker stack.
* [terraform-aws-ssh-bastion-service](https://github.com/joshuamkite/terraform-aws-ssh-bastion-service) ⭐ 212 | 🐛 0 | 🌐 HCL | 📅 2024-09-19 - Terraform plan to deploy ssh bastion as a stateless service on AWS.
* [terraform-aws-ecr](https://github.com/cloudposse/terraform-aws-ecr) ⭐ 190 | 🐛 9 | 🌐 HCL | 📅 2026-02-16 - Manages Docker container registries on AWS ECR.
* [tf\_aws\_bastion\_s3\_keys](https://github.com/terraform-community-modules/tf_aws_bastion_s3_keys) ⭐ 188 | 🐛 12 | 🌐 HCL | 📅 2023-03-30 - Creates bastion hosts on AWS EC2.
* [terraform-aws-transit-gateway](https://github.com/terraform-aws-modules/terraform-aws-transit-gateway) ⭐ 163 | 🐛 0 | 🌐 HCL | 📅 2026-03-05 - Creates Transit Gateway resources on AWS.
* [terraform-aws-eventbridge](https://github.com/terraform-aws-modules/terraform-aws-eventbridge) ⭐ 156 | 🐛 2 | 🌐 HCL | 📅 2026-01-08 - Creates EventBridge resources on AWS.
* [terraform-aws-key-pair](https://github.com/cloudposse/terraform-aws-key-pair) ⭐ 153 | 🐛 3 | 🌐 HCL | 📅 2025-10-01 - Automatically Generate SSH Key Pairs (Public/Private Keys).
* [terraform-aws-route53](https://github.com/terraform-aws-modules/terraform-aws-route53) ⭐ 153 | 🐛 0 | 🌐 HCL | 📅 2026-01-12 - Creates Route53 resources on AWS.
* [terraform-aws-elb](https://github.com/terraform-aws-modules/terraform-aws-elb) ⭐ 149 | 🐛 0 | 🌐 HCL | 📅 2025-03-29 - Creates Elastic load-balancer on AWS (verified module).
* [terraform-cloudflare-maintenance](https://github.com/adinhodovic/terraform-cloudflare-maintenance) ⭐ 128 | 🐛 4 | 🌐 HCL | 📅 2026-04-10 - Module to create a Maintenance Page using Cloudflare Workers.
* [terraform-aws-dynamodb-table](https://github.com/terraform-aws-modules/terraform-aws-dynamodb-table) ⭐ 118 | 🐛 5 | 🌐 HCL | 📅 2026-01-08 - Creates DynamoDB table on AWS.
* [terraform-aws-vpn-gateway](https://github.com/terraform-aws-modules/terraform-aws-vpn-gateway) ⭐ 117 | 🐛 3 | 🌐 HCL | 📅 2025-10-19 - Creates VPN gateway resources on AWS.
* [terraform-ecs-jenkins](https://github.com/shuaibiyy/terraform-ecs-jenkins) ⭐ 106 | 🐛 3 | 🌐 HCL | 📅 2017-10-08 - Provisions Jenkins on AWS ECS using Terraform.
* [terraform-aws-efs](https://github.com/cloudposse/terraform-aws-efs) ⭐ 95 | 🐛 8 | 🌐 HCL | 📅 2026-01-01 - Defines an EFS Filesystem.
* [terraform-aws-redshift](https://github.com/terraform-aws-modules/terraform-aws-redshift) ⭐ 88 | 🐛 0 | 🌐 HCL | 📅 2026-01-08 - Creates Redshift resources on AWS.
* [terraform-aws-postgresql-rds](https://github.com/azavea/terraform-aws-postgresql-rds) ⭐ 87 | 🐛 8 | 🌐 HCL | 📅 2023-06-20 - Creates PostgreSQL on RDS.
* [terraform-aws-dms](https://github.com/terraform-aws-modules/terraform-aws-dms) ⭐ 72 | 🐛 2 | 🌐 HCL | 📅 2025-10-21 - Creates AWS DMS (Database Migration Service) resources on AWS.
* [terraform-aws-datadog-forwarders](https://github.com/terraform-aws-modules/terraform-aws-datadog-forwarders) ⭐ 64 | 🐛 3 | 🌐 HCL | 📅 2026-01-08 - Creates resources on AWS to forward logs/metrics to Datadog.
* [terraform-aws-msk-kafka-cluster](https://github.com/terraform-aws-modules/terraform-aws-msk-kafka-cluster) ⭐ 63 | 🐛 1 | 🌐 HCL | 📅 2026-04-09 - Creates AWS MSK (Managed Streaming for Kafka) resources on AWS.
* [terraform-aws-rds-proxy](https://github.com/terraform-aws-modules/terraform-aws-rds-proxy) ⭐ 60 | 🐛 2 | 🌐 HCL | 📅 2026-01-15 - Creates AWS RDS Proxy resources on AWS.
* [terraform-static-website-s3-cloudfront](https://github.com/sjevs/terraform-static-website-s3-cloudfront) ⭐ 41 | 🐛 0 | 🌐 HCL | 📅 2016-11-04 - Creates static websites on AWS S3 & Cloudfront based on variables.
* [terraform-gce-atlantis](https://github.com/bschaatsbergen/terraform-gce-atlantis) ⭐ 37 | 🐛 15 | 🌐 HCL | 📅 2026-04-07 - Creates Terraform configurations for running [Atlantis](https://runatlantis.io) on Google Compute Engine.
* [terraform-aws-managed-service-prometheus](https://github.com/terraform-aws-modules/terraform-aws-managed-service-prometheus) ⭐ 33 | 🐛 0 | 🌐 HCL | 📅 2026-01-09 - Creates AWS Managed Service for Prometheus (AMP) resources on AWS.
* [terraform-aws-appconfig](https://github.com/terraform-aws-modules/terraform-aws-appconfig) ⭐ 29 | 🐛 0 | 🌐 HCL | 📅 2025-10-21 - Creates AWS AppConfig resources on AWS.
* [terraform-aws-lambda-auto-package](https://github.com/nozaq/terraform-aws-lambda-auto-package) ⭐ 28 | 🐛 3 | 🌐 HCL | 📅 2026-04-02 - A terraform module to define a lambda function which source files are automatically built and packaged for lambda deployment.
* [rancher-terraform-digitalocean](https://github.com/lunagt/rancher-terraform-digitalocean) ⭐ 24 | 🐛 0 | 🌐 HCL | 📅 2017-03-13 - Rancher server on digitalocean.
* [terraform-aws-customer-gateway](https://github.com/terraform-aws-modules/terraform-aws-customer-gateway) ⭐ 19 | 🐛 0 | 🌐 HCL | 📅 2025-10-21 - Creates Customer Gateway on AWS.
* [terraform-azurerm-sqlserver](https://github.com/metadevpro/terraform-azurerm-sqlserver-seed) ⭐ 9 | 🐛 2 | 🌐 HCL | 📅 2023-09-12 - Create SQl Server Database on Azure.
* [terraform-aws-jenkins-ha-agents](https://github.com/neiman-marcus/terraform-aws-jenkins-ha-agents) ⭐ 8 | 🐛 2 | 🌐 HCL | 📅 2024-03-06 - EC2 Based Jenkins deployment with HA (spot) agents. Runs on EFS for immutability. Fully customizable, with sensible defaults.
* [terraform-azurerm-iis](https://github.com/ghostinthewires/terraform-azurerm-iis-install) ⭐ 6 | 🐛 1 | 🌐 HCL | 📅 2019-01-08 - Install IIS Server on Azure VM instance.
* [terraform-aws-account-lookup](https://github.com/be-bold/terraform-aws-account-lookup) ⭐ 4 | 🐛 1 | 🌐 HCL | 📅 2026-03-05 - This Terraform module allows querying AWS accounts and outputs the accounts in various mappings or as a complete list, with the ability to apply a search filter to the account list and group the accounts by existing tags using a submodule.
* [nis2shield/infrastructure](https://github.com/nis2shield/infrastructure) ⭐ 2 | 🐛 0 | 🌐 HCL | 📅 2026-01-05 - Terraform modules for automated NIS2 compliance and secure infrastructure deployment.
* [terraform-azurerm-mysql](https://github.com/foreverXZC/terraform-azurerm-mysql) ⭐ 2 | 🐛 5 | 🌐 Go | 📅 2019-09-30 - Create MySql Database on Azure.
* [terraform-azurerm-redis](https://github.com/rahulkhengare/terraform-azurerm-redis) ⭐ 1 | 🐛 0 | 🌐 HCL | 📅 2018-06-22 - Create Redis on Azure.
* [terraform-azurerm-aks](https://github.com/kjanshair/terraform-azurerm-aks) ⭐ 0 | 🐛 0 | 🌐 HCL | 📅 2018-08-25 - Create AKS resources on Azure.
* [terraform-aws-modules](https://github.com/terraform-aws-modules) - Collection of Terraform AWS modules supported by the community (includes official AWS modules).
* [terraform-digitalocean-droplet](https://registry.terraform.io/modules/terraform-digitalocean-modules/droplet/digitalocean/latest) - Terraform module for managing DigitalOcean Droplets and related resources.
* [terraform-linode-k8s](https://registry.terraform.io/modules/linode/k8s/linode/latest) - Installs Kubernetes on Linode Instances.

## Self-Hosted Registries

* [citizen](https://github.com/outsideris/citizen) ⭐ 651 | 🐛 45 | 🌐 JavaScript | 📅 2024-10-12 - Private Terraform Module/Provider Registry
* [terralist](https://github.com/terralist/terralist) ⭐ 482 | 🐛 20 | 🌐 Go | 📅 2026-04-11 - Terraform Private Registry for modules and providers manageable from a REST API.
* [Terrareg](https://github.com/matthewjohn/terrareg) ⭐ 338 | 🐛 18 | 🌐 Python | 📅 2026-04-01 - Terraform module registry.
* [boring-registry](https://github.com/boring-registry/boring-registry) ⭐ 264 | 🐛 29 | 🌐 Go | 📅 2026-04-13 - Private Terraform Module/Provider Registry with API key authentication and blob storage support
* [tapir](https://github.com/PacoVK/tapir) ⭐ 237 | 🐛 28 | 🌐 Java | 📅 2026-04-13 - Private Terraform Registry.
* [anthology](https://github.com/erikvanbrakel/anthology) ⭐ 138 | 🐛 4 | 🌐 Go | 📅 2021-12-03 - Private Terraform registry implementation as an alternative to the official registry.
* [nrkno/terraform-registry](https://github.com/nrkno/terraform-registry) ⭐ 118 | 🐛 22 | 🌐 Go | 📅 2026-03-25 - A private Terraform registry with modular store backends.
* [philips-labs/terraform-registry](https://github.com/philips-labs/terraform-registry) ⭐ 106 | 🐛 5 | 🌐 Go | 📅 2026-02-11 - Terraform registry to serve arbitrary Terraform provider releases hosted on Github
* [terustry](https://github.com/veepee-oss/terustry) ⭐ 72 | 🐛 0 | 🌐 Rust | 📅 2024-08-13 - Open Source terraform provider registry acting as a proxy for gitlab or github releases.
* [terraform-simple-registry](https://github.com/apparentlymart/terraform-simple-registry) ⭐ 68 | 🐛 1 | 🌐 Go | 📅 2022-04-14 - Simple implementation of the Terraform registry protocols.
* [petra](https://github.com/devoteamgcloud/petra) ⭐ 45 | 🐛 10 | 🌐 Go | 📅 2024-06-06 - Private Terraform Registry Manager

## Managed Registries

* [cloudsmith](https://help.cloudsmith.io/docs/terraform-modules-repository) - Managed package hoster for internal and external clients. :heavy\_dollar\_sign:

## Providers

### Hashicorp supported providers

* [terraform-provider-aws](https://github.com/hashicorp/terraform-provider-aws) ⭐ 10,830 | 🐛 3,495 | 🌐 Go | 📅 2026-04-14 - Provider for Amazon Web Services.
* [terraform-provider-azurerm](https://github.com/hashicorp/terraform-provider-azurerm) ⭐ 4,921 | 🐛 3,810 | 🌐 Go | 📅 2026-04-13 - Provider for Azure.
* [terraform-provider-google](https://github.com/hashicorp/terraform-provider-google) ⭐ 2,601 | 🐛 2,439 | 🌐 Go | 📅 2026-04-14 - Provider for Google Cloud Platform.
* [terraform-provider-kubernetes](https://github.com/hashicorp/terraform-provider-kubernetes) ⭐ 1,710 | 🐛 177 | 🌐 Go | 📅 2026-03-19 - Provider for Kubernetes.
* [terraform-provider-helm](https://github.com/hashicorp/terraform-provider-helm) ⭐ 1,068 | 🐛 140 | 🌐 Go | 📅 2026-04-10 - Provider for Helm.
* [terraform-provider-vsphere](https://github.com/hashicorp/terraform-provider-vsphere) ⭐ 669 | 🐛 125 | 🌐 Go | 📅 2026-04-13 - Provider for VMware vSphere.
* [terraform-provider-docker](https://github.com/hashicorp/terraform-provider-docker) ⚠️ Archived - Provider for Docker. :skull:

### Vendor supported providers

* [terraform-provider-dominos](https://github.com/nat-henderson/terraform-provider-dominos) ⭐ 1,178 | 🐛 17 | 🌐 Go | 📅 2024-05-28 - Provider for Dominos Pizza.
* [terraform-provider-github](https://github.com/integrations/terraform-provider-github) ⭐ 1,115 | 🐛 320 | 🌐 Go | 📅 2026-04-13 - Provider for GitHub.
* [terraform-provider-keycloak](https://github.com/mrparkers/terraform-provider-keycloak) ⭐ 911 | 🐛 347 | 🌐 Go | 📅 2026-04-13 - Provider to manage the settings of your [Keycloak](https://www.keycloak.org/) identity provider server.
* [terraform-provider-hcloud](https://github.com/hetznercloud/terraform-provider-hcloud) ⭐ 701 | 🐛 63 | 🌐 Go | 📅 2026-04-13 - Provider for Hetzner Cloud.
* [terraform-provider-snowflake](https://github.com/Snowflake-Labs/terraform-provider-snowflake) ⭐ 673 | 🐛 286 | 🌐 Go | 📅 2026-04-13 - Provider for Snowflake data warehouse.
* [terraform-provider-alicloud](https://github.com/aliyun/terraform-provider-alicloud) ⭐ 653 | 🐛 654 | 🌐 Go | 📅 2026-04-14 - Provider for Alibaba Cloud.
* [terraform-provider-digitalocean](https://github.com/digitalocean/terraform-provider-digitalocean) ⭐ 561 | 🐛 167 | 🌐 Go | 📅 2026-04-13 - Provider for DigitalOcean.
* [terraform-provider-openstack](https://github.com/terraform-provider-openstack/terraform-provider-openstack) ⭐ 466 | 🐛 192 | 🌐 Go | 📅 2026-03-19 - Plugin for OpenStack.
* [terraform-provider-datadog](https://github.com/DataDog/terraform-provider-datadog) ⭐ 441 | 🐛 331 | 🌐 Go | 📅 2026-04-13 - Provider for Datadog.
* [terraform-provider-gitlab](https://github.com/gitlabhq/terraform-provider-gitlab) ⭐ 426 | 🐛 111 | 📅 2026-03-19 - Provider for GitLab.
* [terraform-provider-azuredevops](https://github.com/microsoft/terraform-provider-azuredevops) ⭐ 422 | 🐛 211 | 🌐 Go | 📅 2026-03-27 - Provider for Azure DevOps (VSTS).
* [terraform-provider-ibm](https://github.com/IBM-Cloud/terraform-provider-ibm) ⭐ 361 | 🐛 751 | 🌐 Go | 📅 2026-04-11 - Provider for IBM Cloud.
* [terraform-provider-iterative](https://github.com/iterative/terraform-provider-iterative) ⭐ 295 | 🐛 68 | 🌐 Go | 📅 2024-12-11 - Terraform plugin built with machine learning in mind.
* [terraform-provider-rancher2](https://github.com/rancher/terraform-provider-rancher2) ⭐ 291 | 🐛 146 | 🌐 Go | 📅 2026-04-09 - Provider for Rancher v2.
* [terraform-provider-artifactory](https://github.com/jfrog/terraform-provider-artifactory) ⭐ 286 | 🐛 60 | 🌐 Go | 📅 2026-04-08 - Provider for [JFrog Artifactory](https://jfrog.com/artifactory/).
* [terraform-provider-stripe](https://github.com/franckverrot/terraform-provider-stripe) ⭐ 245 | 🐛 20 | 🌐 Go | 📅 2023-08-14 - Provider for Stripe.
* [terraform-provider-azapi](https://github.com/Azure/terraform-provider-azapi) ⭐ 235 | 🐛 106 | 🌐 Go | 📅 2026-04-14 - Provider for Azure Resource Manager Rest API
* [terraform-provider-elasticstack](https://github.com/elastic/terraform-provider-elasticstack) ⭐ 204 | 🐛 189 | 🌐 Go | 📅 2026-04-14 - Provider for Elasticsearch and Kibana.
* [terraform-provider-spinnaker](https://github.com/armory-io/terraform-provider-spinnaker) ⭐ 143 | 🐛 15 | 🌐 Go | 📅 2024-03-14 - Provider for [Spinnaker](https://spinnaker.io/).
* [terraform-provider-k8s](https://github.com/banzaicloud/terraform-provider-k8s) ⭐ 135 | 🐛 23 | 🌐 Go | 📅 2022-09-08 - Simple Kubernetes Provider, works with any manifest.
* [terraform-provider-uptimerobot](https://github.com/louy/terraform-provider-uptimerobot) ⚠️ Archived - Provider to manage uptimerobot resources. :skull:
* [terraform-provider-pingdom](https://github.com/russellcardullo/terraform-provider-pingdom) ⚠️ Archived - Provider to manage Pingdom resources. :skull:
* [terraform-provider-panos](https://github.com/PaloAltoNetworks/terraform-provider-panos) ⭐ 109 | 🐛 150 | 🌐 Go | 📅 2026-04-09 - Provider for [Palo Alto Networks next-generation firewalls](https://www.paloaltonetworks.com/network-security).
* [terraform-provider-heroku](https://github.com/heroku/terraform-provider-heroku) ⭐ 103 | 🐛 41 | 🌐 Go | 📅 2026-04-09 - Provider for Heroku.
* [terraform-provider-ucloud](https://github.com/ucloud/terraform-provider-ucloud) ⭐ 72 | 🐛 24 | 🌐 Go | 📅 2026-03-11 - Provider to manage UCloud resources.
* [terraform-provider-linode](https://github.com/btobolaski/terraform-provider-linode) ⭐ 71 | 🐛 0 | 🌐 Go | 📅 2019-04-12 - Provider for Linode.
* [terraform-provider-healthchecksio](https://github.com/kristofferahl/terraform-provider-healthchecksio) ⭐ 70 | 🐛 2 | 🌐 Go | 📅 2026-03-19 - Provider to manage healthchecks.io resources.
* [terraform-provider-spotinst](https://github.com/spotinst/terraform-provider-spotinst) ⭐ 64 | 🐛 33 | 🌐 Go | 📅 2026-04-09 - Provider for spotinst.
* [terraform-provider-atlas](https://github.com/ariga/terraform-provider-atlas) ⭐ 63 | 🐛 15 | 🌐 Go | 📅 2026-02-09 - Provider for [Atlas](https://atlasgo.io/).
* [terraform-provider-buildkite](https://github.com/buildkite/terraform-provider-buildkite) ⭐ 60 | 🐛 12 | 🌐 Go | 📅 2026-04-13 - Provider for Buildkite.
* [terraform-provider-graphql](https://github.com/sullivtr/terraform-provider-graphql) ⭐ 59 | 🐛 6 | 🌐 Go | 📅 2026-01-22 - Provider for GraphQL queries and mutations.
* [terraform-provider-coder](https://github.com/coder/terraform-provider-coder) ⭐ 57 | 🐛 40 | 🌐 Go | 📅 2026-04-10 - Provider for [Coder](https://coder.com)
* [terraform-provider-confluent](https://github.com/confluentinc/terraform-provider-confluent) ⭐ 54 | 🐛 114 | 🌐 Go | 📅 2026-04-14 - Provider for Confluent.
* [terraform-provider-secrethub](https://github.com/secrethub/terraform-provider-secrethub) ⚠️ Archived - Provider for SecretHub. :skull:
* [terraform-provider-checkly](https://github.com/checkly/terraform-provider-checkly) ⭐ 43 | 🐛 8 | 🌐 Go | 📅 2026-04-10 - Manage [Checkly](https://www.checklyhq.com) resources for API & E2E monitoring.
* [terraform-provider-env0](https://github.com/env0/terraform-provider-env0) ⭐ 41 | 🐛 12 | 🌐 Go | 📅 2026-04-13 - Provider for [env0](https://www.env0.com/)
* [terraform-provider-vaulted](https://github.com/sumup-oss/terraform-provider-vaulted) ⭐ 39 | 🐛 11 | 🌐 Go | 📅 2026-02-05 - Encrypted HashiCorp Vault secrets via Terraform that can be stored in SCM such as Git.
* [terraform-provider-sigsci](https://github.com/signalsciences/terraform-provider-sigsci) ⭐ 27 | 🐛 13 | 🌐 Go | 📅 2026-03-19 - Provider for Signal Sciences.
* [terraform-provider-scp](https://github.com/splunk/terraform-provider-scp) ⭐ 23 | 🐛 19 | 🌐 Go | 📅 2026-03-05 - Provider for Splunk Cloud Platform.
* [terraform-provider-scalr](https://github.com/Scalr/terraform-provider-scalr) ⭐ 19 | 🐛 5 | 🌐 Go | 📅 2026-04-13 - Provider for [Scalr](https://www.scalr.com/)
* [terraform-provider-phare](https://github.com/phare/terraform-provider-phare) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2026-04-10 -  Terraform provider for [Phare](https://phare.io).

### Community providers

* [terraform-provider-proxmox](https://github.com/Telmate/terraform-provider-proxmox) ⭐ 2,878 | 🐛 130 | 🌐 Go | 📅 2026-04-13 - Terraform Proxmox provider.
* [terraform-provider-docker](https://github.com/kreuzwerker/terraform-provider-docker) ⭐ 793 | 🐛 42 | 🌐 Go | 📅 2026-04-14 - Terraform Docker provider.
* [terraform-provider-minio](https://github.com/aminueza/terraform-provider-minio) ⭐ 337 | 🐛 8 | 🌐 Go | 📅 2026-04-13 - Terraform provider for managing MinIO S3 buckets and IAM Users.
* [terraform-provider-terracurl](https://github.com/devops-rob/terraform-provider-terracurl) ⭐ 158 | 🐛 30 | 🌐 Go | 📅 2026-03-11 - Provider to make managed and unmanaged API calls to your target endpoint.
* [terraform-provider-value](https://github.com/pseudo-dynamic/terraform-provider-value) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2022-09-24 - Value Provider for Terraform.
* [terraform-provider-multipass](https://github.com/todoroff/terraform-provider-multipass) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2026-04-02 - Terraform provider for Multipass.
* [terraform-provider-plancost](https://github.com/plancost/terraform-provider-plancost) ⭐ 5 | 🐛 6 | 🌐 Go | 📅 2026-03-11 - Terraform provider for Azure cost estimation and cost guardrails.
* [terraform-provider-uname](https://github.com/julienlevasseur/terraform-provider-uname) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2026-01-27 - Uname Provider for Terraform.

## Testing

* [terratest](https://github.com/gruntwork-io/terratest) ⭐ 7,893 | 🐛 82 | 🌐 Go | 📅 2026-04-14 - Terratest is a Go library that makes it easier to write automated tests for your infrastructure code.
* [terraform-compliance](https://github.com/terraform-compliance/cli) ⭐ 1,446 | 🐛 95 | 🌐 Python | 📅 2025-12-08 - BDD Testing for Terraform Files.
* [kitchen-terraform](https://github.com/newcontext-oss/kitchen-terraform) ⚠️ Archived - Provides a set of Test Kitchen plugins which enable a system to use Test Kitchen to converge a Terraform configuration and verify the resulting Terraform state with InSpec controls. :skull:
* [terraform\_validate](https://github.com/elmundio87/terraform_validate) ⚠️ Archived - Assists in the enforcement of user-defined standards in Terraform. :skull:
* [clarity](https://github.com/xchapter7x/clarity) ⭐ 138 | 🐛 3 | 🌐 Go | 📅 2021-07-08 - A declarative test framework for Terraform for unit testing. :skull:
* [rspec-terraform](https://github.com/bsnape/rspec-terraform) ⭐ 92 | 🐛 2 | 🌐 Ruby | 📅 2015-09-10 - RSpec tests for your Terraform modules. :skull:

## Tools

* [terraform-bundle](https://github.com/hashicorp/terraform/tree/main/tools/terraform-bundle) ⭐ 48,133 | 🐛 1,891 | 🌐 Go | 📅 2026-04-13 - Easily builds bundles containing a Terraform binary as well as provider binaries. Useful for CI and air-gapped Terraform Enterprise.
* [terraformer](https://github.com/GoogleCloudPlatform/terraformer) ⚠️ Archived - CLI tool to generate terraform files from existing infrastructure. Infrastructure to Code. Supported many providers.
* [Infracost](https://github.com/infracost/infracost) ⭐ 12,264 | 🐛 125 | 🌐 Go | 📅 2026-04-13 - Cloud cost estimates for Terraform in your CLI and pull requests.
* [terragrunt](https://github.com/gruntwork-io/terragrunt) ⭐ 9,495 | 🐛 250 | 🌐 Go | 📅 2026-04-14 - Terragrunt is a thin wrapper for Terraform that provides extra tools for keeping your Terraform configurations DRY, working with multiple Terraform modules, and managing remote state.
* [atlantis](https://github.com/runatlantis/atlantis) ⭐ 8,996 | 🐛 894 | 🌐 Go | 📅 2026-04-14 - Unified workflow for collaborating on Terraform through GitHub.
* [Checkov](https://github.com/bridgecrewio/checkov/) ⭐ 8,623 | 🐛 153 | 🌐 Python | 📅 2026-04-13 - Terraform static analysis tool for terraform>=0.12
* [tfsec](https://github.com/aquasecurity/tfsec) ⭐ 6,981 | 🐛 15 | 🌐 Go | 📅 2026-03-25 - Terraform static analysis tool that supports terraform <0.12 & >=0.12 & directly integrates with HCL parser for better results.
* [tflint](https://github.com/terraform-linters/tflint) ⭐ 5,676 | 🐛 30 | 🌐 Go | 📅 2026-04-14 - Terraform linter for detecting errors that can not be detected by `terraform plan`
* [terrascan](https://github.com/tenable/terrascan) ⚠️ Archived - Collection of security and best practice test for static code analysis of terraform templates
* [terraform-cdk](https://github.com/hashicorp/terraform-cdk) ⚠️ Archived - CDK (Cloud Development Kit) for Terraform allows developers to use familiar programming languages to define cloud infrastructure and provision it through HashiCorp Terraform.
* [tfenv](https://github.com/tfutils/tfenv) ⭐ 4,907 | 🐛 66 | 🌐 Shell | 📅 2025-12-01 - Terraform version manager inspired by rbenv.
* [terraform-docs](https://github.com/terraform-docs/terraform-docs) ⭐ 4,745 | 🐛 179 | 🌐 Go | 📅 2026-04-13 - Quick utility to generate docs from terraform modules.
* [terraforming](https://github.com/dtan4/terraforming) ⚠️ Archived - Export existing AWS resources to Terraform style (tf, tfstate). Similar to `terraformer`. :skull:
* [AIaC](https://github.com/gofireflyio/aiac) ⭐ 3,791 | 🐛 2 | 🌐 Go | 📅 2026-03-24 - Artificial Intelligence Infrastructure-as-Code Generator
* [pre-commit-terraform](https://github.com/antonbabenko/pre-commit-terraform) ⭐ 3,691 | 🐛 28 | 🌐 Shell | 📅 2026-04-08 - pre-commit git hooks for Terraform and Terragrunt: auto-format, validate, update docs, run security checks, estimate costs, and more.
* [terramate](https://github.com/terramate-io/terramate) ⭐ 3,560 | 🐛 97 | 🌐 Go | 📅 2026-04-13 - Tool for managing multiple Terraform stacks that comes with support for change detection and code generation
* [rover](https://github.com/im2nguyen/rover) ⭐ 3,286 | 🐛 45 | 🌐 Go | 📅 2025-07-30 - Interactive Terraform state and configuration explorer.
* [driftctl](https://github.com/snyk/driftctl) ⭐ 2,634 | 🐛 150 | 🌐 Go | 📅 2026-04-09 - Detect, track, and alert on infrastructure drift :skull:
* [KICS](https://github.com/Checkmarx/kics) ⭐ 2,611 | 🐛 295 | 🌐 Open Policy Agent | 📅 2026-04-13 - Scans IaC projects for security vulnerabilities, compliance issues, and infrastructure misconfiguration. Currently working with Terraform projects, Kubernetes manifests, Dockerfiles, AWS CloudFormation Templates, and Ansible playbooks.
* [former2](https://github.com/iann0036/former2) ⭐ 2,394 | 🐛 181 | 🌐 JavaScript | 📅 2025-06-12 - Generate terraform configuration from your existing resources within your AWS account.
* [terracognita](https://github.com/cycloidio/terracognita) ⭐ 2,359 | 🐛 93 | 🌐 Go | 📅 2025-09-02 - Reads from existing Cloud Providers (reverse Terraform) and generates your infrastructure as code on Terraform configuration.
* [blast radius](https://github.com/28mm/blast-radius) ⭐ 2,185 | 🐛 47 | 🌐 JavaScript | 📅 2024-08-14 - Interactive visualizations of Terraform dependency graphs. :skull:
* [inframap](https://github.com/cycloidio/inframap) ⭐ 2,011 | 🐛 49 | 🌐 Go | 📅 2025-08-13 - Read your tfstate or HCL to generate a graph specific for each provider, showing only the resources that are most important/relevant.
* [terraboard](https://github.com/camptocamp/terraboard) ⭐ 2,006 | 🐛 19 | 🌐 Go | 📅 2026-04-14 - Web dashboard to inspect Terraform States.
* [aztfexport](https://github.com/Azure/aztfexport) ⭐ 1,885 | 🐛 46 | 🌐 Go | 📅 2026-04-02 - A tool to bring existing Azure resources under Terraform's management.
* [terraform-landscape](https://github.com/coinbase/terraform-landscape) ⭐ 1,625 | 🐛 33 | 🌐 Ruby | 📅 2024-03-20 - *(only 0.11 and earlier)* Improve Terraform's plan output to be easier to read and understand.
* [terravision](https://github.com/patrickchugh/terravision) ⭐ 1,462 | 🐛 12 | 🌐 Python | 📅 2026-04-12 - Generates professional cloud architecture diagrams from Terraform code using official AWS/Azure/GCP icons and design standards. Runs 100% client-side with CI/CD integration.
* [tenv](https://github.com/tofuutils/tenv) ⭐ 1,350 | 🐛 45 | 🌐 Go | 📅 2026-04-13 - OpenTofu/Terraform/Terragrunt version manager.
* [cf-terraforming](https://github.com/cloudflare/cf-terraforming) ⭐ 1,345 | 🐛 11 | 🌐 Go | 📅 2026-03-23 A command line utility to facilitate terraforming your existing Cloudflare resources.
* [atmos](https://github.com/cloudposse/atmos) ⭐ 1,281 | 🐛 241 | 🌐 Go | 📅 2026-04-14 - A universal tool that converts deep merged YAML to module inputs. :alien:
* [tftui](https://github.com/idoavrah/terraform-tui) ⭐ 1,277 | 🐛 11 | 🌐 Python | 📅 2024-07-09 - A textual user interface for Terraform state.
* [tfmigrate](https://github.com/minamijoyo/tfmigrate) ⭐ 1,262 | 🐛 23 | 🌐 Go | 📅 2025-12-22 - A Terraform state migration tool for GitOps.
* [k2tf](https://github.com/sl1pm4t/k2tf) ⭐ 1,228 | 🐛 28 | 🌐 Go | 📅 2025-12-12 - Kubernetes YAML to Terraform HCL converter.
* [layerform](https://github.com/briefercloud/layerform) ⚠️ Archived - Layerform helps engineers create reusable environment stacks using plain .tf files. Ideal for multiple "staging" environments. :skull:
* [gaia](https://github.com/gaia-app/gaia) ⭐ 1,074 | 🐛 75 | 🌐 Java | 📅 2023-03-30 - Gaia is a Terraform 🌍 UI for your modules, and self-service infrastructure 👨‍💻. :skull:
* [tfk8s](https://github.com/jrhouston/tfk8s) ⭐ 1,054 | 🐛 25 | 🌐 Go | 📅 2024-01-17 - A tool for converting Kubernetes YAML manifests to Terraform HCL
* [terratag](https://github.com/env0/terratag) ⭐ 1,047 | 🐛 5 | 🌐 Go | 📅 2026-03-26 - Terratag is a CLI tool that enables users of Terraform to automatically create and maintain tags across their entire set of AWS, Azure, and GCP resources.
* [yj](https://github.com/sclevine/yj) ⭐ 1,040 | 🐛 23 | 🌐 Go | 📅 2024-01-01 - CLI - Convert between YAML, TOML, JSON, and HCL. Preserves map order.
* [regula](https://github.com/fugue/regula) ⚠️ Archived - Evaluates Terraform infrastructure-as-code for potential AWS, Azure, and Google Cloud security misconfigurations and compliance violations prior to deployment.
* [yor](https://github.com/bridgecrewio/yor) ⭐ 922 | 🐛 10 | 🌐 Go | 📅 2026-04-10 - Automatically tag and trace infrastructure as code frameworks (Terraform, Cloudformation, and Serverless).
* [tfautomv](https://github.com/busser/tfautomv) ⭐ 890 | 🐛 16 | 🌐 Go | 📅 2026-04-09 - Generate Terraform `moved` blocks automatically for painless refactoring
* [pike](https://github.com/jamesWoolfenden/pike) ⭐ 889 | 🐛 8 | 🌐 Go | 📅 2026-04-12 - Pike calculates the permissions or IAM policy required to build your Terraform.
* [serverless.tf - Doing serverless with Terraform](https://serverless.tf/) - serverless.tf is an opinionated open-source framework for developing, building, deploying, and securing serverless applications and infrastructures on AWS using Terraform. [Read more](https://github.com/antonbabenko/serverless.tf) ⭐ 868 | 🐛 1 | 📅 2025-03-19.
* [AirIAM](https://github.com/bridgecrewio/AirIAM) ⭐ 822 | 🐛 35 | 🌐 Python | 📅 2025-03-18 - AirIAM is a tool for AWS IAM to least privilege Terraform execution framework.
* [iam-policy-json-to-terraform](https://github.com/flosell/iam-policy-json-to-terraform) ⭐ 819 | 🐛 13 | 🌐 JavaScript | 📅 2026-04-13 - Small tool to convert an IAM Policy in JSON format into a Terraform aws\_iam\_policy\_document
* [tads-boilerplate](https://github.com/Thomvaill/tads-boilerplate) ⚠️ Archived - The power of Ansible and Terraform + the simplicity of Docker Swarm = Infrastructure as Code and DevOps best practices.
* [aws2tf](https://github.com/aws-samples/aws2tf) ⭐ 744 | 🐛 0 | 🌐 Python | 📅 2026-04-11 - automates the importing of existing AWS resources into Terraform and outputs the Terraform HCL code.
* [terragrunt-atlantis-config](https://github.com/transcend-io/terragrunt-atlantis-config) ⭐ 737 | 🐛 87 | 🌐 HCL | 📅 2025-11-20 - Generate Atlantis config for Terragrunt projects.
* [tf-summarize](https://github.com/dineshba/tf-summarize) ⭐ 687 | 🐛 25 | 🌐 Go | 📅 2026-03-20 - A command-line utility to print the summary of the terraform plan
* [pug](https://github.com/leg100/pug) ⭐ 673 | 🐛 20 | 🌐 Go | 📅 2026-01-02 - The terminal user interface for terraform power users.
* [Terraform-Visual](https://github.com/hieven/terraform-visual) ⭐ 666 | 🐛 36 | 🌐 TypeScript | 📅 2023-10-26 - A simple but powerful tool to visualize Terraform plan.
* [tfupdate](https://github.com/minamijoyo/tfupdate) ⭐ 646 | 🐛 14 | 🌐 Go | 📅 2025-11-20 - Update version constraints in your Terraform configurations.
* [hcledit](https://github.com/minamijoyo/hcledit) ⭐ 535 | 🐛 21 | 🌐 Go | 📅 2025-04-10 - A command line editor for HCL.
* [tfcmt](https://github.com/suzuki-shunsuke/tfcmt) ⭐ 523 | 🐛 36 | 🌐 Go | 📅 2026-04-14 - CLI to notify the result of plan and apply as Pull Request comment.
* [json2hcl](https://github.com/kvz/json2hcl) ⚠️ Archived - Convert JSON to HCL and vice versa. :ghost:
* [hcl2json](https://github.com/tmccombs/hcl2json) ⭐ 474 | 🐛 10 | 🌐 Go | 📅 2026-04-04 - Convert hcl2 to json.
* [threatcl](https://github.com/threatcl/threatcl) ⭐ 457 | 🐛 15 | 🌐 Go | 📅 2026-04-12 - Documenting your Threat Models with HCL
* [terraform.py](https://github.com/mantl/terraform.py) ⚠️ Archived - Ansible dynamic inventory script for parsing Terraform state files. :skull:
* [astro](https://github.com/uber/astro/) ⭐ 436 | 🐛 23 | 🌐 Go | 📅 2023-03-19 - Astro is a tool for managing multiple Terraform executions as a single command. :ghost:
* [terraform-graph-beautifier](https://github.com/pcasteran/terraform-graph-beautifier) ⭐ 388 | 🐛 10 | 🌐 Go | 📅 2024-04-29 - Command line tool allowing to convert the barely usable output of the terraform graph command to something more meaningful and explanatory.
* [Shisho](https://github.com/flatt-security/shisho) ⚠️ Archived - Lightweight static analyzer for Terraform.
* [terraform-operator](https://github.com/GalleyBytes/terraform-operator) ⭐ 381 | 🐛 26 | 🌐 Go | 📅 2025-12-09 - A Kubernetes CRD to handle Terraform operations.
* [tfaction](https://github.com/suzuki-shunsuke/tfaction) ⭐ 380 | 🐛 65 | 🌐 TypeScript | 📅 2026-04-14 - GitHub Actions collection for Opinionated Terraform Workflow
* [terrahelp](https://github.com/opencredo/terrahelp) ⭐ 379 | 🐛 8 | 🌐 Go | 📅 2023-03-24 - Command line utility aimed at providing supplementary functionality which can sometimes prove useful when working with Terraform.
* [tfmcp](https://github.com/nwiizo/tfmcp) ⭐ 362 | 🐛 0 | 🌐 Rust | 📅 2026-03-26 - A CLI tool that helps you interact with Terraform via the Model Context Protocol (MCP), allowing AI assistants like Claude to manage and operate Terraform environments.
* [scenery](https://github.com/dmlittle/scenery) ⚠️ Archived - Another Terraform plan output prettifier. :ghost: :skull:
* [modules.tf-lambda](https://github.com/antonbabenko/modules.tf-lambda) ⭐ 356 | 🐛 15 | 🌐 Python | 📅 2021-08-20 - Infrastructure as code generator from visual diagrams created with [Cloudcraft.co](https://cloudcraft.co/app) to Terraform.
* [pipeform](https://github.com/magodo/pipeform) ⭐ 349 | 🐛 1 | 🌐 Go | 📅 2025-01-31 - Terraform runtime TUI
* [terraform-iam-policy-validator](https://github.com/awslabs/terraform-iam-policy-validator) ⭐ 346 | 🐛 15 | 🌐 Python | 📅 2025-06-09 - CLI validates AWS IAM Policies in a Terraform template against AWS IAM best practices.
* [terracost](https://github.com/cycloidio/terracost) ⭐ 338 | 🐛 22 | 🌐 Go | 📅 2025-11-24 - Cloud cost estimation for Terraform in your CLI.
* [terraform-aws-clickops-notifier](https://github.com/cloudandthings/terraform-aws-clickops-notifier) ⭐ 332 | 🐛 24 | 🌐 Python | 📅 2026-04-09 - Get notified when actions are taken in the AWS Console.
* [tfschema](https://github.com/minamijoyo/tfschema) ⭐ 314 | 🐛 4 | 🌐 Go | 📅 2025-04-10 - Schema inspector for Terraform providers.
* [fogg](https://github.com/chanzuckerberg/fogg) ⭐ 307 | 🐛 4 | 🌐 Go | 📅 2026-04-09 - A tool for eliminating toil in managing terraform repositories.
* [tfscaffold](https://github.com/tfutils/tfscaffold) ⭐ 282 | 🐛 12 | 🌐 HCL | 📅 2025-02-12 - Framework for controlling multi-environment multi-component terraform-managed AWS infrastructure.
* [tftarget](https://github.com/future-architect/tftarget) ⭐ 274 | 🐛 13 | 🌐 Go | 📅 2024-12-24 - CLI Tool to do `terraform xxx -target={...}` interactively.
* [asdf](https://github.com/asdf-community/asdf-hashicorp) ⭐ 263 | 🐛 15 | 🌐 Shell | 📅 2026-01-01 - HashiCorp plugin for the [asdf](https://github.com/asdf-vm/asdf) ⭐ 25,257 | 🐛 176 | 🌐 Go | 📅 2026-04-13 version manager
* [tfsort](https://github.com/AlexNabokikh/tfsort) ⭐ 237 | 🐛 14 | 🌐 Go | 📅 2025-10-01 - CLI utility to sort Terraform variables and outputs.
* [validIaC](https://github.com/gofireflyio/validiac) ⭐ 235 | 🐛 14 | 🌐 TypeScript | 📅 2025-05-08 - ValidIaC combines the best open-source tools to help ensure Terraform best practices, hygiene & security.
* [tfvar](https://github.com/shihanng/tfvar) ⭐ 230 | 🐛 4 | 🌐 Go | 📅 2026-03-11 - tfvar scans your Terraform configurations or modules and extracts the variables into formats of your choice (tfvar, environment variables, etc.) for editing.
* [tofuenv](https://github.com/tofuutils/tofuenv) ⭐ 225 | 🐛 21 | 🌐 Shell | 📅 2026-02-10 - OpenTofu version manager inspired by tfenv
* [terrahub](https://github.com/tfxor/terrahub) ⭐ 224 | 🐛 19 | 🌐 Twig | 📅 2022-04-16 - TerraHub is terraform automation and orchestration tool. Seamlessly integrated into console.terrahub.io, enterprise friendly GUI to show realtime terraform executions, as well as auditing and reporting capabilities for historical terraform runs. :heavy\_dollar\_sign:
* [tfmask](https://github.com/cloudposse-archives/tfmask) ⚠️ Archived - Terraform utility to mask select output from `terraform plan` and `terraform apply`
* [stacks](https://github.com/cisco-open/stacks) ⭐ 189 | 🐛 5 | 🌐 Python | 📅 2026-03-29 - Stacks, the Terraform code pre-processor
* [prettyplan](https://github.com/chrislewisdev/prettyplan) ⭐ 187 | 🐛 1 | 🌐 TypeScript | 📅 2019-10-08 - Prettyplan ([available online here](https://chrislewisdev.github.io/prettyplan/)) is a small tool to help you view large Terraform plans with ease. :ghost:
* [terraform-cleaner](https://github.com/sylwit/terraform-cleaner) ⭐ 183 | 🐛 3 | 🌐 Go | 📅 2023-03-31 - Tiny utility which detects unused variables in your terraform modules.
* [tfjson](https://github.com/palantir/tfjson) ⚠️ Archived - Utility to read in a Terraform plan file and dump it out in JSON. :skull:
* [tf-profile](https://github.com/datarootsio/tf-profile/) ⭐ 165 | 🐛 5 | 🌐 Go | 📅 2025-03-15 - Profiler for Terraform runs. Generate global stats, resource-level stats or visualizations.
* [tfmv](https://github.com/suzuki-shunsuke/tfmv) ⭐ 158 | 🐛 6 | 🌐 Go | 📅 2026-03-31 - Rename Terraform resources and generate moved blocks
* [tftree](https://github.com/busser/tftree) ⭐ 158 | 🐛 7 | 🌐 Go | 📅 2026-04-14 - Display your Terraform module call stack in your terminal.
* [terraform-plan-parser](https://github.com/lifeomic/terraform-plan-parser) ⭐ 156 | 🐛 13 | 🌐 TypeScript | 📅 2026-04-02 - Command line utility and JavaScript API for parsing stdout from `terraform plan` and converting it to JSON. :ghost:
* [terraformize](https://github.com/naorlivne/terraformize) ⚠️ Archived - Apply\Destroy Terraform modules via a simple REST API endpoint. :skull:
* [redc](https://github.com/wgpsec/redc) ⭐ 144 | 🐛 1 | 🌐 Go | 📅 2026-03-17 - Next-generation red team infrastructure automation tool built on Terraform, supporting multi-cloud deployment (Alibaba Cloud, Tencent Cloud, AWS, etc.) with one-command deployment for creating, configuring, and destroying red team environments.
* [coretech/terrafile](https://github.com/coretech/terrafile) ⚠️ Archived - Systematically manage external modules from Github for use in Terraform (written in Go). :skull:
* [tfproviderlint](https://github.com/bflad/tfproviderlint) ⭐ 139 | 🐛 85 | 🌐 Go | 📅 2025-05-08 - Terraform Provider Lint Tool.
* [cfnctl](https://github.com/rogerwelin/cfnctl) ⭐ 135 | 🐛 5 | 🌐 Go | 📅 2024-01-19 - Cfnctl brings the Terraform cli experience to AWS Cloudformation.
* [terraform-repl](https://github.com/paololazzari/terraform-repl) ⭐ 134 | 🐛 3 | 🌐 Shell | 📅 2024-11-30 - A terraform console wrapper for a better interactive console experience.
* [terrars](https://github.com/andrewbaxter/terrars) ⭐ 114 | 🐛 3 | 🌐 Rust | 📅 2024-07-21 - Terrars is a tool for building Terraform stacks in Rust. This is an alternative to the CDK.
* [ruby-terraform](https://github.com/infrablocks/ruby_terraform) ⭐ 112 | 🐛 4 | 🌐 Ruby | 📅 2026-04-13 - Simple Ruby wrapper for invoking terraform commands.
* [tgf](https://github.com/coveooss/tgf) ⭐ 110 | 🐛 5 | 🌐 Go | 📅 2026-04-14 - Terragrunt frontend for executing Terragrunt/Terraform through Docker.
* [sato](https://github.com/JamesWoolfenden/sato) ⭐ 109 | 🐛 1 | 🌐 Go | 📅 2026-04-02 - Sato helps you convert your legacy Cloudformation into Terraform.
* [pretf](https://github.com/raymondbutcher/pretf) ⭐ 105 | 🐛 19 | 🌐 Python | 📅 2022-08-11 - drop-in Terraform wrapper that generates Terraform configuration with Python. See [pretf documentation](https://pretf.readthedocs.io/en/latest/) :skull:
* [tfedit](https://github.com/minamijoyo/tfedit) ⭐ 103 | 🐛 3 | 🌐 Go | 📅 2025-04-10 - A refactoring tool for Terraform.
* [hclgrep](https://github.com/magodo/hclgrep) ⭐ 97 | 🐛 1 | 🌐 Go | 📅 2024-03-07 - Syntax based grep for HCL(v2).
* [tfgen](https://github.com/refl3ction/tfgen) ⭐ 90 | 🐛 7 | 🌐 Go | 📅 2025-11-11 - Terraform code generator for consistent codebase and DRY.
* [tfprovidercheck](https://github.com/suzuki-shunsuke/tfprovidercheck) ⭐ 88 | 🐛 9 | 🌐 Go | 📅 2026-04-12 - CLI to prevent malicious Terraform Providers from being executed
* [tpm](https://github.com/Madh93/tpm) ⭐ 85 | 🐛 3 | 🌐 Go | 📅 2025-08-21 - A package manager for Terraform providers.
* [terrastate](https://github.com/rohinivsenthil/terrastate) ⭐ 77 | 🐛 2 | 🌐 TypeScript | 📅 2021-12-08 - Visual Studio Code extension to monitor/deploy/destroy Terraform resources in your workspace
* [tau](https://github.com/avinor/tau) ⚠️ Archived - Tau is a thin wrapper on top of terraform to manage multiple deployments, dependencies, and secrets. :skull:
* [tfgpt](https://github.com/flavius-dinu/tfgpt) ⭐ 74 | 🐛 1 | 🌐 Go | 📅 2023-04-01 - A CLI tool that integrates Terraform with OpenAI's GPT-3.5 Turbo to provide explanations for Terraform commands and concepts.
* [terraform-diff](https://github.com/contentful-labs/terraform-diff) ⭐ 70 | 🐛 0 | 🌐 Go | 📅 2025-09-18 - Always know where you need to run Terraform plan & apply!
* [terraformsh](https://github.com/pwillis-els/terraformsh) ⭐ 69 | 🐛 5 | 🌐 Shell | 📅 2026-03-16 - A wrapper in Bash for easier CLI UX and DRY hierarchical configs
* [travelgrunt](https://github.com/ivanilves/travelgrunt) ⭐ 69 | 🐛 4 | 🌐 Go | 📅 2025-10-04 - cd inside \[mono]repos without fatigue!
* [tfocus](https://github.com/nwiizo/tfocus) ⭐ 68 | 🐛 0 | 🌐 Rust | 📅 2025-01-19 - tfocus is a super interactive tool for selecting and executing Terraform plan/apply on specific resources. Think of it as an "emergency tool" - not for everyday use.
* [terrap-cli](https://github.com/sirrend/terrap-cli) ⭐ 66 | 🐛 1 | 🌐 Go | 📅 2023-12-05 - Terrap - a powerful CLI tool that scans your infrastructure and identifies any required changes.
* [xterrafile](https://github.com/devopsmakers/xterrafile) ⚠️ Archived Systematically manage external modules from the module registry, git, or local directories for use in Terraform (written in Go). :skull:
* [TerraDepot](https://github.com/derBroBro/TerraDepot) ⭐ 65 | 🐛 2 | 🌐 Python | 📅 2020-02-15 Terraform state repository, based on the default http remote backend. Allows the central administration of tfstates on AWS S3.
* [hcledit](https://github.com/mercari/hcledit) ⭐ 62 | 🐛 13 | 🌐 Go | 📅 2024-09-04 - Go package to edit HCL configuration
* [para](https://github.com/paraterraform/para) ⭐ 58 | 🐛 0 | 🌐 Go | 📅 2019-09-09 - The missing 3rd-party plugin manager and a "Swiss army knife" for Terraform/Terragrunt - just 1 tool to facilitate all workflows. :skull:
* [pytest-terraform](https://github.com/cloud-custodian/pytest-terraform) ⭐ 57 | 🐛 6 | 🌐 Python | 📅 2026-04-08 - pytest terraform plugin with fixtures and offline replay support.
* [renovate-config](https://github.com/SpotOnInc/renovate-config) ⭐ 53 | 🐛 3 | 📅 2026-04-07 - Sharable Config Presets for Renovatebot, especially useful for DevOps folks.
* [drifthound](https://github.com/treezio/drifthound) ⭐ 49 | 🐛 14 | 🌐 Ruby | 📅 2026-03-06 - Continuous infrastructure drift detection with historical tracking and notifications.
* [terramagic](https://github.com/miltlima/terramagic) ⭐ 48 | 🐛 0 | 🌐 Python | 📅 2026-03-10 - Wizard tool for create folders and terraform files automated, written in Python !
* [tfreveal](https://github.com/breml/tfreveal) ⭐ 47 | 🐛 0 | 🌐 Go | 📅 2026-04-10 - A Terraform utility to show Terraform plans with all the secret (sensitive) values revealed.
* [tfvaultenv](https://github.com/oulman/tfvaultenv) ⭐ 47 | 🐛 4 | 🌐 Go | 📅 2024-01-29 - tfvaultenv reads secrets from HashiCorp Vault and outputs environment variables for various Terraform providers with those secrets.
* [cloud-audit](https://github.com/gebalamariusz/cloud-audit) ⭐ 42 | 🐛 5 | 🌐 Python | 📅 2026-04-07 - AWS security auditing CLI with remediation engine that generates Terraform code for fixing misconfigurations.
* [python-terrafile](https://github.com/claranet/python-terrafile) ⭐ 38 | 🐛 3 | 🌐 Python | 📅 2019-10-17 - Systematically manage external modules from Github for use in Terraform.
* [terraboot](https://github.com/MastodonC/terraboot) ⭐ 38 | 🐛 0 | 🌐 Clojure | 📅 2018-03-19 - DSL to generate a terraform configuration and run it.
* [fuzzy-terraform-rm](https://github.com/paololazzari/fuzzy-terraform-rm) ⭐ 36 | 🐛 0 | 🌐 Go | 📅 2023-11-21 - A fuzzy-finder command-line tool for removing resources from terraform state.
* [terraeasy](https://github.com/jaceq/terraeasy) ⭐ 35 | 🐛 1 | 🌐 Shell | 📅 2024-11-18 - Easy Terraform wrapper
* [tfmigrator](https://github.com/tfmigrator/cli) ⚠️ Archived - Go library and CLI to migrate Terraform Configuration and State
* [scratchrelaxtv](https://github.com/YakDriver/scratchrelaxtv) ⭐ 34 | 🐛 14 | 🌐 Python | 📅 2023-03-13 - Simple Python tool to help with module development - extract vars from `main.tf` to generate `variables.tf` and make module usage stub from `variables.tf`.
* [prettyplan for TF 0.12+](https://github.com/cloudandthings/terraform-pretty-plan) ⭐ 33 | 🐛 6 | 🌐 Vue | 📅 2022-08-27 - Prettyplan for TF 0.12+ ([available online here](https://cloudandthings.github.io/terraform-pretty-plan/)) is a small tool to help you view large Terraform plans with ease. :ghost:
* [tfrepl](https://github.com/ysoftwareab/tfrepl) ⭐ 32 | 🐛 0 | 🌐 Shell | 📅 2023-06-11 - A Terraform REPL, giving you a full shell experience. Readline based. No dependencies. Save config changes. History.
* [tfmake](https://github.com/tfmake/tfmake) ⭐ 29 | 🐛 0 | 🌐 Shell | 📅 2025-06-29 - Automating Terraform with the power of make.
* [terrascope](https://github.com/spilliams/terrascope) ⭐ 27 | 🐛 48 | 🌐 Go | 📅 2026-04-12 - Build orchestrator for terraform monorepos.
* [flora](https://github.com/ketchoop/flora) ⭐ 26 | 🐛 11 | 🌐 Go | 📅 2022-10-07 - Terraform version manager.
* [trupositive](https://github.com/trupositive-ai/trupositive) ⭐ 15 | 🐛 3 | 🌐 Shell | 📅 2026-02-27 - Zero-config wrapper that automatically injects Git metadata (commit SHA, branch, repo) into all Terraform-managed resources.
* [terraform-provisioner](https://github.com/shuaibiyy/terraform-provisioner) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2017-08-06 - Tool for managing multiple provisions of the same Terraform scripts.
* [hq](https://github.com/miller-time/hq) ⭐ 9 | 🐛 2 | 🌐 Rust | 📅 2025-03-23 - command-line HCL processor
* [hcldump](https://github.com/magodo/hcldump) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2021-12-27 - Dump the HCL (v2) abstract syntax tree.
* [tf-init-booster](https://github.com/hayorov/terraform-init-booster) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2023-10-10 - A Pre-terraform routine that speedups terraform modules download for bulky blueprints.
* [tfwrapper](https://github.com/manheim/tfwrapper) ⭐ 8 | 🐛 0 | 🌐 Ruby | 📅 2021-01-15 - Rubygem providing rake tasks for running Hashicorp Terraform sanely.
* [terraform-credentials-vault](https://github.com/oulman/terraform-credentials-vault) ⭐ 5 | 🐛 1 | 🌐 Go | 📅 2023-06-09 - A Terraform "credentials helper" plugin that allows providing credentials for Terraform-native services (private module registries, Terraform Cloud, etc) via environment variables.
* [terraform-rake-tasks](https://github.com/gina-alaska/terraform-rake-tasks) ⭐ 4 | 🐛 0 | 🌐 Ruby | 📅 2017-08-18 - Shared Rake tasks for managing terraform plans.
* [zephy](https://github.com/henrybravo/zephy) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2025-10-15 - Compare Azure resources deployed in a subscription against resources managed by Terraform Enterprise (HCP & Selfhosted) workspaces *when your cloud's resource tagging strategy is insufficient*.
* [dxw/terrafile](https://github.com/dxw/terrafile) ⭐ 2 | 🐛 5 | 🌐 Ruby | 📅 2026-03-19 - Systematically manage external modules from Github for use in Terraform (written in Ruby).
* [terradozer](https://github.com/chenrui333/terradozer) ⭐ 1 | 🐛 14 | 🌐 Go | 📅 2026-03-01 - Terraform destroy without configuration files.
* [terraform-ai-skills](https://github.com/anmolnagpal/terraform-ai-skills) ⭐ 1 | 🐛 0 | 🌐 Markdown | 📅 2026-03-20 - AI-powered skill for GitHub Copilot, Claude, and ChatGPT that automates bulk Terraform module management — provider upgrades, workflow standardization, and releases across 10–200+ repositories on AWS, GCP, Azure, and DigitalOcean.
* [Argonaut](https://www.argonaut.dev/) - Deploy apps and infrastructure on your cloud in minutes. Autogenerate Terraform modules, customize configurations through PRs. Support for app deployments on Kubernetes and Lambda environments.
* [balcony](https://oguzhan-yilmaz.github.io/balcony/) - CLI tool for easy AWS API reads. Also generates Terraform import-blocks, and actual Terraform Resource code.
* [burrito](https://padok-team.github.io/burrito/) - Burrito is a TACoS (Terraform Automation Collaboration Software) Kubernetes Operator.
* [Coder](https://coder.com/) - Coder provisions software development environments on your infrastructure via Terraform.
* [InfraScan](https://infrascan.soldevelo.com) - Advanced Infrastructure Auditor for cost and security analysis of Terraform, AWS, and Kubernetes.
* [library.tf](https://library.tf) - Library.tf is built and designed to not just provide you with all of the registry information for Terraform and OpenTofu but to provide all of the insights you need to make decisions. Quickly find modules or providers that are supported and maintained and not full of bugs.
* [pluralith](https://www.pluralith.com/) - Terraform state visualization and automated generation of infrastructure documentation. :heavy\_dollar\_sign:
* [Riftmap](https://riftmap.dev) - Cross-repo dependency and change impact engine that scans multi-repo infrastructure across Terraform, Docker, Helm, and more to visualize what depends on what and what breaks when something changes.
* [ReleaseRun Terraform Provider Matrix](https://releaserun.com/tools/terraform-provider-matrix/) - Free browser tool to check Terraform provider version compatibility across Terraform and OpenTofu versions.
* [ReleaseRun Terraform Security Scanner](https://releaserun.com/tools/terraform-security/) - Free browser-based scanner for `.tf` files. Checks hardcoded credentials, open ports to 0.0.0.0/0, public S3/RDS, unencrypted storage, missing deletion\_protection. A-F grade. No install required.
* [Speakeasy](https://www.speakeasyapi.dev/) - Generate a terraform provider from an OpenAPI specification.
* [Styra Declarative Authorization Service (DAS)](https://www.styra.com/terraform-cloud-config-management-with-styra-das-and-open-policy-agent) - Provides a managed [Open Policy Agent (OPA)](https://www.openpolicyagent.org) platform for Application and Infrastructure use cases, including Terraform, Terraform Cloud, and Kubernetes. Enforce policy guardrails during development, in CI/CD pipelines, and at deploy time. Styra DAS Free provides multiple systems and users, policy impact analysis, decision logging and replay, and access to Styra's Terraform policy library.
* [terracove](https://elementtech.github.io/terracove/) - Recursively test a directory tree for Terraform diffs and coverage.
* [terrashine](https://isawan.github.io/terrashine/) - Terrashine is a terraform provider mirror1 implementation that works by automatically caching dependencies as providers are requested.
* [terraspace](https://terraspace.cloud) - The Terraform Framework

### CI

* [setup-terraform](https://github.com/hashicorp/setup-terraform) ⭐ 1,558 | 🐛 70 | 🌐 JavaScript | 📅 2026-04-13 - Sets up Terraform CLI in your GitHub Actions workflow.
* [terraform-plan](https://github.com/cds-snc/terraform-plan) ⭐ 64 | 🐛 14 | 🌐 JavaScript | 📅 2026-04-13 - GitHub Action to run Terraform plan and add a comment with the changes.

### IDE

* [vscode-terraform-live-graph](https://github.com/adamiBs/vscode-terraform-live-graph) ⭐ 238 | 🐛 16 | 🌐 TypeScript | 📅 2023-06-12 - Terraform Live Graph Extension for Visual Studio Code is a plugin that allows you to generate a live Terraform graph as you code.
* [tf-nav](https://marketplace.visualstudio.com/items?itemName=owenrumney.tf-nav) - Terraform Navigation Extension to created an index of resources by type of file with an easy to navigate treeview.

## Libraries

* [pyhcl](https://github.com/virtuald/pyhcl) ⭐ 340 | 🐛 12 | 🌐 Python | 📅 2026-01-20 - HCL parser in Python
* [python-hcl2](https://github.com/amplify-education/python-hcl2/) ⭐ 304 | 🐛 7 | 🌐 Python | 📅 2026-04-10 - HCL2 parser in Python
* [hcl-rs](https://github.com/martinohmann/hcl-rs) ⭐ 175 | 🐛 6 | 🌐 Rust | 📅 2026-04-02 - HCL parsing and encoding libraries for rust with serde support
* [tree-sitter-hcl](https://github.com/tree-sitter-grammars/tree-sitter-hcl) ⭐ 137 | 🐛 7 | 🌐 HCL | 📅 2026-01-17 - HCL grammar for tree-sitter
* [hcl4j](https://github.com/bertramdev/hcl4j) ⭐ 74 | 🐛 12 | 🌐 Java | 📅 2025-08-28 - HCL parser in Java
* [rhcl](https://github.com/winebarrel/rhcl) ⚠️ Archived - Pure Ruby HCL parser :skull:
* [nu\_plugin\_hcl](https://github.com/Yethal/nu_plugin_hcl) ⭐ 14 | 🐛 0 | 🌐 Rust | 📅 2026-04-13 - HCL parser plugin for [Nushell](https://github.com/nushell/nushell) ⭐ 39,037 | 🐛 1,490 | 🌐 Rust | 📅 2026-04-14

## Boilerplates

* [Terraform Generator](https://github.com/sudokar/generator-tf-module) ⭐ 274 | 🐛 7 | 🌐 JavaScript | 📅 2024-05-02 - Scaffolding for a new terraform module or project with support of test frameworks (terratest and kitchen-terraform)
* [Terraform GitOps Framework](https://www.kubestack.com) - Everything you need to build reliable automation for AKS, EKS, and GKE Kubernetes clusters in one free and open-source framework.

## Self-hosted Terraform Platforms

* [Burrito](https://github.com/padok-team/burrito) ⭐ 708 | 🐛 62 | 🌐 Go | 📅 2026-04-13 - TACoS Kubernetes Operator - "ArgoCD for Terraform"
* [OTF](https://github.com/leg100/otf) ⭐ 664 | 🐛 9 | 🌐 Go | 📅 2026-04-09 - Open Terraforming Framework, an open source alternative to Terraform Enterprise with full Terraform CLI integration.
* [Lynx](https://github.com/clivern/lynx) ⭐ 366 | 🐛 21 | 🌐 Elixir | 📅 2026-04-10 - Fast, Secure and Reliable Terraform Backend. It has a user-friendly dashboard, project and environment management, state versioning, locking and snapshots support.
* [Stack-Lifecycle-Deployment](https://github.com/D10S0VSkY-OSS/Stack-Lifecycle-Deployment) ⭐ 262 | 🐛 19 | 🌐 CSS | 📅 2026-04-14 - OpenSource solution that defines and manages the complete lifecycle of resources used and provisioned into a cloud.
* [cloud-concierge](https://github.com/dragondrop-cloud/cloud-concierge) ⭐ 246 | 🐛 41 | 🌐 Go | 📅 2025-10-19 - Open Source, codify unmanaged resources as Terraform, detect drift, and cloud cost and security analysis, delivered as a Pull Request.
* [Terrakube](https://docs.terrakube.io) - Open Source alternative to Terraform Enterprise with private registry, remote state, custom flows, scheduled workspaces, and visual states.
* [Digger](https://digger.dev) - Open Source Alternative to Terraform Cloud - Run Terraform plan & apply jobs in your CI.
* [Terrateam](https://terrateam.io) - Open-source alternative to Terraform Cloud/Enterprise, GitOps-first with native GitHub integration and designed for scale, security, and reliability.

## Managed Terraform Platforms :heavy\_dollar\_sign:

* [compliance.tf](https://compliance.tf) - Terraform modules with SOC 2, PCI DSS, HIPAA, NIST 800-53, and 35+ other frameworks built in. Non-compliant configs fail at `terraform plan` before anything applies. :heavy\_dollar\_sign:
* [ControlMonkey](https://www.controlmonkey.io/) - Alternative to Terraform Cloud with Terraform/OpenTofu code generation, cloud inventory and IaC coverage. Includes out-of-the-box policies, drift remediation, and a ClickOps activity scanner. :heavy\_dollar\_sign:
* [Firefly](https://www.firefly.ai/) - Alternative to Terraform Cloud by leveraging your CI tool. Firefly platform also scans your cloud to asses the IaC coverage & drift detection. :heavy\_dollar\_sign:
* [Scalr](https://www.scalr.com/) - Alternative to Terraform Enterprise with OPA integration, organizational structure, custom hooks, native integrations with other DevOps platforms, and centralized reporting. :heavy\_dollar\_sign:
* [Stategraph](https://stategraph.com) - Terraform and OpenTofu without the state file bottleneck. Replace the flat state file with a real database. Teams plan in parallel, state is queryable via SQL, and plans run in seconds instead of minutes. :heavy\_dollar\_sign:
* [env0](https://www.env0.com/) - Alternative to Terraform Cloud/Enterprise with OPA integration, custom flows and Terragrunt support :heavy\_dollar\_sign:
* [Brainboard](https://www.brainboard.co) - Visually Design, Deploy & Manage modern cloud infrastructures starting from any Cloud Provider - AWS, GCP, Azure :heavy\_dollar\_sign:
* [Spacelift](https://spacelift.io/) - Alternative to Terraform Cloud/Enterprise. Collaborative Infrastructure Delivery Platform for Terraform :heavy\_dollar\_sign:

## Terraform Enterprise Tooling

* [tfe-state-explorer](https://github.com/segment-boneyard/tfe-state-explorer) ⚠️ Archived - Simple shell for exploring remote terraform enterprise state, with autocomplete. :skull:
* [terraform-enterprise-migrator](https://github.com/silinternational/tfc-ops) ⭐ 13 | 🐛 2 | 🌐 Go | 📅 2026-03-30 - Script for migrating Terraform Enterprise environments from Legacy to new version of Terraform Enterprise.
* [terraform-enterprise-cli](https://github.com/skierkowski/terraform-enterprise-cli) ⭐ 12 | 🐛 10 | 🌐 Ruby | 📅 2018-05-23 - Terraform Enterprise Command Line Interface.
* [terraform-enterprise-client](https://github.com/skierkowski/terraform-enterprise-client) ⭐ 8 | 🐛 1 | 🌐 Ruby | 📅 2018-05-27 - Terraform Enterprise API Ruby Client and Command Line tool.

## Videos

* [Your Weekly Dose of Terraform](https://bit.ly/terraform-youtube) - YouTube channel with weekly live streams covering Terraform news, reviews, interviews, Q\&A, live coding, and some hacking with Terraform.
* [Terraform explained in 15 mins](https://www.youtube.com/watch?v=l5k1ai_GBDE) - Terraform explained in 15 mins.
* [Terraform Course](https://www.youtube.com/watch?v=SLB_c_ayRMo) - Automate your AWS cloud infrastructure.
* [How to Build Reusable, Composable, Battle tested Terraform Modules](https://www.youtube.com/watch?v=LVgP63BkhKQ) - Yevgeniy Brikman talks about how to write Terraform code so that it is reusable, composable and testable. The presentation focuses on Terraform modules but also provides a brief and clear explanation of what problem Terraform was created to solve and a short demo of Terraform basics (\~39 min, October 2017).
* [Building Scalable, Repeatable Infrastructure in the Cloud with Terraform](https://www.youtube.com/watch?v=cG7pcksTAnY) - Demonstrates how Terraform enables the practice of Infrastructure as Code by deploying TeamCity in AWS using a hosted PostgreSQL.
* [Creating a Google Compute Instance with Terraform](https://www.youtube.com/watch?v=fo3VX33Zx0c) - Example of creating a Google Compute Instance with Terraform code.
* [Creating a Terraform Provider for Just About Anything](https://www.hashicorp.com/resources/creating-terraform-provider-for-anything) - Learn how to contribute to a Terraform provider or create your own from this walkthrough.
* [Evolving Your Infrastructure with Terraform](https://www.youtube.com/watch?v=wgzgVm7Sqlk) - CTO of OpenCredo provides an extensive look at using Terraform in the real-world with the help of some interesting use-cases.
* [Going Multi-Cloud with Terraform and Nomad](https://www.youtube.com/watch?v=e42A4aBZUkQ).
* [How to Extend the Terraform Provider List](https://www.youtube.com/watch?v=2BvpqmFpchI) - In this talk, Paul will walk through the creation of a terraform provider.
* [Orchestrating Containers with Terraform and Consul](https://www.infoq.com/presentations/terraform-consul/) - Mitchell Hashimoto shows how Terraform can be used to deploy and scale containerized workloads.
* [Production ChaosMonkey with Terraform](https://www.youtube.com/watch?v=CPI6W3LK0-g) - How DigitalOcean uses Terraform to run production integration tests.
* [Running a Terraform Environment at Scale](https://www.youtube.com/watch?v=3JVGSq7QIS0) - Running Terraform at scale with hundreds of AWS accounts.
* [Setup Continuous Integration for a Terraform module](https://www.youtube.com/watch?v=vuJ6bjYKUcA) - Example of using CI with Kitchen-Terraform to test, tag and publish our Terraform module, which creates a Google Compute Instance.
* [State of Terraform Providerland](https://www.youtube.com/watch?v=ar1PF5iDtbg) - How Terraform providers work and how to write one.
* [Terraform At Scale](https://www.youtube.com/watch?v=RldRDryLiXs) - How Segment uses Terraform.
* [Terraform w/ Lee Trout](https://www.youtube.com/watch?v=p2ESyuqPw1A) - Focuses on development patterns and how to effectively structure Terraform code.
* [Terraforming the Composable World](https://www.youtube.com/watch?v=cHrOXPatFeg) - Integrating Terraform with an on-premise bare metal provisioning.
* [Test and verify a Google Compute Instance with Kitchen-Terraform](https://www.youtube.com/watch?v=kiH3-LEveek) - Example of using Kitchen-Terraform to test our Terraform code that creates a Google Compute.
* [Untangling Terraform Through Refactoring](https://www.youtube.com/watch?v=OH6iDKaXpZs) - How to refactor your Terraform code in a careful way with minimum risk.
* [Complete Terraform Course - From BEGINNER to PRO! (Learn Infrastructure as Code)](https://www.youtube.com/watch?v=7xngnjfIlK4) - Complete course from beginner to pro, with no cloud provider focus, with a general approach

## Editor Plugins

* [Terraform-ls](https://github.com/hashicorp/terraform-ls) ⭐ 1,169 | 🐛 252 | 🌐 Go | 📅 2026-04-10 (Terraform Language Server)
* [Vim-Terraform](https://github.com/hashivim/vim-terraform) ⭐ 1,110 | 🐛 5 | 🌐 Vim Script | 📅 2025-05-24
* [Terraform-lsp](https://github.com/juliosueiras/terraform-lsp) ⭐ 588 | 🐛 25 | 🌐 Go | 📅 2023-03-06 (Language Server Protocol for Terraform)
* [Vim-Terraform-Completion](https://github.com/juliosueiras/vim-terraform-completion) ⭐ 338 | 🐛 18 | 🌐 Vim script | 📅 2022-03-04
* [Emacs terraform-mode](https://github.com/hcl-emacs/terraform-mode) ⭐ 238 | 🐛 8 | 🌐 Emacs Lisp | 📅 2025-11-15
* [vim-hcl](https://github.com/jvirtanen/vim-hcl) ⭐ 143 | 🐛 1 | 🌐 Vim Script | 📅 2025-01-10 - Syntax highlighting for HCL
* [Intellij](https://plugins.jetbrains.com/plugin/7808-terraform-and-hcl)
* [VS Code](https://marketplace.visualstudio.com/items?itemName=hashicorp.terraform)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Shuaib Yunus has waived all copyright and related or neighboring rights to this work.
