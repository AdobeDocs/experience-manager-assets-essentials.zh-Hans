---
title: 管理数字资产
description: 在 [!DNL Assets Essentials]中移动、删除、复制、重命名、更新资产，以及对其进行版本更新。
role: Business Practitioner,Leader
contentOwner: AG
source-git-commit: 3389908e3ba085362b48a18cd3c106e658484a96
workflow-type: tm+mt
source-wordcount: '585'
ht-degree: 0%

---


# 管理资产{#manage-assets}

您可以使用[!DNL Assets Essentials]的用户友好界面轻松执行各种数字资产管理(DAM)任务。 添加资产后，您可以搜索、下载、移动、复制、重命名、删除、更新和编辑资产。

使用[!DNL Assets Essentials]完成以下资产管理任务。 选择资产后，顶部的工具栏中会显示以下选项。

![选择资产时的工具栏选项](assets/toolbar-image-selected.png)

*图：工具栏中可用于选定图像的选项。*

* ![取消选](assets/do-not-localize/close-icon.png) 择图标取消选择所选内容。
* ![详细](assets/do-not-localize/edit-in-icon.png) 信息图标单击以预览资产并查看详细元数据。预览时，您可以查看版本和编辑图像。
* ![下载](assets/do-not-localize/download-icon.png) 图标将选定的资产下载到本地文件系统。
* ![删除](assets/do-not-localize/delete-icon.png) 图标删除选定的资产或文件夹。
* 

   <!-- ![checkout icon](assets/do-not-localize/checkout-icon.png) --> Checkout an asset.
* ![复制](assets/do-not-localize/copy-icon.png) 图标复制所选文件或文件夹。
* ![移动](assets/do-not-localize/move-icon.png) 图标将选定的资产或文件夹移动到存储库层次结构中的其他位置。
* ![“重命](assets/do-not-localize/rename-icon.png) 名”图标重命名选定的资产或文件夹。使用唯一名称，否则重命名会失败并出现警告。 您可以使用新名称重试。
* 
   <!-- ![assign task icon](assets/do-not-localize/assign-task-icon.png) --> Assign tasks to other users to collaborate on an asset.

您可以在资产缩略图上查看相同的选项。

![用于管理资产的资产缩略图的选项](assets/options-on-thumbnail.png)

[!DNL Assets Essentials] 工具栏中仅显示取决于选定资产类型的相关选项。

![选择资产时的工具栏选项](assets/toolbar-folder-selected.png)

*图：工具栏中选定文件夹的可用选项。*

![选择资产时的工具栏选项](assets/toolbar-pdf-selected.png)

*图：工具栏中可用于选定PDF文件的选项。*

## 下载和分发资产 {#download}

您可以选择一个或多个资产或文件夹，或者选择两者的组合，然后将所选内容下载到本地文件系统。 您可以编辑资产并再次上传或在[!DNL Assets Essentials]之外分发资产。 您还可以[下载资产的演绎版](/help/add-delete.md#renditions)。

## 资产版本控制 {#versions-of-assets}

<!-- 
TBD: query for engineering: How many versions are maintained. What happens when we reach that limit? Are old versions automatically removed? -->

[!DNL Assets Essentials] 版本资产。您可以查看版本历史记录、以前的版本，还可以将资产的以前版本恢复为最新版本（如果需要，可以将该版本还原为以前的版本）。 资产版本会在以下情况下创建：

* 上传与现有资产文件名相同，且与现有资产文件夹相同的新资产。 [!DNL Assets Essentials] 系统会提示覆盖以前的资产或将新资产另存为版本。请参阅[上传重复的资产](/help/add-delete.md#resolve-upload-fails)。

   ![上传时创建版本](assets/uploads-manage-duplicates.png)

   *图：上传与现有资产名称相同的资产时，您可以创建该资产的一个版本。*

* 编辑图像，然后单击&#x200B;**[!UICONTROL Save as Version]**。 请参阅[编辑图像](/help/edit-images.md)。

   ![将编辑的图像另存为版本](assets/edit-image2.png)

   *图：将已编辑的图像另存为版本。*

* 打开现有资产的版本。 单击&#x200B;**[!UICONTROL New Version]**，然后在存储库中上传较新版本的资产。

   ![用于从版本历史记录上传资产新版本的选项](assets/view-asset-versions2.png)

### 查看资产版本{#view-versions}

在上传资产的重复副本或已修改副本时，您可以创建其版本。 版本控制允许您查看历史资产，并根据需要还原到以前的版本。

要查看版本，请打开资产的预览，然后单击右侧边栏中的&#x200B;**[!UICONTROL Versions]** ![版本图标](assets/do-not-localize/versions-clock-icon.png)。 要预览特定版本，请选择它。 若要还原到该值，请单击&#x200B;**[!UICONTROL Make Latest]**。

您还可以从版本时间轴创建版本。 选择最新版本，单击&#x200B;**[!UICONTROL New Version]**，然后从本地文件系统上传资产的新副本。

![查看资产版本](assets/view-asset-versions1.png)

*图：查看资产的版本、还原到之前的版本或上传其他新版本。*
