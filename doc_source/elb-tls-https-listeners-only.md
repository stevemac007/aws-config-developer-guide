# elb\-tls\-https\-listeners\-only<a name="elb-tls-https-listeners-only"></a>

Checks if your Classic Load Balancer is configured with SSL or HTTPS listeners\.
+ If the Classic Load Balancer does not have a listener configured, then the rule returns NOT\_APPLICABLE\.
+ The rule is COMPLIANT if the Classic Load Balancer listeners are configured with SSL or HTTPS\.
+ The rule is NON\_COMPLIANT if a listener is not configured with SSL or HTTPS\.

**Identifier:** ELB\_TLS\_HTTPS\_LISTENERS\_ONLY

**Trigger type:** Configuration changes

**AWS Region:** All supported AWS regions except Asia Pacific \(Jakarta\), Asia Pacific \(Osaka\) Region

**Parameters:**

None  

## AWS CloudFormation template<a name="w76aac11c31c17b7d267c17"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.