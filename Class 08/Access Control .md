## Access Control (ACL)

### 5 steps to RBAC

**What is Role Based Access Control (RBAC) and why do we care?**

Role-Based Access Control (RBAC) is a security model that provides a method for managing and controlling access to resources within a system or organization. It is a widely adopted approach for ensuring proper authorization and enforcing security policies.

**Describe a Role/Permission heirarchy that you might implement using RBAC.**

1-Superadmin:This role has full access and control over all system resources
2-Admin:This role has administrative privileges to manage system configurations
3-Manager:This role has permissions to manage specific departments or teams within the organization.
4-Employee:This role represents regular employees within the organization.
5-Guest:This role is assigned to external users or temporary visitors who require limited access to certain resources or functionalities.

**What approach might you take to implement RBAC?**

1-Identify roles: Begin by identifying the different roles within your organization.
2-Determine permissions: Once you have identified the roles, determine the specific permissions or access rights associated with each role. 
3-Assign permissions to roles: Map the identified permissions to the corresponding roles.

### wiki - RBAC

**If Authentication is “you are who you say you are,” what is Authorization?**

the process of granting or denying access rights and permissions to authenticated users or entities.

**Name three primary rules defined for RBAC.**

1-Role Assignment:
2-Role Authorization
3-Role-Permission Association

**Describe RBAC to a non-technical friend.**

RBAC, which stands for Role-Based Access Control, is a way to manage and control access to different things, like information or features, in a system or organization. Imagine it like a big building with different rooms and areas. RBAC helps ensure that only the right people can enter specific rooms or use certain resources.

### RBAC tutorial

**What Are access rights Associated with? The User? or The Role? Explain.**

Access rights in RBAC (Role-Based Access Control) are associated with roles, not individual users. In RBAC, access rights or permissions are assigned to roles based on the responsibilities and job functions associated with those roles.

**Access Rights, or Authorization, is activated after a user successfully does what?**

Access Rights, or Authorization, is activated after a user successfully completes the process of authentication.

**Explain how RBAC might benefit a business.**

1-Improved Security: RBAC enhances security by ensuring that users have appropriate access rights based on their roles and responsibilities.
2-Simplified Access Management: RBAC simplifies the management of access rights by grouping them into roles.
3-Compliance and Auditability: RBAC aids in meeting regulatory compliance requirements and enables easier auditing.