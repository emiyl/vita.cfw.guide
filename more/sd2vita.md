---
title: SD2Vita
layout: single
sidebar:
  nav: "side"
---

SD2Vita is a microSD to gamecard adapter for the PS Vita. This means that you can use a microSD card as storage for your Vita instead of Sony's expensive proprietary memory cards.

Make sure your Vita and computer are connected to the same internet
{: .notice .notice--info}

The first part of this guide requires you to have Windows
{: .notice .notice--info}

You must have the latest version of VitaShell installed
{: .notice .notice--info}

## Downloads
- An FTP Client
	- For Windows, I'd recommend [FileZilla](https://filezilla-project.org/){:target="_blank"} or [WinSCP](https://winscp.net/eng/download.php){:target="_blank"}
- The latest release of [gamecard-microsd](/assets/files/gamesd.skprx)
- The latest release of [Win32 Disk Imager](https://sourceforge.net/projects/win32diskimager/){:target="_blank"}
- [zzBlank.img](/assets/files/zzBlank.img)

## Formatting your microSD Card

![Format microSD Card](/assets/images/formatmicrosd.png "Format microSD Card"){: .align-right}
1. Insert your microSD card into your computer
2. Open Win32 Disk Imager
3. Select `zzBlank.img` from your computer
4. Select your microSD card
5. Press "Write"
6. Take out your microSD card and put it back in
7. Format your microSD card from Windows
8. Select the following options
  - File System: exFAT
  - Allocation Unit Size: Default Allocation Size
  - Don't put in a volume label

## Installing SD2Vita
Make sure your Vita and computer are connected to the same internet

1. Open VitaShell on your Vita
2. Press **Select**
3. Open your FTP client on your computer
4. Type in the IP Address and Port shown on your Vita
5. Insert your MicroSD Card into your computer
6. Format your microSD card
6. Copy the contents of `ux0` to your microSD card
7. Eject your MicroSD Card and put it into your SD2Vita card
8. Navigate to `ux0:data` on the FTP Client
9. Transfer the `gamesd.skprx` file
10. Press **O** to close the FTP server
11. Navigate to `ux0:data` on your Vita
12. Go to the `gamesd.skprx` file and press **Triangle**
13. Select "Copy"
14. Navigate to `ur0:tai` on your Vita
15. Press **Triangle** and select "Paste"
16. Open `config.txt`
17. Go to `*KERNEL` and press **Triangle**
18. Select "Insert Empty Line"
20. Type into the new line `ur0:tai/gamesd.skprx`
21. Exit and save changes
22. Insert your SD2Vita card into the Vita with the MicroSD card inserted
24. Reboot your Vita
