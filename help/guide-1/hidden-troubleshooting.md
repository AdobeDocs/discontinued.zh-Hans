---
title: 隐藏的故障排除测试
description: 这是一个隐藏的故障排除测试
hide: true
hidefromtoc: true
source-git-commit: 388f61fa721e0fedf858634dde807baeadde06f3
workflow-type: tm+mt
source-wordcount: '2876'
ht-degree: 0%

---

# AEM中的故障排除


## 单行表

| AEM Sites疑难解答 |
|--- |
| + [(Dynamic Media)旋转集在AEM Dynamic Media](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26715)中卡在处理状态 |
| + [数字资源管理(DAM)呈现版本与AEM中的原始文件不匹配](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26639) |
| + [未在AEMaaCS](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26873)中生成智能裁剪演绎版 |
| + [(Dynamic Media)修复AEM](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26533)中的视频上传、处理和渲染问题 |
| + [(Asset Link) Adobe Asset Link使链接在使用InDesign](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26922)时处于无法访问状态 |
| + AEMaaCS中的Dynamic Media与DAM卡视图之间视频缩略图不匹配[](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26677) |
| + [(Dynamic Media)使用API](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26902)从Dynamic Media导出资源和元数据 |
| + [AEM as a Cloud Service](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26610)对大型MP4文件的资源处理失败 |
| + [(Dynamic Media) Dynamic Media视频播放器在较低环境中无法正常工作](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26871) |
| + [(Dynamic Media with OpenAPI)基于IMS用户组通过开放API激活对Dynamic Media的受限Assets访问](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26103) |
| + [当具有ZIP压缩格式的Tiff文件上载到AEM Assets时，不会生成任何演绎版](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-23916) |
| + [AEM在10万个令牌之后截断从大型PDF提取的文本](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26785) |
| + [(Dynamic Media)正在更改DM Assets](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-17628)的Dynamic Media URL |
| + [解决AEMaaCS中非管理员用户的元数据架构可见性问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26655) |
| + Dynamic Media中TIFF图像演绎版的[(Dynamic Media)背景颜色更改问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26637) |
| + [AEMaaCS资产轮换问题使后续轮换不可见](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26528) |
| + [(Brand Portal)使用OAuth服务器到服务器凭据激活Brand Portal](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-22074) |
| + [(Dynamic Media)解决Adobe Experience Manager 6.5 Dynamic Media中智能裁剪损坏的图像问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26367) |
| + [提高Photoshop Firefly API集成的单部分资源上传限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26450) |
| + [(Dynamic Media)为PDF文件解决AEM环境中的Dynamic Media资源名称差异](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26461) |
| + [某些图像在Adobe Experience Manager (AEM) as a Cloud Service - Asset](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26233)中未显示缩略图演绎版 |
| + [(Dynamic Media) Dynamic Media常规设置页面未打开](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25294) |
| + [(Dynamic Media)在AEM](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26197)中使用Dynamic Media解决视频文件中的音频问题 |
| + [自动标记AEM as a Cloud Service中新上传的资源](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25925) |
| + [智能标记功能在AEM中从JWT迁移到OAuth后不起作用](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25889) |
| + [解决AEM Managed Services中的共享链接问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25903) |
| + [(Brand Portal)共享链接下载问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25771) |
| + AEM Dynamic Media中的[(Dynamic Media)资源处理失败](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25607) |
| + Adobe Experience Manager (AEM) Dynamic Media中的[(Dynamic Media)资源同步失败](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25885) |
| + [正在更新AEM as a Cloud Service中视频资源的自定义缩略图](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25829) |
| + [Adobe Experience Manager (AEM) Assets中的图像元数据差异](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25828) |
| + [将资源文件夹拖放到AEM Assets Web UI失败](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-21865) |
| + [(Brand Portal) Brand Portal编辑器和查看器看不到任何图像](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-20177) |
| + [(Dynamic Media)正在解决AEM as a Cloud Service](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25525)中的资源处理问题 |
| + [Adobe Experience Manager as a Cloud Service中大型PDF的文本提取限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25518) |
| + [(Asset Link)解决InDesign](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25562)中的Adobe Experience Manager (AEM)资源链接连接问题 |
| + [(Asset Link) Adobe Asset Link插件网络错误：无法访问服务器](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25506) |
| + [(Dynamic Media) Dynamic Media同步用户建议](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25471) |

