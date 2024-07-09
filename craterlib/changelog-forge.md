**Bug Fixes**:

- Removed the server pinger call, which causes lag with Simple RPC on Direct connections/lan - Fixes [#88](https://github.com/hypherionmc/simple-rpc-public/issues/88)
- Actually return a `null` when trying to pull single player server data when it should return server data (nojang api)


**API Changes**

- Added a boolean flag to player join/leave events when the event was sent from Vanish
