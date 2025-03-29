<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Gull dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/gull)](https://ci-apps.yunohost.org/ci/apps/gull/)
![Status działania](https://apps.yunohost.org/badge/state/gull)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/gull)

[![Zainstaluj Gull z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gull)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Gull na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

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


**Dostarczona wersja:** 1.0~ynh1

**Demo:** <https://s.aeoly.us/>

## Zrzuty ekranu

![Zrzut ekranu z Gull](./doc/screenshots/screenshot.png)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://s.aeoly.us/>
- Repozytorium z kodem źródłowym: <https://github.com/aeolyus/gull>
- Sklep YunoHost: <https://apps.yunohost.org/app/gull>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/gull_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/gull_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gull_ynh/tree/testing --debug
lub
sudo yunohost app upgrade gull -u https://github.com/YunoHost-Apps/gull_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
