# Dokuwiki pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/dokuwiki.svg)](https://dash.yunohost.org/appci/app/dokuwiki) ![](https://ci-apps.yunohost.org/ci/badges/dokuwiki.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/dokuwiki.maintain.svg)  
[![Installer Dokuwiki avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dokuwiki)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Dokuwiki rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

DokuWiki est un logiciel wiki Open Source simple à utiliser et très polyvalent qui ne nécessite pas de base de données. Il est apprécié par les utilisateurs pour sa syntaxe propre et lisible. La facilité de maintenance, de sauvegarde et d'intégration en fait un favori d'administrateur. Des contrôles d'accès et des connecteurs d'authentification intégrés rendent DokuWiki particulièrement utile dans le contexte de l'entreprise et le grand nombre de plugins apportés par sa communauté dynamique permettent un large éventail de cas d'utilisation au-delà d'un wiki traditionnel.

## Caractéristiques spécifiques YunoHost

* Fonctionne avec les utilisateurs YunoHost ainsi que le SSO - i.e. button de déconnexion
* Définit un utilisateur "administrateur" lors de l'installation
* Droits d'édition par défaut du wiki définis en lecture seule afin que les invités ne puissent éditer les pages. (Nécessaire surtout lorsque le wiki est public pour éviter le spam et le vandalisme. Peut être changé depuis la partie administration du wiki)
* Lors de la mise à jour, les plugins officiels sont également mis à jour. Nous vous recommandons toutefois de vérifier le bon fonctionnement des plugins dans le panneau d'administration après cette opération. Nous ne pouvons pas savoir si des plugins spéciaux posent problèmes...


**Version incluse :** 2020.07.29~ynh4

**Démo :** https://demo.yunohost.org/dokuwiki/doku.php?id=start&do=login&u=demo&p=demo

## Captures d'écran

![](./doc/screenshots/DokuWiki_Screenshot.png)

## Avertissements / informations importantes

## Limitations

* Impossible d'ajouter et d'utiliser les utilisateurs internes de DokuWiki, seulement ceux de YunoHost (travail nécessaire pour [authchained plugin](https://www.dokuwiki.org/plugin:authchained))

## Documentations et ressources

* Site officiel de l'app : https://www.dokuwiki.org
* Documentation officielle de l'admin : https://www.dokuwiki.org/manual
* Dépôt de code officiel de l'app : https://github.com/splitbrain/dokuwiki
* Documentation YunoHost pour cette app : https://yunohost.org/app_dokuwiki
* Signaler un bug : https://github.com/YunoHost-Apps/dokuwiki_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing --debug
ou
sudo yunohost app upgrade dokuwiki -u https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps