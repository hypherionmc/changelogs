- REQUIRES [CraterLib](https://www.curseforge.com/minecraft/mc-mods/craterlib) - [Modrinth](https://modrinth.com/mod/craterlib)
- [Migration guide](https://sdlink.fdd-docs.com/migration/) for V2 users


*Requires CraterLib 2.0.1 or newer*


**Bug Fixes**:

* Fixed Linked commands ignoring the 'useLinkedNames' config setting
* Added missing `Send Message In Threads` permissions to invite link and permission checker
* Channels set to "0" is no longer considered an error, but is logged as a warning
* Now forcefully logging discord disconnect errors, making it clearer why your bot refused to start.
* Change lower limit of topic updates to 6 minutes to prevent ratelimits
* Chat/Event/Console channel cache not reloading with `reloadcache` command
* Fix Join/Leave messages not working with Vanish
* Prevent discord messages from being processed before the bot is ready to do so

**Changes**:

* Improved the way we load the role cache, so it uses less resources on slower servers
* Swapped the position of the `allowedChannels` config option in the linked commands section
