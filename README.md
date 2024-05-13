# palera1n
[![GitHub Release](https://img.shields.io/github/v/release/palera1n/palera1n?include_prereleases)](https://github.com/palera1n/palera1n/releases)
[![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/palera1n/palera1n/total)](https://github.com/palera1n/palera1n/releases)
[![GitHub License](https://img.shields.io/github/license/palera1n/palera1n?color=%23C96FAD)](https://github.com/palera1n/palera1n/blob/main/LICENSE)


Jailbreak for A8 through A11, T2 devices, on iOS/iPadOS/tvOS 15.0, bridgeOS 5.0 and higher.




| ![Screenshot of macOS Terminal.app](assets/image-1.png)	| 
|:--:												| 
| A screenshot of palera1n being used in a Terminal | 

## Device Support

> [!NOTE]  
> Apple TV & iBridge support are not currently in the beta releases of palera1n, ETA s0n

<!--- Mobile --->

| iPhone(s)                 | iPad(s)                        		| iPod(s)   					| Apple TV(s) 					|
|-							|-										|-								|-								|
| iPhone 6s                 | iPad mini 4							| iPod Touch (7th generation)	| Apple TV HD                 	|
| iPhone 6s Plus            | iPad (5th generation)					|								| Apple TV 4K (1st generation)	|
| iPhone SE (2016)          | iPad (6th generation)					|								|								|
| iPhone 7                  | iPad (7th generation)					|								|								|
| iPhone 7 Plus             | iPad Pro (9.7")						|								|								|
| iPhone 8                  | iPad Pro (12.9") (1st generation)		|								|								|
| iPhone 8 Plus             | iPad Pro (10.5")						|								|								|
| iPhone X                  | iPad Pro (12.9") (2nd generation)		|								|								|

> Note that on `A11` (iPhone X, 8, 8 Plus), **you must disable your passcode while in the jailbroken state** (on iOS 16, you need to **reset your device** before proceeding with palera1n).

<!--- T2 --->
<details>
<summary>Apple T2 Device Support (click to expand)</summary>

| Apple T2              	|
|-							|
| Apple T2 iMac20,1         |
| Apple T2 iMac20,2         |
| 			              	|
| Apple T2 MacBookAir8,1    |
| Apple T2 MacBookAir8,2    |
| Apple T2 MacBookAir9,1    |
| 			              	|
| Apple T2 MacBookPro15,1   |
| Apple T2 MacBookPro15,2   |
| Apple T2 MacBookPro15,3   |
| Apple T2 MacBookPro15,4   |
| Apple T2 MacBookPro16,1   |
| Apple T2 MacBookPro16,2   |
| Apple T2 MacBookPro16,3   |
| Apple T2 MacBookPro16,4   |
| 			              	|
| Apple T2 iMacPro1,1       |
| Apple T2 Macmini8,1       |
| Apple T2 MacPro7,1        |
|			              	|
| iBridge2,11 (Unknown Mac) |
| iBridge2,13 (Unknown Mac) |



</details>


## Computer Requirements
1. **USB-A** cables are recommended to use, USB-C to may have issues with palera1n and getting into DFU mode.
> Due to USB-C cables having different accessory IDs, your device may not be able to be recognized when using USB-C due to not being able to assert to its USB voltage pin.

2. **Linux or macOS computer**
> AMD CPUs (not AMD Mobile) have an issue where it causes them to have a very low success rate with checkm8 exploit. It is not recommended that you use them with palera1n.

> USB-C port on Apple Silicon Macs *may* require manual unplugging and replugging of the lightning cable after checkm8 exploit. This problem may be solved by connecting via USB hub, though extensions can vary.

## Installing
Visit https://palera.in

## Disclaimers
We are **NOT** responsible for any data loss, or the result of a device being bricked. When using palera1n, the user should accept responsibility if anything happens to their device during the process.
- If your device is stuck in recovery, please run futurerestore `--exit-recovery`, or use `irecovery -n`.
- If you're unable to get out of recovery via these methods please restore with iTunes or Finder.
- palera1n **will not work** in VirtualBox, VMware or any virtual machine that doesn't support PCI passthrough.

## Troubleshooting
Make sure you're following the guides provided [here](https://palera.in), also when asking for support make sure you provide full details on your device, such as:
- iPhone/iPad/iPod
- iOS Version
- Passcode enabled?
- Logs, if panicked then send latest `panic-full` log from your iDevice.

Using `-V` and `-v` would help with debugging.

Join the [Support Discord](https://dsc.gg/palera1n), and find the palera1n-c thread under #jailbreak [here](https://discord.com/channels/1028398973452570725/1074251283143344180).

# Credits
<details><summary>palera1n-c Contributors and Credits</summary>
<p>

- [Nick Chan](https://github.com/asdfugil) for the rewrite
- [Nebula](https://github.com/itsnebulalol) - palera1n owner and manager
- [Mineek](https://github.com/mineek)
- [Tom](https://github.com/plooshi) for updated ploosh kpf and universal loader
- [Lakhan Lothiyi](https://github.com/llsc12) for palera1n loader app
- [checkra1n](https://github.com/checkra1n) for the base of the kpf
- [the Procursus Team](https://github.com/ProcursusTeam) for the amazing [bootstrap](https://github.com/ProcursusTeam/Procursus)
- [Évelyne](https://github.com/evelyneee) for [ElleKit](https://github.com/evelyneee/ellekit), rootless tweak injection
- [Sam Bingner](https://github.com/sbingner) for [Substitute](https://github.com/sbingner/substitute), rootful tweak injection

</details>
</p>

<br>
<p align="center">
Thank you so much to our Patreons that make the future development possible! You may sub <a href="https://patreon.com/palera1n">here</a>, if you'd like to.</br>
</p>
<p align="center">
<a href="https://github.com/samh06"><img width=64 style="border-radius: 25%;" src="https://user-images.githubusercontent.com/18669106/206333607-881d7ca1-f3bf-4e18-b620-25de0c527315.png"></img></a>
<a href="https://havoc.app"><img width=64 style="border-radius: 25%;" src="https://docs.havoc.app/img/standard_icon.png"></img></a>
<a href="https://twitter.com/yyyyyy_public"><img width=64 style="border-radius: 25%;" src="https://cdn.discordapp.com/attachments/1054239098006683688/1072587455779328040/image.png?size=400"></img></a>
<a href="https://twitter.com/0xSp00kyb0t"><img width=64 style="border-radius: 25%;" src="https://pbs.twimg.com/profile_images/1603601553226620935/1t4yD1bD_400x400.jpg"></img></a>
<a href="https://chariz.com"><img width=64 src="https://chariz.com/img/favicon.png"></img></a>
<a href="https://twitter.com/stars6220"><img width=64 style="border-radius: 25%;" src="https://pbs.twimg.com/profile_images/1621062976982728706/pWVZQ-NO_400x400.jpg"></img></a>
<a href="https://github.com/TheFunnyMan16"><img width=64 style="border-radius: 25%;" src="https://cdn.discordapp.com/attachments/1050068822473842778/1082867264807772281/IMG_3942.jpg">
<a href="https://github.com/beast9265"><img width=64 style="border-radius: 25%;" src="https://avatars.githubusercontent.com/u/79794946?v=4"></img></a>
<a href="https://twitter.com/0x7FF7"><img width=64 style="border-radius: 25%;" src="https://pbs.twimg.com/profile_images/1630818481191919618/8MWaJ1F7_400x400.jpg"></img></a>
<a href="https://sideloadly.io/"><img width=64 style="border-radius: 25%;" src="https://sideloadly.io/icon.png"></img></a>
<a href="https://blog.stevesec.com/"><img width=64 style="border-radius: 25%;"  src="https://blog.stevesec.com/img/avatar.jpg"></img></a>
</p>
