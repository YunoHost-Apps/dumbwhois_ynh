<!--
N.B.: Diese README wurde automatisch von <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> generiert.
Sie darf NICHT von Hand bearbeitet werden.
-->

# DumbWhois für YunoHost

[![Integrations-Level](https://apps.yunohost.org/badge/integration/dumbwhois)](https://ci-apps.yunohost.org/ci/apps/dumbwhois/)
![Funktionsstatus](https://apps.yunohost.org/badge/state/dumbwhois)
![Wartungsstatus](https://apps.yunohost.org/badge/maintained/dumbwhois)

[![DumbWhois mit YunoHost installieren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbwhois)

*[Dieses README in anderen Sprachen lesen.](./ALL_README.md)*

> *Mit diesem Paket können Sie DumbWhois schnell und einfach auf einem YunoHost-Server installieren.*  
> *Wenn Sie YunoHost nicht haben, lesen Sie bitte [die Anleitung](https://yunohost.org/install), um zu erfahren, wie Sie es installieren.*

## Übersicht

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


**Ausgelieferte Version:** 2025.03.24~ynh1

## Bildschirmfotos

![Bildschirmfotos von DumbWhois](./doc/screenshots/screenshot.png)

## Dokumentation und Ressourcen

- Offizielle Website der App: <https://www.dumbware.io/>
- Upstream App Repository: <https://github.com/DumbWareio/DumbWhois>
- YunoHost-Shop: <https://apps.yunohost.org/app/dumbwhois>
- Einen Fehler melden: <https://github.com/YunoHost-Apps/dumbwhois_ynh/issues>

## Entwicklerinformationen

Bitte senden Sie Ihren Pull-Request an den [`testing` branch](https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing).

Um den `testing` Branch auszuprobieren, gehen Sie bitte wie folgt vor:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing --debug
oder
sudo yunohost app upgrade dumbwhois -u https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing --debug
```

**Weitere Informationen zur App-Paketierung:** <https://yunohost.org/packaging_apps>
