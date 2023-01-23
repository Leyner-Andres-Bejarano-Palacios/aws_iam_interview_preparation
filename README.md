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