| AEM Assets疑难解答 |
|--- |
| + AEM的资源下载ZIP文件中缺少[演绎版](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-27140) |
| + [内容片段未包含在AEM Assets许可证中](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26616) |
| + [尽管具有读取权限，但在Assets视图中仍受限制发表评论](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26928) |
| + [(Dynamic Media)旋转集在AEM Dynamic Media](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26715)中卡在处理状态 |
| + [数字资源管理(DAM)呈现版本与AEM中的原始文件不匹配](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26639) |
| + [未在AEMaaCS](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26873)中生成智能裁剪演绎版 |
| + [(Dynamic Media)修复AEM](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26533)中的视频上传、处理和渲染问题 |
| + [(Asset Link) Adobe Asset Link使链接在使用InDesign](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26922)时处于无法访问状态 |
| + AEMaaCS中的Dynamic Media与DAM卡视图之间视频缩略图不匹配[](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26677) |
| + [(Dynamic Media)使用API](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26902)从Dynamic Media导出资源和元数据 |
| + [AEM as a Cloud Service](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26610)对大型MP4文件的资源处理失败 |
| + [(Dynamic Media) Dynamic Media视频播放器在较低环境中无法正常工作](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26871) |
| + [(Dynamic Media with OpenAPI)基于IMS用户组通过开放API激活对Dynamic Media的受限Assets访问](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26103) |
| + [当具有ZIP压缩格式的Tiff文件上载到AEM Assets时，不会生成任何演绎版](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-23916) |
| + [AEM在10万个令牌之后截断从大型PDF提取的文本](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26785) |
| + [(Dynamic Media)正在更改DM Assets](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-17628)的Dynamic Media URL |
| + [解决AEMaaCS中非管理员用户的元数据架构可见性问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26655) |
| + Dynamic Media中TIFF图像演绎版的[(Dynamic Media)背景颜色更改问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26637) |
| + [AEMaaCS资产轮换问题使后续轮换不可见](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26528) |
| + [(Dynamic Media)解决Adobe Experience Manager 6.5 Dynamic Media中智能裁剪损坏的图像问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26367) |
| + [提高Photoshop Firefly API集成的单部分资源上传限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26450) |
| + [(Dynamic Media)为PDF文件解决AEM环境中的Dynamic Media资源名称差异](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26461) |
| + [某些图像在Adobe Experience Manager (AEM) as a Cloud Service - Asset](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26233)中未显示缩略图演绎版 |
| + [(Dynamic Media) Dynamic Media常规设置页面未打开](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25294) |
| + [(Dynamic Media)在AEM](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26197)中使用Dynamic Media解决视频文件中的音频问题 |
| + [自动标记AEM as a Cloud Service中新上传的资源](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25925) |
| + [智能标记功能在AEM中从JWT迁移到OAuth后不起作用](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25889) |
| + [解决AEM Managed Services中的共享链接问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25903) |
| + AEM Dynamic Media中的[(Dynamic Media)资源处理失败](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25607) |
| + Adobe Experience Manager (AEM) Dynamic Media中的[(Dynamic Media)资源同步失败](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25885) |
| + [正在更新AEM as a Cloud Service中视频资源的自定义缩略图](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25829) |
| + [Adobe Experience Manager (AEM) Assets中的图像元数据差异](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25828) |
| + [将资源文件夹拖放到AEM Assets Web UI失败](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-21865) |
| + [(Dynamic Media)正在解决AEM as a Cloud Service](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25525)中的资源处理问题 |
| + [Adobe Experience Manager as a Cloud Service中大型PDF的文本提取限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25518) |
| + [(Asset Link)解决InDesign](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25562)中的Adobe Experience Manager (AEM)资源链接连接问题 |
| + [(Asset Link) Adobe Asset Link插件网络错误：无法访问服务器](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25506) |
| + [(Dynamic Media) Dynamic Media同步用户建议](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25471) |

