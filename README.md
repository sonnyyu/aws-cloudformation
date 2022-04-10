# Create stack
```sh
aws cloudformation create-stack --stack-name MyNetwork --template-body file://base-vpc.yml
aws cloudformation wait stack-create-complete --stack-name MyNetwork
```
# Update stack
```sh
aws cloudformation update-stack --stack-name MyNetwork --template-body file://base-vpc.yml
aws cloudformation wait stack-update-complete --stack-name MyNetwork
```
# Delete stack
```sh
aws cloudformation delete-stack --stack-name MyNetwork
aws cloudformation wait delete-stack-complete --stack-name MyNetwork
```

