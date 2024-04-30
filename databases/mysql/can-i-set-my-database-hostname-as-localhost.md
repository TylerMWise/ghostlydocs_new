# Can I set my database hostname as 'localhost'?

No, you would need to set the database hostname as the server that it's on at Ghostly Cloud.

You can find this by going to the **MySQL Databases** icon within a package. The hostname you’ll need to use will be something similiar to ‘shareddb1b.hosting.stackcp.net’ although it's likely the database name on your package will be different.

'localhost' generally means the MySQL databases are hosted on the same server as the websites, which is quite common in the web hosting industry with hosts that have a 'single-server' approach where all services run from the same machine.

It's different at Ghostly Cloud as we split all services and have a strict 'one server, one rule' policy.&#x20;

At the Ghostly Cloud data centres, web traffic, MySQL traffic and storage are all physically different machines, so 'localhost' doesn't work.
