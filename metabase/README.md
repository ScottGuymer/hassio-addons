# Home Assistant Add-on: Metabase

Meet the easy, open source way for everyone to ask questions and learn from data. See for more information https://www.metabase.com.

![metabase-shield] ![addon-shield] ![aarch64-shield] ![amd64-shield] [![Community Forum][forum-shield]][forum]

![Metabase](https://raw.githubusercontent.com/sanderdw/hassio-addons/master/images/metabase.png)

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg?style=flat-square
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg?style=flat-square

[metabase-shield]: https://img.shields.io/badge/Metabase%20Version-%200.40.0-purple.svg?style=flat-square
[addon-shield]: https://img.shields.io/badge/Addon%20Version-%200.3.0-purple.svg?style=flat-square
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg?style=flat-square
[forum]: https://community.home-assistant.io/t/metabase-add-on-for-home-assistant/286413
## Configure the repository

See config instructions here: https://github.com/sanderdw/hassio-addons

## Configure the add-on

1. Install PostgresDB (TimescaleDB) by Expaso: https://community.home-assistant.io/t/home-assistant-add-on-postgresql-timescaledb/198176.
2. Add the "metabase" db as an exta database entry in the Configuration tab.
3. Start TimescaleDB addon to initialize.
4. Install this addon.
5. Configure settings in the "Configuration" tab if defaults are changed by you.
6. Start Metabase addon.
7. Go to http://yourhomeassistant:7778 (wait untill add-on is initialized) - Note: Ingress not working yet.
8. Walkthrough the Metabase setup.
12. _Optional:_ Add the Home Assistant PostgreSQL DB (You need to have the recorder configured: https://www.home-assistant.io/integrations/recorder/)
12. _Optional:_ Add the DSMR Reader PostgreSQL DB
9. Explore!