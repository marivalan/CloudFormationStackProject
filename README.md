**The project provisions several resources, including a Lambda function, API Gateway REST API method, DynamoDB table
and an IAM role with the necessary IAM policies.
**It's crucial to add dependencies between these resources to ensure they are created in the correct order,
guaranteeing proper permission delegation.
The following image describes the resources and dependencies,
![WhatsApp Image 2024-07-18 at 12 10 59](https://github.com/user-attachments/assets/60fe93a1-2e06-4975-86b1-bfa579129309)
