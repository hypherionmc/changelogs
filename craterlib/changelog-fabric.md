**Requires Fabric API for FABRIC**

**Requires Quilt Standard Libraries for Quilt**

**Bug Fixes**:

* Fix UTF-8 Parsing for non-english languages in RPC SDK
* Fix Creative Tabs not being registered on fabric
* Fix Fabric network handler not sending client packets to server
* Fix Apple M1 compat on RPC SDK (Yes, again. F-you apple... Seriously)
* Fix LateInit event firing too early on Forge

**New Stuff**:

* Added MessageBroadcastEvent (Fired when messages are broadcast to players)