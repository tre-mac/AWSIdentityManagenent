# AWS Identity Managenent

AWS IAM Lab: Introduction to Identity and Access Management
Overview
This repository contains the documentation and configuration details for a lab exploring AWS Identity and Access Management (IAM). The lab focuses on managing users, security credentials, and permissions to control access to AWS resources.

Objectives
Create IAM Users and Groups.

Apply IAM Policies to groups to define specific capabilities.

Demonstrate a real-world scenario by adding users to groups based on job functions.

Use the IAM Sign-in URL to test account access.

Experiment with the effects of policies on service access.
_____________________________________________________________________________________________
Lab Configuration
1. User & Group Assignments
The following users and groups were created to simulate a corporate environment:

| User | Group | Permissions Inherited |

| user-1 | S3-Support | Read-Only access to Amazon S3 |

| user-2 | EC2-Support | Read-Only access to Amazon EC2 |

| user-3 | EC2-Admin | View, Start, and Stop Amazon EC2 instances |

