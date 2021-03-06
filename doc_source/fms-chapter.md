# AWS Firewall Manager<a name="fms-chapter"></a>

AWS Firewall Manager simplifies your AWS WAF Classic, AWS Shield Advanced, and Amazon VPC security groups administration and maintenance tasks across multiple accounts and resources\. With Firewall Manager, you set up your AWS WAF Classic firewall rules, Shield Advanced protections, and Amazon VPC security groups just once\. The service automatically applies the rules and protections across your accounts and resources, even as you add new resources\. 

Firewall Manager provides these benefits:
+ Helps to protect resources across accounts
+ Helps to protect all resources of a particular type, such as all Amazon CloudFront distributions
+ Helps to protect all resources with specific tags
+ Automatically adds protection to resources that are added to your account
+ Allows you to subscribe all member accounts in an AWS Organizations organization to AWS Shield Advanced, and automatically subscribes new in\-scope accounts that join the organization
+ Allows you to apply security group rules to all member accounts or specific subsets of accounts in an AWS Organizations organization, and automatically applies the rules to new in\-scope accounts that join the organization
+ Lets you use your own rules, or purchase managed rules from AWS Marketplace

Firewall Manager is particularly useful when you want to protect your entire organization rather than a small number of specific accounts and resources, or if you frequently add new resources that you want to protect\. Firewall Manager also provides centralized monitoring of DDoS attacks across your organization\.

**Topics**
+ [AWS Firewall Manager Pricing](aws-fms-pricing.md)
+ [AWS Firewall Manager Prerequisites](fms-prereq.md)
+ [Getting Started with AWS Firewall Manager to Enable AWS WAF Classic Rules](getting-started-fms.md)
+ [Getting Started with AWS Firewall Manager to Enable AWS Shield Advanced Protection](getting-started-fms-shield.md)
+ [Getting Started with AWS Firewall Manager Amazon VPC Security Group Policies](getting-started-fms-security-group.md)
+ [Working with Rule Groups](working-with-rule-groups.md)
+ [Working with AWS Firewall Manager Policies](working-with-policies.md)
+ [Tutorial: Creating a Policy with Hierarchical Rules](hierarchical-rules.md)
+ [Viewing Resource Compliance with a Policy](fms-compliance.md)
+ [AWS Firewall Manager Findings](fms-findings.md)
+ [Designating a Different Account as the AWS Firewall Manager Administrator Account](fms-change-administrator.md)
+ [Security in AWS Firewall Manager](fms-security.md)
+ [AWS Firewall Manager Quotas](fms-limits.md)