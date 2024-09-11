<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Easy!Appointments

[![集成程度](https://dash.yunohost.org/integration/easyappointments.svg)](https://ci-apps.yunohost.org/ci/apps/easyappointments/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/easyappointments.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/easyappointments.maintain.svg)

[![使用 YunoHost 安装 Easy!Appointments](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=easyappointments)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Easy!Appointments。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

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


**分发版本：** 1.5.0~ynh3

**演示：** <https://demo.easyappointments.org/>

## 截图

![Easy!Appointments 的截图](./doc/screenshots/screenshots.png)

## 文档与资源

- 官方应用网站： <https://easyappointments.org/>
- 官方管理文档： <https://easyappointments.org/docs.html#1.4.3/readme.md>
- 上游应用代码库： <https://github.com/alextselegidis/easyappointments>
- YunoHost 商店： <https://apps.yunohost.org/app/easyappointments>
- 报告 bug： <https://github.com/YunoHost-Apps/easyappointments_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/easyappointments_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/easyappointments_ynh/tree/testing --debug
或
sudo yunohost app upgrade easyappointments -u https://github.com/YunoHost-Apps/easyappointments_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
