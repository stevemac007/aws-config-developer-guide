# lambda\-vpc\-multi\-az\-check<a name="lambda-vpc-multi-az-check"></a>

Checks if Lambda has more than 1 availability zone associated\. The rule is NON\_COMPLIANT if only 1 availability zone is associated with the Lambda or the number of availability zones associated is less than number specified in the optional parameter\. 

**Identifier:** LAMBDA\_VPC\_MULTI\_AZ\_CHECK

**Trigger type:** Configuration changes

**AWS Region:** All supported AWS regions except Asia Pacific \(Osaka\) Region

**Parameters:**

availabilityZones \(Optional\)Type: int  
Number of expected Availability zones\.

## AWS CloudFormation template<a name="w76aac11c31c17b7d337c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.