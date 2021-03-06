# Step 4: Configure Amazon SNS Notifications and Amazon CloudWatch Alarms<a name="get-started-fms-shield-cloudwatch"></a>

You can monitor your protected resources for potential DDoS activity using Amazon SNS\. To receive notification of possible attacks, create an Amazon SNS topic for each Region\.<a name="get-started-fms-shield-sns-procedure"></a>

**To create an Amazon SNS topic in Firewall Manager \(console\)**

1. Sign in to the AWS Management Console using the Firewall Manager administrator account that you set up in the prerequisites, and then open the Firewall Manager console at [https://console.aws.amazon.com/wafv2/fms](https://console.aws.amazon.com/wafv2/fms)\. 
**Note**  
For information about setting up a Firewall Manager administrator account, see [Step 2: Set the AWS Firewall Manager Administrator Account](enable-integration.md)\.

1. In the navigation pane, under **AWS FMS**, choose **Settings**\.

1. Choose **Create new topic**\.

1. Enter a topic name\.

1. Enter an email address that the Amazon SNS messages will be sent to, and then choose **Add email address**\.

1. Choose **Update SNS configuration**\.

You can continue from this step without configuring Amazon SNS notifications or CloudWatch alarms\. However, doing so significantly reduces your visibility of possible DDoS events\.

After you configure the Amazon SNS notifications and CloudWatch alarms, we recommend that you follow the instructions in [Step 5: Deploy AWS WAF Classic Rules](get-started-fms-shield-deploy-waf-automations.md)\.