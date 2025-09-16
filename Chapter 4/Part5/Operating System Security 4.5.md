
---

## Active Directory 

Active Directory is a database of everything on the network like computers, user accounts, file shares, printers, groups, etc. It is specific for Windows. 

Since all of this information is stored in a central redundant database, all of authentications can be managed from this central resource.

AD can be used to authenticate users or a group of users to access specific resources with specific permissions. AD can also be used to reset passwords and to add or remove users.

## Group Policy

Group policies allow for setting of different configuration settings or permissions for each individual user or device. This is usually run from a central console known as the **Group Policy Management Editor** which allows to configure login scripts when a user connects to the network. Can set up network configurations such as **quality of service (QoS)**. Can set up security parameters that all of these devices and users must follow. 

## Security-Enhanced Linux (SELinux)

Linux OS by default works as a discretionary access control device. This means that the user has their own discretion to be able to assign rights and permissions to different resources in the Linux OS. But in many highly secure environments, a discretionary access control in not appropriate. Instead, they would use a mandatory access control where all of the rights and permissions are assigned by a central administrator. 