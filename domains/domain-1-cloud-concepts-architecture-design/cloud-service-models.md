# Cloud Service Models

Priority: 🔴 Critical  
Exam Frequency: ⭐⭐⭐⭐⭐

## Overview

The major cloud service models are:

- IaaS: Infrastructure as a Service
- PaaS: Platform as a Service
- SaaS: Software as a Service

The key exam concept is understanding which party is responsible for each layer.

## IaaS

IaaS gives the customer virtualized infrastructure.

Customer usually manages:

- Operating system
- Middleware
- Runtime
- Applications
- Data

CSP usually manages:

- Physical datacenter
- Physical servers
- Storage infrastructure
- Networking infrastructure
- Virtualization layer

Examples:

- Azure Virtual Machines
- AWS EC2
- Google Compute Engine

## PaaS

PaaS gives the customer a managed platform for running applications.

Customer usually manages:

- Application code
- Data
- Application configuration

CSP usually manages:

- Operating system
- Runtime
- Middleware
- Infrastructure
- Scaling platform

Examples:

- Azure App Service
- Azure SQL Database
- Google App Engine
- AWS Elastic Beanstalk

## SaaS

SaaS gives the customer a complete application.

Customer usually manages:

- Users
- Data usage
- Access policies
- Configuration

CSP manages most of the technology stack.

Examples:

- Microsoft 365
- Salesforce
- Google Workspace

## Exam Shortcut

Ask: **Am I managing the operating system?**

- Yes = likely IaaS
- No, but I deploy code = likely PaaS
- No, I just use the app = SaaS

