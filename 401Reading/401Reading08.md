# 401 Reading 08

## 5 steps to RBAC

1. What is Role Based Access Control (RBAC) and why do we care?
    [5 steps to simple role-based access control](https://www.csoonline.com/article/3060780/5-steps-to-simple-role-based-access-control.html)
    - Assigning system access to users based on their role within an organization.

2. Describe a Role/Permission heirarchy that you might implement using RBAC.
    - Admin roles are the most common. But you can also designate manager roles, user or something in between

3. What approach might you take to implement RBAC?
    - Inventory systems
    - Analyze workforce and create roles
    - Assign people to roles
    - Never make one-off changes
    - Audit roles periodically

## wiki - RBAC

1. If Authentication is “you are who you say you are,” what is Authorization?
    [Role-Based Access Control](https://en.wikipedia.org/wiki/Role-based_access_control)
    - Determines if the person in a given role has access to the info they are trying to access

2. Name three primary rules defined for RBAC.
    - Role Assignment
    - Role Authorization
    - Permission Authorization

3. Describe RBAC to a non-technical friend.
    - Role-based Access Control is a method of assigning roles to individuals and setting permissions for those roles

## Videos

## RBAC tutorial

1. What Are access rights Associated with? The User? or The Role? Explain.
    [Role Based Access Control](https://www.youtube.com/watch?v=C4NP8Eon3cA)
    - Access is based on the role. Access is given based on the set of rules given to a specific role

2. Access Rights, or Authorization, is activated after a user successfully does what?
    - Once authentication is complete and role is determined

3. Explain how RBAC might benefit a business.
    - Assigning roles makes it easier to set permissions for users. Rather than setting permissions for individuals as they come and go, you just need to assign a role, which is basically a preset set of rules

## Reflection

1. What are your learning goals after reading and reviewing the class README?
    - To learn more about interaction between frontend and backend regarding roles and authorization