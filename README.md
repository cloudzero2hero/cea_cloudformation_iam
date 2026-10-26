# CEA CloudFormation IAM

## Project Overview

This project builds AWS Identity and Access Management (IAM) resources using AWS CloudFormation and YAML.
The infrastructure is developed incrementally, with each stage documented and committed to GitHub.


This project goes through the process of creating a new IAM user, adding them to a group, applying IAM role for EC2 and a Custom policy for S3 using AWS CloudFormation and YAML.

The objective is to show the above process clearly, documenting each development and maintaining a clear Git history.

## Technologies

Amazon IAM

AWS CloudFormation

YAML

Git and GitHub

Windows PowerShell

## Development Roadmap

Stage 1: Create the IAM user.

Stage 2: Create an IAM group and add the user.

Stage 3: Create an EC2 IAM role and trust policy.

Stage 4: Create a custom S3 object-read policy.

Stage 5: Validate the template and document security considerations.

## Repository Structure

templates/iam.yaml - CloudFormation iam template.
docs/development-log.md - Developments and implementation notes.

## Status

In development. Resources are introduced and documented with each development stage.

## Security Considerations

IAM permissions should follow the principle of least privilege. Broad managed policies such as AdministratorAccess and PowerUserAccess should not be attached to production identities without a justified requirement.

The project is for demonstration purposes only. Review all IAM permissions before deployment.
