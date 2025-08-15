# AWS Security Foundations - Week 2

This week focuses on strengthening IAM security by creating and attaching custom policies.  
We implemented two key policies:  

## 🔑 MFA Policy
- Requires users to have MFA enabled before performing sensitive operations.  
- JSON file: [MFApolicy.json](policies/MFApolicy.json)  
- Proof: ![MFA Policy Screenshot](screenshots/MFAPolicy.png)  

## 🗂️ S3 ReadOnly Policy
- Grants **read-only** permissions on all S3 buckets.  
- Allows `s3:Get*` and `s3:List*` actions.  
- JSON file: [S3ReadOnlyPolicy.json](policies/S3ReadOnlyPolicy.json)  
- Proof: ![S3 Policy Screenshot](screenshots/jsonpolicy.png)  

## 📸 Additional Proof
- IAM policies attached successfully: ![Attached Policies](screenshots/attachedpolicies.png)  
- S3 bucket list access test: ![Bucket List](screenshots/bucketlist.png)  

---

✅ **Outcome**: Successfully created and tested custom IAM policies that enforce security best practices.  
Next step → Week 3.

