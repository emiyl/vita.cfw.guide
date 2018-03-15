---
title: Installing VitaShell to System
layout: single
sidebar:
  nav: "side"
---

After installing HENkaku Enso on 3.65, you can lose VitaShell if you format the system. If you haven't made a backup, you could lose the ability to install homebrew. So what you can do instead, is install it to the system, which will allow you to keep VitaShell even after formatting.

## Important

The software used in this guide (VitaRW) is potentially **very dangerous**. If you mess with any other files while using it, you could risk losing homebrew with no way to get it back!

I will not be held responsible for any damage done to your system. If you lose homebrew access, that'll be your fault for not reading the guide properly.

You must have VitaShell already installed beforehand. This will replace the near app, so near will not be usable after this. This guide involves rebuilding the database, which will reset your icon layout. This step is necessary and VitaShell will not work on vs0 without doing this.

**Read the guide really carefully.**

Now, let's begin.

## Downloads
- An FTP Client
	- For Windows, I'd recommend [FileZilla](https://filezilla-project.org/){:target="_blank"} or [WinSCP](https://winscp.net/eng/download.php){:target="_blank"}
- The latest release of [VitaRW](https://vitadb.rinnegatamante.it/get_hb_link.php?id=151)

## Instructions

1. Open VitaShell on your Vita
2. Press **Select**
3. Open your FTP client on your computer
4. Type in the IP Address and Port shown on your Vita
5. Navigate to `ux0:data` on the FTP Client
6. Transfer the `VitaRW.vpk` file to your Vita
7. Press **O** on your Vita to close the server
8. Navigate to `ux0:data` on your Vita
9. Press **X** on the `VitaRW.vpk` file to install it
	- Make sure you have [unsafe homebrew enabled](/guide/installing-henkaku/#enabling-unsafe-homebrew){:target="_blank"}
10. Close VitaShell and open VitaRW
11. Wait for it to do its thing, it'll close automatically
  - If it looks like it's frozen, just wait a bit
12. Open VitaShell again
13. Navigate to `vs0:app/NPXS10000/`
14. Go to `eboot.bin` and press **Triangle**
15. Navigate to `ux0:data`
16. Press **Triangle** and then paste
	- This will be your backup of near and will be the only way to restore the app
13. Navigate to `ux0:app/VITASHELL/`
14. Go to `eboot.bin` and press **Triangle**
15. Navigate to `vs0:app/NPXS10000/`
  - Make sure you are inside that directory
  - Make very sure you are inside that directory
16. Press **Triangle** and then paste
17. Navigate to `ur0:shell/db/`
18. Delete `app.db`
19. Turn off your Vita
20. Uninstall VitaRW

VitaShell should now be installed inside the Near application. Just launch Near to use VitaShell. It'll have an annoying bar on the top, so you should probably have the real VitaShell installed too, but I imagine this will only be useful for reinstalling it after a format.
