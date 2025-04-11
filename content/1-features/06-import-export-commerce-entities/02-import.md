### Import

For each type of import entity, you can download a sample file. This sample file is generic and not related to your store build, but will give you a good starting point to create your own import template.

Import behavior for product-related entities:

* Add/Update: appends import table data to what is already specified. If a value exists on the product in the database, that value is set to the imported value. This is the setting used for well over 90% of imports.
* Replace: deletes the product and re-adds it with the values specified in the import. This is quite dangerous to do as product IDs are changed AND all other values are destroyed.
* Delete: does what you think.

Import behavior for customer-related entities:

* Add/Update Complex Data: any value that the import row contains is replaced, all other values are appended.
* Delete Entities: no surprises here.
* Custom Action: the behavior is determined for each row based on the value in the `<code>_action</code>` column.

**Further reading:**
* [Data Import](https://docs.magento.com/user-guide/system/data-import.html)
* [Data Scheduled Import/Export](https://docs.magento.com/user-guide/system/data-scheduled-import-export.html)
