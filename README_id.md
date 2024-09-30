<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Easy!Appointments untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/easyappointments.svg)](https://ci-apps.yunohost.org/ci/apps/easyappointments/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/easyappointments.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/easyappointments.maintain.svg)

[![Pasang Easy!Appointments dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=easyappointments)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Easy!Appointments secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

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


**Versi terkirim:** 1.5.0~ynh3

**Demo:** <https://demo.easyappointments.org/>

## Tangkapan Layar

![Tangkapan Layar pada Easy!Appointments](./doc/screenshots/screenshots.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://easyappointments.org/>
- Dokumentasi admin resmi: <https://easyappointments.org/docs.html#1.5.0/readme.md>
- Depot kode aplikasi hulu: <https://github.com/alextselegidis/easyappointments>
- Gudang YunoHost: <https://apps.yunohost.org/app/easyappointments>
- Laporkan bug: <https://github.com/YunoHost-Apps/easyappointments_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/easyappointments_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/easyappointments_ynh/tree/testing --debug
atau
sudo yunohost app upgrade easyappointments -u https://github.com/YunoHost-Apps/easyappointments_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
