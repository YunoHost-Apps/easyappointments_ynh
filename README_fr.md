<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Easy!Appointments pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/easyappointments.svg)](https://ci-apps.yunohost.org/ci/apps/easyappointments/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/easyappointments.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/easyappointments.maintain.svg)

[![Installer Easy!Appointments avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=easyappointments)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Easy!Appointments rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Easy!Appointments est une application Web hautement personnalisable qui permet aux clients de prendre rendez-vous avec vous via une interface Web sophistiquée. De plus, il offre la possibilité de synchroniser vos données avec Google Agenda afin que vous puissiez les utiliser avec d'autres services. Il s'agit d'un projet open source que vous pouvez télécharger et installer même pour un usage commercial. Easy!Appointments fonctionnera sans problème avec votre site Web existant car il peut être installé dans un seul dossier du serveur et bien sûr partager une base de données existante.

### Caractéristiques

- Gestion des clients et des rendez-vous.
- Organisation des services et prestataires.
- Plan de travail et règles de réservation.
- Synchronisation de Google Agenda.
- Système de notifications par e-mail.
- Installation auto-hébergée.
- Interface utilisateur traduite.


**Version incluse :** 1.5.0~ynh1

**Démo :** <https://demo.easyappointments.org/>

## Captures d’écran

![Capture d’écran de Easy!Appointments](./doc/screenshots/screenshots.png)

## Documentations et ressources

- Site officiel de l’app : <https://easyappointments.org/>
- Documentation officielle de l’admin : <https://easyappointments.org/docs.html#1.4.3/readme.md>
- Dépôt de code officiel de l’app : <https://github.com/alextselegidis/easyappointments>
- YunoHost Store : <https://apps.yunohost.org/app/easyappointments>
- Signaler un bug : <https://github.com/YunoHost-Apps/easyappointments_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/easyappointments_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/easyappointments_ynh/tree/testing --debug
ou
sudo yunohost app upgrade easyappointments -u https://github.com/YunoHost-Apps/easyappointments_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
