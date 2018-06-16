---
title: Updating to HENkaku Ensō 3.65
layout: single
toc: true
sidebar:
  nav: "side"
---

You need an official Sony Memory Card to update to Enso 3.65 on a PS Vita 1000.
{: .notice--info}

If you are on a firmware version below 3.60, update using <a href="/guide/updating-to-3.60/">this guide</a>.
{: .notice--info}

If you have not yet installed HENkaku, follow <a href="/guide/installing-henkaku/">this guide</a>. Do not proceed to installing HENkaku Ensō.
{: .notice--info}

Once 3.65 is installed, there will be no way to revert to 3.60.
{: .notice--danger}

This guide will update your HENkaku enabled console to 3.65 with HENkaku Ensō. This is not installable from 3.61 or above.

## Important

If you do not follow this guide correctly, you could lose homebrew access, with **no way to get it back!**

Only follow this guide if you want to legitimately activate your Vita for official PSN content or install games which require a firmware version higher than 3.61!

Please follow all steps in this guide carefully. I will not be responsible to anything that happens to your device when using this.

## Warnings

**DO NOT:**
- Reflash the 3.65 PUP
- Mess with system partitions
- Use applications which mess with system partitions

Doing so could leave you on 3.65 without any way to regain homebrew access.

Formatting your Vita should be safe however.

## Downloads

- An FTP Client
	- For Windows, I'd recommend [FileZilla](https://filezilla-project.org/){:target="_blank"} or [WinSCP](https://winscp.net/eng/download.php){:target="_blank"}
- The latest release of [VitaShell](https://github.com/TheOfficialFloW/VitaShell/releases/latest/){:target="_blank"}
  - You must have v1.82 or later
  - VitaShell v1.82 and earlier no longer automatically update, so you will need to download it again if it's not already installed
- The latest release of [update365](https://github.com/TheOfficialFloW/update365/releases/latest){:target="_blank"}
  - Download both files
- The latest release of [CMA](http://cma.dl.playstation.net/cma/win/gb/index.html){:target="_blank"}
  - [QCMA](https://codestation.github.io/qcma/){:target="_blank"} works too if you want to use that
  - Remember to not have both programs installed
- The latest release of [HENkaku Ensō](https://github.com/henkaku/enso/releases/latest/){:target="_blank"}
  - Only if you have previously installed HENkaku Ensō

## Instructions

Do not reboot, turn off, or let your PS Vita run out of charge while following this guide unless told to.

### Preparing
---

1. Remove any microSD cards or USB devices
	- Alternatively disable the plugins in `tai/config.txt`
1. Delete VitaShell if it's already installed
  - Make sure MolecularShell is still installed
  - [Reinstall HENkaku](/guide/installing-henkaku/#instructions){:target="_blank"} while holding down **R** to install it
1. Open MolecularShell on your Vita
1. Open `ux0`
1. Go down to the `VitaShell` directory
1. Press **Triangle** and then select "Delete"
1. Delete the `patch/VITASHELL/` directory
1. Press **Select**
1. Open your FTP client on your computer
1. Type in the IP Address and Port shown on your Vita
1. Navigate to `ux0:data` on the FTP Client
1. Transfer the `VitaShell.vpk` file to your Vita
1. Transfer the `updater.vpk` file to your Vita
1. Transfer the `enso.vpk` file to your Vita
  - Only if you have previously installed HENkaku Ensō
1. Transfer the `PSP2UPDAT.PUP` file to your Vita
1. Press **O** on your Vita to close the server
1. Navigate to `ux0:data` on your Vita
1. Press **X** on the VitaShell and updater `.vpk` files to install both of the homebrew applications
	- Make sure you have [unsafe homebrew enabled](/guide/installing-henkaku/#enabling-unsafe-homebrew){:target="_blank"}

1. Press **X** on the `enso.vpk` file to install it
  - Only if you have previously installed HENkaku Ensō
1. Press **Triangle** on the `PSP2UPDAT.PUP` file and select "Move"
1. Navigate to `ux0:app/UPDATE365/`
1. Press **Triangle** and then select "Paste"
  - The 'PSP2UPDAT.PUP' file should be there
1. Open `ux0:tai/config.txt`
1. Add a hashtag before (disable) each plugin you may have installed
	- e.g. NoNpDrm, ReNpDrm, ReStore, DownloadEnabler, gamesd (SD2Vita), etc.
	- e.g. turn `ux0:tai/gamesd.skrpx` to `#ux0:tai/gamesd.skrpx`
1. Open`ur0:tai/config.txt`
1. Add a hashtag before (disable) each plugin
1. Exit MolecularShell

### Backing up VitaShell
---

We will now make a backup of VitaShell on your computer so you can restore it if you lose it on 3.65.

1. Download and install the CMA software onto your computer
1. Connect your PS Vita to your computer via a USB cable or network connection
1. Open the "Content Manager" application on your PS Vita
1. Select "Copy Content"
1. Select "PS Vita System -> PC"
1. Select "Applications"
1. Select "PS Vita"
1. Select "VitaShell"
1. Click "Copy" in the right hand corner
1. Select "Okay"
  - Overwrite any copies previously saved
  - The copy will be saved in `Documents/PS Vita/APP` on your computer
1. Exit Content Manager

### Unlinking Memory Card
---

1. Open the System Settings application
1. Select "HENkaku Settings"
1. Disable "Enable PSN Spoofing"
1. Select "Unlink Memory Card"
  - If you do not do this, you will not be able to use your memory card on 3.65

### Uninstalling HENkaku Ensō
---

If you never installed Ensō, this doesn't apply to you and you can skip to the next section.

1. Open up the HENkaku Ensō application
1. Read what's on screen and then press **O**
1. Press **Triangle** to uninstall HENkaku Ensō
1. Reboot when prompted

### Installing HENkaku Ensō for 3.65
---

Do not open any other apps than the guide tells you to until 3.65 has been installed.

1. Reboot your device
1. Open the Web Browser
1. Go to [http://go.henkaku.xyz](http://go.henkaku.xyz){:target="_blank"}
1. Launch the HENkaku Ensō 3.65 Update application
1. Follow the on-screen instructions
1. When it reboots to 3.65, make sure to re-enable PSN Spoofing to 3.68

HENkaku Ensō should now be installed on your PS Vita with firmware version 3.65. If you want you can install VitaShell to System to avoid losing it when formatting by following [this guide](/more/installing-vitashell-to-system/).

You may now uncomment any plugins in the `config.txt`. Some plugins may not work as they might not have been updated to support 3.65. Make sure to download the latest versions before using them.
