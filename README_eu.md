<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# DumbWhois YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/dumbwhois)](https://ci-apps.yunohost.org/ci/apps/dumbwhois/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/dumbwhois)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/dumbwhois)

[![Instalatu DumbWhois YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbwhois)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek DumbWhois YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

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


**Paketatutako bertsioa:** 1.0.0~ynh1

## Pantaila-argazkiak

![DumbWhois(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://www.dumbware.io/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/DumbWareio/DumbWhois>
- YunoHost Denda: <https://apps.yunohost.org/app/dumbwhois>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/dumbwhois_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing --debug
edo
sudo yunohost app upgrade dumbwhois -u https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
