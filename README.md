# fritzbox-cloudflare-ddns
FRITZ!Box – Cloudflare Dynamic DNS update

You need to open your router DynDNS configuration page, for FRITZ!Box under:  
**Internet** >> **Permit Access** >> **DynDNS**

```
DynDNS Provider: User-defined  
Update URL: https://yourserver.tld/ddns.php?domain=<domain>&ipv4=<ipaddr>&ipv6=<ip6addr>&user=<username>&pass=<pass>  
Domain name: sub.domain.tld  
Username: (username of your choosing)  
Password: (choose a password)  
```
*Username and Password are used for the simple authentication in the PHP script*
