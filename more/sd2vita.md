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
- The latest release of [gamecard-microsd](https://github.com/ArkSource/gamecard-microsd/releases/latest/){:target="_blank"}

## Instructions
Make sure your Vita and computer are connected to the same internet

1. Open MolecularShell on your Vita
2. Press **Select**
3. Open your FTP client on your computer
4. Type in the IP Address and Port shown on your Vita
5. Insert your MicroSD Card into your computer
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
