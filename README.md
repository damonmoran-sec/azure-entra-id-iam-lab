# Azure Entra ID Identity and Access Management Lab

## Objective
This lab demonstrates how to manage users, groups, and role-based access in Microsoft Entra ID using a Microsoft Azure Free Subscription. It also shows how to review audit and sign-in logs for security monitoring.

## Environment
- Microsoft Azure Free Subscription
- Microsoft Entra ID (Azure Active Directory)
- Default Directory

## Lab Steps

### 1. Create Users
Created two users in the tenant:
- **User One**
- **User Two**

### 2. Create a Security Group
Created a security group named **IT-Group** and added **User One** as a member.

### 3. Assign Role
Assigned the **User Administrator** role to **User One** to demonstrate delegated administrative control over users and groups.

### 4. Review Logs
Used the **Audit logs** and **Sign-in logs** features to verify operations and user activity.

## Skills Demonstrated
- Identity and Access Management (IAM)
- Group and Role Management
- Role Based Access Control (RBAC)
- Audit and Security Log Analysis

## Screenshots

### Users
![Users](users.png)

### Group Membership
![Group](group.png)

### Assigned Roles
![Assigned Roles](roles.png)

### Audit Logs
![Audit Logs](audit.png)

### Sign-in Logs
![Sign-in Logs](signin.png)

---

## Notes
This lab was completed on a free Azure subscription using only built-in Microsoft Entra ID features.
