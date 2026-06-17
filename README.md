# Netflix DevSecOps Project

## Project Overview

This project demonstrates the implementation of a complete DevSecOps workflow for deploying and securing a Netflix-style web application. The objective of this project is to automate application delivery, integrate security scanning into the CI/CD pipeline, and monitor the deployed application using industry-standard DevOps tools.

The project includes source code management, continuous integration, security testing, containerization, monitoring, and Kubernetes-based deployment.

---

## Project Objectives

* Automate application deployment using Jenkins
* Perform code quality analysis using SonarQube
* Identify vulnerable dependencies using OWASP Dependency Check
* Scan containers using Trivy
* Containerize the application using Docker
* Deploy workloads using Kubernetes
* Implement GitOps practices using ArgoCD
* Monitor infrastructure and application metrics using Prometheus and Grafana
* Build a production-style DevSecOps workflow

---

## Project Architecture

GitHub Repository

↓

Jenkins CI/CD Pipeline

↓

SonarQube Analysis

↓

OWASP Dependency Check

↓

Trivy Security Scan

↓

Docker Image Build

↓

Container Registry

↓

Kubernetes Deployment

↓

Prometheus Monitoring

↓

Grafana Dashboard

---

## Technologies Used

* React
* Vite
* Docker
* Jenkins
* SonarQube
* OWASP Dependency Check
* Trivy
* Kubernetes
* ArgoCD
* Prometheus
* Grafana
* AWS EC2
* AWS EKS

---

## Deployment Workflow

### Infrastructure Setup

* Launch Ubuntu EC2 instance
* Configure Docker and required dependencies
* Clone application repository
* Build and run application containers

### Security Integration

* Configure SonarQube for static code analysis
* Integrate OWASP Dependency Check
* Perform filesystem and container image scanning using Trivy

### CI/CD Automation

* Configure Jenkins pipeline
* Automate build, scan, and deployment stages
* Manage Docker image creation and publishing

### Monitoring and Observability

* Install Prometheus
* Configure Node Exporter
* Visualize metrics using Grafana dashboards

### Kubernetes Deployment

* Deploy application resources using Kubernetes manifests
* Configure services and ingress resources
* Manage deployments using GitOps workflows

---

## Learning Outcomes

Through this project I gained hands-on experience in:

* CI/CD Pipeline Design
* DevSecOps Practices
* Container Security
* Docker and Kubernetes
* Infrastructure Monitoring
* GitOps Deployment Strategy
* Cloud Deployment on AWS

---

## Author

Anurag Naithani

GitHub:
https://github.com/anuragnaithani

LinkedIn:
https://www.linkedin.com/in/anurag-naithani/
