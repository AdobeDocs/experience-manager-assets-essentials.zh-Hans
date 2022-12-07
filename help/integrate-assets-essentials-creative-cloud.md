---
title: 将 Assets Essentials 与 Creative Cloud 应用程序集成
description: 将 Assets Essentials 与 Creative Cloud 应用程序集成，以使您可使用 Adobe Asset Link 应用程序内置面板从支持的 [!DNL Adobe Creative Cloud] 桌面应用程序中连接到 [!DNL Assets Essentials] 存储库。
exl-id: 611fd958-3fd3-4c46-bee9-8b866b7dc208
source-git-commit: 268b7eb82b15b658207f24750eeae085ce5bb3d4
workflow-type: ht
source-wordcount: '854'
ht-degree: 100%

---

# 将 Assets Essentials 与 Creative Cloud 应用程序集成 {#integrate-assets-essentials-creative-cloud-applications}

![用于切换深色和浅色主题的首选项](assets/cce-creative-cloud.png)

## 迄今为止的故事

在本教程中[配置 Experience Manager Assets Essentials ](adminster-aem-assets-essentials.md)后，您可以在此体验的基础上将 Creative Cloud 应用程序与 Assets Essentials 集成。

## 目标

* **受众**：Creative Cloud 管理员

* **目标**：将 Assets Essentials 与 Creative Cloud 应用程序集成，以使您的创意用户可使用 Adobe Asset Link 应用程序内置面板从支持的[!DNL Assets Essentials]桌面应用程序中连接到[!DNL Adobe Creative Cloud]存储库。

## 概述

