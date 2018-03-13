---
title: SD2Vita
layout: single
sidebar:
  nav: "side"
---

SD2Vita is a microSD to gamecard adapter for the PS Vita. This means that you can use a microSD card as storage for your Vita instead of Sony's expensive proprietry memory cards.

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
5. Insert your MicroSD Card into your computer
6. Backup your Memory Card's contents to your MicroSD card
7. Eject your MicroSD Card and put it into your SD2Vita card
8. Navigate to `ux0:data` on the FTP Client
9. Transfer the Switch SD2Vita `.vpk` file
10. Press **O** to close the FTP server
11. Navigate to `ux0:data` on your Vita
12. Press **X** to install the Switch SD2Vita `.vpk` file
13. Close MolecularShell and open Switch SD2Vita from the Home Menu
14. Choose where to mount your SD Card and Memory Card
	- Select **Switch to ux0** to mount your SD Card as `ux0` and your memory card as `uma0`
	- Select **Switch to uma0** to mount your SD Card as `uma0` and your memory card as `ux0`
15. Insert your SD2Vita card into the Vita with the MicroSD card inserted
16. Select **Reboot your PS Vita**
