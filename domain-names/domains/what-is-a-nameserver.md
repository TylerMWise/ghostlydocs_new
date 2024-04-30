# What is a nameserver?

A nameserver manages a directory of domains that match specific IP addresses, like a phonebook: with names and numbers.

It is where the DNS server records for your domain (e.g. 'example.com') are stored. Whenever you type a domain name into a web browser, nameservers provide the IP address, which is a string of numbers. If nameservers were not in place, you would need to memorise that string of figures for every website you want to visit.

When you type 'www.examplewebsite.com' into a web browser, your browser uses DNS to look up the nameservers for www.examplewebsite.com. The nameservers ns1.examplewebsite.com and ns2.examplewebsite.com are retrieved.

Your browser then uses the nameservers to look up the IP address for 'www.examplewebsite.com'. Your browser will then receive an IP address which it will then send a request for. The web server hosting the website sends the requested page to the browser.&#x20;

Our nameservers make use of Google's high-end DNS infrastructure, providing fully redundant and stable nameservers.

```
ns1.ghostly.cloud
ns2.ghostly.cloud
ns3.ghostly.cloud
ns4.ghostly.cloud
```
