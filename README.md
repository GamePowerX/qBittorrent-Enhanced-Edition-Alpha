qBittorrent Enhanced Edition Alpha
------------------------------------------
Unofficial version of the newest qBittorrent Alpha merged with the latest c0re100/qBittorrent-Enhanced-Edition with a few custom changes.
********************************
# Custom changes added in this repo:
1. Country names of peers appear next to the country flag rather than in the tooltip
2. External IP address is shown in the statusbar
3. Number of connected peers showing in the statusbar
4. Number of the downloading piece showing in the row of the peer
------------------------------------------
[Important Note for user and tracker operators](NOTE.md)
********************************
# Features from c0re100/qBittorrent-Enhanced-Edition:
1. Auto Ban Xunlei, QQ, Baidu, Xfplay, DLBT and Offline downloader

2. _Auto Ban Unknown Peer from China_ Option (Default: OFF)

3. Auto Update Public Trackers List (Default: OFF)

4. Auto Ban BitTorrent Media Player Peer Option (Default: OFF)

5. Peer whitelist/blacklist
********************************
### Description:
qBittorrent is a bittorrent client programmed in C++ / Qt that uses
libtorrent (sometimes called libtorrent-rasterbar) by Arvid Norberg.

It aims to be a good alternative to all other bittorrent clients
out there. qBittorrent is fast, stable and provides unicode
support as well as many features.

The free [IP to Country Lite database](https://db-ip.com/db/download/ip-to-country-lite) by [DB-IP](https://db-ip.com/) is used for resolving the countries of peers. The database is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

### Installation:
For installation, follow the instructions from INSTALL file, but simple:

```
./configure
make && make install
qbittorrent
```

will install and execute qBittorrent hopefully without any problem.

### Misc:
For more information please visit:
https://www.qbittorrent.org

or our wiki here:
http://wiki.qbittorrent.org

Use the forum for troubleshooting before reporting bugs:
http://forum.qbittorrent.org

Please report any bug (or feature request) to:
http://bugs.qbittorrent.org

For enhanced features bug(such as Auto Ban, API, Auto Update Tracker lists or our custom features), please first report to:
https://github.com/GamePowerX/qBittorrent-Enhanced-Edition-Alpha/issues
