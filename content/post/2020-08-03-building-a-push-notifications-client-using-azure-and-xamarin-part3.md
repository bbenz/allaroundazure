---
title: "Building a Notifications client with Xamarin and Azure: Adding the Azure Functions endpoint - Part 3"
author: Frank Boucher
date: 2020-08-03
draft: false
image: 2020-08-03-Laurent-Bugnion_Part3.jpg
---

#### 📺 021 - Laurent Bugnion 🎙️ Frank Boucher

<!--more-->

{{< video "3kihzhNbjCY" >}}

🔗 [@LBugnion](https://twitter.com/lbugnion)
🔗 [Bio](https://developer.microsoft.com/en-us/advocates/laurent_bugnion)

---

In our last episode, we configured the Windows application to receive notifications, and we created the Azure Notification Hub which is the central piece of our notification system. We ended the session by testing sending a notification to the Windows application. 
However we ran out of time and couldn't finish adding the Android application to the Notification Hub. This will be the start of this session.

After this is complete and tested, we will add the Azure Functions endpoint. This HTTP endpoint will be the point of entry to the whole system, and will make it easy to send push notifications to your own devices from any long running system such as logic apps, other Azure Functions, websites, server-side activities like video encoding etc. This will all be done from Visual Studio (the super powerful IDE for Windows).

---

### Useful Links

🔗 

☁️