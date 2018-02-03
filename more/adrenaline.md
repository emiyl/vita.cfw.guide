---
title: Adrenaline
layout: single
sidebar:
  nav: "side"
---

Adrenaline is an extremely useful piece of software which lets you run PS1 and PSP games and homebrew from your memory card.

If you installed HENkaku using the No-PC route of my guide, download the `.vpk` files from below and install them in VitaShell from `ux0:download`.

## Downloads
- An FTP Client
	- For Windows, I'd recommend [FileZilla](https://filezilla-project.org/){:target="_blank"} or [WinSCP](https://winscp.net/eng/download.php){:target="_blank"}
- The latest release of [Adrenaline](https://github.com/TheOfficialFloW/Adrenaline/releases/latest){:target="_blank"}
- The latest release of [PSP Homebrew Browser](/assets/files/PSPhbb_dev.vpk)

## Instructions
Make sure your Vita and computer are connected to the same internet

1. Open MolecularShell on your Vita
2. Press **Select**
3. Open your FTP client on your computer
4. Type in the IP Address and Port shown on your Vita
5. Navigate to `ux0:data` on the FTP Client
6. Transfer the Adrenaline `.vpk` file
7. Transfer the PSP Homebrew Browser `.vpk` file
8. Press **O** on your Vita to close the server
9. Navigate to `ux0:data` on your Vita
10. Press **X** on the `.vpk` files to install both of the homebrew applications you downloaded
	- Make sure you have unsafe homebrew enabled
11. Open the Adrenaline application from the home menu
12. Press **X** to download the PSP 6.61 firmware
13. Adrenaline will automatically close
14. Open Adrenaline again and press **X** to install the firmware
15. Press **X** to boot the PSP XMB
16. Once you've set up the Vita, hold the PS button and select **Settings > Exit PspEmu Application**
17. Open up VitaShell or MolecularShell and navigate to `ur0:tai`
18. Open `config.txt` 
19. Go to `*KERNEL` and press **Triangle > Insert Empty Line**
20. Type into the new line: `ux0:app/PSPEMUCFW/sce_module/adrenaline_kernel.skprx`
21. Reboot