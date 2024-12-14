<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Dokuwiki dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/dokuwiki)](https://ci-apps.yunohost.org/ci/apps/dokuwiki/)
![Status działania](https://apps.yunohost.org/badge/state/dokuwiki)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/dokuwiki)

[![Zainstaluj Dokuwiki z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dokuwiki)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Dokuwiki na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

DokuWiki is a simple to use and highly versatile Open Source wiki software that doesn't require a database. It is loved by users for its clean and readable syntax. The ease of maintenance, backup and integration makes it an administrator's favorite. Built in access controls and authentication connectors make DokuWiki especially useful in the enterprise context and the large number of plugins contributed by its vibrant community allow for a broad range of use cases beyond a traditional wiki.

## YunoHost specific features

* Integrate with YunoHost users and SSO - i.e. logout button
* Allow one user to be the "administrator" (set at the installation)
* Default authorization is set as read only so guest people cannot edit pages. (Especially needed if wiki is public to avoid spam and defacing. Can be changed from admin panel)
* During the upgrade, official plugins are also upgraded. We recommend that you should check that they run properly in the administration panel after the upgrade. We cannot know if some plugins are broken...


**Dostarczona wersja:** 2024.02.06a~ynh1

**Demo:** <https://demo.yunohost.org/dokuwiki/doku.php?id=start&do=login&u=demo&p=demo>

## Zrzuty ekranu

![Zrzut ekranu z Dokuwiki](./doc/screenshots/DokuWiki_Screenshot.png)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://www.dokuwiki.org>
- Oficjalna dokumentacja dla administratora: <https://www.dokuwiki.org/manual>
- Repozytorium z kodem źródłowym: <https://github.com/dokuwiki/dokuwiki>
- Sklep YunoHost: <https://apps.yunohost.org/app/dokuwiki>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/dokuwiki_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing --debug
lub
sudo yunohost app upgrade dokuwiki -u https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
