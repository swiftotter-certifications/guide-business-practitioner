### Currency Settings

There are three types of currency configuration (Stores > Configuration > General > Currency Setup):

* **Base currency:** this is the currency in which a product’s price is entered. This value flows through to the order and is the amount and currency that the order is charged in. The scope for this setting is driven by the Price scope in Store Configuration. Note that this is a critical element to determining how many websites/stores/store views a website should have.
* **Default Display currency:** this is the currency that the customer sees on the frontend.
* **Allowed currencies:** this is how you allow customers to choose which currency they want to browse the website in.

Default display and allowed currencies will use the conversion rates setup in the admin to calculate the current estimated conversion. These can be set in Stores > Currency > Rates

For reference, product prices before the product page (category pages, up-sell, cross-sell and related products) are indexed and stored in the database. Starting at the product page, Adobe Commerce uses price calculation classes to determine the product’s price.

**Further reading:**

* [Currency Setup](https://docs.magento.com/user-guide/configuration/general/currency-setup.html)
