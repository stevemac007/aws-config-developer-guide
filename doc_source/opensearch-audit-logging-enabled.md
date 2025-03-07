# opensearch\-audit\-logging\-enabled<a name="opensearch-audit-logging-enabled"></a>

Checks if Amazon OpenSearch Service domains have audit logging enabled\. The rule is NON\_COMPLIANT if an OpenSearch Service domain does not have audit logging enabled\. 

**Identifier:** OPENSEARCH\_AUDIT\_LOGGING\_ENABLED

**Trigger type:** Configuration changes

**AWS Region:** All supported AWS regions except Asia Pacific \(Osaka\), Europe \(Milan\), Africa \(Cape Town\) Region

**Parameters:**

cloudWatchLogsLogGroupArnList \(Optional\)Type: CSV  
Comma\-separated list of Amazon CloudWatch Logs log groups that should be configured for audit logs\.

## AWS CloudFormation template<a name="w76aac11c31c17b7d351c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.