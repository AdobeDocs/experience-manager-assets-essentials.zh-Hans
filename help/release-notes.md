---
title: 发行说明
description: ' [!DNL Assets Essentials] 的发行说明和已知问题'
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 4cced7aba92fd0f041842e5ef78d02f0a4f7ffe0
workflow-type: tm+mt
source-wordcount: '549'
ht-degree: 59%

---

# [!DNL Assets Essentials] 的发行说明 {#release-notes}

的当前版本 [!DNL Assets Essentials] 于2022年3月09日发布。 此版本提供了：

* [!DNL Assets Essentials] 现在，您可以 [生成链接并与外部利益相关方共享资产](share-links-for-assets.md)，他们无权访问 [!DNL Assets Essentials] 应用程序。 您可以为链接定义过期日期，然后使用您首选的通信方法（如电子邮件或消息传送服务）与他人共享该链接。 链接的收件人可以预览并下载资产。

* 的 [!DNL Assets Essentials] 现在包含 [管理员产品配置文件](deploy-administer.md#add-users-to-essentials) Admin Console，以及现有的常规用户和消费者用户产品配置文件。 管理员现在可以将其他用户分配给管理员产品配置文件。

* Assets Essentials现在允许管理员 [管理存储库中可用文件夹的访问级别](manage-permissions.md). 作为管理员，您可以创建用户组并为这些组分配权限以管理访问级别。 您还可以将权限管理权限委派给文件夹级别的用户组。

* 基于客户反馈的增强功能和错误修复。

此外， [!DNL Adobe Asset Link] Creative Cloud扩展(Photoshop、Illustrator和InDesign)发布了 [新版本3.2](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)，提高了面板启动时间和下载速度的性能。


## 已知问题 {#known-issues}

[!DNL Assets Essentials] 产品的已知问题列表将持续修订和更新：

* 无

如果您遇到任何问题，亦或有改进请求，请向团队[提供反馈](#provide-feedback)。

## 过去的版本 {#past-release}

### 2022.1.0 发布 {#january-2022}

[!DNL Assets Essentials] 将于2022年2月03日发布，并进行以下更新：

* 改进了 [!UICONTROL 创建文件夹] 操作。 <!-- CQ-4338818 -->

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

* 您可以创建和管理自定义元数据表单，以在 [!UICONTROL 元数据Forms] 选项 [!DNL Settings]. 请参阅[元数据表单](metadata.md#metadata-forms)。
* 多个错误修复和产品改进，包括上传具有多个子文件夹的嵌套文件夹时更好的性能。

### 2021.6.0 发布 {#june2021}

[!DNL Assets Essentials] 的首个版本在 2021 年 6 月 21 日发布，提供了轻量级的资源管理功能。它支持以下主要功能和 CRUD（创建、读取、更新和删除）操作：

* 上传并添加资源，包括嵌套文件夹。预览资源和版本。
* 全文搜索、精细搜索筛选条件以及保存的搜索，用于快速发现资源。
* 基本资源管理操作，例如更新、删除、下载和管理元数据。
* [!DNL Assets Essentials] 可供 [!DNL Adobe Journey Optimizer] 用户在创建消息时管理资源。有关更多信息，请参阅[与其他 Adobe 解决方案集成](/help/integration.md)。
