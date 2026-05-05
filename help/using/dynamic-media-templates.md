---
title: 如何管理 Dynamic Media 模板？
description: 了解如何使用所见即所得模板编辑器创建 Dynamic Media 模板，并包含多个图像和文本图层，以快速创建横幅和宣传单，并在下游应用程序中使用它们。
hide: true
hidefromtoc: true
role: User
exl-id: 07de648e-4ae2-4524-8e05-3cf10bb6006d
source-git-commit: 4c176db86c9f3219f2cb63edda71435a2aa76850
workflow-type: tm+mt
source-wordcount: '3000'
ht-degree: 99%

---

# Dynamic Media 模板{#dynamic-media-templates}

| [搜索最佳实践](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-cloud-service/content/assets/best-practices/search-best-practices) | [元数据最佳实践](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-cloud-service/content/assets/best-practices/metadata-best-practices) | [Content Hub](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-cloud-service/content/assets/content-hub/product-overview) | [AEM Assets 开发人员文档](https://developer.adobe.com/experience-cloud/experience-manager-apis/) |
| ------------- | --------------------------- |---------|-----|

>[!CONTEXTUALHELP]
>id="assets_dm_templates"
>title="管理 Dynamic Media 模板"
>abstract="通过易于使用的所见即所得界面，即时创建并个性化设置图像和文本横幅，并将 Dynamic Media URL 嵌入任何第一方或第三方应用程序中，以打造极具吸引力的体验。 尝试一下！"
>additional-url="https://images-tv.adobe.com/mpcv3/4477/b74738ca-888c-4a37-9a9e-14fabd68ee45_1738206841.854x480at800_h264.mp4" text="观看视频"

使用所见即所得模板编辑器创建 Dynamic Media 模板，并包含多个图像和文本图层，以快速创建横幅和宣传单，并在下游应用程序中使用它们。 您还可以为模板中包含的图像和文本图层添加参数，使用 [Dynamic Media URL](https://experienceleague.adobe.com/zh-hans/docs/commerce-admin/content-design/wysiwyg/storage/catalog-urls-dynamic-media) 实时更新这些图层的值。

几个主要功能包括：

* **Dynamic Media 所见即所得模板编辑器：**&#x200B;通过图像和文本图层创建可自定义横幅。
* **图层参数化：**&#x200B;为图层定义动态键值对，以启用实时更新。
* **Dynamic Media URL 支持：**&#x200B;为模板使用 Dynamic Media URL，集成来自第一方或第三方应用程序的个性化数值。
* **图层可见性控件：**&#x200B;根据需要动态隐藏或显示图层。
* **智能调整文本大小：**&#x200B;按照指定的区域自动调整文本大小。

Dynamic Media 模板的一些主要优势包括：

* **优化 1:1个性化：**&#x200B;根据实时客户信号定制内容。
* **减少手动工作：**&#x200B;自动进行并加快内容创建和管理。
* **确保一致的全渠道体验：**&#x200B;保持跨渠道的品牌一致性。
* **有效地重复使用内容：**&#x200B;避免一次性使用内容，通过动态的参数化模板进行扩展。
* **降低风险：**&#x200B;实时更新定价、折扣和链接。
* **提高客户参与度：**&#x200B;推动与上下文相关的交互式体验。

>[!NOTE]
>
>订阅了增强安全性 SKU 的客户无法在这个云服务计划上使用任何 Dynamic Media 功能，包括 Dynamic Media 模板。

## 开始之前{#prerequisites-for-dynamic-media-wysiwyg-template}

要创建 Dynamic Media 模板，您必须：

1. 具有 Dynamic Media 访问权限。
1. [将您的 AEM Assets 实例中可用的图像与 Dynamic Media 同步，以将其用于创建模板](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-cloud-service/content/assets/dynamicmedia/config-dm)。
1. 已在触屏UI上验证以下内容：
   * 在&#x200B;**[!UICONTROL 编辑 Dynamic Media 配置页面]**&#x200B;中，**[!UICONTROL 默认情况下设为禁用]**&#x200B;的 **[!UICONTROL Dynamic Media 同步模式]**&#x200B;未应用于任何 AEM 文件夹（未勾选&#x200B;**[!UICONTROL 同步所有内容]**）。 有关详细信息，请参阅[配置 Dynamic Media 云服务](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-cloud-service/content/assets/dynamicmedia/config-dm)。
   * 对于模板创建后保存其中的目标文件夹或子文件夹，**[!UICONTROL Dynamic Media 同步模式]**&#x200B;设置为&#x200B;**[!UICONTROL 为子文件夹启用]**。 有关详细信息，请参阅[配置 Dynamic Media 云服务](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-cloud-service/content/assets/dynamicmedia/config-dm)。

## 创建 Dynamic Media 所见即所得模板{#how-to-create-dynamic-media-wysiwyg-template}

按照以下步骤创建 DM 模板：

1. [创建一个空白画布](#create-a-canvas)
1. [将图像添加到画布上](#add-images-to-the-canvas)
1. [在画布中添加文本图层](#add-text-to-the-canvas)
1. [编辑或删除一个图层](#edit-or-delete-a-layer)
1. [参数化图层](#parameterise-a-layer)

### 创建一个空白画布{#create-a-canvas}

按照以下步骤创建一个空白画布：

1. 导航到 Assets Essentials，点击左侧面板中可用的 **[!UICONTROL Dynamic Media Assets]**。

   ![Dynamic Media 模板](/help/using/assets/DM-Assets1.png)

1. 点击&#x200B;**[!UICONTROL 创建模板]**，将模板保存在 Dynamic Media Assets 下，或者导航到一个文件夹，然后点击&#x200B;**[!UICONTROL 创建模板]**，将模板保存在这个文件夹中。 现在会显示&#x200B;**[!UICONTROL 新模板]**对话框。
   ![如何创建可实时自定义的动态模板](/help/using/assets/new-template.png)
要在 **[!UICONTROL Dynamic Media Assets]** 下[创建文件夹](/help/using/add-delete.md)，请在 **[!UICONTROL Assets]** 中创建文件夹。 **[!UICONTROL Assets]** 下面的文件夹树会复制在 **[!UICONTROL Dynamic Media Assets]** 下面。
1. 指定模板名称，定义画布宽度和高度，然后点击&#x200B;**[!UICONTROL 创建]**。 屏幕上会显示一个空白画布，画布的两侧有用于创建模板的菜单选项。 将鼠标悬停在菜单选项上，可查看相应的工具提示。
   ![实时可自定义模板](/help/using/assets/blank-canvas-page.png)

>[!NOTE]
>
> 允许的宽度和高度范围从 50 到 5000。

**右窗格中的菜单选项：**&#x200B;使用这些选项将必要的图像和文本图层添加到画布中。

* ![DM 模板](/help/using/assets/add-image.svg)：点击将图像添加到画布中。
* ![可自定义的模板](/help/using/assets/add-text.svg)：点击将文本添加到画布中。
* ![可自定义的模板](/help/using/assets/show-layers-list.svg)：点击查看画布上所有图层（图像和文本）的列表。 添加到画布中的每个图像和文本都展示为一个单独的图层。

**左窗格中的菜单选项：**&#x200B;将这些选项用于下面提到的常用编辑器操作。

* ![DM 模板](/help/using/assets/layer-selector.svg)：选择一个图层。
* ![创建可立即自定义的模板](/help/using/assets/undo.svg)：点击撤消上一个操作，或者按下 **Ctrl** + **Z** (Windows) 或 **Cmd** + **Z** (Mac)。
* ![用于快速创建横幅的模板](/help/using/assets/redo.svg)：点击重做上一个操作，或者按下 **Ctrl** + **Y** (Windows) 或 **Cmd** + **Y** (Mac)。
* ![用于快速创建宣传单的模板](/help/using/assets/zoomin.svg)：点击放大画布，或者按下 **Ctrl** + **+** (Windows) 或 Cmd + **+** (Mac)。
* ![用于快速创建横幅的模板](/help/using/assets/ZoomOut-1.svg)：点击缩小画布，或者按下 **Ctrl** + **-** (Windows) 或 **Cmd** + **-** (Mac)。
* 如果没有编辑文本或属性，请按下 **Backspace** 或 **delete** 删除选定的图层。

在画布图层上点击![用于快速创建宣传单的模板](/help/using/assets/show-layers-list.svg) **>**&#x200B;更多选项 (![](/help/using/assets/three-dots.svg))，可在创建模板时随时编辑画布尺寸。
![](/help/using/assets/edit-canvas1.png)

>[!NOTE]
>
> 模板最多允许 20 个图层，包括画布。

### 将图像添加到画布上{#add-images-to-the-canvas}

按照以下步骤将图像添加到画布中：

1. 点击![立即创建横幅](/help/using/assets/add-image.svg)，显示[资产选择器](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-cloud-service/content/assets/manage/asset-selector/overview-asset-selector)面板。 面板会显示您的 AEM Assets 实例中同步到 Dynamic Media 的图像。
1. 浏览面板或使用搜索栏中的关键词查找特定的图像。
1. 将图像拖放到画布上，以供使用。 查看[**[!UICONTROL 属性面板]**](#reposition-resize-delete-a-layer)，可将画布上的图层调整大小或重新定位。
   ![几秒内创建横幅](/help/using/assets/add-image-to-canvas.png)

### 在画布中添加文本图层{#add-text-to-the-canvas}

按照以下步骤将文本图层添加到画布中：

1. 点击![快速创建新横幅](/help/using/assets/add-text.svg)，将文本图层添加到画布中，并打开属性面板。
1. 选择图层，点击文本进行更新。
1. 在属性面板中启用&#x200B;**[!UICONTROL 智能调整文本大小]**，可自动调整文本长度和字体大小，最佳适应指定区域。
   ![最佳可自定义横幅](/help/using/assets/add-text-layer.png)

查看[**[!UICONTROL 属性面板]**](#reposition-resize-delete-a-layer)，将图层重新定位、调整大小、旋转或删除。 在面板中更改&#x200B;**[!UICONTROL 文本]**&#x200B;部分中相应字段的值，可将文本格式设置为所需的字体、大小、颜色、样式、（在图层中的）对齐方式。

>[!NOTE]
>
> 要使用与默认 Adobe Sans F2 字体系列不同的字体，您需要将该字体文件上传并发布到 AEM Assets 和 Dynamic Media。 如果您的实例中有一些旧字体，请确保[重新处理](/help/using/reprocessing.md)，然后在模板编辑器中查看它们。

### 编辑或删除一个图层 {#edit-or-delete-a-layer}

按照以下步骤编辑或删除一个画布图层：

1. 点击![支持动态更新的模板](/help/using/assets/show-layers-list.svg)，然后在画布上或从图层列表中选择这个图层。
1. 点击&#x200B;**更多选项**（![支持实时更新的模板](/help/using/assets/three-dots.svg)），可编辑或删除图层。
1. 点击&#x200B;**[!UICONTROL 删除]**&#x200B;可删除图层。
1. 点击&#x200B;**[!UICONTROL 编辑]**，通过[**[!UICONTROL 属性面板]**](#reposition-resize-delete-a-layer)编辑图层。
   ![快速横幅创建](/help/using/assets/edit-delete-layer.png)

### 属性面板{#properties-panel}

要导航到图层的属性面板，请执行以下操作：

1. 点击![快速创建内容](/help/using/assets/show-layers-list.svg)。
1. 从列表中选择图层。

面板中显示图层中心点在画布平面上的位置（X 和 Y 值）、图层的尺寸（宽度和高度）和文本格式选项。

![快速创建内容](/help/using/assets/properties-panel.png)

在图层的属性面板中选择画布上的另一个图层，导航到其属性面板。


#### 将图层重新定位、调整大小、旋转或删除{#reposition-resize-delete-a-layer}

查看这些常见的用于编辑文本或图像图层的图层编辑操作：

* **重新定位图层：**&#x200B;拖动图层，将其移到画布上的任意位置。 此操作会更新属性面板中的 X 和 Y 值。
* **调整图层大小：**&#x200B;选择图层，拖动其边缘手柄以调整大小。 此操作会更新属性面板中的 W（宽度）和 H（高度）值。
* **旋转图层：**&#x200B;拖动垂直位于图层上方的方形手柄，使其围绕其中心旋转。 此操作会更新属性面板中的角度值。
* **删除图层：**&#x200B;按下 **Backspace** 或&#x200B;**删除**，然后点击&#x200B;**[!UICONTROL 确认]**，删除选定的图层。

#### 文本格式设置选项{#text-formatting-options-on-properties-panel}

在面板中更改&#x200B;**[!UICONTROL 文本]**&#x200B;部分中相应字段的值，可将文本格式设置为所需的字体、大小、颜色、样式、（在图层中的）对齐方式。

**[!UICONTROL 智能调整文本大小]**&#x200B;确保包含&#x200B;**[!UICONTROL 智能调整文本大小]**（[版面调整](https://experienceleague.adobe.com/zh-hans/docs/dynamic-media-developer-resources/image-serving-api/image-serving-api/http-protocol-reference/text-formatting/r-copy-fitting)），通过智能调整任何文本的字体大小和长度，使其最佳适应指定的区域。 此功能可防止文本溢出，或最大限度地减少文本底部出现额外空间。
![立即创建内容](/help/using/assets/smart-text-resize.png)

### 参数化图层 {#parameterise-a-layer}

创建包含多个图像和文本层的模板后，可为所选的图层设置参数。 一个图层或其属性参数化后，会获得一个键值对（也称为参数）。 此参数可以包含在模板 URL 中，以实时更新图层的位置、大小或内容，这样就可以立即自定义模板。

要参数化图层，请执行以下操作：

1. 点击![即时创建内容](/help/using/assets/show-layers-list.svg)，选择一个图层，然后点击&#x200B;**[!UICONTROL 参数]**。 现在显示&#x200B;**[!UICONTROL 参数]**&#x200B;面板。
1. 切换&#x200B;**[!UICONTROL 包含参数]**，将一个属性参数化。 请参阅[这里](#parameterisation-options-or-allowed-parameters)，了解该属性参数化以后的行为。
1. **可选：**&#x200B;重命名参数名称。 参数名称由图层名称后加一个后缀组成。 对于选定的图层，其所有参数化属性具有相同的图层名称，后面加一个不同的后缀。 按照语义命名惯例重命名图层名称，这样您在 URL 中包含参数时，参数名称本身可以表示出图层的内容或其用途。
1. 单击&#x200B;**[!UICONTROL 保存]**。
   ![即时创建内容](/help/using/assets/parameterise-a-layer.png)
如要在图像和文本图层的参数面板之间进行切换，请选择画布上的图层，然后点击**[!UICONTROL 参数]**。

#### 参数面板选项 {#parameterisation-options-or-allowed-parameters}

参数化的属性可以作为 URL 参数包含在模板 URL 中，这样就可以通过 URL 实时编辑模板。

**图像参数：**

**X：** 包含进去，这样就可以通过更改 URL 中的参数值，将图层沿其中心线水平移动，与模板平面的 X 轴平行移动。
**Y：** 包含进去，这样就可以通过更改 URL 中的参数值，将图层沿其中心线垂直移动，与模板平面的 Y 轴平行移动。
**宽度：**包含进去，这样就可以通过更改 URL 中的参数值来调整图层的宽度。
**高度：**包含进去，这样就可以通过更改 URL 中的参数值来调整图层的高度。
**隐藏：**包含进去，这样就可以使用 0（显示）和 1（隐藏）来隐藏或显示模板中的图层。
**来源：**&#x200B;包含进去，这样就可以通过更改 URL 中参数值中的图像路径，将图层的图像改换成新图像。

**文本格式设置参数：**

包含以下参数，通过更新 URL 中的参数值可从 URL 编辑文本及其字体、颜色和大小。

**文本：**包含进去，这样就可以从 URL 更新文本。
**字体系列：**包含进去，这样就可以从 URL 更新文本的字体。
**字体大小：**包含进去，这样就可以从 URL 更新文本的字体大小。
**文本颜色：**&#x200B;包含进去，这样就可以从 URL 更新文本的字体颜色。

### 将图层分组，以同时控制其可见性{#group-layers}

保持您的模板灵活性的另一种方法是只使用一个参数名称控制多个图层。 这个策略对于可见性（隐藏或显示图层）参数很有用，可以从单个模板更新设计或图形。

按照以下步骤为多个图层的隐藏参数（![快速创建内容](/help/using/assets/Visibility-icon.svg)）分配相同的名称，这样您就可以将它们同时隐藏或显示。

1. 导航到图层的[**[!UICONTROL 属性面板]**](#parameterise-a-layer)。
1. 如果之前未设置参数，请切换&#x200B;**[!UICONTROL 隐藏]**&#x200B;参数。
1. **可选：**&#x200B;重命名隐藏参数。
1. 复制隐藏参数的名称。
1. 从画布中选择其他图层，前往这些图层的参数面板，如果之前未参数化，就切换它们的&#x200B;**[!UICONTROL 隐藏]**&#x200B;参数。
1. 将它们的&#x200B;**[!UICONTROL 隐藏参数]**&#x200B;名称替换为刚才复制的名称。
1. 点击 **[!UICONTROL 保存]**，将图层分组。
1. 在[**[!UICONTROL 预览和发布]**](#preview-and-publish-template-and-copy-template-deliver-url)部分中执行步骤 3，然后执行步骤 4，查看您的更改。

## 预览并发布模板，以复制传递 URL{#preview-and-publish-template-and-copy-template-deliver-url}

按照以下步骤预览和发布模板，并复制传递 URL：

1. 在画布页面上点击&#x200B;**[!UICONTROL 预览]**。 您还可以导航到 **[!UICONTROL Assets Essentials]** **>** **[!UICONTROL Dynamic Media Assets]** **>**&#x200B;查找并选择您的模板&#x200B;**>**&#x200B;点击&#x200B;**[!UICONTROL 编辑模板]** **>**&#x200B;点击&#x200B;**[!UICONTROL 预览]**。 预览页面上显示模板及其参数（参数化的图层和属性）、发布状态以及&#x200B;**[!UICONTROL 发布]**&#x200B;选项。
1. 在&#x200B;**[!UICONTROL 模板参数]**&#x200B;面板中选择参数，编辑这些参数的值，预览中相应模板图层的内容、大小、位置或文本格式会立即更新。 例如：
   1. 选择文本图层，编辑其文本，或者
   1. 选择一个图像图层，点击![即时创建内容](/help/using/assets/add-image.svg)，在资产选择器中选择一个图像，然后点击&#x200B;**[!UICONTROL 刷新]**。

   模板会立即更新，显示编辑后的文本，并将以前的图像替换为新图像。 此外，图像参数值反映了新的图像路径。 同样，您可以通过调整图层的值来调整其大小，所做的更改会实时应用到模板上。
1. 在列表中选择[分组的图层](#group-layers)的隐藏参数，在模板中显示或隐藏它们。
1. **可选：**&#x200B;将&#x200B;**[!UICONTROL 隐藏]**&#x200B;参数值在 0 和 1 之间改变，然后点击&#x200B;**[!UICONTROL 刷新]**，查看更改的结果。 具有相同隐藏参数的图层会一起隐藏或显示出来。 同样，您可以从 URL 控制图层的可见性。

   ![即时创建内容](/help/using/assets/dm-templates-publish-status.png)
您还可以切换**[!UICONTROL 包含所有参数]**，以编辑所有显示的参数值，并在模板预览中查看更新。
   <br>
1. 要在预览页面上发布模板，请点击&#x200B;**[!UICONTROL 发布]**，然后确认发布。 然后会显示“发布完成”消息，发布状态会更新为“已发布”。

>[!NOTE]
>
>要发布模板，需要先发布模板图像。

### 复制传递 URL

**[!UICONTROL 预览]**&#x200B;页面上选定的参数会成为模板 URL 中的 URL 参数。

要复制预览中显示的已发布模板的 URL，请执行以下操作：

1. 点击&#x200B;**[!UICONTROL 复制 URL]**。 现在会显示&#x200B;**[!UICONTROL 复制 URL]** 对话框。 选择并复制显示的 URL。 请注意，URL 中的第一个参数在问号 **(?)** 的后面开始 键值对以 **$** 开头，以 **&amp;** 结尾。 键和值通过等号 **(=)** 分隔，键在左侧，值在右侧。
1. 将这个 URL 粘贴到您的浏览器选项卡中，查看您的实时模板。 通过直接更新 URL 中必需参数的值（键的值）可实时自定义模板，如&#x200B;**预览和发布**&#x200B;部分的[步骤 2](#preview-and-publish-template-and-copy-template-deliver-url) 中所述。
1. 使用这个 URL 快速促销您的产品或服务。 您可以与客户共享这个 URL，或者将其集成到您的网站或任何下游第三方应用程序，以显示横幅，实时更新，以反映正在进行的优惠活动。

在这个视频中了解如何分步创建一个 Dynamic Media 模板。
>[!VIDEO](https://video.tv.adobe.com/v/3443281)

## 从 URL 对模板进行实时更新{#update-the-template-from-the-url}

直接在 URL 中编辑参数可能会比较繁琐。 可以如此简化：

1. 复制 URL，将其粘贴到记事本中。
1. 使用 Cmd+F (Mac) 或 Ctrl+F (Windows) 查找并编辑参数值。 例如：
   * 替换图像图层的图像路径。
   * 调整图层尺寸和位置（如果已经[参数化](#parameterise-a-layer)）。
   * 编辑文本图层的文本、字体、颜色、大小或对齐方式。
   * 将可见性的值在 0 和 1 之间改变。

将这个更新的 URL 粘贴到浏览器中，查看更改的结果。

## 编辑模板{#edit-the-template}

按以下这些步骤编辑模板：

1. 在 Assets Essentials 上点击 **[!UICONTROL Dynamic Media Assets]**。
2. 导航到模板位置。
3. 选择模板。
4. 点击&#x200B;**[!UICONTROL 编辑模板]**。 模板画布在图层面板中显示此模板及其所有图层的列表。 根据您的要求开始编辑模板。

## 要注意的重要事项 {#important-points-to-note}

* 创建了模板并将其中的图像图层为动态更新进行参数化以后，请确保计划用于未来更新的图像具有与参数化的图像相同的尺寸。 这样可以确保图像最佳放在图层内，不会溢出，也不会留下空白区域。 目前，模板不支持按照图层自动调整适合的图像尺寸。
* 文本图层不支持子字符串。 用户无法在文本图层的子字符串上应用不同的字体属性。
* Dynamic Media 模板目前不支持多个 Dynamic Media 公司。
* 在复制或移动时，目标选择器会显示所有文件夹（包括非 Dynamic Media 同步的文件夹）。 目前它也不显示 Dynamic Media 模板资产（两者都是目标选择器的限制）。
* 在 Assets 部分中对文件夹执行的任何更新操作（例如发布或删除）都会影响这个文件夹中提供可用的 Dynamic Media 模板。
* Dynamic Media 模板没有垃圾箱功能。 如果某个资产被移至垃圾箱后又被恢复，这个资产就会在 AEM 中，而不是在 Dynamic Media 中恢复。 这同样适用于 Dynamic Media 模板。

## 另请参阅

1. 探索 [Dynamic Media 及其功能](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media)
1. 探索[具有 OpenAPI 功能的 Dynamic Media](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media-open-apis/dynamic-media-open-apis-overview)
