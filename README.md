📌 Project Overview:-

This project demonstrates how to launch a Windows Server EC2 instance on AWS and securely connect to it using Remote Desktop Protocol (RDP).
It covers EC2 creation, security configuration, key pair usage, and RDP connectivity.

This project is suitable for AWS beginners / fresher cloud engineers and aligns with AWS Solutions Associate.

🛠️ Services & Tools Used :-

Amazon EC2

AWS Management Console

Key Pair (.pem)

Remote Desktop Connection (RDP)

EC2 Key Decryption Tool

📋 Prerequisites:-

AWS Account (Free Tier)

Basic knowledge of AWS EC2

Laptop/Desktop (Windows OS)

Internet connection

⚙️ Step-by-Step Implementation:-

1️⃣ Launch Windows EC2 Instance

Login to AWS Console

Navigate to EC2 → Launch Instance

Select instance type: t2.micro (Free Tier)

Create or select a Key Pair

Make sure RDP traffic is allowed

Allow RDP (Port 3389) from your IP

2️⃣ Obtain Windows Administrator Password

Go to EC2 → Instances

Select your Windows instance

Click Get Password

Upload your .pem key file

Launch instance

Decrypt and copy the Administrator password

3️⃣ Connect to Windows EC2 Using RDP

Open Remote Desktop Connection

Username: Administrator

Paste the decrypted password

Click Connect

✅ Successfully connected to Windows Server EC2 instance.

🔐 Security Best Practices:-

Restrict RDP access to your IP only

Stop or terminate EC2 instance when not in use

Do not expose .pem files publicly

📚 Learning Outcomes:-

Hands-on experience with Windows EC2

Understanding RDP connectivity

Security group configuration

Key pair and password decryption

Real-world cloud deployment workflow

📎 Project Use Case:-

Practice project for AWS beginners

Resume & GitHub portfolio project

Foundation for Windows-based workloads on AWS

🧑‍💻 Author:-

Tooba Rizvi,

Aspiring Cloud Engineer,

GitHub: https://github.com/rizvitooba28-eng.
