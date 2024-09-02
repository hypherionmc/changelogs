Requires CraterLib 2.1.0 and above


**New Features**:

- Added LuckPerms support for all Maintenance Mode commands
- Added support for [MC formatting](https://www.digminecraft.com/lists/color_list_pc.php) codes in MOTD and Kick messages
- Added a Maintenance Start/End Schedule (Uses [cron](https://www.uptimia.com/cron-expression-generator) timing)
- Added a config option to not kick online players when maintenance is enabled
- Added support for [MiniMessage](https://docs.advntr.dev/minimessage/format.html) formatting (Same formatting used by MiniMOTD)

**Bug Fixes**:

- Icons now reload when the `/mct reload` command is used
- Players are now kicked when they are removed from the allowed list during maintenance

**Technical Changes**:

- Now uses the Nojang API from CraterLib to be version independent
- Removed the need for Commons Compress, which caused false flags on CurseForge
