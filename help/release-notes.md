---
title: 发行说明
description: ' [!DNL Assets Essentials]的发行说明和已知问题'
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: eda2ba0d271310d0e87f904dc7622583a80d002e
workflow-type: tm+mt
source-wordcount: '288'
ht-degree: 1%

---


# [!DNL Assets Essentials]的发行说明 {#release-notes}

[!DNL Assets Essentials]的当前版本于2021年8月30日发布。 它提供与[!DNL Adobe Workfront]的集成，让[!DNL Workfront]用户在管理其工作的上下文中管理其数字资产。 请参阅[与其他Adobe解决方案的集成](/help/integration.md)。

要详细了解解决方案，请参阅[ [!DNL Assets Essentials]](introduction.md)简介。 要开始使用这些功能，请参阅[开始](/help/get-started.md)。

## 已知问题 {#known-issues}

[!DNL Assets Essentials]产品的已知问题清单不断修订和更新：

* 要上传一个或多个资产，当您将项目拖到存储库中包含子文件夹的文件夹中时，上传内容会自动进入其中一个子文件夹。 解决方法是单击[!DNL Upload assets]选项并拖到对话框中。<!-- CQ-4327753 -->
* 上传文件夹后，新文件夹有时可能会在左边栏中显示错误，而不是在树视图中显示。 解决方法是刷新浏览器。<!-- CQ-4323534 -->

<!--
* Use assets that do not have whitespace in the file names. The replies to comments do not work for such assets.
-->

如果您遇到任何问题甚至是增强功能请求，[会向团队提供反馈](#provide-feedback)。

## 过去版本 {#past-release}

### 2021.7.0版 {#july2021}

[!DNL Assets Essentials] 2021.7.0于2021年7月29日发布，其更新如下：

* 您可以创建和管理自定义元数据表单，以用于在[!UICONTROL Metadata Forms]选项下[!DNL Settings]的资产详细信息屏幕中向用户显示元数据属性。 请参阅[元数据表单](metadata.md#metadata-forms)。
* 各种错误修复和产品改进，包括在上载包含许多子文件夹的嵌套文件夹时性能更佳。

### 2021.6.0版 {#june2021}

2021年6月21日发布的[!DNL Assets Essentials]第一版提供了轻量级的资产管理功能。 它支持以下主要功能和CRUD（创建、读取、更新和删除）操作：

* 上传和添加资产，包括嵌套文件夹。 预览资产和版本。
* 全文搜索、细致入微的搜索过滤器，以及为快速发现资产而进行的保存搜索。
* 基本的资产管理操作，如更新、删除、下载和管理元数据。
* [!DNL Assets Essentials] 可 [[!DNL Adobe Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html)用
