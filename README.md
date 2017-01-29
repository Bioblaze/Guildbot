# Guildbot - A Discord bot for Gaming Guilds & Communities

> Become a Patreon! [Donate](https://www.patreon.com/BioblazePayne)


                      ▄▄ • ▄• ▄▌▪  ▄▄▌  ·▄▄▄▄  ▄▄▄▄·       ▄▄▄▄▄
                      ▐█ ▀ ▪█▪██▌██ ██•  ██▪ ██ ▐█ ▀█▪▪     •██
                      ▄█ ▀█▄█▌▐█▌▐█·██▪  ▐█· ▐█▌▐█▀▀█▄ ▄█▀▄  ▐█.▪
                      ▐█▄▪▐█▐█▄█▌▐█▌▐█▌▐▌██. ██ ██▄▪▐█▐█▌.▐▌ ▐█▌·
                      ·▀▀▀▀  ▀▀▀ ▀▀▀.▀▀▀ ▀▀▀▀▀• ·▀▀▀▀  ▀█▄▀▪ ▀▀▀


[![Discord chat](https://img.shields.io/badge/discord-join%20chat%20%E2%86%92-brightgreen.svg?style=flat)](https://discord.gg/T8uVhzU)

---

Guildbot focuses on guild events, DKP/IDKP and Other Forms of Loot Systems, and connection with MMORPG/RPG Style Databases and Tools.
More information to be posted soon.

## Download via npm

```sh
$ npm install Guildbot

$ cd ./node_modules/Guildbot

$ mv ./* ../../
```

## Download via git

```sh
$ git clone https://github.com/Bioblaze/Guildbot
```

Guildbot depends on [Node.js](http://nodejs.org/) and [npm](http://npmjs.org/).


For Openshift Hosting
```
WEB: {
  MONGODB: process.env.OPENSHIFT_MONGODB_DB_URL + process.env.OPENSHIFT_APP_NAME || 'mongodb://' + process.env.OPENSHIFT_MONGODB_DB_USERNAME + ":" + process.env.OPENSHIFT_MONGODB_DB_PASSWORD + "@" + process.env.OPENSHIFT_MONGODB_DB_HOST + ':' + process.env.OPENSHIFT_MONGODB_DB_PORT + '/' + process.env.OPENSHIFT_APP_NAME
}
```
