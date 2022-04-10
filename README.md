# Create VPC stack
```sh
aws cloudformation create-stack --stack-name MyNetwork --template-body file://base-vpc.yml
aws cloudformation wait stack-create-complete --stack-name MyNetwork
```
# Update VPC stack
```sh
aws cloudformation update-stack --stack-name MyNetwork --template-body file://base-vpc.yml
aws cloudformation wait stack-update-complete --stack-name MyNetwork
```
# Delete VPC stack

aws cloudformation delete-stack --stack-name MyNetwork
aws cloudformation wait stack-delete-complete --stack-name MyNetwork
```
# describe-stacks
```sh
aws cloudformation describe-stacks
```
