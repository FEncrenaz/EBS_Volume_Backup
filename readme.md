# Configure EBS Volume Backup Policy 

Use python script to configure EBS volume backup policy

## Primary usage

- Run the python file with 4 prompted fields to create a new policy, and 5 to update the current policy with policy id.

## Components & Libraries

- AWS EC2

- boto3

## Permissions

In order to perform desired actions, several permission should be obtained:

- Default volume backup policy permission

## Procedure

* After creating a new policy, the script will create policy as well as creating a txt file with the policy id.

* If updates are needed, use the policy id in the text file to update current policy with policy id as the fifth input argument. 

* Example config: python dlm.py Test_Instance 14 INSTANCE
