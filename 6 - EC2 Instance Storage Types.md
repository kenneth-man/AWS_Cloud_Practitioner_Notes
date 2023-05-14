# Section 6 - EC2 Instance Storage Types

## **Elastic Block Store** (EBS)
- ### **EBS Volume** = Attached to EC2 Instances in a AZ (e.g. us-east-1a) so they persist data even after termination
	- 1 **EBS Volume** to 1 **EC2 Instance**
	- Provision Capacity Amount
	- **Non-root** and **root** volumes can be **encrypted**
	- **Reduce cost:** Change EBS Volume type (SSD/HDD), Delete Snapshots
	- **Used when data is often changing/ High read write**
- ### **EBS Snapshot** = Backup of an EBS Volume at a point in time; **stored in S3**
	- Can copy snapshots across AZ or Region.
	- **EBS Snapshot Archive** = Moving snapshots to another storage tier

<br>

## **Amazon Machine Image** (AMI)
- ### Customization of an EC2 Instance (software, configuration, OS...), **quickly launch to replace instances incase of failure**
- ### **3 Types:**
	- **Public** = AWS provided and manages the AMI
	- **Custom** = You create and maintain the AMI
	- **Marketplace** = 3rd party AMI; AWS performs periodic security checks on products

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
