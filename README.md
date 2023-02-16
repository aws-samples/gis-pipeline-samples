## GIS Pipeline Automation with AWS Cloudformation

 
1. This cloudformation template creates an windows  EC2 instance with Agsoft Metashape Professional software pre-installed. User is responsible for activating the software license.
2. By default, g4dn.2xlarge instance is created. User can change this to another instance type in template or modify the instance type from AWS console after instance is created.
3. Use this template in ap-south-1 region only.
 
Pre-requisite to use this template:
 
1. Active AWS account
2. VPC with public subnet and security group (with RDP port open to required IP/cidr block)


NOTE- These templates are only provided as a reference and are not officially part of AWS documentation. Users can download the samples and make changes as per the requirement.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

