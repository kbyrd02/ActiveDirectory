# ActiveDirectory
Built an Active Directory home lab in VMware using Windows Server 2025 as the domain controller and Windows 11 (64-bit) as the client. I created a domain, organizational units, users, and security groups. I also joined the Windows client to the domain.

<img width="1534" height="1079" alt="image" src="https://github.com/user-attachments/assets/c6617270-afd4-4535-a6c4-2f095650e543" />

DOMAIN & OUs: Created organizational units for Accounting, HR, and IT to organize accounts by department.

<img width="823" height="580" alt="image" src="https://github.com/user-attachments/assets/f9ffd1f0-9f73-4252-9d69-6b9dcae9be0d" />

USER ACCOUNTS: Created test user accounts within each department's organizational unit. This is the example for the IT department.

<img width="907" height="605" alt="image" src="https://github.com/user-attachments/assets/6b0d3c9c-0f7d-4066-a80a-4c3b54872aa1" />

SECURITY GROUP MEMBERSHIP: Added department users to security groups to manage access to shared resources. This screenshot shows that the user, Kayla Byrd, is a member of the security group named "IT Staff".

<img width="481" height="519" alt="image" src="https://github.com/user-attachments/assets/1b4e2642-a66a-4dc3-be98-02e36f5b4535" />

CLIENT DOMAIN MEMBERSHIP: Joined the Windows client computer to the Active Directory domain. "Computer01" is the client computer name and "homelab.local" is the domain controller.

<img width="1182" height="675" alt="image" src="https://github.com/user-attachments/assets/056fb289-1e8e-4248-b429-efbbfc54385c" />

SUCCESSFUL DOMAIN LOGIN: Signed into the client using a domain account and verified the account with the whoami command.

<img width="1171" height="681" alt="image" src="https://github.com/user-attachments/assets/83366249-531c-4e21-b98b-6fdeab604af7" />

<img width="845" height="557" alt="image" src="https://github.com/user-attachments/assets/754e4630-2eab-476c-b941-8ca257cbc610" />

NTFS FOLDER PERMISSIONS: Disabled inheritance on each department folder and assigned folder permissions to the department's security group.

<img width="811" height="679" alt="image" src="https://github.com/user-attachments/assets/9d51f639-b5e6-4dd9-9f61-b66cecf43da4" />

SHARE PERMISSIONS: Configured share permissions to control access to folder over the network.

 <img width="1513" height="698" alt="image" src="https://github.com/user-attachments/assets/f04bfe55-9b3f-4d2a-8695-968d08b55158" />

 <img width="1531" height="685" alt="image" src="https://github.com/user-attachments/assets/52135552-f6de-44fb-9251-6c58c0255145" />

<img width="1535" height="676" alt="image" src="https://github.com/user-attachments/assets/9524d8df-0ebd-4e22-9810-e1d6c4ca4090" />

CONFIRMED SUCCESSFULL FOLDER ACCESS: Signed in as an HR domain user and verified access to the HR shared folder by creating a test file, closing it, reopening it to confirm that I can read it, editing it, and then saving it again to test write access. Then, I deleted the test file to confirm modify access.

<img width="1209" height="660" alt="image" src="https://github.com/user-attachments/assets/f6d2ee82-1a12-4684-98b2-6c2b3ff1ceee" />

CONFIRM DENIAL OF FOLDER ACCESS: Verified that a user from another department (HR) was denied access to the restricted shared folder (IT).
