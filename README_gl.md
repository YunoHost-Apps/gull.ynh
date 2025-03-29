<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Gull para YunoHost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/gull)](https://ci-apps.yunohost.org/ci/apps/gull/)
![Estado de funcionamento](https://apps.yunohost.org/badge/state/gull)
![Estado de mantemento](https://apps.yunohost.org/badge/maintained/gull)

[![Instalar Gull con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gull)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Gull de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

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


**Versión proporcionada:** 1.0~ynh1

**Demo:** <https://s.aeoly.us/>

## Capturas de pantalla

![Captura de pantalla de Gull](./doc/screenshots/screenshot.png)

## Documentación e recursos

- Web oficial da app: <https://s.aeoly.us/>
- Repositorio de orixe do código: <https://github.com/aeolyus/gull>
- Tenda YunoHost: <https://apps.yunohost.org/app/gull>
- Informar dun problema: <https://github.com/YunoHost-Apps/gull_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/gull_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gull_ynh/tree/testing --debug
ou
sudo yunohost app upgrade gull -u https://github.com/YunoHost-Apps/gull_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
