# Week 0 — Billing and Architecture

# Checklist 1. Recreate Conceptual Diagram in Lucid Charts

To start with, I need to create a conceptual diagram which is going to give synthesised knowlege of what I'm going to design. Below is my homework screen short

![01-Cruddur Conceptual Diagram](https://user-images.githubusercontent.com/125898525/222930940-8435750c-4892-40ca-b502-c4475b2ca7b8.jpg)

- LUCID CHART LINK: https://lucid.app/lucidchart/d4d163c3-a42a-4658-a6e5-78f4f399b411/edit?viewport_loc=-1611%2C1634%2C2663%2C1142%2C0_0&invitationId=inv_f4e2ea42-52f5-4579-8d1f-6477b0b488ba

# Checklist 2. Recreate Logical Architectual Diagram

Below is the screenshot and link for Architectual diagram of cruddur application that I recreate to complete my homework.

![02-Architectual Diagram](https://user-images.githubusercontent.com/125898525/222930966-3a341862-1915-47bc-8650-51422967be06.jpg)

- LUCIDCHART LINK: https://lucid.app/lucidchart/b54ce76e-ea70-489c-bc92-823c8879f844/edit?viewport_loc=-997%2C264%2C3451%2C1480%2C0_0&invitationId=inv_bf6c3d24-88e7-41aa-9dd0-b29e7114f095

# Checklist 3. Create Admin User

![Admin User](https://user-images.githubusercontent.com/125898525/222930987-714b890c-bacd-4c0e-8830-8f10876dc9d3.JPG)

# Checklist 4. Installed AWS CLI

![Installed AWS CLI](https://user-images.githubusercontent.com/125898525/222931004-fdd2d557-d724-4a5d-86e9-c107911ff2ba.JPG)

# Checklist 5. Create a Budget

![Budget](https://user-images.githubusercontent.com/125898525/222931017-d701e998-012a-4c09-87c1-562d38a9b375.JPG)

# Checklist 6. Created Billing Alarm and Generate AWS User credentials

I have created a billing alarm of $10 for the project bootcamp. I also generated a AWS User credentials for my IAM account to use.

# Checklist 7. AWS Organizations & AWS IAM (by Ashish Rajan)

# 1. MFA 

Mutifactor Authentication means the provision of two or more verification factor by the user to gain access in the AWS account.

![MFA](https://blog.miniorange.com/wp-content/uploads/sites/19/2021/02/multi-factor-authentication-mfa.webp)

# 2. AWS Organization 

This is a service in the AWS cloud platform that allows you to create another account within an organization.

![AWS Organization](https://docs.aws.amazon.com/images/organizations/latest/userguide/images/AccountOuDiagram.png)

# 3. CloudTrail

CloudTrail records all users activity and API usage in AWS services.

![CloudTrail](https://d1.awsstatic.com/product-marketing/CloudTrail/product-page-diagram_AWS-CloudTrail_HIW%402x.d314033178a16dbbd99111038789685e42f23278.png)

# 4. IAM User

There are basically 3 kinds of users in AWS:
1. IAM User: Those that use password and email to open a AWS account
2. The System Users: These are users that perform on behalf of the authorized individuals.
3. Federated Users: Those that are federated from your own on-premise environment without a username or any form of verification
The best practice for assigning a role to any user is by following the principle of least previlege (assign Only the required permission to perfom a task)

![IAM User](https://d1.awsstatic.com/product-marketing/IAM/iam-how-it-works-diagram.04a2c4e4a1e8848155840676fa97ff2146d19012.png)

# 5. Top 5 Security Best Practices

1. Data protection and residency in accordance to security policy.
2. Identity and Access management with the least privilege policy.
3. Governance & compliance of AWS services being used(Global vs Regional services)
4. Shared responsibity of Threat Detection
5. Incident Response plans to include cloud.






