<!--
N.B.: Aquest README ha estat generat automàticament per <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NO s'ha de modificar manualment.
-->

# DumbWhois per YunoHost

[![Nivell d'integració](https://apps.yunohost.org/badge/integration/dumbwhois)](https://ci-apps.yunohost.org/ci/apps/dumbwhois/)
![Estat de funcionament](https://apps.yunohost.org/badge/state/dumbwhois)
![Estat de manteniment](https://apps.yunohost.org/badge/maintained/dumbwhois)

[![Instal·la DumbWhois amb YunoHosth](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbwhois)

*[Llegeix aquest README en altres idiomes.](./ALL_README.md)*

> *Aquest paquet et permet instal·lar DumbWhois de forma ràpida i senzilla en un servidor YunoHost.*  
> *Si no tens YunoHost, consulta [la guia](https://yunohost.org/install) per saber com instal·lar-lo.*

## Visió general

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


**Versió inclosa:** 2025.03.24~ynh1

## Captures de pantalla

![Captures de pantalla de DumbWhois](./doc/screenshots/screenshot.png)

## Documentació i recursos

- Lloc web oficial de l'aplicació: <https://www.dumbware.io/>
- Repositori oficial del codi de l'aplicació: <https://github.com/DumbWareio/DumbWhois>
- Botiga YunoHost: <https://apps.yunohost.org/app/dumbwhois>
- Reportar un error: <https://github.com/YunoHost-Apps/dumbwhois_ynh/issues>

## Informació per a desenvolupadors

Envieu les pull request a la [branca `testing`](https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing).

Per provar la branca `testing`, procedir com descrit a continuació:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing --debug
o
sudo yunohost app upgrade dumbwhois -u https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing --debug
```

**Més informació sobre l'empaquetatge d'aplicacions:** <https://yunohost.org/packaging_apps>
