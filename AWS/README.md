
# 1. How use AWS-CLI

```bash
aws configure

    AWS Access Key ID [********************]:
    AWS Secret Access Key [*******************]:
    Default region name [sa-east-1]:
    Default output format [json]:
```

# 2. How use CDK (Cloud Development Kit)

- Install CDK

```bash
npm install -g aws-cdk
cdk --version
cdk init app --language=typescript
```

- Before deploy the stack, you need to bootstrap the account, this command will create a bucket in S3 to store the CDK templates

```bash
cdk bootstrap
```

- Deploy the stack

```bash
cdk deploy
```