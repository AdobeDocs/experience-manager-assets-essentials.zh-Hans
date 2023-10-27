---
title: AEM Assets中用于Creative Cloud集成的跨组织权限
description: 了解如何在AEM Assets中为Creative Cloud集成配置跨组织权限。 连接到已设置到其他IMS组织的Creative Cloud权利，以便轻松使用AEM Assets中的最新Creative Cloud集成，包括Express和Creative Cloud库。
source-git-commit: b0e20aa3a29a6a37453da16f18d474baf67edb24
workflow-type: tm+mt
source-wordcount: '294'
ht-degree: 0%

---

# Creative Cloud集成的跨组织授权  {#cross-org-entitlements}

Experience Manager Assets能够连接到设置到其他IMS组织的Creative Cloud权利，以便轻松地使用AEM Assets中的最新Creative Cloud集成，包括Express和Creative Cloud库。

如果您的Creative Cloud产品和AEM Assets配置为单独的IMS组织，则可以连接到其他Creative Cloud组织，以便能够在两个解决方案之间执行集成的工作流。

## 前提条件 {#prerequisites}

* Experience Manager Assets管理员权限

* 跨Creative Cloud和Experience Manager使用的同一用户ID的Creative Cloud的有效权限。 对具有相同电子邮件地址的个人和Federated ID的权利被视为不同的用户ID。

## 连接到新的Creative Cloud组织 {#connect-to-creative-cloud-org}

要连接到新的Creative Cloud组织，请执行以下步骤：

1. 导航到 **[!UICONTROL 设置]** > **[!UICONTROL Creative Cloud]**.

1. 使用选择新的Creative Cloud组织 **[!UICONTROL 选择新Creative Cloud组织ID]** 下拉列表。 该列表显示了您有权访问的所有组织。 选择具有有效Creative Cloud授权的组织。

1. 单击 **[!UICONTROL 切换组织]** 以切换到新组织。

   ![跨组织授权](assets/cross-org-entitlements.png)

## 限制 {#limitations}

* 您可以每次将AEM Assets连接到一个Creative Cloud组织。 不支持一次连接到多个Creative Cloud组织。

* 您在AEM Assets中连接到的Creative Cloud组织适用于贵组织内的所有用户。

