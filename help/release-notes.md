---
title: 发行说明
description: ' [!DNL Assets Essentials] 的发行说明和已知问题'
role: User,Leader,Admin,Architect,Developer
contentOwner: AK
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: f273e1e3c8a290e0beee0423da00c63013062c43
workflow-type: tm+mt
source-wordcount: '1117'
ht-degree: 80%

---

# [!DNL Assets Essentials] 的发行说明 {#release-notes}

的当前版本 [!DNL Assets Essentials] 将于2022年7月14日发布。

此版本提供：

**智能收藏集**

将搜索结果另存为智能收藏集，以动态更新收藏集内容。 如果向Assets Essentials存储库添加的资产符合在 [创建智能收藏集](manage-collections.md#create-smart-collection)，则智能收藏集的内容会自动更新。

**通知**

Assets Essentials通知允许您 [监控对存储库中可用的资产或文件夹执行的操作](manage-notifications.md). 您需要选择并订阅向您发送通知的内容。 您还可以配置向您发送通知的类别。

**报告**

资产报表允许管理员评估Adobe Experience Manager Assets Essentials中的用户活动。 “报表和实时统计”功能板提供有关用户如何与部署中可用资产交互的有用信息。 [使用报表中的信息](manage-reports.md) ，以获取关键成功量度来衡量企业内和客户对资产的采用情况。

查看资产下载报表和实时统计功能板模块，以查看正在下载的资产和下载频率。

**基于客户反馈的改进**

基于客户反馈的增强和错误修复。


## 已知问题 {#known-issues}

[!DNL Assets Essentials] 产品的已知问题列表将持续修订和更新：

<!--

* Assets Essentials does not support creating Private collections.

-->


* Assets Essentials不支持编辑智能收藏集。

* 专用收藏集可供创建者和具有管理员权限的用户使用。 作为管理员，您无法将访问集合的权限委派给其他用户。

如果您遇到任何问题，亦或有改进请求，请向团队[提供反馈](#provide-feedback)。

## 过去的版本 {#past-release}

### 2022.5.0 {#may-2022}

[!DNL Assets Essentials] 的当前版本于 2022 年 6 月 16 日发布。

此版本提供：

**资源状态增强**

* 现在通过 Assets Essentials 可[设置资源的到期日期](manage-organize.md#set-asset-status)。此外，还可根据 `Expired` 资源状态和到期日期范围[筛选资源](search.md#refine-search-results)。

* 现在可查看废纸篓中所有可用资源的资源状态指示器。因此，可根据资源的状态决定是否还原该资源。

**搜索筛选器增强**

* 现在通过 Assets Essentials 可使用 `No Status` 资源状态[筛选资源](search.md#refine-search-results)。

<!--

* Assets Essentials now supports [using a wildcard operator (*) while using custom filters](search.md#custom-filters) to enable Assets Essentials to display assets in the results that partially match the search criteria.

-->

**收藏集增强**

<!--

* Assets Essentials now enables you to [create Private collections](manage-collections.md#create-collection).

-->

* Assets Essentials 现在支持[下载收藏集](manage-collections.md)。

* 现在可编辑收藏集的“描述”元数据字段。

**文档增强**

* 现已提供 [Assets Essentials 概览文档](introduction.md)的新版本。

**基于客户反馈的改进**

* 基于客户反馈的增强和错误修复。

### 2022.4.0 {#april-2022}

[!DNL Assets Essentials] 的当前版本于 2022 年 5 月 12 日发布。此版本提供了：

* [!DNL Assets Essentials] 现在支持[创建收藏集](manage-collections.md)。收藏集是 Experience Manager Assets Essentials 中的一组资源。使用收藏集可在用户之间共享资源。与文件夹不同，一个收藏集可以包含来自不同位置的资源。

* Assets Essentials 现在还支持向用户界面[添加自定义筛选条件](search.md#custom-filters)。除了标准筛选条件之外，您还可以应用这些自定义筛选条件来优化您的搜索结果。

* Assets Essentials 现在允许您为存储库中可用的资源[设置状态](manage-organize.md#set-asset-status)。设置资源状态以更好地治理和管理下游对数字资源的使用。

* 基于客户反馈的增强和错误修复。

#### Chrome 中的无痕模式 {#incognito-mode}

在此版本中，我们优化了 UI 交付的性能和 Assets Essentials 中的特定功能（评论资源和图像编辑），具体取决于浏览器本地存储和启用的第三方 Cookie。默认情况下，Chrome Web 浏览器中的无痕模式会阻止第三方 Cookie - 为用户提供了多个选项，以便继续访问所有功能：

* 当用户需要分离浏览器会话时，可使用 Chrome 配置文件而不是无痕模式

* 在 Chrome 中的无痕模式屏幕上禁用 `Block third-party cookies`

### 2022.2.0 {#march-2022}

[!DNL Assets Essentials] 发布于 2022 年 3 月 9 日，提供以下更新：

* [!DNL Assets Essentials]现在使您能够[生成链接并与无权访问[!DNL Assets Essentials]应用程序的外部利益相关者](share-links-for-assets.md)共享资源。您可以定义链接的到期日期，然后使用您喜欢的通信方式（如电子邮件或消息服务）与他人共享。链接的接收者可以预览并下载资源。

* 除了现有的常规和消费者用户产品配置文件外，[!DNL Assets Essentials] 现在还包括 Admin Console 上的[管理员产品配置文件](deploy-administer.md#add-users-to-essentials)。管理员现在可以将其他用户分配给管理员产品配置文件。

* Assets Essentials 现在允许管理员[管理存储库中可用文件夹的访问级别](manage-permissions.md)。作为管理员，您可以创建用户组并向这些组分配权限以管理访问级别。您还可以将权限管理权委派给文件夹级别的用户组。

* 基于客户反馈的增强和错误修复。

此外，[!DNL Adobe Asset Link]Creative Cloud 扩展（Photoshop、Illustrator 和 InDesign）发布了[新版本 3.2](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)，在面板启动时间和下载速度方面进行了性能改进。


### 2022.1.0 发布 {#january-2022}

[!DNL Assets Essentials] 发布于 2022 年 2 月 3 日，提供以下更新：

* 针对[!UICONTROL 创建文件夹]操作的性能改进。<!-- CQ-4338818 -->

### 2021.11.0 发布 {#november-2021}

[!DNL Assets Essentials] 发布于 2021 年 12 月 16 日，提供以下更新：

* Adobe 在完成配置过程后自动部署 Assets Essentials。管理员不需要使用 [!DNL Cloud Manager] 用户界面执行额外的步骤来部署 Assets Essentials。此自动部署将对在 2022 年 1 月 6 日之后配置的环境可用。
* Adobe Exchange 上提供了与 Assets Essentials 配合使用的新版本 Creative Cloud 插件 - [Adobe Asset Link for Adobe XD v 2.1.0](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) 和 [Adobe Asset Link for Photoshop/InDesign/Illustrator v 3.1.65](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)。
* 多个错误修复和产品增强功能，包括以前的已知问题（现在文件夹上传之后正确显示在左导航树中<!-- CQ-4337638 -->，执行拖放上传操作时，用户可在执行放置操作时选择当前文件夹或者任意子文件夹<!-- CQ-4327753 -->）。

### 2021.8.0 发布 {#august2021}

[!DNL Assets Essentials] 2021.8.0 发布于 2021 年 8 月 30 日，提供以下更新：

* 与 [!DNL Adobe Workfront] 集成，使得 [!DNL Workfront] 用户可以在管理其工作的环境中管理器数字资源。有关更多信息，请参阅[与其他 Adobe 解决方案集成](/help/integration.md)。

### 2021.7.0 发布 {#july2021}

[!DNL Assets Essentials] 2021.7.0 发布于 2021 年 7 月 29 日，提供以下更新：

* 您可以创建和管理自定义的元数据表单，用于在[!DNL Settings]下[!UICONTROL 元数据表单]选项的资源详细信息屏幕中，向用户显示元数据属性。请参阅[元数据表单](metadata.md#metadata-forms)。
* 多个错误修复和产品改进，包括上传具有多个子文件夹的嵌套文件夹时更好的性能。

### 2021.6.0 发布 {#june2021}

[!DNL Assets Essentials] 的首个版本在 2021 年 6 月 21 日发布，提供了轻量级的资源管理功能。它支持以下主要功能和 CRUD（创建、读取、更新和删除）操作：

* 上传并添加资源，包括嵌套文件夹。预览资源和版本。
* 全文搜索、精细搜索筛选条件以及保存的搜索，用于快速发现资源。
* 基本资源管理操作，例如更新、删除、下载和管理元数据。
* [!DNL Assets Essentials] 可供 [!DNL Adobe Journey Optimizer] 用户在创建消息时管理资源。有关更多信息，请参阅[与其他 Adobe 解决方案集成](/help/integration.md)。
