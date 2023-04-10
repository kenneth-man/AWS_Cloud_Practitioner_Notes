# Section 4 - Identity and Access Management (IAM)

## **IAM**
- ### Global service
- ### **User** = People within your organization that can be grouped
- ### **Group** = Can only contain Users
- ### **Permissions** = Apply permission policies to **Users/Groups** in JSON; **Inline Policies** permission policies to a single user
- ### ***AWS managed policies cannot be edited; Users can create custom policies***
- ### **Deploy SSL server certificates**
- ### **Roles** = Apply permission policies to AWS services; **Max 1 role to 1 instance**
- ### **Password Policy** = Apply policies for passwords of AWS accounts
- ### **Multi Factor Authentication (MFA)** = Password you know + Security device you own
	- **MFA Options:**
		- Virtual MFA device (e.g. **authy**)
		- Universal 2nd Factor Security Key (**U2F**) (e.g. **Yubikey**)
		- Hardware Key Fob MFA Device for **AWS GovCloud**
- ### **Security Tools**
	- ### **IAM Credentials Report** = All your account's users and credentials
	- ### **IAM Access Advisor** = Shows permissions for a user and when they last accessed services

<br>

## **Accessing AWS/AWS APIS**
- ### **AWS Management Console**
	- Protected by password and/or MFA
- ### **AWS Command Line Interface (CLI)**
	- Manage AWS services using the command line
	- Protected by access and secret keys
- ### **AWS Software Developer Kit (SDK)**
	- Manage AWS services using a programming language
	- Protected by access and secret keys
