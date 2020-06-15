# FreeProxyList
This project is using scrapy (https://scrapy.org/) to extract proxy from:
- http proxy (http://www.free-proxy-list.net/)
- https proxy (https://www.sslproxies.org/)

## How to use
Using python pip install scrapy library
```
pip install Scrapy

cd [FreeProxyList PATH]

scrapy crawl freeproxy
```

## You will get
- `httpproxies.txt` with 300 addresses for free `http` proxies
- `sslproxies.txt` with 300 addresses for free `ssl` proxies
