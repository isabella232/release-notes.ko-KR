---
title: 최신 릴리스 정보
description: ' [!DNL Experience Cloud] 제품 및 서비스의 최신 릴리스 정보, 새로운 기능 및 새로운 설명서에 대해 알아봅니다.  [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise], and [!DNL Document Cloud]에 대한 새로운 도움말 및 튜토리얼 찾기.'
doc-type: release notes
last-update: November 2021
author: mfrei
mini-toc-levels: 1
exl-id: null
source-git-commit: f348d6153d81dae8ef84cd1aeb797e707104f392
workflow-type: tm+mt
source-wordcount: '4128'
ht-degree: 60%

---

# Adobe Experience Cloud 릴리스 노트 - 2021년 11월

![배너](assets/experience-cloud-banner-3.png)

[!DNL Experience Cloud] 애플리케이션과 서비스는 매달 업데이트됩니다. 이 페이지는 [!DNL Experience Cloud] 및 [!DNL Experience Platform]의 최신 릴리스 업데이트, 설명서 및 튜토리얼을 찾을 수 있는 중앙 위치입니다. [!DNL Creative Cloud for enterprise] 및 [!DNL Document Cloud]에 대한 새로운 설명서도 찾을 수 있습니다.

>[!NOTE]
>
>월별 [Adobe 우선 순위 제품 업데이트](https://www.adobe.com/kr/subscription/priority-product-update.html) 를 구독하면 이 페이지의 업데이트에 대한 이메일 알림을 받을 수 있습니다. 이 페이지는 한 달 동안 유지되므로 Adobe 엔터프라이즈 제품 및 Experience League 설명서에 대한 업데이트를 정기적으로 확인하십시오.

릴리스 시기: **2021년 11월**

최신 업데이트: **2021년 10월 22일**

* [[!DNL Experience League] 라이브 이벤트](#events)
* [[!DNL Experience Cloud Central Interface Components] 및 관리](#ecloud)
* [Adobe [!UICONTROL 시스템 상태]](#status)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics) 및 [Customer Journey Analytics](#cust-journey)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Document Cloud]](#doc-cloud)
* [[!DNL Creative Cloud for enterprise]](#creative-cloud)

도움이 필요하십니까? [Adobe Experience League](https://experienceleague.adobe.com/?lang=ko-KR/#home) 에서 제품 및 기술 문서, Adobe에서 제공하는 교육 과정, 비디오 튜토리얼, 빠른 답변, 커뮤니티 통찰력 및 강사 중심의 트레이닝을 확인할 수 있습니다.

## ![아이콘](/assets/experience-league.png) [!DNL Experience League] 라이브 이벤트 {#events}

[라이브 이벤트 Experience League](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en) Adobe 전문가 및 특별 손님과 함께 Adobe 기술을 귀사에 제공하는 데 중요한 역할을 합니다. 아래 일정을 확인하여 실시간으로 참여하거나 이전에 녹화된 이벤트를 시청하십시오.

| 이벤트 날짜 | 시간 | 이벤트 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2021년 10월 21일 | 온디맨드 | [누가 클릭했는가? Adobe Analytics를 사용한 링크 클릭에 대한 고급 보고](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en) | 라이브 비디오 이벤트 | 웹 또는 모바일 속성과의 사용자 상호 작용에 대한 보고는 고객의 여정을 이해하는 데 중요한 부분입니다. Adobe Analytics를 사용하면 애플리케이션에서 클릭할 때마다 누가, 무엇을, 왜, 어디에서 클릭하는지 이해할 수 있습니다. Activity Map 분류 및 사용자 지정 속성 분석을 사용하여 사용자 참여를 보다 잘 이해할 수 있는 주요 팁을 Adobe Analytics 전문가로부터 배워 보십시오. |
| 2021년 10월 4일 | 온디맨드 | [Adobe 개발자 라이브](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=en) | 비디오 | 이벤트가 없거나 특정 세션의 재생을 찾고 계십니까? Experience League에서 찾으십시오. Developers Live는 업계 전반에 걸쳐 디자인, 컨텐츠 제작 워크플로우, 문서 서비스 및 고객 경험 관리를 제공하는 최신 기술 향상 및 개발자 도구를 소개합니다. 기조 연설을 보고 Analytics API, 클라이언트 데이터 레이어, 오픈 소스 프로젝트 Adobe I/O 등에 대해 알아보십시오. |

{style=&quot;table-layout:auto&quot;}

자세한 비디오는 YouTube의 [Adobe Experience League 채널](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw)을 참조하십시오.

## ![아이콘](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] 및 관리 {#ecloud}

| 기능 | 설명 |
| ------- | ------- |
| 홈 페이지 | Experience Cloud 홈 바닥글 정보가 기본 설정에서 법적 공지 및 언어 선택을 포함하여 사용자 프로필 카드로 이동되었습니다. |
| AEP 대시보드 | [!DNL Helios Lite] Experience Platform 위젯 작성 워크플로우 내에서 차트 권장 사항을 제공합니다. 데이터 선택(현재 단일 변수 데이터 선택)이 주어지면, [!DNL Helios] 는 해당 데이터 선택 시 적절한 시각화를 사용할 것을 권장합니다. |
| AEP 대시보드 | [!DNL Instory] 차트에 대한 ML 기반 설명 및 캡션을 제공합니다. 그래프 데이터에서 주요 변경 사항 및 장애를 호출한 관련 글머리 기호로 AEP 대시보드 페이지의 차트를 장식합니다. |

{style=&quot;table-layout:auto&quot;}

**[!DNL Experience Cloud Central UI Components] 및 관리에 대한 추가 도움말 리소스**

* [중앙 인터페이스 구성 요소](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=ko-KR) 및 사용자 관리에 대한 관리 도움말
* [장소 - 위치 서비스](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=ko-KR)에 대한 도움말 및 릴리스 정보
* [인물 - 고객 속성 및 대상 라이브러리](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=ko-KR)에 대한 도움말

## ![아이콘](/assets/adobe.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status]는 Adobe 제품 및 서비스 중단, 중단 및 유지 관리 이벤트에 대한 자세한 정보, 상태 업데이트 및 이메일 알림을 제공합니다. [status.adobe.com](https://status.adobe.com/)에서 관련 정보를 확인하십시오.

([!DNL Adobe System Status]에 대한 최신 릴리스 정보는 [2020년 5월 21일](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=ko-KR) 릴리스 정보를 참조하십시오.)

## ![아이콘](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Experience Platform 및 [!UICONTROL Mobile SDK]에 대한 릴리스 업데이트 정보와 새로운 설명서가 포함되어 있습니다.

**2021년 9월 29일**

모든 자세한 내용은 [Experience Platform 릴리스 정보](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=ko-KR)를 참조하십시오.

### Experience Platform 튜토리얼 및 교육 과정 {#tutorials-platform}

Experience Platform 및 서비스를 위해 게시된 최신 비디오, 튜토리얼 또는 교육 과정입니다.

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2021년 11월 | [ 자사 데이터 컨텍스트의 데이터 공동 작업 ](https://experienceleague.adobe.com/docs/platform-learn/tutorials/industry/data-collaboration-in-the-first-party-data-context.html?lang=en#) | 비디오 | 적은 데이터에 대한 액세스 권한을 통해 경험 약속을 이행합니다. 광고주, 게시자 또는 에이전시에 상관없이 이 웨비나는 타사 쿠키 없이 향후에 데이터 공동 작업을 위한 기회를 여는 데 도움이 됩니다. |
| 2021년 10월 | [[!DNL Platform] 관리](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-A-1-2021.1.admin) | 교육 과정 | 권한 및 샌드박스 관리를 포함하여 Experience Platform의 관리 활동에 대해 알아봅니다. |

{style=&quot;table-layout:auto&quot;}

### Adobe 모바일 SDK

Adobe Experience Platform Mobile SDK에 대한 [릴리스 정보 및 변경 로그](https://aep-sdks.gitbook.io/docs/release-notes)를 참조하십시오.

## ![아이콘](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

릴리스 날짜: **2021년 10월 28일**

* [Adobe Analytics의 새로운 기능](#aa-features)
* [Customer Journey Analytics의 새로운 기능](#cust-journey)
* [Adobe Analytics의 수정 사항](#aa-fixes)
* [Analytics 관리자에 대한 중요 공지](#aa-notices)
* [Analytics 교육 과정 및 튜토리얼](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics의 새로운 기능 {#aa-features}

| 기능 | 설명 | [일반 가용성](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=en) - 대상 날짜 |
| ----------- | ---------- | ------- |
| Analysis Workspace의 분 수준 날짜 범위 | 패널 달력의 고급 설정에서 분 수준 날짜 범위를 적용하거나 사용자 지정 날짜 범위를 작성할 수 있습니다. 여러 일에 걸쳐 있는 날짜 범위에 대해 보고하는 경우, 시작 시간이 첫 번째 날에 적용되고 종료 시간이 범위의 마지막 날에 적용됩니다. | 2021년 10월 18일 |
| [!UICONTROL 미디어 재생 소요 시간] | Adobe 스트리밍 미디어 재생 [!UICONTROL 소요 시간]은 시청자 참여에 대한 가치 있는 통찰력을 제공하며 미디어 조직에서는 시간대 지정 기능이 있는 고급 소요 시간 분석을 통해 분 단위 사용자 참여에 대한 보다 심층적이고 세부적인 통찰력을 얻을 수 있습니다. 특정 시점에 미디어 스트림을 보는 데 소요된 시간을 관찰할 수 있습니다. 새로운 5분, 15분 및 30분 세부기간을 포함하여 재생 기간을 다양한 세부기간으로 분할할 수 있습니다. [자세히 알아보기](https://experienceleague.adobe.com/docs/media-analytics/using/media-reports/media-workspace-panels/media-playback-time-spent.html?lang=en) | 2021년 10월 18일 |
| 빠른 [!UICONTROL 세그먼트 빌더] | 비즈니스 사용자가 간소화된 인라인 프로젝트 워크플로에서 기본 세그먼트를 빠르게 적용할 수 있습니다. [!UICONTROL 세그먼트 빌더]로 이동할 필요가 없습니다. [자세히 알아보기](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/components/segments/quick-segments.html?lang=en) | 2021년 10월 21일 |
| Analysis Workspace 왼쪽 레일 검색 개선 사항 | 왼쪽 레일 검색 1)에서는 구성 요소 최신성 및 관련성을 계속 고려하는 것 외에도 광범위한 일치보다 정확하게 일치하는 항목에 우선 순위를 둡니다. 2) 일치하는 문자를 강조 표시하여 검색 결과를 보다 이해하기 쉽게 만듭니다. 3) 차원과 관련된 분류를 쉽게 찾을 수 있습니다. 4) 마지막으로 와일드카드(`*`) 검색을 지원하여 필요한 특정 구성 요소를 보다 쉽게 찾을 수 있습니다. 참고: 와일드카드 검색은 아직 차원 항목 수준에서 작동하지 않습니다. | 2021년 10월 21일 |
| Analysis Workspace 어두운 테마 | 어두운 테마를 표시 옵션으로 사용할 수 있습니다. | 2021년 10월 21일 |

{style=&quot;table-layout:auto&quot;}

### Customer Journey Analytics의 새로운 기능 {#cust-journey}

| 기능 | 설명 | [일반 가용성](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html) - 대상 날짜 |
| ----------- | ---------- | ----- |
| Analysis Workspace의 분 수준 날짜 범위 | 패널 달력의 고급 설정에서 분 수준 날짜 범위를 적용하거나 사용자 지정 날짜 범위를 작성할 수 있습니다. 여러 일에 걸쳐 있는 날짜 범위에 대해 보고하는 경우, 시작 시간이 첫 번째 날에 적용되고 종료 시간이 범위의 마지막 날에 적용됩니다. | 2021년 10월 18일 |
| 빠른 [!UICONTROL 필터 빌더] | 비즈니스 사용자가 간소화된 인라인 프로젝트 워크플로에서 기본 세그먼트를 빠르게 적용할 수 있습니다. [!UICONTROL 필터 빌더]로 이동할 필요가 없습니다. [자세히 알아보기](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-components/cja-filters/quick-filters.html) | 2021년 10월 21일 |
| Analysis Workspace 왼쪽 레일 검색 개선 사항 | 왼쪽 레일 검색 1)에서는 구성 요소 최신성 및 관련성을 계속 고려하는 것 외에도 광범위한 일치보다 정확하게 일치하는 항목에 우선 순위를 둡니다. 2) 일치하는 문자를 강조 표시하여 검색 결과를 보다 이해하기 쉽게 만듭니다. 3) 차원과 관련된 분류를 쉽게 찾을 수 있습니다. 4) 마지막으로 와일드카드(`*`) 검색을 지원하여 필요한 특정 구성 요소를 보다 쉽게 찾을 수 있습니다. 참고: 와일드카드 검색은 아직 차원 항목 수준에서 작동하지 않습니다. | 2021년 10월 21일 |
| Analysis Workspace 어두운 테마 | 어두운 테마를 표시 옵션으로 사용할 수 있습니다. | 2021년 10월 21일 |
| 차원 할당에 대한 전환 확인 기간 | 최대 90일의 검색 창이 데이터 보기 구성의 지속성 아래의 차원 할당 설정에 추가됩니다. [자세히 알아보기](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dataviews/component-settings/persistence.html) | 2021년 10월 28일 |

{style=&quot;table-layout:auto&quot;}

### Adobe Analytics의 수정 사항 {#aa-fixes}

* 경고 관리자에서 경고를 삭제할 수 없는 문제를 해결했습니다. (AN-270656)
* 간헐적으로 Data Warehouse 요청이 실패하는 문제를 해결했습니다. (AN-273713, AN-272790)
* 분류가 업데이트되지 않는 문제를 수정했습니다. (AN-272211)

### Customer Journey Analytics 수정 사항 {#cja-fixes}

* CJA 성능 문제(프로젝트를 로드하는 동안 오류 메시지)가 해결되었습니다. (AN-269451, AN-270649)
* CJA에서 세션 시작 이 페이지 이름에 대한 흐름 항목과 일치하지 않는 문제를 수정했습니다. (AN-273501)
* CJA의 폴아웃 보고서가 제대로 작동하지 않는 문제가 해결되었습니다. (AN-269761)

#### Adobe Analytics의 추가 수정 사항

AN-263327; AN-267807; AN-269757; AN-272789; AN-272888; AN-273155; AN-273320; AN-273369; AN-273405; AN-273469; AN-273581; AN-273642; AN-273688; AN-273988; AN-274007; AN-274030; AN-274156; AN-274188; AN-274226

#### CJA의 추가 수정 사항

AN-270649

### [!DNL Analytics] 관리자에 대한 중요 공지 {#aa-notices}

| 공지 | 추가 또는 업데이트 날짜 | 설명 |
| ----------- | ---------- | ---------- |
| 3개의 Analytics API 서비스에 대한 EOL | 2021년 9월 16일 | **2021년 10월 20일**&#x200B;에 다음 Analytics Legacy API 서비스가 사용 수명 종료 날짜에 도달하여 중단됩니다. 이들 서비스를 사용하여 구축한 현재 모든 통합은 해당 날짜부터 더 이상 작동하지 않습니다.<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>이전 OAuth 인증 (OAuth 및 JWT)</li></ul>Adobe는 질문에 답변하고 진행 방법에 대한 지침을 제공하기 위해 [이전 API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) 를 제공했습니다. 이들 서비스를 사용하는 API 통합은 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 또는 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)로 마이그레이션할 수 있습니다. 이전 OAuth 계정은 [Adobe I/O](https://developer.adobe.com/console) Analytics 통합 계정으로 마이그레이션할 수 있으며, 이 계정은 1.4 Analytics API 및 2.0 Analytics API에 모두 액세스하는 데 사용할 수 있습니다. |
| Data Sources에서 전체 처리를 위한 EOL | 2021년 10월 18일 | 설정 **2022년 1월 31일**, Adobe은 사용자가 오프라인 히트 데이터를 Analytics에 수집할 수 있는 전체 처리 과정을 종료합니다. 이 기능은 를 통해 사용할 수 있습니다 [대량 데이터 삽입 API](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md). [자세히 알아보기](https://experienceleague.adobe.com/docs/analytics/import/data-sources/data-types-and-categories/datasrc-fullproc-eol.html?lang=ko-KR?lang=ko) |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

AppMeasurement 릴리스(버전 2.22.2)에 대한 최신 업데이트는 [JavaScript용 AppMeasurement 릴리스 정보](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=en)를 참조하십시오.

### Analytics 교육 과정 및 튜토리얼 {#tutorials-analytics}

[!DNL Analytics] 및 [!UICONTROL Customer Journey Analytics]의 최신 교육 과정, 튜토리얼 및 문서입니다.

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2021년 11월 | [Adobe Analytics의 세그먼트 컨테이너](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-containers.html?lang=en) | 비디오 (업데이트됨) | 이 비디오에서는 컨테이너를 사용하는 방법을 학습하고 각 컨테이너 유형에 대한 몇 가지 예를 들어 보십시오. |
| 2021년 11월 | [Adobe Analytics의 순차적 세그먼테이션](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/sequential-segmentation.html?lang=en#) | 비디오 (업데이트됨) | 사이트 또는 애플리케이션에서 일련의 동작을 통해 Analysis Workspace에서 세그먼트를 만드는 방법을 알아봅니다. |
| 2021년 11월 | [순차적인 세분화 전/후 시퀀스](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/before-after-sequences-in-sequential-segmentation.html?lang=en) | 비디오 (업데이트됨) | 특정 사용자 경로 전 또는 후의 데이터만 가져오도록 Adobe Analytics에서 세그먼트화하는 방법을 알아봅니다. |
| 2021년 11월 | [Customer Journey Analytics용 Report Builder](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/report-builder-for-customer-journey-analytics.html) | 비디오 | Report Builder의 간단하고 유연한 드래그 앤 드롭 UI를 사용하여 Excel 내의 모든 Customer Journey Analytics 데이터에서 복잡한 데이터 쿼리와 사용자 지정 보고서를 만들 수 있습니다. |
| 2021년 10월 | [시각화를 사용하여 데이터 스토리 전달](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2021.1.visualizations) | 교육 과정 | 프로젝트에 시각화를 추가하고, 데이터를 시각화로 가져오는 방법, 각 시각화가 보여 주는 항목 등 시각화에 대한 기본 사항을 알아봅니다. 필요한 정확한 데이터를 얻기 위해 설정을 구성하는 방법에 대해 알아봅니다. 또한 일반 분석에 실용적인 시각화를 만드는 데 도움이 되는 몇 가지 팁과 사용 사례를 얻을 수 있습니다. |

{style=&quot;table-layout:auto&quot;}

### Analytics 도움말 리소스

* [Adobe Analytics 제품 설명서 및 튜토리얼](https://experienceleague.adobe.com/docs/analytics.html?lang=ko-KR)

## ![아이콘](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager의 수정 및 개선 사항.

* 모든 API 호출이 다음을 반환하는 문제를 해결했습니다. `Undocumented` Swagger 인터페이스를 통해 수행하는 동안 오류가 발생했습니다. (AAM-59190)
* 일부 상황에서 잘못된 사용자 역할이 파트너에 할당되는 문제를 해결했습니다. (AAM-59451)
* API에 대/소문자를 구분하는 인증 헤더가 필요한 문제를 해결했습니다. (AAM-58528)

## ![아이콘](/assets/aem.png) Experience Manager {#aem}

Adobe는 릴리스 정보를 최신 상태로 유지하기 위해 [Experience Manager 릴리스 업데이트 및 로드맵](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html) 페이지를 방문할 것을 권장합니다.

**업데이트 10/13/2021:** 다음을 확인하십시오 [2021년 9월 릴리스 개요](https://video.tv.adobe.com/v/337381) 새로운 기능에 대한 개요는 비디오를 참조하십시오.

### 커뮤니티

* [Adobe Developers Live](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk) | 2021년 10월 4~5일, 7:00 PDT

   Adobe Developers Live는 다양한 배경과 하나의 목적을 가진 Adobe 개발자와 경험 빌더를 한데 모아 놀라운 통합 경험을 만듭니다. 이 이틀 간의 컨퍼런스에서는 중요한 개발자 업데이트, 기술 세션 및 커뮤니티 네트워킹 기회를 제공합니다.

   Experience Cloud, Document Cloud 및 Creative Cloud의 Adobe 제품 팀에서는 업계 전반에 걸쳐 디자인, 컨텐츠 제작 워크플로우, 문서 서비스 및 고객 경험 관리를 제공하는 최신 기술 향상 및 개발자 도구를 소개합니다.

   Adobe는 20개의 Experience Manager 세션을 계획하고 있습니다. 널리 알려 주십시오!

   * [전체 세션 목록](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-october-2021-complete-session-list/m-p/423041#M120517)
   * [무료 등록 – 로그인하여 참석 여부 알리기](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)
   * [Adobe Developers Live 커뮤니티](https://experienceleaguecommunities.adobe.com:443/t5/adobe-experience-manager/registration-for-adobe-developers-live-is-now-open-4th-amp-5th/td-p/422127)

### 새로운 Experience Manager 교육 과정 및 튜토리얼 {#tutorials-aem}

지난 달에 게시된 새로운 비디오, 튜토리얼 및 교육 과정입니다.

| 게시일 | 이름 | 설명 | 유형 | 버전 |
| -----------| ---------- | ---------- |---------- | ---------- |
| 2021년 11월 | [Adobe Experience Manager Sites 기본 사항](https://experienceleague.adobe.com/docs/experience-manager-skill-builder/skill-builder/2021/authoring-fundamentals.html?lang=en) | 비디오 시리즈 | 이 5파트로 구성된 웨비나 시리즈에서 Adobe Experience Manager에서 풍부하고 매력적인 고객 경험을 만드는 방법을 알아봅니다. 기본 개념 및 작업을 학습하면서 컨텐츠 작성 빌딩 블록으로 시작하십시오. AEM 내에서 디지털 자산을 처리하는 사이트 관리 기능과 기본 사항에 대해 알아봅니다. 나중에 콘텐츠를 재사용하고 여러 채널에서 전달하여 시간을 절약하고 보다 효율적으로 사용할 수 있는 기능을 알아보십시오. | AEM Sites |
| 2021년 11월 | [AEM으로 이동 계획 as a Cloud Service](https://experienceleague.adobe.com/?recommended=ExperienceManager-A-1-2021.1.migration) | 교육 과정 | AEM as a Cloud Service으로 이동하는 것과 프로세스를 단순화하는 사용 가능한 도구로 이동하는 것에 대한 고려 사항에 대해 알아봅니다. | AEM CS |
| 2021년 11월 | [AEM as a Cloud Service로 이동](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2021.1.migration) | 교육 과정 | AEM 6에서 Experience Manager as a Cloud Service으로 성공적으로 이동하는 방법을 알아봅니다. | AEM CS |
| 2021년 11월 | [대화형 DoR 다운로드](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/document-services/generate-interactive-dor.html?lang=en#create-custom-servlet) | 비디오 | 적응형 양식 데이터를 사용하여 대화형 DoR을 다운로드하는 방법을 학습합니다. | AEM 양식 |
| 2021년 11월 | [Adobe Experience Manager as a Cloud Service 전문가 시리즈](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/aem-experts-series.html?lang=en) | 비디오 시리즈 | Adobe을 구축하는 전문 엔지니어의 AEM(Adobe Experience Manager) as a Cloud Service 및 이를 제공하는 전문 서비스 팀에 대해 알아봅니다. Adobe의 전문가들과 함께 AEM as a Cloud Service이 무엇인지, AEM 6과 어떻게 비교되는지, AEM 6에서 AEM으로 어떻게 이동하는지 살펴보십시오. | AEM CS |
| 2021년 11월 | [서비스 사용자](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/advanced/service-users.html?lang=en) | 비디오 | AEM 코드에서 서비스 사용자를 만들고 사용하여 AEM 리포지토리에 제어되고 프로그래밍 방식으로 액세스하는 방법을 알아봅니다. | AEM CS |

{style=&quot;table-layout:auto&quot;}

### Experience Manager 릴리스 정보 {#aem-links}

아래에서 Experience Manager에 대한 릴리스 정보 및 기타 릴리스 정보 링크를 찾아보십시오.

* [[!DNL Experience Manager as a Cloud Service] 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html?lang=ko-KR)
* [[!DNL Experience Manager as a Cloud Service] 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/home.html?lang=ko-KR)
* [[!DNL Experience Manager Cloud Manager] 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=ko-KR)
* [자동 양식 전환 서비스 릴리스 정보](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=ko-KR)
* [Experience Manager 6.5 서비스 팩 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=ko-KR)
* [Experience Manager 6.4 Cumulative Fix Pack 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=ko-KR)
* [[!DNL Experience Manager Assets Dynamic Media] 릴리스 정보](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=ko-KR)
* [[!DNL Experience Manager Brand Portal] 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=ko-KR)
* [Experience Manager 데스크탑 앱 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=ko-KR)
* [[!DNL Experience Manager Dispatcher] 릴리스 정보](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=ko-KR)
* [Adobe Primetime 릴리스 정보](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=ko-KR)
* [Livefyre 릴리스 정보](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=ko-KR)

### Experience Manager용 기타 도움말 리소스

* [[!DNL Experience Manager as a Cloud Service] 안내서](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=ko-KR)
* [Experience Manager 6.5 학습 및 지원 홈](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=ko-KR)
* [Experience Manager 6.4 학습 및 지원 홈](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=ko-KR)
* [Experience Manager 6.3 학습 및 지원 홈](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=ko-KR)
* [Experience Manager 6.2 학습 및 지원 홈](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=ko-KR#previous-updates)
* [이전 버전의 Experience Manager 설명서](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [[!DNL Cloud Manager] 사용 안내서](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=ko-KR)
* [[!DNL Dynamic Media Classic] 도움말 홈](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=ko-KR)
* [Experience Manager 설명서: 최신 업데이트](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=ko-KR#aem-as-a-cloud-service)

## ![아이콘](/assets/magento.png) [!DNL Commerce] (Magento) {#magento}

Adobe Commerce 릴리스 정보에 대한 다음 링크를 참조하십시오.

* [Adobe Commerce 및 Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Adobe Commerce용 클라우드 제품군](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 새로운 Adobe Commerce 자습서 {#commerce-tutorials}

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2021년 11월 | [Adobe Commerce 비디오 및 Tutorials](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/overview.html?lang=en) | 튜토리얼 홈 | 이러한 자습서 리소스에는 고급 항목 보기를 제공하는 비디오 시리즈와 특정 작업 및 프로세스를 타겟팅하는 개별 비디오가 포함됩니다. 이 컬렉션은 백엔드 개발자, 프런트 엔드 개발자, 시스템 관리자, 상인 및 조직 내의 기타 역할을 위한 유용한 콘텐츠를 제공하도록 설계되었습니다. |

## ![아이콘](/assets/target.png) [!DNL Target] {#target}

마지막 업데이트 날짜: **2021년 10월 20일**

최신 릴리스 정보는 [[!DNL Target] 릴리스 정보](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=ko-KR)를 참조하십시오.

## ![아이콘](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign은 온라인 및 오프라인 마케팅 채널 간에 직관적이고, 자동화된 방식으로 일대일 메시지를 제공합니다. 이제 고객이 습관 및 선호도에 따라 결정된 작업 환경을 통해 원하는 사항을 예측할 수 있습니다.

### 최신 Campaign 제품 릴리스

릴리스된 최신 기능, 개선 사항 및 수정 사항에 대해 자세히 알아보십시오.

* [Campaign v8 릴리스 정보](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/release-notes.html?lang=ko-KR)
* [Campaign Classic v7 릴리스 정보](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=ko-KR)
* [Campaign Standard 릴리스 정보](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=ko-KR)

### 새로운 [!UICONTROL Campaign] 교육 과정 및 튜토리얼 {#tutorials-campaign}

Adobe Campaign용 최신 튜토리얼 및 교육 과정입니다.

| 게시일 | 이름 | 설명 | 유형 | 버전 |
| -----------| ---------- | ---------- |---------- | ---------- |
| 2021년 11월 | [캠페인을 대상으로 Experience Platform 연결](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-platform/import-experience-platform-data-into-campaign/connect-campaign-to-experience-platform-as-destination.html?lang=en) | 비디오 | Amazon S3 연결 유형을 사용하여 대상에 Adobe Experience Platform 세그먼트를 활성화하는 방법을 알아봅니다. | AEP &amp; Campaign V8 |
| 2021년 11월 | [Experience Platform과 통합 - 개요](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-platform/overview.html?lang=en) | 비디오 | Campaign과 Experience Cloud 간에 데이터를 공유하는 방법을 알아봅니다. | AEP &amp; Campaign V8 |
| 2021년 11월 | [Experience Platform에서 수신자 데이터 가져오기 및 이메일 보내기](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-platform/import-experience-platform-data-into-campaign/import-recipient-data-from-platform.html?lang=en) | 비디오 | Adobe Experience Platform에서 Campaign으로 수신자 데이터를 가져오기 위해 Adobe Campaign에서 외부 계정을 구성하는 방법을 배웁니다. Experience Platform에서 받은 수신자를 업로드하고 타겟팅하는 워크플로우를 만드는 방법을 이해합니다. | AEP &amp; Campaign V8 |
| 2021년 11월 | [워크플로우에서 SOAP API 사용](https://experienceleague.adobe.com/docs/campaign-learn/use-soap-apis/introduction.html?lang=en) | 비디오 자습서 | Adobe Campaign Soap API를 사용하는 방법 및 API를 통해 수신된 데이터를 기반으로 고급 전달 워크플로를 만드는 방법에 대해 알아봅니다. | Campaign V8 |

{style=&quot;table-layout:auto&quot;}

### Campaign 도움말 리소스

* Adobe Campaign v8: [설명서](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=ko-KR) - [릴리스 노트](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=ko-KR) - [구현 안내서](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=ko-KR)
* Adobe Campaign Standard: [Campaign Standard 설명서](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=ko-KR) - [릴리스 정보](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [사용 방법 비디오](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=ko-KR) - [릴리스 계획](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=ko-KR) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=ko-KR)
* Adobe Campaign Classic: [Campaign Classic v7 설명서](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=ko-KR) - [릴리스 정보](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [사용 방법 비디오](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=ko-KR) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=ko-KR)
* Adobe Campaign 제어판: [설명서](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=ko-KR) - [릴리스 정보](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=ko-KR) - [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=ko-KR) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=ko-KR) 방법 비디오

## ![아이콘](/assets/experience_platform_appicon_24.png) Journey Optimizer {#journey-opt}

Adobe Journey Optimizer를 사용하면 단일 애플리케이션에서 수백만 고객을 위한 예정된 옴니채널 캠페인과 일대일 순간을 관리할 수 있으며, 지능적인 의사 결정과 통찰력으로 전체 여정을 최적화할 수 있습니다.

### 최신 Journey Optimizer 제품 릴리스

[Journey Optimizer 릴리스 정보](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html)에서 최신 기능, 개선 사항 및 수정 사항에 대해 알아봅니다.

### Journey Optimizer 튜토리얼 및 교육 과정 {#tutorials-ajo}

최신 Journey Optimizer 튜토리얼:

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2021년 10월 | [데이터 엔지니어를 위한 [!DNL Journey Optimizer] 에서 데이터 구성 및 관리](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.2) | 교육 과정 | Journey Optimizer에서 여정 관리에 필요한 데이터를 구성하고 관리하는 방법에 대해 알아봅니다. |
| 2021년 10월 | [여정 관리자 및 관리자를 위한 [!DNL Journey Optimizer] 시작하기](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.1) | 교육 과정 | 첫 번째 여정을 만들기 위해 알아야 하는 모든 것을 배웁니다. |
| 2021년 10월 | [여정 관리자를 위한 [!DNL Journey Optimizer] 구성](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-A-1-2021.1) | 교육 과정 | [!DNL Journey Optimizer] 아키텍처 및 통합 지점에 대해 이해합니다. [!DNL Journey Optimizer]를 구성하는 방법에 대해 알아봅니다. |

{style=&quot;table-layout:auto&quot;}

### [!DNL Journey Optimizer]를 위한 추가 리소스

* [Journey Optimizer 설명서](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=ko-KR) - [릴리스 노트](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [방법 비디오](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=ko-KR)
* [의사 결정 관리 설명서](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started/starting-offer-decisioning.html?lang=ko) - [릴리스 노트](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [방법 비디오](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html)

## ![아이콘](/assets/experience_platform_appicon_24.png) [!DNL Journey Orchestration] {#journey-orch}

Experience Platform을 사용하여 모든 개인의 요구 사항을 실시간으로 지능적으로 예측하여 경험 채널에서 규모에 맞게 고객 여정을 조율할 수 있습니다.

### 최신 [!DNL Journey Orchestration] 제품 릴리스

의 최신 기능, 개선 사항 및 수정 사항에 대해 자세히 알아보십시오 [[!DNL Journey Orchestration] 릴리스 노트](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=ko-KR).

#### [!DNL Journey Orchestration]를 위한 추가 리소스

* [Journey Orchestration 설명서](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=ko-KR) - [릴리스 노트](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [방법 비디오](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=ko-KR) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=ko-KR)

## ![아이콘](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] 는 리드 관리를 위한 완전한 애플리케이션이며, 복잡한 구매 여정의 모든 단계에서 고객 경험을 전환하여 고객 경험을 혁신하고자 하는 B2B 마케터입니다.

### 주요 Marketo Engage 업데이트

최신 릴리스 일정 정보 및 릴리스 정보는 [!DNL Marketo Engage] [릴리스 일정](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=ko-KR)을 참조하십시오.

## ![아이콘](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe [!DNL Workfront]는 아이디어 공유, 콘텐츠 생성, 복잡한 프로세스 관리 및 최상의 작업 수행을 위한 통합 작업 관리 애플리케이션입니다.

모든 제품에 대한 최신 정보를 보려면 [[!DNL Workfront] 릴리스](https://one.workfront.com/s/product-releases) 페이지를 참조하십시오.

## ![아이콘](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

[!DNL Adobe Advertising Cloud]의 릴리스 정보.

* [ [!DNL Advertising Cloud DSP]의 새로운 기능](#adcloud-dsp)
* [ [!DNL Advertising Cloud Search]의 새로운 기능](#adcloud-search)

### [!DNL Advertising Cloud DSP]의 새로운 기능 {#adcloud-dsp}

마지막 업데이트: **2021년 10월 7일**

| 기능 | 설명 |
| ------- | ----------- |
| 설명서 | 모두 [DSP 및 기타 Advertising Cloud 설명서](https://experienceleague.adobe.com/docs/advertising-cloud.html) on [!DNL Experience League] 이제 모든 언어로 번역된 기계입니다. 표시된 언어를 변경하려면 페이지의 왼쪽 하단에 있는 &quot;언어 변경&quot; 메뉴를 사용합니다. |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud Search]의 새로운 기능 {#adcloud-search}

마지막 업데이트: **2021년 10월 7일**

| 기능 | 설명 |
| ------- | ----------- |
| [!UICONTROL 보고서], [!UICONTROL 알림 센터] | (10월 9일 릴리스) 사용자 지정 또는 예약된 보고서가 완료되거나 실패할 때 Advertising Cloud Search에서 보내는 보고서에 대한 모든 이메일 알림은 이제 [!UICONTROL 알림 센터]. 보고서에 대해 기본적으로 이메일 알림 및 웹 알림이 활성화되지만 선택적으로 알림 설정을 변경할 수 있습니다. 이 변경 사항:<ul><li>전자 메일 수신자는 Advertising Cloud Search의 등록된 인증된 사용자로 제한되어 있으며 광고주 계정에 액세스할 수 있습니다. 이 기능을 사용하면 권한이 없는 사용자에게 기밀 데이터가 전송되지 않습니다.</li><li>이메일의 형식과 콘텐츠는 [!UICONTROL 알림 센터] 템플릿에는 보고서의 세부 사항을 더 포함하고 모든 보고서 형식에 대한 직접 다운로드 링크가 포함됩니다.</li><li>보고서 알림은 고유한 알림 환경 설정을 사용하는 새로운 알림 유형입니다. [!UICONTROL 알림 센터].</li></ul>자동화를 사용하여 전자 메일 알림에서 보고서를 가져오는 경우, 프로세스 지속성을 위해 필터링 논리를 업데이트해야 할 수 있습니다. |
| 광고 인사이트 | 추가 Insights는 Beta 모드에서 사용할 수 있습니다. |

{style=&quot;table-layout:auto&quot;}

## ![아이콘](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Adobe Document Cloud용으로 게시된 새로운 비디오, 튜토리얼 또는 교육 과정

### Document Cloud 과정 및 튜토리얼 {#tutorials-doc-cloud}

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2021년 11월 | [작업 공간 기본 사항](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/get-to-know-the-acrobat-dc-interface.html) | 비디오 (업데이트됨) | Acrobat DC 인터페이스를 통해 일관된 작업 공간 환경을 사용하여 데스크탑, 웹 및 모바일 장치에서 손쉽게 파일 및 도구에 액세스하는 방법을 알아봅니다. |
| 2021년 11월 | [Acrobat 웹을 사용한 어디에서나 작업](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/acrobatweb.html) | 비디오 | 브라우저에서 Acrobat 웹 도구를 사용하여 어디에서나 비즈니스 문서 요청을 처리하는 방법을 알아봅니다. |
| 2021년 11월 | [Office에서 웹용 PDF 만들기 ](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/createofficeweb.html) | 비디오 | 웹 앱용 Microsoft® Office를 종료하지 않고 PDF 파일을 만드는 방법을 알아봅니다. 이 추가 기능을 사용하려면 Acrobat DC for teams 또는 Acrobat DC for enterprise 구독 서비스가 필요합니다. |
| 2021년 11월 | [실시간 공동 작업](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/collaborate.html) | 비디오 | 주석을 수집하거나 응답을 공동으로 작업하고 문서의 진행 상황을 실시간으로 추적하여 프로젝트를 앞으로 나아가게 합니다. |
| 2021년 11월 | [ 이동 중에도 생산성 향상](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/productivity.html) | 비디오 | Acrobat Reader 모바일 앱을 사용하여 태블릿 또는 휴대폰에서 바로 더 많은 작업을 수행할 수 있습니다. |

{style=&quot;table-layout:auto&quot;}

Document Cloud 도움말은 다음을 참조하십시오.

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=ko-KR)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=ko-KR)
* [Document Cloud 학습 및 지원](https://helpx.adobe.com/kr/support/document-cloud.html)

## ![아이콘](/assets/creative-cloud-24.png) Creative Cloud for enterprise {#creative-cloud}

최신 튜토리얼은 [Creative Cloud for enterprise 튜토리얼](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=ko-KR)을 참조하십시오.
