Novacash Core version *1.1.0* is now available from:  <https://github.com/novabitsoftware/novacash/releases>

This is a new major version release, including various bug fixes and performance improvements, as well as updated translations.

Please report bugs using the issue tracker at github: <https://github.com/novabitsoftware/novacash/issues>


Mandatory Update
==============

Novacash Core v1.1.0 is a mandatory update for all users. This release contains new consensus rules and improvements that are not backwards compatible with older versions. Users will have a grace period of approximately one week to update their clients before enforcement of this update goes into effect.

Masternodes will need to be restarted once both the masternode daemon and the controller wallet have been upgraded.


How to Upgrade
==============

If you are running an older version, shut it down. Wait until it has completely shut down (which might take a few minutes for older versions), then run the installer (on Windows) or just copy over /Applications/Novacash-Qt (on Mac) or novacashd/novacash-qt (on Linux).


Compatibility
==============

Novacash Core is extensively tested on multiple operating systems using the Linux kernel, macOS 10.10+, and Windows 7 and later.

Microsoft ended support for Windows XP on [April 8th, 2014](https://www.microsoft.com/en-us/WindowsForBusiness/end-of-xp-support), No attempt is made to prevent installing or running the software on Windows XP, you can still do so at your own risk but be aware that there are known instabilities and issues. Please do not report issues about Windows XP to the issue tracker.

Apple released it's last Mountain Lion update August 13, 2015, and officially ended support on [December 14, 2015](http://news.fnal.gov/2015/10/mac-os-x-mountain-lion-10-8-end-of-life-december-14/). Novacash Core software starting with v1.1.0 will no longer run on MacOS versions prior to Yosemite (10.10). Please do not report issues about MacOS versions prior to Yosemite to the issue tracker.

Novacash Core should also work on most other Unix-like systems but is not frequently tested on them.

 
Notable Changes
==============

## zNOVA disabled

Novacash is a clone of PIVX. Unlike PIVX we do not support 100 % anonymization. Regulatory bodies are seeking to expand their anti-money laundering regulations so they can crack down on crypto anonymity. We believe that private coins will have a hard time on the cryptocurrency market in future. First exchanges start to delisten private coins. In addition a few vulnerabilites have been detected on the Zerocoin protocol. Therefore we decided to disable zNOVA. In future vesions the Zerocoin code will be removed completely.

## Credits

Thanks to everyone who directly contributed to this release.

