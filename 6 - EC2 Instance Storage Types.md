# Section 6 - EC2 Instance Storage Types

# **6EC2ST-EBS(VS),AMI(PCM),IB,IS,EFS(I),FSx**

## **Elastic Block Store** (EBS)
- ### **EBS Volume** = Attached to EC2 Instances in a AZ (e.g. us-east-1a) so they persist data even after termination
	- 1 **EBS Volume** to 1 **EC2 Instance**
	- Provision Capacity Amount
- ### **EBS Snapshot** = Backup of an EBS Volume at a point in time
	- Can copy snapshots across AZ or Region.
	- **EBS Snapshot Archive** = Moving snapshots to another storage tier

<br>

## **Amazon Machine Image** (AMI)
- ### Customization of an EC2 Instance (software, configuration, OS...)
- ### **3 Types:**
	- **Public AMI** = AWS provided and manages the AMI
	- **Custom AMI** = You create and maintain the AMI
	- **AWS Marketplace AMI** = 3rd party AMI

<br>

## **Image Builder**
- ### Automatically build, test and distribute AMI'S on a schedule e.g. weekly

<br>

## **Instance Store**
- ### High performance hardware disk attached to an EC2 Instance
- ### Storage lost if stopped **(ephemeral)**; not designed for long term storage

<br>

## **Elastic File System** (EFS)
- ### Attached to multiple EC2 instances in a region
- No Provisioning Capacity Amount
- ### **EFS Infrequent Access (EFS-IA)** = **Cost optimized** for infrequently accessed files
- ### **Linux; NFS Protocol**

<br>

## **FSx**
- ### Managed 3rd party AWS file storage
- ### **2 options:**
	- **FSx Lustre** = For **High Performance Computing** in Linux
	- **FSx Windows File Server** = **Windows; SMB Protocol**
