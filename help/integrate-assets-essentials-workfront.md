---
title: 将Assets Essentials与Adobe Workfront集成
description: 将Assets Essentials与Adobe Workfront应用程序集成，以便您能够访问Workfront应用程序中的Assets Essentials存储库。
source-git-commit: 7d49060ba2e02bd9c5caf9753ef56b5feed5b3df
workflow-type: tm+mt
source-wordcount: '616'
ht-degree: 16%

---


# 将Assets Essentials与Adobe Workfront集成 {#integrate-assets-essentials-workfront}

![切换设色和浅色主题的偏好设置](assets/cce-workfront.png)

## 到目前为止

之后 [配置Experience Manager Assets Essentials](adminster-aem-assets-essentials.md) 和 [将Creative Cloud应用程序与Assets Essentials集成](integrate-assets-essentials-creative-cloud.md)，则您可以在上进行构建，以将Adobe Workfront应用程序与Assets Essentials集成。

## 目标

* **受众**:Adobe Workfront管理员

* **目标**:将Assets Essentials与Adobe Workfront应用程序集成，以便您能够访问Workfront应用程序中的Assets Essentials存储库。

## 概述

[[!DNL Adobe Workfront]](https://www.workfront.com/) 是一个工作管理应用程序，可帮助您在一个位置管理工作的整个生命周期。 之间的本机集成 [!DNL Adobe Workfront] 和 [!DNL Assets Essentials] 使组织能够通过将工作与资产管理本质地联系起来，提高内容的投放速度和上市时间。 对于管理工作，用户可以在同一个解决方案中访问所需的文档和图像。

执行以下任务以将Workfront与Experience Manager Assets Essentials集成：

* [将用户添加到Workfront产品配置文件](#add-users-to-product-profiles)

* [将用户添加到Assets Essentials产品配置文件](#add-workfront-users-assets-essentials-product-profiles)

* [配置Experience Manager Assets Essentials集成](#configure-assets-essentials-integration)

## 将用户添加到Workfront产品配置文件 {#add-users-to-product-profiles}

要将用户添加到Workfront产品配置文件，请执行以下操作：

1. 访问 [Admin Console](https://adminconsole.adobe.com) 对于贵组织，单击 **[!UICONTROL 产品]** 在顶部栏中，单击 **[!UICONTROL Workfront]**，然后单击列表中的第一个实例。 请勿单击列表中的第二个和第三个实例。

   ![Admin Console 管理员配置文件](assets/workfront-instances.png)

   Admin Console显示唯一可用的产品配置文件。

1. 要将用户添加到产品配置文件，请单击该配置文件，然后单击 **[!UICONTROL 添加用户]**，提供用户详细信息，然后单击 **[!UICONTROL 保存]**.

   ![添加用户管理员配置文件](assets/add-users-workfront.png)

   添加用户时，用户将收到电子邮件邀请以开始使用。您可以在 [!DNL Admin Console] 的产品配置文件设置中关闭电子邮件邀请。

1. 要从组中删除某个用户，请单击改组，选择现有用户，然后选择&#x200B;**[!UICONTROL 删除用户]**。

有关如何使用Adobe Admin Console在Workfront中创建用户和系统管理员的更多信息，请参阅 [在Adobe Admin Console中管理用户](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FAdministration_and_Setup%2FAdd_users%2FCreate_and_manage_users%2Fadmin-console.htm&amp;_LANG=enus).

## 将用户添加到Assets Essentials产品配置文件 {#add-workfront-users-assets-essentials-product-profiles}

将Workfront用户分配到以下Assets Essentials产品配置文件之一：

* **[!DNL Assets Essentials]用户** 具有访问完整的Assets Essentials用户界面的权限。 这些用户可以在Assets Essentials应用程序中上传、组织、标记和查找数字资产。 此外，用户还可以在 [!DNL Adobe Workfront] 应用程序。
* **[!DNL Assets Essentials]消费者用户**:有权访问 [!DNL Adobe Workfront] 应用程序。

有关如何将用户分配给Assets Essentials产品配置文件的更多信息，请参阅 [将用户分配给Assets Essentials产品配置文件](adminster-aem-assets-essentials.md#add-users-to-product-profiles).

## 配置Experience Manager Assets Essentials集成 {#configure-assets-essentials-integration}

使用Workfront将用户添加到Admin Console和Assets Essentials产品配置文件后，您可以 [配置Experience Manager Assets Essentials集成](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2F_workfront-for-aem-asset-essentials.htm).

设置集成后，您可以：

* [从Experience Manager Assets Essentials链接资产和文件夹](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Flink-to-aem.htm&amp;_LANG=enus)

* [将文档发送到Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fsend-to-aem.htm&amp;_LANG=enus)

* [为Experience Manager Assets Essentials校样链接的资产](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fproof-linked-asset-aem.htm)

* [从Experience Manager Assets Essentials查看或下载链接的资产](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fview-download-asset.htm)
