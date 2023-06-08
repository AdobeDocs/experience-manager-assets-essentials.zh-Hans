---
title: 为带有工作管理解决方案的 Creative Cloud Pro 设置 Assets Essentials
description: 本教程介绍的管理员历程使 Assets Essentials 应用程序能够与 Creative Cloud 桌面应用程序和 Adobe Workfront 应用程序集成。Creative Cloud 桌面应用程序包括 Adobe Photoshop、Adobe Illustrator、Adobe InDesign 和 Adobe XD。
exl-id: a5e9e0c3-35ec-41de-9656-f4f0f88946c7
source-git-commit: 65200f73a954e4ebf4fbd6dc3a819acc6e0beda4
workflow-type: tm+mt
source-wordcount: '941'
ht-degree: 100%

---

# 带有工作管理解决方案的 Creative Cloud Pro 的 Assets Essentials {#creative-cloud-enterprise-user-journeys}

![切换深色和浅色主题的偏好](assets/cce-next-banner-landing-page.png)

## 简介 {#introduction}

带有工作管理解决方案的 Creative Cloud Pro 企业版集成了创意、内容和工作管理工具，以提高您制作创意内容和快速实现业务目标的能力。该解决方案包括以下组件：

* Creative Cloud Pro

* Adobe Workfront

* Experience Manager Assets Essentials

本教程介绍的管理员历程使 Assets Essentials 应用程序能够与 Creative Cloud 桌面应用程序和 Adobe Workfront 应用程序集成。Creative Cloud 桌面应用程序包括 Adobe Photoshop、Adobe Illustrator、Adobe InDesign 和 Adobe XD。

## 部署类型 {#deployment-types}

由于该解决方案包含来自 Creative Cloud 和 Adobe Experience Cloud 的应用程序和服务，因此它们可能部署在您公司的一个或两个 Adobe Admin Console 中。

如果部署在 Admin Console 中，则需要额外的配置步骤：

