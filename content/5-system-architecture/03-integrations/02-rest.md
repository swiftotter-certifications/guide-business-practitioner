### REST

This utilizes JSON (Javascript Object Notation) to send information and retrieve information. The Magento checkout utilizes the REST API. The REST API is fairly unstructured and is the easiest (fastest) method for integrating with Magento.

This is used in a variety of connections, such as:

* Frontend integration, for example, the Magento checkout
* Frontend enhancements where cookies are not utilized
* Server-to-server integrations (see above)

The REST API is not strongly typed. This can result in validation problems (i.e. passing a float where an integer is expected). As such, developers need to keep this in mind to prevent strange data problems (like rounding a decimal number to an integer with no decimal places). With the REST API, there is no defined query language, so formulating selection criteria is up to the developer to specify
