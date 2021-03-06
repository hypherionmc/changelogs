**Requires Fabric API for FABRIC**

**Requires Quilt Standard Libraries for Quilt**

**Bug Fixes**:

* Fixed Status Command failing on 1.16.5
* Limit Whitelisting to one account per user. Discord Admins and Moderators bypass this limit
* Now has full 1.19 support
* Added better hooks for Chat and Commands on Fabric, so this should be more accurate now!
* Fixed Topic Updates being scheduled too quickly on restarts, resulting in a server hang due to rate limits

**New Stuff**:

* You can now choose between EMBEDS and Plain text for both Webhook and Normal channel messages
* Added Webhook support for LOGS channel. Now you can seperate the two in Webhook mode
* Added a new config section to allow you to choose what kinds of messages are considered LOGS and CHAT
