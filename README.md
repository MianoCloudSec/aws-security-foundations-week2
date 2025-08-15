# AWS Security Foundations – Week 2  

This week we focused on strengthening **IAM security** and **S3 bucket access control** by creating and attaching custom policies.  

---

## 🔑 MFA Policy  

- Requires users to have MFA enabled before performing sensitive operations.  
- **JSON file:** [MFApolicy.json](policies/MFApolicy.json)  
- **Proof:** ![MFA Policy Screenshot](screenshots/MFAPolicy.png)  

---

## 📂 S3 ReadOnly Policy  

- Grants **read-only** permissions on all S3 buckets.  
- Allows `s3:Get*` and `s3:List*` actions.  
- **JSON file:** [S3ReadOnlyPolicy.json](policies/S3ReadOnlyPolicy.json)  
- **Proof:** ![S3 Policy Screenshot](screenshots/S3ReadOnlyPolicy.png)  

---

## 📸 Additional Proof  

- IAM policies attached successfully: ![Attached Policies](screenshots/attachedpolicies.png)  
- Verified bucket list access: ![Bucket List](screenshots/bucketlist.png)  

---

## ✅ Summary  

By implementing these custom IAM policies, we improved AWS account security with:  
- Mandatory MFA for sensitive actions.  
- Least-privilege, read-only S3 access.  

This lays the foundation for secure cloud operations.  
