---
title: Content Credentials 集成
description: Content Credentials 与 AEM Assets 集成，是 AEM Assets Essentials UI 中的重要功能，可以提供关于资产历史的背景信息，包括资产的制造方式以及参与制造的人员。 Content Credentials 就像为数字内容提供的一种营养成分标签，有助于提高透明度，建立受众的信任。
role: User
exl-id: 703f74a6-24d4-4181-8174-9ff4a90ee7aa
TQID: https://experienceleague.adobe.com/witCqgAh8EKfD-hdn8efjZ-M4sypX44KB2ELs3ECInI
product_v2: id: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
feature_v2: id: ec4263d9-bf7c-44c7-b3f1-3e664861c8f2
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
topic_v2: id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dc
source-git-commit: f026b389ce582ece5d2ca8745d291b1ae50d657e
workflow-type: tm+mt
source-wordcount: 474
ht-degree: 100%

---

# Content Credentials {#content-credentials}

品牌对内容透明度、AI 来源披露以及防止资产被篡改的关注程度空前提高。 Adobe 的 Content Authenticity Initiative (CAI) 构建了符合[内容来源和真实性联盟](https://c2pa.org/specifications/specifications/1.1/specs/C2PA_Specification.html#_trust_model) (C2PA) 技术标准的工具。 Content Credentials 是一种全新的加密且可防篡改的元数据，有助于帮助查看者了解内容的来源与演变，并保障品牌资产的完整性。 Content Credentials 可包含多种溯源数据，深入呈现数字资产的历史信息。

这些信息包括：

* **签发方或签名者：**&#x200B;签发数字签名以验证或签署资产的实体或公司的信息。
* **签发日期：** Content Credential 被应用于此资产的日期。
* **归属和使用：**&#x200B;关于资产制作者的信息，包括姓名、社交媒体账号或其他与身份相关的信息。
* **过程：**&#x200B;对资产进行任何编辑或更改的记录。
* **设备详细信息：**&#x200B;关于在创建或编辑资产时使用的应用程序或设备的信息。
* **使用的 AI 工具：**&#x200B;如果使用了生成式 AI 编辑或创建资产，可能会包含所使用的模型的名称。
* **其他相关信息：**&#x200B;可能还包含其他数据，以帮助提供有关资产历史的更多上下文。

要获得完整的视图，[验证](https://contentcredentials.org/verify)可以在资产历史记录中提供更全面的洞察。

Adobe Experience Manager Assets 现在支持 Content Credentials，允许用户直接在 AEM 的 Assets Essentials UI 中查看 Content Credentials。 查看资产详细信息时，Content Credentials 的任何图像（例如使用生成式 AI 服务创建的图像）都会在一个专门的面板中显示清单细节。 如果下载、发布或共享资产，凭据会与此资产一起保持完整。

![资产](/help/using/assets/content-credentials.png)

## 访问 Content Credentials {#access-content-credentials}

1. 前往 Assets Essentials UI，然后点击左窗格中的 **Assets**。
1. 导航到一个文件夹，然后选择需要的资产。
1. 点击&#x200B;**详细信息**，然后从最右边的窗格中选择 `Cr pin`。 Content Credentials 选项卡中显示关于该资产的以下信息。
   1. **生成的图像：** Content Credentials 应用的日期和时间。
   1. **内容摘要：**表示资产是部分还是完全由 AI 生成，或者经过哪些编辑。
      ![内容摘要](/help/using/assets/content-credentials1.png)
   1. **过程：**详细说明生成此资产时使用的应用程序、设备和 AI 工具（如 Adobe Firefly），以及之后所做的更改。
      ![过程](/help/using/assets/CR-Process.png)
   1. **关于这个 Content Credentials：**签发方名称以及签发的日期和时间。
      ![签发方](/help/using/assets/CR-issuer.png)
