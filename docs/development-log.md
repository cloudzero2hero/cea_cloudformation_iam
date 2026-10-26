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

## Stage 2 - IAM Group and User addition

### Implemented
- Create the DeveloperGroup IAM group.
- Add the user to the group.

### Outstanding
- Define the EC2 role and trust relationship.
- Add a scoped S3 object-read policy.

### Validation
- Pending CloudFormation template validation.
- Deployment not yet performed.

## Stage 3 - Define EC2 role

### Implemented
- Define the EC2 role and trust relationship.

### Outstanding
- Add a scoped S3 object-read policy.

### Validation
- Pending CloudFormation template validation.
- Deployment not yet performed.

## Stage 4 - Add custom S3 policy for EC2 role

### Implemented
- Add a scoped S3 object-read policy.

### Outstanding
- Deploy and validation within AWS console.

### Validation
- Pending CloudFormation template validation.
- Deployment not yet performed.

## Stage 5 - Deploy template and validate on AWS
### Implemented
- Deploy and validation within AWS console.
- Successfully deployed and validates within the AWS console.

### Outstanding
- None

### Validation
- Pending CloudFormation template validation.
- Deployment not yet performed.