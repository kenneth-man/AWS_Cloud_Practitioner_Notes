# Section 9 - Databases and Analytics

## **Relational Databases** (SQL)
- ### Data Tables that have relationships with each other
- ### **AWS RDS**
	- Create a DB in the cloud using schema
	- **Automated backups and patching via RDS console**
	- **Managed by AWS so simplifies DB Admin role**
	- **Scale up by increasing the instance size or storage capacity**
	- **Dbs created with RDS (all use EBS Volume for storage):**
		- **Aurora** = **Cloud optimized**; better performance than Postgres/MySQL on RDS
		- **Postgres**
		- **MySQL**
	- **Deployment Options:**
		- **Read Replicas**
			- Create up to 5 Read Replicas (copies of your RDS database); application can read from all replicas
			- Writing data is only to the main DB
		- **Multi-AZ**
			- Create up to 1 replication **(Failover DB)** from another AZ
			- Reading/writing data is only to the main DB, until there is a main DB outage, then the **Failover DB** is able to read/write from
		- **Multi-Region**
			- Same as **Read Replicas** but replicas are from different regions

<br>

## **Non-Relational Databases** (NoSQL and JSON)
- ### **DynamoDB**
	- Managed, Serverless, Schemaless
	- **DynamoDB Accelerator (DAX)** = **In-Memory cache** for DynamoDB; cache most frequently read objects
	- **Global Tables** = read/write to any AWS Region

<br>

<details>
  	<summary>
		<strong>
			<font size=5>
				Redshift
			</font>
		</strong>
	</summary>
	<font size=4>
		<strong>SQL Data Warehouse</strong> for <strong>OLAP</strong> (Online Analytical Processing of Data)
	</font>
</details>

<br>
 
<details>
  	<summary>
		<strong>
			<font size=5>
				ElastiCache
			</font>
		</strong>
	</summary>
	<font size=4>
		<strong>In-Memory databases</strong>; cache data for frequently read/write workloads
	</font>
</details>

<br>

<details>
  	<summary>
		<strong>
			<font size=5>
				Elastic MapReduce (EMR)
			</font>
		</strong>
	</summary>
	<font size=4>
		Create Hadoop clusters to process vast amount of data
	</font>
</details>

<br>

<details>
  	<summary>
		<strong>
			<font size=5>
				Athena
			</font>
		</strong>
	</summary>
	<font size=4>
		Query data on Amazon S3
	</font>
</details>

<br>

<details>
  	<summary>
		<strong>
			<font size=5>
				Quantum Ledger Database (QLDB)
			</font>
		</strong>
	</summary>
	<font size=4>
		Managed DB for recording immutable financial transactions
	</font>
</details>

<br>

<details>
  	<summary>
		<strong>
			<font size=5>
				QuickSight
			</font>
		</strong>
	</summary>
	<font size=4>
		Create interactive dashboards from AWS databases
	</font>
</details>

<br>

<details>
  	<summary>
		<strong>
			<font size=5>
				Amazon Managed Blockchain
			</font>
		</strong>
	</summary>
	<font size=4>
		Managed Hyperledger Fabric & Ethereum blockchains
	</font>
</details>

<br>

<details>
  	<summary>
		<strong>
			<font size=5>
				Neptune
			</font>
		</strong>
	</summary>
	<font size=4>
		Managed graph database; complex connected datasets
	</font>
</details>

<br>
 
<details>
  	<summary>
		<strong>
			<font size=5>
				DocumentDB
			</font>
		</strong>
	</summary>
	<font size=4>
		<strong>AWS implementation</strong> of MongoDB
	</font>
</details>

<br>

<details>
  	<summary>
		<strong>
			<font size=5>
				Database Migration Service (DMS)
			</font>
		</strong>
	</summary>
	<font size=4>
		Migrate data from database to database
	</font>
</details>

<br>

<details>
  	<summary>
		<strong>
			<font size=5>
				Glue
			</font>
		</strong>
	</summary>
	<font size=4>
		Managed <strong>Extract, Transform, Load</strong> (ETL) service
	</font>
</details>
