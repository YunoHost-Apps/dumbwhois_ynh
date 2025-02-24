<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# DumbWhois para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/dumbwhois)](https://ci-apps.yunohost.org/ci/apps/dumbwhois/)
![Estado funcional](https://apps.yunohost.org/badge/state/dumbwhois)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/dumbwhois)

[![Instalar DumbWhois con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbwhois)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarDumbWhois rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

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


**Versión actual:** 1.0.0~ynh1

## Capturas

![Captura de DumbWhois](./doc/screenshots/screenshot.png)

## Documentaciones y recursos

- Sitio web oficial: <https://www.dumbware.io/>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/DumbWareio/DumbWhois>
- Catálogo YunoHost: <https://apps.yunohost.org/app/dumbwhois>
- Reportar un error: <https://github.com/YunoHost-Apps/dumbwhois_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing --debug
o
sudo yunohost app upgrade dumbwhois -u https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
