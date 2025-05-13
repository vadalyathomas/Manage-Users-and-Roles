# Manage-Users-and-Roles with Active Directory

In this Lab, I configured access control authority for multiple administrators (NSX-Admin, NSX-Auditor, and NSX-Network). I created groups in Active Directory (AD), and then added users to the new groups. Next, I added Active Directory as an identity source in the NSX manager. Finally, I assigned user groups to the pre-defined roles available in NSX (Network Virtualization and Security Platform, a VMWare product), and then I inserted and tested the various permissions.

Once a domain is added to the NSX manager as an identitiy source, Active Directorty users and groups can be used for access control in NSX.

![IMG_2327](https://github.com/user-attachments/assets/de33e237-7b94-4eb7-8bbd-93faeb8fa4ec)

An LDAP(Lightweight Directory Accesss Protocol) identitiy source is used to bind NSX to an Active Directory domain for access control.

![IMG_2330](https://github.com/user-attachments/assets/2b9ebe8c-4084-4411-8001-b6c73846aa9c)

Assigning Roles to users and groups, controls what functionality is available.
