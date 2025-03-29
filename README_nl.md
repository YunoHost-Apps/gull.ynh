<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Gull voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/gull)](https://ci-apps.yunohost.org/ci/apps/gull/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/gull)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/gull)

[![Gull met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gull)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Gull snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

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


**Geleverde versie:** 1.0~ynh1

**Demo:** <https://s.aeoly.us/>

## Schermafdrukken

![Schermafdrukken van Gull](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Officiele website van de app: <https://s.aeoly.us/>
- Upstream app codedepot: <https://github.com/aeolyus/gull>
- YunoHost-store: <https://apps.yunohost.org/app/gull>
- Meld een bug: <https://github.com/YunoHost-Apps/gull_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/gull_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gull_ynh/tree/testing --debug
of
sudo yunohost app upgrade gull -u https://github.com/YunoHost-Apps/gull_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
