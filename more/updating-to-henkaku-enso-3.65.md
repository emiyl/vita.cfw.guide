---
title: Updating to HENkaku Ensō 3.65
layout: single
toc: true
sidebar:
  nav: "side"
---

You can now update your 3.60 HENkaku enabled PS Vita to 3.65, while keeping HENkaku installed. This is not installable from 3.61 or above.

<div class="notice"><p>If you are on a firmware version below 3.60, update using <a href="/guide/updating-to-3.60/">this guide</a>.</p>
<p>If you have not yet installed HENkaku, follow <a href="/guide/installing-henkaku/">this guide</a>. Do not proceed to installing HENkaku Ensō.</p></div>

## Important
If you do not follow this guide correctly, you could lose homebrew access, with **no way to get it back!**

Only follow this guide if you want to install games which require a firmware version higher than 3.61!

Please follow all steps in this guide carefully. I will not be responsible to anything that happens to your device when using this.

If you have any tips to improve the guide, please contact me on my [Discord](/help/discord/){:target="_blank"}.

## Warnings

**DO NOT:**
- Reflash the 3.65 PUP
- Mess with system partitions
- Use applications which mess with system partitions

Doing so could leave you on 3.65 without any way to regain homebrew access.

Formatting your Vita should be safe however.

## Compatibility

Many plugins and applications have not been updated to support 3.65. As such, some of them on your Vita may stop working. Software such as VitaShell, Adrenaline, DownloadEnabler, SD2Vita, and more have been updated though however. Download the latest version to use them.

## Downloads

- An FTP Client
	- For Windows, I'd recommend [FileZilla](https://filezilla-project.org/){:target="_blank"} or [WinSCP](https://winscp.net/eng/download.php){:target="_blank"}
- The latest release of [VitaShell](https://github.com/TheOfficialFloW/VitaShell/releases/latest/){:target="_blank"}
  - You must have v1.82 or later
  - VitaShell no longer automatically updates, so you will need to download it again if it's not already installed
- The latest release of [update365](https://github.com/TheOfficialFloW/update365/releases/latest){:target="_blank"}
  - Download both files
- The latest release of [CMA](http://cma.dl.playstation.net/cma/win/gb/index.html){:target="_blank"}
- The latest release of [HENkaku Ensō](https://github.com/henkaku/enso/releases/download/v1.0/enso.vpk)
  - Only if you have previously installed HENkaku Ensō

## Instructions

Do not reboot, turn off, or let your PS Vita run out of charge while following this guide unless told to.

### Preparing
---

1. Make sure SD2Vita is not enabled and the SD Card is not inserted
1. Delete VitaShell if it's already installed
  - Make sure MolecularShell is still installed
  - [Reinstall HENkaku](/guide/installing-henkaku/#instructions){:target="_blank"} while holding down **R** to install it
2. Open MolecularShell on your Vita
3. Open `ux0`
3. Go down to the `VitaShell` directory
3. Press **Triangle** and then select "Delete"
3. Press **Select**
4. Open your FTP client on your computer
5. Type in the IP Address and Port shown on your Vita
6. Navigate to `ux0:data` on the FTP Client
7. Transfer the `VitaShell.vpk` file to your Vita
8. Transfer the `updater.vpk` file to your Vita
9. Transfer the `enso.vpk` file to your Vita
  - Only if you have previously installed HENkaku Ensō
9. Transfer the `PSP2UPDAT.PUP` file to your Vita
10. Press **O** on your Vita to close the server
11. Navigate to `ux0:data` on your Vita
12. Press **X** on the `.vpk` files to install both of the applications you downloaded
	- Make sure you have [unsafe homebrew enabled](/guide/installing-henkaku/#enabling-unsafe-homebrew){:target="_blank"}

13. Press **X** on the `enso.vpk` file to install it
  - Only if you have previously installed HENkaku Ensō
13. Press **Triangle** on the `PSP2UPDATE.PUP` file and select "Move"
14. Navigate to `ux0:app/UPDATE365/`
15. Press **Triangle** and then select "Paste"
  - The 'PSP2UPDAT.PUP' file should be there
16. Open `ux0:tai/config.txt`
17. Add a hashtag before each user-made plugin
	- e.g. NoNpDrm, ReNpDrm, ReStore, DownloadEnabler, gamesd (SD2Vita), etc.
	- e.g. turn `ux0:tai/gamesd.skrpx` to `#ux0:tai/gamesd.skrpx`
18. Open`ur0:tai/config.txt`
19. Add a hashtag before each user-made plugin
20. Exit MolecularShell

### Backing up VitaShell
---

We will now make a backup of VitaShell on your computer so you can restore it if you lose it on 3.65.

1. Download and install the CMA software onto your computer
2. Connect your PS Vita to your computer via a USB cable or network connection
3. Open the "Content Manager" application on your PS Vita
4. Select "Copy Content"
5. Select "PS Vita System -> PC"
6. Select "Applications"
7. Select "PS Vita"
8. Select "VitaShell"
9. Click "Copy" in the right hand corner
10. Select "Okay"
  - Overwrite any copies previously saved
  - The copy will be saved in `Documents/PS Vita/APP` on your computer
21. Exit Content Manager
21. Open the System Settings application
22. Select "HENkaku Settings"
23. Select "Unlink Memory Card"
  - If you do not do this, you will not be able to use your memory card on 3.65

### Uninstalling HENkaku Ensō
---

If you never installed Ensō, this doesn't apply to you and you can skip to the next section.

1. Open up the HENkaku Ensō application you installed earlier
2. Read what's on screen and then press **O**
3. Press **Triangle** to uninstall HENkaku Ensō
4. Reboot when prompted

### Installing HENkaku Ensō for 3.65
---

1. Reboot your device
2. Open the Web Browser
  - Do not open any other apps
3. Go to [http://go.henkaku.xyz](http://go.henkaku.xyz){:target="_blank"}
4. Once HENkaku is installed, launch the HENkaku Ensō 3.65 Update application
5. Follow the on-screen instructions
6. Enjoy!

HENkaku Ensō should now be installed on your PS Vita with firmware version 3.65. If you notice any issues with my guide, please contact me on [Discord](/help/discord/).

Some plugins may not work as they might not have been updated to support 3.65. Make sure to download the latest versions before using them.
