---
title: Finalising Setup (No PC)
layout: single
sidebar:
  nav: "side-nopc"
---

On July 29th, Sony disabled activation on HENkaku-enabled devices. This means that if you didn’t activate your device before then, you can’t use the PS Store.

[ReNpDrm](http://renpdrm.customprotocol.com/release_page.php){:target="_blank"} and [ReStore](http://renpdrm.customprotocol.com/release_page.php){:target="_blank"} are plugins by [CelesteBlue](https://twitter.com/CelesteBlue123){:target="_blank"} that allow you to activate your Vita and use the PS Store.

Bans are _theoretically_ possible, however none have been reported. Use this software at your own risk. CelesteBlue or I will not take responsibility for anything that happens to your device.

### Downloads
- An FTP Client
	- For Windows, I'd recommend [FileZilla](https://filezilla-project.org/){:target="_blank"} or [WinSCP](https://winscp.net/eng/download.php){:target="_blank"}
- The latest release of [ReNpDrm](http://renpdrm.customprotocol.com/renpdrm_download.php)
- The latest release of [ReStore](http://renpdrm.customprotocol.com/restore_download.php)

### Instructions
Make sure your Vita and computer are connected to the same internet

1. Open the Web Browser on your Vita to this page
2. Download the latest release of [ReNpDrm](http://renpdrm.customprotocol.com/renpdrm_download.php)
3. Download the latest release of [ReStore](http://renpdrm.customprotocol.com/restore_download.php)
4. Open VitaShell and navigate to `uxo:download`
5. Copy the ReNpDrm `.skrpx` file to the `ur0:tai/` directory
6. Copy the ReStore `.surpx` file to the `ur0:tai/` directory
12. Open `ur0:tai/config.txt`
13. Go to `*KERNEL` and press **Triangle > Insert empty line**
14. Type into the new line: `ur0:tai/renpdrm.skprx`
13. Go to `*main` and press **Triangle > Insert empty line**
14. Type into the new line: `ur0:tai/restore.suprx`
15. Exit and save changes
16. Delete the directory `ux0:tai` if it exists
	- If you have any other plugins previously installed, copy those over to `ur0:tai` and edit `ur0:tai/config.txt` accordingly
17. Reboot your console