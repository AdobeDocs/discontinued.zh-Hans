---
title: 隐藏故障排除测试
description: 这是一个隐藏的故障排除测试
hide: true
hidefromtoc: true
source-git-commit: 388f61fa721e0fedf858634dde807baeadde06f3
workflow-type: ht
source-wordcount: '2876'
ht-degree: 100%

---

# AEM 中的故障排除


## 单行表

| AEM Sites 故障排除 |
|--- |
| + [(Dynamic Media) AEM Dynamic Media 中旋转集卡在处理状态](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26715) |
| + [AEM 中数字资产管理 (DAM) 演绎版与原始文件不一致](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26639) |
| + [AEMaaCS 中未生成智能裁剪演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26873) |
| + [(Dynamic Media) 修复 AEM 中视频上传、处理与渲染失败的问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26533) |
| + [(Asset Link) 使用 InDesign 时，Adobe Asset Link 导致链接状态不可访问](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26922) |
| + [AEMaaCS 中 Dynamic Media 与 DAM 卡片视图的视频缩略图不一致](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26677) |
| + [(Dynamic Media) 使用 API 从动态媒体导出资产和元数据](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26902) |
| + [AEM as a Cloud Service 中上传大 MP4 文件时资产处理失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26610) |
| + [(Dynamic Media) Dynamic Media 视频播放器在较低环境中无法正常工作](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26871) |
| + [（带 OpenAPI 的 Dynamic Media）根据 IMS 用户组将受限的 Assets 访问权限激活到带 Open API 的 Dynamic Media](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26103) |
| + [当 ZIP 压缩格式的 Tiff 文件上传到 AEM Assets 时，不生成演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-23916) |
| + [超过 100,000 个令牌后从大 PDF 中提取文本时 AEM 将其截断](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26785) |
| + [(Dynamic Media) 更改 DM 资产的动态媒体 URL](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-17628) |
| + [解决 AEMaaCS 中非管理员用户无法查看元数据架构的问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26655) |
| + [(Dynamic Media) Dynamic Media 中 TIFF 图像演绎版背景色变更问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26637) |
| + [AEMaaCS 资产旋转问题使后续操作不可见](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26528) |
| + [(Brand Portal) 使用 OAuth 服务器到服务器凭据激活 Brand Portal](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-22074) |
| + [(Dynamic Media) 解决 Adobe Experience Manager 6.5 Dynamic Media 中点击智能裁剪后图像无法显示的问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26367) |
| + [增加 Photoshop Firefly API 集成的单部分资产上传限制](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26450) |
| + [(Dynamic Media) 解决 AEM 环境中 PDF 文件的动态媒体资产名称差异](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26461) |
| + [某些图像在 Adobe Experience Manager (AEM) as a Cloud Service - Asset 中不显示缩略图演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26233) |
| + [(Dynamic Media) 动态媒体常规设置页面不打开](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25294) |
| + [(Dynamic Media) 通过 AEM 中的 Dynamic Media 解决视频文件中的音频问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26197) |
| + [在 AEM as a Cloud Service 中自动标记新上传的资产](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25925) |
| + [在 AEM 中从 JWT 迁移到 OAuth 后，智能标记功能不起作用](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25889) |
| + [解决 AEM Managed Services 中的共享链接问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25903) |
| + [(Brand Portal) 共享链接下载问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25771) |
| + [(Dynamic Media) AEM Dynamic Media 中的资产处理失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25607) |
| + [(Dynamic Media) Adobe Experience Manager (AEM) Dynamic Media 中的资产同步失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25885) |
| + [更新 AEM as a Cloud Service 中视频资产的自定义缩略图](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25829) |
| + [Adobe Experience Manager (AEM) Assets 中的图像元数据差异](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25828) |
| + [将资产文件夹拖放到 AEM Assets Web UI 时失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-21865) |
| + [(Brand Portal) Brand Portal 编辑器和查看器无法看到任何图像](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-20177) |
| + [(Dynamic Media) 解决 AEM as a Cloud Service 中的资产处理问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25525) |
| + [Adobe Experience Manager as a Cloud Service 中大 PDF 的文本提取限制](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25518) |
| + [(Asset Link) 解决 InDesign 中的 Adobe Experience Manager (AEM) 资产链接连接问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25562) |
| + [(Asset Link) Adobe Asset Link 插件网络错误：服务器不可到达](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25506) |
| + [(Dynamic Media) 动态媒体同步用户推荐](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25471) |

