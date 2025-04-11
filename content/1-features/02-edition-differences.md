## 1.02 Distinguish the differences between all editions of Adobe Commerce products

### What are the benefits and drawbacks of on-premise vs. cloud?

**On-premise (hosted)**

The merchant is responsible for maintaining their website. Since merchants are experts at selling products, they often do not have the budget or the internal expertise to ensure that the site is properly maintained. Also, new technology requirements in 2.4 (for instance, ElasticSearch) add complexity to the server architecture, so be mindful that inexperienced hosting providers or developers can cause problems. The good news is that many hosting providers have learned the secrets of Adobe Commerce hosting and are providing at least reasonable service.

**Adobe Commerce Cloud**

Adobe Commerce Cloud offers a one-stop approach. The merchant is still responsible for applying patches, but they do not have to worry about the hosting environment because it is maintained by the team that writes the software. The goal is that this provides an exceptional hosting package with unparalleled support and service. Cloud is built on platform.sh. Platform.sh provides the platform with the capability for continuous integration (automated way to get code to production).

In addition, Cloud is integrated with 3rd-party systems to provide a better experience:

* **Fastly full-page cache** and **content delivery network (CDN)**. This also features GeoIP routing to specific store views. Fastly also optimizes images and prevents attacks through the WAF.
* **New Relic Application Performance Monitor** to find performance bottlenecks (or slow-running code) in the application.
* **SendGrid** service for sending outbound emails
* **ElasticSearch** for database search
* **SWAT** (not necessarily a 3rd-party tool) to ensure service continuity. 
* **PrivateLink** to connect the transacting environment with other AWS instances. ([see more](https://devdocs.magento.com/cloud/project/privatelink-service.html))
* **SSH access**. ([see more](https://devdocs.magento.com/cloud/env/environments-ssh.html))

Cloud has multiple environments. We won't get into all the details, but here are a few of the most important:

* **Integration:** multiple integration environments for testing purposes before continuing to production
* **Staging:** a single environment that closely replicates (or is identical to) production
* **Production:** a single environment that is used for running a production website

There are two types of Cloud packages from Adobe Commerce: Starter and Pro

* Pro basically has all the Starter features plus:
  * Business Intelligence Pro
  * Dedicated hardware environment for production (better stability and availability)
  * Slightly different paths for getting code to production 
  * B2B is standard (can add to starter with additional licensing fees)

**Further reading:**
* [Cloud Guide for Commerce](https://devdocs.magento.com/cloud/bk-cloud.html)
