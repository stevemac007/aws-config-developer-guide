# ec2\-stopped\-instance<a name="ec2-stopped-instance"></a>

Checks if there are instances stopped for more than the allowed number of days\. The instance is NON\_COMPLIANT if the state of the ec2 instance has been stopped for longer than the allowed number of days\.

**Identifier:** EC2\_STOPPED\_INSTANCE

**Trigger type:** Periodic

**AWS Region:** All supported AWS regions except Asia Pacific \(Jakarta\), Asia Pacific \(Osaka\), Europe \(Milan\), Africa \(Cape Town\) Region

**Parameters:**

AllowedDays \(Optional\)Type: intDefault: 30  
The number of days an ec2 instance can be stopped before it is NON\_COMPLIANT\. The default number of days is 30\.

## AWS CloudFormation template<a name="w76aac11c31c17b7d191c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.