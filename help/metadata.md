---
title: 管理元数据
description: 在 [!DNL Assets Essentials] 中管理资源的元数据
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: cfc105d1-41fc-4418-9905-b2a28a348682
source-git-commit: 02f28c00b387fbcac4cd917fab7763124fdd5d70
workflow-type: ht
source-wordcount: '1026'
ht-degree: 100%

---

# [!DNL Assets Essentials] 中的元数据 {#metadata}

元数据是指有关数据的数据或者描述。例如，作为资源，您的图像可以包含有关拍摄图像所用相机的信息或者任何版权信息。此信息是图像的元数据。元数据对于高效的资源管理非常关键。元数据是某个资源的所有可用数据的集合，但资源中并不一定包含元数据。

元数据可帮助您进一步分类资源，在数字化信息大量增长时非常有用。它可以基于文件名、缩略图和内存管理数百个文件。但是，这种方法不具备扩展性。随着涉及的人数以及托管资源数的增长，这种方法很快就会出现不足。

随着元数据的增加，数字资源的价值会随之增长，因为资源会变得：

* 更易于访问 - 系统和用户可以轻松地找到它。
* 更易于管理 - 您可以轻松地找到具有一组相同属性的资源并对其应用更改。
* 完整 - 元数据越多，资源就能携带更多信息和具体情境。

由于这些原因，Assets 为您提供了合适的方法来创建、管理和交换数字资源的元数据。

## 查看元数据 {#view-metadata}

要查看某个资源的元数据，请浏览到该资源或搜索该资源，然后在工具栏中单击&#x200B;**[!UICONTROL 详情]**。

![查看资源的元数据](assets/metadata-view1.png)

*图：要查看资源及其元数据，请在工具栏中单击&#x200B;**[!UICONTROL 详情]**或者双击该资源。*

标题、描述和上传日期等基本元数据在[!UICONTROL 基本]选项卡中提供。[!UICONTROL 高级]选项卡包含更多高级元数据，例如相机型号、镜头详细信息和地理位置标签。[!UICONTROL 标记]选项卡包含根据图像的内容自动应用的标记。

## 更新元数据 {#update-metadata}

您可以手动更新一些元数据字段。这些字段包括[!UICONTROL 标题]、[!UICONTROL 描述]、[!UICONTROL 作者]和[!UICONTROL 关键字]。

## 标记 {#tags}

