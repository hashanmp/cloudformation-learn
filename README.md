These requirements are not must do’s. But If you do them you can score more points in the assessment.
1. Automate this entire setup, so anyone can provision/destroy the setup using a single click of a button
   I.
   You can use a suitable AWS or any cloud/virtual service or any other suitable tool/template to
   automate infrastructure provisioning/destruction.
###   DB > RDS
reference:
https://computingforgeeks.com/setup-aws-rds-mysql-db-instance-with-cloudformation/
   
### Service > EC2 inside docker
reference: 
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/quickref-autoscaling.html

https://github.com/awsdocs/aws-cloudformation-user-guide/blob/main/doc_source/example-templates-autoscaling.md
###   VPC > 2 AZs/ 2 private subnets / 2 public subnets
reference: https://docs.aws.amazon.com/codebuild/latest/userguide/cloudformation-vpc-template.html

   II.
   You can use any configuration management tool (such as Puppet, Chef or Ansible) to bootstrap the
   server.
   
2. Business requirement is to make the website available 9*5. Do the required to support this business requirement
   
   without any manual intervention of Application Support team.
3. Ensure availability and reliability of this setup
4. Ensure the solution is cost effective.
5. Solution you suggest should


