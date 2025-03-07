# s3\-version\-lifecycle\-policy\-check<a name="s3-version-lifecycle-policy-check"></a>

Checks if Amazon Simple Storage Service \(Amazon S3\) version enabled buckets have lifecycle policy configured\. The rule is NON\_COMPLIANT if Amazon S3 lifecycle policy is not enabled\. 

**Identifier:** S3\_VERSION\_LIFECYCLE\_POLICY\_CHECK

**Trigger type:** Configuration changes

**AWS Region:** All supported AWS regions

**Parameters:**

bucketNames \(Optional\)Type: CSV  
Comma\-separated list of Amazon S3 bucket names that have lifecycle policy enabled\.

## AWS CloudFormation template<a name="w76aac11c31c17b7d461c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.