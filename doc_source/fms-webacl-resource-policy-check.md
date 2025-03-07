# fms\-webacl\-resource\-policy\-check<a name="fms-webacl-resource-policy-check"></a>

Checks if the web ACL is associated with an Application Load Balancer, API Gateway stage, or Amazon CloudFront distributions\. When AWS Firewall Manager creates this rule, the FMS policy owner specifies the `WebACLId` in the FMS policy and can optionally enable remediation\.

**Identifier:** FMS\_WEBACL\_RESOURCE\_POLICY\_CHECK

**Trigger type:** Configuration changes

**AWS Region:** All supported AWS regions except Asia Pacific \(Jakarta\) Region

**Parameters:**

webACLIdType: String  
The WebACLId of the web ACL\.

resourceTags \(Optional\)Type: String  
The resource tags \(ApplicationLoadBalancer, ApiGatewayStage and CloudFront distributions\) that the rule should be associated with\. \(for example, \{ "tagKey1" : \["tagValue1"\], "tagKey2" : \["tagValue2", "tagValue3"\] \}\)

excludeResourceTags \(Optional\)Type: boolean  
If true, exclude resources that match resourceTags\.

fmsManagedToken \(Optional\)Type: String  
A token generated by AWS Firewall Manager when creating the rule in customer account\. AWS Config ignores this parameter when customer creates this rule\.

fmsRemediationEnabled \(Optional\)Type: boolean  
If true, AWS Firewall Manager will update non\-compliant resources according to FMS policy\. AWS Config ignores this parameter when customer creates this rule\.

## AWS CloudFormation template<a name="w76aac11c31c17b7d277c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.