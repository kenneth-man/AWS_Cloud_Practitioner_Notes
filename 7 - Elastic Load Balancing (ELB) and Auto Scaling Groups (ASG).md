# Section 7 - Elastic Load Balancing (ELB) and Auto Scaling Groups (ASG)

# **7EA-DEF(SEAA),ELB(ANG),ASG(MDP)**

## **Definitions**
- ### **Scalability** = Handle greater loads by adapting
	- **2 types:**
		- **Vertical** = Changing instance size for an application; **scale up**, **scale down**
			- Non-Distributed systems
		- **Horizontal (Elasticity)** = Changing number of instances for an application; **scale out**, **scale in**
			- Distributed systems
- ### **Elasticity** = Acquire resources as you need them
- ### **Availability** = Running application in at-least 2 AZ
- ### **Agility** = Time to make resources available to you

<br>

## **Elastic Load Balancer** (ELB)
- ### Distribute traffic across EC2 Instances in a region
- ### **3 Types:**
	- **Application Load Balancer** (HTTP/HTTPS/gRPC; ***LAYER 7***)
	- **Network Load Balancer** (TCP/UDP; ***LAYER 4***)
	- **Gateway Load Balancer** (GENEVE; ***LAYER 3***)

<br>

## **Auto Scaling Group** (ASG)
- ### Implement elasticity for an application
- EC2 Instances created with ASG, are registered with an ELB
- ### **3 Scaling Strategies:**
	- **Manual Scaling** = Change the size of an ASG manually
	- **Dynamic Scaling** = Respond to changing demand
		- **3 policies:**
			- **Simple/Step**
			- **Target Tracking** = Specify a target to maintain
			- **Scheduled** = Anticipate scaling based on usage patterns
	- **Predictive Scaling** = Machine learning predicts future traffic
