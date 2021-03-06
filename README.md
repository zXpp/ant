
![](./src/assets/READEME/logoAndID.png)

## ANT Downloader

[![Build Status](https://travis-ci.com/anatasluo/ant.svg?branch=master)](https://travis-ci.com/anatasluo/ant)
[![Stable Version](https://img.shields.io/badge/version-1.3.6-blueviolet.svg)](https://img.shields.io/badge/version-1.1.0-blueviolet.svg)
[![License: MPL 2.0](https://img.shields.io/badge/License-MPL%202.0-brightgreen.svg)](https://opensource.org/licenses/MPL-2.0)

### [English](README.md) | [中文](README_zh.md)

> ANT Downloader is a BitTorrent Client developed by golang, angular 7, and electron. ANT aims to be a lightweight, feature-rich, easy-to-use and nice-looking client.

If you like this application, please consider give a star for this project.

## Why you should consider ANT Downloader:
- a BitTorrent client for all platforms
- a BitTorrent client with aesthetic appearance
- a BitTorrent client with low resource occupancy, total size of installation package for windows is only about 40M.
- a BitTorrent client with rich set of functions including:
    - support for IPV4 and IPV6 settings
    - support for torrent file and magnet link
    - support for playing video while downloading
- a easy-to-use BitTorrent client. ANT Downloader will take care of most settings needed for a BitTorrent client, including:
  - Reduce time to analyse magnet link by using [itorrents](https://itorrents.org/)
  - Update best tracker servers from [trackerslist](https://github.com/ngosang/trackerslist)
  - ...

## Considering features in following version:
- [ ] Download and steam selected file (Current version will download all files in one torrent and only steam the biggest file.)
- [ ] Support different UI themes
- [ ] Support more download methods like ed2k, webTorrent
- [ ] Control ANT Downloader from remote machine.

## TODO List
- Add support for network speed limit
- Add support for maximum number of download task

## Architecture:
![](./src/assets/READEME/architecture.jpg)

## Preview:
+ ### Add torrent download task
![](./src/assets/READEME/task.gif)
--------------

+ ### Playing video while downloading
![](./src/assets/READEME/steaming.png)
--------------

## Get Started

You can download packaged binary file directly from [Release](https://github.com/anatasluo/ant/releases)

You can also build project with one of following cmd, and it depends on your system:
```
npm run electron:linux
```

```
npm run electron:windows
```

```
npm run electron:mac
```

More npm usage is described in package.json, make sure your system has following dependences
+ node >= 11.0.x
+ golang >= 1.10.x


# Special thanks

+ [anacrolix/torrent](https://github.com/anacrolix/torrent)
+ [goTorrent](https://github.com/deranjer/goTorrent)
+ [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix)
+ [cloud-torrent](https://github.com/jpillora/cloud-torrent)

# Contact me
You can send emails to luolongjuna@gmail.com.
