# Provision Virtual Machine (1)
- Create a resource
- Ubuntu Server
- Create
	- Name `myFirstAzureVM`
	- See all sizes
	- Size: B2s
	- Review + create
	- *Validation passes*
	- Create
- Download private key pair and create resource
# Provision Virtual Machine (2)
- Create a resource
- Ubuntu Server
- Create
	- Name `lab-vm`
	- Security type: Standard
	- Size: Standard_D2s_v3
	- Authentication type: Password
		- Username: `student`
	- Inbound ports: HTTPS, SSH
- Next: Disks
- Standard SSD (locally-redundant-storage)
- Review + create
- *Validation passes*
- Create
- Go to resource
- Copy Public IP address
- Cloud Shell
- Bash
- Show advanced settings
	- Cloud shell region: East US
	- Storage account Create new: lab-cloudshell
	- File share Create new: lab-cloudshell
	- Create storage
- Create
```
ssh student@<ip>
sudo apt update
sudo apt install -y nginx
curl localhost
```
- Open browser on IP to verify
# Provision Storage Account
- Create a resource
- Storage account
- Create
	- Create
# Provision Storage Container
- Storage accounts
- Select previous created storage account
- Containers
	- + Container
		- `public`
		- Blob
		- Create