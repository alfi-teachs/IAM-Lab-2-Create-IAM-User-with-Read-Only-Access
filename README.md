# IAM-Lab-3-Create-IAM-User-with-Read-Only-acess 

# AWS IAM: Adding Permissions (IAM read acess ) to Existing Users

https://www.youtube.com/watch?v=xGzwaOrz5RU&t=7s

creating user and attaching permission for IAM read acess

Objective

Create an IAM user
Attach Read-Only policy
Verify access

# Part 1: Login as IAM User (Before Permission)

Open Incognito / Private window

Paste your IAM user login URL

Enter:

Username

Password

👉 Login

What you’ll notice:

Limited access

Many services (like IAM) may show Access Denied

Keep this window open (you’ll come back to it)

# Part 2: Login as Root User

Now open a normal browser window (not incognito)

Go to AWS Console

Login using Root user email + password

# Part 3: Add Permission to Existing User

Go to IAM (Identity and Access Management)

Click Users

Select your IAM user

Add Permissions

Go to Permissions tab

Click Add permissions

Choose:
✅ Attach policies directly

Search for:
IAMReadOnlyAccess

Select:
✅ IAMReadOnlyAccess

👉 Click Next
👉 Click Add permissions

# Part 4: Verify in Incognito Window

Go back to your Incognito IAM user session

# Important:

Either refresh the page

Or log out and log in again

What You’ll See Now

IAM service is now accessible

User can view IAM details

But cannot:

Create users

Delete users

Modify policies

# What This Lab Shows (Core Concept)

Before → User had no permission

After → User has read-only access to IAM

So:
👉 Permissions define what a user can do
👉 Policies are how AWS gives those permissions
