# S3-Daily-Backup-Demo

# ✅ Step 1: Prepare Your Environment (Using Free Tier)

## 1. Launch a Free Tier-Eligible EC2 Instance

To stay within the AWS Free Tier, follow these steps:

### 🔹 Sign in to the AWS Console

Go to: [https://console.aws.amazon.com/ec2](https://console.aws.amazon.com/ec2)

### 🔹 Launch a New Instance

Click **“Launch Instance”**, then configure the following:

---

### ✅ Basic Settings

- **Name**: `awscli-lab-instance` (or any name you prefer)

### ✅ Amazon Machine Image (AMI)

- Select **Amazon Linux 2023 AMI** (Free Tier eligible)

### ✅ Instance Type

- Choose **t2.micro** or **t3.micro** — both are Free Tier eligible

### ✅ Key Pair (Login)

- **Option 1**: Proceed without a key pair (if using EC2 Instance Connect)
- **Option 2**: Select/Create a key pair (if using SSH)

### ✅ Network Settings

- Allow **SSH (port 22)** access **from your IP only** for better security

### ✅ Storage (Volume)

- Keep default: **8 GB General Purpose SSD (gp2)**  
- ⚠️ *Do not increase the volume to stay within Free Tier limits*

---

### 🚀 Final Step

Click **“Launch Instance”** to start your EC2 setup.

### 

---

## 📸 Output Screenshot

### ✅ Successfully Launched EC2 Instance

Below is a screenshot of the EC2 instance after successful launch:

![EC2 Instance Screenshot](images/ec2-instance-success.png)

*This confirms that the EC2 instance named `awscli-lab-instance` was successfully created using the Amazon Linux 2023 AMI and is running under Free Tier settings (t2.micro or t3.micro). The status checks show "2/2 checks passed," indicating the instance is healthy and ready to use.*

---

