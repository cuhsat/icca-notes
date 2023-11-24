# Provision Virtual Machine (1)
- Compute engine
- VM instances
- CREATE INSTANCE
	- Name `my-first-gcp-vm`
	- Any region
	- Series E2
	- e2-micro
	- Create
# Provision Virtual Machine (2)
- Compute Engine
- Vm instances
- CREATE INSTANCE
	- Name `lab-vm`
	- Region us-east1
	- Type e2-micro
	- Boot disk > Change
		- OS: Ubuntu
		- Version: Ubuntu 20.04 LTS
		- SELECT
	- FireWall
		- Allow HTTP Traffic
	- CREATE
- Refresh to update Status
- Click on VM to open
- Open in browser window
```
sudo apt update
sudo apt install -y nginx
curl localhost
exit
```
Copy External IP address
Open new tab and run it