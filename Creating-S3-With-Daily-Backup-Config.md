# ✅ Step 4: Create an S3 Bucket (Free Tier Eligible)

Amazon S3 provides **5 GB of standard storage for free** each month under the AWS Free Tier.

### 🛠️ To create your S3 bucket:

```bash
aws s3 mb s3://your-unique-bucket-name
```

---

> 🔸 Important
- Replace `your-unique-bucket-name` with a globally unique, all lowercase name.
- Example: `james-daily-backup-2025`

### ✅ S3 Bucket Naming Rules:
- Must be all lowercase
- No spaces
- Must be globally unique across all AWS accounts
- Avoid special characters (only . and - are allowed)

---

### Verify the Created Bucket

You can verify the bucket was created by listing all buckets:
```bash
aws s3 ls
```
