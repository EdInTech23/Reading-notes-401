Readings: Cloud Identity and Access Management (IAM) with AWS
Below you will find reading materials and additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

Reading
Lessons Learned from the Capital One Data Breach (PDF)

What were the three commands used for the attack?
Three Commands Used for the Attack:
The specific commands used in the Capital One data breach are not publicly detailed to avoid promoting similar attacks. However, in similar security incidents, attackers commonly use commands that:

Probe the environment to understand the resources and permissions available (aws sts get-caller-identity to identify the role and permissions of the compromised credentials).
Enumerate the S3 buckets or other resources accessible to the compromised credentials (aws s3 ls or similar commands to list accessible storage resources).
Extract data from accessible resources (aws s3 cp to copy data from an S3 bucket to their own environment).
What misconfiguration of AWS components allowed the attacker to access sensitive data?
Misconfiguration of AWS Components:
The Capital One data breach was significantly enabled by a misconfiguration in the AWS environment. Common misconfigurations that lead to such vulnerabilities include:

Improperly Configured IAM Roles: The attacker was able to assume an IAM role that had too broad permissions, including access to S3 buckets containing sensitive data.
Open Security Groups or Firewall Rules: Excessively permissive security groups or firewall rules that allow access to resources from any IP address or untrusted sources.
Server-Side Request Forgery (SSRF) Vulnerability: The application used by Capital One was vulnerable to SSRF, which allowed the attacker to query the AWS metadata service for credentials associated with the role assigned to the EC2 instance.
What are two of the AWS Governance practices that could have prevented such attack?
AWS Governance Practices to Prevent Such Attacks:
Implementing robust governance practices is crucial to preventing similar attacks. Two key AWS governance practices include:

Least Privilege Access: Ensuring that IAM roles and policies grant the minimum necessary permissions required for a task. Regularly reviewing and auditing IAM policies to remove unnecessary permissions can mitigate the risk of exploitation.
Regular Security Audits and Compliance Checks: Using AWS services like AWS Config, AWS CloudTrail, and AWS Security Hub to continuously monitor and audit the environment for compliance with security best practices and to detect unusual or unauthorized activities.
© Code Fellows 2024
