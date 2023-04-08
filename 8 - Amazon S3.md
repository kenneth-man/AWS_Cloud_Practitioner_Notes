# Section 8 - Amazon S3

# **8S3-S3F(BOSVRS),S3SC(SIOGGGI),SF(SSS)**

## **S3 Features**
- ### Backup and restore **Data lakes**, and **Archives**
- ### **Bucket (*Directory*)** = Stores **Objects**
	- Must have a globally unique name across all regions all accounts; Region scoped
- ### **Object (*File*)**
	- Contains a key, which is the full path of your object
- ### **Security**
	- S3 Bucket Policies, S3 Encryption, Attach IAM policies to users
- ### **Serve static websites**
- ### **99.99999% Data durability**
- ### **Replication (Cross-Region, Same-Region)**
- ### **Storage Gateway** = Allow on-premise storage to use S3
	- ### **Gateway Virtual Tape Library** = Used with popular backup software
	- ### **File Gateway** = Store and retrieve objects in S3
	- ### **Volume Gateway** = Block-based volumes
- ### **Lifecycle Management**
	- Change storage classes based on age

<br>

## **S3 Storage Classes**
- ### **Standard**
	- Frequently accessed data
	- **GB per month storage** and **Data egress** fee
- ### **Standard Infrequent Access**
	- Infrequently accessed data
	- Cost on retrieval of data
- ### **One Zone-Infrequent Access**
	- Same as above but only in a single AZ; data lost when AZ is destroyed
- ### **Glacier Instant Retrieval**
	- Millisecond retrieval
	- **90** days minimum storage duration
- ### **Glacier Flexible Retrieval**
	- **3 Speeds:**
		- **Expedited** (1-5 minutes)
			- Cost on retrieval of data
		- **Standard** (3-5 hours)
			- Cost on retrieval of data
		- **Bulk** (5-13 hours)
			- Free
	- **90** days minimum storage duration
- ### **Glacier Deep Archive**
	-  **180** days minimum storage duration
- ### **Intelligent Tiering**
	- Move Storage Classes based on usage patterns

<br>

## **AWS Snow Family**
- ### Import data into S3 via a physical device
- ### **Data Migration** = Migrate data into/out of AWS
- ### **Edge Computing** = Preprocess data where location may not have internet access
- ### **Snowcone**
	- Edge Computing and Data Migration
	- TeraBytes of data (TBS)
- ### **Snowball Edge**
	- Natively supports AWS Database Migration Service (DMS)
	- Edge Computing and Data Migration
	- PetaBytes (PB)
- ### **Snowmobile Truck**
	- Data Migration
	- ExaBytes (EB)

<br>

## **AWS Storage Options Overview**
	- BLOCK
		- Amazon EBS
		- EC2 Instance Store
	- FILE
		- Amazon EFS
	- OBJECT
		- Amazon S3
		- Amazon Glacier
