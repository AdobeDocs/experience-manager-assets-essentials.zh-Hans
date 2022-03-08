---
title: 部署和管理用户
description: 管理用例，如 [!DNL Assets Essentials].
role: Admin
exl-id: ef91126f-3aee-442b-b242-a6bf4034f3dc
source-git-commit: cbf75aaf05a0f3d798edf4d508325b28d9ca0dcb
workflow-type: tm+mt
source-wordcount: '1070'
ht-degree: 1%

---

# 部署 [!DNL Assets Essentials] 添加用户 {#administer}

[!DNL Adobe Experience Manager Assets Essentials] 由Adobe为其客户配置。 作为配置的一部分， [!DNL Assets Essentials] 会添加到 [!DNL Adobe Admin Console]. 客户还可以访问 [!DNL Experience Manager Cloud Manager] 作为部署工具，并 [!DNL Admin Console] 管理用户权限 [!DNL Assets Essentials] 解决方案。

## 自动部署Assets Essentials {#automatic-deployment-assets-essentials}

配置Assets Essentials解决方案后，管理员会收到来自Adobe的电子邮件。 电子邮件包含欢迎消息和要开始使用的链接。 此外，Adobe还会启动自动部署Assets Essentials的流程。 部署过程需要一小时才能完成。

从电子邮件中的链接，访问和登录 [Admin Console](https://adminconsole.adobe.com). 如果您拥有对多个组织帐户的管理员访问权限，请选择相应的组织或使用顶部栏中的切换器切换到该帐户。 完成自动部署过程后，将 [!DNL AEM Assets Essentials] 在 [!DNL Admin Console].

![Assets Essentials部署](assets/assets-essentials-deployment.png)

成功部署Assets Essentials解决方案后，管理员需要执行以下任务：

* [管理用户访问权限](#add-users-to-essentials) 组织成员 [!DNL Assets Essentials].
* （可选） [查看服务状态和日志](#view-logs).

>[!NOTE]
>
>如果Assets Essentials在2022年1月06日之前配置，请执行 [Cloud Manager中的部署步骤](#deploy-essentials) 管理组织成员的用户访问权限之前。


## 用户管理 {#add-users-to-essentials}

管理员可管理哪些用户有权访问 [!DNL Assets Essentials]. 管理员使用 [!DNL Adobe Admin Console] 添加或删除用户访问权限。 [!DNL Assets Essentials] 具有以下两种类型的用户访问权限。

* **[!DNL Assets Essentials]用户** 拥有完整用户界面的访问权限。 这些用户可以上传、组织、标记和查找数字资产。
* **[!DNL Assets Essentials]消费者用户**:有权访问 [!DNL Adobe Journey Optimizer] 电子邮件模板编辑器。 有关更多信息，请参阅 [使用 [!DNL Assets Essentials] in [!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html).

在 [!DNL Admin Console]，这两种访问类型由两种 [!UICONTROL 产品配置文件]. 要向两个用户档案中的任意一个添加和删除组织成员，请执行以下步骤：

1. 访问 [!DNL Admin Console] 对于贵组织，单击 **[!UICONTROL 产品]** 在顶部栏中，单击 **[!UICONTROL AEM Assets Essentials]**，然后单击 [!DNL Assets Essentials] 环境。 [!DNL Assets Essentials] 具有两个产品配置文件，它们表示常规用户和消费者用户的访问权限。

   ![两种用户的两个配置文件](assets/adminconsole-user-types.png)

   *图：可使用两个配置文件来添加这两种类型的用户。*

1. 要将用户添加到群组，请单击该群组，选择 **[!UICONTROL 添加用户]**，提供用户详细信息，然后单击 **[!UICONTROL 保存]**. 添加用户时，用户会收到开始使用的电子邮件邀请。 您可以在 [!DNL Admin Console].

   ![将用户添加到 [!DNL Assets Essentials]](assets/adminconsole-add-user.png)

   *图：将用户添加到 [!DNL Assets Essentials] 从 [!DNL Admin Console].*

1. 要从群组中删除用户，请单击该群组，选择现有用户，然后选择 **[!UICONTROL 删除用户]**.

>[!TIP]
>
>在 [!DNL Admin Console]，则可以使用CSV文件批量管理用户。 要了解更多信息，请参阅 [[!DNL Admin Console] 文档](https://helpx.adobe.com/enterprise/using/accounts.html).

## 查看服务状态和访问日志 {#view-logs}

配置后，管理员将部署 [!DNL Assets Essentials] 一次。 初始部署后，Adobe会进行服务维护和更新。 管理员可以使用 [!DNL Cloud Manager] 用户界面来检查服务状态并下载最近的访问日志。

1. 用户报告问题时，请检查 [!DNL Assets Essentials] 在 **[!UICONTROL 计划概述]** 界面。 在解决方案的正常工作过程中，状态为 `Running`. 如果 [!DNL Cloud Manager] 显示任何其他状态，请在 [!DNL Admin Console] 支持部分。

   ![状态 [!DNL Assets Essentials] in [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *图：的正常状态 [!DNL Assets Essentials] in [!DNL Cloud Manager] is `Running`.*

1. 要下载最近的访问日志，请单击 ![选项图标](assets/do-not-localize/options-ellipses-icon.png)，选择 **[!UICONTROL 下载日志]**，并按照屏幕上的说明进行操作。 您可以使用日志审核HTTPS访问请求。

   ![ 用于下载访问日志的选项](assets/cloudmanager-download-logs.png)

   *图：用于下载访问日志的选项。*

## 部署 [!DNL Assets Essentials] {#deploy-essentials}

>[!NOTE]
>
>仅当在2022年1月06日之前配置了Assets Essentials时，才执行这些步骤。

配置后， [!DNL Assets Essentials] 授权将添加到您组织的 [!DNL Admin Console]. 组织管理员必须先部署该解决方案，然后才能将其提供给用户。 管理员使用 [!DNL Cloud Manager] 用户界面。 初始部署后，Adobe会进行服务维护和更新。 配置解决方案后，管理员会收到来自Adobe的电子邮件。 电子邮件包含欢迎消息和要开始使用的链接。 要部署，请执行以下步骤：

1. 从电子邮件中的链接，访问和登录 [Admin Console](https://adminconsole.adobe.com). 如果您拥有对多个组织帐户的管理员访问权限，请选择相应的组织或使用顶部栏中的切换器切换到该帐户。 产品卡 [!DNL Assets Essentials] 在 [!DNL Admin Console].

   ![[!DNL Assets Essentials] 卡入 [!DNL Admin Console]](assets/essentials-in-admin-console.png)

   *图： [!DNL Assets Essentials] 卡入 [!DNL Admin Console].*

   >[!NOTE]
   >
   >如果您可以查看 **[!UICONTROL AEM Assets Essentials]** 在产品部分中添加卡片，而不是 **[!UICONTROL AEM Assets Essentials - Cloud Manager]** 卡，Assets Essentials的部署已完成。 您可以跳过其余步骤。

1. 将您自己作为管理员添加到 `AEM Assets Essentials - Cloud Manager` 中的产品配置文件 [!DNL Admin Console]. 您可以添加组织的其他成员，也可以添加多个管理员，而不是您自己。

1. 单击 ![添加图标](assets/do-not-localize/add-icon.svg) to [!UICONTROL 选择产品配置文件]，然后选择 [!UICONTROL 部署管理器 — Assets Essentials] 作为 **[!UICONTROL 产品配置文件]**. 此步骤中添加的用户会收到来自Adobe的电子邮件，该电子邮件具有 [!DNL Cloud Manager] 和可以进行部署。

   ![添加管理员并在 [!DNL Admin Console]](assets/adminconsole-user1.png)

   *图：添加管理员并在 [!DNL Admin Console].*

1. 访问 [!DNL Cloud Manager]，单击电子邮件中具有 [!DNL Cloud Manager]. 或者，访问 [https://experience.adobe.com/#/cloud-manager/](https://experience.adobe.com/#/cloud-manager/) 中。

1. 在Cloud Manager用户界面中，单击 **[!UICONTROL 添加程序]** 中。

1. 提供您选择的名称，并（可选）上传图像(它表示 [!DNL Cloud Manager])，然后单击 **[!UICONTROL 创建]**. [!DNL Cloud Manager] 设置程序需要几分钟。

1. 程序准备就绪后，将指针悬停在图块上并单击 ![添加环境图标](assets/do-not-localize/add-environment-icon.png).

1. 添加 [!DNL Assets Essentials] 为贵组织提供服务，单击 **[!UICONTROL 添加环境]**，选择名称和部署区域，然后单击 **[!UICONTROL 保存]**. 以后无法更改部署区域。 尝试匹配的部署区域 [!DNL Assets Essentials] 与您打算使用的其他解决方案的部署区域 [!DNL Assets Essentials]. 匹配是确保以最快的速度对数字资产进行网络访问，并确保尽可能最短的延迟。

   ![在 [!DNL Cloud Manager]](assets/cloudmanager-add-environment-for-essentials.png)

   *图：在 [!DNL Cloud Manager] 开始使用 [!DNL Assets Essentials].*

1. 几分钟后，成功创建环境后，您便可以访问 [!DNL Admin Console] 并将贵组织的用户添加到 [!DNL Assets Essentials] 解决方案。 单击 ![选项图标](assets/do-not-localize/options-ellipses-icon.png) ，然后选择 **[!UICONTROL 管理访问权限]** 选项。

   ![中的就绪环境 [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *图：中的环境 [!DNL Cloud Manager] 已准备好使用。*

>[!MORELIKETHIS]
>
>* [[!DNL Admin Console] 帮助](https://helpx.adobe.com/enterprise/using/admin-console.html)
>* [[!DNL Cloud Manager] 帮助](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=zh-Hans)
>* [Adobe Journey Optimizer文档](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html)
>* [发行说明](release-notes.md)
>* [开始使用 [!DNL Assets Essentials]](get-started.md)

