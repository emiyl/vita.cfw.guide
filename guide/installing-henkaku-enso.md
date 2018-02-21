---
title: Installing HENkaku Ensō (FTP)
layout: single
sidebar:
  nav: "side"
---

HENkaku requires us to relaunch the exploit upon every reboot. This might not be hard, but it can get annoying. This is why we recommend installing HENkaku Ensō. Ensō will automatically install HENkaku on boot, making it the best solution to PS Vita homebrew right now.

## Downloads
- An FTP Client
	- For Windows, I'd recommend [FileZilla](https://filezilla-project.org/){:target="_blank"} or [WinSCP](https://winscp.net/eng/download.php){:target="_blank"}
- The latest release of [HENkaku Ensō](https://github.com/henkaku/enso/releases/download/v1.0/enso.vpk)

## Instructions
1. Open MolecularShell on your Vita
2. Press Select
3. Open your FTP client on your computer
4. Type in the IP Address and Port shown on your Vita
5. Navigate to `ux0:data` on the FTP Client
6. Transfer the Ensō `.vpk` file
8. Press **O** on your Vita to close the server
9. Navigate to `ux0:data` on your Vita
10. Press **X** on the Ensō `.vpk` file to install it
	- Make sure you still have unsafe homebrew enabled
11. Exit back to the home menu and open the Ensō application
12. Press **O** to accept terms
13. Press **X** to install Ensō
	- If it says os0 modifications detected, press **X** to install the 3.60 PUP

<center><a href="/guide/blocking-updates" style="text-decoration: none;color: #ccc;font-weight:normal;"><button style="vertical-align:middle"><span><font size="+2">Blocking Updates</font></span></button></a></center>
