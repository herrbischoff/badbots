# badbots

Current CIDR-formatted list of unwanted bots caught on my systems, updated
hourly.

## Bad Bots

These contain hacking attempts, probing, scanning, impersonating search engines
and lots more. As only manually curated filters trigger a listing, this should
be safe to use.

* [IPv4 Addresses](https://github.com/herrbischoff/badbots/raw/master/badbots_ipv4.cidr)
* [IPv6 Addresses](https://github.com/herrbischoff/badbots/raw/master/badbots_ipv6.cidr)

## Email Spam Bots

Spam senders, especially those with an unusually high SpamAssassin score (15+).

* [IPv4 Addresses](https://github.com/herrbischoff/badbots/raw/master/spam_ipv4.cidr)
* [IPv6 Addresses](https://github.com/herrbischoff/badbots/raw/master/spam_ipv6.cidr)

## Crawlers

These contain a wide range of automated crawlers from the areas of SEO, data
mining, aggressive Chinese and Russian bots, questionable security research and
similar. May not be suitable for general use.

* [IPv4 Addresses](https://github.com/herrbischoff/badbots/raw/master/crawlers_ipv4.cidr)
* [IPv6 Addresses](https://github.com/herrbischoff/badbots/raw/master/crawlers_ipv6.cidr)

## Facebook Crawler

There are now Facebook Crawler IP ranges available, generated with the
instructions to be found via [Facebook's webmaster
documentation](https://developers.facebook.com/docs/sharing/webmasters/crawler).
Effectively it's generating what's meant to be a whitelist. You can use it as
such — or the opposite.

* [IPv4 Addresses](https://github.com/herrbischoff/badbots/raw/master/facebook_ipv4.cidr)
* [IPv6 Addresses](https://github.com/herrbischoff/badbots/raw/master/facebook_ipv6.cidr)

## Providers

Several large ISPs with a track record of being the origin of many attacks.

* [Folder](https://github.com/herrbischoff/badbots/raw/master/providers/)

## VNPT (Vietnam Posts and Telecommunications Group)

This particular state-owned telecommunications company has an ongoing problem
with spammers, break-in attempts and malware. They are either not up to the
task to contain this to a reasonable degree or they just don't care. There's
now a list of IPs caught by my systems, especially repeated attempts with that
pesky message `hostname static.vnpt.vn does not resolve to address
14.169.239.162`.

Probably empty since I'm blocking email from VN for the time being.

* [IPv4 Addresses](https://github.com/herrbischoff/badbots/raw/master/vnpt_ipv4.cidr)
* [IPv6 Addresses](https://github.com/herrbischoff/badbots/raw/master/vnpt_ipv6.cidr)

## VPN

Many popular and obscure commercial VPN providers. Blocking those has
effectively halved my abusive traffic.

* [IPv4 Addresses](https://github.com/herrbischoff/badbots/raw/master/vpn_ipv4.cidr)
* [IPv6 Addresses](https://github.com/herrbischoff/badbots/raw/master/vpn_ipv6.cidr)

## WordPress

Any kind of WordPress-focused abuse: scanning, probing, user enumeration,
XMLRPC spamming, bruteforce password attacks, you name it.

* [IPv4 Addresses](https://github.com/herrbischoff/badbots/raw/master/wordpress_ipv4.cidr)
* [IPv6 Addresses](https://github.com/herrbischoff/badbots/raw/master/wordpress_ipv6.cidr)
