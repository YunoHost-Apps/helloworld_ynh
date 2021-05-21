# Hello World pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/helloworld.svg)](https://dash.yunohost.org/appci/app/helloworld) ![](https://ci-apps.yunohost.org/ci/badges/helloworld.status.svg)  ![](https://ci-apps.yunohost.org/ci/badges/helloworld.maintain.svg)
[![Installer helloworld avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=helloworld)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install helloworld quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Vue d'ensemble

Une app simple et bidon pour illustrer comme le packaging d'app de YunoHost fonctionne

**Version incluse:** 0.1~ynh1







## Documentations et ressources

* Site official de l'app : https://en.wikipedia.org/wiki/%22Hello,_World!%22_program



* Documentation YunoHost pour cette app: https://yunohost.org/app_helloworld
* Signaler un bug: https://github.com/YunoHost-Apps/helloworld_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/helloworld_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/helloworld_ynh/tree/testing --debug
or
sudo yunohost app upgrade helloworld -u https://github.com/YunoHost-Apps/helloworld_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications:** https://yunohost.org/packaging_apps