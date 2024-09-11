<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Easy!Appointments voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/easyappointments.svg)](https://ci-apps.yunohost.org/ci/apps/easyappointments/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/easyappointments.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/easyappointments.maintain.svg)

[![Easy!Appointments met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=easyappointments)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Easy!Appointments snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Easy!Appointments is a highly customizable web application that allows customers to book appointments with you via a sophisticated web interface. Moreover, it provides the ability to sync your data with Google Calendar so you can use them with other services. It is an open source project that you can download and install even for commercial use. Easy!Appointments will run smoothly with your existing website as it can be installed in a single folder of the server and of course share an existing database.

### Features
The application is designed to be flexible enough so that it can handle any enterprise work flow.

- Customers and appointments management.
- Services and providers organization.
- Working plan and booking rules.
- Google Calendar synchronization.
- Email notifications system.
- Self hosted installation.
- Translated user interface.


**Geleverde versie:** 1.5.0~ynh3

**Demo:** <https://demo.easyappointments.org/>

## Schermafdrukken

![Schermafdrukken van Easy!Appointments](./doc/screenshots/screenshots.png)

## Documentatie en bronnen

- Officiele website van de app: <https://easyappointments.org/>
- Officiele beheerdersdocumentatie: <https://easyappointments.org/docs.html#1.4.3/readme.md>
- Upstream app codedepot: <https://github.com/alextselegidis/easyappointments>
- YunoHost-store: <https://apps.yunohost.org/app/easyappointments>
- Meld een bug: <https://github.com/YunoHost-Apps/easyappointments_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/easyappointments_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/easyappointments_ynh/tree/testing --debug
of
sudo yunohost app upgrade easyappointments -u https://github.com/YunoHost-Apps/easyappointments_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
