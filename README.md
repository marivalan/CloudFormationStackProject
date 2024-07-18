**The project provisions several resources, including a Lambda function, API Gateway REST API method, DynamoDB table
and an IAM role with the necessary IAM policies.
**It's crucial to add dependencies between these resources to ensure they are created in the correct order,
guaranteeing proper permission delegation.
The following image describes the resources and dependencies,
