---
title: "Building a Notifications client with Xamarin and Azure: Adding the Azure Functions endpoint - Part 3"
author: Frank Boucher
date: 2020-08-03
draft: true
image: 2020-08-03-Laurent-Bugnion_Part3.jpg
---

#### 📺 021 - Laurent Bugnion 🎙️ Frank Boucher

<!--more-->

{{< video "3kihzhNbjCY" >}}

---

In our last episode, we configured the Windows application to receive notifications, and we created the Azure Notification Hub which is the central piece of our notification system. We ended the session by testing sending a notification to the Windows application.

However we ran out of time and couldn't finish adding the Android application to the Notification Hub. This will be the start of this session.

After this is complete and tested, we will add the Azure Functions endpoint. This HTTP endpoint will be the point of entry to the whole system, and will make it easy to send push notifications to your own devices from any long running system such as logic apps, other Azure Functions, websites, server-side activities like video encoding etc. This will all be done from Visual Studio (the super powerful IDE for Windows).

---

### Useful Links

🔗 [Windows Push Notification Services](https://docs.microsoft.com/en-us/windows/uwp/design/shell/tiles-and-notifications/windows-push-notification-services--wns--overview?WT.mc_id=allaroundazure-blog-lbugnion)

🔗 [Notification Hubs Windows Store .NET Get Started Push Notifications](https://docs.microsoft.com/en-us/azure/notification-hubs/?WT.mc_id=allaroundazure-blog-lbugnion)

🔗 [Azure Notification Hubs](https://docs.microsoft.com/en-us/azure/notification-hubs/?WT.mc_id=allaroundazure-blog-lbugnion)

🔗 [Create Notification Hub Portal](https://docs.microsoft.com/en-us/azure/notification-hubs/create-notification-hub-portal?WT.mc_id=allaroundazure-blog-lbugnion)

🔗 [Notification Hubs](https://azure.microsoft.com/en-us/services/notification-hubs/?WT.mc_id=allaroundazure-blog-lbugnion)

🔗 [Notification Hubs Pricing](https://azure.microsoft.com/en-us/pricing/details/notification-hubs/?WT.mc_id=allaroundazure-blog-lbugnion)

🔗 [Badges](https://docs.microsoft.com/en-us/windows/uwp/design/shell/tiles-and-notifications/badges?WT.mc_id=allaroundazure-blog-lbugnion)

🔗 [Adaptive Interactive Toasts](https://docs.microsoft.com/en-us/windows/uwp/design/shell/tiles-and-notifications/adaptive-interactive-toasts?WT.mc_id=allaroundazure-video-lbugnion)


### Learn more about Laurent Bugnion

🔗 [@LBugnion](https://twitter.com/lbugnion)

🔗 [Bio](https://developer.microsoft.com/en-us/advocates/laurent_bugnion)

<br />

☁️
