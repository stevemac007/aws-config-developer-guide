# iam\-policy\-blacklisted\-check<a name="iam-policy-blacklisted-check"></a>

Checks if for each IAM resource, a policy ARN in the input parameter is attached to the IAM resource\. The rule is NON\_COMPLIANT if the policy ARN is attached to the IAM resource\. AWS Config marks the resource as COMPLIANT if the IAM resource is part of the `exceptionList` parameter irrespective of the presence of the policy ARN\.

**Identifier:** IAM\_POLICY\_BLACKLISTED\_CHECK

**Trigger type:** Configuration changes

**AWS Region:** All supported AWS regions

**Parameters:**

policyArnsType: CSVDefault: arn:aws:iam::aws:policy/AdministratorAccess  
Comma\-separated list of IAM policy arns which should not be attached to any IAM entity\.

exceptionList \(Optional\)Type: CSV  
Comma\-separated list IAM users, groups, or roles that are exempt from this rule\. For example, users:\[user1;user2\], groups:\[group1;group2\], roles:\[role1;role2;role3\]\.

## AWS CloudFormation template<a name="w76aac11c31c17b7d297c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.