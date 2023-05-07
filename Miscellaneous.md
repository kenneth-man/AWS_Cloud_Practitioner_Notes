## **Common/important questions**

- ### Customers in AWS are responsible for **Encrypting data at rest** and **in transit**

<details>
  	<summary>
		<strong>
			<font size=5>
				Free (6)
			</font>
		</strong>
	</summary>
	<font size=4>
		IAM, Auto Scaling, Billing Dashboard, Bulletins, Security Blog, Whitepapers
	</font>
</details>

<details>
  	<summary>
		<strong>
			<font size=5>
				Global (3)
			</font>
		</strong>
	</summary>
	<font size=4>
		IAM, S3, CloudFront
	</font>
</details>

<details>
  	<summary>
		<strong>
			<font size=5>
				Managed (2)
			</font>
		</strong>
	</summary>
	<font size=4>
		DynamoDB, EMR
	</font>
</details>

<details>
  	<summary>
		<strong>
			<font size=5>
				Reservable (5)
			</font>
		</strong>
	</summary>
	<font size=4>
		DynamoDB, RDS, EC2, Redshift, ElastiCache
	</font>
</details>

<details>
  	<summary>
		<strong>
			<font size=5>
				Automated Scaling (4)
			</font>
		</strong>
	</summary>
	<font size=4>
		DynamoDB, Aurora, S3, Lambda
	</font>
</details>

<details>
  	<summary>
		<strong>
			<font size=5>
				Automated Data Encryption (2)
			</font>
		</strong>
	</summary>
	<font size=4>
		Storage Gateway, S3 Glacier
	</font>
</details>

<details>
  	<summary>
		<strong>
			<font size=5>
				Asynchronous integration
			</font>
		</strong>
	</summary>
	<font size=4>
		Loose coupling between services (SQS, Step Functions...)
	</font>
</details>

<details>
  	<summary>
		<strong>
			<font size=5>
				Shared Controls
			</font>
		</strong>
	</summary>
	<font size=4>
		Apply to both infrastructure and customer layer
	</font>
</details>

<details>
  	<summary>
		<strong>
			<font size=5>
				Inherited Controls
			</font>
		</strong>
	</summary>
	<font size=4>
		Managed for customer by AWS
	</font>
</details>

<br>

- ### **Shared Responsibility Model**

	- ### **Shared Responsibility Model** is part of which pillar of the AWS Well-Architected Framework?
		- Security

![](sharedResponsibilityModel.jpg)

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
		- Infrastructure Event Management (IEM) for additional fee
	### **Enterprise**
		(Same as Business, in addition...)
		- Includes Technical Account Manager (MONITORING) and Concierge (ACCOUNT & BILLING)
		- x < 15 minutes response time for business-critical system failure
	### **Enterprise on Ramp**
		(Same as Enterprise except...)
		- x < 30 minutes response time for business-critical system failure

<br>

<details>
  	<summary>
		<strong>
			<font size=5>
				SaaS
			</font>
		</strong>
	</summary>
	<font size=4>
		Whole stack is managed for you; Focus on how you will use the software
	</font>
</details>

<details>
  	<summary>
		<strong>
			<font size=5>
				Paas
			</font>
		</strong>
	</summary>
	<font size=4>
		Don’t need to manage infrastructure (hardware and OS); Focus on deployment and management of applications.
	</font>
</details>

<details>
  	<summary>
		<strong>
			<font size=5>
				IaaS
			</font>
		</strong>
	</summary>
	<font size=4>
		Hardware and hypervisor are managed for you; Most flexibility and control
	</font>
</details>

<details>
  	<summary>
		<strong>
			<font size=5>
				Acceptable Use Policy
			</font>
		</strong>
	</summary>
	<font size=4>
		Customers can Penetration test selected services in their infrastructure without needing approval from AWS
	</font>
</details>

<details>
  	<summary>
		<strong>
			<font size=5>
				Active-Active
			</font>
		</strong>
	</summary>
	<font size=4>
		Workload deployed to multiple regions; fault tolerance for natural disasters
	</font>
</details>

<details>
  	<summary>
		<strong>
			<font size=5>
				Per Second billing
			</font>
		</strong>
	</summary>
	<font size=4>
		Linux, Windows, Ubuntu
	</font>
</details>

<details>
  	<summary>
		<strong>
			<font size=5>
				Amazon Cloud Directory
			</font>
		</strong>
	</summary>
	<font size=4>
		Organize data hierarchies based on relationships
	</font>
</details>

<details>
  	<summary>
		<strong>
			<font size=5>
				Trusted Advisor
			</font>
		</strong>
	</summary>
	<font size=4>
		Real-time recommendations to optimize Cost, Security, Fault tolerance, Performance + Identify underutilized EC2 instances <strong>AND</strong> unrestricted access to EC2 instance ports
	</font>
</details>

<details>
  	<summary>
		<strong>
			<font size=5>
				Service limits
			</font>
		</strong>
	</summary>
	<font size=4>
		Contact AWS support to increase service limits + AWS Trusted Advisor monitors service limits
	</font>
</details>

<details>
  	<summary>
		<strong>
			<font size=5>
				APN Consulting Partners
			</font>
		</strong>
	</summary>
	<font size=4>
		Professionals help design, build and manage AWS workloads
	</font>
</details>

<details>
  	<summary>
		<strong>
			<font size=5>
				Simple Workflow Service (SWF)
			</font>
		</strong>
	</summary>
	<font size=4>
		Coordinate tasks across distributed application components
	</font>
</details>

<details>
  	<summary>
		<strong>
			<font size=5>
				Avoid CAPEX costs?
			</font>
		</strong>
	</summary>
	<font size=4>
		Public cloud
	</font>
</details>

<details>
  	<summary>
		<strong>
			<font size=5>
				How does AWS help customers achieve compliance?
			</font>
		</strong>
	</summary>
	<font size=4>
		AWS has common compliance certifications: PCI, ISO, HIPAA
	</font>
</details>
