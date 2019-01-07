(note: this is a temporary file, to be added-to by anybody, and moved to release-notes at release time)


This is a new major version release, including various bug fixes and performance improvements, as well as updated translations.

Please report bugs using the issue tracker at github: <https://github.com/Escrow-Coin/Escrow/issues>


Mandatory Update
==============

ESCO Core v1.0.3 is a mandatory update for all users. This release contains new consensus rules and improvements that are not backwards compatible with older versions. Users will have a grace period of one week to update their clients before enforcement of this update is enabled.


How to Upgrade
==============

If you are running an older version, shut it down. Wait until it has completely shut down (which might take a few minutes for older versions), then run the installer (on Windows) or just copy over /Applications/ESCO-Qt (on Mac) or escrowd/escrow-qt (on Linux).


Compatibility
==============

ESCO Core is extensively tested on multiple operating systems using
the Linux kernel, macOS 10.8+, and Windows Vista and later.

Microsoft ended support for Windows XP on [April 8th, 2014](https://www.microsoft.com/en-us/WindowsForBusiness/end-of-xp-support),
No attempt is made to prevent installing or running the software on Windows XP, you
can still do so at your own risk but be aware that there are known instabilities and issues.
Please do not report issues about Windows XP to the issue tracker.

ESCO Core should also work on most other Unix-like systems but is not
frequently tested on them.

### :exclamation::exclamation::exclamation: MacOS 10.13 High Sierra :exclamation::exclamation::exclamation:

**Currently there are issues with the 1.0.3 gitian release on MacOS version 10.13 (High Sierra), no reports of issues on older versions of MacOS.**

 
Notable Changes
==============

ESCO Daemon & Client (RPC Changes)
--------------

### New RPC command
`getfilesyncstate`



Technical Changes
--------------


*1.0.3* Change log
--------------

Detailed release notes follow. This overview includes changes that affect behavior, not code moves, refactors and string updates. For convenience in locating the code changes and accompanying discussion, both the pull request and git merge commit are mentioned.

### Core Features


### Build System

 
### P2P Protocol and Network Code


### GUI

 
### RPC/REST
 

### Wallet

 
### Miscellaneous
 
 
 
## Credits

Thanks to everyone who directly contributed to this release:
