# React CI/CD Pipeline on AWS

![AWS CI/CD Pipeline](media/image1.png)

This project implements a complete CI/CD pipeline for a React application using AWS services. The pipeline automates building, testing, and deployment processes.

## Key Features
- 🚀 Automated deployments on code push
- ✅ Unit and integration testing
- 🔐 Secure AWS infrastructure
- 📦 Production-ready builds
- 🔄 Zero-downtime deployments

## Pipeline Architecture
![Pipeline Architecture](media/image5.png)
1. **Source**: GitHub repository
2. **Build**: AWS CodeBuild
3. **Test**: Jest + Testing Library
4. **Deploy**: AWS S3 + CloudFront
5. **Notify**: AWS SNS

## Prerequisites
- AWS Account
- Node.js 16.x+
- AWS CLI v2
- Git

## Setup Instructions

### 1. Clone Repository
```bash
git clone https://github.com/your-username/react-cicd-aws.git
cd react-cicd-aws
