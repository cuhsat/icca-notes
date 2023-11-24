# Provision EC2 Instance (1)
- Services
- EC2
- Launch instance
- Amazon Linux AMI
- t2.micro
- Key pair
- Create new key pair
- name `demo`
- Create key pair
- *Check network settings*
- *Check storage settings*
- Name and tags
- Name `myFirstEC2`
- *Look at summary on the right side*
- Launch instance 
# Provision EC2 Instance (2)
- Search EC2 in search box
- Select EC2
- Instances
- Launch instances
- Name `lab-vm`
- Application and OS Images
	- Amazon Linux
	- t2.micro
	- Create new key pair
	- `lab-vm-key-pair`
	- RSA
	- .pem
- Network settings
	- Edit
	- Security Group
	- Add security group rule
	- Type: HTTP
	- Source Type: Anywhere
- Launch instance
- View all instances
- *Check instance State status*
- Refresh
- Click on instance ID
- Connect
- EC2 Instance Connect
- Connect
```
sudo amazon-linux-extras install nginx1
[y]
sudo systemctl start nginx
curl localhost
exit
```
- Summary page
- Copy External Public IPv4 address
- Open browser on IP address to verify
# Provision S3 Bucket
- Services
- S3
- Create bucket
- Unique name and region of choice
- *Check all advanced settings for the bucket*
- Create bucket