| AEM Forms疑难解答 |
|--- |
| + [(Dynamic Media)旋转集在AEM Dynamic Media](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26715)中卡在处理状态 |
| + [数字资源管理(DAM)呈现版本与AEM中的原始文件不匹配](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26639) |
| + [未在AEMaaCS](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26873)中生成智能裁剪演绎版 |
| + [(Dynamic Media)修复AEM](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26533)中的视频上传、处理和渲染问题 |
| + [(Asset Link) Adobe Asset Link使链接在使用InDesign](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26922)时处于无法访问状态 |
| + AEMaaCS中的Dynamic Media与DAM卡视图之间视频缩略图不匹配[](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26677) |
| + [(Dynamic Media)使用API](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26902)从Dynamic Media导出资源和元数据 |
| + [AEM as a Cloud Service](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26610)对大型MP4文件的资源处理失败 |
| + [(Dynamic Media) Dynamic Media视频播放器在较低环境中无法正常工作](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26871) |
| + [(Dynamic Media with OpenAPI)基于IMS用户组通过开放API激活对Dynamic Media的受限Assets访问](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26103) |
| + [当具有ZIP压缩格式的Tiff文件上载到AEM Assets时，不会生成任何演绎版](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-23916) |
| + [AEM在10万个令牌之后截断从大型PDF提取的文本](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26785) |
| + [(Dynamic Media)正在更改DM Assets](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-17628)的Dynamic Media URL |
| + [解决AEMaaCS中非管理员用户的元数据架构可见性问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26655) |
| + Dynamic Media中TIFF图像演绎版的[(Dynamic Media)背景颜色更改问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26637) |
| + [AEMaaCS资产轮换问题使后续轮换不可见](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26528) |
| + [(Brand Portal)使用OAuth服务器到服务器凭据激活Brand Portal](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-22074) |
| + [(Dynamic Media)解决Adobe Experience Manager 6.5 Dynamic Media中智能裁剪损坏的图像问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26367) |
| + [提高Photoshop Firefly API集成的单部分资源上传限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26450) |
| + [(Dynamic Media)为PDF文件解决AEM环境中的Dynamic Media资源名称差异](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26461) |
| + [某些图像在Adobe Experience Manager (AEM) as a Cloud Service - Asset](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26233)中未显示缩略图演绎版 |
| + [(Dynamic Media) Dynamic Media常规设置页面未打开](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25294) |
| + [(Dynamic Media)在AEM](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26197)中使用Dynamic Media解决视频文件中的音频问题 |
| + [自动标记AEM as a Cloud Service中新上传的资源](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25925) |
| + [智能标记功能在AEM中从JWT迁移到OAuth后不起作用](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25889) |
| + [解决AEM Managed Services中的共享链接问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25903) |
| + [(Brand Portal)共享链接下载问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25771) |
| + AEM Dynamic Media中的[(Dynamic Media)资源处理失败](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25607) |
| + Adobe Experience Manager (AEM) Dynamic Media中的[(Dynamic Media)资源同步失败](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25885) |
| + [正在更新AEM as a Cloud Service中视频资源的自定义缩略图](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25829) |
| + [Adobe Experience Manager (AEM) Assets中的图像元数据差异](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25828) |
| + [将资源文件夹拖放到AEM Assets Web UI失败](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-21865) |
| + [(Brand Portal) Brand Portal编辑器和查看器看不到任何图像](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-20177) |
| + [(Dynamic Media)正在解决AEM as a Cloud Service](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25525)中的资源处理问题 |
| + [Adobe Experience Manager as a Cloud Service中大型PDF的文本提取限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25518) |
| + [(Asset Link)解决InDesign](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25562)中的Adobe Experience Manager (AEM)资源链接连接问题 |
| + [(Asset Link) Adobe Asset Link插件网络错误：无法访问服务器](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25506) |
| + [(Dynamic Media) Dynamic Media同步用户建议](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25471) |

