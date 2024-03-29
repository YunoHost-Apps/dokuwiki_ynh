<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Dokuwiki per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/dokuwiki.svg)](https://dash.yunohost.org/appci/app/dokuwiki) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/dokuwiki.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/dokuwiki.maintain.svg)

[![Installa Dokuwiki con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dokuwiki)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Dokuwiki su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

DokuWiki is a simple to use and highly versatile Open Source wiki software that doesn't require a database. It is loved by users for its clean and readable syntax. The ease of maintenance, backup and integration makes it an administrator's favorite. Built in access controls and authentication connectors make DokuWiki especially useful in the enterprise context and the large number of plugins contributed by its vibrant community allow for a broad range of use cases beyond a traditional wiki.

## YunoHost specific features

* Integrate with YunoHost users and SSO - i.e. logout button
* Allow one user to be the "administrator" (set at the installation)
* Default authorization is set as read only so guest people cannot edit pages. (Especially needed if wiki is public to avoid spam and defacing. Can be changed from admin panel)
* During the upgrade, official plugins are also upgraded. We recommend that you should check that they run properly in the administration panel after the upgrade. We cannot know if some plugins are broken...


**Versione pubblicata:** 2024.02.06a~ynh1

**Prova:** <https://demo.yunohost.org/dokuwiki/doku.php?id=start&do=login&u=demo&p=demo>

## Screenshot

![Screenshot di Dokuwiki](./doc/screenshots/DokuWiki_Screenshot.png)

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://www.dokuwiki.org>
- Documentazione ufficiale per gli amministratori: <https://www.dokuwiki.org/manual>
- Repository upstream del codice dell’app: <https://github.com/dokuwiki/dokuwiki>
- Store di YunoHost: <https://apps.yunohost.org/app/dokuwiki>
- Segnala un problema: <https://github.com/YunoHost-Apps/dokuwiki_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing --debug
o
sudo yunohost app upgrade dokuwiki -u https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
