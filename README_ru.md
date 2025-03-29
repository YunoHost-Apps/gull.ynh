<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Gull для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/gull)](https://ci-apps.yunohost.org/ci/apps/gull/)
![Состояние работы](https://apps.yunohost.org/badge/state/gull)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/gull)

[![Установите Gull с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gull)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Gull быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Galène is a videoconference server (an “SFU”) that is easy to deploy and that requires moderate server resources. It was originally designed for lectures and conferences (where a single speaker streams audio and video to hundreds or thousands of users), but later evolved to be useful for student practicals (where users are divided into many small groups), and meetings (where a dozen users interact with each other).

### Client features:

- multiparty audio and video
- text chat
- reasonably good support for mobile (Android and iPhone/iPad)
- screen and window sharing, including sharing multiple windows simultaneously (not on mobile)
- streaming video and audio from disk
- activity detection
- LDAP support
- invite user
- Command-line client for Galene file transfer


**Поставляемая версия:** 1.0~ynh1

**Демо-версия:** <https://s.aeoly.us/>

## Снимки экрана

![Снимок экрана Gull](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://s.aeoly.us/>
- Репозиторий кода главной ветки приложения: <https://github.com/aeolyus/gull>
- Магазин YunoHost: <https://apps.yunohost.org/app/gull>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/gull_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/gull_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gull_ynh/tree/testing --debug
или
sudo yunohost app upgrade gull -u https://github.com/YunoHost-Apps/gull_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
