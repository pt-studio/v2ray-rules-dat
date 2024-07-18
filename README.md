# v2ray-rules-dat customize for VNese

Credit https://github.com/Loyalsoldier/v2ray-rules-dat

Download links

- geoip.dat
  - https://github.com/pt-studio/v2ray-rules-dat/releases/latest/download/geoip.dat
  - https://cdn.jsdelivr.net/gh/pt-studio/v2ray-rules-dat@release/geoip.dat
- geosite.dat
  - https://github.com/pt-studio/v2ray-rules-dat/releases/latest/download/geosite.dat
  - https://cdn.jsdelivr.net/gh/pt-studio/v2ray-rules-dat@release/geosite.dat

## geoip.dat

- Generated through the repository [@Loyalsoldier/geoip](https://github.com/Loyalsoldier/geoip)
- The global IP addresses (IPv4 and IPv6) come from [MaxMind GeoLite2](https://dev.maxmind.com/geoip/geoip2/geolite2/)
- New categories (for users with special needs):
  - geoip:cloudflare
  - geoip:cloudfront
  - geoip:facebook
  - geoip:fastly
  - geoip:google
  - geoip:netflix
  - geoip:telegram
  - geoip:twitter

> Want to customize the `geoip.dat` file? Check out the repository [@Loyalsoldier/geoip](https://github.com/Loyalsoldier/geoip)。

## geosite.dat

- Based on data from [@v2fly/domain-list-community/data](https://github.com/v2fly/domain-list-community/tree/master/data) generated through the repository [@Loyalsoldier/domain-list-custom](https://github.com/Loyalsoldier/domain-list-custom)

- **Added EasyList and EasyListChina ad domains**：Obtained from [@AdblockPlus/EasylistChina+Easylist.txt](https://easylist-downloads.adblockplus.org/easylistchina+easylist.txt) and added to the `geosite:category-ads-all` category
- **Added AdGuard DNS Filter ad domains**：Obtained from [@AdGuard/DNS-filter](https://kb.adguard.com/en/general/adguard-ad-filters#dns-filter) and added to the `geosite:category-ads-all` category
- **Added Peter Lowe's ad and privacy tracking domains**：Obtained from [@PeterLowe/adservers](https://pgl.yoyo.org/adservers) and added to the `geosite:category-ads-all` category
- **Added Dan Pollock's ad domains**：Obtained from [@DanPollock/hosts](https://someonewhocares.org/hosts) and added to the `geosite:category-ads-all` category
- **Added system upgrade and privacy tracking domains related to Windows operating systems**：
  - Based on data from [@crazy-max/WindowsSpyBlocker](https://github.com/crazy-max/WindowsSpyBlocker/tree/master/data/hosts)
  - [**Use with caution**] Privacy tracking domains used by Windows operating systems [@crazy-max/WindowsSpyBlocker/hosts/spy.txt](https://github.com/crazy-max/WindowsSpyBlocker/blob/master/data/hosts/spy.txt) added to the `geosite:win-spy` category
  - [**Use with caution**] ystem upgrade domains used by Windows operating systems [@crazy-max/WindowsSpyBlocker/hosts/update.txt](https://github.com/crazy-max/WindowsSpyBlocker/blob/master/data/hosts/update.txt) added to the `geosite:win-update` category
  - [**Use with caution**] Additional privacy tracking domains used by Windows operating systems [@crazy-max/WindowsSpyBlocker/hosts/extra.txt](https://github.com/crazy-max/WindowsSpyBlocker/blob/master/data/hosts/extra.txt) added to the `geosite:win-extra` category

