- REQUIRES [CraterLib](https://www.curseforge.com/minecraft/mc-mods/craterlib) - [Modrinth](https://modrinth.com/mod/craterlib)
- [Migration guide](https://sdlink.fdd-docs.com/migration/) for V2 users


*Requires CraterLib 2.0.1 or newer*


**Bug Fixes**:

* Fixed vanished players still being shown in the player list command in discord
* Fixed join/leave messages not working properly with Vanish (Needs CraterLib update)
* Fixed Discord formatting not being stripped when `formatting` is set to false (Needs CraterLib update)
* Finally fixed the 2 year old server hang on shutdown bug
* Potentially fixed an issue with the bot hanging on startup on some hosting providers
* Added a better fix for the bot trying to process discord messages when it's not ready
* Fixed the config migration system not creating a backup of the old config
* Fixed the `setchannel` command overriding all existing webhook and channel configs

**New Features**:

* Added a `reloadbot` command in Minecraft to completely reload the bot and config without a server restart
* Added a config option to switch between Silent and Normal bot replies
* Added a new `%role%` variable to `mcPrefix` to display the name of the highest role the discord user has
* Added a new `%color% %end_color%` variable to `mcPrefix` to use the Discord user color in game
* Added a config option to change how the Webhook name is displayed for chat messages
* Added the player count in the footer of the `/playerlist` discord command
* Added a new config option to display the discord user information on a hover tooltip in-game
