### How can MSI sourcing algorithms be used?

Sourcing algorithms determine the source to ship from. Note that choosing stock for fulfillment of an order is manual. You can choose the default algorithm, but it still requires manual intervention via admin to create a shipment.

**Distance priority:** use this if you wish to prioritize the closest source (warehouse). This would be helpful if you ship from multiple warehouses and wish to reduce shipping costs by shipping from a closer warehouse.

**Source priority:** use this if you have a preferred source. This would be helpful if you have a warehouse and a store and wish to preserve stock at your store.

**Google Maps or Offline?**

Google Maps requires an API key, and along with this, a credit card or a free-tier cap. I can't imagine why you wouldn't use Google Maps as that's guaranteed accurate, but maybe there's someone out there that wouldn't? I'll spare you the time of me trying to answer this question as I can guarantee it's not on the test.

To configure offline calculation, you must select this method and THEN https://www.geonames.org/download the address to lat/lon dataset. This must be done for every country you are shipping from AND every country to which you ship.
