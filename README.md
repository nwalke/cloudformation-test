# CloudFormation Test

Trying my hand at creating a CF stack!

This will standup a web service (the Ubuntu Apache default page) inside a VPC with an ELB and AutoScaling for good measure.  It uses Chef client in local mode to run the Apache2 cookbook.

To launch in your account, click this button:

[![cloudformation-launch-stack](cloudformation-launch-stack.png?raw=true)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=nwalke-cf-test&templateURL=https://s3.amazonaws.com/nwalke-cf-test/main.yaml)  
