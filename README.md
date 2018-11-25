## Skiptracer - OSINT scraping framework
![python](https://img.shields.io/badge/python-2.7-green.svg) ![version](https://img.shields.io/badge/version-0.2.0-brightgreen.svg) ![licence](https://img.shields.io/badge/license-GPLv3-lightgrey.svg) [![](https://images.microbadger.com/badges/image/xshuden/skiptracer.svg)](https://microbadger.com/images/xshuden/skiptracer "Get your own image badge on microbadger.com") [![](https://images.microbadger.com/badges/version/xshuden/skiptracer.svg)](https://microbadger.com/images/xshuden/skiptracer "Get your own version badge on microbadger.com")

![screen](https://i.imgur.com/gG0KZ0F.png)

Initial attack vectors for recon usually involve utilizing pay-for-data/API (Recon-NG), or paying to utilize transforms (Maltego) to get data mining results. Skiptracer utilizes some basic python webscraping (BeautifulSoup) of PII paywall sites to compile passive information on a target on a ramen noodle budget.

Example:
----

[![asciicast](https://asciinema.org/a/RosGkr3mie2s6hjwUJC1TT2lJ.png)](https://asciinema.org/a/RosGkr3mie2s6hjwUJC1TT2lJ)


Docker Installation
----
```
$ docker run -it --name skiptracer xshuden/skiptracer 
OR
$ docker run --rm -it --name skiptracer xshuden/skiptracer  # container is deleted when you're done
```
Installation
----
```
$ git clone https://github.com/xillwillx/skiptracer.git skiptracer
$ cd skiptracer
```
__Install requirements__
```
$ pip install -r requirements.txt
```
__Run__
```
$ python skiptracer.py -l (phone|email|sn|name|plate)
```

Usage
----
Full details on how to use Skiptracer are on the wiki located [here](https://github.com/xillwillx/skiptracer/wiki)