通过[Adobe Asset Link 应用程序内置面板](https://www.adobe.com/cn/creativecloud/business/enterprise/adobe-asset-link.html)，创意专业人员可从受支持的[!DNL Assets Essentials]桌面应用程序中连接到[!DNL Adobe Creative Cloud]存储库。该面板可用于 [!DNL Adobe Photoshop]、[!DNL Adobe Illustrator]、[!DNL Adobe InDesign] 和 [!DNL Adobe XD]。它简化了对资源的访问，从而有助于提高内容速度。

只有将 Creative Cloud 应用程序与 Experience Manager Assets Essentials 存储库集成时，Creative Cloud 应用程序用户才能使用 Adobe Asset Link 应用程序内置面板。

通过执行以下任务，将 Assets Essentials 与 Creative Cloud 应用程序集成：

* [在 Creative Cloud 和 Experience Cloud Admin Console 之间创建目录信任关系](#directory-trusting-cc-assets-essentials-consoles)

* [将 Creative Cloud 用户添加到 Assets Essentials 产品配置文件](#add-cc-users-assets-essentials-product-profiles)

* [安装 Adobe Asset Link](#install-asset-link)

* [使用 Adobe Asset Link](#use-asset-link)

## 在 Creative Cloud 和 Experience Cloud Admin Console 之间创建目录信任关系 {#directory-trusting-cc-assets-essentials-consoles}

如果您的 Creative Cloud 部署在一个单独的 Adobe Admin Console 中，而不是部署在带有 Assets Essentials（Experience Cloud 解决方案）的 Adobe Admin Console 中，则需要在两个控制台之间添加信任关系。

要集成 Creative Cloud 和 Assets Essentials 应用程序，Creative Cloud 的 Admin Console 中可用的用户必须在 Experience Cloud 的 Admin Console 中可用。如果 Creative Cloud 和 Assets Essentials 部署在不同的 Admin Console 中，它们之间需要建立信任关系才能实现这一点。

在 Experience Cloud Admin Console 中，单击&#x200B;**[!UICONTROL “设置”]**，并使用&#x200B;**[!UICONTROL “目录”]**&#x200B;选项卡创建一个目录，在这两个 Admin Console 之间建立[目录信任关系](https://helpx.adobe.com/cn/enterprise/using/set-up-identity.html#directory-trusting)。

## 将 Creative Cloud 用户添加到 Assets Essentials 产品配置文件 {#add-cc-users-assets-essentials-product-profiles}

在 Creative Cloud 的 Admin Console 和 Experience Cloud 的 Admin Console 之间建立目录信任关系后，将 Creative Cloud 用户分配到 Experience Cloud Admin Console 中 [!DNL Assets Essentials] 产品卡下的&#x200B;**[!DNL Assets Essentials]“用户”**&#x200B;产品配置文件。这使得 Creative Cloud 用户可以从他们的 Adobe Asset Link 插件面板访问 Assets Essentials；此外，这将使他们能够访问 Assets Essentials web 完整的用户界面，以便使用 web 浏览器上载、组织、标记和查找数字资源。

其他 Assets Essentials 产品配置文件（**[!DNL Assets Essentials]管理员**&#x200B;和&#x200B;**[!DNL Assets Essentials]消费者用户**）用于不同的用户权限（应用程序管理员和用户通过与 Experience Cloud 的集成访问 Assets Essentials）。

有关如何将用户分配到 Assets Essentials 产品配置文件的更多信息，请参阅[将用户分配到 Assets Essentials 产品配置文件](adminster-aem-assets-essentials.md#add-users-to-product-profiles)。

## 安装 Adobe Asset Link {#install-asset-link}

[!DNL Adobe Asset Link] 插件可以通过两种方式安装并提供给创意用户：

* 创意用户可以从其 [!DNL Creative Cloud Desktop] 应用程序安装插件
* Creative Cloud 管理员可以在 Admin Console 中将 Asset Link 插件添加到 Creative Cloud 程序包中

是否选择添加取决于组织的 IT 政策。

[此处](https://helpx.adobe.com/cn/creative-cloud/kb/installingextensionsandaddons.html)解释了&#x200B;**使用[!DNL Creative Cloud Desktop]应用程序**&#x200B;进行的安装。在 [Adobe Exchange](https://exchange.adobe.com/) Marketplace 上托管的有两个可用插件，具体取决于 Creative Cloud 应用程序的情况：

* 对于 [!DNL Adobe Photoshop]、[!DNL Adobe Illustrator] 和 [!DNL Adobe InDesign]：[Adobe Asset Link CEP](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)
* 对于 [!DNL Adobe XD]：[Adobe Asset Link](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)

Creative Cloud 管理员在 Admin Console 中&#x200B;**安装 Creative Cloud 软件包**，方法是在构建部署软件包时加入 Asset Link 插件，此后可以将其部署到用户机器上。在托管的选择插件屏幕中，在&#x200B;**精选商用插件**&#x200B;部分中搜索 **Adobe Asset Link**。有关详细信息，请参阅[通过 Admin Console 打包应用程序](https://helpx.adobe.com/cn/enterprise/using/package-apps-admin-console.html)。

## 使用 Adobe Asset Link {#use-asset-link}

创意用户现在可以将 Adobe Asset Link 与 Photoshop、Illustrator、InDesign 或 XD 一起使用。要在 InDesign 或 Illustrator 中打开该面板，请转到“窗口”>“扩展”>“Adobe Asset Link”。在 Photoshop 中，转到“窗口”>“扩展（旧版）”>“Adobe Asset Link”。

有关如何为 Adobe XD 设置 Adobe Asset Link 的信息，请单击[此处](https://helpx.adobe.com/cn/enterprise/using/adobe-asset-link-for-xd.html)。

>[!NOTE]
>
>在使用 Apple Silicon/M1 硬件时，需要使用 Rosetta 兼容模式启动 Adobe Photoshop，以确保创意用户能够访问 Adobe Asset Link 面板，这是因为它是使用 CEP 扩展技术构建的。如需更多信息，请参阅[在 Apple Silicon 中使用 Photoshop](https://helpx.adobe.com/photoshop/kb/photoshop-for-apple-silicon.html)。


通过 Adobe Asset Link 使用和修改存储在 Assets Essentials 存储库中的资源。您可以执行各种任务，例如：

* 搜索和浏览资源

* 上传资源

* 排序和过滤资源

* 放置、下载和拖动资源

* 签出和签入资源

* 查看版本历史记录和文件详细信息

有关如何执行这些任务的说明，请参阅[使用 Adobe Asset Link](https://helpx.adobe.com/in/enterprise/using/manage-assets-using-adobe-asset-link.html) 管理资源。

## 接下来呢？

您现在已将 Creative Cloud 应用程序与 Assets Essentials 集成，[请将 Adobe Workfront 与 Experience Manager Assets Essentials 集成](integrate-assets-essentials-workfront.md)。
