---
layout: page
title: Projects & Achievements
permalink: /projects/
---

# Key Projects & Achievements

## Infrastructure Cost Optimization at GXBank

### EKS Cluster Optimization
- **Challenge**: High operational costs and maintenance overhead
- **Solution**: Upgraded EKS clusters to standard support, implemented Karpenter for auto-scaling
- **Impact**: $25k/month savings ($20k from upgrades + $5k from Karpenter migration)

### Logging Cost Reduction
- **Challenge**: Excessive Datadog logging costs
- **Solution**: Optimized configuration and retention policies for EKS and ArgoCD
- **Impact**: 70% reduction in logging costs

## Zero-Downtime Service Mesh Upgrades

### Istio Upgrade Across 45+ Clusters
- **Challenge**: Upgrading Istio service mesh without service interruption
- **Solution**: Implemented canary upgrade strategy with automated Argo Workflows
- **Impact**: Zero downtime upgrades with automated Slack notifications for monitoring

## Infrastructure as Code Standardization

### Terraform Module Refactoring
- **Challenge**: Duplicated and hard-to-maintain infrastructure code
- **Solution**: Consolidated EKS Terraform code into reusable modules
- **Impact**: Significantly reduced manual toil and improved maintainability

### Karpenter Integration
- **Challenge**: Inefficient cluster auto-scaling with Cluster Autoscaler
- **Solution**: Developed Terraform module for Karpenter with monthly AMI rotation
- **Impact**: Improved scalability, reduced resource waste, enhanced security with CVE updates

## Multi-Cloud Deployment Experience

### Alicloud to AWS Migration (Up Devlabs)
- **Challenge**: Migrate sports streaming platform from Alicloud to AWS
- **Solution**: Implemented CI/CD pipeline on AWS EKS with proper DNS and CDN configuration
- **Impact**: Improved performance and reliability for streaming services

### Hybrid Cloud Management (Ciro Solution)
- **Challenge**: Managing applications across multiple cloud providers
- **Solution**: Standardized deployment with Helm charts, centralized monitoring
- **Impact**: Unified operations across GCP, Alicloud, and on-premises infrastructure

## Automation & ChatOps

### Telegram Bot for Kubernetes Operations
- **Challenge**: Need for quick cluster operations and monitoring
- **Solution**: Python-based Telegram bot for ChatOps on staging clusters
- **Impact**: Faster incident response and simplified cluster management

### CI/CD Pipeline Optimization
- **Challenge**: Complex deployment processes across multiple environments
- **Solution**: Refactored Jenkins shared libraries, implemented GitOps with ArgoCD
- **Impact**: Streamlined deployments with improved reliability and rollback capabilities

## Embedded Systems Development

### Sony TV Production Testing System
- **Challenge**: Automated hardware defect detection in TV manufacturing
- **Solution**: Developed embedded Linux software for peripheral control and testing
- **Impact**: Deployed globally across Sony TV manufacturing plants

---

## Technical Certifications Achieved

- **AWS Solutions Architect Associate** - Cloud architecture and infrastructure design
- **CNCF Kubestronaut** (5th in Malaysia) - Complete Kubernetes certification track:
  - CKAD (Kubernetes Application Developer)
  - CKA (Kubernetes Administrator) 
  - CKS (Kubernetes Security Specialist)
  - KCNA (Kubernetes and Cloud Native Associate)
  - KCSA (Kubernetes and Cloud Native Security Associate)

*These projects demonstrate expertise in cost optimization, infrastructure automation, zero-downtime deployments, and multi-cloud operations at enterprise scale.*
