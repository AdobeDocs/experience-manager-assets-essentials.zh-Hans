---
title: 支持的文件格式
description: ' [!DNL Assets Essentials] 的各种用例支持的文件格式'
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: bc44e98d-446e-41ff-b5b4-9dc324834630
source-git-commit: 243a41aef81cd1fdcbad8f4355fe2d888db394d1
workflow-type: ht
source-wordcount: '527'
ht-degree: 100%

---

# [!DNL Assets Essentials] 中支持的文件格式 {#file-format-support}

[!DNL Assets Essentials] 支持广泛的文件格式，各种功能支持的文件类型也各不相同。

* ![图像文件类型图标](assets/image-icon.svg) 图像：JPG、PNG、GIF、TIFF 等
* ![Creative Cloud 类型图标](assets/creative-cloud-files.svg) Creative Cloud 文件：PSD、PSB、AI 和 INDD
* ![相机类型图标](assets/camera-icon.svg) Camera RAW 文件：CR2/CR3、NEF、SRW/SRF 等
* ![文档文件类型图标](assets/document-icon.svg) 文档：DOCX、PDF、PPTX 和 XLSX
* ![视频文件类型图标](assets/video-icon.svg) 视频：MP4

[!DNL Assets Essentials] 支持各种二进制文件格式并提供基本服务，例如存储、上传、复制、移动、删除和添加元数据。

[!DNL Assets Essentials] 还支持各大领先相机制造商的各种 Camera Raw 文件，包括 Canon (CR2/CR3)、Nikon (NEF)、Sony (SRW/SRF)、Fujifilm (RAF)、Olympus (ORF) 等，此功能由 Adobe Camera Raw 提供支持。

根据用例和功能，对各种文件类型的支持程度不同，如下所述：使用图例了解支持级别。

| 支持级别 | 描述 |
|-------------------|-------------------------|
| ✓ | 支持 |
| ✓ ‡ | 有条件支持 |
| − | 不适用 |

## 添加、上传和查看资源 {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| 资源类型 | [浏览](/help/using/navigate-view.md) | 复制 | [上传](/help/using/add-delete.md) | 创建 | [删除](/help/using/add-delete.md#delete-assets) | 详细信息 | 图像缩放 | [最近查看的项目](/help/using/navigate-view.md) |
|-------------------|----------|----------|----------|----------|----------|-------------------|------------|-----------------|
| 栅格图像 | ✓ | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| RAW 文件 | ✓ | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| 文件夹 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | − | − |
| MP4 视频 | ✓ | ✓ | ✓ | − | ✓ | ✓ ‡ | − | ✓ |
| PDF | ✓ | ✓ | ✓ | − | ✓ | ✓ | − | ✓ |
| PSD、AI、PSB和 INDD | ✓ | ✓ | ✓ | − | ✓ | ✓ ‡ | − | ✓ |
| 其他二进制文件 | ✓ | ✓ | ✓ | − | ✓ | ✓ | − | ✓ |

<!-- Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## 搜索、使用和编辑资源 {#support-to-search-use-edit}

| 资源类型 | [下载](/help/using/manage-organize.md#download) | 拖放 | [图像编辑器](/help/using/edit-images.md) | [搜索](/help/using/search.md) | [智能标记](/help/using/metadata.md#tags) | [重命名](/help/using/manage-organize.md) | [版本](/help/using/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| 栅格图像 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| RAW 文件 | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ | ✓ |
| 文件夹 | ✓ | ✓ | − | ✓ | − | ✓ | ✓ |
| 视频 | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| CC Libraries | − | − | − | − | − | ✓ | ✓ |
| PDF | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| PSD 和 PSB | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| AI 和 INDD | ✓ | ✓ | − | ✓ | − | ✓ | ✓ |
| 其他二进制文件 | ✓ | ✓ | − | ✓ | − | ✓ | ✓ |


## 审阅资源和协作 {#support-to-review-collaborate}

| 资源类型 | 批注 | 评论 | 创建任务并审阅 |
|---------------|----------|----------|-------------------------|
| 栅格图像 | ✓ | ✓ | ✓ |
| RAW 文件 | ✓ | ✓ | ✓ |
| 文件夹 | − | − | − |
| 视频 | − | ✓ | ✓ |
| CC Libraries | − | − | − |
| PDF | − | ✓ | ✓ |
| PSD、PSB、AI 和 INDD | − | ✓ | ✓ |
| 其他二进制文件 | − | ✓ | ✓ |
| DOC | − | ✓ | ✓ |
| DOCX | − | ✓ | ✓ |
| PPT | − | ✓ | ✓ |
| PPTX | − | ✓ | ✓ |
| XLS | − | ✓ | ✓ |
| XLSX | − | ✓ | ✓ |
| TXT | − | ✓ | ✓ |
| RTF | − | ✓ | ✓ |

## 其他资源管理任务 {#support-to-manage-assets}

| 资源类型 | [元数据](/help/using/metadata.md) | [演绎版](/help/using/add-delete.md#renditions) | [垃圾桶](/help/using/add-delete.md#delete-assets) | 复制 | 移动 |
|---------------|-------------------|------------|----------|----------|----------|
| 栅格图像 | ✓ | ✓ | ✓ | ✓ | ✓ |
| RAW 文件 | ✓ | ✓ | ✓ | ✓ | ✓ |
| 文件夹 | ✓ | − | ✓ | ✓ | ✓ |
| 视频 | ✓ | − | ✓ | ✓ | ✓ |
| CC Libraries | ✓ | − | − | − | − |
| PDF | ✓ | − | ✓ | ✓ | ✓ |
| AI 和 INDD | ✓ | − | ✓ | ✓ | ✓ |
| PSD 和 PSB | ✓ | ✓ | ✓ | ✓ | ✓ |
| 其他二进制文件 | ✓ | − | ✓ | ✓ | ✓ |

[!DNL Adobe Asset Link] 的用户可以从支持的 [!DNL Adobe Creative Cloud] 桌面应用程序上传文件，并将其签入（上传新版本）[!DNL Assets Essentials] 存储库中。

<!-- TBD: Saving the template table separately for later use.
| Asset type    | Features |
|---------------|----------|
| Raster images |          |
| Folders       |          |
| Videos        |          |
| CC Libraries  |          |
| PDF files     |          |
| PSD, PSB           |          |
| AI            |          |
| INDD          |          |

>[!MORELIKETHIS]
>
>* []()
-->

## 后续步骤 {#next-steps}

* 利用 Assets Essentials 用户界面上的[!UICONTROL 反馈]选项提供产品反馈

* 通过右侧边栏中的[!UICONTROL 编辑此页面]![编辑页面](assets/do-not-localize/edit-page.png)或[!UICONTROL 记录问题]![创建 GitHub 问题](assets/do-not-localize/github-issue.png)来提供文档反馈

* 联系[客户关怀团队](https://experienceleague.adobe.com/zh-hans?support-solution=General#support)
