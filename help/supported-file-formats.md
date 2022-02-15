---
title: 支持的文件格式
description: 支持各种用例的文件格式 [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: bc44e98d-446e-41ff-b5b4-9dc324834630
source-git-commit: b9d333a862cca6227ef386ae8dadf431c2fb6d71
workflow-type: tm+mt
source-wordcount: '308'
ht-degree: 16%

---

# 支持 [!DNL Assets Essentials] {#file-format-support}

[!DNL Assets Essentials] 支持多种文件格式，每种功能都支持不同文件类型。

* ![图像文件类型图标](assets/image-icon.svg) 图像：JPG、PNG、GIF、TIFF等
* ![creative cloudtype图标](assets/creative-cloud-files.svg) Creative Cloud文件：PSD、人工智能和INDD
* ![相机类型图标](assets/camera-icon.svg) Camera Raw文件：CR2/CR3、NEF、SRW/SRF等
* ![文档文件类型图标](assets/document-icon.svg) 文档：DOCX、PDF、PPTX和XLSX
* ![视频文件类型图标](assets/video-icon.svg) 视频：MP4

[!DNL Assets Essentials] 支持任何包含基本服务的二进制文件格式，例如存储、上传、复制、移动、删除和添加元数据。

[!DNL Assets Essentials] 还支持来自众多领先相机制造商的相机原始文件，这些制造商包括由Adobe Camera Raw提供支持的佳能(CR2/CR3)、尼康(NEF)、索尼(SRW/SRF)、富士胶片(RAF)、奥林匹斯(ORF)等。

各种文件类型对用例和功能的支持程度不同，如下所述。 使用图例了解支持级别。

| 支持级别 | 描述 |
|-------------------|-------------------------|
| ✓ | 支持 |
| ✓ ? | 有条件支持 |
| - | 不适用 |

## 添加、上传和查看资产 {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| 资产类型 | [浏览](/help/navigate-view.md) | 复制 | [上传](/help/add-delete.md) | 创建 | [删除](/help/add-delete.md#delete-assets) | 详细信息 | 图像缩放 | [最近查看的项目](/help/navigate-view.md) |
|-------------------|----------|----------|----------|----------|----------|-------------------|------------|-----------------|
| 光栅图像 | ✓ | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| 原始文件 | ✓ | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| 文件夹 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | - | - |
| MP4视频 | ✓ | ✓ | ✓ | - | ✓ | ✓ ? | - | ✓ |
| PDF | ✓ | ✓ | ✓ | - | ✓ | ✓ | - | ✓ |
| PSD、人工智能和INDD | ✓ | ✓ | ✓ | - | ✓ | ✓ ? | - | ✓ |
| 其他二进制文件 | ✓ | ✓ | ✓ | - | ✓ | ✓ | - | ✓ |

<!-- Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## 搜索、使用和编辑资产 {#support-to-search-use-edit}

| 资产类型 | [下载](/help/manage-organize.md#download) | 拖放 | [图像编辑器](/help/edit-images.md) | [搜索](/help/search.md) | [智能标记](/help/metadata.md#tags) | [重命名](/help/manage-organize.md) | [版本](/help/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| 光栅图像 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| 原始文件 | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ | ✓ |
| 文件夹 | ✓ | ✓ | - | ✓ | - | ✓ | ✓ |
| 视频 | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| CC库 | - | - | - | - | - | ✓ | ✓ |
| PDF | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| PSD、人工智能和INDD | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| 其他二进制文件 | ✓ | ✓ | - | ✓ | - | ✓ | ✓ |


## 审核资产和协作 {#support-to-review-collaborate}

| 资产类型 | 注释 | 注释 | 创建任务和查看 |
|---------------|----------|----------|-------------------------|
| 光栅图像 | ✓ | ✓ | ✓ |
| 原始文件 | ✓ | ✓ | ✓ |
| 文件夹 | - | - | - |
| 视频 | - | ✓ | ✓ |
| CC库 | - | - | - |
| PDF | - | ✓ | ✓ |
| PSD、人工智能和INDD | - | ✓ | ✓ |
| 其他二进制文件 | - | ✓ | ✓ |

## 其他资产管理任务 {#support-to-manage-assets}

| 资产类型 | [元数据](/help/metadata.md) | [演绎版](/help/add-delete.md#renditions) | [垃圾桶](/help/add-delete.md#delete-assets) | 复制 | 移动 |
|---------------|-------------------|------------|----------|----------|----------|
| 光栅图像 | ✓ | ✓ | ✓ | ✓ | ✓ |
| 原始文件 | ✓ | ✓ | ✓ | ✓ | ✓ |
| 文件夹 | ✓ | - | ✓ | ✓ | ✓ |
| 视频 | ✓ | - | ✓ | ✓ | ✓ |
| CC库 | ✓ | - | - | - | - |
| PDF | ✓ | - | ✓ | ✓ | ✓ |
| PSD、人工智能和INDD | ✓ | - | ✓ | ✓ | ✓ |
| 其他二进制文件 | ✓ | - | ✓ | ✓ | ✓ |

用户 [!DNL Adobe Asset Link] 可以将文件上传和签入（上传新版本）到 [!DNL Assets Essentials] 支持的存储库 [!DNL Adobe Creative Cloud] 桌面应用程序。

<!-- TBD: Saving the template table separately for later use.
| Asset type    | Features |
|---------------|----------|
| Raster images |          |
| Folders       |          |
| Videos        |          |
| CC Libraries  |          |
| PDF files     |          |
| PSD           |          |
| AI            |          |
| INDD          |          |

>[!MORELIKETHIS]
>
>* []()
-->
