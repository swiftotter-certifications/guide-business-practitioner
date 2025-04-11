### Content Staging

Staging (Scheduled Updates, Content Updates) is a powerful feature in Commerce. This allows you to make changes to content, preview, and then release them at a specified date/time.

**Further reading:**

* [Content Staging](https://docs.magento.com/user-guide/cms/content-staging.html)

**Staging Timelines**

Staging timelines allow you to visualize updates on a timeline. This is done in Content > Content Staging > Dashboard.

**Use Cases for staging**

Staging is a powerful way to make updates to the website. You are able to visualize changes before they go live. In addition, you can schedule a group of changes to go live at any given point. This is especially useful for a sale or a product launch that begins at midnight on a specific day (so you don’t have to set your alarm to release it, or worse yet, configure it).

**How can staging be previewed?**

There are two ways:

1. Go into the entity that you are editing, select the update, and click Preview.
2. Go into the content staging dashboard, select the update, and click Preview.

Previews can be shared, but only with admins with permissions to view this area of the admin. Also, note that promotions in progress versus those planned for the future are shown in different colors. After a scheduled change has begun, you will not be able to edit any component of it. This is why staging and preview are such valuable tools.

**Limitations of Staging**

* Staging is not version management. While previous staging updates are stored, the changes from every time you save a product are not stored.
* Staging relies on a properly configured and running cron system. Otherwise, staging updates will not be released.

**Which entities can staging be used with?**

* Products
* Categories
* Catalog Price Rules (replaces start and end dates)
* Cart Price Rules (replaces start and end dates)
* CMS Pages
* CMS Blocks

**How can staging be used with third party extensions?**

Staging is used with 3rd-party extensions if they choose to integrate it. There’s not much else to say.
