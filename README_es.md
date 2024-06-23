<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Dokuwiki para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/dokuwiki.svg)](https://dash.yunohost.org/appci/app/dokuwiki) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/dokuwiki.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/dokuwiki.maintain.svg)

[![Instalar Dokuwiki con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dokuwiki)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarDokuwiki rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

DokuWiki is a simple to use and highly versatile Open Source wiki software that doesn't require a database. It is loved by users for its clean and readable syntax. The ease of maintenance, backup and integration makes it an administrator's favorite. Built in access controls and authentication connectors make DokuWiki especially useful in the enterprise context and the large number of plugins contributed by its vibrant community allow for a broad range of use cases beyond a traditional wiki.

## YunoHost specific features

* Integrate with YunoHost users and SSO - i.e. logout button
* Allow one user to be the "administrator" (set at the installation)
* Default authorization is set as read only so guest people cannot edit pages. (Especially needed if wiki is public to avoid spam and defacing. Can be changed from admin panel)
* During the upgrade, official plugins are also upgraded. We recommend that you should check that they run properly in the administration panel after the upgrade. We cannot know if some plugins are broken...


**Versión actual:** 2024.02.06a~ynh1

**Demo:** <https://demo.yunohost.org/dokuwiki/doku.php?id=start&do=login&u=demo&p=demo>

## Capturas

![Captura de Dokuwiki](./doc/screenshots/DokuWiki_Screenshot.png)

## Documentaciones y recursos

- Sitio web oficial: <https://www.dokuwiki.org>
- Documentación administrador oficial: <https://www.dokuwiki.org/manual>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/dokuwiki/dokuwiki>
- Catálogo YunoHost: <https://apps.yunohost.org/app/dokuwiki>
- Reportar un error: <https://github.com/YunoHost-Apps/dokuwiki_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing --debug
o
sudo yunohost app upgrade dokuwiki -u https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
