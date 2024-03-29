# sam-boilerplate

This is a boilerplate repo for aws sam

## Solution Overview

![](./doc/architecture.png)

## Prerequisites

### Setup Environment

* [Set Up Your AWS Account]()
* [Install AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
* [Install AWS SAM CLI]()

### Setup Credentials

```bash
export AWS_ACCESS_KEY_ID=""
export AWS_SECRET_ACCESS_KEY=""
export AWS_SESSION_TOKEN=""
aws sts get-caller-identity
```

## Dependency

* [Enterprise Network]

## Deploy 

### Local

```bash
aws sts get-caller-identity
sam build && sam deploy --guided
```

## Reference

* [Redrive Announcement](https://aws.amazon.com/about-aws/whats-new/2023/11/aws-step-functions-restarting-workflows-failure/)
* [Redrive Blog](https://aws.amazon.com/blogs/compute/introducing-aws-step-functions-redrive-a-new-way-to-restart-workflows/#:~:text=Redrive%20works%20for%20Standard%20Workflows,to%20redrive%2C%20and%20choose%20Redrive)
