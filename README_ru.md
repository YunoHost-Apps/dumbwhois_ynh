<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# DumbWhois для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/dumbwhois)](https://ci-apps.yunohost.org/ci/apps/dumbwhois/)
![Состояние работы](https://apps.yunohost.org/badge/state/dumbwhois)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/dumbwhois)

[![Установите DumbWhois с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbwhois)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить DumbWhois быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

A simple web application for looking up WHOIS, IP, and ASN information using free APIs. The application automatically detects the type of query and provides formatted results with a clean, modern UI that supports both light and dark modes.

### Features

    🔍 Automatic detection of query type (Domain, IP, or ASN)
    🌐 Direct WHOIS domain lookup with support for all TLDs
    🌍 IP geolocation with multiple fallback services
    🔢 ASN (Autonomous System Number) details
    🎨 Clean and modern UI with dark mode support
    📱 Responsive design for mobile and desktop
    🚫 No authentication required
    ⚙️ Environment variable configuration
    🔄 Automatic service fallback for IP lookups
    🌐 Full IPv6 support
    📋 Clear source attribution for all lookups
    🔍 DNS resolution for domain IP addresses
    🔗 URL query parameter support for direct lookups


**Поставляемая версия:** 1.0.0~ynh1

## Снимки экрана

![Снимок экрана DumbWhois](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://www.dumbware.io/>
- Репозиторий кода главной ветки приложения: <https://github.com/DumbWareio/DumbWhois>
- Магазин YunoHost: <https://apps.yunohost.org/app/dumbwhois>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/dumbwhois_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing --debug
или
sudo yunohost app upgrade dumbwhois -u https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
