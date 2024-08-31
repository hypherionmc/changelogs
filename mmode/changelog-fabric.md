**Requires Fabric API for FABRIC**

**Requires Quilt Standard Libraries for Quilt**

**New Features**:

- Added LuckPerms support for all MaintenanceMode commands
- Added support for MC formatting codes in MOTD and Kick messages
- Added a Maintenance Start/End Schedule (Uses cron timing)
- Added a config option to not kick online players when maintenance is enabled
- Added support for MiniMessage formatting (Same formatting used by MiniMOTD)

**Bug Fixes**:

- Icons now reload when the `/mct reload` command is used
- Players are now kicked when they are removed from the allowed list during maintenance

**Technical Changes**:

- Now uses the Nojang API from CraterLib to be version independent
- Removed the need for Commons Compress, which caused false flags on CurseForge
