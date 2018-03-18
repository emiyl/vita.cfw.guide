---
title: Installing VitaShell to System
layout: single
sidebar:
  nav: "side"
---

After installing HENkaku Enso on 3.65, you can lose VitaShell if you format the system. If you haven't made a backup, you could lose the ability to install homebrew. So what you can do instead, is install it to the system, which will allow you to keep VitaShell even after formatting.

This guide will replace a system app, so that application will not be usable after this. This guide involves rebuilding the database, which will reset your icon layout. This step is necessary and VitaShell will not work on vs0 without doing this.

You will be able to place VitaShell inside the following applications:
- near
- PS3 Remote Play
- Party
- Calendar

## Downloads
- An FTP Client
	- For Windows, I'd recommend [FileZilla](https://filezilla-project.org/){:target="_blank"} or [WinSCP](https://winscp.net/eng/download.php){:target="_blank"}
- The latest release of [HBInjector](https://github.com/emiyl/HBInjector/releases/latest/){:target="_blank"}

## Instructions

1. Open MolecularShell or VitaShell on your Vita
2. Press **Select**
3. Open your FTP client on your computer
4. Type in the IP Address and Port shown on your Vita
5. Navigate to `ux0:data` on the FTP Client
6. Transfer the `HBInjector.vpk` file to your Vita
7. Press **O** on your Vita to close the server
8. Navigate to `ux0:data` on your Vita
9. Press **X** on the `HBInjector.vpk` file to install it
	- Make sure you have [unsafe homebrew enabled](/guide/installing-henkaku/#enabling-unsafe-homebrew){:target="_blank"}
10. Close VitaShell and open HBInjector
11. Follow the on-screen instructions

VitaShell should now be installed inside your selected system application. Just launch it to use VitaShell.
