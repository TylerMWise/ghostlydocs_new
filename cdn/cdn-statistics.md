# CDN Statistics

With the Ghostly Cloud CDN, you can get an understanding about the traffic and requests accessing your sites.

Detailed data sets are collated and presented in charts for each of your sites at Ghostly Cloud, giving you insights about your site’s performance.

**Accessing site Statistics**

You can access the statistics for each site you host from the package overview page with your Ghostly Cloud account.

* Select the package you wish to view the statistics for by selecting **Manage.**
* Select **Statistics**

You’ll be presented with the **CDN Statistics** overview with the option to switch to the **Traffic Distribution** view.

Total Bandwidth -  This refers to the amount of data (in bytes) sent through the Ghostly Cloud CDN to the client. This is split between data that’s been served from the origin server (uncached bandwidth) and served from the CDN nodes (cached bandwidth).

Total Hits - This refers to the number of files and sessions that have been transferred using the CDN network, it’s important to note that this isn't the same as ‘unique visitors’.

You can filter the statistics by a time period using the toggles at the top-right of each section.

&#x20;

**Traffic Distribution**

The statistics also show a geographic overview of incoming requests to your side. This can also be toggled between Last Hour, Last Day and Last Week.

You can hover over a country to see figures for that location.

&#x20;

**Total Bandwidth**

* Total Bandwidth - Total amount of bandwidth (sum of bytes) served by Ghostly Cloud's CDN network
* Cached Bandwidth - Amount of bandwidth for requests considered as “cached”, i.e., the response is served from Ghostly Cloud's CDN Cache
* Uncached Bandwidth - Amount of bandwidth for requests considered as “uncached”, i.e., the response is served directly from backend server

&#x20;

**Total Hits**

* Total Hits - Total number of requests captured by Ghostly Cloud's CDN network.
* Cached Hits - Number of requests considered as “cached”, i.e., the response is served from Ghostly Cloud's CDN Cache.
* Uncached Hits _-_ Number or requests considered as “uncached”, i.e., the response is served directly from the backend server.

&#x20;

**SSL Hits vs Non-SSL Hits**

This graph shows the number of requests that are encrypted via the HTTPS protocol as opposed to the unencrypted HTTP protocol. If requests to a site such as http://example.com are made, this would constitute an insecure request.&#x20;

You’ll want to ensure that as much as possible requests to your sites are made over HTTPS. Most often, this can be achieved using a 301 redirect, WordPress plugin, or ensuring the WordPress site and home URL utilise HTTPS. You will also need an SSL certificate to cover the site.&#x20;

&#x20;

**HTTP Successful Requests vs Error Requests**

Successful Request - These requests are defined as being all HTTP requests in the range of 200-399, such as '200 OK' requests or 301 Redirects.

Error Requests  - These are defined as being HTTP requests ≥ 400, such as 404 Not Found requests or 503 Internal Server Errors.&#x20;

It’s important that the amount of successful requests is maximised. If you’re seeing a higher rate of error requests, you should consider checking the access and error logs for any data about requests.
