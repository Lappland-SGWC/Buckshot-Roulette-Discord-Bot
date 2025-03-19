<h1 align="center">Buckshot Roulette Discord Bot</h1>

> [!IMPORTANT]
> The main README.md might not be updated or delayed updated.
> Use the [web repo](https://Lappland-SGWC.github.io/Buckshot-Roulette-Discord-Bot/) instead.
>

[![Github release](https://img.shields.io/badge/current_bot_version-v0.5.4-green?style=for-the-badge
)](./)
[![updated](https://img.shields.io/badge/Last%20update-13th%20may%20at%2008%3A42-00ffff?style=for-the-badge)](./)

[![tos](https://img.shields.io/badge/terms_of_service-v1.0.2-green?style=for-the-badge
)](./ToS.md)
[![updated](https://img.shields.io/badge/Last%20update-5th%20June%20at%2010%3A49-00ffff?style=for-the-badge)](./ToS.md)

[![privacy policy](https://img.shields.io/badge/Privacy_Policy-v0.1.0.4-green?style=for-the-badge
)](./Privacy%20Policy.md)
[![updated](https://img.shields.io/badge/Last%20update-6th%20may%20at%2008%3A28-00ffff?style=for-the-badge)](./Privacy%20Policy.md)

# Overview

- [Informations](#brdb)
  - [Word](#word)
  - [Todo](#todo)
- [how to Install](#install)
- [How to](#how-to)
  - [play](#play)
  - [setup](#setup)
    - [Boot channel setup](#boot)
    - [Vote channel setup](#votes)
- [Features](#features)
  - [Game](#game)
  - [Commands](#commands)
- [BRDB version](#versions)
- [Permissions and usage](#permissions)
- [Links](#links)
- [Credits](#credits)

# [BRDB](#overview)

This is the official Buckshot Roulette Discord Bot repo of Raven's bot

## [WORD](#overview)

if you encounter any bugs, errors or anything else, then make sure to report it.

I might need to join the server to identify the error and fix it.

## [TODO](#overview)

- [ ] Dealer adrenaline action
- [ ] change save files from user specific to user and channel specific save
- [ ] 24/7 hosting

# [INSTALL](#overview)

1. Click or copy the [link](#links) and <kbd>Ctrl</kbd>+<kbd>V</kbd>/open (in) a new tab in your browser.

2. Select the server you want to add the bot to.\
[![step2](./assets/images/step2.png)](./)

3. Configurate permissions as you like and click on ``Authorize``.\
[![step3](./assets/images/step3.png)](./)

4. Done. The bot is now on your server. Have Fun.\
[![step4](./assets/images/step4.png)](./)

# [HOW-TO](#overview)

``How-to`` Informations are here.

## [PLAY](#overview)

``How-to-play``

1. go into the designated channel/thread/forum or create a new private thread.\
[![image](https://img.shields.io/badge/Image%20status-pending-ff0000?style=for-the-badge)](./)

2. type ``/buckshot_roulette player start``.\
[![image](https://img.shields.io/badge/Image%20status-pending-ff0000?style=for-the-badge)](./)

3. play by using the modal menu or buttons under the embed messages.\
[![image](https://img.shields.io/badge/Image%20status-pending-ff0000?style=for-the-badge)](./)

4. get current game info (charges, inv, loaded shells) via ``/buckshot_roulette player info``.\
[![image](https://img.shields.io/badge/Image%20status-pending-ff0000?style=for-the-badge)](./)

## [SETUP](#overview)

you get how-to-setup infos here.

### [Boot](#overview)

How to setup the booting message channel for the bot.

You get messages, when the bot goes online.

1. type ``/buckshot_roulette setup booting_message select_channel:[any channel]``\
[![boot1](./assets/images/boot1.png)](./)

2. wait for the bot to send himself a verification message.\
[![boot2](./assets/images/boot2.png)](./)

3. Setup is done. You now receive booting messages from the bot, when its online.\
[![boo3](./assets/images/boot3.png)](./)

### [Votes](#overview)

How to setup the vote message channel for the bot.

you can vote for upcomming updates or changes.

1. type ``/buckshot_roulette setup vote_channel select_channel:[any channel]``\
[![vote1](./assets/images/vote1.png)](./)

2. wait for the bot to send himself a verification message.\
[![vote2](./assets/images/vote2.png)](./)

3. Setup is done. You now receive vote messages from the bot, when there are new votes.\
[![vote3](./assets/images/vote3.png)](./)

# [FEATURES](#overview)

## [GAME](#overview)

Player actions:

| Supported since Version | Action | Supported |
| --- | --- | --- |
| <0.2.x | SHOOT SELF | :white_check_mark: |
| <0.2.x | SHOOT DEALER | :white_check_mark: |
| <0.2.x | BEER | :white_check_mark: |
| <0.2.x | HANDCUFFS | :white_check_mark: |
| <0.2.x | MAGNIFYING GLASS | :white_check_mark: |
| <0.2.x | SAW | :white_check_mark: |
| <0.2.x | CIGARETTS | :white_check_mark: |
| <0.2.x | EXPIRED MEDICINE | :white_check_mark: |
| <0.2.x | BURNER PHONE | :white_check_mark: |
| <0.2.x | ADRENALINE | :white_check_mark: |
| <0.2.x | INVERTER | :white_check_mark: |

Dealer actions:

| Supported since Version | Action | Supported |
| --- | --- | --- |
| <0.4.x | SHOOT SELF | :white_check_mark: |
| <0.4.x | SHOOT PLAYER | :white_check_mark: |
| <0.4.x | BEER | :white_check_mark: |
| <0.4.x | HANDCUFFS | :white_check_mark: |
| <0.4.x | MAGNIFYING GLASS | :white_check_mark: |
| <0.4.x | SAW | :white_check_mark: |
| <0.4.x | CIGARETTS | :white_check_mark: |
| <0.4.x | EXPIRED MEDICINE | :white_check_mark: |
| 0.4.8 | BURNER PHONE | :white_check_mark: |
| :x: | ADRENALINE | :x: |
| <0.4.x | INVERTER | :white_check_mark: |

## [COMMANDS](#overview)
>
> [!NOTE]
> Admin commands are only avalable for the bot owner.
>

| Version | Command | Command Sup Group | Command Group | Result |
| --- | --- | --- | --- | --- |
| 0.1.5 | buckshot_roulette | player | start | Creates a message with a modal menu to select actions and start the game in your current channel |
| 0.2.7 | buckshot_roulette | player | info | Get informations about your current game |
| 0.4.1 | buckshot_roulette | ranks | local | Get all scores in your server |
| 0.4.1 | buckshot_roulette | ranks | global | Get all scores from every server |
| 0.4.6 | buckshot_roulette | setup | booting_message | Creates a Booting webhook in a desired channel |
| 0.5.2 | buckshot_roulette | setup | vote_channel | :x: |
| 0.5.2 | buckshot_roulette | admin | vote | Nothing/.deferUptade() |
| 0.5.2 | buckshot_roulette | admin | get_vote | Nothing/.deferUptade() |

# [VERSIONS](#overview)

| Version | Feature |
| --- | --- |
| 0.5.4 | Fixed a bug, that could cause the dealer to always shoot live at you, when the gun is loaded blank after userd burner phone on that round |
| 0.5.3 | changed booting message conf. and bug fix |
| 0.5.2 | Added 1 new setup command |
| <0.5.1 | Basically everything else (didn't noted all changes) |

# [PERMISSIONS](#overview)
>
> [!IMPORTANT]
> Required permissions are subject to change
>

> [!WARNING]
> Make sure the bot has the requred permissions or it will not work correctly.
>

| Permission | Default | Required | Usage |
| --- | --- | --- | --- |
| Add Reactions | :white_check_mark: | :x: | Nothing yet, but planned in the future |
| Administrator | :x: | :x: | :x: |
| Attach Files | :white_check_mark: | :white_check_mark: | requred for the game embed to work properly |
| Ban Members | :x: | :x: | :x: |
| Change Nickname | :white_check_mark: | :x: | no usage yet |
| Connect | :x: | :x: | :x: |
| Create Events | :white_check_mark: | :x: | creating events for votes |
| Create Expressions | :x: | :x: | :x: |
| Create Instant Invite | :white_check_mark: | :white_check_mark: | required to give quick and helpfull support and bug fixes |
| Create Polls | :white_check_mark: | :white_check_mark: | for feature and other votes required |
| Create Private Threads | :x: | :x: | :x: |
| Create Public Threads | :x: | :x: | :x: |
| Deafen Members | :x: | :x: | :x: |
| Embed Links | :white_check_mark: | :white_check_mark: | required forthe game embed to work properly |
| Kick Members | :x: | :x: | :x: |
| Manage Channels | :x: | :x: | :x: |
| Manage Events | :white_check_mark: | :white_check_mark: | required to make changes in poll events |
| Manage Expressions | :x: | :x: | :x: |
| Manage Messages | :x: | :x: | :x: |
| Manage Nicknames | :x: | :x: | :x: |
| Manage Roles | :x: | :x: | :x: |
| Manage Server | :x: | :x: | :x: |
| Manage Threads | :x: | :x: | :x: |
| Manage Webhooks | :white_check_mark: | :white_check_mark: | required to create a booting webhook |
| Mention Everyone | :white_check_mark: | :x: | used for @here pings for booting messages and polls |
| Moderate Members | :x: | :x: | :x: |
| Move Members | :x: | :x: | :x: |
| Mute Members | :x: | :x: | :x: |
| Priority Speaker | :x: | :x: | :x: |
| Read Message History | :white_check_mark: | :x: | required for remote support (WIP) |
| Read Messages/View Channels | :white_check_mark: | :white_check_mark: | required for the bot to register booting webhook and game embeds |
| Request To Speak | :x: | :x: | :x: |
| Send Messages | :white_check_mark: | :white_check_mark: | required for the game embeds and everything else |
| Send Messages in Threads | :white_check_mark: | :white_check_mark: | required if bot is used in a thread or forum |
| Send TTS Messages | :x: | :x: | :x: |
| Speak | :x: | :x: | :x: |
| Use Embedded Activities | :white_check_mark: | :white_check_mark: | embed working stuff |
| Use External Emojis | :white_check_mark: | :white_check_mark: | Bot uses emojis from other servers to work properly |
| Use External Sounds | :x: | :x: | :x: |
| Use External Stickers | :x: | :x: | :x: |
| Use Slash Commands | :white_check_mark: | :white_check_mark: | required for the bot to work in general |
| Use Soundboard | :x: | :x: | :x: |
| Use Voice Activity | :x: | :x: | :x: |
| Video | :x: | :x: | :x: |
| View Audit Log | :x: | :x: | :x: |
| View Creator Monetization Insights | :x: | :x: | :x: |
| View Server Insights | :x: | :x: | :x: |

# [LINKS](#overview)

[Main server:](https://Discord.gg/9Nu2KNWSwn)

```https
https://Discord.gg/9Nu2KNWSwn
```

[Bot invite link:](https://discord.com/oauth2/authorize?client_id=1228396964970889286)

```https
https://discord.com/oauth2/authorize?client_id=1228396964970889286
```

# [CREDITS](#overview)

Friend and Support during developement

- Waulesi

Beta 0.4.x testers

- Luke
- Lyna
- Char Aznable
- antlerswitch
- ANONYMOUS
- ANOMYMOUS
- ANONYMOUS
