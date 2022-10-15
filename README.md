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

![image](https://user-images.githubusercontent.com/109040029/195967156-377262d1-b2c8-4e0e-bb5f-35b8955c9acb.png)

![image](https://user-images.githubusercontent.com/109040029/195967165-f80ccd7d-49de-48b9-aeed-3e66bf77871c.png)

![image](https://user-images.githubusercontent.com/109040029/195967173-469177b4-d234-44b5-befa-b525cab8919c.png)

![image](https://user-images.githubusercontent.com/109040029/195967184-805c844c-8f13-483f-9c9e-0f59ca508426.png)
