---
keywords: Adobe experience cloud；Adobe Experience Cloud；device co-op；Device Co-op；生命周期结束
title: “[!DNL Device Co-op] 生命周期结束常见问题解答”
description: 了解 Device Co-op 的生命周期结束计划。
exl-id: 015ba95c-0c8d-415e-969c-b8670494de98
source-git-commit: 180dd414dd0b595518f54cddc5b02ed06ecc0b16
workflow-type: tm+mt
source-wordcount: '1138'
ht-degree: 95%

---

# [!DNL Device Co-op] 生命周期结束常见问题解答

本文档提供有关 [!DNL Adobe Experience Cloud Device Co-op] 生命周期结束 (EOL) 计划的常见问题解答。 当该计划生效时，Adobe 将在 [Experience Cloud 发行说明](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html)和[优先产品更新](https://www.adobe.com/subscription/priority-product-update.html)中提供提前通知。

[!DNL Device Co-op] 是一个让参与者共同努力以更好地识别跨数字接触点的消费者的计划，同时确保最高水平的隐私和透明度。

## 常见问题解答

以下是有关 [!DNL Device Co-op] EOL 计划的常见问题解答列表。

## 为什么 [!DNL Device Co-op] 被弃用？

AdTech 环境即将发生的更改预计将导致 [!DNL Device Co-op] 在未来几年成为过时的解决方案。 [!DNL Device Co-op] 主要由第三方 cookie 组成，而 [!DNL Google's] 宣布他们将在 2022 年之前在 [!DNL Google Chrome] 上阻止第三方 cookie 将降低 [!DNL Device Co-op] 的有效性。 [!DNL Chrome] 拥有约 65% 的浏览器市场份额，其他主要浏览器已经实施了对第三方 cookie 的阻止。 一旦 [!DNL Chrome] 阻止第三方 cookie，大部分第三方 cookie 将被阻止，[!DNL Device Co-op] 将被废弃。

## 为什么 Adobe 现在结束 [!DNL Device Co-op] 注册？

注册即将结束，以防止由于第三方 cookie 即将发生的行业更改而导致无法满足客户期望的风险。 [!DNL Device Co-op] 需要几个月的时间来准备，另外几个月的时间来从服务中提取价值。此时任何进一步的注册都可能导致品牌无法体验到 [!DNL Device Co-op] 的全部价值。

## 2022 年 7 月，Google 宣布将 Chrome 上的第三方 cookie 弃用推迟到 2024 年。 这会影响到 [!DNL Device Co-op] EOL 计划？

不，Adobe 的 [!DNL Device Co-op] EOL 计划将继续保持不变，不会延长。

## 新客户可以注册吗？

自 2021 年 6 月 11 日起，Adobe 将不再接受新的注册 [!DNL Device Co-op]。

## 现有合同是否续订？

自 2021 年 6 月 11 日起，Adobe 将不再续订 [!DNL Device Co-op] 合同。 如果您想继续使用 [!DNL Device Co-op] 服务，您可以根据当前的许可条款继续这样做，直到项目结束。

## [!DNL Device Co-op] 项目的确切结束日期是什么时候？

[!DNL Device Co-op] 项目将于 2022 年结束。 具体时间和日期取决于何时 [!DNL Google] 开始阻止第三方 cookie。 退役工作预计将于 2022 年 9 月开始。

## 哪些应用程序会受到 Device Co-op 生命周期结束的影响？

以下应用程序将受到 [!DNL Device Co-op] 生命周期终止程序的影响：

- [[!DNL Adobe Analytics]](https://experienceleague.adobe.com/docs/analytics.html?lang=en)
- [[!DNL Adobe Audience Manager]](https://experienceleague.adobe.com/docs/audience-manager/user-guide/overview/aam-overview.html?lang=en)
- [[!DNL Adobe Advertising Cloud]](https://experienceleague.adobe.com/docs/advertising-cloud.html?lang=en)
- [[!DNL Adobe Target]](https://experienceleague.adobe.com/docs/target/using/introduction/intro.html?lang=en)

## 我有哪些选择可以替代 [!DNL Device Co-op]？

### [!DNL Analytics]

您可以使用[!DNL Analytics][跨设备分析 (CDA)](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html) 功能，因为它同时支持 Adobe Experience Platform 标识服务[专用图形](https://experienceleague.adobe.com/docs/analytics/components/cda/device-graph.html?lang=en)和[基于字段的拼接](https://experienceleague.adobe.com/docs/analytics/components/cda/field-based-stitching.html?lang=en)。

### [!DNL Audience Manager]

[!DNL Audience Manager] 维护与第三方设备图形合作伙伴的集成，包括 [!DNL LiveRamp] 和 [!DNL Tapad]，尽管您必须直接与图形合作伙伴建立商业关系，才能利用 [!DNL Audience Manager]。所有客户都应更新任何合作个人资料合并规则以使用除 [!DNL Device Co-op.] 之外的任何选项

### [!DNL Real-time Customer Data Platform]

没有计划修改当前 [!DNL Audience Manager Data Management Platform] (DMP)。 但是，第三方 cookie 的弃用可能会给大多数 DMP 用户带来规模挑战。 为了帮助客户改进他们的数据管理实践，Adobe 鼓励减少对标识符的依赖，这些标识符将在来年面临限制。 营销团队必须建立第一方数据策略，重点关注包括个人身份信息 (PII) 在内的持久标识符，这可以通过 [!DNL Real-time Customer Data Platform]（实时 CDP）来解决。

[!DNL Real-time CDP] 通过扩展可用于创建受众的标识符集以包括 PII，减少对第三方 cookie 和设备 ID 的依赖。 [!DNL Real-time CDP] 的基础是实时客户档案，它将个人属性数据与行为数据实时结合在一起，并允许营销人员通过获得专利的数据治理控制来创建丰富的受众区段。 与 [!DNL Audience Manager] 一样，[!DNL Real-time CDP] 提供洞察力和个性化用例，同时产生更细化的个人层面洞察力，并可以将受众激活到更广泛的目标，包括广告技术和营销技术，包括付费媒体、社交媒体、电子邮件和客户系统。

[!DNL Real-time CDP] 还将包括访问 [Adobe Experience Platform 区段匹配 (Beta)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match/overview.html?lang=en)，这使品牌可以通过合作伙伴关系扩展自己的第一方数据集，并获得更好的洞察力和个性化。

### [!DNL Target]

目前没有可用于 [!DNL Target] 的替代方案，因为 [!DNL Target] 提供了一种称为 `mbox3rdPartyId` 的确定性跨设备标识拼接功能，其功能类似于 Adobe 的客户 ID。此功能允许[!DNL Target]客户在入站渠道中完成[!DNL Target]测试和个性化合并个人资料和活动参与。

### Adobe Advertising Cloud

[!DNL Advertising Cloud] 客户将无法再使用 [!DNL Device Co-op] 用于跨设备受众定位和量度。 使用 [!DNL Advertising Cloud]，您仍然可以利用 Adobe 与 [!DNL LiveRamp] 的 [!DNL Device Graph] 合作伙伴关系，在 [!DNL LiveRamp's] 能力和规模的范围内继续执行这些功能。 您必须让使用 [!DNL Device Co-op] 的营销活动结束，然后切换到 [!DNL LiveRamp] 设备图形提供程序，或者不再利用基于人员的定位。

## 哪些现有功能和实施可以帮助我为无 cookie 的未来做好准备？

您现有的访客 ID 服务实施为 Analytics [CDA](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html) 提供支持。 如果您现有的声明 ID 是经过哈希处理的电子邮件，则可用于支持以下功能：

- [!DNL Audience Manager] [以人为本的目标](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html)。
- [Experience Platform 区段匹配 (Beta)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match/overview.html?lang=en)。

## 我可以保留我的数据吗[!DNL Device Co-op]？

对于 [!DNL Audience Manager] 和 [!DNL Advertising Cloud] 用户，来自 [!DNL Device Co-op] 的数据将无法传输到第三方图表。 [!DNL Device Co-op] 数据只会为 [!DNL Analytics Ultimate] 用户使用 CDA 迁移，[!DNL Device Co-op] 切换到基于字段的拼接。 所有其他解决方案都不会迁移其数据。

## 是否必须采用其他功能？

虽然采用其他 Adobe 功能不是强制性的，但您应该尽快开始实施其他功能，以便在 [!DNL Device Co-op] 弃用之前留出时间和适当的协调。

## 如果我选择，我什么时候必须采用替代解决方案？

采用其他功能不是强制性的。 仅当您希望继续解决 [!DNL Device Co-op] 解决的用例时，才建议您这样做。 如果您选择采用其他功能，则必须在 [!DNL Device Co-op] 项目结束前的 2022 年（具体时间待公布）之前这样做。

## 采用需要多长时间？

这将取决于功能。 例如，如果使用带有 [!DNL Device Co-op] 的跨设备分析的 Analytics Ultimate 客户需要迁移到实时专用设备图形或基于字段的拼接，则采用将需要一些时间。

## 那么 [!UICONTROL 人员] 量度？

弃用 [!DNL Device Co-op]，则 [!UICONTROL 人员] 量度不再相关。 在不久的将来（日期待定），我们将删除 [!UICONTROL 人员] 量度。 到那时，我们将其数据重定向到 [!UICONTROL 独特访客] 量度以防止项目、区段和计算量度中断。

