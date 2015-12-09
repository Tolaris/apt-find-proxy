apt-find-proxy
==============

apt-find-proxy, a tool to use APT proxies only if they are found.

On a Debian/Ubuntu system, install the .deb file from my repository:

http://www.tolaris.com/apt-repository/

Then run:

	apt-get update
	apt-get install apt-find-proxy

Or create the deb file on your own:

```
dpkg-deb --build apt-find-proxy/
dpkg -i apt-find-proxy.deb
```
