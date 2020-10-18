# dnsmasq safe search enforced

## Intro

Several search engines provide DNS based enforcement of safe search.

* [Google SafeSearcg documentation](https://support.google.com/websearch/answer/186669?hl=en)
* [Bing SafeSearch documentation](http://help.bing.microsoft.com/#apex/bing/en-us/10003/0)
* [Duckduckgo safe search docuemntation](https://help.duckduckgo.com/duckduckgo-help-pages/features/safe-search/)


This file is a dnsmasq compatible configuration file containing the cname mappings described above.

## Installation

### Linux

Install in the config file in `/etc/dnsmasq.d`
Restart the DNS resolver:
`/etc/init.d/dnsmasq restart`
or 
`sudo restart network-manager`


### Pihole
Install in the config file in `/etc/dnsmasq.d`
Restart the DNS reolver (aka pihole-FTL) via `pihole restartdns`

