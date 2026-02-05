---
title: 隐藏测试
description: 这是隐藏测试
hide: true
hidefromtoc: true
landing-page-breadcrumb-title: Test AEM 6.5
landing-page-name: experience-manager-65
feature: Annotations
hold: true
exl-id: e6e5ba1c-98a5-4d7d-9913-426df31bc7a3
source-git-commit: 32b9cb0dd618b9cb97b22e54e17d05f75f3c51fa
workflow-type: tm+mt
source-wordcount: '219'
ht-degree: 9%

---

# 隐藏测试

2026年2月4日 — `hold: true`启用。
测试新密钥

这是一个隐藏的测试。 我正在添加此`[`以确保它在v2渲染中正常工作！

## 在新选项卡中打开 {#section_92882928}

`[See What's new](auditor.md) {target="_blank"}`

[在同一选项卡中打开](auditor.md)

[带引号空格的新选项卡](auditor.md) {target="_blank"}

[带有锚点的新选项卡](auditor.md){target=&quot;_blank}

[带引号的新制表符](auditor.md){target="_blank"}

[新制表符，空格不含引号](auditor.md) {target=_blank}

[不带引号的新制表符](auditor.md){target=_blank}

[带有深层链接的新选项卡](commerce-channels.md#channel-manager-extension){target="_blank"}

[将新选项卡与深层链接定位在一起](https://experienceleague.adobe.com/en/docs/analytics/analyze/home#key-analytics-resources){target="_blank"}

[带有外部链接的新选项卡](https://www.adobe.com){target="_blank"}

[新建选项卡根链接](/help/guide-1/auditor.md){target="_blank"}


<table>
  <tr>
    <th>带引号</a></th>
    <th>不带引号</th>
  </tr>
  <tr>
    <td><a href="https://www.adobe.com" target="_blank">Adobe新选项卡</a></td>
    <td><a href="https://www.adobe.com" target="_blank">Adobe新选项卡</td>
  </tr>
  <tr>
    <td><a href="https://www.adobe.com">Adobe无新选项卡</a></td>
    <td><a href="https://www.adobe.com">Adobe无新选项卡</td>
  </tr>
</table>

## 评论测试

2025年11月18

<!-- ## Comment with basic text

This is a new line.

Second new line. -->


注释如下。 如果这是您在本文中看到的最后一件事，则是由注释语法造成的。

1. 单击&#x200B;**[!UICONTROL 创建]**。

<!-- ## Create an exclusion using Advanced Search

You can also create exclusions using [!UICONTROL Advanced Search] on the [Catalog Search](/help/main/c-recommendations/c-products/catalog-search.md#save-as) page ( [!UICONTROL Recommendations] > [!UICONTROL Catalog Search] > [!UICONTROL Advanced Search]). 

![Save as dialog](/help/main/c-recommendations/c-products/assets/save-as.png)

After creating a search using "id > contains," for example, you can then click [!UICONTROL Save As] > [!UICONTROL Exclusion].

>[!IMPORTANT]
>
>The [!UICONTROL Advanced Search] functionality is case-insensitive; however, products returned at the time of delivery are based on case-sensitive search. This mismatch might lead to confusion. Ensure that you consider case-sensitivity when you create exclusions based on results using the Advanced Search functionality. For example, if you perform a search for "Holiday," that initial search lists results containing "Holiday" and "holiday." If you then create an exclusion with the intent to exclude products containing "holiday," only products containing "holiday" are excluded. Products containing "Holiday" are not excluded. -->

此行在注释之后。

## 视频测试

### 纯视频无成绩单 — 应显示成绩单，因为metadata.md会向下滴流

>[!VIDEO](https://video.tv.adobe.com/v/332116?hidetitle=true)

### 成绩单设置为true

>[!VIDEO](https://video.tv.adobe.com/v/332116?hidetitle=true){transcript=true}

### 成绩单设置为false — 视频成绩单不应显示

>[!VIDEO](https://video.tv.adobe.com/v/332116?hidetitle=true){transcript=false}

## 相对链接

* [概述](overview.md)
* [Search和Promote](search-promote.md)
* [社交](social.md)

## 显式深层链接

[其他概述(root)](/help/guide-1/overview.md#additional-products)

[其他概述](overview.md#additional-products)

## 悬停文本测试 {#this-is-a-heading-anchor}

无悬停文本

```
![alt text](assets/maui-flip.jpg)
```

![替换文本](assets/maui-flip.jpg)


是悬停文本

```
![alt text](assets/maui-flip.jpg "Hover text")
```

![替换文本](assets/maui-flip.jpg "悬停文本")

## 幻灯片

语法：

```
>[!SLIDE](analyze-project)
https://experienceleague-stage.adobe.com/en/slides/analyze-project
```

已渲染：

<!--
>[!SLIDE](analyze-project)
-->

Bob：测试主题位置内容后，请删除幻灯片评论。
