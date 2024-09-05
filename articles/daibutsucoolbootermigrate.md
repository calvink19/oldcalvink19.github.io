# daibutsu migrator for iOS 8 dualboots
(info from [here](https://github.com/LukeZGD/daibutsu-migrator/tree/main), just changed a few things)  

If you dual-boot with iOS 8 with your main partition using EtasonJB, Home Depot, or openpwnage, you might have a risk of entering a bootloop (especially with EtasonJB).

"daibutsu migrator" installs the latest daibutsu untether (2.0.3) to devices that are already jailbroken with EtasonJB, Home Depot, or openpwnage.

The latest daibutsu untether by kok3shidoll/dora and Clarity is compatible with all 32-bit devices iOS 8.0 to 8.4.1.

### How to install daibutsu migrator

1. Upgrade all packages in Cydia
1. Add Luke's repo: https://lukezgd.github.io/repo
1. Install "daibutsu migrator"
1. After the device reboots, open Cydia
1. After the respring, open Cydia again and remove "daibutsu migrator"
1. The migration process is complete, your device is now jailbroken with daibutsu.
3. If you're using the coolbooter app, it'll give you an option to install a new partition. DO NOT CLICK INSTALL.
4. Go to cydia and install Mterminal and coolbootercli.
5. Type in `su root`, default password is `alpine`.
6. Type in `coolbootercli -b`. You will now boot into your coolbooter partition.

### Notes
- A5(X) support is limited to 8.3 to 8.4.1 only for now. A6(X) is fully supported for 8.0 to 8.4.1.
- Currently, the only way to jailbreak A6(X) devices on 8.0 to 8.4 is to use [Legacy iOS Kit](https://github.com/LukeZGD/Legacy-iOS-Kit) for installing daibutsu.
- Credits to LukeZGD for the original tutorial.
