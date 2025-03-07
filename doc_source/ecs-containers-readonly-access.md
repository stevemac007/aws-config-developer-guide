# ecs\-containers\-readonly\-access<a name="ecs-containers-readonly-access"></a>

Checks if Amazon Elastic Container Service \(Amazon ECS\) Containers only have read\-only access to its root filesystems\. The rule is NON\_COMPLIANT if the readonlyRootFilesystem parameter in the container definition of ECSTaskDefinitions is set to ‘false’\. 

**Identifier:** ECS\_CONTAINERS\_READONLY\_ACCESS

**Trigger type:** Configuration changes

**AWS Region:** All supported AWS regions

**Parameters:**

None  

## AWS CloudFormation template<a name="w76aac11c31c17b7d207c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.