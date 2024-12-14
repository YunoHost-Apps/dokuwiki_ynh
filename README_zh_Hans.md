<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Dokuwiki

[![集成程度](https://apps.yunohost.org/badge/integration/dokuwiki)](https://ci-apps.yunohost.org/ci/apps/dokuwiki/)
![工作状态](https://apps.yunohost.org/badge/state/dokuwiki)
![维护状态](https://apps.yunohost.org/badge/maintained/dokuwiki)

[![使用 YunoHost 安装 Dokuwiki](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dokuwiki)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Dokuwiki。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

DokuWiki is a simple to use and highly versatile Open Source wiki software that doesn't require a database. It is loved by users for its clean and readable syntax. The ease of maintenance, backup and integration makes it an administrator's favorite. Built in access controls and authentication connectors make DokuWiki especially useful in the enterprise context and the large number of plugins contributed by its vibrant community allow for a broad range of use cases beyond a traditional wiki.

## YunoHost specific features

* Integrate with YunoHost users and SSO - i.e. logout button
* Allow one user to be the "administrator" (set at the installation)
* Default authorization is set as read only so guest people cannot edit pages. (Especially needed if wiki is public to avoid spam and defacing. Can be changed from admin panel)
* During the upgrade, official plugins are also upgraded. We recommend that you should check that they run properly in the administration panel after the upgrade. We cannot know if some plugins are broken...


**分发版本：** 2024.02.06a~ynh1

**演示：** <https://demo.yunohost.org/dokuwiki/doku.php?id=start&do=login&u=demo&p=demo>

## 截图

![Dokuwiki 的截图](./doc/screenshots/DokuWiki_Screenshot.png)

## 文档与资源

- 官方应用网站： <https://www.dokuwiki.org>
- 官方管理文档： <https://www.dokuwiki.org/manual>
- 上游应用代码库： <https://github.com/dokuwiki/dokuwiki>
- YunoHost 商店： <https://apps.yunohost.org/app/dokuwiki>
- 报告 bug： <https://github.com/YunoHost-Apps/dokuwiki_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing --debug
或
sudo yunohost app upgrade dokuwiki -u https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
