# Section 10 - More Compute Services

# **10MCS-(DEFLLEB)**

<details>
  	<summary>
		<strong>
			<font size=5>
				Docker
			</font>
		</strong>
	</summary>
	<font size=4>
		Run applications in containers that run the same way, regardless of where they're run
	</font>
</details>

<br>

<details>
  	<summary>
		<strong>
			<font size=5>
				Elastic Container Service (ECS)
			</font>
		</strong>
	</summary>
	<font size=4>
		Run <strong>Docker</strong> containers by provisioning EC2 Instances
	</font>
</details>

<br>

<details>
  	<summary>
		<strong>
			<font size=5>
				Fargate
			</font>
		</strong>
	</summary>
	<font size=4>
		Run <strong>Docker</strong> containers without provisioning EC2 instances; Serverless
	</font>
</details>

<br>

<details>
  	<summary>
		<strong>
			<font size=5>
				Lightsail
			</font>
		</strong>
	</summary>
	<font size=4>
		Predictable, low pricing for simple applications; <strong>Virtual private servers</strong>, <strong>Managed MySQL DBs</strong>
	</font>
</details>

<br>

<details>
  	<summary>
		<strong>
			<font size=5>
				Lambda
			</font>
		</strong>
	</summary>
	<font size=4>
		- Serverless, FaaS, Automated scaling
	</font>
	<br>
	<font size=4>
		- Invocation time is up to 15 minutes
	</font>
	<br>
	<font size=4>
		- Supports many programming languages except Docker
	</font>
	<br>
	<font size=4>
		- <strong>API Gateway</strong> = Expose Lambda functions as a <strong>HTTP API</strong>
	</font>
	<br>
	<font size=4>
		- <strong>2 types of Lambda Billing:</strong>
	</font>
	<br>
	<font size=3>
		&nbsp; &nbsp; - Time run * RAM provisioned
	</font>
	<br>
	<font size=3>
		&nbsp; &nbsp; - Number of calls/invocations
	</font>
	
</details>

<br>

<details>
  	<summary>
		<strong>
			<font size=5>
				Elastic Container Registry (ECR)
			</font>
		</strong>
	</summary>
	<font size=4>
		Store <strong>Docker</strong> containers on AWS; Ran by <strong>ECS</strong> or <strong>Fargate</strong>
	</font>
</details>

<br>

<details>
  	<summary>
		<strong>
			<font size=5>
				Batch
			</font>
		</strong>
	</summary>
	<font size=4>
		Run batch (vast amount) jobs on AWS across managed EC2 Instances
	</font>
</details>