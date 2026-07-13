\# 🔒 **AWS Security Audit \& Cost Optimization**



> End-to-end AWS Security Audit project demonstrating security assessment, compliance monitoring, remediation, and cost optimization using AWS native services.



\---



**# 📌 Project Overview**



This project demonstrates how to identify, analyze, remediate, and validate security vulnerabilities in an AWS environment using AWS native services.



The environment was intentionally configured with security misconfigurations, which were detected using AWS Config and AWS CloudTrail. Each finding was remediated following AWS Security Best Practices and validated after remediation. Cost optimization was implemented using AWS Cost Explorer and AWS Budgets.



\---



**# 🏗️ Architecture**



<p align="center">

<img src="Architecture/architecture.png" width="100%">

</p>



\---



**# 🛠️ AWS Services Used**



\- AWS IAM

\- Amazon EC2

\- Amazon EBS

\- Amazon S3

\- AWS Config

\- AWS CloudTrail

\- Amazon CloudWatch

\- AWS Budgets

\- AWS Cost Explorer

\- Security Groups



\---



**# 🎯 Objectives**



\- Identify AWS security vulnerabilities

\- Implement IAM security best practices

\- Secure Amazon S3

\- Encrypt Amazon EBS

\- Harden Security Groups

\- Monitor compliance using AWS Config

\- Enable auditing using CloudTrail

\- Optimize AWS costs



\---



**# ⚙️ Project Workflow**



```

Create Insecure Resources

&#x20;       │

&#x20;       ▼

AWS Config Detection

&#x20;       │

&#x20;       ▼

CloudTrail Logging

&#x20;       │

&#x20;       ▼

Security Analysis

&#x20;       │

&#x20;       ▼

Remediation

&#x20;       │

&#x20;       ▼

Compliance Validation

&#x20;       │

&#x20;       ▼

Cost Optimization

```



\---



**# 🚨 Security Findings**



|        Finding         | Severity | Status   |

|------------------------|----------|----------|

| IAM Users without MFA  | High     | ✅ Fixed |

| Public S3 Bucket       | Critical | ✅ Fixed |

| Wildcard IAM Policy    | Critical | ✅ Fixed |

| Unencrypted EBS Volume | High     | ✅ Fixed |

| Open Security Group    | High     | ✅ Fixed |



\---



\# 🔐 **Remediation**



\## **1.** Missing MFA on IAM Users



| Before | After |

|--------|-------|

| <img src="Screenshots/Before/before-iam-users-no-mfa.png" width="450"> | <img src="Screenshots/After/after-iam-users-mfa-enabled.png" width="450"> |



\### Actions Performed



\- Enabled Virtual MFA using Google Authenticator

\- Verified compliance using AWS Config



\---



\## **2**. Public Amazon S3 Bucket



| Before | After |

|--------|-------|

| <img src="Screenshots/Before/before-public-s3.png" width="450"> | <img src="Screenshots/After/after-s3-private.png" width="450"> |



\### Actions Performed



\- Enabled Block Public Access

\- Removed Bucket Policy

\- Enabled Server Side Encryption



\---



\## **3**. Overly Permissive IAM Policy



| Before | After |

|--------|-------|

| <img src="Screenshots/Before/before-wildcard-policy.png" width="450"> | <img src="Screenshots/After/after-iam-policy-removed.png" width="450"> |



\### Actions Performed



\- Detached wildcard IAM policy

\- Applied Least Privilege



\---



\## **4**. Unencrypted Amazon EBS Volume



| Before | After |

|--------|-------|

| <img src="Screenshots/Before/before-ebs-volume.png" width="450"> | <img src="Screenshots/After/after-ebs-encrypted.png" width="450"> |



\### Actions Performed



\- Created encrypted snapshot

\- Created encrypted EBS volume



\---



\## **5**. Open Security Group



| Before | After |

|--------|-------|

| <img src="Screenshots/Before/before-open-security-group.png" width="450"> | <img src="Screenshots/After/after-security-group.png" width="450"> |



\### Actions Performed



\- Removed public SSH access

\- Restricted access to My IP



\---



\# 📊 **AWS Config**



AWS Config continuously monitored AWS resources and validated compliance after remediation.



<p align="center">

<img src="Screenshots/After/after-config-dashboard.png" width="100%">

</p>



\---



\# 📜 **AWS CloudTrail**



CloudTrail recorded all management API activity for auditing and compliance.



<p align="center">

<img src="Screenshots/Before/before-cloudtrail-dashboard.png" width="100%">

</p>



\---



**# 💰 Cost Optimization**



\## AWS Cost Explorer



<p align="center">

<img src="Screenshots/After/cost-explorer.png" width="100%">

</p>



\---



\## **AWS Budget**



<p align="center">

<img src="Screenshots/After/aws-budget.png" width="100%">

</p>



\---



**# 📈 Skills Demonstrated**



\- AWS IAM

\- AWS Security

\- AWS Config

\- AWS CloudTrail

\- Amazon EC2

\- Amazon EBS

\- Amazon S3

\- Security Groups

\- CloudWatch

\- AWS Budgets

\- AWS Cost Explorer

\- Compliance Monitoring

\- Security Remediation

\- Cost Optimization



\---



**# 📂 Repository Structure**



```text

aws-security-audit-cost-optimization/

│

├── README.md

├── Architecture/

├── Screenshots/

│   ├── Before/

│   └── After/

├── Policies/

```



\---



\# 👨‍💻 Author



\*\*Akash\*\*



\- 🎓 Final Year B.Tech (Computer Science Engineering)

\- ☁️ AWS Certified Solutions Architect – Associate (SAA-C03)

