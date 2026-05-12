---
title: 在 Assets Essentials 中进行批量元数据编辑
description: 了解如何为 Assets Essentials 上提供的多个资产同时更新一个预定义的标准元数据字段集。
exl-id: 17185160-6c51-4581-a716-77b365ef3dd9
TQID: https://experienceleague.adobe.com/zfRAzwQWEhdCwSVuWKDz-ndudFtv-mIhmjzyNkg8sOQ
product_v2: id: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
feature_v2: id: a01bfd36-4ab8-4bf8-9dc0-5b45b890552e
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554id: f8a45b24-4be7-4f1b-909b-60d06b483a20
topic_v2: id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dc
source-git-commit: f026b389ce582ece5d2ca8745d291b1ae50d657e
workflow-type: tm+mt
source-wordcount: 649
ht-degree: 100%

---

<table>
    <tr>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="新建">
            <a href="https://experienceleague.adobe.com/zh-hans/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-prime-ultimate"><b>Dynamic Media Prime 和 Ultimate</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="新建">
            <a href="https://experienceleague.adobe.com/zh-hans/docs/experience-manager-cloud-service/content/assets/assets-ultimate-overview"><b>AEM Assets Ultimate</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="新建">
            <a href="http://experienceleague.adobe.com/zh-hans/docs/experience-manager-cloud-service/content/assets/integrate-aem-assets-edge-delivery-services"><b>AEM Assets 与 Edge Delivery Services 集成</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="新建">
            <a href="https://experienceleague.adobe.com/zh-hans/docs/experience-manager-cloud-service/content/assets/assets-view/aem-assets-view-ui-extensibility"><b>UI 可扩展性</b></a>
        </td>
          <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="新建">
            <a href="https://experienceleague.adobe.com/zh-hans/docs/experience-manager-assets-essentials/help/custom-search-filters"><b>自定义搜索过滤器</b></a>
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://experienceleague.adobe.com/zh-hans/docs/experience-manager-cloud-service/content/assets/best-practices/search-best-practices"><b>搜索最佳实践</b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/zh-hans/docs/experience-manager-cloud-service/content/assets/best-practices/metadata-best-practices"><b>元数据最佳实践</b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/zh-hans/docs/experience-manager-cloud-service/content/assets/content-hub/product-overview"><b>Content Hub</b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/zh-hans/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media-open-apis/dynamic-media-open-apis-overview"><b>具有 OpenAPI 功能的 Dynamic Media</b></a>
        </td>
        <td>
            <a href="https://developer.adobe.com/experience-cloud/experience-manager-apis/"><b>AEM Assets 开发人员文档</b></a>
        </td>
    </tr>
</table>

# 在 Assets Essentials 中进行批量元数据编辑{#how-to-edit-the-metadata-of-multiple-assets-simultaneously}

Assets Essentials 中的&#x200B;**批量元数据编辑**&#x200B;功能允许用户同时为多个资产文件编辑一个预定义的标准元数据字段集。 选择多个资产，一次批量更新这些资产的预定义的标准元数据集，而不是为每个资产单独更新其标准元数据。 此功能提高了大量资产中标准元数据属性的效率、一致性和准确性，从而提高资产的可搜索性，便于组织。

## 批量编辑资产元数据 {#how-to-bulk-edit-the-metadata-of-multiple-assets-on-assets-essentials}

执行以下步骤，一次性批量编辑多个资产的元数据：

1. 在 Assets Essentials 上点击 **Assets**。
1. 浏览特定的资产或者在搜索栏中使用关键词搜索资产。
1. 选择资产，然后点击顶部菜单中的&#x200B;**批量元数据编辑**。
   ![bulk-metadata-edit](/help/using/assets/bulk-metadata-edit1.png)
1. 在编辑元数据页面上，在&#x200B;**属性**&#x200B;面板中编辑以下字段：
   * **状态：**&#x200B;为选定的资产选择一个状态。
   * **有效期限：**&#x200B;设置一个日期，在此日期之后资产不再有效或不再需要。
   * **作者：**&#x200B;指定作者的姓名。
   * **关键词：**&#x200B;添加提供关于此资产的高级信息的特定词语或文本字符串，以提高资产的可发现性。 添加一个关键词，然后按下 Enter 或者返回，将另一个关键词添加到列表中。
   * **标记：**&#x200B;点击![标记图标](/help/using/assets/tags-icon.svg)，从可用的选项中选择标记。 标记提供了关于资产的更具体的信息，增强它们的可发现性。 标记应用于选定资产后，会显示在&#x200B;**属性**&#x200B;面板中。 如果找不到相关的标记，请创建标记，然后将其分配给选定的资产。 有关创建标记并将其分配给资产的详细信息，请参阅[在 Assets Essentials 中管理标记](/help/using/tagging-management.md)。
   * 点击&#x200B;**保存**，将上述元数据更新应用到选定的资产。 保存后，关键词和标记会附加上去，状态、有效期限和作者的更新详细信息将覆盖各自的现有详细信息。
     ![save-bulk-metadata-edit-properties](/help/using/assets/save-bulk-metadata-edit-properties2.png)

     >[!NOTE]
     >
     >您可以一次编辑 100 个资产的元数据。

要查看已应用于某个资产的元数据更新，请导航至资产详细信息页面（选择资产，然后点击&#x200B;**详细信息**），然后点击 ![](/help/using/assets/info-icon-solid-black.svg)，在&#x200B;**信息**&#x200B;面板中查看资产的元数据。

>[!NOTE]
>
>**状态**、**有效期限**、**作者**、**关键词**&#x200B;和&#x200B;**标记**&#x200B;是可用于批量元数据编辑的标准元数据属性，无论有哪些文件夹特有的元数据。 只有当这些元数据属性包含在元数据表单中并应用于资产文件夹时，它们才会显示在资产详细信息页面上。 如果在资产详细信息页面上找不到这些标准元数据属性，请编辑资产文件夹的元数据表单，将这些属性包含进去。 请参阅 [Assets Essentials 中的元数据](/help/using/metadata.md)，了解如何创建或编辑元数据表单以及将其应用到文件夹上。
