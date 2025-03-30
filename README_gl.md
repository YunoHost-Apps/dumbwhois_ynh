<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# DumbWhois para YunoHost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/dumbwhois)](https://ci-apps.yunohost.org/ci/apps/dumbwhois/)
![Estado de funcionamento](https://apps.yunohost.org/badge/state/dumbwhois)
![Estado de mantemento](https://apps.yunohost.org/badge/maintained/dumbwhois)

[![Instalar DumbWhois con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbwhois)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar DumbWhois de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

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


**Versión proporcionada:** 2025.03.24~ynh1

## Capturas de pantalla

![Captura de pantalla de DumbWhois](./doc/screenshots/screenshot.png)

## Documentación e recursos

- Web oficial da app: <https://www.dumbware.io/>
- Repositorio de orixe do código: <https://github.com/DumbWareio/DumbWhois>
- Tenda YunoHost: <https://apps.yunohost.org/app/dumbwhois>
- Informar dun problema: <https://github.com/YunoHost-Apps/dumbwhois_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing --debug
ou
sudo yunohost app upgrade dumbwhois -u https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
