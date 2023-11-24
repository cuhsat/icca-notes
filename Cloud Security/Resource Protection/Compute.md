Infrastructure Compute Protection:
- Patch management
- Attack surface minimisation
- OS hardening
- Resource protection
- Multiple instance (scale out)

Platform Compute Protection

> The cloud provider is responsible for patching compute resources

Patching:
- Infrastructure as a Service
	- OS - automated option in AWS and Azure
	- Service (such as web server or database server)
- Platform as a Service
		- Always patched by the provider

Confidential Compute:
- Encrypt in Transit (User)
- Trusted Execution Environment (Enclave)
- Encryption at Rest (Data)

> An enclave or trusted execution environment that provides an isolated execution environment

Protects against:
- Unauthorised data access
- Code corruption

> Available on specific compute instance sizes

Compute monitoring:
- Agent
	- Platform Monitor (aggregate)
	- 3rd Party Monitor (aggregate)