---
title: 在 [!DNL Assets Essentials]中搜索和发现资产
description: 在 [!DNL Assets Essentials]中搜索和发现资产。
role: Business Practitioner
source-git-commit: 3389908e3ba085362b48a18cd3c106e658484a96
workflow-type: tm+mt
source-wordcount: '386'
ht-degree: 1%

---


# 在[!DNL Assets Essentials] {#search-assets}中搜索资产

[!DNL Assets Essentials] 提供有效的搜索功能，默认情况下只能使用。搜索是全文搜索，因为它是全文搜索。 强大的搜索功能可让您快速发现适当的资产并帮助您提高内容速度。 [!DNL Assets Essentials] 提供全文搜索，甚至通过元数据（如智能标记、标题、创建日期和版权）进行搜索。

要搜索资产，请

* 在页面顶部的搜索框中单击。 默认情况下，它会搜索您当前正在浏览的文件夹中。 执行下列操作之一：

   ![搜索框](assets/search-box.png)

   * 使用关键字搜索，并（可选）更改文件夹。 按返回。

   * 直接搜索最近查看的资产，以开始使用该资产。 单击搜索框，然后从建议中选择最近查看的资产。

## 筛选搜索结果{#refine-search-results}

您可以根据以下参数筛选搜索结果。

![搜索过滤器](assets/filters1.png)

*图：根据各种参数筛选搜索的资产。*

* 文件类型：按支持的文件类型（即`Images`、`Documents`和`Videos`）筛选搜索结果。
* MIME类型：筛选一种或多种支持的文件格式。<!-- TBD:  [supported file formats](/help/supported-file-formats.md). -->
* 图像大小：提供用于筛选图像的最小和最大尺寸中的一个或多个。 大小以像素为单位提供，而不是图像的文件大小。
* 创建日期：元数据中提供的资产创建日期。 使用的标准日期格式为`yyyy-mm-dd`。
* 修改日期：资产的上次修改日期。 使用的标准日期格式为`yyyy-mm-dd`。

您可以按`Name`、`Relevancy`、`Size`、`Modified`和`Created`的增减顺序对搜索的资产进行排序。

## 保存的搜索 {#saved-search}

在[!DNL Assets Essentials]中，搜索功能非常简单。 在搜索框内，您不仅可以键入关键字并按返回查看结果，而且只需一次单击即可快速再次搜索最近搜索的关键词。

您还可以根据有关元数据和资产类型的特定条件筛选搜索结果。 对于常用的过滤器，为了改善搜索体验，[!DNL Assets Essentials]允许您保存搜索参数。 然后，您可以选择保存的搜索以进行搜索，并只需单击一次即可应用过滤器。

要创建保存的搜索，请搜索某些资产，应用一个或多个过滤器，然后单击[!UICONTROL Filters]面板中的[!UICONTROL Save Search]。

![从“过滤器”面板保存搜索](assets/saved-search.png)

<!-- TBD: Search behavior. Full-text search. Ranking and rank boosts. Hidden assets.
Report poor UX that users can only save a filtered search and not a simple search.
.
Are other supported files fully indexed and support full-text search? Eg. audio/videos files can at best have metadata indexed.
Anything about ranking of assets displayed in search results?

What about temporarily hiding an asset (suspending search on it) from the search results? If an asset is undergoing review collaboration, should it be used by others? Should it be hidden in search?

When userA is searching and userB add an asset that matches search results, will the asset display in search as soon as userA refreshes the page? Assuming indexing is near real-time. May not be so for bulk uploads.
-->