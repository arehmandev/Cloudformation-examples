# Cloudformation examples

This repo contains some Cloudformation examples (in JSON).

Appdemo.json is the main one. It creates:

VPC

1 Public Subnet

1 x t2 small Amazon Linux EC2 instance - private IP 10.0.0.10

Elastic IP attached to EC2

Cloud-init userdata bash script - installs polymer js application

Instructions:
```
1.Use AWS Cloudformation to load the template
2. (By default the name of the EC2 key is demokey, ensure you have a key called demokey)
3. Wait for template to finish, browse to IP of EC2 to see application
