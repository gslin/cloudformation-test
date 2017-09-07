# cloudformation-test

    aws cloudformation create-stack --stack-name test --template-body file://01-ec2-simple.yml
    aws cloudformation update-stack --stack-name test --template-body file://01-ec2-simple.yml
    aws cloudformation delete-stack --stack-name test