| AEM Assets 故障排除 |
|--- |
| + [AEM 中资产下载 ZIP 文件缺少演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-27140) |
| + [AEM Assets 许可证中未包含内容片段](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26616) |
| + [尽管有读取权限，但在 Assets 视图中注释受限](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26928) |
| + [(Dynamic Media) AEM Dynamic Media 中旋转集卡在处理状态](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26715) |
| + [AEM 中数字资产管理 (DAM) 演绎版与原始文件不一致](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26639) |
| + [AEMaaCS 中未生成智能裁剪演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26873) |
| + [(Dynamic Media) 修复 AEM 中视频上传、处理与渲染失败的问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26533) |
| + [(Asset Link) 使用 InDesign 时，Adobe Asset Link 导致链接状态不可访问](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26922) |
| + [AEMaaCS 中 Dynamic Media 与 DAM 卡片视图的视频缩略图不一致](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26677) |
| + [(Dynamic Media) 使用 API 从动态媒体导出资产和元数据](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26902) |
| + [AEM as a Cloud Service 中上传大 MP4 文件时资产处理失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26610) |
| + [(Dynamic Media) Dynamic Media 视频播放器在较低环境中无法正常工作](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26871) |
| + [（带 OpenAPI 的 Dynamic Media）根据 IMS 用户组将受限的 Assets 访问权限激活到带 Open API 的 Dynamic Media](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26103) |
| + [当 ZIP 压缩格式的 Tiff 文件上传到 AEM Assets 时，不生成演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-23916) |
| + [超过 100,000 个令牌后从大 PDF 中提取文本时 AEM 将其截断](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26785) |
| + [(Dynamic Media) 更改 DM 资产的动态媒体 URL](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-17628) |
| + [解决 AEMaaCS 中非管理员用户无法查看元数据架构的问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26655) |
| + [(Dynamic Media) Dynamic Media 中 TIFF 图像演绎版背景色变更问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26637) |
| + [AEMaaCS 资产旋转问题使后续操作不可见](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26528) |
| + [(Dynamic Media) 解决 Adobe Experience Manager 6.5 Dynamic Media 中点击智能裁剪后图像无法显示的问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26367) |
| + [增加 Photoshop Firefly API 集成的单部分资产上传限制](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26450) |
| + [(Dynamic Media) 解决 AEM 环境中 PDF 文件的动态媒体资产名称差异](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26461) |
| + [某些图像在 Adobe Experience Manager (AEM) as a Cloud Service - Asset 中不显示缩略图演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26233) |
| + [(Dynamic Media) 动态媒体常规设置页面不打开](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25294) |
| + [(Dynamic Media) 通过 AEM 中的 Dynamic Media 解决视频文件中的音频问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26197) |
| + [在 AEM as a Cloud Service 中自动标记新上传的资产](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25925) |
| + [在 AEM 中从 JWT 迁移到 OAuth 后，智能标记功能不起作用](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25889) |
| + [解决 AEM Managed Services 中的共享链接问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25903) |
| + [(Dynamic Media) AEM Dynamic Media 中的资产处理失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25607) |
| + [(Dynamic Media) Adobe Experience Manager (AEM) Dynamic Media 中的资产同步失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25885) |
| + [更新 AEM as a Cloud Service 中视频资产的自定义缩略图](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25829) |
| + [Adobe Experience Manager (AEM) Assets 中的图像元数据差异](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25828) |
| + [将资产文件夹拖放到 AEM Assets Web UI 时失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-21865) |
| + [(Dynamic Media) 解决 AEM as a Cloud Service 中的资产处理问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25525) |
| + [Adobe Experience Manager as a Cloud Service 中大 PDF 的文本提取限制](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25518) |
| + [(Asset Link) 解决 InDesign 中的 Adobe Experience Manager (AEM) 资产链接连接问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25562) |
| + [(Asset Link) Adobe Asset Link 插件网络错误：服务器不可到达](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25506) |
| + [(Dynamic Media) 动态媒体同步用户推荐](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25471) |

