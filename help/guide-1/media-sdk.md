---
title: Adobe Media SDK（版本1.x和2.x）生命周期终止常见问题解答
description: 获取有关Adobe Media SDK版本1.x和2.x（以前称为视频心率库）生命周期结束的常见问题解答。
source-git-commit: d014c200dd926ccf0116faa50c4bffb1d234e926
workflow-type: tm+mt
source-wordcount: '1046'
ht-degree: 0%

---


# Adobe Media SDK（版本1.x和2.x）生命周期终止常见问题解答

Adobe Media SDK **2.x于2021年8月31日停止支持**。 视频心率库(VHL) **1.x已弃用**，并且已有几年不受支持。

## 发生了什么情况？

原始的视频心率库(VHL)（后来更名为Media SDK）为音频和视频分析提供了客户端跟踪。 Adobe已将跟踪功能转换为功能更强的新实施：

* **Media SDK 3.x （仅限Analytics）：**&#x200B;当前支持。 使用媒体收集API跟踪媒体。 建议尚未迁移到Edge Network的现有2.x用户使用。
* **适用于Edge Network的流媒体（推荐）：**&#x200B;当前推荐的实施。 使用Adobe Experience Platform Web SDK、Mobile SDK或Media Edge API通过Edge Network发送媒体数据，从而支持在Adobe Analytics、Customer Journey Analytics、Real-Time CDP和Adobe Journey Optimizer中使用。

## 生命周期终止中包括哪些内容，哪些内容未包括？

**生命周期结束（不再支持）：**

* Video Heartbeat Library (VHL) 1.x — 所有平台(Android、iOS、JavaScript、Apple TV、Chromecast、Roku、TVML)
* Media SDK 2.x — Android、iOS、JavaScript

**未结束生命周期（仍受支持）：**

* Media SDK 3.x — JavaScript、Chromecast、Roku（仅限Analytics）
* Streaming Media for Edge Network — 所有受支持的平台

## 为什么停用版本1.x和2.x？

从版本3.0开始，Media SDK经过重新设计，可直接使用媒体收集API，而无需使用委托模式并简化跟踪器的创建。 较旧的1.x和2.x SDK所依赖的心率服务器体系结构已被取代。

Adobe还引入了Edge Network实施，以便提供单个数据收集管道，该管道能够馈送旧版心率SDK无法支持的多个下游Adobe应用程序。

## 可在何处找到归档的文档？

旧版文档已存档在GitHub上，可供参考：

| 版本 | 状态 | 已存档的文档 |
|---|---|---|
| 1.x（视频心率库） | 已弃用 | [`video-heartbeat` GitHub存储库](https://github.com/Adobe-Marketing-Cloud/video-heartbeat/tree/master/docs) |
| 2.x (Media SDK) | 2021年8月31日终止支持 | [`media-sdks` GitHub存储库](https://github.com/Adobe-Marketing-Cloud/media-sdks/blob/master/docs/2.x/README.md) |

## 我的过渡选项是什么？

**选项1：迁移到Media SDK 3.x（仅限Analytics）**

如果您使用的是2.x并专门使用Adobe Analytics，则迁移到3.x是最简单的途径。 有关完整的API比较和代码示例，请参阅[2.x到3.x迁移指南](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/media-sdk/setup/migrate-js-2x-to-3x.html)。

**选项2：迁移到Edge Network的流媒体（推荐）**

对于新的实施，或者当您希望跨多个Adobe应用程序使用数据时，请使用Adobe Experience Platform Edge Network：

* [Media Edge Web SDK](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/edge/edge-web-sdk.html)
* [Media Edge Mobile SDK](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/edge/edge-mobile-sdk.html)
* [Media Edge API](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/edge/implementation-edge-api.html)

## 常见问题解答

+++**是否会影响对Roku SDK和Chromecast SDK的支持？**

没有。 Roku SDK和Chromecast SDK仍作为Media SDK 3.x（仅限Analytics）的一部分提供和支持。 此生命周期终止仅涵盖1.x和2.x版本。

+++

+++**Media Analytics JavaScript SDK实施是否会受到影响？**

没有。 使用JavaScript SDK for Media Analytics的客户可以继续使用独立的SDK或标记扩展。

+++

+++**我仍在Media SDK 2.x上。 我应该怎么做？**

Adobe建议将所有新项目迁移到Edge Network实施。 如果需要中间步骤，请[从JavaScript SDK 2.x迁移到3.x](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/media-sdk/setup/migrate-js-2x-to-3x.html)，然后计划迁移到Edge Network。

+++

+++**迁移到支持的实施的工作量是多少？**

迁移工作取决于每位客户的实施，因此会有所不同。 查看迁移文档后，请咨询顾问或客户关怀团队以获得其他支持：

* [使用移动设备Edge SDK — Android和iOS实施流媒体](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/edge/edge-mobile-sdk.html)
* [从JavaScript SDK 2.x迁移到3.x](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/media-sdk/setup/migrate-js-2x-to-3x.html)

+++

+++**是否需要使用Adobe Experience Platform Tags作为标签管理系统？**

对于移动应用程序实施，Experience Platform Tags不能像用于Web一样用作标记管理系统。 配置SDK扩展需要标签UI。 这与使用Adobe Mobile Services UI配置Mobile v4 SDK的方式相似。 标记会根据您选择的扩展提供自定义的安装说明。

+++

+++**终止支持是否会影响适用于tvOS的SDK？**

是的。 对于tvOS（版本10+），建议的实施是使用Adobe Experience Platform Mobile SDK迁移到适用于Edge Network的流媒体。 有关详细信息，请参阅[使用Mobile Edge SDK实施流媒体](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/edge/edge-mobile-sdk.html)。

+++

+++**终止支持是否会影响Fire TV和Android TV的SDK？**

是的。 对于Fire TV和Android TV，建议的实施是使用Adobe Experience Platform Mobile SDK迁移到Streaming Media for Edge Network。 有关详细信息，请参阅[使用Mobile Edge SDK实施流媒体](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/edge/edge-mobile-sdk.html)。

+++

+++**在哪里可以找到Mobile v4 SDK的生命周期结束信息？**

请参阅[Mobile Services生命周期结束常见问题解答](mobile-services.md)。 Mobile Services平台和Mobile v4 SDK于2022年12月31日停止服务。

+++

+++**如果有任何问题，我可以前往何处？**

请联系您的Adobe客户团队或Adobe客户关怀团队，以获取迁移帮助。

+++

>[!MORELIKETHIS]
>
>* [流媒体实施概述](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/overview.html)
>* [Edge Network流媒体](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/edge/implementation-edge.html)
>* [Media SDK 3.x — JavaScript设置](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/media-sdk/setup/web-implementation.html)
