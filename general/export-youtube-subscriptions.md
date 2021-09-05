---
title: "Export YouTube Subscriptions"
description: "Invidious's Export YouTube Subscriptions documentation."
lead: "Invidious's Export YouTube Subscriptions documentation."
date:
lastmod:
draft: false
images: []
menu:
  docs:
    parent: "general"
weight: 100
toc: true
---

**The steps below as well as the resulting file name are different depending on your Google language 
settings.**

1. Open [Google Takeout](https://takeout.google.com/takeout/custom/youtube).
2. Under `Create a new export` choose `YouTube and YouTube Music`.
3. Click on `All YouTube data included` and only tick `subscriptions` in the dialog that opens.
4. Click on `Next step`, make sure `Export once` is chosen and click on `Create export`.
5. Wait until the export creation is finished, then on the same page click on `Download` under  
   `Your latest export` that should now be visible.
6. Extract the downloaded archive and find the file `subscriptions.json`.
7. While logged into your Invidious account go to Subscriptions -> Manage Subscriptions -> 
   Import/Export -> Import YouTube subscriptions, select the file you just downloaded and click on 
   `Import`.
