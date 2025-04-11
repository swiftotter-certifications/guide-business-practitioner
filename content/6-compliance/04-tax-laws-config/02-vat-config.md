### Configuring VAT

To set up VAT for European countries:

* Import the applicable rates into Magento using System > Import/Export Tax Rates
* Create two tax rules:
    * B2C
        * Select a B2C customer group (those that do not have a valid VAT ID)
        * Select all EU B2C tax rates
    * B2B
        * Select a B2B customer group (customers who have a valid VAT ID)
        * Select tax rates applicable to the current country
* You can also set up automatic group assignment for validated VAT

Remember, the above does not constitute tax advice and will certainly not stand up in a court of law.

**Further reading:**

* [Configuring VAT ID Validation](https://docs.magento.com/user-guide/tax/vat-validation-configure.html)
