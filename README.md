# AWS Security Projects Repository

Welcome to my AWS Security Projects repository! This space showcases various projects and scripts I've developed to enhance and automate security within the Amazon Web Services ecosystem.

This repository aims to demonstrate my skills and understanding of AWS security best practices, automation techniques, and infrastructure-as-code principles. Feel free to explore the different projects and their associated documentation.

## Projects Overview

Here's a brief overview of the projects you'll find in this repository:

* **[Landing Zone Accelerator solution (LZA) ](LandingZoneAccelerator):** Automated deployment and configuration of the AWS Landing Zone Accelerator, a solution that helps you set up a secure, multi-account AWS environment based on AWS best practices. It provides a comprehensive framework for governance, security, and networking.
    * Key Technologies: AWS Landing Zone Accelerator, CloudFormation, AWS Organizations, IAM
    * Highlights: Fully automated deployment of a secure foundation, adherence to AWS best practices, centralized governance, streamlined multi-account management.
* **[Migration Acceleration Program from AWS (MAP)](MigrationAccelerationProgram):** Implementation of security best practices and automation within the context of an AWS Migration Acceleration Program (MAP) engagement. This project focuses on ensuring a secure and compliant migration of workloads to AWS, leveraging AWS security services and automation tools throughout the migration lifecycle.
    * Key Technologies: AWS Migration Acceleration Program (MAP) framework, AWS Security Hub, AWS Config, AWS CloudFormation, IAM
    * Highlights: Secure migration planning and execution, implementation of security controls during migration, leveraging AWS best practices for migrated workloads.
* **[Perimeter Security with WAF and Network Firewall](PerimeterSecurity):** Implementation of a robust perimeter security strategy leveraging AWS WAF (Web Application Firewall) to protect web applications from common web exploits and AWS Network Firewall to control network traffic at the VPC level, establishing clear boundaries and security rules for inbound and outbound traffic.
    * Key Technologies: AWS WAF, AWS Network Firewall, AWS CloudFormation, AWS Firewall Manager (optional), IAM
    * Highlights: Protection against OWASP Top 10 vulnerabilities, granular control over network traffic, centralized management of firewall rules (with Firewall Manager).
* **[Security Baseline](SecurityBaseline):** Establishment of a comprehensive security baseline across an AWS Organization, focusing on implementing foundational security controls as outlined in the provided checklist. This project involves deploying and configuring services like CentralView for inventory visibility, enabling Control Tower controls, enforcing IAM password policies, enabling MFA, centralizing security events, and activating security monitoring services like Security Hub, GuardDuty, IAM Access Analyzer, and Inspector.
    * Key Technologies: AWS Organizations, AWS Control Tower, AWS CentralView, IAM, AWS Config, AWS Security Hub, Amazon GuardDuty, AWS IAM Access Analyzer, Amazon Inspector, AWS Macie (as applicable), CloudFormation/Terraform (for automation).
    * Highlights: Centralized security posture management, enforcement of organizational security policies, enhanced visibility and threat detection across accounts, automated compliance checks.


## Getting Started

To explore a specific project, navigate to its dedicated directory within this repository. Each project directory will typically contain:

* **README.md:** A detailed explanation of the project, its architecture, how to deploy it (if applicable), and any relevant considerations.
* **Code/Scripts:** The source code, scripts, or configuration files for the project.
* **Diagrams (optional):** Architectural diagrams illustrating the project's components and flow.
* **Documentation (optional):** Additional documentation or guides related to the project.

## Technologies Used

This repository leverages a variety of AWS services and tools, including but not limited to:

* AWS Identity and Access Management (IAM)
* Amazon Virtual Private Cloud (VPC)
* AWS Network Firewall
* AWS Security Hub
* Amazon GuardDuty
* AWS Config
* AWS Systems Manager (SSM)
* AWS Lambda
* Amazon Simple Storage Service (S3)
* Amazon CloudWatch Logs
* AWS Organizations
* AWS Landing Zone Accelerator
* Infrastructure-as-Code (IaC) tools like Terraform and/or AWS CloudFormation (specific tools will be mentioned in individual project READMEs)
* Scripting languages such as Python and Bash (as applicable)

## Contributions

While this repository primarily showcases my personal projects, I am always open to feedback and suggestions. If you have any ideas for improvements or identify any issues, please feel free to open an issue or submit a pull request.

## Disclaimer

The projects and scripts in this repository are provided for educational and demonstrative purposes. While I have made efforts to ensure their functionality and security, they should be reviewed and tested thoroughly before being implemented in a production environment. I am not responsible for any issues or security vulnerabilities that may arise from the use of these projects.

## Contact

You can connect with me on https://www.linkedin.com/in/juliocesarqq/ or reach out via juliocesarqq@hotmail.com

Thank you for visiting my AWS Security Projects repository! I hope you find the content valuable.
