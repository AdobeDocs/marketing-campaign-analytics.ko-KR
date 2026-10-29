---
title: 관리
description: Marketing Campaign Analytics 관리 방법을 알아봅니다.
feature: Administration
exl-id: 76d6d15d-a838-4ee2-9929-e55ea8946b80
autotag-review: '2026-05-01T09:07:55.299Z'
TQID: 'https://experienceleague.adobe.com/GZOR-NsylnAmpFEuZNDpvF0Br8eL-HKGYIPUBs00sNQ'
product_v2:
  - id: b88c80e3-31df-4609-989d-d4dac0e6d973
    internal-label: Marketing Campaign Analytics
feature_v2:
  - id: a567f0f7-0057-4079-8ded-5b24cc25af15
    internal-label: Harmonized data
  - id: d822825b-9821-40d5-9b0d-42a9e3f317c5
    internal-label: Plans
  - id: e0abf868-dae2-4c1c-83e9-b21799232845
    internal-label: Datasets
  - id: f40f1683-8300-4054-aab8-77da06ad63ff
    internal-label: Models
  - id: f6633d1c-3d2d-4f48-95d4-4bbc9913db52
    internal-label: Data governance
  - id: fbd94e4b-f9b8-42a4-8df5-3f917aabae24
    internal-label: Schemas
  - id: fe2edbb1-46f9-4347-a27c-577cab3640cb
    internal-label: Administration
subfeature_v2:
  - id: abe9e290-7d2f-4131-b71e-ef9900865044
    internal-label: Access control
  - id: a6da0571-746e-4d59-89a4-7b691b1c3b9a
    internal-label: Architecture
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
topic_v2:
  - id: b23e006f-0a29-4f1d-8fd0-77aa56f3d12b
    internal-label: Data modeling
  - id: c7d04a2c-412a-4c9d-9d7a-4456eaa5adeb
    internal-label: Governance
  - id: ebde5b41-29c9-4f5e-9ef6-1197e85409e3
    internal-label: Data management
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
  - id: f4e6943a-c91a-4134-a2c7-f4f20cfff2f0
    internal-label: Privacy
source-git-commit: 9d6bd798e97d36d49b7753dc9574b102efb3d6bf
workflow-type: tm+mt
source-wordcount: '201'
ht-degree: 6%
---
# 관리

{{mm-mca-rebranding}}

[Adobe Admin Console](https://helpx.adobe.com/kr/enterprise/using/admin-console.html)을(를) 사용하여 Marketing Campaign Analytics 제품 및 사용자를 관리하십시오.

Marketing Campaign Analytics이 제대로 작동하려면 올바른 권한을 설정해야 합니다.

Adobe Experience Cloud UI에서:

1. 왼쪽 레일에서 **[!UICONTROL ADMINISTRATION]** 아래의 **[!UICONTROL Permissions]**&#x200B;을(를) 선택합니다.

1. 왼쪽 패널에서 ![사용자](/help/assets/icons/User.svg) **[!UICONTROL Roles]**&#x200B;을(를) 선택합니다.

1. 기존 역할을 선택하거나 **[!UICONTROL Create role]**&#x200B;을(를) 사용하여 역할을 만드십시오(예: **Marketing Campaign Analytics**). 기존 역할을 선택한 경우 ![편집](/help/assets/icons/Edit.svg) **[!UICONTROL Edit]**&#x200B;을(를) 선택하여 역할에 대한 권한을 편집합니다. 자세한 내용은 [역할 관리](https://helpx.adobe.com/kr/enterprise/using/admin-console.html)를 참조하십시오.

1. 역할에 대해 하나 이상의 샌드박스를 선택했는지 확인합니다.

1. 역할의 리소스 목록에 **Adobe Marketing Campaign Analytics** 리소스를 추가합니다.

1. 구성 중인 역할에 대해 올바른 **[!UICONTROL Adobe Marketing Campaign Analytics]** 권한을 선택하십시오. 다음 역할 중 하나 이상을 선택할 수 있습니다.

   - **[!UICONTROL View Adobe Marketing Campaign Analytics Harmonized Data]**
   - **[!UICONTROL Manage Adobe Marketing Campaign Analytics Harmonized Data]**
   - **[!UICONTROL View Adobe Marketing Campaign Analytics Models Configuration]**
   - **[!UICONTROL Manage Adobe Marketing Campaign Analytics Models Configuration]**
   - **[!UICONTROL View Adobe Marketing Campaign Analytics Plans Configuration]**
   - **[!UICONTROL Manage Adobe Marketing Campaign Analytics Plans Configuration]**

     ![Marketing Campaign Analytics RBAC](/help/assets/mix-modeler-rbac.png)


1. 역할에 대한 추가 권한을 선택해야 합니다. 예를 들어 데이터 세트와 스키마를 보거나 관리하려면 다음을 선택합니다.

   - **[!UICONTROL Data Management]**: 관련 옵션을 선택하십시오. **[!UICONTROL View Datasets]** 또는 **[!UICONTROL Manage Datasets]**.

   - **[!UICONTROL Data Modeling]**: 관련 옵션을 선택하십시오. **[!UICONTROL Manage Schemas]** 또는 **[!UICONTROL View Schemas]**.

   <!--
    * **[!UICONTROL Data Governance]**: ensure you select **[!UICONTROL View User Activity Log]** and **[!UICONTROL View Data Usage Policies]**.
    -->

   <!--![Permissions](assets/permissions-including-privacy.png)-->

   **[!UICONTROL Save]**&#x200B;을(를) 선택하여 권한을 저장합니다.

1. **[!UICONTROL Role]** 내의 **[!UICONTROL Details]**&#x200B;에서 적절한 **[!UICONTROL Users]** 또는 **[!UICONTROL User groups]**&#x200B;을(를) 추가하여 사용자에게 Marketing Campaign Analytics에 대한 액세스 권한을 제공합니다.
