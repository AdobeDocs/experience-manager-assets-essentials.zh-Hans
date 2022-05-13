---
title: 将Assets Essentials与Creative Cloud应用程序集成
description: 将Assets Essentials与Creative Cloud应用程序集成，以便您能够使用Adobe资产链接应用程序内面板连接到 [!DNL Assets Essentials] 支持 [!DNL Adobe Creative Cloud] 桌面应用程序。
source-git-commit: f4e56fc6bb76eeb2770b18be88b7da1a1829069c
workflow-type: tm+mt
source-wordcount: '854'
ht-degree: 4%

---


# 将Assets Essentials与Creative Cloud应用程序集成 {#integrate-assets-essentials-creative-cloud-applications}

![切换设色和浅色主题的偏好设置](assets/cce-creative-cloud.png)

## 到目前为止

之后 [配置Experience Manager Assets Essentials](adminster-aem-assets-essentials.md) 在本教程中，您可以基于体验进行构建，以将Creative Cloud应用程序与Assets Essentials集成。

## 目标

* **受众**:Creative Cloud管理员

* **目标**:将Assets Essentials与Creative Cloud应用程序集成，以便创意用户可以使用Adobe资产链接应用程序内面板连接到 [!DNL Assets Essentials] 支持 [!DNL Adobe Creative Cloud] 桌面应用程序。

## 概述

[Adobe资产链接应用程序内面板](https://www.adobe.com/creativecloud/business/enterprise/adobe-asset-link.html) 让创意专业人员能够连接 [!DNL Assets Essentials] 支持 [!DNL Adobe Creative Cloud] 桌面应用程序。 该面板可用于 [!DNL Adobe Photoshop]、[!DNL Adobe Illustrator]、[!DNL Adobe InDesign] 和 [!DNL Adobe XD]。它可简化对资产的访问，进而帮助提高内容速度。

Creative Cloud应用程序用户只有在您将Adobe应用程序与Experience Manager Assets Essentials存储库集成后，才能使用Creative Cloud资产链接应用程序内面板。

执行以下任务以将Assets Essentials与Creative Cloud应用程序集成：

* [在Creative Cloud和Experience CloudAdmin Console之间创建目录信任](#directory-trusting-cc-assets-essentials-consoles)

* [将Creative Cloud用户添加到Assets Essentials产品配置文件](#add-cc-users-assets-essentials-product-profiles)

* [安装Adobe资产链接](#install-asset-link)

* [使用Adobe资产链接](#use-asset-link)

## 在Creative Cloud和Experience CloudAdmin Console之间创建目录信任 {#directory-trusting-cc-assets-essentials-consoles}

如果您的Creative Cloud部署在与使用Assets Essentials(Experience Cloud解决方案)的Adobe管理控制台不同的控制台中，则您需要在两个控制台之间添加信任关系。

要集成Creative Cloud和Assets Essentials应用程序，在Admin Console中可用以进行Creative Cloud的用户必须在Admin Console中可用以进行Experience Cloud。 如果Creative Cloud和Assets Essentials部署到不同的Admin Console中，则需要它们之间的信任关系才能启用此功能。

在Experience CloudAdmin Console上，单击 **[!UICONTROL 设置]** 并使用 **[!UICONTROL 目录]** 选项卡，以创建要建立的目录 [目录信任](https://helpx.adobe.com/enterprise/using/set-up-identity.html#directory-trusting) 两个Admin Console之间。

## 将Creative Cloud用户添加到Assets Essentials产品配置文件 {#add-cc-users-assets-essentials-product-profiles}

在Creative CloudAdmin Console和Experience CloudAdmin Console之间建立目录信任后，将Creative Cloud用户分配给 **[!DNL Assets Essentials]用户** 下方的产品配置文件 [!DNL Assets Essentials] 产品卡。Experience CloudAdmin Console 它允许Creative Cloud用户从其Adobe资产链接插件面板中访问Assets Essentials;此外，它还允许用户访问完整的Assets Essentials web用户界面，以使用web浏览器上传、组织、标记和查找数字资产。

其他Assets Essentials产品配置文件 —  **[!DNL Assets Essentials]管理员** 和 **[!DNL Assets Essentials]消费者用户**  — 用于不同的用户权限(应用程序管理员和通过Experience Cloud集成访问Assets Essentials的用户)。

有关如何将用户分配给Assets Essentials产品配置文件的更多信息，请参阅 [将用户分配给Assets Essentials产品配置文件](adminster-aem-assets-essentials.md#add-users-to-product-profiles).

## 安装Adobe资产链接 {#install-asset-link}

[!DNL Adobe Asset Link] 插件可通过两种方式进行安装并提供给创意用户：

* 创意用户可以通过 [!DNL Creative Cloud Desktop] 应用程序
* Creative Cloud管理员可以将Creative Cloud链接插件添加到Admin Console中的资产包

选择取决于组织IT政策。

**安装使用 [!DNL Creative Cloud Desktop] 应用程序** 描述 [此处](https://helpx.adobe.com/creative-cloud/kb/installingextensionsandaddons.html). 有两个插件可用并托管在上 [Adobe交换](https://exchange.adobe.com/) 市场，具体取决于Creative Cloud应用程序：

* 对于 [!DNL Adobe Photoshop], [!DNL Adobe Illustrator]和 [!DNL Adobe InDesign]: [Adobe资产链接CEP](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)
* 对于 [!DNL Adobe XD]: [Adobe资产链接](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)

**安装Creative Cloud包** 由Admin Console中的Creative Cloud管理员完成，方法是在构建部署包时包含资产链接插件，该部署包稍后可部署到用户计算机。 在“托管的选择插件”屏幕中，搜索 **Adobe资产链接** 在 **特色业务插件** 中。 有关更多信息，请参阅 [通过Admin Console打包应用程序](https://helpx.adobe.com/enterprise/using/package-apps-admin-console.html).

## 使用Adobe资产链接 {#use-asset-link}

创意用户现在可以将Adobe资产链接与Photoshop、Illustrator、InDesign或XD结合使用。 要在InDesign或Illustrator中打开面板，请转到Windows >扩展>Adobe资产链接。 在Photoshop中，转到窗口>扩展（旧版）>Adobe资产链接。

有关如何为Adobe XD设置Adobe资产链接的信息，请单击 [此处](https://helpx.adobe.com/cn/enterprise/using/adobe-asset-link-for-xd.html).

>[!NOTE]
>
>在使用Apple Silicon/M1硬件时，Adobe Photoshop需要使用Rosetta兼容模式来启动，以确保创意用户有权访问Adobe资产链接面板，因为该面板是使用CEP扩展技术构建的。 有关更多信息，请参阅 [Photoshop硅业](https://helpx.adobe.com/photoshop/kb/photoshop-for-apple-silicon.html).


使用Adobe资产链接可处理和修改存储在Assets Essentials存储库中的资产。 您可以执行各种任务，例如：

* 搜索和浏览资产

* 上传资源

* 排序和筛选资产

* 放置、下载和拖动资产

* 签出和签入资产

* 查看版本历史记录和文件详细信息

有关如何执行这些任务的说明，请参阅 [使用Adobe资产链接管理资产](https://helpx.adobe.com/in/enterprise/using/manage-assets-using-adobe-asset-link.html).

## 下一步

现在，您已将Creative Cloud应用程序与Assets Essentials集成， [将Adobe Workfront与Experience Manager Assets Essentials集成](integrate-assets-essentials-workfront.md).
