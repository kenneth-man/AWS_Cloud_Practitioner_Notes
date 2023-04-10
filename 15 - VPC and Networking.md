# 15 - Virtual Private Cloud and Networking

<details>
  	<summary>
		<strong>
			<font size=5>
				VPC
			</font>
		</strong>
	</summary>
	<font size=4>
		- <strong>Subnets</strong> = VPC contains multiple subnets. Network partition of a VPC to isolate resources and network configurations; bound to 1 AZ
	</font>
	<br>
	<font size=4>
		- <strong>2 Gateways:</strong>
	</font>
	<br>
	<font size=3>
		&nbsp; &nbsp; - <strong>Internet Gateway</strong> = Provide Internet access at VPC level
	</font>
	<br>
	<font size=3>
		&nbsp; &nbsp; - <strong>NAT Gateway</strong> = Provide Internet access to private subnets
	</font>
	<br>
	<font size=4>
		- <strong>2 Security Options:</strong>
	</font>
	<br>
	<font size=3>
		&nbsp; &nbsp; - <strong>N(etwork)ACL</strong> = Stateless Firewall rules for inbound/outbound requests, at VPC level
	</font>
	<br>
	<font size=3>
		&nbsp; &nbsp; - <strong>Security Groups</strong> = Stateful Firewall rules for inbound/outbound requests, at EC2 Instance level
	</font>
	<br>
	<font size=4>
		- <strong>Peering</strong> = Privately connect 2 VPC without overlapping IP ranges
	</font>
	<br>
	<font size=4>
		- <strong>Endpoints</strong> = Private access to AWS Services
	</font>
	<br>
	<font size=4>
		- <strong>Flow Logs</strong> = Network traffic logs
	</font>
</details>

<br>

<details>
  	<summary>
		<strong>
			<font size=5>
				Networking
			</font>
		</strong>
	</summary>
	<font size=4>
		- <strong>PrivateLink</strong> = Privately connect to a service in a 3rd party VPC with encrypted channel
	</font>
	<br>
	<font size=4>
		- <strong>2 VPNS:</strong>
	</font>
	<br>
	<font size=3>
		&nbsp; &nbsp; - <strong>Site to Site VPN</strong> = Public internet VPN connection between on-premise networks and AWS
	</font>
	<br>
	<font size=3>
		&nbsp; &nbsp; - <strong>Client VPN</strong> = <strong>OpenVPN</strong> connection into <strong>yourVPC</strong>
	</font>
	<br>
	<font size=4>
		- <strong>Direct Connect</strong> = Direct private connection to AWS
	</font>
	<br>
	<font size=4>
		- <strong>Transit Gateway</strong> = Connect VPC and on-premise networks
	</font>
</details>