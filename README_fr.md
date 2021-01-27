# OpenTracker pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/opentracker.svg)](https://dash.yunohost.org/appci/app/opentracker) ![](https://ci-apps.yunohost.org/ci/badges/opentracker.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/opentracker.maintain.svg)  
[![Installer OpenTracker avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=opentracker)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer OpenTracker rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
OpenTracker est un projet de tracker bittorrent ouvert et gratuit. Il vise une utilisation minimale des ressources.

**Version incluse :** 1.0

## Screenshots

![](Link to a screenshot of this app.)

## Configuration

`udp://mydomain.com:6969`

by default the tracker will run on 6969 port on both UDP and TCP.

visit `http://serverIP:6969/stats` to view the tracker stats.

## Documentation

 * Documentation officielle : http://erdgeist.org/arts/software/opentracker/index/#overview
 * Documentation YunoHost : Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ?
* L'application peut-elle être utilisée par plusieurs utilisateurs ?

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/opentracker%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/opentracker/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/opentracker%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/opentracker/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations que vous souhaitez ajouter sur cette application.

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/opentracker_ynh/issues
 * Site de l'application : http://erdgeist.org/arts/software/opentracker/
 * Dépôt de l'application principale : http://erdgeist.org/gitweb/opentracker/
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/opentracker_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/opentracker_ynh/tree/testing --debug
or
sudo yunohost app upgrade opentracker -u https://github.com/YunoHost-Apps/opentracker_ynh/tree/testing --debug
```
