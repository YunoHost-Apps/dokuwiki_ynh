<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Dokuwiki voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/dokuwiki)](https://ci-apps.yunohost.org/ci/apps/dokuwiki/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/dokuwiki)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/dokuwiki)

[![Dokuwiki met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dokuwiki)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Dokuwiki snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

DokuWiki is a simple to use and highly versatile Open Source wiki software that doesn't require a database. It is loved by users for its clean and readable syntax. The ease of maintenance, backup and integration makes it an administrator's favorite. Built in access controls and authentication connectors make DokuWiki especially useful in the enterprise context and the large number of plugins contributed by its vibrant community allow for a broad range of use cases beyond a traditional wiki.

## YunoHost specific features

* Integrate with YunoHost users and SSO - i.e. logout button
* Allow one user to be the "administrator" (set at the installation)
* Default authorization is set as read only so guest people cannot edit pages. (Especially needed if wiki is public to avoid spam and defacing. Can be changed from admin panel)
* During the upgrade, official plugins are also upgraded. We recommend that you should check that they run properly in the administration panel after the upgrade. We cannot know if some plugins are broken...


**Geleverde versie:** 2024.02.06a~ynh1

**Demo:** <https://demo.yunohost.org/dokuwiki/doku.php?id=start&do=login&u=demo&p=demo>

## Schermafdrukken

![Schermafdrukken van Dokuwiki](./doc/screenshots/DokuWiki_Screenshot.png)

## Documentatie en bronnen

- Officiele website van de app: <https://www.dokuwiki.org>
- Officiele beheerdersdocumentatie: <https://www.dokuwiki.org/manual>
- Upstream app codedepot: <https://github.com/dokuwiki/dokuwiki>
- YunoHost-store: <https://apps.yunohost.org/app/dokuwiki>
- Meld een bug: <https://github.com/YunoHost-Apps/dokuwiki_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing --debug
of
sudo yunohost app upgrade dokuwiki -u https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
