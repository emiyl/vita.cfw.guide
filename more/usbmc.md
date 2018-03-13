---
title: USBMC
layout: single
sidebar:
  nav: "side"
---

USBMC, just like SD2Vita, is a solution to Sony's expensive proprietry memory cards. It allows you to use USB memory with a PSTV, or a microSD card with PSVD boards on 3G Vita 1000s.

<p class="notice">This does not work on 3.65</p>

## Downloads
- An FTP Client
	- For Windows, I'd recommend [FileZilla](https://filezilla-project.org/){:target="_blank"} or [WinSCP](https://winscp.net/eng/download.php){:target="_blank"}
- The latest release of [USBMC](https://github.com/yifanlu/usbmc/releases/latest/){:target="_blank"}

## Instructions
Make sure your Vita and computer are connected to the same internet

1. Open MolecularShell on your Vita
2. Press **Select**
3. Open your FTP client on your computer
4. Type in the IP Address and Port shown on your Vita
5. Navigate to `ux0:data` on the FTP Client
6. Transfer the USBMC `.vpk` file
7. Press **O** to close the FTP server
8. Navigate to `ux0:data` on your Vita
9. Press **X** to install the USBMC `.vpk` file
10. Close MolecularShell and open USBMC Installer from the Home Menu
11. Press **X** to install the drivers and reboot
11. Enter the USBMC Installer application again
11. Press **X** to copy the files to your USB or microSD Card
	- Make sure you have inserted your USB memory into the PSTV first
