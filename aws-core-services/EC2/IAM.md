# Identity Access and Management
`IAM` is a global service.

# IAM Users and Groups.
When a user creates an account on the AWS console, A root account is created by default. This account should not be shared or used for day-to-day activities.
Best practice: Create Users within your organization and group them. Groups contain only users and not other groups.
Users don't have to belong to a group, but a user can belong to multiple groups.
Users and groups are created to give them permissions.

# IAM Permissions
Users or groups can be assigned JSON documents called policies. These policies define permissions for the users.

BEST PRACTICE: Apply the Principle of least privilege, where a user is not given more permissions than needed.

# IAM Roles
`IAM Roles` are a secure way to grant permissions to entities you trust. Examples of entities include the following:
1. `IAM` user in another account.
2. Application code running on an `EC2 Instance` that needs to perform actions on AWS resources.
3. An AWS service that needs to act on resources in your account to provide its features.
4. Users from a corporate directory who use identity federation with SAML.

IAM roles issue keys that are valid for short durations, making them a more secure way to grant access.

Some AWS services will need to perform actions on your behalf. To do so, we will assign permissions to AWS services with `IAM roles.`

Common roles:
1. EC2 Instance roles
2. Lambda Function roles
3. Roles for CloudFormation
