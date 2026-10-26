# Development Log

## Stage 1 - IAM User Foundation

### Implemented
- Created the initial CloudFormation template.
- Defined the `MyIAMUser` resource.
- Set the IAM user name to `Rob_Developer`.
- Added 'AdministratorAccess' managed policy.

### Outstanding
- Create the DeveloperGroup IAM group.
- Add the user to the group.
- Define the EC2 role and trust relationship.
- Add a scoped S3 object-read policy.

### Validation
- Pending CloudFormation template validation.
- Deployment not yet performed.