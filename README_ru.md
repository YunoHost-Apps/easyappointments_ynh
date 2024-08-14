<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Easy!Appointments для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/easyappointments.svg)](https://ci-apps.yunohost.org/ci/apps/easyappointments/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/easyappointments.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/easyappointments.maintain.svg)

[![Установите Easy!Appointments с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=easyappointments)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Easy!Appointments быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

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


**Поставляемая версия:** 1.5.0~ynh1

**Демо-версия:** <https://demo.easyappointments.org/>

## Снимки экрана

![Снимок экрана Easy!Appointments](./doc/screenshots/screenshots.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://easyappointments.org/>
- Официальная документация администратора: <https://easyappointments.org/docs.html#1.4.3/readme.md>
- Репозиторий кода главной ветки приложения: <https://github.com/alextselegidis/easyappointments>
- Магазин YunoHost: <https://apps.yunohost.org/app/easyappointments>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/easyappointments_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/easyappointments_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/easyappointments_ynh/tree/testing --debug
или
sudo yunohost app upgrade easyappointments -u https://github.com/YunoHost-Apps/easyappointments_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