* Creative Cloud 服务和应用程序（Creative Cloud Pro 企业版和可选模块）在[ Adobe Admin Console 中进行管理，用于 Creative Cloud 部署](https://helpx.adobe.com/content/help/en/enterprise/admin-guide.html)。

* Adobe Workfront 和 Adobe Experience Manager Assets Essentials 在 [Adobe Admin Console 中管理，以使用 Experience Cloud solutions 解决方案](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html)。

要集成 Creative Cloud 和 Assets Essentials 应用程序，Creative Cloud 的 Admin Console 中可用的用户必须在 Experience Cloud 的 Admin Console 中可用。要使用户在 Experience Cloud Admin Console 中可用，请创建一个目录，以在这两个 Admin Console 之间建立[目录信任](https://helpx.adobe.com/cn/enterprise/using/set-up-identity.html#directory-trusting)关系。

![Creative Cloud 用户](assets/creative-cloud-users.svg)

如图所示，基于两个控制台之间的信任关系，Creative Cloud 用户可自动在 Experience Cloud Admin Console 中变得可用。然后您可以将用户添加到 Assets Essentials 产品配置文件。因此，Creative Cloud 用户可以访问 Adobe Asset Link 应用程序，该应用程序可以与 Assets Essentials 存储库交互。有关更多信息，请参阅[将 Assets Essentials 与 Creative Cloud 应用程序集成](integrate-with-creative-cloud.md)。

## Experience Manager 文档历程 {#documentation-journeys}

文档历程可将许多不同的，甚至复杂的主题和功能联系在一起；它提供了一种叙述，可帮助读者（可能是 Assets Essentials 的新手）从头到尾理解和解决业务问题，同时会假设读者不具备丰富的背景或 Assets Essentials 知识。

文档历程是围绕最佳实践准则而设计的，其中包含了 Adobe 的最新研究、Adobe 顾问提供的成熟实施经验以及来自客户项目的反馈。

## 前提条件

* [访问 Adobe Admin Console 以获得 Experience Cloud 解决方案](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html)

* [访问 Adobe Admin Console，以进行 Creative Cloud 企业版部署](https://helpx.adobe.com/cn/enterprise/admin-guide.html)

## 管理员 Experience Manager Assets Essentials {#administer-assets-essentials}

![切换深色和浅色主题的偏好](assets/cce-assets.png)

Adobe Experience Manager Assets Essentials 是 Adobe Experience Manager Assets 的一个新的轻量级版本。Assets Essentials 通过简化且一致的用户界面提供统一的资源管理和协作功能。其易用性使得更多创意与营销团队可以轻松地存储、发现和分发数字资源。

Adobe Experience Manager Assets Essentials 由 Adobe 为其客户提供。作为资源调配的一部分，Assets Essentials 会被添加至 Adobe Admin Console 中的客户组织中。

管理员使用 Admin Console 管理用户对 Assets Essentials 产品的权限：

* 添加用户组

* 向用户组添加用户

* 将用户添加到 Assets Essentials 产品配置文件

在 Admin Console 中管理用户权限后，管理员可以使用 Assets Essentials 应用程序来：

* 创建文件夹结构以最佳的方式支持组织的需要

* 管理对文件夹结构的权限

* 设置元数据表单

[![参阅指南](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](deploy-administer.md)

您现在已经配置并管理 Assets Essentials 应用程序，请[将 Creative Cloud 应用程序与 Experience Manager Assets Essentials 应用程序集成](integrate-with-creative-cloud.md)。

## 将 Creative Cloud applications 应用程序与 Experience Manager Assets Essentials 集成 {#administer-creative-cloud-applications}

![切换深色和浅色主题的偏好设置](assets/cce-creative-cloud.png)

通过[Adobe Asset Link 应用程序内置面板](https://www.adobe.com/cn/creativecloud/business/enterprise/adobe-asset-link.html)，创意专业人员可从受支持的[!DNL Assets Essentials]桌面应用程序中连接到[!DNL Adobe Creative Cloud]存储库。该面板可用于 [!DNL Adobe Photoshop]、[!DNL Adobe Illustrator]、[!DNL Adobe InDesign] 和 [!DNL Adobe XD]。它简化了对资源的访问，随之可以提升内容速度。

该教程可指导您将 [!DNL Adobe Photoshop]、[!DNL Adobe Illustrator]、[!DNL Adobe InDesign] 和 [!DNL Adobe XD] 应用程序与 Experience Manager Assets Essentials 集成。

目标：

* 在 Creative Cloud 和 Experience Cloud Admin Console 之间创建目录信任关系

* 将 Creative Cloud 用户添加到 Assets Essentials 产品配置文件

* 安装 Adobe Asset Link

* 使用 Adobe Asset Link

[![参阅指南](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-with-creative-cloud.md)

您现在已将 Creative Cloud 应用程序与 Assets Essentials 集成，请[将 Adobe Workfront 与 Experience Manager Assets Essentials 集成](integrate-with-workfront.md)。

## 将 Adobe Workfront 与 Experience Manager Assets Essentials 集成 {#administer-adobe-workfront}

![切换深色和浅色主题的偏好设置](assets/cce-workfront.png)

[[!DNL Adobe Workfront]](https://www.workfront.com/) 是一个工作管理应用程序，可帮助您在一个地方管理整个工作生命周期。[!DNL Adobe Workfront] 和 [!DNL Assets Essentials] 之间的本机集成使组织能够通过将工作和资源管理内在地联系起来，提高内容速度和上市时间。对于管理工作，用户可以在同一个解决方案中访问所需的文档和图像。

该教程可指导您管理 Adobe Workfront，然后将其与 Experience Manager Assets Essentials 集成。

目标：

* 将用户添加到 Workfront 产品配置文件

* 将用户添加到 Assets Essentials 产品配置文件

* 配置 Experience Manager Assets Essentials 集成

[![参阅指南](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-with-workfront.md)
