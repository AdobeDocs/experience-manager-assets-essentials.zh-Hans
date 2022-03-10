---
title: 发行说明
description: 的发行说明和已知问题 [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 4cced7aba92fd0f041842e5ef78d02f0a4f7ffe0
workflow-type: tm+mt
source-wordcount: '549'
ht-degree: 0%

---

# 的发行说明 [!DNL Assets Essentials] {#release-notes}

的当前版本 [!DNL Assets Essentials] 于2022年3月09日发布。 此版本提供：

* [!DNL Assets Essentials] 现在，您可以 [生成链接并与外部利益相关方共享资产](share-links-for-assets.md)，他们无权访问 [!DNL Assets Essentials] 应用程序。 您可以为链接定义过期日期，然后使用您首选的通信方法（如电子邮件或消息传送服务）与他人共享该链接。 链接的收件人可以预览并下载资产。

* 的 [!DNL Assets Essentials] 现在包含 [管理员产品配置文件](deploy-administer.md#add-users-to-essentials) Admin Console，以及现有的常规用户和消费者用户产品配置文件。 管理员现在可以将其他用户分配给管理员产品配置文件。

* Assets Essentials现在允许管理员 [管理存储库中可用文件夹的访问级别](manage-permissions.md). 作为管理员，您可以创建用户组并为这些组分配权限以管理访问级别。 您还可以将权限管理权限委派给文件夹级别的用户组。

* 基于客户反馈的增强功能和错误修复。

此外， [!DNL Adobe Asset Link] Creative Cloud扩展(Photoshop、Illustrator和InDesign)发布了 [新版本3.2](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)，提高了面板启动时间和下载速度的性能。


## 已知问题 {#known-issues}

的已知问题列表 [!DNL Assets Essentials] 产品不断修订和更新：

* 无

如果您遇到任何问题，甚至遇到增强请求， [提供反馈](#provide-feedback) 敬团队。

## 过去版本 {#past-release}

### 2022.1.0版 {#january-2022}

[!DNL Assets Essentials] 将于2022年2月03日发布，并进行以下更新：

* 改进了 [!UICONTROL 创建文件夹] 操作。 <!-- CQ-4338818 -->

### 2021.11.0版本 {#november-2021}

[!DNL Assets Essentials] 将于2021年12月16日发布，并进行以下更新：

* Adobe在完成配置过程后自动部署Assets Essentials。 管理员无需执行其他步骤即可使用部署Assets Essentials [!DNL Cloud Manager] 用户界面。 此自动部署将适用于2022年1月6日之后配置的环境。
* 在AdobeExchange上提供了使用Assets Essentials的新版Creative Cloud插件 —  [适用于Adobe XD的Adobe资产链接版本2.1.0](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) 和 [适用于Photoshop的Adobe资产链接/InDesign/Illustrator v 3.1.65](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html).
* 各种错误修复和产品增强功能，包括以前的已知问题（文件夹现在在上传后正确显示在左侧导航树中）<!-- CQ-4337638 -->，拖放上载允许用户在拖放以进行上载时选择当前文件夹或任何子文件夹<!-- CQ-4327753 -->)。

### 2021.8.0版 {#august2021}

[!DNL Assets Essentials] 2021.8.0于2021年8月30日发布，其更新如下：

* 集成 [!DNL Adobe Workfront] 这样 [!DNL Workfront] 用户在管理其工作的上下文中管理其数字资产。 有关更多信息，请参阅 [与其他Adobe解决方案集成](/help/integration.md).

### 2021.7.0版 {#july2021}

[!DNL Assets Essentials] 2021.7.0于2021年7月29日发布，其更新如下：

* 您可以创建和管理自定义元数据表单，以在 [!UICONTROL 元数据Forms] 选项 [!DNL Settings]. 请参阅 [元数据表单](metadata.md#metadata-forms).
* 各种错误修复和产品改进，包括在上载包含许多子文件夹的嵌套文件夹时性能更佳。

### 2021.6.0版 {#june2021}

的 [!DNL Assets Essentials]，于2021年6月21日推出，提供了轻量级的资产管理功能。 它支持以下主要功能和CRUD（创建、读取、更新和删除）操作：

* 上传和添加资产，包括嵌套文件夹。 预览资产和版本。
* 全文搜索、细致入微的搜索过滤器，以及为快速发现资产而进行的保存搜索。
* 基本的资产管理操作，如更新、删除、下载和管理元数据。
* [!DNL Assets Essentials] 可用于 [!DNL Adobe Journey Optimizer] 用户在创建消息时管理资产。 有关更多信息，请参阅 [与其他Adobe解决方案集成](/help/integration.md).
