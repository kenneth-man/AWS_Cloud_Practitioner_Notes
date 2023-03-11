# Section 5 - Elastic Compute Cloud (EC2)

# **5EC2-EC2,EC2IT(GCMS),PO(ORSSDC)**

## **EC2 Instance**
- Virtual server in the Elastic Compute Cloud (EC2) that runs applications in AWS; IaaS
- ### **Security Groups** = Firewall for EC2 instances; controls what traffic is allowed in/out of EC2 instance
- ### **User Data** = **Bootstrap Script** launched at the first start of an instance to Install updates, software...
- ### Use when need for full control over and instance and DB; patching OS

<br>

## **EC2 Instance Types**
- EC2 Instance Naming Convention e.g. **m5.2xlarge**
	- **m** = Instance Class
	- **5** = generation
	- **2xlarge** = Size within the Instance Class
- ### **General Purpose (M, T, A)**
	- Balance between Compute, Memory and Networking
- ### **Compute Optimized (C)**
	- For tasks that require high performance
- ### **Memory Optimized (R, X, High Memory, Z)**
	- For tasks that process large data sets in memory (RAM)
- ### **Storage Optimized (I, D, H)**
	- For tasks that require high, sequential read and write access to a data set

<br>

## **EC2 Instance Purchasing Options**
- ### **On-Demand**
	- For short-term un-interrupted workloads
	- Pay for what you use
- ### **Reserved**
	- Specify a Reservation Period: **1/3 years**
	- Payment Options: **No upfront, Partial upfront, All upfront**
	- **Regional/Zonal Scope**
	- **Convertible Reserved Instance** (Special **Reserved Instance** which can change the EC2 instance type, family...)
	- Buy/Sell in the **Reserved Instance Marketplace**
- ### **Savings Plan**
	- Commitment to an amount of usage (e.g. paying upfront £X/hour for **1/3 years**)
	- Usage beyond commitment is billed at **On-Demand** price
	- Cannot change EC2 instance family/AWS region
- ### **Spot Instances**
	- For workloads that can allow failure (e.g. Batch Jobs, Flexible workloads)
	- Not suitable for critical jobs or databases
	- Cheapest option
	- Can lose instances at any time; highest bidder for the instance wins
- ### **Dedicated Hosts**
	- Fully dedicated physical server for your use only
	- For software that has compliance or regulatory needs
	- Payment options: **On-Demand, Reserved**
	- Dearest option
- ### **Capacity Reservations**
	- Reserve **On-Demand** instances in a specific AZ for any duration; Charged at **On-Demand** rate whether you run instances or not
	- No time commitment (create/cancel anytime)
	- No billing discount
