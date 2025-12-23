                                           ShopEasy – Production Grade E-Commerce Application (v2.0)

ShopEasy is a production-grade, cloud-native e-commerce application built to demonstrate modern CI/CD and GitOps practices using Jenkins, Docker, Kubernetes (AWS EKS), and Argo CD.

This repository represents Version 2.0 of the application, which includes major UI improvements, functional enhancements, and an automated deployment workflow aligned with real-world DevOps practices.


              Architecture Overview

          Developer → GitHub → Jenkins (CI)
                     ↓
                     
              Docker Image Build & Push
                     ↓
                     
          Kubernetes Manifests Repository
                     ↓
                     
                Argo CD (GitOps)
                     ↓
                     
           AWS EKS Kubernetes Cluster
                     ↓
                     
               ShopEasy Web Application

Technology Stack

Application  
Backend: Flask (Python)  
Frontend: HTML, CSS, Bootstrap  

DevOps and Cloud:

CI: Jenkins (Multibranch Pipeline)  
Containerization: Docker  
Container Registry: Docker Hub  
Orchestration: Kubernetes (AWS EKS)  
Continuous Deployment: Argo CD (GitOps)  
Cloud Provider: AWS  
Version Control: Git and GitHub  
CI/CD and GitOps Workflow

Continuous Integration:

Jenkins multibranch pipeline  
Source code checkout from GitHub  
Docker image build  
Docker image push to registry  
Automated update of Kubernetes manifests with new image versions

Continuous Deployment:

Argo CD monitors Kubernetes manifests stored in Git  
Automatically synchronizes changes to the EKS cluster  
Provides application health monitoring and deployment visibility


Version History:

Version 1.0 – Initial Release  
Basic Flask e-commerce application
Dockerized application
Kubernetes deployment on AWS EKS



Version 2.0 – Feature Enhancement Release (Current)  
Complete UI redesign
Product catalog with categories
Order tracking interface
User account UI
Wishlist and cart indicators
Updated footer with versioning and author details
Refactored codebase for better maintainability
Stable GitOps-based deployment workflow


Application Footer (v2.0)

© 2025 ShopEasy v2.0 | CI/CD & GitOps Enabled | Developed by Mohammad Ikram

Author  
Mohammad Ikram

DevOps | Cloud | CI/CD | GitOps

GitHub: https://github.com/mohammadikram01

LinkedIn: www.linkedin.com/in/mohammad-ikram
