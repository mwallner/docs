---
Order: 200
Title: Package Synchronization
Description: Keep changes made to applications outside of Chocolatey in sync
---

Chocolatey maintains its own state of the world, while Windows maintains the state of Programs and Features. If an application is upgraded or uninstalled outside of Chocolatey, such as is the case with Google Chrome and its auto updating utility, Chocolatey open source doesn't know about the change. The synchronize features in licensed editions keep Chocolatey's state in sync with Programs and Features, removing possible system-installed state drift.

* [Automatic Sync (All Licensed Editions)](./automatic-sync)
* [Synchronize Command](./choco-sync-command) (currently Business edition only - check https://chocolatey.org/compare#compare for availability)
* [All Packages in Programs And Features (C4B)](./packages-to-programs)