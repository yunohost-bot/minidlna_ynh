# MiniDLNA pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/minidlna.svg)](https://dash.yunohost.org/appci/app/minidlna) ![](https://ci-apps.yunohost.org/ci/badges/minidlna.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/minidlna.maintain.svg)  
[![Installer MiniDLNA avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=minidlna)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer MiniDLNA rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

MiniDLNA est un simple serveur multimédia, dont le but est d'être entièrement compatible avec les clients DLNA/UPnP-AV.


**Version incluse :** 1.0~ynh8



## Avertissements / informations importantes

## Configuration

Éditez le fichier `/etc/minidlna.conf` pour ajuster la configuration de MiniDLNA.

## Fonctionnalités spécifiques à YunoHost

* Utilise les répertoires multimédia partagés.
* Lié à transmission, Nextcloud et toute autre application qui utilise les répertoires multimédia.

## Documentations et ressources

* Site officiel de l'app : http://minidlna.sourceforge.net
* Documentation YunoHost pour cette app : https://yunohost.org/app_minidlna
* Signaler un bug : https://github.com/YunoHost-Apps/minidlna_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing --debug
ou
sudo yunohost app upgrade minidlna -u https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps