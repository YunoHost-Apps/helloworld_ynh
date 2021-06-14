# Hello World pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/helloworld.svg)](https://dash.yunohost.org/appci/app/helloworld) ![](https://ci-apps.yunohost.org/ci/badges/helloworld.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/helloworld.maintain.svg)  
[![Installer Hello World avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=helloworld)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Hello World rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Une app simple et bidon pour illustrer comme le packaging d'app de YunoHost fonctionne

**Version incluse :** 0.1~ynh1



## Documentations et ressources

* Site officiel de l'app : https://en.wikipedia.org/wiki/%22Hello,_World!%22_program
* Documentation YunoHost pour cette app : https://yunohost.org/app_helloworld
* Signaler un bug : https://github.com/YunoHost-Apps/helloworld_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/helloworld_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/helloworld_ynh/tree/testing --debug
ou
sudo yunohost app upgrade helloworld -u https://github.com/YunoHost-Apps/helloworld_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps