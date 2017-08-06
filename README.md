# AllTalk Reset
Sometimes AllTalk is enabled and forgotten about.  This setting will not disable itself on map change or server restart so unfortunately, a server could be stuck in AllTalk mode for an entire day before an Admin can be reached.  This Shine Extension will automatically run "sh_alltalk false" to disable AllTalk on Round End, before a Map Cycle and after a Map Load.

## Requirements
1. Shine Administration NS2 plugin running on the server.
2. Add "shine_alltalk_reset" to the ActiveExtensions of your Shine BaseConfig.json, with a value of true.
3. AllTalk should now be auto-disabled under the previously mentioned conditions.
