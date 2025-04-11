### Configuration

MSI provides configuration values to select the distance provider (Google Maps or offline).

If the merchant wishes to open a new store and ship stock from there, they must first create the new source. The source must be added to the stock linked to the website. Then, they assign that source to individual products (Assign Sources button) or with mass actions on the product grid:

* **Assign Inventory Source:** adds a new inventory source for selected products
* **Transfer Inventory to Source:** moves inventory from one source to another source
* **Unassign Inventory Source:** removes the inventory source for the selected products

Now you are now able to set quantities for each at the product level.

This is somewhat off-topic, but in Adobe Commerce, you can select “Use deferred Stock update” in the Catalog Inventory configuration. Enabling this makes the inventory table updates happen asynchronously after an order is placed. Not enabling this can lead to errors when two or more orders are placed at the exact same time.

**Further reading:**

* [Inventory Management](https://devdocs.magento.com/guides/v2.4/inventory/)
* [Managing Inventory in Commerce](https://docs.magento.com/user-guide/catalog/inventory-management.html)
* [Magento 2 Multi Source Inventory (MSI)](https://firebearstudio.com/blog/magento-2-multi-source-inventory-msi.html)
{