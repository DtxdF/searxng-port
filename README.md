# SearxNG (port)

SearXNG is a free internet metasearch engine which aggregates results from more than 70 search services. Users are neither tracked nor profiled. Additionally, SearXNG can be used over Tor for online anonymity.

docs.searxng.org

![searxng logo](https://raw.githubusercontent.com/searxng/searxng/master/src/brand/searxng.svg)

## How to use this Port

```console
poudriere ports -c -m git+http -p dtxdf-searxng -U github.com/DtxdF/searxng-port
poudriere bulk -j <jail> -O dtxdf-searxng
```
