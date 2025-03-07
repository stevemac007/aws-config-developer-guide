# s3\-bucket\-level\-public\-access\-prohibited<a name="s3-bucket-level-public-access-prohibited"></a>

Checks if Amazon Simple Storage Service \(Amazon S3\) buckets are publicly accessible\. This rule is NON\_COMPLIANT if an Amazon S3 bucket is not listed in the `excludedPublicBuckets` parameter and bucket level settings are public\. 

**Identifier:** S3\_BUCKET\_LEVEL\_PUBLIC\_ACCESS\_PROHIBITED

**Trigger type:** Configuration changes

**AWS Region:** All supported AWS regions except China \(Beijing\), China \(Ningxia\), AWS GovCloud \(US\-East\), AWS GovCloud \(US\-West\), Asia Pacific \(Jakarta\), Asia Pacific \(Osaka\) Region

**Parameters:**

excludedPublicBuckets \(Optional\)Type: CSV  
Comma\-separated list of known allowed public Amazon S3 bucket names\.

## AWS CloudFormation template<a name="w76aac11c31c17b7d437c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.