# Energy-vault-Security-Project

                                         ENERGRGY VAULT SECURITY FRAMEWORK

           THE SHARED SECURITY RESPONSIBILITY MODEL
This is a security and compliance framework that outlines the responsibilities of cloud service providers (CSPs) and customers for securing every aspect of the cloud environment, including hardware, infrastructure, endpoints, data, configurations, settings, operating system (OS), network. AWS is responsible for patching and fixing flaws within the infrastructure, but customers are responsible for patching their guest OS and applications, etc.

SECURITY FRAMEWORK GOALS IN ENERGY VAULT
A.	OBJECTIVES OF THREE TIER APPLICATION SECURITY   IN ENERGY VAULT
To provides Security Framework guidance for implementing a secure operational posture for a three-tier Web architecture deployed to the Energy Vault environment.
	Implementing Zero Trust strategic approach to secure Energy Vault environment by eliminating implicit trust and continuously validating every stage of a digital interaction.
	Identity and Access Management (IAM)
•	Ensuring IAM policies exist for the EC2 IAM roles
•	Autoscaling Group Launch-Configurations are configured appropriately
•	SNS Topics do not allow the “Everyone” group to publish and subscribe
	Data protection
•	Ensuring databases running on RDS and all EBS volumes are encrypted
•	Elastic Load Balancing (ELB) have the appropriate SSL Certificate and are using HTTPS listener
•	All S3 buckets have secure policies enabled that require encryption for objects stored in buckets
	Business continuity
•	Auto-Scaling Groups are associated with an ELB and are configured for multiple Availability Zones (AZs)
•	Amazon Machine Images (AMIs) are configured for the Auto-Scaling Launch Configuration
•	RDS backup retention policies are set in place
	Event monitoring and response
•	SNS topics include appropriate notification for CloudWatch alarms
•	RDS event subscriptions are enabled
•	CloudWatch alarms are created for logs
	Audit and logging
•	Logging for ELB and CloudFront is enabled
•	CloudWatch log groups are created
•	Config rules for encrypted volumes are applied
•	Config rules for EIPs are attached to EC2 instances
	Networking
•	Enable CloudFront content distribution network
•	Ensure subnets are configured for each tier
•	Routing tables have the default route defined to allow connection to the VPC gateway
•	ELB Security Group is configured to accept HTTPS only


B.	OBJECTIVES of implementing accounts Security in Energy Vault
To Centrally secure and audit the enterprise accounts. Simplify user-based permission management, enhance governance and compliance, Manage and optimize costs across the company’s accounts and resources:
	Security, Identity, and Compliance on AWS and the company
	Using the Security Operations Center (NOC) to ensuring that corporate infrastructure is capable of sustaining business operations.
	Aligning Best Practices for a Successful Security Operations Center: designing security Strategy with Business Goals, Enabling End-to-End Visibility, Continuously Monitor the Network, Secure and Patch Vulnerabilities, Proactively Mitigate and Address Threats
	using the Network Operations Center Best Practices (NOC) to protect Energy vault against cyber threats that could disrupt business operations.
	Implementing Network Operations Center Best Practices for a Successful Security Operations Center: Implement a Tiered Organization/Workflow, Tracking Meaningful Operational Metrics, implement a Standardized Framework for Process Management, Develop and Maintain a Business Continuity Plan
	Automate AWS account creation and management, and provision resources with AWS CloudFormation Stack sets. Maintain a secure environment with policies and management of AWS security services

WHY ENERGY VAULT
Since Energy Vault® LDES solutions are based on proprietary gravity energy technology and ideally deployed for use cases requiring 4 or more hours of storage capacity. The Energy Vault® EVx™ platform utilizes a mechanical process of lifting and lowering composite blocks to store and dispatch electrical energy, it is recommendable that security framework and best practices should be implemented with the enterprise accounts, infrastructure, Pipeline, and other platform that the company is hosting its resources and even other third-party tools as per requirements:
	Implement security Framework and tools that are but not limited to the following:
AWS Identity and Access Management, Amazon Guard Duty for intelligent threat detection on unauthorized deployments that indicate a possible account compromise, Amazon Macie. AWS Config, AWS CloudTrail, Security Hub for security findings, priority security issues and consolidated security status across Energy Vault AWS account, Trusted Advisor that will scan your infrastructure and compare it to AWS best practices and provides recommendation for  Cost optimization, fault tolerance, security, service limit and performance, Amazon Inspector,  to scans the company’s work workloads for software vulnerabilities and unintended network exposure., AWS Shield to manage DDoS  for detection and automatic inline mitigations that minimize application downtime and latency, AWS Web Application Firewall (WAF) that will  help protect Energy Vault web applications from common web exploits that could affect application availability, compromise security, or consume excessive resources, CloudTrail to
logs all API activity in the company’s account including the creation/modification/deletion of EC2 resources
	Automate AWS account creation
Create AWS accounts and add them to user-defined groups for instant security policy application, touchless infrastructure deployments, and auditing.
	Enable proactive protection with a dedicated security group
Create a security group and provide users with read-only access to your resources to actively monitor, identify, and mitigate security concerns.
	Ensure user access to designated resources
Enable single sign-on access and apply service control policies to allow only user actions that meet your security and compliance requirements.
	Pipeline Security- As per requirements, the company can implement some security framework around it CICD SDLC using SonarQube, OWASP, DAST, SAST, Backup, IAM, automating and constant testing, plugin, branching strategy.
	Share common resources across accounts
More easily share central resources, software applications, directories, and services within your organization. Implement defense in-depth, penetration testing and zero trust network: user/application authentication, device authentication, and trust.
                 Taking into consideration all these security  technologies, Energy Vault Company will securely use excess energy to compress and store air, then release it to turn generator turbines., powering green growth through electrification; build a more self-sufficient, decarbonized, and affordable energy system, bring to life a market for long duration  energy storage technologies, and the regulatory framework, storing excess energy as heat in concrete-like “thermal batteries” for use in industrial processes, building green hydrogen and battery storage system for wind farm ,add green hydrogen solutions,  expands green hydrogen and starts building gravity storage system. Therefore, it is of utmost importance to implement security framework in Energy Vault Company and Harness the Potential of Long -Duration Energy Storage enhance vulnerability management, monitoring, compliance and other Security Framework around Energy Storage Deployment, Innovation, Investment and Policy.





<img width="598" alt="image" src="https://user-images.githubusercontent.com/85325135/206883182-79995767-0ce9-447c-8999-7a6360f31ad0.png">

<img width="520" alt="image" src="https://user-images.githubusercontent.com/85325135/206884331-e1880c37-d067-44cc-a704-d76987f22107.png">