[!DNL Assets Essentials] 使用 [Adobe Sensei](https://www.adobe.com/sensei.html) 提供的人工智能，自动将相关标记应用到您上传的所有资源。正如其名，这些标记被称为“智能标记”，可以帮助您快速找到相关资源，从而提升内容速度。智能标记是未包含在图像中的元数据示例。

智能标记根据图像的内容生成，近乎实时地应用。上传资源时，用户界面会在资源缩略图上显示[!UICONTROL 处理中]并保持片刻。处理完成后，您可以[查看元数据](#view-metadata)和智能标记。

![查看资源的智能标记](assets/metadata-view-tags.png)

*图：要查看资源的智能标记，请在工具栏中单击&#x200B;**[!UICONTROL 详情]**或者双击该资源。*

智能标记还包含以百分比显示的置信度分数。它指示与所应用标记对应的置信度。您可以审核自动应用的智能标记。

## 添加或更新标记 {#manually-tag}

在使用 [!DNL Adobe Sensei] 智能服务添加的智能标记之外，您还可以为资源添加多个标记。打开资源以预览，单击[!UICONTROL 标记]，然后在[!UICONTROL 关键词]字段中键入所需的关键词。要添加标记，请按 Return。[!DNL Assets Essentials] 近乎实时地对关键词编制索引，您的团队很快就可以使用新关键词来搜索更新的资源。

您也可以在[!UICONTROL 智能标记]部分中，删除由 [!DNL Assets Essentials] 自动添加到所有上传资源的标记。

## 元数据表单 {#metadata-forms}

默认情况下，Assets Essentials 提供了多个标准元数据字段。组织可能会有额外的元数据需求，需要更多元数据字段来添加特定于业务的元数据。企业可以利用元数据表单，将自定义元数据字段添加到资源的[!UICONTROL 详情]页面。特定于业务的元数据可以改进其资源的管理和发现。

您可以为不同的资源类型（不同的 MIME 类型）配置元数据表单。使用与文件的 MIME 类型相同的表单名称。Essentials 自动将上传的资源与表单的名称匹配。例如，如果存在名为 `PDF` 或 `pdf` 的元数据表单，则上传的 PDF 文档将包含该表单中定义的元数据字段。您可以从头开始创建表单，也可以重新利用现有表单。

>[!IMPORTANT]
>
>针对特定文件类型的新元数据表单将完全替换 [!DNL Assets Essentials] 提供的默认元数据表单。如果您删除或重命名元数据表单，则默认元数据字段将重新对新资源可用。

要创建元数据表单，请按照以下步骤操作：

1. 在左侧边栏中，单击&#x200B;**[!UICONTROL 设置]** > **[!UICONTROL 元数据表单]**。

   ![左侧边栏中的元数据表单选项](assets/metadata-forms-sidebar.png)

1. 在用户界面的右上角区域单击&#x200B;**[!UICONTROL 创建]**。
1. 提供表单的名称，然后单击&#x200B;**[!UICONTROL 创建]**。
1. 在右边栏的&#x200B;**[!UICONTROL 设置]**&#x200B;中提供选项卡的名称。
1. 从左边栏中提供的&#x200B;**[!UICONTROL 组件]**，将所需的组件拖动到表单中的选项卡上。按照所需顺序拖动组件。

   ![左侧边栏中的元数据表单选项](assets/metadata-form-new.png)

   *图：元数据表单创建界面，带有添加组件的选项和预览表单的选项。*

1. 对于各个组件，在右边栏的&#x200B;**[!UICONTROL 设置]**&#x200B;中提供名称，提供与所支持属性的映射。
1. （可选）对于组件，选择&#x200B;**[!UICONTROL 必需]**&#x200B;使该元数据字段为必填项，并选择&#x200B;**[!UICONTROL 只读]**&#x200B;使该字段在资产[!UICONTROL 详细]页面中不可编辑。
1. （可选）单击&#x200B;**[!UICONTROL 预览]**&#x200B;以预览您创建的表单。
1. （可选）添加多个选项卡并在每个选项卡中添加所需的组件。
1. 表单完成后，单击&#x200B;**[!UICONTROL 保存]**。

创建表单后，当用户上传具有匹配 MIME 类型的资源时，将会自动应用表单。

要重用现有的表单创建新表单，请选择一个元数据表单，在工具栏中单击&#x200B;**[!UICONTROL 复制]**，提供名称，然后单击&#x200B;**[!UICONTROL 确认]**。您可以编辑元数据表单来进行更改。更改表单后，它会用于在更改之后上传的资源。它不会更改现有资源。

## 后续步骤 {#next-steps}

* [观看视频，了解如何在 Assets Essentials 中管理元数据表单](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/configuring/metadata-forms.html)

* 利用 Assets Essentials 用户界面上的[!UICONTROL 反馈]选项提供产品反馈

* 通过右侧边栏中的[!UICONTROL 编辑此页面]![编辑页面](assets/do-not-localize/edit-page.png)或[!UICONTROL 记录问题]![创建 GitHub 问题](assets/do-not-localize/github-issue.png)来提供文档反馈

* 联系[客户关怀团队](https://experienceleague.adobe.com/?support-solution=General#support)

<!-- TBD: Cannot create a form using the second option. Documenting only the first option for now.
To reuse an existing form to create a new form, do one of these:

* Select a metadata form and click **[!UICONTROL Copy]** from the toolbar, provide a name, and click **[!UICONTROL Confirm]**.

* Click **[!UICONTROL Create]**, select **[!UICONTROL Use existing form structure as template]** option, and select an existing form. 
-->

<!-- TBD: Queries for PM and engg.

Can we edit the existing metadata in any form?

How to moderate smart tags?

Allow or deny list for smart tags?

What about Tags displayed just above Smart Tags in the UI?

Is there a detailed metadata tab. Where do the other details of an asset go?

How can one search based strictly on the metadata. Similar to AEM Assets GQL queries.
-->

<!-- TBD: Link to related articles if any.

>[!MORELIKETHIS]
>
>* [Search assets](search.md).
-->
