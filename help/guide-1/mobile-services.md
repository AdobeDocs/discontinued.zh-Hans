---
title: Adobe Mobile Services 终止使用常见问题
description: 获取有关 Adobe Mobile Services 终止使用公告的常见问题的解答。
exl-id: c5f44341-7b87-4530-b86e-17e2911a7959
source-git-commit: 343e0a727c570c9eec503d7903d0477134fc6189
workflow-type: ht
source-wordcount: '421'
ht-degree: 100%

---

# Adobe Mobile Services 终止使用常见问题

Adobe Mobile Services 的终止使用日期为 **2022 年 12 月 31 日**。

## 发生了什么情况？

Mobile Services 已于 2022 年 12 月 31 日终止使用。在此日期之后，支持以 Mobile 为中心的 UI、客户获取、深度链接、应用程序内消息传递、推送通知和地理位置的 Mobile Services 不再受支持。

## 包含哪些内容，不包含哪些内容？

本次终止使用仅包括 Adobe Mobile Services，即 [mobilemarketing.adobe.com](https://mobilemarketing.adobe.com) 上的独立平台。依赖此接口的 Mobile 版本 4 SDK 已于 2021 年 8 月 31 日失效。

本次终止使用不包括适用于移动应用程序的 Adobe Analytics，它是 Adobe Experience Platform Mobile SDK 的一部分。Adobe 将继续为这些功能（包括应用程序内行为、生命周期分析、消息交互跟踪和受众配置文件）提供支持。

## 为什么停用该功能？

随着 Adobe 不断扩展其移动营销功能，以前在 Mobile Services 中提供的功能将在 Adobe Experience Cloud 解决方案中发布或通过 Adobe Exchange 首选合作伙伴提供。这一过渡为您提供了更强大、更灵活的移动营销功能。

## 在 Mobile Services 中创建的现有处理规则会发生什么情况？

在 Mobile Services UI 中创建或生成的[处理规则](https://experienceleague.adobe.com/docs/analytics/admin/admin-tools/processing-rules/processing-rules.html?lang=zh-Hans)将在 Mobile Services 终止使用日期之前自动迁移到 Adobe Analytics。迁移的处理规则的行为方式与 Adobe Analytics 中的其他处理规则类似，您可以随意查看或编辑它们。此迁移无需用户执行任何操作。

Mobile Services 失效后，所有处理规则逻辑将在 Adobe Analytics 内专门处理，通常包括使用[上下文数据变量](https://experienceleague.adobe.com/docs/analytics/implementation/vars/page-vars/contextdata.html?lang=zh-Hans)。

## 提供了哪些过渡选项？

Adobe 根据您组织的用例提供了三个过渡路径。

1. **应用程序内消息传递和推送通知**：Adobe 可以将您的消息传递工作流转换为 Adobe Journey Optimizer。该产品可帮助组织优化和个性化整个客户历程（包括移动消息传递）中的体验。
1. **客户获取和深度链接**：通过 Adobe Exchange 首选合作伙伴计划提供客户获取和深度链接。Adobe 的合作关系团队会做适当的介绍，确保您找到最能满足需求的解决方案。
1. **Places Service**：Places Service 提供免费的地理位置功能。请参阅 [Places Service 文档](https://experienceleague.adobe.com/docs/places/using/home.html?lang=zh-Hans)。

## 如果我有疑问，可以在何处寻求帮助？

请参阅 [Adobe Mobile Services 终止使用 Spark 页面](https://spark.adobe.com/page/C6D30y09zaRpD/)以了解更多信息。如有任何其他问题，请联系您的 Adobe 代表。
