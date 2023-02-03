# aws_iam_interview_preparation
Another entry in the interview preparation saga

## Theorical Questions Section

### Theorical Question 1

How would you give permissions to a user ?

<details><summary><b>Answer</b></summary>

1. Add user to group – Make the user a member of a group. The policies from the group are attached to the user.

2. Copy permissions from existing user – Copy all group memberships, attached managed policies, inline policies, and any existing permissions boundaries from the source user.

3. Attach policies directly to user – Attach a managed policy directly to the user. For easier permissions management, attach your policies to a group and then make users members of the appropriate groups. 

</details>

<details><summary><b>Source</b></summary>

- https://docs.aws.amazon.com/IAM/latest/UserGuide/id_users_change-permissions.html

</details>

### Theorical Question 2

Do you know what the root user is ?

<details><summary><b>Answer</b></summary>

When you create an AWS account, you begin with one sign-in identity that has complete access to all AWS services and resources in the account. This identity is called the AWS account root user and is accessed by signing in with the email address and password that you used to create the account. We strongly recommend that you don't use the root user for your everyday tasks.  

</details>

<details><summary><b>Source</b></summary>

- https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html

</details>

### Theorical Question 3

Do you know what the MFA (Multi Factor Authentication) is ?

<details><summary><b>Answer</b></summary>

You can add two-factor authentication to your account and to individual users for extra security. With MFA you or your users must provide not only a password or access key to work with your account, but also a code from a specially configured device. 

</details>

<details><summary><b>Source</b></summary>

- https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html

</details>

### Theorical Question 4

Do you know what the Identity federation is ?

<details><summary><b>Answer</b></summary>

You can allow users who already have passwords elsewhere—for example, in your corporate network or with an internet identity provider—to get temporary access to your AWS account.

</details>

<details><summary><b>Source</b></summary>

- https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html

</details>

### Theorical Question 5

Do you know what eventual consistency mean for IAM ?

<details><summary><b>Answer</b></summary>

If a request to change some data is successful, the change is committed and safely stored. However, the change must be replicated across IAM, which can take some time. Such changes include creating or updating users, groups, roles, or policies.  Also, be sure to verify that the changes have been propagated before production workflows depend on them.

</details>

<details><summary><b>Source</b></summary>

- https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html

</details>

### Theorical Question 6

Do you understand what least-privilege permissions means ?

<details><summary><b>Answer</b></summary>

When you set permissions with IAM policies, grant only the permissions required to perform a task. You do this by defining the actions that can be taken on specific resources under specific conditions, also known as least-privilege permissions. You might start with broad permissions while you explore the permissions that are required for your workload or use case. 

</details>

<details><summary><b>Source</b></summary>

- https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#bp-users-federation-idp

</details>

### Theorical Question 7

What security best practice do you know ?

<details><summary><b>Answer</b></summary>

read the link in the source

</details>

<details><summary><b>Source</b></summary>

- https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#bp-users-federation-idp

</details>