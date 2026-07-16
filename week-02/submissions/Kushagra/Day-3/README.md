# Week 2 - Day 3: IAM Roles and STS

## Name
Kushagra

## Topics Practiced
- Trust policy vs permission policy
- STS AssumeRole
- EC2 role and instance profile
- Cross-service role assumption
- Temporary credentials
- Least-privilege S3 access
- AwS Cli Commands

## What I Built
I attached an IAM role to EC2 and allowed it to read from one S3 bucket without
storing permanent access keys.

## Allowed Test
listing and reading a S3 bucket from an EC2 instance.

## Denied Test
uploading files from Ec2 instace to s3 bucket

## What I Learned

### Write the difference between a trust policy and permission policy in your own words.

- Permission policy decides what actions can user or service perform
- Trust policy decides who can assume role (for e.g, services,user,federated user)

## LinkedIn Post
[LinkedIn Link](https://www.linkedin.com/posts/kushagra-ghadi_10weeksofaws-10weeksofaws-cloudadhar-ugcPost-7483580646997614592-ZaQ7/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEdd1JEBGLKm2xnLGzZYAectlvG9YGy5c3A)

## Minimum Accepted Submission

- Role Attached to ec2
    ![image](./screenshots/role-attached-to-ec2.png)

- S3 Read Allowed and Write denied
    ![image](./screenshots/s3-read-allowed_s3-write-denied.png)
