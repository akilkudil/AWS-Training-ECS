# AWS-Training-ECS
AWS-Training-ECS


Getting started with ECR:

http://docs.aws.amazon.com/AmazonECR/latest/userguide/ECR_AWSCLI.html

Prerequisites:

1. Create IAM User attached to Administrator group with AdministratorAccess
2.Create IAM Role 
	(a) ecs-instance-role : AmazonEC2ContainerServiceforEC2Role(CloudWatch, ECR, ECS)
            http://docs.aws.amazon.com/AmazonECS/latest/developerguide/instance_IAM_role.html
	(b) ecs-service-role : AmazonEC2ContainerServiceRole (EC2, ELB, ELB2)
        (c) Also check Amazon EC2 Container Service Task Role
3. Create Keypair
4. Create VPC
5. Create SG

Steps:
1. select Community AMIs and search for amazon-ecs-optimized Amis
2. Launch instances with ecs-instance-role with Terminate shutdown behaviour with keypair for ssh/rdp access
3. create task definition