## 三列表

| AEM Sites疑难解答 | AEM Assets疑难解答 | AEM Forms疑难解答 |
|--- |--- |--- |
| + [(Dynamic Media)旋转集在AEM Dynamic Media](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26715)中卡在处理状态 | + AEM的资源下载ZIP文件中缺少[演绎版](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-27140) | + [(Dynamic Media)旋转集在AEM Dynamic Media](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26715)中卡在处理状态 |
| + [数字资源管理(DAM)呈现版本与AEM中的原始文件不匹配](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26639) | + [内容片段未包含在AEM Assets许可证中](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26616) | + [数字资源管理(DAM)呈现版本与AEM中的原始文件不匹配](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26639) |
| + [未在AEMaaCS](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26873)中生成智能裁剪演绎版 | + [尽管具有读取权限，但在Assets视图中仍受限制发表评论](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26928) | + [未在AEMaaCS](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26873)中生成智能裁剪演绎版 |
| + [(Dynamic Media)修复AEM](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26533)中的视频上传、处理和渲染问题 | + [(Dynamic Media)旋转集在AEM Dynamic Media](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26715)中卡在处理状态 | + [(Dynamic Media)修复AEM](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26533)中的视频上传、处理和渲染问题 |
| + [(Asset Link) Adobe Asset Link使链接在使用InDesign](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26922)时处于无法访问状态 | + [数字资源管理(DAM)呈现版本与AEM中的原始文件不匹配](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26639) | + [(Asset Link) Adobe Asset Link使链接在使用InDesign](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26922)时处于无法访问状态 |
| + AEMaaCS中的Dynamic Media与DAM卡视图之间视频缩略图不匹配[](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26677) | + [未在AEMaaCS](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26873)中生成智能裁剪演绎版 | + AEMaaCS中的Dynamic Media与DAM卡视图之间视频缩略图不匹配[](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26677) |
| + [(Dynamic Media)使用API](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26902)从Dynamic Media导出资源和元数据 | + [(Dynamic Media)修复AEM](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26533)中的视频上传、处理和渲染问题 | + [(Dynamic Media)使用API](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26902)从Dynamic Media导出资源和元数据 |
| + [AEM as a Cloud Service](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26610)对大型MP4文件的资源处理失败 | + [(Asset Link) Adobe Asset Link使链接在使用InDesign](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26922)时处于无法访问状态 | + [AEM as a Cloud Service](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26610)对大型MP4文件的资源处理失败 |
| + [(Dynamic Media) Dynamic Media视频播放器在较低环境中无法正常工作](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26871) | + AEMaaCS中的Dynamic Media与DAM卡视图之间视频缩略图不匹配[](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26677) | + [(Dynamic Media) Dynamic Media视频播放器在较低环境中无法正常工作](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26871) |
| + [(Dynamic Media with OpenAPI)基于IMS用户组通过开放API激活对Dynamic Media的受限Assets访问](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26103) | + [(Dynamic Media)使用API](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26902)从Dynamic Media导出资源和元数据 | + [(Dynamic Media with OpenAPI)基于IMS用户组通过开放API激活对Dynamic Media的受限Assets访问](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26103) |
| + [当具有ZIP压缩格式的Tiff文件上载到AEM Assets时，不会生成任何演绎版](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-23916) | + [AEM as a Cloud Service](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26610)对大型MP4文件的资源处理失败 | + [当具有ZIP压缩格式的Tiff文件上载到AEM Assets时，不会生成任何演绎版](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-23916) |
| + [AEM在10万个令牌之后截断从大型PDF提取的文本](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26785) | + [(Dynamic Media) Dynamic Media视频播放器在较低环境中无法正常工作](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26871) | + [AEM在10万个令牌之后截断从大型PDF提取的文本](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26785) |
| + [(Dynamic Media)正在更改DM Assets](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-17628)的Dynamic Media URL | + [(Dynamic Media with OpenAPI)基于IMS用户组通过开放API激活对Dynamic Media的受限Assets访问](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26103) | + [(Dynamic Media)正在更改DM Assets](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-17628)的Dynamic Media URL |
| + [解决AEMaaCS中非管理员用户的元数据架构可见性问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26655) | + [当具有ZIP压缩格式的Tiff文件上载到AEM Assets时，不会生成任何演绎版](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-23916) | + [解决AEMaaCS中非管理员用户的元数据架构可见性问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26655) |
| + Dynamic Media中TIFF图像演绎版的[(Dynamic Media)背景颜色更改问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26637) | + [AEM在10万个令牌之后截断从大型PDF提取的文本](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26785) | + Dynamic Media中TIFF图像演绎版的[(Dynamic Media)背景颜色更改问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26637) |
| + [AEMaaCS资产轮换问题使后续轮换不可见](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26528) | + [(Dynamic Media)正在更改DM Assets](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-17628)的Dynamic Media URL | + [AEMaaCS资产轮换问题使后续轮换不可见](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26528) |
| + [(Brand Portal)使用OAuth服务器到服务器凭据激活Brand Portal](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-22074) | + [解决AEMaaCS中非管理员用户的元数据架构可见性问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26655) | + [(Brand Portal)使用OAuth服务器到服务器凭据激活Brand Portal](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-22074) |
| + [(Dynamic Media)解决Adobe Experience Manager 6.5 Dynamic Media中智能裁剪损坏的图像问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26367) | + Dynamic Media中TIFF图像演绎版的[(Dynamic Media)背景颜色更改问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26637) | + [(Dynamic Media)解决Adobe Experience Manager 6.5 Dynamic Media中智能裁剪损坏的图像问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26367) |
| + [提高Photoshop Firefly API集成的单部分资源上传限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26450) | + [AEMaaCS资产轮换问题使后续轮换不可见](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26528) | + [提高Photoshop Firefly API集成的单部分资源上传限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26450) |
| + [(Dynamic Media)为PDF文件解决AEM环境中的Dynamic Media资源名称差异](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26461) | + [(Dynamic Media)解决Adobe Experience Manager 6.5 Dynamic Media中智能裁剪损坏的图像问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26367) | + [(Dynamic Media)为PDF文件解决AEM环境中的Dynamic Media资源名称差异](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26461) |
| + [某些图像在Adobe Experience Manager (AEM) as a Cloud Service - Asset](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26233)中未显示缩略图演绎版 | + [提高Photoshop Firefly API集成的单部分资源上传限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26450) | + [某些图像在Adobe Experience Manager (AEM) as a Cloud Service - Asset](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26233)中未显示缩略图演绎版 |
| + [(Dynamic Media) Dynamic Media常规设置页面未打开](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25294) | + [(Dynamic Media)为PDF文件解决AEM环境中的Dynamic Media资源名称差异](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26461) | + [(Dynamic Media) Dynamic Media常规设置页面未打开](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25294) |
| + [(Dynamic Media)在AEM](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26197)中使用Dynamic Media解决视频文件中的音频问题 | + [某些图像在Adobe Experience Manager (AEM) as a Cloud Service - Asset](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26233)中未显示缩略图演绎版 | + [(Dynamic Media)在AEM](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26197)中使用Dynamic Media解决视频文件中的音频问题 |
| + [自动标记AEM as a Cloud Service中新上传的资源](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25925) | + [(Dynamic Media) Dynamic Media常规设置页面未打开](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25294) | + [自动标记AEM as a Cloud Service中新上传的资源](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25925) |
| + [智能标记功能在AEM中从JWT迁移到OAuth后不起作用](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25889) | + [(Dynamic Media)在AEM](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26197)中使用Dynamic Media解决视频文件中的音频问题 | + [智能标记功能在AEM中从JWT迁移到OAuth后不起作用](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25889) |
| + [解决AEM Managed Services中的共享链接问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25903) | + [自动标记AEM as a Cloud Service中新上传的资源](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25925) | + [解决AEM Managed Services中的共享链接问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25903) |
| + [(Brand Portal)共享链接下载问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25771) | + [智能标记功能在AEM中从JWT迁移到OAuth后不起作用](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25889) | + [(Brand Portal)共享链接下载问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25771) |
| + AEM Dynamic Media中的[(Dynamic Media)资源处理失败](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25607) | + [解决AEM Managed Services中的共享链接问题](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25903) | + AEM Dynamic Media中的[(Dynamic Media)资源处理失败](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25607) |
| + Adobe Experience Manager (AEM) Dynamic Media中的[(Dynamic Media)资源同步失败](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25885) | + AEM Dynamic Media中的[(Dynamic Media)资源处理失败](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25607) | + Adobe Experience Manager (AEM) Dynamic Media中的[(Dynamic Media)资源同步失败](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25885) |
| + [正在更新AEM as a Cloud Service中视频资源的自定义缩略图](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25829) | + Adobe Experience Manager (AEM) Dynamic Media中的[(Dynamic Media)资源同步失败](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25885) | + [正在更新AEM as a Cloud Service中视频资源的自定义缩略图](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25829) |
| + [Adobe Experience Manager (AEM) Assets中的图像元数据差异](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25828) | + [正在更新AEM as a Cloud Service中视频资源的自定义缩略图](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25829) | + [Adobe Experience Manager (AEM) Assets中的图像元数据差异](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25828) |
| + [将资源文件夹拖放到AEM Assets Web UI失败](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-21865) | + [Adobe Experience Manager (AEM) Assets中的图像元数据差异](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25828) | + [将资源文件夹拖放到AEM Assets Web UI失败](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-21865) |
| + [(Brand Portal) Brand Portal编辑器和查看器看不到任何图像](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-20177) | + [将资源文件夹拖放到AEM Assets Web UI失败](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-21865) | + [(Brand Portal) Brand Portal编辑器和查看器看不到任何图像](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-20177) |
| + [(Dynamic Media)正在解决AEM as a Cloud Service](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25525)中的资源处理问题 | + [(Dynamic Media)正在解决AEM as a Cloud Service](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25525)中的资源处理问题 | + [(Dynamic Media)正在解决AEM as a Cloud Service](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25525)中的资源处理问题 |
| + [Adobe Experience Manager as a Cloud Service中大型PDF的文本提取限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25518) | + [Adobe Experience Manager as a Cloud Service中大型PDF的文本提取限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25518) | + [Adobe Experience Manager as a Cloud Service中大型PDF的文本提取限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25518) |
| + [(Asset Link)解决InDesign](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25562)中的Adobe Experience Manager (AEM)资源链接连接问题 | + [(Asset Link)解决InDesign](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25562)中的Adobe Experience Manager (AEM)资源链接连接问题 | + [(Asset Link)解决InDesign](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25562)中的Adobe Experience Manager (AEM)资源链接连接问题 |
| + [(Asset Link) Adobe Asset Link插件网络错误：无法访问服务器](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25506) | + [(Asset Link) Adobe Asset Link插件网络错误：无法访问服务器](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25506) | + [(Asset Link) Adobe Asset Link插件网络错误：无法访问服务器](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25506) |
| + [(Dynamic Media) Dynamic Media同步用户建议](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25471) | + [(Dynamic Media) Dynamic Media同步用户建议](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25471) | + [(Dynamic Media) Dynamic Media同步用户建议](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25471) |
