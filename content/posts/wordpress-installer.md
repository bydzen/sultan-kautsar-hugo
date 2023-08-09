---
title: "Wordpress Installer"
date: 2023-08-09T16:03:41+07:00
tags: ['rayatiga', 'wordpress', 'bash-script']
categories: ['documentation']
author: 'Sultan Kautsar'
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: 'Automation script for installing and setup WordPress in server.'
canonicalURL: 'https://canonical.url/to/page'
disableHLJS: true
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
  image: 'https://sultankautsar.com/asset/image/sultankautsar-og.png'
  alt: "Rebage"
  caption: "<text>" # display caption under cover
  relative: false # when using page bundles set this to true
  hidden: true # only hide on current single page
---

# wordpress-installer

Automation script for installing and setup WordPress in server.

## installation

```bash
git clone https://github.com/rayatiga/wordpress-installer.git
```

## preparing

Go to inside `wordpress-installer` directory

```bash
cd wordpress-installer/
```

Make `wp-install.sh` executable

```bash
chmod +x wp-install.sh
```

## using

Execute with `sudo` or `root` privileges

```bash
sudo ./wp-install.sh
```
