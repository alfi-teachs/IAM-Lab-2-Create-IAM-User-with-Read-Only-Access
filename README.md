# IAM-Lab-2-Create-IAM-User-with-Read-Only-Access

https://www.youtube.com/watch?v=xGzwaOrz5RU&t=132s

creating user and attaching permission for IAM read acess

Objective

Create an IAM user
Attach Read-Only policy
Verify access

Step 1: Go to IAM

Console → Services → IAM → Users → Create user

Step 2: Configure User
User name: read-user1

Select:
✔️ Console access (if needed)

Click Next.

Step 3: Attach Policy

Choose:   Attach policies directly

Search and select:
✔️ ReadOnlyAccess

This is an AWS managed policy that allows viewing resources but not modifying or deleting them.

Click Next → Create user

Step 4: Verify Permissions
Login as the new user.
Try:

View EC2 instances ✔️
View S3 buckets ✔️

Try deleting a bucket ❌ (Access Denied)
Try launching EC2 ❌ (Access Denied)
