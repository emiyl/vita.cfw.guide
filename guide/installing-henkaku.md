---
title: Installing HENkaku
layout: single
sidebar:
  nav: "side"
---

This part will guide you through installing HENkaku and custom homebrew software. The exploit will require you to relaunch the exploit on every reboot via the HENkaku website, but don’t worry, we’ll install a version which doesn’t require this later.

## Downloads
- An FTP Client
	- For Windows, I'd recommend [FileZilla](https://filezilla-project.org/){:target="_blank"} or [WinSCP](https://winscp.net/eng/download.php){:target="_blank"}
- The latest release of [VitaShell](https://github.com/TheOfficialFloW/VitaShell/releases/latest){:target="_blank"}
- The latest release of [Vita Homebrew Browser](https://github.com/devnoname120/vhbb/releases/latest){:target="_blank"}

## Instructions
1. Open the Web Browser on your PS Vita
2. Go to [https://henkaku.xyz/go](https://henkaku.xyz/go){:target="_blank"}

MolecularShell and HENkaku should now be installed on your Vita

[Error C2-12828](/help/faq/#error-c2-12828-when-launching-henkaku)

## Enabling Unsafe Homebrew
This will allow us to access the Vita’s internal memory and install homebrew which requires extended permissions. This can be dangerous, so be careful when installing homebrews which require it.

1. Open the Settings application
2. Select HENkaku Settings
3. Check **Enable Unsafe Homebrew**

<p class="notice">If you are looking to install HENkaku Enso for 3.65, stop here and proceed <a href="/more/updating-to-henkaku-enso-3.65/">here</a>.</p>

## Installing Homebrew
Now we’ve got that out the way, we can start to install some homebrew applications to put on our Home Menu

1. Open MolecularShell on your Vita
2. Press Select
3. Open your FTP client on your computer
4. Type in the IP Address and Port shown on your Vita
5. Navigate to `ux0:data` on the FTP Client
6. Transfer the VitaShell `.vpk` file
7. Transfer the Vita Homebrew Browser `.vpk` file
8. Press **O** on your Vita to close the server
9. Navigate to `ux0:data` on your Vita
2. Press **X** on the `.vpk` files to install both of the homebrew applications you downloaded
	- Make sure you still have unsafe homebrew enabled

You can now use VitaShell as your main file browser, and use Vita Homebrew Browser to download whatever homebrew you want. Keep in mind that Unsafe Homebrew must be enabled to run Vita Homebrew Browser.

[Installing HENkaku Ensō](/guide/installing-henkaku-enso){: .btn .btn--light-outline}
{: style="text-align: center;"}
