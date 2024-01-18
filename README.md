# Configure S3 Bucket with S3 Bucket Policies

In this scenario, the objective was to configure an S3 bucket with appropriate policies to ensure secure access control. The following steps were taken during the implementation:

## Project Overview

The project involved configuring an S3 bucket with specific policies to control access securely. Key configurations included:

- **S3 Bucket Creation:** Created an S3 bucket with two folders named Stage, Dev, and Prod.

- **Bucket Policy Implementation:** Wrote a bucket policy that allowed IAM user A to access only the Prod folder, ensured that all other users could access only the Dev folder, and implemented a policy preventing all IAM users from accessing the Prod folder.

## Access Control

The setup ensured controlled access to the sensitive data within the S3 bucket:

- **IAM User A Access:** Allowed IAM user A to access only the Prod folder.

- **Limited Access for Others:** Ensured that all other IAM users could access only the Dev folder.

- **Restriction on Prod Folder:** Implemented a policy preventing all IAM users from accessing the Prod folder.

## Benefits

The configuration provided the following benefits:

- **Enhanced Security:** Ensured that only authorized personnel (IAM user A) could access sensitive data in the Prod folder.

- **Controlled Access:** Dev folder remained accessible to other team members while restricting access to the Prod folder.

## Technology Stack

- **AWS Services:**
  - Amazon S3
  - AWS Identity and Access Management (IAM)

## Deployment Process

The deployment process focused on implementing policies to control access to specific folders within the S3 bucket.

## Conclusion

This configuration successfully provided enhanced security and control over the S3 bucket and its contents. IAM user A could access the Prod folder, while other team members had access to the Dev folder, ensuring controlled and secure access.

