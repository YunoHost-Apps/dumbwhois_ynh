<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 DumbWhois

[![集成程度](https://apps.yunohost.org/badge/integration/dumbwhois)](https://ci-apps.yunohost.org/ci/apps/dumbwhois/)
![工作状态](https://apps.yunohost.org/badge/state/dumbwhois)
![维护状态](https://apps.yunohost.org/badge/maintained/dumbwhois)

[![使用 YunoHost 安装 DumbWhois](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbwhois)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 DumbWhois。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

A simple web application for looking up WHOIS, IP, and ASN information using free APIs. The application automatically detects the type of query and provides formatted results with a clean, modern UI that supports both light and dark modes.

### Features

- Automatic detection of query type (Domain, IP, or ASN)
- Direct WHOIS domain lookup with support for all TLDs
- IP geolocation with multiple fallback services
- ASN (Autonomous System Number) details
- Clean and modern UI with dark mode support
- Responsive design for mobile and desktop
- No authentication required
- Environment variable configuration
- Automatic service fallback for IP lookups
- Full IPv6 support
- Clear source attribution for all lookups
- DNS resolution for domain IP addresses
- URL query parameter support for direct lookups


**分发版本：** 1.0.0~ynh1

## 截图

![DumbWhois 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://www.dumbware.io/>
- 上游应用代码库： <https://github.com/DumbWareio/DumbWhois>
- YunoHost 商店： <https://apps.yunohost.org/app/dumbwhois>
- 报告 bug： <https://github.com/YunoHost-Apps/dumbwhois_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing --debug
或
sudo yunohost app upgrade dumbwhois -u https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
