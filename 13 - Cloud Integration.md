# 13 - Cloud Integration

<details>
  	<summary>
		<strong>
			<font size=5>
				SQS
			</font>
		</strong>
	</summary>
	<font size=4>
		- <strong>Queue service</strong>; up to 14 days message retention
	</font>
	<br>
	<font size=4>
		- <strong>Decouple applications</strong>
	</font>
	<br>
	<font size=4>
		- Multiple Producers, Consumers; share the reads from <strong>distributed applications</strong> and delete messages when read by consumers
	</font>
</details>

<br>

<details>
  	<summary>
		<strong>
			<font size=5>
				SNS
			</font>
		</strong>
	</summary>
	<font size=4>
		- <strong>Notification Service</strong>; No message retention
	</font>
	<br>
	<font size=4>
		- <strong>Decouple applications</strong>
	</font>
	<br>
	<font size=4>
		- 1 message to many subscribers; text and email
	</font>
	<br>
	<font size=4>
		- Sends all messages to all subscribers
	</font>
</details>

<br>

<details>
  	<summary>
		<strong>
			<font size=5>
				SES
			</font>
		</strong>
	</summary>
	<font size=4>
		- <strong>Email Service</strong>; pay as you go
	</font>
	<br>
	<font size=4>
		- Send and recieve (bulk) email from within any application
	</font>
</details>

<br>

<details>
  	<summary>
		<strong>
			<font size=5>
				Kinesis
			</font>
		</strong>
	</summary>
	<font size=4>
		Real-time data streaming, persistence and analytics
	</font>
</details>

<br>

<details>
  	<summary>
		<strong>
			<font size=5>
				Amazon MQ
			</font>
		</strong>
	</summary>
	<font size=4>
		Managed message broker for <strong>ActiveMQ</strong> and <strong>RabbitMQ</strong>; <strong>MQTT</strong>, <strong>AMQP</strong> protocols
	</font>
</details>