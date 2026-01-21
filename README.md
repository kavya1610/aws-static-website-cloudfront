# Secure Static Website Hosting on AWS (S3 + CloudFront)

## 📌 Project Overview
This project demonstrates how to host a static website on AWS using a secure, production-style architecture.

The website is stored in a private Amazon S3 bucket and served globally using Amazon CloudFront with HTTPS enabled.

## 🏗️ Architecture
- Amazon S3 (private bucket for static files)
- Amazon CloudFront (CDN for global content delivery)
- IAM best practices (separate admin user, no root usage)
- HTTPS enforced via CloudFront

## 🔒 Security
- S3 bucket is NOT publicly accessible
- CloudFront is the only service allowed to access S3
- No public read permissions on the bucket

## 💸 Cost Awareness
- AWS WAF was intentionally not enabled to avoid unnecessary cost
- Built using AWS Free Tier–friendly services

## 🚀 Live Demo
CloudFront URL:d2uyy29cmc2o5s.cloudfront.net


## 📚 What I Learned
- Secure static website hosting on AWS
- Using CloudFront with private S3 origins
- IAM best practices for real-world projects
- CDN caching and HTTPS configuration

## 🔮 Future Improvements
- CI/CD pipeline using GitHub Actions
- Infrastructure as Code using Terraform
- Custom domain with Route 53

