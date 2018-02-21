---
title: Installing HENkaku
layout: single
sidebar:
  nav: "side-nopc"
---

This part will guide you through installing HENkaku and custom homebrew software. The exploit will require you to relaunch the exploit on every reboot via the HENkaku website, but don’t worry, we’ll install a version which doesn’t require this later.

## Instructions
1. Open the Web Browser on your PS Vita
2. Go to [https://henkaku.xyz/go](https://henkaku.xyz/go){:target="_blank"}

MolecularShell and HENkaku should now be installed on your Vita

## Enabling Unsafe Homebrew
This will allow us to access the Vita’s internal memory and install homebrew which requires extended permissions. This can be dangerous, so be careful when installing homebrews which require it.

1. Open the Settings application
2. Select HENkaku Settings
3. Check **Enable Unsafe Homebrew**

## Enabling downloads
The Vita’s browser only lets us download certain types of files, such as audio and video files. Unfortunately, it won’t normally let us download Vita homebrew files, but with the Download Enabler plugin, we can download any file we want!

1. Open the Web Browser on your PS Vita and navigate to this website
2. Click the following link to download [Download Enabler v3](/assets/files/de3.mp4) onto your Vita
3. Open MolecularShell and navigate to `ux0:video/XX`
4. Rename `de3.mp4` to `de3.suprx`
5. Press **Triangle** and copy the file
6. Navigate to `ur0:tai` and paste it there
7. Open `config.txt`
8. Go to `*main` and press **Triangle > Insert empty line**
9. Type into the new line: `ur0:tai/de3.suprx`
10. Exit and save changes
11. Delete `ux0:tai`
12. Reboot your console
13. Reinstall HENkaku as shown above

## Installing Homebrew
Now we’ve got that out the way, we can start to download some homebrew applications to put on our Home Menu

1. Open the Web Browser on your PS Vita and navigate to this page
2. Download the latest release of [VitaShell](https://github.com/TheOfficialFloW/VitaShell/releases/latest){:target="_blank"}
3. Download the latest release of [Vita Homebrew Browser](https://github.com/devnoname120/vhbb/releases/latest){:target="_blank"}
4. Open MolecularShell and navigate to `ux0:download`
5. Press **X** on the `.vpk files` to install both of the homebrew applications you just downloaded
	- Make sure you still have unsafe homebrew enabled

You can now use VitaShell as your main file browser, and use Vita Homebrew Browser to download whatever homebrew you want. Keep in mind that Unsafe Homebrew must be enabled to run Vita Homebrew Browser.

<center><a href="/guide/no-pc/installing-henkaku-enso" style="text-decoration: none;color: #ccc;font-weight:normal;"><button style="vertical-align:middle"><span><font size="+2">Installing HENkaku Ensō</font></span></button></a></center>
