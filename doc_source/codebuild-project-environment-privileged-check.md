# codebuild\-project\-environment\-privileged\-check<a name="codebuild-project-environment-privileged-check"></a>

Checks if an AWS CodeBuild project environment has privileged mode enabled\. The rule is NON\_COMPLIANT for a CodeBuild project if ‘privilegedMode’ is set to ‘true’\. 

**Identifier:** CODEBUILD\_PROJECT\_ENVIRONMENT\_PRIVILEGED\_CHECK

**Trigger type:** Configuration changes

**AWS Region:** All supported AWS regions except Asia Pacific \(Osaka\) Region

**Parameters:**

exemptedProjects \(Optional\)Type: CSV  
Comma\-separated list of CodeBuild project names that are allowed to have ‘privilegedMode’ with value ‘true’\.

## AWS CloudFormation template<a name="w76aac11c31c17b7d101c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.