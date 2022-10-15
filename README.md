How to encrypt an (unencrypted) EC2 EBS volume of a deployed/running EC2 instance

•	Locate the EC2 instances & copy device name
•	Create a snapshot of the EBS volume
•	Copy snapshot (unencrypted) to an encrypted copy
•	Create an EBS volume from the encrypted snapshot, in the same availability zone 
•	Stop the EC2 instance
•	Detach existing volume
•	Attach the new volume with the copied device name
•	Delete the unencrypted EBS Volume
•	Restart the EC2 instance

![image](https://user-images.githubusercontent.com/109040029/195967321-bf9e611f-be85-4c43-892e-c3981ffc903b.png)

![image](https://user-images.githubusercontent.com/109040029/195967354-d6089c73-2bbf-4fab-ba17-3352184ff131.png)

![image](https://user-images.githubusercontent.com/109040029/195967386-e304eaca-7171-4b05-a38f-42d323e39b18.png)

![image](https://user-images.githubusercontent.com/109040029/195967411-a659374e-a081-45a6-abd9-58ae64b78038.png)
