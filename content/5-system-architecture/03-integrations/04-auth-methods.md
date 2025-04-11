### Authentication methods for APIs

**oAuth**

Basic functionality:

* The 3rd-party website needs to connect to Magento
* You have a Magento admin user account
* The 3rd-party website directs you to the Magento OAuth page
* Magento asks you to log in (if you aren’t already logged in)
* Magento then asks you to authorize the 3rd-party website
* When you do, you are redirected to the 3rd-party website with a token from Magento providing authorization

**Further reading:**

* [OAuth-based authentication](https://devdocs.magento.com/guides/v2.4/get-started/authentication/gs-authentication-oauth.html)

**Token**

There are two use cases for tokens: public communications and private communications.

Public communications represent when someone can locate the token being used. In these cases, the token is typically limited based on the permissions that the user has (for example an admin user will have more permissions than a visitor who isn’t even logged in). These tokens are usually time-limited as well.

Private communications represent when a 3rd-party should have little to no access to a token. These cases would be server-to-server integrations or a mobile app. You can configure these tokens in System > Integrations.

**Further reading:**

* [Token-based authentication](https://devdocs.magento.com/guides/v2.4/get-started/authentication/gs-authentication-token.html)

**Login credentials**

If a customer is logged in, Magento can utilize this login to provide authorization for areas in the system. For example, a developer can look up the customer’s ID in these cases.

For admin users, a token must first be generated with the admin user’s session. Then, they can access resources with the token.

**Credential management in admin**

System > Integrations: used to configure token and OAuth endpoints. You can assign specific resources (activities or available data) to a specific token. If you are developing a mobile app for your store, you likely do not want the mobile app to have access to create shopping cart rules.

System > Users: an admin user has API access to everything that they have admin interface access to. For example, to prevent an admin user from accessing your customers (in the admin panel or API), simply uncheck their access in Role Resources.
