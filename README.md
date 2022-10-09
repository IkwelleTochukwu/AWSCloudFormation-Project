# AWSCloudFormation-Project

# You are asked to create three-tier architecture and perform following tasks in each tier:

1. Web tier: Launch an instance in the public subnet so that the instance should allow 
HTTP and SSH from the Internet
2. Application tier: Launch an instance in the private subnet of the web tier, and it 
should allow only SSH from the public subnet of the web tier 
3. DB tier: Launch an RDS MySQL instance in the private subnet, and it should allow 
connection on port 3306 only from the private subnet of the application tier
4. Setup a Route 53 hosted zone, and direct the traffic to the EC2 instance

# You are also asked to propose a solution so that:
1. The development team can test the code without having to involve the System Admins 
and can invest their time in testing the code rather than provisioning, configuring, and 
updating the resources needed to test the code
2. When the development team deletes the stack,the RDS DB instance should not be 
deleted

# Project requirements:
A created hosted zone in Route53 in a AWS account

To work with the AWS::Route53::HostedZone::Id AWS-Specific parameter type.
