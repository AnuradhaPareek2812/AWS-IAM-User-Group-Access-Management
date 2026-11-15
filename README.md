# AWS IAM User and Group Access Management

## Project Overview
This project demonstrates Identity and Access Management (IAM) in AWS. It includes creating IAM groups, assigning AWS managed policies, and testing permissions using the IAM Policy Simulator.

## Objectives
- Create IAM users and groups.
- Assign permissions using IAM policies.
- Implement role-based access control through groups.
- Test access permissions using the IAM Policy Simulator.

## IAM Groups and Policies

| IAM Group | Attached Policy | Purpose |
|---|---|---|
| Project-Testers | ViewOnlyAccess | View AWS resources |
| Project-Developers | AmazonEC2ReadOnlyAccess | View EC2 resources |
| Project-Admins | AmazonEC2FullAccess | Manage EC2 resources |

## Tools Used
- Amazon Web Services (AWS)
- AWS IAM Console
- IAM Policy Simulator

## Testing
The IAM Policy Simulator was used to verify permissions:
- Developers: DescribeInstances allowed; RunInstances denied.
- Admins: DescribeInstances and RunInstances allowed.

## Screenshots
See the screenshots folder for implementation and testing evidence.

## Learning Outcomes
- Understanding IAM users, groups and policies.
- Applying the principle of least privilege.
- Managing access using AWS managed policies.
- Testing permissions using the IAM Policy Simulator.

## Conclusion
Successfully implemented an AWS IAM access management project by creating groups, attaching policies, and verifying access permissions.