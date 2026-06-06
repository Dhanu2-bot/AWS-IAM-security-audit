# AWS-IAM-security-audit
INTERN ID: CITS811
# AWS IAM Security Audit

## Project Overview

This project focuses on performing a security audit of AWS Identity and Access Management (IAM) configurations. The audit reviews IAM users, groups, roles, password policies, Multi-Factor Authentication (MFA), and access keys to identify potential security risks and recommend improvements.

---

## Objective

The objective of this project is to:

- Review IAM security configurations
- Identify security vulnerabilities
- Verify password policies
- Check MFA configuration
- Review user permissions
- Audit access keys
- Recommend security best practices

---

## AWS Services Used

- AWS Identity and Access Management (IAM)
- Amazon S3 (for project storage)

---

## Audit Scope

The following IAM components were reviewed:

1. IAM Users
2. IAM Groups
3. IAM Roles
4. Password Policy
5. Multi-Factor Authentication (MFA)
6. Access Keys
7. User Permissions

---

## Audit Steps

### Step 1: Review IAM Users
- Verified available IAM users
- Reviewed console access settings

### Step 2: Check MFA Configuration
- Verified MFA status for IAM users
- Identified accounts without MFA

### Step 3: Review Password Policy
- Checked password complexity requirements
- Verified minimum password length

### Step 4: Review User Permissions
- Reviewed attached IAM policies
- Identified excessive permissions

### Step 5: Review IAM Groups
- Verified group-based access management

### Step 6: Review IAM Roles
- Audited roles and trust relationships

### Step 7: Review Access Keys
- Checked active access keys
- Verified key management practices

---

## Findings

| Audit Area | Status |
|------------|---------|
| IAM Users | Pass |
| Password Policy | Pass |
| IAM Groups | Pass |
| IAM Roles | Pass |
| MFA Configuration | Review Required |
| User Permissions | Review Required |
| Access Keys | Review Required |

---

## Recommendations

- Enable MFA for all IAM users
- Apply Principle of Least Privilege
- Rotate access keys every 90 days
- Remove unused IAM users
- Review permissions regularly
- Avoid using root account for daily operations
- Conduct periodic security audits

---

## Project Structure

```
aws-iam-security-audit/
│
├── README.md
├── AWS_IAM_Audit_Report.docx
├── AWS_IAM_Security_Audit_Findings.docx
├── AWS_IAM_Recommendations_Report.docx
└── screenshots/
```

---

## Screenshots

1. IAM Dashboard
2. IAM Users List
3. MFA Configuration
4. Password Policy
5. User Permissions
6. IAM Groups
7. IAM Roles
8. Access Keys
9. Findings Table
10. Recommendations Report

---

## Conclusion

The AWS IAM Security Audit was successfully completed by reviewing IAM users, groups, roles, password policies, MFA settings, and access keys. The audit identified areas for security improvement and provided recommendations to strengthen access management and security within the AWS environment.

---

## Author

AWS Cloud Computing Internship Project
