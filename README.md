# OpenTracker for YunoHost

[![Integration level](https://dash.yunohost.org/integration/opentracker.svg)](https://dash.yunohost.org/appci/app/opentracker) ![](https://ci-apps.yunohost.org/ci/badges/opentracker.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/opentracker.maintain.svg)  
[![Install OpenTracker with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=opentracker)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install OpenTracker quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
OpenTracker is a open and free bittorrent tracker project. It aims for minimal resource usage.

**Shipped version:** 1.0

## Screenshots

![](Link to a screenshot of this app.)

## Configuration

`udp://serverIP:6969`

by default the tracker will run on 6969 port on both UDP and TCP.

visit `https://serverIP:6969/stats` to view the tracker stats.

## Documentation

 * Official documentation: http://erdgeist.org/arts/software/opentracker/index/#overview
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

 * Are LDAP and HTTP auth supported?
 * Can the app be used by multiple users?

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/opentracker%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/opentracker/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/opentracker%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/opentracker/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/opentracker_ynh/issues
 * App website: http://erdgeist.org/arts/software/opentracker/
 * Upstream app repository: http://erdgeist.org/gitweb/opentracker/
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/opentracker_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/opentracker_ynh/tree/testing --debug
or
sudo yunohost app upgrade opentracker -u https://github.com/YunoHost-Apps/opentracker_ynh/tree/testing --debug
```
