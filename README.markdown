Amazon Marketplace Web Services (Amazon MWS)
============================================


There are six feeds to manage products on Amazon
------------------------------------------------

* Product feed - Contains descriptive information about the products in your catalog. Establishes the mapping between your unique identifier (the SKU) and the Amazon unique identifier (the ASIN: Amazon Standard Identification Number). This is always the first feed to send when listing a new item.

* Inventory feed - Communicates the current stock levels of the products you are listing on Amazon. Includes values for restock dates as well as your fulfilment latency (the time it will take you to process the order before shipping it).

* Pricing feed - Sets the current prices for your products, whether the regular (standard) prices or temporary (sale) prices.

* Image feed - Supplies URLs (on your server) from which Amazon can pull images to associate with your products.

* Relationship feed (not always applicable) - Defines relationships between different products in your catalog. There are two types of relationships:

* Variation (the most common type of relationship) - Allows customers to select from a list of variations of the same product, such as different sizes and colours.

* Accessory - Allows customers to select products classified as accessories to the main product on a product detail page. For example, a portable radio might have batteries and external speakers listed as accessories.

* Overrides feed (not always applicable) - Allows you to override the account-level shipping settings with SKU-level shipping settings. This can work well for a heavy or oversized product such as a kayak. 


Amazon documentation is located at https://developer.amazonservices.co.uk/gp/mws/docs.html
