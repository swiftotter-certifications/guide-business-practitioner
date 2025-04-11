## 6.03 Explain common security aspects of an Adobe Commerce project

Requiring 2 factor authentication for admin users and creating a unique admin url helps prevent auto-login attacks

Limiting admin user access scope by setting up appropriate user roles, forcing password resets, and utilizing the admin action log keeps your admin secure, which in turn keeps your store secure.

Enabling secure pages (HTTPS) and setting up a proper SSL cert encrypts communications, which is vital for PCI compliance

Configuring recaptcha for front end submissions helps prevent bots and spam submissions. This can help prevent DDos attacks.

Applying security patches as they become available keeps your store safe from known vulnerabilities. To allow merchants to install this faster than a version upgrade, Adobe has begun releasing security only patches.

It is best practice to install security patches using composer through the lower environments per standard deployment procedure. Adobe commerce also offers the ability to install updates via scheduled cron task, but this can be risky for a site as it would deploy to the live site without testing. Note that as of 2.4, the web installation wizard is no longer available to use.
