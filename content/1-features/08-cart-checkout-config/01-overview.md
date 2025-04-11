### Overview

As mentioned in 1.4, there are many native configurations that affect cart and checkout. These configurations are mostly inside the sales menu of the store configuration. It is recommended that you go through this area in its entirety to review each configuration and what the native options are.

The most noteworthy areas for this section are:

* Sales > Shipping Settings
* Sales > Tax
* Sales > Checkout

**Further reading:**
* [Sales](https://docs.magento.com/user-guide/configuration/sales.html)

**What can registered customers do that guest customers cannot?**

Registered customers can save address information and use previously-saved addresses.

Registered customers can also save payment information (if a vault-enabled payment method is enabled and chosen) and utilize this payment method in the future.

Registered customers can also use the Instant Purchase feature.

You can enable/disable guest checkout here: Sales > Checkout > Allow Guest Checkout

**Further reading:**
* [Guest Checkout](https://docs.magento.com/user-guide/sales/checkout-guest.html)

**Why is the payment step last before order placement?**

The payment step is located here for several reasons:

* Customers are used to entering payment details last.
* When utilizing off-site hosted payment methods, customers are immediately redirected there to make their payment.
* When utilizing on-site hosted payment methods, the card information is tokenized and sent with the place order request.
