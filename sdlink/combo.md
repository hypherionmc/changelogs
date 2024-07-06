- REQUIRES [CraterLib](https://www.curseforge.com/minecraft/mc-mods/craterlib) - [Modrinth](https://modrinth.com/mod/craterlib)
- [Migration guide](https://sdlink.fdd-docs.com/migration/) for V2 users


**Bug Fixes**:

* Fixed Linked commands ignoring the 'useLinkedNames' config setting
* Added missing `Send Message In Threads` permissions to invite link and permission checker
* Channels set to "0" is no longer considered an error, but is logged as a warning
* Now forcefully logging discord disconnect errors, making it clearer why your bot refused to start.


**Changes**:

* Improved the way we load the role cache, so it uses less resources on slower servers
