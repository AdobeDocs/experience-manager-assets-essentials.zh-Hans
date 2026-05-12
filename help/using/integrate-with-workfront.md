---
title: 将 Assets Essentials 与 Adobe Workfront 集成
description: 将 Assets Essentials 与 Adobe Workfront 应用程序集成，以使您可在 Workfront 应用程序中访问 Assets Essentials 存储库。
exl-id: 9605fa3a-d454-48b5-9f84-b384eb1ad493
TQID: https://experienceleague.adobe.com/VpoSSKnrDT7do5QtUolcbPiw4lsO2DEbgLGvJxUslaw
product_v2:
  - id: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
  - id: f8a45b24-4be7-4f1b-909b-60d06b483a20
topic_v2:
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
source-git-commit: f026b389ce582ece5d2ca8745d291b1ae50d657e
workflow-type: tm+mt
source-wordcount: 570
ht-degree: 100%

---

# 将 Assets Essentials 与 Adobe Workfront 集成 {#integrate-assets-essentials-workfront}

[[!DNL Adobe Workfront]](https://www.workfront.com/) 是一个工作管理应用程序，可帮助您在一个地方管理整个工作生命周期。 [!DNL Adobe Workfront] 和 [!DNL Assets Essentials] 之间的本机集成使组织能够通过将工作和资源管理内在地联系起来，提高内容速度和上市时间。 对于管理工作，用户可以在同一个解决方案中访问所需的文档和图像。

请执行以下任务以将 Workfront 与 Experience Manager Assets Essentials 集成：

* [将用户添加到 Workfront 产品配置文件](#add-users-to-product-profiles)

* [将用户添加到 Assets Essentials 产品配置文件](#add-workfront-users-assets-essentials-product-profiles)

* [配置 Experience Manager Assets Essentials 集成](#configure-assets-essentials-integration)

## 将用户添加到 Workfront 产品配置文件 {#add-users-to-product-profiles}

要将用户添加到 Workfront 产品配置文件：

1. 访问您所在组织的 [Admin Console](https://adminconsole.adobe.com)，依次单击顶栏中的&#x200B;**[!UICONTROL 产品]**、**[!UICONTROL Workfront]**、列表中的第一个实例。 不要单击列表中的第二个和第三个实例。

   ![Admin Console 管理员配置文件](assets/workfront-instances.png)

   Admin Console 显示唯一可用的产品配置文件。

1. 要将用户添加到产品配置文件，请单击该配置文件，单击&#x200B;**[!UICONTROL 添加用户]**，提供该用户的详细信息，然后单击&#x200B;**[!UICONTROL 保存]**。

   ![添加用户管理员配置文件](assets/add-users-workfront.png)

   添加用户时，用户将收到电子邮件邀请以开始使用。 您可以在 [!DNL Admin Console] 的产品配置文件设置中关闭电子邮件邀请。

1. 要从组中删除某个用户，请单击改组，选择现有用户，然后选择&#x200B;**[!UICONTROL 删除用户]**。

有关如何用 Adobe Admin Console 在 Workfront 中创建用户和系统管理员的详细信息，请参阅[在 Adobe Admin Console 中管理用户](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&topicId=Content%2FAdministration_and_Setup%2FAdd_users%2FCreate_and_manage_users%2Fadmin-console.htm&_LANG=enus)。

## 将用户添加到 Assets Essentials 产品配置文件 {#add-workfront-users-assets-essentials-product-profiles}

将 Workfront 用户分配到以下 Assets Essentials 产品配置文件之一：

* **[!DNL Assets Essentials]用户**&#x200B;有权访问整个 Assets Essentials 用户界面。 这些用户可在 Assets Essentials 应用程序中上传、整理、标记和查找数字资源。 此外，这些用户还有权访问 [!DNL Adobe Workfront] 应用程序中嵌入的资源选择体验。
* **[!DNL Assets Essentials]使用者用户**：有权访问 [!DNL Adobe Workfront] 应用程序中嵌入的资源选择体验。

此外，还有 **[!DNL Assets Essentials]管理员**&#x200B;产品配置文件，它提供对应用程序的管理访问权限。

有关如何将用户分配给 Assets Essentials 产品配置文件的详细信息，请参阅[将用户分配给 Assets Essentials 产品配置文件](deploy-administer.md#add-users-to-product-profiles)。

## 配置 Experience Manager Assets Essentials 集成 {#configure-assets-essentials-integration}

使用 Admin Console 将用户添加到 Workfront 和 Assets Essentials 产品配置文件后，即可[配置 Experience Manager Assets Essentials 与 Adobe Workfront 的集成](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2F_workfront-for-aem-asset-essentials.htm)。

设置集成后，您可以：

* [链接 Experience Manager Assets Essentials 中的资产和文件夹](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Flink-to-aem.htm&_LANG=enus)

* [向 Experience Manager Assets Essentials 发送文件](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fsend-to-aem.htm&_LANG=enus)

* [验证 Experience Manager Assets Essentials 的链接资产](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fproof-linked-asset-aem.htm)

* [查看或下载 Experience Manager Assets Essentials 的链接资产](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fview-download-asset.htm)
