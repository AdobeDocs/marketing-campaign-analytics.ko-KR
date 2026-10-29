---
title: Marketing Campaign Analytics 워크플로
description: Marketing Campaign Analytics의 일반적인 워크플로를 이해합니다.
feature: Ingest Data, Plans, Harmonized Data, Models
exl-id: 200ff846-5d78-4b25-a425-bfd558b88c88
autotag-review: '2026-05-01T09:15:33.908Z'
TQID: 'https://experienceleague.adobe.com/aOlJN-eYN6Cl-qohzpJbleuQeJFxx3cdxWknVUbmn5I'
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
  - id: fbd94e4b-f9b8-42a4-8df5-3f917aabae24
    internal-label: Schemas
subfeature_v2:
  - id: ad7101f7-ae92-401b-a25a-d3060d42989d
    internal-label: Aggregate datasets
  - id: a4dc3e7d-bd07-4ac8-8e49-ff2e8fecf1e7
    internal-label: Event datasets
  - id: ee1bf083-e090-4def-936b-c111d29f42d0
    internal-label: Ingest data
  - id: d1167c89-f64a-42ca-ac95-1d91b7790df2
    internal-label: Summary datasets
  - id: bc2f5225-03d4-4bc8-89ec-99d78c30e6dd
    internal-label: Conversions
  - id: d4b8ba18-64c1-4413-be54-74405ec7f558
    internal-label: Dataset mapping
  - id: ba4fd72c-282e-4fb6-abc1-08e6fb87b2ad
    internal-label: Dataset rules
  - id: b4655f7e-1a6e-4fa3-a7c5-3c34d4786e49
    internal-label: Harmonized fields
  - id: b2d4aeb9-eabe-49f6-8edb-bb2862d5980b
    internal-label: Marketing touchpoints
  - id: c89e26b6-808d-4500-8b01-450a63466999
    internal-label: Build model
  - id: a9505d76-24a1-4ffe-bd01-6ac32d5af453
    internal-label: Model insights
  - id: cb40363e-1205-4921-971c-9ee6bdb18329
    internal-label: Scoring data
  - id: d7b067e6-4f39-41e9-a081-7650346a84cd
    internal-label: Build plans
  - id: b2520ae7-8f6c-4952-935e-aacc2c10256f
    internal-label: Compare plans
  - id: e6c284e0-b6e6-4f82-bf96-e96bb5157b90
    internal-label: Plan insights
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
topic_v2:
  - id: d00e9f03-e50b-4162-b143-0c0817c937c2
    internal-label: Customer journeys
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
    internal-label: Insights
source-git-commit: 9d6bd798e97d36d49b7753dc9574b102efb3d6bf
workflow-type: tm+mt
source-wordcount: '248'
ht-degree: 1%
---
# Marketing Campaign Analytics 워크플로

Marketing Campaign Analytics의 사용자 워크플로우에 대한 소개는 이 비디오 를 참조하십시오.

>[!VIDEO](https://video.tv.adobe.com/v/3424854/?learn=on)


Marketing Campaign Analytics의 일반적인 워크플로우는 다음 활동으로 구성됩니다.

![대체 텍스트](/help/assets/ApplicationWorkflow.svg)

|  | 활동 | 설명 |
|---|---|---|
| ![데이터](/help/assets/icons/Data.svg){width="100"} | [**데이터 수집**](../ingest-data/overview.md) | Experience Platform의 이벤트 데이터(예: Adobe Analytics, Web SDK, 기타 소스), 마케팅 채널의 집계 데이터(예: TV, 벽으로 둘러싸인 정원, 이메일, 소유 및 운영되는 활동), 고객의 외부 요인 데이터(예: 구독 서비스의 가격 변경) 및 내부 요인 데이터(예: 휴일 플랜)를 수집합니다. |
| ![DataCheck](/help/assets/icons/DataCheck.svg){width="100"} | [**데이터 통합**](../harmonize-data/overview.md) | 매핑 규칙 및 충돌 해결 규칙을 구성하여 Marketing Campaign Analytics에서 캠페인 성과를 측정하고 계획하는 데 필요한 다양한 마케팅 데이터 세트를 병합합니다. |
| ![FileConfig](/help/assets/icons/FileGear.svg){width="100"} | [**모델 빌드**](../models/overview.md) | 마케팅 접점(예: 채널), 전환 정의 및 내부 및 외부 요인이 있는 모델 인스턴스를 빌드합니다. |
| ![파일 데이터](/help/assets/icons/FileData.svg){width="100"} | [**교육 및 점수 모델**](../models/overview.md) | 머신 러닝 교육 및 채점을 사용하여 집계 및 이벤트 수준 점수를 만드십시오. |
| ![파일 차트](/help/assets/icons/FileChart.svg){width="100"} | [**계획 작성**](../plans/overview.md) | 계획을 만들고 빌드합니다. Marketing Campaign Analytics 모델의 결과를 사용하여 비즈니스 목표를 달성하기 위한 마케팅 자금의 최상의 할당을 결정합니다. |
| ![대시보드](/help/assets/icons/Dashboard.svg){width="100"} | [**개요 대시보드**](../dashboard/overview.md) | 구성 가능한 다양한 시각화를 사용하여 조정된 데이터, 모델 및 계획에 대한 통찰력을 얻으십시오. |

{style="table-layout:auto"}

입력 데이터가 Marketing Campaign Analytics으로 유입될 수 있는 방법과 Marketing Campaign Analytics이 자체 인터페이스뿐만 아니라 Customer Journey Analytics과 같은 다른 솔루션에 대한 출력 데이터를 생성하는 방법에 대한 개요가 아래에 나와 있습니다.

![Marketing Campaign Analytics 입력 출력 데이터 흐름](../assets/mm-input-output.png)

<!--
The detailed data-oriented flowchart below illustrates how:

* harmonized data is based on:

  * experience event data (originating from Analytics source connector, collected through Experience Platform SDKs and APIs, ingested through source connectors, or using streaming ingestion),
  * aggregate or summary data from walled gardens (like Facebook, YouTube), traffic sources, or offline advertising data, and 
  * definitions of harmonized fields and dataset rules.

* a model is based on:

  * the conversion and marketing touchpoint definitions resulting from the harmonized data and 
  * non-marketing aggregate or summary data containing internal or external factors.

* mult-touch attribution event scores can potentially be fed back into Experience Platform data lake for use in subsequent model configuration, training and scoring.

![Comprehensive workflow](/help/assets/comprehensive-workflow.svg)
-->
