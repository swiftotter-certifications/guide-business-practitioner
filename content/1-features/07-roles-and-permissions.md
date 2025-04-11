## 1.07 Demonstrate how to restrict the Adobe Commerce data access with roles and permissions

**User Roles**

User roles define what capabilities an admin user has. For example, you can prevent an admin user from modifying products or viewing orders. Additionally, in Commerce, you can restrict an admin user to a particular website.

These are configured in System > Permissions > User Roles.

Each admin user can have one role assigned to them.

There are hundreds of configuration points of authorization for a user. They cover every aspect of the default admin area. It is best practice to limit the scope of user privileges to include only what is needed.

Note that 2FA, which is enabled by default in 2.4, has its own permission that must be enabled for a user to be able to sign in.

**Further reading:**
* [Permissions](https://docs.magento.com/user-guide/system/permissions.html)