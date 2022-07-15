---
title: 在Assets Essentials中管理报表
description: 使用Assets Essentials报表中的信息获取关键成功量度，以衡量企业内部和客户对资产的采用情况。
source-git-commit: 511b7904eca972e76f55e574c7c364dd88fb1721
workflow-type: tm+mt
source-wordcount: '515'
ht-degree: 4%

---

# 管理报表 {#manage-reports}

通过资产报告，管理员可以评估Adobe Experience Manager Assets Essentials部署的实用程序。 这些报表提供了有关用户如何与部署中可用资产进行交互的有用信息。

使用报表中的信息获取关键成功量度，以衡量企业内和客户对资产的采用情况。

## 访问报告 {#access-reports}

分配给 [Assets Essentials管理员产品配置文件](deploy-administer.md) 可以在Assets Essentials中访问实时统计和报告。

## 查看实时统计信息 {#view-live-statistics}

Assets Essentials允许您查看为Assets Essentials部署自动生成的下载数据。 您可以选择查看过去30天或过去12个月内执行的资产下载次数。

![选中资源时的工具栏选项](assets/asset-reports-live-statistics.png)

导航到 **[!UICONTROL 设置]** > **[!UICONTROL 实时统计]** 查看自动生成的下载数据。

## 创建报表 {#create-report}

要创建报表，请执行以下操作：

1. 导航到 **[!UICONTROL 设置]** > **[!UICONTROL 报表]** 单击 **[!UICONTROL 创建报表]**.

1. 在 [!UICONTROL 配置] 选项卡，为报表指定标题和可选描述。

1. 使用 **[!UICONTROL 选择文件夹路径]** 字段。

1. 选择报表的日期间隔。

1. 在 [!UICONTROL 列] 选项卡，选择需要在报表中显示的列名称。

1. 单击&#x200B;**[!UICONTROL 创建]**。

   ![下载报表](assets/download-reports-config.png)

下表说明了可添加到报表的所有列的用法：

<table>
    <tbody>
     <tr>
      <th><strong>列名称</strong></th>
      <th><strong>描述</strong></th>
     </tr>
     <tr>
      <td>标题</td>
      <td>资产的标题。</td>
     </tr>
     <tr>
      <td>路径</td>
      <td>资产在Assets Essentials中可用的文件夹路径。</td>
     </tr>
     <tr>
      <td>类型</td>
      <td>资产的MIME类型。</td>
     </tr>
     <tr>
      <td>大小</td>
      <td>资产的大小。</td>
     </tr>
     <tr>
      <td>下载者</td>
      <td>下载资产的用户的电子邮件ID。</td>
     </tr>
     <tr>
      <td>下载日期</td>
      <td>执行资产下载操作的日期。</td>
     </tr>
     <tr>
      <td>创作</td>
      <td>资产的作者。</td>
     </tr>
     <tr>
      <td>创建日期</td>
      <td>资产上传到Assets Essentials的日期。</td>
     </tr>
     <tr>
      <td>修改日期</td>
      <td>上次修改资产的日期。</td>
     </tr>
     <tr>
      <td>已过期</td>
      <td>资产的过期状态。</td>
     </tr>
     <tr>
      <td>按用户名下载</td>
      <td>下载资产的用户的名称。</td>
     </tr>           
    </tbody>
   </table>

## 查看报表列表 {#view-report-list}

之后 [创建报告](#create-report)，则可以查看报表列表并选择以CSV格式下载或删除这些报表。

要查看报表列表，请导航至 **[!UICONTROL 设置]** > **[!UICONTROL 报表]**.

对于每个报表，您都可以查看报表标题、报表类型、创建报表时指定的描述、报表状态、创建报表的作者的电子邮件ID以及报表创建日期。

`Completed ` 报表状态表示报表已准备好下载。

![报告列表](assets/list-of-reports.png)


## 下载CSV报表 {#download-csv-report}

要下载CSV格式的报表，请执行以下操作：

1. 导航到 **[!UICONTROL 设置]** > **[!UICONTROL 报表]**.

1. 选择报表并单击 **[!UICONTROL 下载CSV]**.

所选报表将下载CSV格式。 CSV报表中显示的列取决于您在 [创建报告](#create-report).

## 删除报表 {#delete-report}

要删除报表，请执行以下操作：

1. 导航到 **[!UICONTROL 设置]** > **[!UICONTROL 报表]**.

1. 选择报表并单击 **[!UICONTROL 删除]**.
