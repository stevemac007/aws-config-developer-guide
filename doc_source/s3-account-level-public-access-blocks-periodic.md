# s3\-account\-level\-public\-access\-blocks\-periodic<a name="s3-account-level-public-access-blocks-periodic"></a>

Checks if the required public access block settings are configured from account level\. 

**Identifier:** S3\_ACCOUNT\_LEVEL\_PUBLIC\_ACCESS\_BLOCKS\_PERIODIC

**Trigger type:** Periodic

**AWS Region:** All supported AWS regions except China \(Beijing\), China \(Ningxia\), AWS GovCloud \(US\-East\), AWS GovCloud \(US\-West\) Region

**Parameters:**

IgnorePublicAcls \(Optional\)Type: String  
IgnorePublicAcls is enforced or not, default True

BlockPublicPolicy \(Optional\)Type: String  
BlockPublicPolicy is enforced or not, default True

BlockPublicAcls \(Optional\)Type: String  
BlockPublicAcls is enforced or not, default True

RestrictPublicBuckets \(Optional\)Type: String  
RestrictPublicBuckets is enforced or not, default True

## AWS CloudFormation template<a name="w76aac11c31c17b7d429c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.