# elasticsearch\-logs\-to\-cloudwatch<a name="elasticsearch-logs-to-cloudwatch"></a>

Checks if Amazon OpenSearch Service \(OpenSearch Service\) domains are configured to send logs to Amazon CloudWatch Logs\. The rule is COMPLIANT if a log is enabled for an OpenSearch Service domain\. This rule is NON\_COMPLIANT if logging is not configured\. 

**Identifier:** ELASTICSEARCH\_LOGS\_TO\_CLOUDWATCH

**Trigger type:** Configuration changes

**AWS Region:** All supported AWS regions except China \(Beijing\), China \(Ningxia\), AWS GovCloud \(US\-East\), AWS GovCloud \(US\-West\) Region

**Parameters:**

logTypes \(Optional\)Type: CSV  
Comma\-separated list of logs that are enabled\. Valid values are 'search', 'index', 'error'\.

## AWS CloudFormation template<a name="w76aac11c31c17b7d245c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.