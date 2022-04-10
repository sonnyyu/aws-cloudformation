# Create stack
aws cloudformation create-stack --stack-name MyNetwork --template-body file://MyNetwork.yml

aws cloudformation wait stack-create-complete --stack-name MyNetwork

# Update stack
aws cloudformation update-stack --stack-name MyNetwork --template-body file://MyNetwork.yml

aws cloudformation wait stack-update-complete --stack-name MyNetwork

# Delete stack
aws cloudformation delete-stack --stack-name MyNetwork
aws cloudformation wait delete-stack-complete --stack-name MyNetwork


