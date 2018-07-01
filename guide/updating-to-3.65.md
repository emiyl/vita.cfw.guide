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

## Downloads

- [PS Vita Firmware 3.65](https://github.com/TheOfficialFloW/update365/releases/download/v1.0/PSP2UPDAT.PUP)
- [QCMA](https://codestation.github.io/qcma/)
- `psp2-updatelist.xml`
	- <a href="/assets/files/us/psp2-updatelist.xml" download>US</a>
	- <a href="/assets/files/eu/psp2-updatelist.xml" download>EU</a>
	- <a href="/assets/files/jp/psp2-updatelist.xml" download>JP</a>

## Instructions

1. Open the Settings application
2. Select **Network > Wi-Fi Settings > Your Network > Advanced Settings > DNS Settings**
	- Make sure you are connected to the internet
	- Make sure **Proxy Server** is set to **Do Not Use**
3. Choose **Manual**
4. Change your **Primary DNS** to `23.96.6.207`
5. Change your **Secondary DNS** to `23.96.6.207`
6. Go back to the main Settings screen
7. Go to **System > Auto-Start Settings**
8. Uncheck **Download Update File for System Software**
6. Go back to the main Settings screen
7. Select **System Update > Update Using Wi-Fi**
8. Be absolutely certain that the message says “3.65”
9. Update your system to 3.65

---
[Blocking Updates](/guide/blocking-updates){: .btn .btn--light-outline}
{: style="text-align: center;"}
