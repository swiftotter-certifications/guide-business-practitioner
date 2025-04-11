## 6.01 Demonstrate how to secure the Adobe Commerce data access with roles and permissions

It is best practice for site security as well as PCI compliance to actively maintain user access.

* Create roles specific to permissions each user group needs. A partner who requires admin access may only require access to their integration’s specific configuration.
* Be sure to include 2FA access to all users. Note there is a permission to manage 2FA as well as one to allow a user to set it up. Be sure to grant the correct permission.
* Be sure restricted users don’t have access to change user roles or permissions. You wouldn't want a restricted user to be able to change their permissions or add another user with unrestricted access.
* Only grant access to users as needed. If you have a staff member temporarily assisting with merchandising, you should disable their user after their work is complete.
* Utilize user access expirations, when appropriate. This is a great way to turn off access without having to manually disable. If the user requires an extension, it takes only a moment to update the expiration date as needed.
* If using Commerce, you can also limit user permissions by website. This is helpful when you have separate merchandising teams. This can help prevent data entry for the incorrect website.

For additional security

* Prevent shared use of a single log in
* Force password resets via configuration
