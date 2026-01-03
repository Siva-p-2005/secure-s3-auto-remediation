# Secure S3 Auto-Remediation Project (AWS)

## 🚀 Project Overview

This project automatically detects and secures publicly exposed Amazon S3 buckets
by enforcing Block Public Access settings. It uses AWS Lambda to scan all S3 buckets,
fix security issues automatically, and send real-time email alerts.

---

## 🧱 Architecture Overview

Manual or Scheduled Trigger  
↓  
AWS Lambda (Security Scan & Auto Fix)  
↓  
Amazon S3 (Scan & Secure)  
&  
Amazon SNS (Email Alert)

---

## 🛠️ AWS Services Used

- Amazon S3 – Secure object storage  
- AWS Lambda – Serverless automation  
- AWS IAM – Permissions  
- Amazon SNS – Email notifications  
- AWS CloudWatch – Logs  
- AWS CloudTrail – Auditing

---
