cloudflarecp
======================
Shell/Bash script to install CloudFlare on cPanel servers, and add CloudFlare IPv4 and IPv6 to ConfigServer Firewall (CSF).

This is for server administrators who want to provide CloudFlare to their cPanel customers, and needs to be used on a VPS/Cloud/Dedicated Server.

API key is required.

## Installation
Download
``` bash
wget https://raw.smyl.es/cloudflarecp/master/cloudflarecp
```
Change permissions to allow execute
``` bash
chmod +x cloudflarecp
```

## Add API Key
Edit cloudflarecp using nano, vim, whatever flavor your like
``` bash
nano cloudflarecp
``` bash

Add API key
``` bash
APIKEY=1a2b3c4d5e6f7g8h9i10
```

## Install CloudFlare
``` bash
./cloudflarecp "My Hosting Company"
```