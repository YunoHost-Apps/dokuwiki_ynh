<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Dokuwiki untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/dokuwiki)](https://ci-apps.yunohost.org/ci/apps/dokuwiki/)
![Status kerja](https://apps.yunohost.org/badge/state/dokuwiki)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/dokuwiki)

[![Pasang Dokuwiki dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dokuwiki)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Dokuwiki secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

DokuWiki is a simple to use and highly versatile Open Source wiki software that doesn't require a database. It is loved by users for its clean and readable syntax. The ease of maintenance, backup and integration makes it an administrator's favorite. Built in access controls and authentication connectors make DokuWiki especially useful in the enterprise context and the large number of plugins contributed by its vibrant community allow for a broad range of use cases beyond a traditional wiki.

## YunoHost specific features

* Integrate with YunoHost users and SSO - i.e. logout button
* Allow one user to be the "administrator" (set at the installation)
* Default authorization is set as read only so guest people cannot edit pages. (Especially needed if wiki is public to avoid spam and defacing. Can be changed from admin panel)
* During the upgrade, official plugins are also upgraded. We recommend that you should check that they run properly in the administration panel after the upgrade. We cannot know if some plugins are broken...


**Versi terkirim:** 2024.02.06a~ynh1

**Demo:** <https://demo.yunohost.org/dokuwiki/doku.php?id=start&do=login&u=demo&p=demo>

## Tangkapan Layar

![Tangkapan Layar pada Dokuwiki](./doc/screenshots/DokuWiki_Screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://www.dokuwiki.org>
- Dokumentasi admin resmi: <https://www.dokuwiki.org/manual>
- Depot kode aplikasi hulu: <https://github.com/dokuwiki/dokuwiki>
- Gudang YunoHost: <https://apps.yunohost.org/app/dokuwiki>
- Laporkan bug: <https://github.com/YunoHost-Apps/dokuwiki_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing --debug
atau
sudo yunohost app upgrade dokuwiki -u https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
