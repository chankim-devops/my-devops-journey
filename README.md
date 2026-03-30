# My DevOps Journey 🚀

I'm a non-CS major beginner on a mission to become a **Cloud / DevOps Engineer** starting from zero.

## What I've Learned Today (March 27, 2026)
- Created my AWS account and set up AWS CLI
- Successfully used `aws s3 cp` to upload and download files to/from an S3 bucket
- Created this GitHub repository to document my entire learning journey

## Next Goals
- **Phase 0**: Master Linux command line + Git & GitHub
- Build consistent daily learning habits

I will update this README every day with what I learn.  
Feel free to follow along!

---

**Current Status**: Beginner (Day 4)  
**Goal**: Junior Cloud/DevOps Engineer within a year


---


## Day 7 - March 30, 2026

### Concepts Learned
- **IAM (Identity and Access Management)** - AWS permission management system
- **IAM User** - Individual account (1 person = 1 account principle)
- **IAM Group** - Collection of users with same permissions
- **IAM Policy** - Document that defines what actions are allowed or denied
- **IAM Role** - Permissions given to AWS services (EC2, Lambda etc.), not people
- **Least Privilege Principle** - Only give the exact permissions needed, nothing more
- **Root Account** - Should avoid using for daily tasks, use IAM User instead
- **JSON** - A text format for storing data (not a program)
- **Region** - Geographic area containing multiple Availability Zones
- **Availability Zone (AZ)** - Individual data center within a Region (usually 3+ per Region)

### Hands-on Practice
- Created a custom IAM Policy (MyS3ReadOnly) - S3 read-only access
- Attached the Policy to an IAM User via AWS Console
- Observed AWS security warning when using wildcard (*) for Resource

### Key Takeaway
> IAM User/Group/Role are all the same level - the difference is just WHO you give the Policy to.
> User = person, Group = group of people, Role = AWS services like EC2
