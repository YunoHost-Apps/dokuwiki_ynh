<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Dokuwiki pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/dokuwiki)](https://ci-apps.yunohost.org/ci/apps/dokuwiki/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/dokuwiki)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/dokuwiki)

[![Installer Dokuwiki avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dokuwiki)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Dokuwiki rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

DokuWiki est un logiciel wiki Open Source simple à utiliser et très polyvalent qui ne nécessite pas de base de données. Il est apprécié par les utilisateurs pour sa syntaxe propre et lisible. La facilité de maintenance, de sauvegarde et d'intégration en fait un favori d'administrateur. Des contrôles d'accès et des connecteurs d'authentification intégrés rendent DokuWiki particulièrement utile dans le contexte de l'entreprise et le grand nombre de plugins apportés par sa communauté dynamique permettent un large éventail de cas d'utilisation au-delà d'un wiki traditionnel.

## Caractéristiques spécifiques YunoHost

* Fonctionne avec les utilisateurs YunoHost ainsi que le SSO - i.e. button de déconnexion
* Définit un utilisateur "administrateur" lors de l'installation
* Droits d'édition par défaut du wiki définis en lecture seule afin que les invités ne puissent éditer les pages. (Nécessaire surtout lorsque le wiki est public pour éviter le spam et le vandalisme. Peut être changé depuis la partie administration du wiki)
* Lors de la mise à jour, les plugins officiels sont également mis à jour. Nous vous recommandons toutefois de vérifier le bon fonctionnement des plugins dans le panneau d'administration après cette opération. Nous ne pouvons pas savoir si des plugins spéciaux posent problèmes...


**Version incluse :** 2024.02.06a~ynh1

**Démo :** <https://demo.yunohost.org/dokuwiki/doku.php?id=start&do=login&u=demo&p=demo>

## Captures d’écran

![Capture d’écran de Dokuwiki](./doc/screenshots/DokuWiki_Screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://www.dokuwiki.org>
- Documentation officielle de l’admin : <https://www.dokuwiki.org/manual>
- Dépôt de code officiel de l’app : <https://github.com/dokuwiki/dokuwiki>
- YunoHost Store : <https://apps.yunohost.org/app/dokuwiki>
- Signaler un bug : <https://github.com/YunoHost-Apps/dokuwiki_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing --debug
ou
sudo yunohost app upgrade dokuwiki -u https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
