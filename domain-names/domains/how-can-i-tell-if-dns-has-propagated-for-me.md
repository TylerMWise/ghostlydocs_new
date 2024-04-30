# How can I tell if DNS has propagated for me?

If you're unsure whether DNS has fully propagated for you, you should check the IP address your requests are resolving-to. The easiest way to do this is to 'ping' the domain name from your local computers. On Windows, you should open a Command Prompt and on macOS a Terminal, and then type:

```powershell
ping domain.com
```

Replacing _domain.com_ with the website you wish to check. The IP address returned will show you which server you're reaching when typing that domain into your web browser. It's a good idea to check both 'www.domain.com' and 'domain.com', as each record will have its own cache.&#x20;

To tell if this is the server at Ghostly Cloud, you should make sure the IP address returned by the “ping” matches the IP address displayed down the right-hand side of our control panel. If this isn't the case, and you have recently created a new hosting package, manually changed your DNS records, or updated your nameservers on the domain, it's likely DNS is still propagating for you.&#x20;
