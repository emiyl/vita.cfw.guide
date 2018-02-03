---
title: SD2Vita
layout: single
sidebar:
  nav: "side"
---

SD2Vita is a microSD to gamecard adapter for the PS Vita. This means that you can use a microSD card as storage for your Vita instead of Sony's expensive proprietry memory cards.

If you installed HENkaku using the No-PC route of my guide, download the `.vpk` files from below and install them in VitaShell from `ux0:download`.

## Downloads
- An FTP Client
	- For Windows, I'd recommend [FileZilla](https://filezilla-project.org/){:target="_blank"} or [WinSCP](https://winscp.net/eng/download.php){:target="_blank"}
- The latest release of [Switch SD2Vita](https://github.com/Applelo/SwitchSD2Vita/releases){:target="_blank"}

## Instructions
Make sure your Vita and computer are connected to the same internet

1. Open MolecularShell on your Vita
2. Press **Select**
3. Open your FTP client on your computer
4. Type in the IP Address and Port shown on your Vita
5. Navigate to `ux0:data` on the FTP Client
6. Transfer the Switch SD2Vita `.vpk` file
7. Press **O** to close the FTP server
8. Navigate to `ux0:data` on your Vita
9. Press **X** to install the Switch SD2Vita `.vpk` file
10. Close MolecularShell and open Switch SD2Vita from the Home Menu
11. Choose where to mount your SD Card and Memory Card
	- Select **Switch to ux0** to mount your SD Card as `ux0` and your memory card as `uma0`
	- Select **Switch to uma0** to mount your SD Card as `uma0` and your memory card as `ux0`
12. Select **Reboot your PS Vita**