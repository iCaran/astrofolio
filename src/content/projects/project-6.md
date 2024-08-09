---
title: 'DeBloater'
description: 'A debloating script for Android devices which does not require root, along with a curated list of packages for a certain handset.'
image:
    url: '/110939d3-724c-4235-83e3-9d420dff5976.webp'
    alt: 'ai'
worksImage1:
    url: '/1.png'
    alt: 'shell'
worksImage2:
    url: '/110939d3-724c-4235-83e3-9d420dff5976.webp'
    alt: 'ai'
platform: Web
stack: Bash, ADB
website: https://bb.chip.icu/d/56-an-android-debloater-tool-general-poco-c31miui-125
github: https://github.com/iCaran/poco_debloat
---

Phones in general these days are extremely bloated with what is essentially just spyware, even the 'feature/dumb phones' come with some Facebook/Google unnecessities installed. I recently bought a cheap POCO device (C31) and was annoyed at the sheer level of what is essentially trash that came with it which I simply don't need. At first, I simply tried to uninstall everything willy-nilly and ended up with an annoying boot loop. This led me to find out that OEM ROMs will simply refuse to work if you try to go absolute 'tinfoil' on them, so I extracted the list of all the packages on my device adb shell pm list packages, and searched every single one to find the limit of what can and cannot be removed or deactivated. The result of that is the lists folder in this repo. For advanced users who want to go beyond the 'safe method' (see below), I advise them to read through the lists or make one of their own, put it in a txt file and run the script.bat. If you choose to do so, see sources.txt in the lists folder for some useful resources for finding out info on most packages easily.