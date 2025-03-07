# efs\-access\-point\-enforce\-root\-directory<a name="efs-access-point-enforce-root-directory"></a>

Checks if Amazon Elastic File System \(Amazon EFS\) access points are configured to enforce a root directory\. The rule is NON\_COMPLIANT if the value of 'Path' is set to '/' \(default root directory of the file system\)\. 

**Identifier:** EFS\_ACCESS\_POINT\_ENFORCE\_ROOT\_DIRECTORY

**Trigger type:** Configuration changes

**AWS Region:** All supported AWS regions

**Parameters:**

approvedDirectories \(Optional\)Type: CSV  
Comma\-separated list of subdirectory paths that are approved for Amazon EFS access point root directory enforcement\.

## AWS CloudFormation template<a name="w76aac11c31c17b7d219c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.