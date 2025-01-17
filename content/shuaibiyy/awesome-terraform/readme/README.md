# Awesome Terraform Overview

Curated list of resources on HashiCorp's Terraform

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/shuaibiyy/awesome-terraform/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 shuaibiyy/awesome-terraform](https://github.com/shuaibiyy/awesome-terraform) · ⭐ 4.8K · 🏷️ Back-End Development

[ [Daily](/content/shuaibiyy/awesome-terraform/README.md) / [Weekly](/content/shuaibiyy/awesome-terraform/week/README.md) / Overview ]

---

# Awesome Terraform [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) <!-- omit in toc -->

> A curated list of resources on [HashiCorp's Terraform](https://www.terraform.io/).
> [<img src="https://rawgit.com/shuaibiyy/awesome-terraform/master/terraform.svg" align="right" width="100">](https://terraform.io)
> Your [contributions (⭐4.7k)](https://github.com/shuaibiyy/awesome-terraform/blob/master/contributing.md) are welcome!

Terraform enables you to safely and predictably create, change, and improve production infrastructure. It is an open source tool that codifies APIs into declarative configuration files that can be shared amongst team members, treated as code, edited, reviewed, and versioned.

## Contents <!-- omit in toc -->

*   [Legend](#legend)
*   [Official Resources](#official-resources)
*   [Community](#community)
*   [Books](#books)
*   [Tutorials and Blog Posts](#tutorials-and-blog-posts)
    *   [Beginner Guides](#beginner-guides)
    *   [Writing Custom Providers](#writing-custom-providers)
    *   [How-To](#how-to)
    *   [Multi-Environment Configuration](#multi-environment-configuration)
    *   [Azure](#azure)
    *   [AWS](#aws)
    *   [Google Cloud](#google-cloud)
    *   [Miscellaneous](#miscellaneous)
*   [Community Modules](#community-modules)
*   [Private Registries](#private-registries)
*   [Providers](#providers)
    *   [Hashicorp supported providers](#hashicorp-supported-providers)
    *   [Vendor supported providers](#vendor-supported-providers)
    *   [Community providers](#community-providers)
*   [Testing](#testing)
*   [Tools](#tools)
    *   [CI](#ci)
    *   [IDE](#ide)
*   [Libraries](#libraries)
*   [Boilerplates](#boilerplates)
*   [Terraform Enterprise](#terraform-enterprise)
*   [Videos](#videos)
*   [Editor Plugins](#editor-plugins)
*   [License](#license)

## Legend

*   Not compatible with *terraform >= 0.12* :ghost:
*   Abandoned :skull:
*   Monetized :heavy\_dollar\_sign:

## Official Resources

*   [Hashicorp Terraform Blog](https://www.hashicorp.com/blog/products/terraform)
*   [Introduction to Terraform](https://www.terraform.io/intro/)
*   [Terraform Documentation](https://www.terraform.io/docs/)
*   [Terraform learn](https://learn.hashicorp.com/terraform/)

## Community

*   [weekly.tf - Terraform Weekly Newsletter](https://weekly.tf) - Various news in the Terraform world (projects, announcements, discussions).
*   [Complete Terraform documentation as PDF files (Updated nightly) (⭐191)](https://github.com/antonbabenko/terraform-docs-as-pdf)
*   [Terraform AWS Modules](https://github.com/terraform-aws-modules) + [meta-configurations repository (⭐73)](https://github.com/terraform-aws-modules/meta)
*   [Terraform Bug Tracker (⭐39k)](https://github.com/hashicorp/terraform/issues)
*   [Terraform Community Modules](https://github.com/terraform-community-modules)
*   [Terraform Twitter Community](https://twitter.com/i/communities/1501688565884928007) <!-- markdown-link-check-disable-line -->
*   [Terraform Discuss](https://discuss.hashicorp.com/c/terraform-core/27)
*   [Terraform Provider/Module Registry](https://registry.terraform.io/)
*   [Terraform PDF Doc (⭐57)](https://github.com/dohsimpson/terraform-doc-pdf) :skull:
*   [Terragrunt Reference Architecture (⭐357)](https://github.com/antonbabenko/terragrunt-reference-architecture)
*   Language-specific communities:
    *   [Telegram (Ukrainian speak community)](https://t.me/terraform_ukraine)

## Books

*   [Big Little Book On Terraform](https://www.amazon.com/Big-Little-Book-Terraform-Omos-ebook/dp/B07PWYPNX8/)
*   [Bootstrapping Microservices with Docker, Kubernetes, and Terraform, Second Editon](https://www.manning.com/books/bootstrapping-microservices-with-docker-kubernetes-and-terraform-second-edition)
*   [Deep-Dive Terraform on Azure](https://link.springer.com/book/10.1007/978-1-4842-7328-9)
*   [Getting Started with Terraform, 2nd ed.](https://www.amazon.com/Getting-Started-Terraform-production-infrastructure/dp/1788623533/)
*   [HashiCorp Infrastructure Automation Certification Guide](https://www.amazon.com/HashiCorp-Infrastructure-Automation-Certification-Guide-ebook/dp/B092KM7LXC/)
*   [Infrastructure as Code](http://shop.oreilly.com/product/0636920039297.do)
*   [Patterns and Practices for Infrastructure as Code: With examples in Python and Terraform](https://www.manning.com/books/patterns-and-practices-for-infrastructure-as-code)
*   [Terraform Best Practices](https://www.terraform-best-practices.com/) - [open-source ebook (⭐1.8k)](https://github.com/antonbabenko/terraform-best-practices)
*   [Terraform Cookbook](https://www.amazon.com/Terraform-Cookbook-Efficiently-Infrastructure-platforms/dp/1800207557)
*   [Terraform in Action](https://www.manning.com/books/terraform-in-action)
*   [Terraform: Up & Running, 3rd ed.](https://www.terraformupandrunning.com/)
*   [The Terraform Book](https://terraformbook.com/)
*   [IaC starting with Terraform(Korean)](https://product.kyobobook.co.kr/detail/S000202478097)

## Tutorials and Blog Posts

### Beginner Guides

*   [A Comprehensive Guide to Terraform](https://blog.gruntwork.io/a-comprehensive-guide-to-terraform-b3d32832baca#.w9x897ywp) - Series of blog posts from the author of "Terraform: Up & Running" that guide the reader from beginning with Terraform to using it in the real world.
*   [Using Terraform for Cloud Deployments - Part 1](https://dev.to/koenighotze/using-terraform-for-cloud-deployments---part-1) - Provisioning an EC2 instance.
*   [Hello, world: The Fargate/Terraform tutorial I wish I had](https://section411.com/2019/07/hello-world/) - Blog post describing setting up an ECS Fargate cluster from scratch
*   [Terraform Security Guide](https://sysdig.com/blog/terraform-security-best-practices/) - Blog post describing security best practices when working with Terraform
*   [Building a SaaS API? Don't Forget Your Terraform Provider](https://www.speakeasyapi.dev/post/build-terraform-providers) - Why you should write a terraform provider

### Writing Custom Providers

*   [Creating custom terraform providers](https://medium.com/@jozmo/creating-custom-terraform-providers-341311823fa2) - Guide for creating custom providers.
*   [Writing a Terraform provider](https://web.archive.org/web/20220516140659/http://blog.jfabre.net/2017/01/22/writing-terraform-provider/) - Guide for creating custom providers.
*   [Writing Custom Providers](https://www.terraform.io/docs/extend/writing-custom-providers.html) - Official documentation for creating custom providers.
*   [Terraform Provider Code generation](https://www.speakeasyapi.dev/docs/create-terraform) - Guide to generating a terraform provider from an OpenAPI specification (Vendor Supported)

### How-To

*   [How To Write OPA for Terraform](https://www.scalr.com/blog/opa-series-part-1-open-policy-agent-and-terraform/) - How to use Open Policy Agent to evaluate and enforce policy on your Terraform plans
*   [Deploying Discourse with Terraform](https://web.archive.org/web/20181001135342/http://www.hashicorp.com/blog/deploying-discourse-with-terraform) - Shows how Terraform can create a running instance of Discourse on DigitalOcean in one command.
*   [Deploying Django to AWS ECS with Terraform](https://testdriven.io/blog/deploying-django-to-ecs-with-terraform/) - Looks at how to use Terraform to spin up the required AWS infrastructure for running a Django app on ECS.
*   [Easily Deploy A Seneca Microservice to ECS with Wercker and Terraform: Part I](http://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-i/), [II](http://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-ii/) & [III](http://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-i/) - Illustrates how Terraform can be incorporated into a microservice deployment pipeline.
*   [Terraform for a Highly Available VPN between AWS and Azure](https://web.archive.org/web/20210616132857/https://deployeveryday.com/2020/04/13/vpn-aws-azure-terraform.html) - Terraform code to deploy a highly available VPN between AWS and Azure.
*   [Terraforming 1Password](https://blog.agilebits.com/2018/01/25/terraforming-1password/) - How 1Password migrated from CloudFormation to Terraform.
*   [Tutorial: How to Use Terraform to Deploy OpenStack Workloads](https://web.archive.org/web/20170611135511/http://www.stratoscale.com/blog/openstack/tutorial-how-to-use-terraform-to-deploy-openstack-workloads/) - Illustrates how easy it is to use the OpenStack Terraform provider to deploy a web server.
*   [Zero Downtime Updates with HashiCorp Terraform](https://www.hashicorp.com/blog/zero-downtime-updates-with-terraform) - Ensuring zero downtime of your infrastructure.
*   [Google Cloud Platform for 10$ a month using terraform (⭐37)](https://github.com/nufailtd/terraform-budget-gcp) - Shows how to use terraform to create a secure Google Kubernetes Cluster, Google Cloud Run Services and other infrastructure elements for less than [10$](https://nufailtd.github.io/budget-gcp/) a month.
*   [Infracost + Terraform + GitHub Actions = Automate Cloud Cost Management](https://betterprogramming.pub/infracost-terraform-github-actions-automate-cloud-cost-management-a62b329f2834?sk=495131c5831bc9276369150da5f3bc2c) - How to use Infracost as the guardrail to manage cloud cost during Terraform development.
*   [How To Wrap Your Terraform Provider for Pulumi](https://www.speakeasyapi.dev/post/pulumi-terraform-provider) - Making your terraform provider pulumi-ready

### Multi-Environment Configuration

*   [Terraform Design Patterns: the Terrafile](http://bensnape.com/2016/01/14/terraform-design-patterns-the-terrafile/) - Managing Terraform modules and their versions within Terraform projects with Terrafile.
*   [Terraform, VPC, and why you want a tfstate file per env](https://charity.wtf/2016/03/30/terraform-vpc-and-why-you-want-a-tfstate-file-per-env/) - Some gotchas surrounding using Terraform in large projects with multiple environments and how to avoid them.
*   [Using Pipelines to Manage Environments with Infrastructure as Code](https://medium.com/@kief/https-medium-com-kief-using-pipelines-to-manage-environments-with-infrastructure-as-code-b37285a1cbf5) - Explains different approaches for building a pipeline to handle infrastructure changes moving from one environment to the next.

### Azure

*   [Learning HashiCorp Terraform](https://web.archive.org/web/20201108000713/https://www.g10s.io/hashicorp-terraform/) - Guide for Azure.
*   [New Terraform Azure Automation Resources](https://bgelens.nl/terraform-automation-resources/) - Azure Automation.
*   [Terraforming Azure PaaS](https://devkimchi.com/2019/01/21/terraforming-azure-paas/) - Deploy PaaS Resources on Azure.

### AWS

*   [AWS Lambda the Terraform Way (⭐1.2k)](https://github.com/nsriram/lambda-the-terraform-way) - Understand AWS Lambda in-depth, beyond executing functions, using Terraform. Also includes guides for integration with S3, API Gateway, DynamoDB, Kinesis, SQS.
*   [Managing AWS Lambda Functions with Terraform](https://spacelift.io/blog/terraform-aws-lambda) - What is AWS Lambda used for and how to use Terraform to manage AWS Lambda functions?

### Google Cloud

*   [Managing infrastructure as code with Terraform, Cloud Build, and GitOps](https://cloud.google.com/architecture/managing-infrastructure-as-code) - Setup and manage infrastructure as code with Terraform, Cloud Build, and GitOps.
*   [Getting started with Terraform on Google Cloud](https://cloud.google.com/community/tutorials/getting-started-on-gcp-with-terraform) - Using Terraform to create a VM in Google Cloud and Starting a basic Python Flask server.
*   [Managing Cloud Infrastructure with Terraform](https://www.cloudskillsboost.google/quests/44) - Deploy Kubernetes Load Balancer Service with Terraform, HTTPS Content-Based Load Balancer with Terraform, Modular Load Balancing with Terraform - Regional Load Balancer, Custom Providers with Terraform, Cloud SQL with Terraform, Building a VPN Between Google Cloud and AWS with Terraform.
*   [Hashicorp Terraform Tutorials for Google Cloud](https://learn.hashicorp.com/collections/terraform/gcp-get-started) - Get started with Terraform on Google Cloud.

### Miscellaneous

*   [Sharing data between Terraform configurations](https://jamesmckay.net/2016/09/sharing-data-between-terraform-configurations/) - Illustrates how to use remote state to share data between Terraform configurations.
*   [The Segment AWS Stack](https://segment.com/blog/the-segment-aws-stack/) - Shows the behind the scenes of the infrastructure powered by Terraform that solved [The Million Dollar Engineering Problem](https://segment.com/blog/the-million-dollar-eng-problem/) at [Segment](https://segment.com/).
*   [Top 3 Terraform Testing Strategies for Ultra-Reliable Infrastructure-as-Code](https://www.contino.io/insights/top-3-terraform-testing-strategies-for-ultra-reliable-infrastructure-as-code)
*   [Two Weeks with Terraform](https://charity.wtf/2016/02/23/two-weeks-with-terraform/) - Some hard-earned experience from using Terraform in the wild, and some operational wisdom.
*   [Terraform: Beyond the Basics with AWS](https://aws.amazon.com/blogs/apn/terraform-beyond-the-basics-with-aws/) - Explanation of a demo using Terraform to provision a sample AWS architecture.
*   [Terraform cost estimation (⭐641)](https://github.com/antonbabenko/terraform-cost-estimation) - Anonymized, secure, and free Terraform cost estimation based on Terraform plan (0.12+) or Terraform state (any version).
*   [How to Debug Terraform Projects: Tutorial](https://spacelift.io/blog/terraform-debug)

## Community Modules

For more Community Modules not listed here please see the [Terraform Module Registry](https://registry.terraform.io/).

*   [rancher-terraform-digitalocean (⭐23)](https://github.com/lunagt/rancher-terraform-digitalocean) - Rancher server on digitalocean.
*   [segmentio/stack (⭐2.1k)](https://github.com/segmentio/stack) - Configures production infrastructure with AWS, Docker, and ECS.
*   [terraform-aws-alb (⭐397)](https://github.com/terraform-aws-modules/terraform-aws-alb) - Creates Application load-balancer on AWS (verified module).
*   [terraform-aws-appconfig (⭐23)](https://github.com/clowdhaus/terraform-aws-appconfig) - Creates AWS AppConfig resources on AWS.
*   [terraform-aws-atlantis (⭐482)](https://github.com/terraform-aws-modules/terraform-aws-atlantis) - Creates Terraform configurations for running [Atlantis](https://runatlantis.io) on AWS Fargate. Github, Gitlab, and BitBucket are supported.
*   [terraform-aws-autoscaling (⭐268)](https://github.com/terraform-aws-modules/terraform-aws-autoscaling) - Creates Auto-Scaling Groups and Launch Configurations (verified module).
*   [terraform-aws-customer-gateway (⭐16)](https://github.com/terraform-aws-modules/terraform-aws-customer-gateway) - Creates Customer Gateway on AWS.
*   [terraform-aws-datadog-forwarders (⭐49)](https://github.com/clowdhaus/terraform-aws-datadog-forwarders) - Creates resources on AWS to forward logs/metrics to Datadog.
*   [terraform-aws-dms (⭐50)](https://github.com/clowdhaus/terraform-aws-dms) - Creates AWS DMS (Database Migration Service) resources on AWS.
*   [terraform-aws-dynamodb-table (⭐89)](https://github.com/terraform-aws-modules/terraform-aws-dynamodb-table) - Creates DynamoDB table on AWS.
*   [terraform-aws-ec2-instance (⭐684)](https://github.com/terraform-aws-modules/terraform-aws-ec2-instance) - Creates EC2 instances on AWS.
*   [terraform-aws-ecr (⭐165)](https://github.com/cloudposse/terraform-aws-ecr) - Manages Docker container registries on AWS ECR.
*   [terraform-aws-ecs (⭐431)](https://github.com/terraform-aws-modules/terraform-aws-ecs) - Creates AWS ECS resources on AWS.
*   [terraform-aws-efs (⭐80)](https://github.com/cloudposse/terraform-aws-efs) - Defines an EFS Filesystem.
*   [terraform-aws-eks (⭐3.8k)](https://github.com/terraform-aws-modules/terraform-aws-eks) - Creates Elastic Kubernetes Service on AWS (very popular module).
*   [terraform-aws-elb (⭐139)](https://github.com/terraform-aws-modules/terraform-aws-elb) - Creates Elastic load-balancer on AWS (verified module).
*   [terraform-aws-eventbridge (⭐119)](https://github.com/terraform-aws-modules/terraform-aws-eventbridge) - Creates EventBridge resources on AWS.
*   [terraform-aws-jenkins-ha-agents (⭐8)](https://github.com/neiman-marcus/terraform-aws-jenkins-ha-agents) - EC2 Based Jenkins deployment with HA (spot) agents. Runs on EFS for immutability. Fully customizable, with sensible defaults.
*   [terraform-aws-jenkins (⭐252)](https://github.com/cloudposse/terraform-aws-jenkins) - Build a Docker image with Jenkins, saves it to an ECR repo, and deploys it to Elastic Beanstalk running a Docker stack.
*   [terraform-aws-key-pair (⭐146)](https://github.com/cloudposse/terraform-aws-key-pair) - Automatically Generate SSH Key Pairs (Public/Private Keys).
*   [terraform-aws-lambda-auto-package (⭐27)](https://github.com/nozaq/terraform-aws-lambda-auto-package) - A terraform module to define a lambda function which source files are automatically built and packaged for lambda deployment.
*   [terraform-aws-lambda (⭐736)](https://github.com/terraform-aws-modules/terraform-aws-lambda) - Terraform module, which builds dependencies and packages, and also creates AWS Lambda resources in countless combinations.
*   [terraform-aws-managed-service-prometheus (⭐21)](https://github.com/clowdhaus/terraform-aws-managed-service-prometheus) - Creates AWS Managed Service for Prometheus (AMP) resources on AWS.
*   [terraform-aws-modules](https://github.com/terraform-aws-modules) - Collection of Terraform AWS modules supported by the community (includes official AWS modules).
*   [terraform-aws-msk-kafka-cluster (⭐38)](https://github.com/clowdhaus/terraform-aws-msk-kafka-cluster) - Creates AWS MSK (Managed Streaming for Kafka) resources on AWS.
*   [terraform-aws-notify-slack (⭐438)](https://github.com/terraform-aws-modules/terraform-aws-notify-slack) - Creates SNS topic and Lambda function, which sends notifications to Slack.
*   [terraform-aws-postgresql-rds (⭐84)](https://github.com/azavea/terraform-aws-postgresql-rds) - Creates PostgreSQL on RDS.
*   [terraform-aws-rds-aurora (⭐356)](https://github.com/terraform-aws-modules/terraform-aws-rds-aurora) - Creates RDS Aurora cluster resources on AWS (verified module).
*   [terraform-aws-rds-proxy (⭐49)](https://github.com/clowdhaus/terraform-aws-rds-proxy) - Creates AWS RDS Proxy resources on AWS.
*   [terraform-aws-rds (⭐793)](https://github.com/terraform-aws-modules/terraform-aws-rds) - Creates RDS resources on AWS (verified module).
*   [terraform-aws-redshift (⭐72)](https://github.com/terraform-aws-modules/terraform-aws-redshift) - Creates Redshift resources on AWS.
*   [terraform-aws-route53 (⭐110)](https://github.com/terraform-aws-modules/terraform-aws-route53) - Creates Route53 resources on AWS.
*   [terraform-aws-s3-bucket (⭐446)](https://github.com/terraform-aws-modules/terraform-aws-s3-bucket) - Creates S3 bucket resources on AWS.
*   [terraform-aws-secure-baseline (⭐1.1k)](https://github.com/nozaq/terraform-aws-secure-baseline) - Set up your AWS account with the secure baseline configuration based on CIS Amazon Web Services Foundations.
*   [terraform-aws-security-group (⭐532)](https://github.com/terraform-aws-modules/terraform-aws-security-group) - Creates EC2-VPC security groups on AWS (verified module).
*   [terraform-aws-ssh-bastion-service (⭐202)](https://github.com/joshuamkite/terraform-aws-ssh-bastion-service) - Terraform plan to deploy ssh bastion as a stateless service on AWS.
*   [terraform-aws-transit-gateway (⭐126)](https://github.com/terraform-aws-modules/terraform-aws-transit-gateway) - Creates Transit Gateway resources on AWS.
*   [terraform-aws-vpc (⭐2.7k)](https://github.com/terraform-aws-modules/terraform-aws-vpc) - Creates VPC resources on AWS (verified and very popular module).
*   [terraform-aws-vpn-gateway (⭐106)](https://github.com/terraform-aws-modules/terraform-aws-vpn-gateway) - Creates VPN gateway resources on AWS.
*   [terraform-azurerm-aks (⭐0)](https://github.com/kjanshair/terraform-azurerm-aks) - Create AKS resources on Azure.
*   [terraform-azurerm-iis (⭐6)](https://github.com/ghostinthewires/terraform-azurerm-iis-install) - Install IIS Server on Azure VM instance.
*   [terraform-azurerm-mysql (⭐2)](https://github.com/foreverXZC/terraform-azurerm-mysql) - Create MySql Database on Azure.
*   [terraform-azurerm-redis (⭐1)](https://github.com/rahulkhengare/terraform-azurerm-redis) - Create Redis on Azure.
*   [terraform-azurerm-sqlserver (⭐8)](https://github.com/metadevpro/terraform-azurerm-sqlserver-seed) - Create SQl Server Database on Azure.
*   [terraform-cloudflare-maintenance (⭐119)](https://github.com/adinhodovic/terraform-cloudflare-maintenance) - Module to create a Maintenance Page using Cloudflare Workers.
*   [terraform-digitalocean-droplet](https://registry.terraform.io/modules/terraform-digitalocean-modules/droplet/digitalocean) - Terraform module for managing DigitalOcean Droplets and related resources.
*   [terraform-ecs-jenkins (⭐103)](https://github.com/shuaibiyy/terraform-ecs-jenkins) - Provisions Jenkins on AWS ECS using Terraform.
*   [terraform-gce-atlantis (⭐22)](https://github.com/bschaatsbergen/terraform-gce-atlantis) - Creates Terraform configurations for running [Atlantis](https://runatlantis.io) on Google Compute Engine.
*   [terraform-google-project-factory (⭐771)](https://github.com/terraform-google-modules/terraform-google-project-factory) - Opinionated Google Cloud Platform project creation and configuration with Shared VPC, IAM, APIs, etc.
*   [terraform-kubestack (⭐587)](https://github.com/kbst/terraform-kubestack) - Kubestack is a framework for Kubernetes platform engineering teams to define the entire cloud native stack in one Terraform code base and continuously evolve the platform safely through GitOps.
*   [terraform-linode-k8s](https://registry.terraform.io/modules/linode/k8s/linode/) - Installs Kubernetes on Linode Instances.
*   [terraform-nixos (⭐274)](https://github.com/nix-community/terraform-nixos) - A set of Terraform modules that are designed to deploy NixOS.
*   [terraform-static-website-s3-cloudfront (⭐37)](https://github.com/sjevs/terraform-static-website-s3-cloudfront) - Creates static websites on AWS S3 & Cloudfront based on variables.
*   [tf\_aws\_bastion\_s3\_keys (⭐191)](https://github.com/terraform-community-modules/tf_aws_bastion_s3_keys) - Creates bastion hosts on AWS EC2.
*   [typhoon (⭐1.9k)](https://github.com/poseidon/typhoon) - Minimal and free Kubernetes distribution with Terraform.

## Private Registries

*   [anthology (⭐123)](https://github.com/erikvanbrakel/anthology) - Private Terraform registry implementation as an alternative to the official registry.
*   [citizen (⭐582)](https://github.com/outsideris/citizen) - Private Terraform Module/Provider Registry
*   [nrkno/terraform-registry (⭐53)](https://github.com/nrkno/terraform-registry) - A private Terraform registry with modular store backends.
*   [petra (⭐31)](https://github.com/devoteamgcloud/petra) - Private Terraform Registry Manager
*   [philips-labs/terraform-registry (⭐67)](https://github.com/philips-labs/terraform-registry) - Terraform registry to serve arbitrary Terraform provider releases hosted on Github
*   [tapir (⭐106)](https://github.com/PacoVK/tapir) - Private Terraform Registry.
*   [terraform-simple-registry (⭐64)](https://github.com/apparentlymart/terraform-simple-registry) - Simple implementation of the Terraform registry protocols.
*   [Terrareg (⭐91)](https://github.com/matthewjohn/terrareg) - Terraform module registry.
*   [terustry (⭐54)](https://github.com/veepee-oss/terustry) - Open Source terraform provider registry acting as a proxy for gitlab or github releases.

## Providers

### Hashicorp supported providers

*   [terraform-provider-aws (⭐8.9k)](https://github.com/hashicorp/terraform-provider-aws) - Provider for Amazon Web Services.
*   [terraform-provider-azurerm (⭐4.2k)](https://github.com/hashicorp/terraform-provider-azurerm) - Provider for Azure.
*   [terraform-provider-docker (⭐132)](https://github.com/hashicorp/terraform-provider-docker) - Provider for Docker.
*   [terraform-provider-google (⭐2.1k)](https://github.com/hashicorp/terraform-provider-google) - Provider for Google Cloud Platform.
*   [terraform-provider-helm (⭐956)](https://github.com/hashicorp/terraform-provider-helm) - Provider for Helm.
*   [terraform-provider-kubernetes (⭐1.5k)](https://github.com/hashicorp/terraform-provider-kubernetes) - Provider for Kubernetes.
*   [terraform-provider-vsphere (⭐580)](https://github.com/hashicorp/terraform-provider-vsphere) - Provider for VMware vSphere.

### Vendor supported providers

*   [terraform-provider-alicloud (⭐558)](https://github.com/aliyun/terraform-provider-alicloud) - Provider for Alibaba Cloud.
*   [terraform-provider-artifactory (⭐249)](https://github.com/jfrog/terraform-provider-artifactory) - Provider for [JFrog Artifactory](https://jfrog.com/artifactory/).
*   [terraform-provider-atlas (⭐43)](https://github.com/ariga/terraform-provider-atlas) - Provider for [Atlas](https://atlasgo.io/).
*   [terraform-provider-azapi (⭐137)](https://github.com/Azure/terraform-provider-azapi) - Provider for Azure Resource Manager Rest API
*   [terraform-provider-azuredevops (⭐327)](https://github.com/microsoft/terraform-provider-azuredevops) - Provider for Azure DevOps (VSTS).
*   [terraform-provider-buildkite (⭐49)](https://github.com/buildkite/terraform-provider-buildkite) - Provider for Buildkite.
*   [terraform-provider-checkly (⭐41)](https://github.com/checkly/terraform-provider-checkly) - Manage [Checkly](https://www.checklyhq.com) resources for API & E2E monitoring.
*   [terraform-provider-confluent (⭐99)](https://github.com/confluentinc/terraform-provider-confluent) - Provider for Confluent.
*   [terraform-provider-datadog (⭐355)](https://github.com/DataDog/terraform-provider-datadog) - Provider for Datadog.
*   [terraform-provider-digitalocean (⭐460)](https://github.com/digitalocean/terraform-provider-digitalocean) - Provider for DigitalOcean.
*   [terraform-provider-dominos (⭐1.1k)](https://github.com/ndmckinley/terraform-provider-dominos) - Provider for Dominos Pizza.
*   [terraform-provider-env0 (⭐31)](https://github.com/env0/terraform-provider-env0) - Provider for [env0](https://www.env0.com/)
*   [terraform-provider-github](https://github.com/integrations/terraform-provider-github) - Provider for GitHub.
*   [terraform-provider-gitlab (⭐375)](https://github.com/gitlabhq/terraform-provider-gitlab) - Provider for GitLab.
*   [terraform-provider-graphql (⭐51)](https://github.com/sullivtr/terraform-provider-graphql) - Provider for GraphQL queries and mutations.
*   [terraform-provider-hcloud (⭐424)](https://github.com/hetznercloud/terraform-provider-hcloud) - Provider for Hetzner Cloud.
*   [terraform-provider-healthchecksio (⭐36)](https://github.com/kristofferahl/terraform-provider-healthchecksio) - Provider to manage healthchecks.io resources.
*   [terraform-provider-heroku (⭐94)](https://github.com/heroku/terraform-provider-heroku) - Provider for Heroku.
*   [terraform-provider-ibm (⭐325)](https://github.com/IBM-Cloud/terraform-provider-ibm) - Provider for IBM Cloud.
*   [terraform-provider-iterative (⭐287)](https://github.com/iterative/terraform-provider-iterative) - Terraform plugin built with machine learning in mind.
*   [terraform-provider-k8s (⭐134)](https://github.com/banzaicloud/terraform-provider-k8s) - Simple Kubernetes Provider, works with any manifest.
*   [terraform-provider-keycloak (⭐516)](https://github.com/mrparkers/terraform-provider-keycloak) - Provider to manage the settings of your [Keycloak](https://www.keycloak.org/) identity provider server.
*   [terraform-provider-linode (⭐71)](https://github.com/btobolaski/terraform-provider-linode) - Provider for Linode.
*   [terraform-provider-openstack (⭐337)](https://github.com/terraform-provider-openstack/terraform-provider-openstack) - Plugin for OpenStack.
*   [terraform-provider-panos (⭐80)](https://github.com/PaloAltoNetworks/terraform-provider-panos) - Provider for [Palo Alto Networks next-generation firewalls](https://www.paloaltonetworks.com/network-security).
*   [terraform-provider-pingdom (⭐121)](https://github.com/russellcardullo/terraform-provider-pingdom) - Provider to manage Pingdom resources.
*   [terraform-provider-rancher2 (⭐229)](https://github.com/rancher/terraform-provider-rancher2) - Provider for Rancher v2.
*   [terraform-provider-scalr (⭐18)](https://github.com/Scalr/terraform-provider-scalr) - Provider for [Scalr](https://scalr.com)
*   [terraform-provider-secrethub (⭐50)](https://github.com/secrethub/terraform-provider-secrethub) - Provider for SecretHub.
*   [terraform-provider-sigsci (⭐25)](https://github.com/signalsciences/terraform-provider-sigsci) - Provider for Signal Sciences.
*   [terraform-provider-snowflake (⭐445)](https://github.com/chanzuckerberg/terraform-provider-snowflake) - Provider for Snowflake data warehouse.
*   [terraform-provider-spinnaker (⭐143)](https://github.com/armory-io/terraform-provider-spinnaker) - Provider for [Spinnaker](https://www.spinnaker.io/).
*   [terraform-provider-spotinst (⭐58)](https://github.com/spotinst/terraform-provider-spotinst) - Provider for spotinst.
*   [terraform-provider-stripe (⭐234)](https://github.com/franckverrot/terraform-provider-stripe) - Provider for Stripe.
*   [terraform-provider-ucloud (⭐65)](https://github.com/ucloud/terraform-provider-ucloud) - Provider to manage UCloud resources.
*   [terraform-provider-uptimerobot (⭐120)](https://github.com/louy/terraform-provider-uptimerobot) - Provider to manage uptimerobot resources.
*   [terraform-provider-vaulted (⭐37)](https://github.com/sumup-oss/terraform-provider-vaulted) - Encrypted HashiCorp Vault secrets via Terraform that can be stored in SCM such as Git.

### Community providers

*   [terraform-provider-docker (⭐464)](https://github.com/kreuzwerker/terraform-provider-docker) - Terraform Docker provider.
*   [terraform-provider-terracurl (⭐107)](https://github.com/devops-rob/terraform-provider-terracurl) - Provider to make managed and unmanaged API calls to your target endpoint.
*   [terraform-provider-value (⭐14)](https://github.com/pseudo-dynamic/terraform-provider-value) - Value Provider for Terraform.

## Testing

*   [clarity (⭐132)](https://github.com/xchapter7x/clarity) - A declarative test framework for Terraform for unit testing.
*   [kitchen-terraform (⭐1.1k)](https://github.com/newcontext-oss/kitchen-terraform) - Provides a set of Test Kitchen plugins which enable a system to use Test Kitchen to converge a Terraform configuration and verify the resulting Terraform state with InSpec controls.
*   [rspec-terraform (⭐90)](https://github.com/bsnape/rspec-terraform) - RSpec tests for your Terraform modules.
*   [terraform\_validate (⭐258)](https://github.com/elmundio87/terraform_validate) - Assists in the enforcement of user-defined standards in Terraform.
*   [terraform-compliance (⭐1.3k)](https://github.com/terraform-compliance/cli) - BDD Testing for Terraform Files.
*   [terratest (⭐7.2k)](https://github.com/gruntwork-io/terratest) - Terratest is a Go library that makes it easier to write automated tests for your infrastructure code.

## Tools

*   [AIaC (⭐2.9k)](https://github.com/gofireflyio/aiac) - Artificial Intelligence Infrastructure-as-Code Generator
*   [AirIAM (⭐738)](https://github.com/bridgecrewio/AirIAM) - AirIAM is a tool for AWS IAM to least privilege Terraform execution framework.
*   [Argonaut](https://argonaut.dev/) - Deploy apps and infrastructure on your cloud in minutes. Autogenerate Terraform modules, customize configurations through PRs. Support for app deployments on Kubernetes and Lambda environments.
*   [astro (⭐424)](https://github.com/uber/astro/) - Astro is a tool for managing multiple Terraform executions as a single command. :ghost:
*   [atlantis (⭐6.6k)](https://github.com/runatlantis/atlantis) - Unified workflow for collaborating on Terraform through GitHub.
*   [atmos (⭐433)](https://github.com/cloudposse/atmos) - A universal tool that converts deep merged YAML to module inputs. :alien:
*   [aws2tf (⭐318)](https://github.com/aws-samples/aws2tf) - automates the importing of existing AWS resources into Terraform and outputs the Terraform HCL code.
*   [aztfexport (⭐1.3k)](https://github.com/Azure/aztfexport) - A tool to bring existing Azure resources under Terraform's management.
*   [balcony](https://oguzhan-yilmaz.github.io/balcony/) - CLI tool for easy AWS API reads. Also generates Terraform import-blocks, and actual Terraform Resource code.
*   [blast radius (⭐1.9k)](https://github.com/28mm/blast-radius) - Interactive visualizations of Terraform dependency graphs. :skull:
*   [burrito](https://padok-team.github.io/burrito/) - Burrito is a TACoS (Terraform Automation Collaboration Software) Kubernetes Operator.
*   [cfnctl (⭐129)](https://github.com/rogerwelin/cfnctl) - Cfnctl brings the Terraform cli experience to AWS Cloudformation.
*   [Checkov (⭐6k)](https://github.com/bridgecrewio/checkov/) - Terraform static analysis tool for terraform>=0.12
*   [Coder](https://coder.com/) - Coder provisions software development environments on your infrastructure via Terraform.
*   [coretech/terrafile (⭐137)](https://github.com/coretech/terrafile) - Systematically manage external modules from Github for use in Terraform (written in Go).
*   [driftctl (⭐2.3k)](https://github.com/snyk/driftctl) - Detect, track, and alert on infrastructure drift
*   [dxw/terrafile (⭐2)](https://github.com/dxw/terrafile) - Systematically manage external modules from Github for use in Terraform (written in Ruby).
*   [flora (⭐22)](https://github.com/ketchoop/flora) - Terraform version manager.
*   [fogg (⭐276)](https://github.com/chanzuckerberg/fogg) - A tool for eliminating toil in managing terraform repositories.
*   [former2 (⭐1.9k)](https://github.com/iann0036/former2) - Generate terraform configuration from your existing resources within your AWS account.
*   [fuzzy-terraform-rm (⭐31)](https://github.com/paololazzari/fuzzy-terraform-rm) - A fuzzy-finder command-line tool for removing resources from terraform state.
*   [gaia (⭐823)](https://github.com/gaia-app/gaia) - Gaia is a Terraform 🌍 UI for your modules, and self-service infrastructure 👨‍💻.
*   [hatchet](https://docs.hatchet.run/) - An all-in-one Terraform management tool.
*   [hcldump (⭐6)](https://github.com/magodo/hcldump) - Dump the HCL (v2) abstract syntax tree.
*   [hcledit (⭐355)](https://github.com/minamijoyo/hcledit) - A command line editor for HCL.
*   [hclgrep (⭐86)](https://github.com/magodo/hclgrep) - Syntax based grep for HCL(v2).
*   [iam-policy-json-to-terraform (⭐728)](https://github.com/flosell/iam-policy-json-to-terraform) - Small tool to convert an IAM Policy in JSON format into a Terraform aws\_iam\_policy\_document
*   [Infracost (⭐9.7k)](https://github.com/infracost/infracost) - Cloud cost estimates for Terraform in your CLI and pull requests.
*   [inframap (⭐1.5k)](https://github.com/cycloidio/inframap) - Read your tfstate or HCL to generate a graph specific for each provider, showing only the resources that are most important/relevant.
*   [json2hcl (⭐466)](https://github.com/kvz/json2hcl) - Convert JSON to HCL and vice versa. :ghost:
*   [k2tf (⭐1.1k)](https://github.com/sl1pm4t/k2tf) - Kubernetes YAML to Terraform HCL converter.
*   [KICS (⭐1.7k)](https://github.com/Checkmarx/kics) - Scans IaC projects for security vulnerabilities, compliance issues, and infrastructure misconfiguration. Currently working with Terraform projects, Kubernetes manifests, Dockerfiles, AWS CloudFormation Templates, and Ansible playbooks.
*   [layerform (⭐1.2k)](https://github.com/ergomake/layerform) - Layerform helps engineers create reusable environment stacks using plain .tf files. Ideal for multiple "staging" environments.
*   [modules.tf-lambda (⭐342)](https://github.com/antonbabenko/modules.tf-lambda) - Infrastructure as code generator from visual diagrams created with [Cloudcraft.co](https://cloudcraft.co/app) to Terraform.
*   [para (⭐53)](https://github.com/paraterraform/para) - The missing 3rd-party plugin manager and a "Swiss army knife" for Terraform/Terragrunt - just 1 tool to facilitate all workflows. :skull:
*   [pike (⭐358)](https://github.com/jamesWoolfenden/pike) - Pike calculates the permissions or IAM policy required to build your Terraform.
*   [pluralith](https://www.pluralith.com/) - Terraform state visualization and automated generation of infrastructure documentation. :heavy\_dollar\_sign:
*   [pre-commit-terraform (⭐2.7k)](https://github.com/antonbabenko/pre-commit-terraform) - pre-commit git hooks to take care of Terraform configurations (auto-format, validate, update docs).
*   [pretf (⭐100)](https://github.com/raymondbutcher/pretf) - drop-in Terraform wrapper that generates Terraform configuration with Python. See [pretf documentation](https://pretf.readthedocs.io/en/latest/)
*   [prettyplan (⭐143)](https://github.com/chrislewisdev/prettyplan) - Prettyplan ([available online here](https://chrislewisdev.github.io/prettyplan/)) is a small tool to help you view large Terraform plans with ease. :ghost:
*   [pytest-terraform (⭐50)](https://github.com/cloud-custodian/pytest-terraform) - pytest terraform plugin with fixtures and offline replay support.
*   [python-terrafile (⭐36)](https://github.com/claranet/python-terrafile) - Systematically manage external modules from Github for use in Terraform.
*   [regula (⭐885)](https://github.com/fugue/regula) - Evaluates Terraform infrastructure-as-code for potential AWS, Azure, and Google Cloud security misconfigurations and compliance violations prior to deployment.
*   [renovate-config (⭐33)](https://github.com/SpotOnInc/renovate-config) - Sharable Config Presets for Renovatebot, especially useful for DevOps folks.
*   [rover (⭐2.7k)](https://github.com/im2nguyen/rover) - Interactive Terraform state and configuration explorer.
*   [ruby-terraform (⭐103)](https://github.com/infrablocks/ruby_terraform) - Simple Ruby wrapper for invoking terraform commands.
*   [sato (⭐50)](https://github.com/JamesWoolfenden/sato) - Sato helps you convert your legacy Cloudformation into Terraform.
*   [scenery (⭐370)](https://github.com/dmlittle/scenery) - Another Terraform plan output prettifier. :ghost:
*   [scratchrelaxtv (⭐26)](https://github.com/YakDriver/scratchrelaxtv) - Simple Python tool to help with module development - extract vars from `main.tf` to generate `variables.tf` and make module usage stub from `variables.tf`.
*   [serverless.tf - Doing serverless with Terraform](https://serverless.tf/) - serverless.tf is an opinionated open-source framework for developing, building, deploying, and securing serverless applications and infrastructures on AWS using Terraform. [Read more (⭐586)](https://github.com/antonbabenko/serverless.tf).
*   [Shisho (⭐360)](https://github.com/flatt-security/shisho) - Lightweight static analyzer for Terraform.
*   [stacks (⭐106)](https://github.com/cisco-open/stacks) - Stacks, the Terraform code pre-processor
*   [Styra Declarative Authorization Service (DAS)](https://www.styra.com/terraform-cloud-config-management-with-styra-das-and-open-policy-agent) - Provides a managed [Open Policy Agent (OPA)](https://www.openpolicyagent.org) platform for Application and Infrastructure use cases, including Terraform, Terraform Cloud, and Kubernetes. Enforce policy guardrails during development, in CI/CD pipelines, and at deploy time. Styra DAS Free provides multiple systems and users, policy impact analysis, decision logging and replay, and access to Styra's Terraform policy library.
*   [tads-boilerplate (⭐694)](https://github.com/Thomvaill/tads-boilerplate) - The power of Ansible and Terraform + the simplicity of Docker Swarm = Infrastructure as Code and DevOps best practices.
*   [tau (⭐76)](https://github.com/avinor/tau) - Tau is a thin wrapper on top of terraform to manage multiple deployments, dependencies, and secrets.
*   [terraboard (⭐1.8k)](https://github.com/camptocamp/terraboard) - Web dashboard to inspect Terraform States.
*   [terraboot (⭐38)](https://github.com/MastodonC/terraboot) - DSL to generate a terraform configuration and run it.
*   [terracognita (⭐1.8k)](https://github.com/cycloidio/terracognita) - Reads from existing Cloud Providers (reverse Terraform) and generates your infrastructure as code on Terraform configuration.
*   [terracost (⭐234)](https://github.com/cycloidio/terracost) - Cloud cost estimation for Terraform in your CLI.
*   [terracove](https://elementtech.github.io/terracove/) - Recursively test a directory tree for Terraform diffs and coverage.
*   [TerraDepot (⭐63)](https://github.com/derBroBro/TerraDepot) Terraform state repository, based on the default http remote backend. Allows the central administration of tfstates on AWS S3.
*   [terradozer (⭐160)](https://github.com/jckuester/terradozer) - Terraform destroy without configuration files.
*   [terraeasy (⭐32)](https://github.com/jaceq/terraeasy) - Easy Terraform wrapper
*   [terraform-aws-clickops-notifier (⭐176)](https://github.com/cloudandthings/terraform-aws-clickops-notifier) - Get notified when actions are taken in the AWS Console.
*   [terraform-bundle (⭐39k)](https://github.com/hashicorp/terraform/tree/master/tools/terraform-bundle) - Easily builds bundles containing a Terraform binary as well as provider binaries. Useful for CI and air-gapped Terraform Enterprise.
*   [terraform-cdk (⭐4.6k)](https://github.com/hashicorp/terraform-cdk) - CDK (Cloud Development Kit) for Terraform allows developers to use familiar programming languages to define cloud infrastructure and provision it through HashiCorp Terraform.
*   [terraform-cleaner (⭐151)](https://github.com/sylwit/terraform-cleaner) - Tiny utility which detects unused variables in your terraform modules.
*   [terraform-credentials-vault (⭐4)](https://github.com/oulman/terraform-credentials-vault) - A Terraform "credentials helper" plugin that allows providing credentials for Terraform-native services (private module registries, Terraform Cloud, etc) via environment variables.
*   [terraform-diff (⭐62)](https://github.com/contentful-labs/terraform-diff) - Always know where you need to run Terraform plan & apply!
*   [terraform-docs (⭐3.7k)](https://github.com/terraform-docs/terraform-docs) - Quick utility to generate docs from terraform modules.
*   [terraform-graph-beautifier (⭐286)](https://github.com/pcasteran/terraform-graph-beautifier) - Command line tool allowing to convert the barely usable output of the terraform graph command to something more meaningful and explanatory.
*   [terraform-iam-policy-validator (⭐203)](https://github.com/awslabs/terraform-iam-policy-validator) - CLI validates AWS IAM Policies in a Terraform template against AWS IAM best practices.
*   [terraform-landscape (⭐1.5k)](https://github.com/coinbase/terraform-landscape) - *(only 0.11 and earlier)* Improve Terraform's plan output to be easier to read and understand.
*   [terraform-operator](https://github.com/isaaguilar/terraform-operator.git) - A Kubernetes CRD to handle Terraform operations.
*   [terraform-plan-parser (⭐143)](https://github.com/lifeomic/terraform-plan-parser) - Command line utility and JavaScript API for parsing stdout from `terraform plan` and converting it to JSON. :ghost:
*   [terraform-provisioner (⭐13)](https://github.com/shuaibiyy/terraform-provisioner) - Tool for managing multiple provisions of the same Terraform scripts.
*   [terraform-rake-tasks (⭐4)](https://github.com/gina-alaska/terraform-rake-tasks) - Shared Rake tasks for managing terraform plans.
*   [terraform-repl (⭐77)](https://github.com/paololazzari/terraform-repl) - A terraform console wrapper for a better interactive console experience.
*   [Terraform-Visual (⭐529)](https://github.com/hieven/terraform-visual) - A simple but powerful tool to visualize Terraform plan.
*   [terraform.py (⭐448)](https://github.com/ciscocloud/terraform.py) - Ansible dynamic inventory script for parsing Terraform state files.
*   [terraformer (⭐11k)](https://github.com/GoogleCloudPlatform/terraformer) - CLI tool to generate terraform files from existing infrastructure. Infrastructure to Code. Supported many providers.
*   [terraforming (⭐4.3k)](https://github.com/dtan4/terraforming) - Export existing AWS resources to Terraform style (tf, tfstate). Similar to `terraformer`.
*   [terraformize (⭐153)](https://github.com/naorlivne/terraformize) - Apply\Destroy Terraform modules via a simple REST API endpoint.
*   [terraformsh (⭐56)](https://github.com/pwillis-els/terraformsh) - A wrapper in Bash for easier CLI UX and DRY hierarchical configs
*   [terragrunt-atlantis-config (⭐504)](https://github.com/transcend-io/terragrunt-atlantis-config) - Generate Atlantis config for Terragrunt projects.
*   [terragrunt (⭐7.2k)](https://github.com/gruntwork-io/terragrunt) - Terragrunt is a thin wrapper for Terraform that provides extra tools for keeping your Terraform configurations DRY, working with multiple Terraform modules, and managing remote state.
*   [Terrahaxs](https://www.terrahaxs.com) - A GitOps Terraform CI/CD GitHub Application :heavy\_dollar\_sign:
*   [terrahelp (⭐377)](https://github.com/opencredo/terrahelp) - Command line utility aimed at providing supplementary functionality which can sometimes prove useful when working with Terraform.
*   [terrahub (⭐219)](https://github.com/TerraHubCorp/terrahub) - TerraHub is terraform automation and orchestration tool. Seamlessly integrated into console.terrahub.io, enterprise friendly GUI to show realtime terraform executions, as well as auditing and reporting capabilities for historical terraform runs. :heavy\_dollar\_sign:
*   [terramagic (⭐41)](https://github.com/miltlima/terramagic) - Wizard tool for create folders and terraform files automated, written in Python !
*   [terramate (⭐2.6k)](https://github.com/mineiros-io/terramate) - Tool for managing multiple Terraform stacks that comes with support for change detection and code generation
*   [terrap-cli (⭐62)](https://github.com/sirrend/terrap-cli) - Terrap - a powerful CLI tool that scans your infrastructure and identifies any required changes.
*   [terrars (⭐65)](https://github.com/andrewbaxter/terrars) - Terrars is a tool for building Terraform stacks in Rust. This is an alternative to the CDK.
*   [terrascan (⭐4.2k)](https://github.com/accurics/terrascan) - Collection of security and best practice test for static code analysis of terraform templates
*   [terrascope (⭐27)](https://github.com/spilliams/terrascope) - Build orchestrator for terraform monorepos.
*   [terrashine](https://isawan.github.io/terrashine/) - Terrashine is a terraform provider mirror1 implementation that works by automatically caching dependencies as providers are requested.
*   [terraspace](https://terraspace.cloud) - The Terraform Framework
*   [terrastate (⭐74)](https://github.com/rohinivsenthil/terrastate) - Visual Studio Code extension to monitor/deploy/destroy Terraform resources in your workspace
*   [terratag (⭐842)](https://github.com/env0/terratag) - Terratag is a CLI tool that enables users of Terraform to automatically create and maintain tags across their entire set of AWS, Azure, and GCP resources.
*   [tf-init-booster (⭐7)](https://github.com/hayorov/terraform-init-booster) - A Pre-terraform routine that speedups terraform modules download for bulky blueprints.
*   [tf-profile (⭐130)](https://github.com/datarootsio/tf-profile/) - Profiler for Terraform runs. Generate global stats, resource-level stats or visualizations.
*   [tf-summarize (⭐398)](https://github.com/dineshba/tf-summarize) - A command-line utility to print the summary of the terraform plan
*   [tfaction (⭐206)](https://github.com/suzuki-shunsuke/tfaction) - GitHub Actions collection for Opinionated Terraform Workflow
*   [tfautomv (⭐589)](https://github.com/padok-team/tfautomv) - Generate Terraform `moved` blocks automatically for painless refactoring
*   [tfcmt (⭐323)](https://github.com/suzuki-shunsuke/tfcmt) - CLI to notify the result of plan and apply as Pull Request comment.
*   [tfedit (⭐82)](https://github.com/minamijoyo/tfedit) - A refactoring tool for Terraform.
*   [tfenv (⭐4.1k)](https://github.com/tfutils/tfenv) - Terraform version manager inspired by rbenv.
*   [tfgen (⭐68)](https://github.com/refl3ction/tfgen) - Terraform code generator for consistent codebase and DRY.
*   [tfgpt (⭐67)](https://github.com/flavius-dinu/tfgpt) - A CLI tool that integrates Terraform with OpenAI's GPT-3.5 Turbo to provide explanations for Terraform commands and concepts.
*   [tfjson (⭐181)](https://github.com/palantir/tfjson) - Utility to read in a Terraform plan file and dump it out in JSON. :skull:
*   [tflint (⭐4.2k)](https://github.com/terraform-linters/tflint) - Terraform linter for detecting errors that can not be detected by `terraform plan`
*   [tfmake (⭐13)](https://github.com/tfmake/tfmake) - Automating Terraform with the power of make.
*   [tfmask (⭐193)](https://github.com/cloudposse/tfmask) - Terraform utility to mask select output from `terraform plan` and `terraform apply`
*   [tfmigrate (⭐958)](https://github.com/minamijoyo/tfmigrate) - A Terraform state migration tool for GitOps.
*   [tfmigrator (⭐35)](https://github.com/tfmigrator/cli) - Go library and CLI to migrate Terraform Configuration and State
*   [tfproviderlint (⭐125)](https://github.com/bflad/tfproviderlint) - Terraform Provider Lint Tool.
*   [tfrepl (⭐25)](https://github.com/ysoftwareab/tfrepl) - A Terraform REPL, giving you a full shell experience. Readline based. No dependencies. Save config changes. History.
*   [tfscaffold (⭐223)](https://github.com/tfutils/tfscaffold) - Framework for controlling multi-environment multi-component terraform-managed AWS infrastructure.
*   [tfschema (⭐281)](https://github.com/minamijoyo/tfschema) - Schema inspector for Terraform providers.
*   [tfsec (⭐6.3k)](https://github.com/aquasecurity/tfsec) - Terraform static analysis tool that supports terraform <0.12 & >=0.12 & directly integrates with HCL parser for better results.
*   [tfsort (⭐111)](https://github.com/AlexNabokikh/tfsort) - CLI utility to sort Terraform variables and outputs.
*   [tftarget (⭐174)](https://github.com/future-architect/tftarget) - CLI Tool to do `terraform xxx -target={...}` interactively.
*   [tftree (⭐129)](https://github.com/busser/tftree) - Display your Terraform module call stack in your terminal.
*   [tftui (⭐698)](https://github.com/idoavrah/terraform-tui) - A textual user interface for Terraform state.
*   [tfupdate (⭐462)](https://github.com/minamijoyo/tfupdate) - Update version constraints in your Terraform configurations.
*   [tfvar (⭐180)](https://github.com/shihanng/tfvar) - tfvar scans your Terraform configurations or modules and extracts the variables into formats of your choice (tfvar, environment variables, etc.) for editing.
*   [tfvaultenv (⭐46)](https://github.com/oulman/tfvaultenv) - tfvaultenv reads secrets from HashiCorp Vault and outputs environment variables for various Terraform providers with those secrets.
*   [tfwrapper (⭐8)](https://github.com/manheim/tfwrapper) - Rubygem providing rake tasks for running Hashicorp Terraform sanely.
*   [tgf (⭐94)](https://github.com/coveo/tgf) - Terragrunt frontend for executing Terragrunt/Terraform through Docker.
*   [tpm (⭐75)](https://github.com/Madh93/tpm) - A package manager for Terraform providers.
*   [travelgrunt (⭐59)](https://github.com/ivanilves/travelgrunt) - cd inside \[mono]repos without fatigue!
*   [validIaC (⭐209)](https://github.com/gofireflyio/validiac) - ValidIaC combines the best open-source tools to help ensure Terraform best practices, hygiene & security.
*   [xterrafile (⭐66)](https://github.com/devopsmakers/xterrafile) Systematically manage external modules from the module registry, git, or local directories for use in Terraform (written in Go).
*   [yor (⭐725)](https://github.com/bridgecrewio/yor) - Automatically tag and trace infrastructure as code frameworks (Terraform, Cloudformation, and Serverless).
*   [Speakeasy](https://www.speakeasyapi.dev/) - Generate a terraform provider from an OpenAPI specification.

### CI

*   [setup-terraform (⭐1.1k)](https://github.com/hashicorp/setup-terraform) - Sets up Terraform CLI in your GitHub Actions workflow.
*   [terraform-plan (⭐45)](https://github.com/cds-snc/terraform-plan) - GitHub Action to run Terraform plan and add a comment with the changes.

### IDE

*   [vscode-terraform-live-graph (⭐196)](https://github.com/adamiBs/vscode-terraform-live-graph) - Terraform Live Graph Extension for Visual Studio Code is a plugin that allows you to generate a live Terraform graph as you code.

## Libraries

*   [nu\_plugin\_hcl (⭐1)](https://github.com/Yethal/nu_plugin_hcl) - HCL parser plugin for [Nushell (⭐27k)](https://github.com/nushell/nushell)
*   [pyhcl (⭐320)](https://github.com/virtuald/pyhcl) - HCL parser in Python
*   [python-hcl2 (⭐206)](https://github.com/amplify-education/python-hcl2/) - HCL2 parser in Python
*   [rhcl (⭐15)](https://github.com/winebarrel/rhcl) - Pure Ruby HCL parser

## Boilerplates

*   [Terraform Generator (⭐249)](https://github.com/sudokar/generator-tf-module) - Scaffolding for a new terraform module or project with support of test frameworks (terratest and kitchen-terraform)
*   [Terraform GitOps Framework](https://www.kubestack.com) - Everything you need to build reliable automation for AKS, EKS, and GKE Kubernetes clusters in one free and open-source framework.

## Terraform Enterprise

*   [terraform-enterprise-cli (⭐10)](https://github.com/skierkowski/terraform-enterprise-cli) - Terraform Enterprise Command Line Interface.
*   [terraform-enterprise-client (⭐8)](https://github.com/skierkowski/terraform-enterprise-client) - Terraform Enterprise API Ruby Client and Command Line tool.
*   [terraform-enterprise-migrator (⭐12)](https://github.com/silinternational/terraform-enterprise-migrator) - Script for migrating Terraform Enterprise environments from Legacy to new version of Terraform Enterprise.
*   [tfe-state-explorer (⭐18)](https://github.com/segmentio/tfe-state-explorer) - Simple shell for exploring remote terraform enterprise state, with autocomplete. :skull:
*   [Scalr](https://scalr.com) - Alternative to Terraform Enterprise with OPA integration, organizational structure, custom hooks, native integrations with other DevOps platforms, and centralized reporting.  :heavy\_dollar\_sign:
*   [env0](https://env0.com) - Alternative to Terraform Cloud/Enterprise with OPA integration, custom flows and Terragrunt support :heavy\_dollar\_sign:
*   [Brainboard](https://www.brainboard.co) - Visually Design, Deploy & Manage modern cloud infrastructures starting from any Cloud Provider - AWS, GCP, Azure :heavy\_dollar\_sign:
*   [OTF (⭐410)](https://github.com/leg100/otf) - Open Terraforming Framework, an open source alternative to Terraform Enterprise with full Terraform CLI integration.
*   [Terrakube](https://docs.terrakube.io) - Open Source alternative to Terraform Enterprise with private registry, remote state, custom flows, scheduled workspaces, and visual states.
*   [Spacelift](https://spacelift.io/) - Alternative to Terraform Cloud/Enterprise. Collaborative Infrastructure Delivery Platform for Terraform :heavy\_dollar\_sign:
*   [Terrateam](https://terrateam.io) - Terraform GitOps with cost estimation, static analysis, access controls, drift detection, and custom workflows. :heavy\_dollar\_sign:
*   [Digger](https://digger.dev) - Open Source Alternative to Terraform Cloud - Run Terraform plan & apply jobs in your CI.
*   [cloud-concierge (⭐143)](https://github.com/dragondrop-cloud/cloud-concierge) - Open Source, codify unmanaged resources as Terraform, detect drift, and cloud cost and security analysis, delivered as a Pull Request.

## Videos

*   [Your Weekly Dose of Terraform](https://bit.ly/terraform-youtube) - YouTube channel with weekly live streams covering Terraform news, reviews, interviews, Q\&A, live coding, and some hacking with Terraform.
*   [Terraform explained in 15 mins](https://www.youtube.com/watch?v=l5k1ai_GBDE) - Terraform explained in 15 mins.
*   [Terraform Course](https://www.youtube.com/watch?v=SLB_c_ayRMo) - Automate your AWS cloud infrastructure.
*   [How to Build Reusable, Composable, Battle tested Terraform Modules](https://www.youtube.com/watch?v=LVgP63BkhKQ) - Yevgeniy Brikman talks about how to write Terraform code so that it is reusable, composable and testable. The presentation focuses on Terraform modules but also provides a brief and clear explanation of what problem Terraform was created to solve and a short demo of Terraform basics (\~39 min, October 2017).
*   [Building Scalable, Repeatable Infrastructure in the Cloud with Terraform](https://www.youtube.com/watch?v=cG7pcksTAnY) - Demonstrates how Terraform enables the practice of Infrastructure as Code by deploying TeamCity in AWS using a hosted PostgreSQL.
*   [Creating a Google Compute Instance with Terraform](https://www.youtube.com/watch?v=fo3VX33Zx0c) - Example of creating a Google Compute Instance with Terraform code.
*   [Creating a Terraform Provider for Just About Anything](https://www.hashicorp.com/resources/creating-terraform-provider-for-anything) - Learn how to contribute to a Terraform provider or create your own from this walkthrough.
*   [Evolving Your Infrastructure with Terraform](https://www.youtube.com/watch?v=wgzgVm7Sqlk) - CTO of OpenCredo provides an extensive look at using Terraform in the real-world with the help of some interesting use-cases.
*   [Going Multi-Cloud with Terraform and Nomad](https://www.youtube.com/watch?v=e42A4aBZUkQ).
*   [How to Extend the Terraform Provider List](https://www.youtube.com/watch?v=2BvpqmFpchI) - In this talk, Paul will walk through the creation of a terraform provider.
*   [Orchestrating Containers with Terraform and Consul](https://www.infoq.com/presentations/terraform-consul) - Mitchell Hashimoto shows how Terraform can be used to deploy and scale containerized workloads.
*   [Production ChaosMonkey with Terraform](https://www.youtube.com/watch?v=CPI6W3LK0-g) - How DigitalOcean uses Terraform to run production integration tests.
*   [Running a Terraform Environment at Scale](https://www.youtube.com/watch?v=3JVGSq7QIS0) - Running Terraform at scale with hundreds of AWS accounts.
*   [Setup Continuous Integration for a Terraform module](https://www.youtube.com/watch?v=vuJ6bjYKUcA) - Example of using CI with Kitchen-Terraform to test, tag and publish our Terraform module, which creates a Google Compute Instance.
*   [State of Terraform Providerland](https://www.youtube.com/watch?v=ar1PF5iDtbg) - How Terraform providers work and how to write one.
*   [Terraform At Scale](https://www.youtube.com/watch?v=RldRDryLiXs) - How Segment uses Terraform.
*   [Terraform w/ Lee Trout](https://www.youtube.com/watch?v=p2ESyuqPw1A) - Focuses on development patterns and how to effectively structure Terraform code.
*   [Terraforming the Composable World](https://www.youtube.com/watch?v=cHrOXPatFeg) - Integrating Terraform with an on-premise bare metal provisioning.
*   [Test and verify a Google Compute Instance with Kitchen-Terraform](https://www.youtube.com/watch?v=kiH3-LEveek) - Example of using Kitchen-Terraform to test our Terraform code that creates a Google Compute.
*   [Untangling Terraform Through Refactoring](https://www.youtube.com/watch?v=OH6iDKaXpZs) - How to refactor your Terraform code in a careful way with minimum risk.
*   [Complete Terraform Course - From BEGINNER to PRO! (Learn Infrastructure as Code)](https://www.youtube.com/watch?v=7xngnjfIlK4) - Complete course from beginner to pro, with no cloud provider focus, with a general approach

## Editor Plugins

*   [Atom terraform-lookup](https://atom.io/packages/terraform-lookup)
*   [Emacs terraform-mode (⭐201)](https://github.com/syohex/emacs-terraform-mode)
*   [Intellij](https://plugins.jetbrains.com/plugin/7808-hashicorp-terraform--hcl-language-support)
*   [Terraform-ls (⭐892)](https://github.com/hashicorp/terraform-ls) (Terraform Language Server)
*   [Terraform-lsp (⭐566)](https://github.com/juliosueiras/terraform-lsp) (Language Server Protocol for Terraform)
*   [Vim-Terraform (⭐996)](https://github.com/hashivim/vim-terraform)
*   [Vim-Terraform-Completion (⭐333)](https://github.com/juliosueiras/vim-terraform-completion)
*   [VS Code](https://marketplace.visualstudio.com/items?itemName=mauve.terraform)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Shuaib Yunus has waived all copyright and related or neighboring rights to this work.

