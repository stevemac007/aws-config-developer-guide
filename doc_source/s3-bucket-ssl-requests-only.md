# s3\-bucket\-ssl\-requests\-only<a name="s3-bucket-ssl-requests-only"></a>

Checks if Amazon S3 buckets have policies that require requests to use Secure Socket Layer \(SSL\)\. The rule is COMPLIANT if buckets explicitly deny access to HTTP requests\. The rule is NON\_COMPLIANT if bucket policies allow HTTP requests\.

**Identifier:** S3\_BUCKET\_SSL\_REQUESTS\_ONLY

**Trigger type:** Configuration changes

**AWS Region:** All supported AWS regions

**Parameters:**

None  

## AWS CloudFormation template<a name="w76aac11c31c17b7d453c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.