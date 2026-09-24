---
title: Adobe Analytics 1.4 API生命周期终止
description: Adobe Analytics 1.4 API和WSSE身份验证于2026年8月31日停止使用。 了解受影响的内容以及如何迁移到Analytics 2.0 API。
source-git-commit: 4056ba0953e81a279d25b15449c7b41a4a5eb7f9
workflow-type: tm+mt
source-wordcount: '743'
ht-degree: 1%
---
# Adobe Analytics 1.4 API生命周期终止

自&#x200B;**2026年8月31日**&#x200B;起，Adobe已停用Adobe Analytics 1.4 API和WSSE身份验证。 不再可访问使用此版本API的所有端点，并且基于该API构建的集成已停止工作。

Adobe Analytics 1.4 API提供了一系列操作，例如报表、分类、数据馈送、区段、计算量度、数据源和报表包配置。 它们已被[Adobe Analytics 2.0 API](https://developer.adobe.com/analytics-apis/docs/2.0)取代，该API允许您执行Adobe Analytics用户界面中提供的几乎任何操作，包括报表和管理组件，如区段和计算量度。 如果您的集成仍需要升级，请按照[迁移到Adobe Analytics 2.0 API](https://developer.adobe.com/analytics-apis/docs/2.0/guides/migration)指南操作。

## 生命周期终止的内容

此生命周期终止将直接影响以下1.4 API功能。 将每个受影响的工作流迁移到[Adobe Analytics 2.0 API](https://developer.adobe.com/analytics-apis/docs/2.0)：

* 报表（包括Data Warehouse、实时报表、路径报表和摘要报表）
* 报表包配置和管理
* 分类
* 区段
* 计算量度
* 数据源
* 数据馈送
* 书签和公司（端点）方法

它还弃用&#x200B;**Adobe Analytics WSSE身份验证**（请参阅下面的[WSSE身份验证](#wsse-authentication)）。

>[!IMPORTANT]
>
>此生命周期结束&#x200B;*不会*&#x200B;影响您的数据收集。 标记（以前称为Adobe Launch）、Web SDK和AppMeasurement等标记解决方案不受影响。 [数据插入API](#data-insertion-api)也&#x200B;*不是*&#x200B;已弃用。 但是，如果您使用1.4数据源或分类API来增强数据，则必须将这些工作流迁移到Adobe Analytics 2.0 API。

## WSSE身份验证

WSSE身份验证是Analytics 1.4 API支持的旧版身份验证协议。 已由[Adobe Developer Console](https://developer.adobe.com/console/home)中提供的基于OAuth的身份验证选项取代。 使用WSSE身份验证的项目必须将其凭据更新为Adobe Developer Console中设置的凭据。

要迁移，请登录到[Adobe Developer Console](https://developer.adobe.com/console/home)并为Analytics 2.0 API集成创建项目。 选择&#x200B;**OAuth用户**&#x200B;或&#x200B;**OAuth服务器到服务器**&#x200B;身份验证方法。

## 数据插入 API

数据插入API是此生命周期结束的&#x200B;**而非**&#x200B;部分。 其文档与其他服务器端收集方法一起移至[Adobe Analytics数据收集API](https://developer.adobe.com/analytics-collection-apis/)网站：

* [数据插入API](https://developer.adobe.com/analytics-collection-apis/methods/data-insertion/)：以查询字符串（图像请求）或XML `POST`的形式一次发送一次点击的事件数据。
* [批量数据插入API](https://developer.adobe.com/analytics-collection-apis/methods/bulk-data-insertion/)：将服务器调用数据的批量上传为文件。 Adobe建议将Bulk Data Insertion API用于新服务器端实施。

## 常见问题

+++这是否会影响我用于Analytics API的现有Adobe Developer项目？

任何使用Analytics 1.4 API的现有项目都会受到影响。 必须将这些集成迁移到[Adobe Analytics 2.0 API](https://developer.adobe.com/analytics-apis/docs/2.0/)。

+++

+++我已与使用Adobe API的其他产品或应用程序共享我的Analytics凭据。 他们是否会受到影响？

如果该产品或应用程序使用您的WSSE凭据或调用Analytics 1.4 API，则它将受到影响，必须迁移。 请联系产品或应用程序提供商，以了解其迁移计划和时间线的详细信息。

+++

+++如何确定我的项目使用哪个API？

项目调用的基本URL决定了它使用的API版本。 Adobe Analytics 1.4 API使用以下基本URL：

* `https://api.omniture.com`
* `https://api3.omniture.com`
* `https://api4.omniture.com`
* `https://api5.omniture.com`

[Adobe Analytics 2.0 API](https://developer.adobe.com/analytics-apis/docs/2.0/)使用以下基本URL：

* `https://analytics.adobe.io`

如果任何API项目调用`api*.omniture.com`，则它们会使用已弃用的Adobe Analytics 1.4 API，并且必须迁移到2.0 API。

+++

+++此生命周期结束是否会影响数据收集？

没有。 此生命周期结束&#x200B;**不会**&#x200B;影响直接数据收集，如Tags、Web SDK、AppMeasurement或数据插入API。 但是，如果您使用1.4数据源或分类API来增强数据，则必须将这些工作流迁移到Adobe Analytics 2.0 API。

+++

如果您对于本页未回答的此生命周期结束有其他问题，请联系您的Adobe客户团队。
