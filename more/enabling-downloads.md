---
title: Enabling Downloads
layout: single
sidebar:
  nav: "side"
---

Vitas can only download media files, such as images and videos, through the browser. Download Enabler is a HENkaku Plugin that allows you to download any file.

### Downloads
- An FTP Client
	- For Windows, I'd recommend [FileZilla](https://filezilla-project.org/){:target="_blank"} or [WinSCP](https://winscp.net/eng/download.php){:target="_blank"}
- The latest release of [Download Enabler](https://github.com/TheOfficialFloW/DownloadEnabler/releases/latest){:target="_blank"}

### Instructions
Make sure your Vita and computer are connected to the same internet

1. Open MolecularShell or VitaShell on your Vita
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
14. Type into the new line: `ur0:tai/download_enabler.suprx`
15. Exit and save changes
16. Delete the directory `ux0:tai` if it exists
	- If you have any plugins already installed, copy those over to `ur0:tai` and edit `ur0:tai/config.txt` accordingly
17. Reboot your console
18. Reinstall HENkaku if Enso is not installed

You should now be able to download any file from the Vita Browser.

The downloaded files are found at `ux0:download`
