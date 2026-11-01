# ActiveDirectory
Built an Active Directory home lab in VMware using Windows Server 2025 as the domain controller and Windows 11 (64-bit) as the client. I created a domain, organizational units, users, and security groups. I also joined the Windows client to the domain.

<img width="1534" height="1079" alt="image" src="https://github.com/user-attachments/assets/c6617270-afd4-4535-a6c4-2f095650e543" />

Created organizational units for Accounting, HR, and IT to organize accounts by department.

<img width="823" height="580" alt="image" src="https://github.com/user-attachments/assets/f9ffd1f0-9f73-4252-9d69-6b9dcae9be0d" />

Created test user accounts within each department's organizational unit. This is the example for the IT department.

<img width="907" height="605" alt="image" src="https://github.com/user-attachments/assets/6b0d3c9c-0f7d-4066-a80a-4c3b54872aa1" />

Added department users to security groups to manage access to shared resources. This screenshot shows that the user, Kayla Byrd, is a member of the security group named "IT Staff".

<img width="481" height="519" alt="image" src="https://github.com/user-attachments/assets/1b4e2642-a66a-4dc3-be98-02e36f5b4535" />

Joined the Windows client computer to the Active Directory domain. "Computer01" is the client computer name and "homelab.local" is the domain controller.

<img width="1182" height="675" alt="image" src="https://github.com/user-attachments/assets/056fb289-1e8e-4248-b429-efbbfc54385c" />

Signed into the client using a domain account and verified the account with the whoami command.
