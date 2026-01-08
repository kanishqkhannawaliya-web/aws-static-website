# AWS Static Website with CI/CD (GitHub Actions)

## 📌 Project Overview
This project demonstrates a production-ready static website hosted on AWS S3 with automated CI/CD deployment using GitHub Actions.

The architecture follows DevOps best practices including IAM security, GitHub Secrets, and automated deployments.

---

## 🏗 Architecture
- GitHub Repository (Source Code)
- GitHub Actions (CI/CD Pipeline)
- AWS IAM (Secure access)
- AWS S3 (Static Website Hosting)
- AWS CloudFront *(Pending account verification)*

---

## 🔐 Security Implementation
- IAM user with least-privilege access
- AWS credentials stored securely using GitHub Secrets
- No hard-coded secrets in repository
- Public access restricted at bucket level

---

## 🚀 CI/CD Workflow
1. Code pushed to `main` branch
2. GitHub Actions triggers deployment
3. AWS credentials loaded securely
4. Website files synced to S3 automatically

---

## 🧪 Deployment Proof
- GitHub Actions workflow runs successfully
- S3 website accessible via public endpoint

---

## 🧠 Skills Demonstrated
- AWS S3 Static Hosting
- GitHub Actions CI/CD
- IAM & Security Best Practices
- Cloud Deployment Automation
- DevOps Workflow Design

---

## 📍 Future Improvements
- Attach CloudFront CDN
- Add HTTPS using ACM
- Enable monitoring and logging
