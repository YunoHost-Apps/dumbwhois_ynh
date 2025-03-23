<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# DumbWhois pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/dumbwhois)](https://ci-apps.yunohost.org/ci/apps/dumbwhois/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/dumbwhois)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/dumbwhois)

[![Installer DumbWhois avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbwhois)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer DumbWhois rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Une application web simple pour rechercher des informations WHOIS, IP et ASN en utilisant des APIs libres. L'application détecte automatiquement le type de requête et fournit des résultats formatés avec une interface utilisateur propre et moderne qui prend en charge les modes clair et foncé.

### Caractéristiques

- Détection automatique du type de requête (domaine, IP ou ASN)
- Recherche directe de domaine WHOIS avec prise en charge de tous les TLDs
- Géolocalisation IP avec plusieurs services de repli
- Détails de l'ASN (numéro de système autonome)
- Interface utilisateur propre et moderne avec prise en charge du mode sombre
- Conception réactive pour les mobiles et les ordinateurs de bureau
- Pas d'authentification requise
- Configuration des variables d'environnement
- Service de repli automatique pour les recherches d'adresses IP
- Prise en charge complète de l'IPv6
- Attribution claire de la source pour toutes les recherches
- Résolution DNS pour les adresses IP des domaines
- Prise en charge des paramètres de requête d'URL pour les recherches directes
    

**Version incluse :** 2025.03.23~ynh1

## Captures d’écran

![Capture d’écran de DumbWhois](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://www.dumbware.io/>
- Dépôt de code officiel de l’app : <https://github.com/DumbWareio/DumbWhois>
- YunoHost Store : <https://apps.yunohost.org/app/dumbwhois>
- Signaler un bug : <https://github.com/YunoHost-Apps/dumbwhois_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing --debug
ou
sudo yunohost app upgrade dumbwhois -u https://github.com/YunoHost-Apps/dumbwhois_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