| AEM Forms 故障排除 |
|--- |
| + [(Dynamic Media) AEM Dynamic Media 中旋转集卡在处理状态](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26715) |
| + [AEM 中数字资产管理 (DAM) 演绎版与原始文件不一致](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26639) |
| + [AEMaaCS 中未生成智能裁剪演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26873) |
| + [(Dynamic Media) 修复 AEM 中视频上传、处理与渲染失败的问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26533) |
| + [(Asset Link) 使用 InDesign 时，Adobe Asset Link 导致链接状态不可访问](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26922) |
| + [AEMaaCS 中 Dynamic Media 与 DAM 卡片视图的视频缩略图不一致](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26677) |
| + [(Dynamic Media) 使用 API 从动态媒体导出资产和元数据](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26902) |
| + [AEM as a Cloud Service 中上传大 MP4 文件时资产处理失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26610) |
| + [(Dynamic Media) Dynamic Media 视频播放器在较低环境中无法正常工作](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26871) |
| + [（带 OpenAPI 的 Dynamic Media）根据 IMS 用户组将受限的 Assets 访问权限激活到带 Open API 的 Dynamic Media](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26103) |
| + [当 ZIP 压缩格式的 Tiff 文件上传到 AEM Assets 时，不生成演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-23916) |
| + [超过 100,000 个令牌后从大 PDF 中提取文本时 AEM 将其截断](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26785) |
| + [(Dynamic Media) 更改 DM 资产的动态媒体 URL](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-17628) |
| + [解决 AEMaaCS 中非管理员用户无法查看元数据架构的问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26655) |
| + [(Dynamic Media) Dynamic Media 中 TIFF 图像演绎版背景色变更问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26637) |
| + [AEMaaCS 资产旋转问题使后续操作不可见](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26528) |
| + [(Brand Portal) 使用 OAuth 服务器到服务器凭据激活 Brand Portal](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-22074) |
| + [(Dynamic Media) 解决 Adobe Experience Manager 6.5 Dynamic Media 中点击智能裁剪后图像无法显示的问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26367) |
| + [增加 Photoshop Firefly API 集成的单部分资产上传限制](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26450) |
| + [(Dynamic Media) 解决 AEM 环境中 PDF 文件的动态媒体资产名称差异](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26461) |
| + [某些图像在 Adobe Experience Manager (AEM) as a Cloud Service - Asset 中不显示缩略图演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26233) |
| + [(Dynamic Media) 动态媒体常规设置页面不打开](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25294) |
| + [(Dynamic Media) 通过 AEM 中的 Dynamic Media 解决视频文件中的音频问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26197) |
| + [在 AEM as a Cloud Service 中自动标记新上传的资产](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25925) |
| + [在 AEM 中从 JWT 迁移到 OAuth 后，智能标记功能不起作用](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25889) |
| + [解决 AEM Managed Services 中的共享链接问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25903) |
| + [(Brand Portal) 共享链接下载问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25771) |
| + [(Dynamic Media) AEM Dynamic Media 中的资产处理失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25607) |
| + [(Dynamic Media) Adobe Experience Manager (AEM) Dynamic Media 中的资产同步失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25885) |
| + [更新 AEM as a Cloud Service 中视频资产的自定义缩略图](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25829) |
| + [Adobe Experience Manager (AEM) Assets 中的图像元数据差异](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25828) |
| + [将资产文件夹拖放到 AEM Assets Web UI 时失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-21865) |
| + [(Brand Portal) Brand Portal 编辑器和查看器无法看到任何图像](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-20177) |
| + [(Dynamic Media) 解决 AEM as a Cloud Service 中的资产处理问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25525) |
| + [Adobe Experience Manager as a Cloud Service 中大 PDF 的文本提取限制](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25518) |
| + [(Asset Link) 解决 InDesign 中的 Adobe Experience Manager (AEM) 资产链接连接问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25562) |
| + [(Asset Link) Adobe Asset Link 插件网络错误：服务器不可到达](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25506) |
| + [(Dynamic Media) 动态媒体同步用户推荐](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25471) |

