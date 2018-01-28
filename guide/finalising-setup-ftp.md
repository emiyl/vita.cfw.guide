---
title: Finalising Setup (FTP)
layout: single
sidebar:
  nav: "side"
---

The following guides are completely optional, however the software is very useful and you may find them helpful.

## Contents
- [Enabling Downloads](#enabling-downloads)
- [Enabling PS Store](#enabling-ps-store)

## Enabling Downloads

Vitas can only download media files, such as images and videos, through the browser. Download Enabler is a HENkaku Plugin that allows you to download any file.

The downloaded files are found at `ux0:download`

### Downloads
- An FTP Client
	- For Windows, I'd recommend [FileZilla](https://filezilla-project.org/){:target="_blank"} or [WinSCP](https://winscp.net/eng/download.php){:target="_blank"}
- The latest release of [Download Enabler](https://github.com/TheOfficialFloW/DownloadEnabler/releases/latest){:target="_blank"}

### Instructions
Make sure your Vita and computer are connected to the same internet

1. Open MolecularShell on your Vita
2. Press **Select**
3. Open your FTP client on your computer
4. Type in the IP Address and Port shown on your Vita
5. Navigate to `ux0:data` on the FTP Client
6. Transfer the Download Enabler `.suprx` file
8. Press **O** on your Vita to close the server
9. Navigate to `ux0:data` on your Vita
10. Press **Triangle** and copy the file
11. Navigate to `ur0:tai` and paste it there
12. Open `config.txt`
13. Go to `*main` and press **Triangle > Insert empty line**
14. Type into the new line: `ur0:tai/de3.suprx`
15. Exit and save changes
16. Delete the directory `ux0:tai` if it exists
	- If you have any plugins already installed, copy those over to `ur0:tai` and edit `ur0:tai/config.txt` accordingly
17. Reboot your console
18. Reinstall HENkaku as shown above

## Enabling PS Store

On July 29th, Sony disabled activation on HENkaku-enabled devices. This means that if you didn’t activate your device before then, you can’t use the PS Store.

[ReNpDrm](http://renpdrm.customprotocol.com/release_page.php){:target="_blank"} and [ReStore](http://renpdrm.customprotocol.com/release_page.php){:target="_blank"} are plugins by [CelesteBlue](https://twitter.com/CelesteBlue123){:target="_blank"} that allow you to activate your Vita and use the PS Store.

Bans are _theoretically_ possible, however none have been reported. Use this software at your own risk. CelesteBlue or I will not take responsibility for anything that happens to your device.

### Downloads
- An FTP Client
	- For Windows, I'd recommend [FileZilla](https://filezilla-project.org/){:target="_blank"} or [WinSCP](https://winscp.net/eng/download.php){:target="_blank"}
- The latest release of [ReNpDrm](http://renpdrm.customprotocol.com/renpdrm_download.php)
- The latest release of [ReStore](http://renpdrm.customprotocol.com/renpdrm_download.php)

### Instructions
Make sure your Vita and computer are connected to the same internet

1. Open MolecularShell on your Vita
2. Press **Select**
3. Open your FTP client on your computer
4. Type in the IP Address and Port shown on your Vita
5. Navigate to `ux0:data` on the FTP Client
6. Transfer the Download Enabler `.suprx` file
8. Press **O** on your Vita to close the server
9. Navigate to `ux0:data` on your Vita
10. Press **Triangle** and copy the file
11. Navigate to `ur0:tai` and paste it there
12. Open `config.txt`
13. Go to `*main` and press **Triangle > Insert empty line**
14. Type into the new line: `ur0:tai/de3.suprx`
15. Exit and save changes
16. Delete the directory `ux0:tai` if it exists
	- If you have any plugins already installed, copy those over to `ur0:tai` and edit `ur0:tai/config.txt` accordingly
17. Reboot your console
18. Reinstall HENkaku as shown above