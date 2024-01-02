- REQUIRES [CraterLib](https://www.curseforge.com/minecraft/mc-mods/craterlib) - [Modrinth](https://modrinth.com/mod/craterlib)
- Fabric requires Fabric API, Quilt requires Quilt Standard Libraries.
- This single Jar supports Forge, Fabric and Quilt. NeoForge support coming soon
- [Migration guide](https://sdlinkbeta.fdd-docs.com/migration/) for V2 users

### THIS SHOULD BE THE LAST BETA BUILD BEFORE WE GO FULL RELEASE

**Bug Fixes**:

* Fixed replies to Webhook messages not being relayed to Minecraft
* Fixed linked commands not being able to run on servers without Verification, or for users without a verified account
* Fixed Access Control not allow players with real Minecraft accounts to verify themselves on offline servers
* Fixed some missed Vanish integration on some messages


**New Features**:

* Added a config option to allow servers to either let people verify multiple MC accounts, or just one
* Added `%player_avatar%` and `%player_name%` variables for custom embeds so you can get player information in some Server messages
