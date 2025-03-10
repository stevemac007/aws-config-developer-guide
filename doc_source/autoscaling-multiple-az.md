# autoscaling\-multiple\-az<a name="autoscaling-multiple-az"></a>

Checks if the Auto Scaling group spans multiple Availability Zones\. The rule is NON\_COMPLIANT if the Auto Scaling group does not span multiple Availability Zones\. 

**Identifier:** AUTOSCALING\_MULTIPLE\_AZ

**Trigger type:** Configuration changes

**AWS Region:** All supported AWS regions

**Parameters:**

minAvailabilityZones \(Optional\)Type: int  
Minimum number of expected Availability zones\.

## AWS CloudFormation template<a name="w76aac11c31c17b7c37c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.