## **Common/important questions**

- ### **AWS Trusted Advisor** =
	- ### Real-time recommendations for provisioning resources following best practices to optimize...**Cost**, **Security**, **Fault tolerance**, **Performance**.
	- ### Identify underutilized EC2 instances

<br>

- ### **Sole responsibility of AWS**
	- ### Availability Zone Management

<br>

- ### Customers in AWS are responsible for **Encrypting data at rest** and **in transit**.

<br>

- ### **AWS Acceptable Use Policy**
	- Customers can perform **Penetration testing** for selected aws services without needing approval from AWS

<br>

- ### **AWS to offer lower pay-as-you-go pricing for thousands of customers**
	- Massive economies of scale

<br>

- ### **Cloud advantages**
	- Increase speed and agility
	- No cost for data center maintenance
	- Stop guessing capacity
	- Trade capital/fixed expenses for variable expenses

<br>

- ### **Free services**
	- IAM
	- Auto scaling
	- Billing Dashboard

<br>

- ### **Global services**
	- IAM
	- S3
	- CloudFront

<br>

- ### **Managed services**
	- DynamoDB
	- EMR

<br>

- ### **Reservable services**
	- DynamoDB
	- RDS
	- EC2
	- RedShift
	- ElastiCache

<br>

- ### **Automatically scale**
	- DynamoDB
	- Aurora
	- S3
	- Lambda

<br>

- ### **Automatic Data Encryption**
	- AWS Storage Gateway
	- S3 Glacier

<br>

- ### **Central user portal to log into third-party business applications**
	- AWS Single Sign-On (SSO) / AWS IAM Identity Center

<br>

- ### **Asynchronous integration**
	- **Loose coupling between services** (SQS, Step Functions...)

<br>

- ### **AWS Shared responsibility model is part of which pillar of the AWS Well-Architected Framework?**
	- Security

<br>

- ### **Shared Responsibility Model**
![](sharedResponsibilityModel.jpg)

<br>

- ### **Shared Controls**
	- ### Apply to both the infrastructure layer and customer layers
		- ### **Patch Management** = AWS responsible for patching the firmware hosts; customers responsible for patching guest OS and applications.

		- ### **Configuration Management** = AWS maintains the configuration of its infrastructure hardware; customer responsible for configuring their own guest OS and applications.

		- ### **Awareness & Training** = AWS trains AWS employees; customer trains their employees.

<br>

- ### **AWS Support Plans (ALL HAVE ACCESS TO CUSTOMER SUPPORT)**
	### **Basic**
		– Forums support.
	### **Developer**
		– Business hours email support
		- 1 person can open unlimited cases
	### **Business**
		– 24/7 email, chat, and phone support
		- AWS Health API access
		- Unlimited people can open unlimited cases
		- x < 1 hour response time for production system down
	### **Enterprise**
		(Same as Business, in addition...)
		- Includes Technical Account Manager (MONITORING) and Concierge (ACCOUNT & BILLING)
		- x < 15 minutes response time for business-critical system failure
	### **Enterprise on Ramp**
		(Same as Enterprise except...)
		- x < 30 minutes response time for business-critical system failure

<br>

- ### **SaaS** = Whole stack is managed for you. Focus on how you will use the software.

<br>

- ### **Paas** = Don’t need to manage the infrastructure level yourself, (hardware and OS). Focus on the deployment and management of applications.

<br>

- ### **IaaS** = Basic building blocks for Cloud; Hardware and hypervisor are managed for you. Highest level of flexibility and control.

<br>

- ### **AWS Cost Management tools**
	- ### Create budgets and receive alerts
	- ### Automatically terminate AWS resources if budget exceeded

<br>

- ### **Active-Active** = Workload deployed to multiple regions; fault tolerance for natural disasters

<br>

- ### **Service limits**
	- ### Contact AWS support to increase service limits
	- ### AWS Trusted Advisor monitor service limits

<br>

- ### **Per/Second billing is only for instances with Linux, Windows or Ubuntu**