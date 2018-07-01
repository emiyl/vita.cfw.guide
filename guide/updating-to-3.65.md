---
title: Updating to 3.65
layout: single
sidebar:
  nav: "side"
---

This will update your PS Vita to system version 3.65 in preparation for the new HENkaku exploit. The exploit only runs on 3.65 and above, so you'll need to update to that before you can proceed.

*Do not* update through the system to 3.68. You cannot install HENkaku Ensō on system versions 3.67 and above. HENkaku Ensō allows you to run homebrew automatically on boot.

This guide is for updating to **STOCK** 3.65. If you are looking to update to HENkaku Ensō 3.65 from 3.60, follow [this guide](/more/updating-to-henkaku-enso-3.65).
{: .notice--info}

This guide is not compatible with PS TV consoles.
{: .notice--danger}

## Downloads

- [PS Vita Firmware 3.65](https://github.com/TheOfficialFloW/update365/releases/download/v1.0/PSP2UPDAT.PUP)
- [QCMA](https://codestation.github.io/qcma/)

## Instructions

1. Install QCMA onto your PC
1. Copy the `PSP2UPDAT.PUP` file to your QCMA Updates folder
	- On Windows this is typically `C:\Users\USERNAME\Documents\PSV Updates`
1. Copy the `psp2-updatelist.xml` file to your QCMA Updates folder
1. On your PS Vita, open the Settings application
1. Enable "Flight Mode"
1. Press the PS button to go back to the home screen
1. Tap the bubble in the top right corner
1. Delete any updates previously downloaded if they exist
1. Launch QCMA on your PC
1. Open QCMA Settings
1. Open the `Other` tab
1. Change the `Use this version for updates` drop down to `Custom`
1. Enter `Custom PS Vita version` to `03.650.000`
1. Click Ok
1. Plug your Vita into your PC via USB
1. On your Vita, open the Settings application again
1. Select "System Update"
1. Select "Update from PC"
1. Be absolutely certain that the message says "Version 3.65"
	- If it does not, go back and see where you went wrong
1. Update your system

---
[Blocking Updates](/guide/blocking-updates){: .btn .btn--light-outline}
{: style="text-align: center;"}
