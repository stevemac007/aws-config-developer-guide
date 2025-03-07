# guardduty\-enabled\-centralized<a name="guardduty-enabled-centralized"></a>

Checks if Amazon GuardDuty is enabled in your AWS account and region\. If you provide an AWS account for centralization, the rule evaluates the Amazon GuardDuty results in the centralized account\. The rule is COMPLIANT when Amazon GuardDuty is enabled\.

**Identifier:** GUARDDUTY\_ENABLED\_CENTRALIZED

**Trigger type:** Periodic

**AWS Region:** All supported AWS regions except China \(Beijing\), China \(Ningxia\), AWS GovCloud \(US\-East\), Asia Pacific \(Jakarta\), Asia Pacific \(Osaka\), Europe \(Milan\), Middle East \(Bahrain\), Africa \(Cape Town\) Region

**Parameters:**

CentralMonitoringAccount \(Optional\)Type: String  
Comma separated list of AWS Accounts \(12\-digit\) where Amazon GuardDuty results are allowed to be centralized\.

## AWS CloudFormation template<a name="w76aac11c31c17b7d283c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.