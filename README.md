<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# OpenTracker for YunoHost

[![Integration level](https://dash.yunohost.org/integration/opentracker.svg)](https://dash.yunohost.org/appci/app/opentracker) ![](https://ci-apps.yunohost.org/ci/badges/opentracker.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/opentracker.maintain.svg)  
[![Install OpenTracker with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=opentracker)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install OpenTracker quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Bittorrent tracker

**Shipped version:** 1.0~ynh1

**Demo:** https://dispatch.khlieng.com/connect

## Disclaimers / important information

## Configuration

`udp://serverIP:6969`

by default the tracker will run on 6969 port on both UDP and TCP.

visit `http://serverIP:6969/stats` to view the tracker stats.

## Documentation and resources

* Official app website: http://erdgeist.org/arts/software/opentracker/
* Official admin documentation: http://erdgeist.org/arts/software/opentracker/
* YunoHost documentation for this app: https://yunohost.org/app_opentracker
* Report a bug: https://github.com/YunoHost-Apps/opentracker_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/opentracker_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/opentracker_ynh/tree/testing --debug
or
sudo yunohost app upgrade opentracker -u https://github.com/YunoHost-Apps/opentracker_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps