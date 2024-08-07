---
title: 编辑图像
description: 使用由 [!DNL Adobe Express] 提供支持的选项编辑图像并将更新后的图像另存为版本。
role: User
exl-id: fc21a6ee-bf23-4dbf-86b0-74695a315b2a
source-git-commit: 53f638e0dc934f2a4134acb89713b5d4828c8d1f
workflow-type: tm+mt
source-wordcount: '1182'
ht-degree: 63%

---

# 在 [!DNL Assets Essentials] 中编辑图像 {#edit-images-in-assets-essentials}

Assets Essentials UI支持由Adobe Express提供的基础图像编辑，该功能已集成到UI中。 此编辑包括调整大小、删除背景、裁剪以及在JPEG格式和PNG格式之间进行转换。 此外，它还允许通过Essentials UI中嵌入的Adobe Express界面进行高级编辑。

在编辑图像之后，您可以将新图像另存为新版本。版本控制可帮助您在需要时还原为原始资源。若要编辑图像，请[打开其预览](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-assets-essentials/help/navigate-view#preview-assets)，然后单击&#x200B;**“编辑图像”。**

>[!NOTE]
>
>您可以使用 Adobe Express 编辑 PNG 和 JPEG 文件类型的图像。

<!--The editing actions that are available are Spot healing, Crop and straighten, Resize image, and Adjust image.-->

## 编辑图像 {#edit-images}

使用链接 — [Assets EssentialsUI](https://experience.adobe.com/#/assets)并选择正确的Assets Essentials库转到Repository UI。 要获得访问权限，请联系您组织的管理员。
有关任何其他参考信息，请参阅 — [开始使用Adobe Experience Manager Assets Essentials](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-assets-essentials/help/get-started)、[了解用户界面](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-assets-essentials/help/navigate-view)、[Assets Essentials用例](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-assets-essentials/help/get-started#use-cases)和[已知问题](https://experienceleague.adobe.com/zh-hans/docs/experience-manager-assets-essentials/help/release-notes)。

### 使用 Adobe Express 在 Essentials UI 上编辑图像{#edit-images-using-adobe-express}

>[!CONTEXTUALHELP]
>id="assets_express_integration"
>title="Adobe Express 集成"
>abstract="可直接在 AEM Assets 中使用简单而直观的受 Adobe Express 支持的图像编辑工具，以提高内容重用率并加快内容速度。"

导航到Essentials UI后，单击&#x200B;**Assets**，选择一个图像，然后单击顶部边栏中的&#x200B;**编辑**。 新屏幕显示了由Adobe Express提供支持的可用编辑选项，包括调整大小、删除背景、裁剪以及在JPEG格式和PNG格式之间进行转换。

#### 调整图像大小 {#resize-image-using-express}

将图像大小调整为热门用例中的特定大小。Assets Essentials 提供针对特定照片大小预先计算的新分辨率，让您可以快速地调整图像大小以适合常见的照片尺寸。要在Assets Essentials界面中调整图像大小，请执行以下步骤：

1. 从左窗格中单击&#x200B;**调整图像大小**。 此时会显示一个对话框，其中显示了由Adobe Express提供支持的调整图像大小功能。
2. 从“调整大小对象”下拉列表中选择适当的社交媒体平台，并从显示的选项中选择图像的大小。
3. 如果需要，使用&#x200B;**“图像比例”**&#x200B;字段缩放图像。
4. 单击&#x200B;**应用**以应用您的更改。
   ![使用 Adobe Express 进行图像编辑](/help/using/assets/adobe-express-resize-image.png)

   您编辑的图像可供下载。您可以将编辑后的资源另存为同一资源的新版本，也可以将其另存为新资源。
   ![使用 Adobe Express 保存图像](/help/using/assets/adobe-express-resize-save.png)

#### 移除背景 {#remove-background-using-express}

您可以按照以下步骤从图像中移除背景：

1. 单击左侧窗格中的 **删除背景**。Experience Manager Assets 不含背景地显示该图像。
2. 单击&#x200B;**[!UICONTROL 应用]**以应用您的更改。
   ![使用 Adobe Express 保存图像](/help/using/assets/adobe-express-remove-background.png)

   您编辑的图像可供下载。您可以将编辑后的资源另存为同一资源的新版本，也可以将其另存为新资源。

#### 裁切图像 {#crop-image-using-express}

使用嵌入的 [!DNL Adobe Express] 快速操作可以简单地将图像转换为完美尺寸。

1. 单击左侧窗格中的 **[!UICONTROL 剪裁图像]**。
2. 拖动该图像四角的手柄以创建您想要的裁切效果。
3. 单击&#x200B;**[!UICONTROL 应用]**。
   ![使用 Adobe Express 保存图像](/help/using/assets/adobe-express-crop-image.png)
裁剪后的图像可供下载。您可以将编辑后的资源另存为同一资源的新版本，也可以将其另存为新资源。

#### 将 JPEG 转化为 PNG {#Convert-JPEG-to-PNG}

您可以使用 Adobe Express 在 JPEG 和 PNG 图像格式之间快速转换。执行以下步骤：

1. 在左侧窗格中单击将 **JPEG 转换为 PNG** 或将 **PNG 转换为 JPEG**。
   ![使用 Adobe Express 转换为 PNG](/help/using/assets/adobe-express-convert-image.png)
2. 单击&#x200B;**[!UICONTROL “下载”。]**

#### 限制 {#limitations-adobe-express}

* 支持的图像分辨率：最小 - 50 像素，最大 - 每维 6000 像素。
* 支持的最大文件大小：17 MB。

### 在 Adobe Express 嵌入式编辑器中编辑图像 {#edit-images-in-adobe-express-embedded-editor}

拥有Express权利的用户可以从Assets EssentialsUI中使用嵌入的Express编辑器，轻松地在Adobe Firefly中使用GenAI编辑内容和新内容。 此功能改进了内容重用并加快了内容速度。 您还可以使用预定义的元素使您的资源看起来令人惊叹，或者只需单击几下即可执行快速操作来编辑图像。

![在Essentials UI中表达](/help/using/assets/express-in-essentials-ui.jpg)
要在Adobe Express嵌入式编辑器中编辑图像，请执行以下步骤：

1. 使用链接 — [AEM Assets Essentials UI](https://experience.adobe.com/#/assets)转到AEM Assets Essentials UI，然后选择正确的存储库。
1. 点击 **资源**，进入文件夹，然后选择一张图像。
1. 单击&#x200B;**在 Adobe Express 中打开**。图像在快捷画布上打开。
1. 对图像进行必要的编辑。
1. 如果你的项目需要你添加更多页面，请单击 **添加**，选择资源，进入文件夹，选择要带到画布页面的图像，然后对图像执行所需的编辑。
1. 要保存一个或多个资源，请单击&#x200B;**保存**。 保存对话框显示保存选项。 要在保存选项之间进行选择，请按照以下说明之一操作，以符合您的要求：
   1. 若要保存单个页面，请单击&#x200B;**另存为版本**&#x200B;以将图像导出为新版本（保留原始格式），并将其保存在同一文件夹中。

   1. 要保存单个页面，请单击&#x200B;**另存为新资产**&#x200B;以将资产导出为其他格式，并将其另存到任意文件夹中作为新资产。

   1. 若要从多个页面中保存单个页面，请单击&#x200B;**另存为版本**，以原始格式和位置保存资产。

   1. 要保存多个页面或多个页面中的单个页面，请单击&#x200B;**另存为新资产**。 此操作将单个或多个资产导出到任意文件夹，并以原始格式或不同格式将它们另存为新资产。

1. 在保存对话框中：
   1. 在 **另存为** 字段中输入文件的名称。
   1. 选择目标文件夹。
   1. 可选：提供详细信息，例如 项目或活动名称、关键字、渠道、时间范围和地区。
1. 单击&#x200B;**另存为新版本**&#x200B;或&#x200B;**另存为新资源**&#x200B;以保存一个或多个资源。

#### 在 Express Editor 中编辑图像的限制 {#limitations-of-editing-images-in-the-express-editor}

* 支持的文件类型：JPEG or PNG。
* 支持的最大文件大小：40 MB。
* 支持的宽度和高度范围：50 到 8000 像素之间。
* 重新加载页面以查看源文件夹中最新保存的新资源。

### 使用 Adobe Express 创建新资源 {#create-new-assets-using-embedded-editor}

通过Assets Essentials，您可以使用Adobe Express嵌入编辑器从头开始创建新模板。 若要使用 Adobe Express 创建新资源，请执行以下步骤：

1. 导航至 **My Workspace**，然后单击显示在快速访问部分上方的&#x200B;**Adobe Express 横幅中的**&#x200B;创建。Adobe Express 空白画布显示在 Assets Essentials 用户界面内。
1. 使用[模板](https://helpx.adobe.com/cn/express/using/work-with-templates.html)创建您的内容。否则，导航至您的内容来修改现有内容。
1. 完成编辑后，单击&#x200B;**保存**。
1. 指定创建资源的目标路径，然后单击&#x200B;**另存为新资源**。

#### 限制 {#limitations}

* 您只能修改 `JPEG` 和 `PNG` 格式类型的图像。
* 资源大小必须小于 40 MB。
* 您可以将图像保存为 `PDF`, `JPEG` 或者 `PNG` 格式。

<!--
## Edit images using [!DNL Adobe Photoshop Express] {#edit-using-photoshop-express}

<!--
After editing an image, you can save the new image as a new version. Versioning helps you to revert to the original asset later, if needed. To edit an image, [open its preview](/help/using/navigate-view.md#preview-assets) and click **[!UICONTROL Edit Image]** ![edit icon](assets/do-not-localize/edit-icon.png) from the rail on the right.

![Options to edit an image](assets/edit-image2.png)

*Figure: The options to edit images are powered by [!DNL Adobe Photoshop Express].*
-->
<!--
### Spot heal images {#spot-heal-images-using-photoshop-express}

If there are minor spots or small objects on an image, you can edit and remove the spots using the spot healing feature provided by Adobe Photoshop.

The brush samples the retouched area and makes the repaired pixels blend seamlessly into the rest of the image. Use a brush size that is only slightly larger than the spot you want to fix.

![Spot healing edit option](assets/edit-spot-healing.png)

<!-- 
TBD: See if we should give backlinks to PS docs for these concepts.
For more information about how Spot Healing works in Photoshop, see [retouching and repairing photos](https://helpx.adobe.com/photoshop/using/retouching-repairing-images.html). 
-->
<!--
### Crop and straighten images {#crop-straighten-images-using-photoshop-express}

Using the crop and straighten option that you can do basic cropping, rotate image, flip it horizontally or vertically, and crop it to dimensions suitable for popular social media websites.

To save your edits, click **[!UICONTROL Crop Image]**. After editing, you can save the new image as a version.

![Option to crop and straighten](assets/edit-crop-straighten.png)

Many default options let you crop your image to the best proportions that fit various social media profiles and posts.

### Resize image {#resize-image-using-photoshop-express}

You can view the common photo sizes in centimeters or inches to know the dimensions. By default, the resizing method retains the aspect ratio. To manually override the aspect ratio, click ![](assets/do-not-localize/lock-closed-icon.png).

Enter the dimensions and click **[!UICONTROL Resize Image]** to resize the image. Before you save the changes as a version, you can either undo all the changes done before saving by clicking [!UICONTROL Undo] or you can change the specific step in the editing process by clicking [!UICONTROL Revert].

![Options when resizing an image](assets/resize-image.png)

### Adjust image {#adjust-image-using-photoshop-express}

[!DNL Assets Essentials] lets you adjust the color, tone, contrast, and more, with just a few clicks. Click **[!UICONTROL Adjust image]** in the edit window. The following options are available in the right sidebar:

* **Popular**: [!UICONTROL High Contrast & Detail], [!UICONTROL Desaturated Contrast], [!UICONTROL Aged Photo], [!UICONTROL B&W Soft], and [!UICONTROL B&W Sepia Tone].
* **Color**: [!UICONTROL Natural], [!UICONTROL Bright], [!UICONTROL High Contrast], [!UICONTROL High Contrast & Detail], [!UICONTROL Vivid], and [!UICONTROL Matte].
* **Creative**: [!UICONTROL Desaturated Contrast], [!UICONTROL Cool Light], [!UICONTROL Turquoise & Red], [!UICONTROL Soft Mist], [!UICONTROL Vintage Instant], [!UICONTROL Warm Contrast], [!UICONTROL Flat & Green], [!UICONTROL Red Lift Matte], [!UICONTROL Warm Shadows], and [!UICONTROL Aged Photo].
* **B&W**: [!UICONTROL B&W Landscape], [!UICONTROL B&W High Contrast], [!UICONTROL B&W Punch], [!UICONTROL B&W Low Contrast], [!UICONTROL B&W Flat], [!UICONTROL B&W Soft], [!UICONTROL B&W Infrared], [!UICONTROL B&W Selenium Tone], [!UICONTROL B&W Sepia Tone], and [!UICONTROL B&W Split Tone].
* **Vignetting**: [!UICONTROL None], [!UICONTROL Light], [!UICONTROL Medium], and [!UICONTROL Heavy].

![Adjust image by editing](assets/adjust-image.png)

<!--
TBD: Insert a video of the available social media options.
-->

### 后续步骤 {#next-steps}

* 利用 Assets Essentials 用户界面上的[!UICONTROL 反馈]选项提供产品反馈

* 通过右侧边栏中的[!UICONTROL 编辑此页面]![编辑页面](assets/do-not-localize/edit-page.png)或[!UICONTROL 记录问题]![创建 GitHub 问题](assets/do-not-localize/github-issue.png)来提供文档反馈

* 联系[客户关怀团队](https://experienceleague.adobe.com/?support-solution=General#support)

>[!MORELIKETHIS]
>
>* [查看资源的版本历史记录](/help/using/navigate-view.md)
