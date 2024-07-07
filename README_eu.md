<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Easy!Appointments YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/easyappointments.svg)](https://ci-apps.yunohost.org/ci/apps/easyappointments/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/easyappointments.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/easyappointments.maintain.svg)

[![Instalatu Easy!Appointments YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=easyappointments)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Easy!Appointments YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

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


**Paketatutako bertsioa:** 1.5.0~ynh1

**Demoa:** <https://demo.easyappointments.org/>

## Pantaila-argazkiak

![Easy!Appointments(r)en pantaila-argazkia](./doc/screenshots/screenshots.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://easyappointments.org/>
- Administratzaileen dokumentazio ofiziala: <https://easyappointments.org/docs.html#1.4.3/readme.md>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/alextselegidis/easyappointments>
- YunoHost Denda: <https://apps.yunohost.org/app/easyappointments>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/easyappointments_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/easyappointments_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/easyappointments_ynh/tree/testing --debug
edo
sudo yunohost app upgrade easyappointments -u https://github.com/YunoHost-Apps/easyappointments_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
