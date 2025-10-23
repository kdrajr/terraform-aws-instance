# AWS EC2 Instance

This module creates EC2 Instance.

### Inputs

* ami_id - (Optional) Default to '''ami-09c813fb71547fc4f'''
* instance_type - (Required) User must supply instance type either t3.micro or t3.small or t3.medium
* sg_ids - (Required) User must supply a list of security group ids to attach to EC2 instance
* tags - (Optional) User can supply the tags to attach to EC2 instance

### Outputs

* public_ip - Public IP of the instance created
* private_ip - Private IP of the instance created