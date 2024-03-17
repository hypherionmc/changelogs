- REQUIRES [CraterLib](https://www.curseforge.com/minecraft/mc-mods/craterlib) - [Modrinth](https://modrinth.com/mod/craterlib)
- Fabric requires Fabric API, Quilt requires Quilt Standard Libraries.
- This single Jar supports Forge, Fabric and Quilt. NeoForge support coming soon
- [Migration guide](https://sdlinkbeta.fdd-docs.com/migration/) for V2 users
- [Documentation](https://sdlinkbeta.fdd-docs.com)


### THIS SHOULD BE ONE OF THE LAST BETA BUILDS BEFORE WE GO FULL RELEASE

**Bug Fixes**:

* Fix chat formatting codes being ignored around the `%user%` placeholder - [#108](https://github.com/hypherionmc/sdlink/issues/108) - HypherionSA
* Fix incompatibility with Beautified-chat-server (and hopefully other chat mods) - [#43](https://github.com/hypherionmc/sdlink/issues/43) - HypherionSA
* Fixed an error being logged to the console on shutdown from messages still trying to send - [#101](https://github.com/hypherionmc/sdlink/issues/101) - HypherionSA
* Fix users and roles still be mentionable from chat when it's disabled in the config - [#102](https://github.com/hypherionmc/sdlink/issues/102) - j00w33
* Fix linked discord commands being broken on 1.20.4 - [#106](https://github.com/hypherionmc/sdlink/issues/106) - HypherionSA

**New Features**:

* You can now use Forum Posts and Threads for chat, event and console relay. Supported in both channels and webhooks - [#109](https://github.com/hypherionmc/sdlink/issues/109) - HypherionSA
* You can now use the Minecraft Whitelist with the access control system for more security, and for mods that require the whitelist to be enabled - HypherionSA
