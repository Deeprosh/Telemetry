# Create an IAM user  
- IAM means Identity and Access Management and we will create the IAM users using root account in AWS.  
- In AWS, whatever we do is using services only likewise to create an user in AWS, we have a service called IAM(Identity and Access Management).  
- Using IAM, one can create user accounts, user groups and also can grant permissions to the users or groups.  
- IAM is mainly used for Authentication and Authorization.  
- The concept of RBAC(Role based access control) is to grant authentication and authorization.
## Real-time scenario using Bank:
- In a bank, we have different areas such as entrance, employees desk, safe area, helpdesk area.  
- As an account holder, when we try to enter the bank firstly the security guard will verify if you have an account but you cannot go to employee desk or safe area just because you 
have an account at a bank.  
- The only thing is you can enter the helpdesk area which means as per the bank account holder policy you have Authentication to enter the helpdesk area.
- Authorization means the actual permissions that you have within the bank to enter just the helpdesk area.  
- Whereas bank manager have the permissions of entering the bank, accessing the machines in bank and also have the permission to enter the safe area as an authorized person of the bank.
## AWS scenario:  
- In AWS, only root user have all the privileges to perform and access anything.The root user is authenticated and authorized to do anything in AWS as per the root user policy.
- For a normal IAM user, they are just authenicated to use the AWS services.  
- Authentiction in AWS is carried by Users and user groups. Whereas authorization in AWS, will be carried when a role or policy is assigned to the IAM user.Only then that particular
- IAM user can perform any read/write/execute operations.  
- 
    
