<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# DumbWhois untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/dumbwhois)](https://ci-apps.yunohost.org/ci/apps/dumbwhois/)
![Status kerja](https://apps.yunohost.org/badge/state/dumbwhois)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/dumbwhois)

[![Pasang DumbWhois dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbwhois)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang DumbWhois secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

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


**Versi terkirim:** 1.0.0~ynh1

## Tangkapan Layar

![Tangkapan Layar pada DumbWhois](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://www.dumbware.io/>
- Depot kode aplikasi hulu: <https://github.com/DumbWareio/DumbWhois>
- Gudang YunoHost: <https://apps.yunohost.org/app/dumbwhois>
- Laporkan bug: <https://github.com/YunoHost-Apps/dumbwhois_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing --debug
atau
sudo yunohost app upgrade dumbwhois -u https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
