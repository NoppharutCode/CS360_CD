1. Create an Amazon ECR repository to store your images.
2. Create security group and allow inbound as TCP/8080 and ssh/22
3. Create Key-Pair in order to be used  to access EC2 (you need to replace key at CD.yml)
4. After deploy if you want to run this CD again you need to delete ec2 by yourself before running it again
5. Set up AWS_ACCESS_KEY_ID, AWS_SECRET_ACCESS_KEY, AWS_SESSION_TOKEN at Secrets of repository (These values can be found awsacadeny console)
6. Access web service by http://{public ip}:8080