#### 24. Lambda Permissions Model

Each Lambda has 2 sets of permissions:

1. Function Policy: Other service use this permission to invoke Lambda functions
2. Execution Role: Used by the Lambda function to access different services that it depends on

![permissions](docs/img/001.png)