## 三列表

| AEM Sites 故障排除 | AEM Assets 故障排除 | AEM Forms 故障排除 |
|--- |--- |--- |
| + [(Dynamic Media) AEM Dynamic Media 中旋转集卡在处理状态](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26715) | + [AEM 中资产下载 ZIP 文件缺少演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-27140) | + [(Dynamic Media) AEM Dynamic Media 中旋转集卡在处理状态](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26715) |
| + [AEM 中数字资产管理 (DAM) 演绎版与原始文件不一致](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26639) | + [AEM Assets 许可证中未包含内容片段](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26616) | + [AEM 中数字资产管理 (DAM) 演绎版与原始文件不一致](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26639) |
| + [AEMaaCS 中未生成智能裁剪演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26873) | + [尽管有读取权限，但在 Assets 视图中注释受限](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26928) | + [AEMaaCS 中未生成智能裁剪演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26873) |
| + [(Dynamic Media) 修复 AEM 中视频上传、处理与渲染失败的问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26533) | + [(Dynamic Media) AEM Dynamic Media 中旋转集卡在处理状态](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26715) | + [(Dynamic Media) 修复 AEM 中视频上传、处理与渲染失败的问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26533) |
| + [(Asset Link) 使用 InDesign 时，Adobe Asset Link 导致链接状态不可访问](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26922) | + [AEM 中数字资产管理 (DAM) 演绎版与原始文件不一致](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26639) | + [(Asset Link) 使用 InDesign 时，Adobe Asset Link 导致链接状态不可访问](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26922) |
| + [AEMaaCS 中 Dynamic Media 与 DAM 卡片视图的视频缩略图不一致](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26677) | + [AEMaaCS 中未生成智能裁剪演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26873) | + [AEMaaCS 中 Dynamic Media 与 DAM 卡片视图的视频缩略图不一致](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26677) |
| + [(Dynamic Media) 使用 API 从动态媒体导出资产和元数据](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26902) | + [(Dynamic Media) 修复 AEM 中视频上传、处理与渲染失败的问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26533) | + [(Dynamic Media) 使用 API 从动态媒体导出资产和元数据](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26902) |
| + [AEM as a Cloud Service 中上传大 MP4 文件时资产处理失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26610) | + [(Asset Link) 使用 InDesign 时，Adobe Asset Link 导致链接状态不可访问](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26922) | + [AEM as a Cloud Service 中上传大 MP4 文件时资产处理失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26610) |
| + [(Dynamic Media) Dynamic Media 视频播放器在较低环境中无法正常工作](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26871) | + [AEMaaCS 中 Dynamic Media 与 DAM 卡片视图的视频缩略图不一致](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26677) | + [(Dynamic Media) Dynamic Media 视频播放器在较低环境中无法正常工作](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26871) |
| + [（带 OpenAPI 的 Dynamic Media）根据 IMS 用户组将受限的 Assets 访问权限激活到带 Open API 的 Dynamic Media](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26103) | + [(Dynamic Media) 使用 API 从动态媒体导出资产和元数据](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26902) | + [（带 OpenAPI 的 Dynamic Media）根据 IMS 用户组将受限的 Assets 访问权限激活到带 Open API 的 Dynamic Media](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26103) |
| + [当 ZIP 压缩格式的 Tiff 文件上传到 AEM Assets 时，不生成演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-23916) | + [AEM as a Cloud Service 中上传大 MP4 文件时资产处理失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26610) | + [当 ZIP 压缩格式的 Tiff 文件上传到 AEM Assets 时，不生成演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-23916) |
| + [超过 100,000 个令牌后从大 PDF 中提取文本时 AEM 将其截断](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26785) | + [(Dynamic Media) Dynamic Media 视频播放器在较低环境中无法正常工作](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26871) | + [超过 100,000 个令牌后从大 PDF 中提取文本时 AEM 将其截断](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26785) |
| + [(Dynamic Media) 更改 DM 资产的动态媒体 URL](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-17628) | + [（带 OpenAPI 的 Dynamic Media）根据 IMS 用户组将受限的 Assets 访问权限激活到带 Open API 的 Dynamic Media](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26103) | + [(Dynamic Media) 更改 DM 资产的动态媒体 URL](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-17628) |
| + [解决 AEMaaCS 中非管理员用户无法查看元数据架构的问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26655) | + [当 ZIP 压缩格式的 Tiff 文件上传到 AEM Assets 时，不生成演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-23916) | + [解决 AEMaaCS 中非管理员用户无法查看元数据架构的问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26655) |
| + [(Dynamic Media) Dynamic Media 中 TIFF 图像演绎版背景色变更问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26637) | + [超过 100,000 个令牌后从大 PDF 中提取文本时 AEM 将其截断](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26785) | + [(Dynamic Media) Dynamic Media 中 TIFF 图像演绎版背景色变更问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26637) |
| + [AEMaaCS 资产旋转问题使后续操作不可见](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26528) | + [(Dynamic Media) 更改 DM 资产的动态媒体 URL](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-17628) | + [AEMaaCS 资产旋转问题使后续操作不可见](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26528) |
| + [(Brand Portal) 使用 OAuth 服务器到服务器凭据激活 Brand Portal](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-22074) | + [解决 AEMaaCS 中非管理员用户无法查看元数据架构的问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26655) | + [(Brand Portal) 使用 OAuth 服务器到服务器凭据激活 Brand Portal](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-22074) |
| + [(Dynamic Media) 解决 Adobe Experience Manager 6.5 Dynamic Media 中点击智能裁剪后图像无法显示的问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26367) | + [(Dynamic Media) Dynamic Media 中 TIFF 图像演绎版背景色变更问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26637) | + [(Dynamic Media) 解决 Adobe Experience Manager 6.5 Dynamic Media 中点击智能裁剪后图像无法显示的问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26367) |
| + [增加 Photoshop Firefly API 集成的单部分资产上传限制](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26450) | + [AEMaaCS 资产旋转问题使后续操作不可见](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26528) | + [增加 Photoshop Firefly API 集成的单部分资产上传限制](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26450) |
| + [(Dynamic Media) 解决 AEM 环境中 PDF 文件的动态媒体资产名称差异](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26461) | + [(Dynamic Media) 解决 Adobe Experience Manager 6.5 Dynamic Media 中点击智能裁剪后图像无法显示的问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26367) | + [(Dynamic Media) 解决 AEM 环境中 PDF 文件的动态媒体资产名称差异](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26461) |
| + [某些图像在 Adobe Experience Manager (AEM) as a Cloud Service - Asset 中不显示缩略图演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26233) | + [增加 Photoshop Firefly API 集成的单部分资产上传限制](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26450) | + [某些图像在 Adobe Experience Manager (AEM) as a Cloud Service - Asset 中不显示缩略图演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26233) |
| + [(Dynamic Media) 动态媒体常规设置页面不打开](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25294) | + [(Dynamic Media) 解决 AEM 环境中 PDF 文件的动态媒体资产名称差异](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26461) | + [(Dynamic Media) 动态媒体常规设置页面不打开](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25294) |
| + [(Dynamic Media) 通过 AEM 中的 Dynamic Media 解决视频文件中的音频问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26197) | + [某些图像在 Adobe Experience Manager (AEM) as a Cloud Service - Asset 中不显示缩略图演绎版](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26233) | + [(Dynamic Media) 通过 AEM 中的 Dynamic Media 解决视频文件中的音频问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26197) |
| + [在 AEM as a Cloud Service 中自动标记新上传的资产](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25925) | + [(Dynamic Media) 动态媒体常规设置页面不打开](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25294) | + [在 AEM as a Cloud Service 中自动标记新上传的资产](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25925) |
| + [在 AEM 中从 JWT 迁移到 OAuth 后，智能标记功能不起作用](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25889) | + [(Dynamic Media) 通过 AEM 中的 Dynamic Media 解决视频文件中的音频问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-26197) | + [在 AEM 中从 JWT 迁移到 OAuth 后，智能标记功能不起作用](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25889) |
| + [解决 AEM Managed Services 中的共享链接问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25903) | + [在 AEM as a Cloud Service 中自动标记新上传的资产](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25925) | + [解决 AEM Managed Services 中的共享链接问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25903) |
| + [(Brand Portal) 共享链接下载问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25771) | + [在 AEM 中从 JWT 迁移到 OAuth 后，智能标记功能不起作用](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25889) | + [(Brand Portal) 共享链接下载问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25771) |
| + [(Dynamic Media) AEM Dynamic Media 中的资产处理失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25607) | + [解决 AEM Managed Services 中的共享链接问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25903) | + [(Dynamic Media) AEM Dynamic Media 中的资产处理失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25607) |
| + [(Dynamic Media) Adobe Experience Manager (AEM) Dynamic Media 中的资产同步失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25885) | + [(Dynamic Media) AEM Dynamic Media 中的资产处理失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25607) | + [(Dynamic Media) Adobe Experience Manager (AEM) Dynamic Media 中的资产同步失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25885) |
| + [更新 AEM as a Cloud Service 中视频资产的自定义缩略图](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25829) | + [(Dynamic Media) Adobe Experience Manager (AEM) Dynamic Media 中的资产同步失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25885) | + [更新 AEM as a Cloud Service 中视频资产的自定义缩略图](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25829) |
| + [Adobe Experience Manager (AEM) Assets 中的图像元数据差异](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25828) | + [更新 AEM as a Cloud Service 中视频资产的自定义缩略图](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25829) | + [Adobe Experience Manager (AEM) Assets 中的图像元数据差异](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25828) |
| + [将资产文件夹拖放到 AEM Assets Web UI 时失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-21865) | + [Adobe Experience Manager (AEM) Assets 中的图像元数据差异](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25828) | + [将资产文件夹拖放到 AEM Assets Web UI 时失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-21865) |
| + [(Brand Portal) Brand Portal 编辑器和查看器无法看到任何图像](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-20177) | + [将资产文件夹拖放到 AEM Assets Web UI 时失败](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-21865) | + [(Brand Portal) Brand Portal 编辑器和查看器无法看到任何图像](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-20177) |
| + [(Dynamic Media) 解决 AEM as a Cloud Service 中的资产处理问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25525) | + [(Dynamic Media) 解决 AEM as a Cloud Service 中的资产处理问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25525) | + [(Dynamic Media) 解决 AEM as a Cloud Service 中的资产处理问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25525) |
| + [Adobe Experience Manager as a Cloud Service 中大 PDF 的文本提取限制](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25518) | + [Adobe Experience Manager as a Cloud Service 中大 PDF 的文本提取限制](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25518) | + [Adobe Experience Manager as a Cloud Service 中大 PDF 的文本提取限制](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25518) |
| + [(Asset Link) 解决 InDesign 中的 Adobe Experience Manager (AEM) 资产链接连接问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25562) | + [(Asset Link) 解决 InDesign 中的 Adobe Experience Manager (AEM) 资产链接连接问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25562) | + [(Asset Link) 解决 InDesign 中的 Adobe Experience Manager (AEM) 资产链接连接问题](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25562) |
| + [(Asset Link) Adobe Asset Link 插件网络错误：服务器不可到达](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25506) | + [(Asset Link) Adobe Asset Link 插件网络错误：服务器不可到达](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25506) | + [(Asset Link) Adobe Asset Link 插件网络错误：服务器不可到达](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25506) |
| + [(Dynamic Media) 动态媒体同步用户推荐](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25471) | + [(Dynamic Media) 动态媒体同步用户推荐](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25471) | + [(Dynamic Media) 动态媒体同步用户推荐](https://experienceleague.adobe.com/zh-hans/docs/experience-cloud-kcs/kbarticles/ka-25471) |
