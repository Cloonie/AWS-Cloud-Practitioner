# Amazon Web Serivce (AWS) Cloud Practitioner

# Security

## AWS Shared Responsibility Model

## AWS Identity and Access Management (IAM)
## User Permissions and Access

AWS Identity and Access Management (IAM)
enables you to manage access to AWS services and resources securely.

Root User account
This user has complete access to all AWS services and resources in the account, it is not recommend to use this account for everyday tasks.

IAM Users
It is an indentity created in AWS. It represents the person or application that interacts with AWS services and resources. It consist of a name and credentials. By default when created it has no permissions associated with it.

IAM Policies
An IAM policy is a document that allows or denies permissions to AWS services and resources. IAM policies enable you to customize users’ levels of access to resources.
Least privilege security principle
you help to prevent users or roles from having more permissions than needed to perform their tasks.

IAM Groups
An IAM group is a collection of IAM users. When you assign an IAM policy to a group, all users in the group are granted permissions specified by the policy.

IAM Roles
An IAM role is an identity that you can assume to gain temporary access to permissions at different times.

Multi-factor authentication
An extra layer of security after your login credentials. For example, a code that is sen to your AWS MFA device

## AWS Organizations