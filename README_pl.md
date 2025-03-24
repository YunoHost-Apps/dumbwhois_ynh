<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# DumbWhois dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/dumbwhois)](https://ci-apps.yunohost.org/ci/apps/dumbwhois/)
![Status działania](https://apps.yunohost.org/badge/state/dumbwhois)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/dumbwhois)

[![Zainstaluj DumbWhois z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbwhois)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację DumbWhois na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

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


**Dostarczona wersja:** 2025.03.23~ynh1

## Zrzuty ekranu

![Zrzut ekranu z DumbWhois](./doc/screenshots/screenshot.png)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://www.dumbware.io/>
- Repozytorium z kodem źródłowym: <https://github.com/DumbWareio/DumbWhois>
- Sklep YunoHost: <https://apps.yunohost.org/app/dumbwhois>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/dumbwhois_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing --debug
lub
sudo yunohost app upgrade dumbwhois -u https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
