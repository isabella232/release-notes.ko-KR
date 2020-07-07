---
title: Adobe Experience Cloud 릴리스 노트
description: Adobe Experience Cloud 릴리스 노트
doc-type: release notes
last-update: June 2020
author: mfrei
translation-type: tm+mt
source-git-commit: efd848cda1046613c889825fff57b868b67e1c80
workflow-type: tm+mt
source-wordcount: '7021'
ht-degree: 99%

---


# Adobe Experience Cloud 릴리스 노트 - 2020년 6월

![배너](/assets/experience-cloud-banner-3.png)

이 페이지에서는 [!DNL Adobe Experience Cloud]에 대한 새로운 기능, 수정 사항 및 중요 정보를 설명합니다. 또한, Adobe Experience Cloud를 최대한 활용할 수 있는 새로운 설명서, 트레이닝 과정 및 비디오 자습서를 소개합니다.

>[!NOTE]
>
>예정된 릴리스에 대한 이메일 알림을 받으려면 [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html)에 가입하십시오.

**릴리스 날짜: 2020년 6월 18일**

제품 출시 날짜는 다를 수 있습니다. 업데이트를 자주 확인하십시오.

최신 업데이트: **2020년 6월 18일**

* [Adobe 시스템 상태](#status)
* [Experience Cloud 인터페이스](#ecloud)
* [Experience Platform](#platform)
* [여정 편성](#journey-orch)
* [Analytics](#analytics)(및 [Customer Journey Analytics](#cust-journey))
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [캠페인](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/ko-KR/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/kr/primetime/user-guide.html)(Primetime 도움말 페이지 링크)

도움이 필요하십니까? [Adobe Experience League](https://experienceleague.adobe.com/#home)에서 제품 및 기술 문서, Adobe에서 제공하는 교육 과정, 비디오 자습서, 빠른 답변, 커뮤니티 통찰력 및 강사 중심의 트레이닝을 확인할 수 있습니다.

## ![아이콘](/assets/adobe.png) Adobe 시스템 상태 {#status}

[!UICONTROL Adobe 시스템 상태]는 Adobe 클라우드 제품 및 서비스 중단, 중단 및 유지 관리 이벤트에 대한 자세한 정보, 상태 업데이트 및 이메일 알림을 제공합니다. [status.adobe.com](https://status.adobe.com/)에서 관련 정보를 확인하십시오.

릴리스 날짜: **2020년 5월 21일**

**새로운 기능**

* Adobe ID를 사용하면 제품 서비스 및 추가 기능 수준까지 세부적으로 이벤트 알림을 구독할 수 있습니다. 보다 신속하게 구독을 설정할 수 있도록, 이제 자동 구독 프로세스가 사용자의 이용 권한에 따라 제품 및 서비스를 추천합니다. 이를 통해 제공되는 이메일의 수가 감소하고 받은 편지함에서 보다 관련성이 높은 알림을 받아 볼 수 있습니다. [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)에서 시작해 보십시오.

**현재 사용할 수 있는 새로운 기능 및 향상된 기능**

| 기능 | 설명 |
| -----------| ---------- |
| 향상된 구독 및 알림 사용자 경험 | <ul><li>[!DNL Marketo Engage] 지역 위치는 이제 선택한 제품 제공 목록을 기반으로 필터링됩니다.</li><li>[!DNL Marketo Engage] 전자 메일 알림은 사용자의 지역, 위치 및 환경 설정과 관련이 있습니다.</li></ul> |
| 이벤트 구독 확인 | <ul><li>이제 진행 중인 단일 이벤트 업데이트를 구독하면 전자 메일 확인이 제공됩니다.</li></ul> |
| 전역 탐색 유용성 개선 사항 | <ul><li>`Adobe.com`의 최상위 탐색 메뉴에서 일관적인 사용자 경험 제공.</li></ul> |

## ![아이콘](/assets/ec_appicon_24.png) Experience Cloud 인터페이스 {#ecloud}

Experience Cloud 인터페이스 관련 일반 업데이트.

**통합 제품 도메인**

Adobe는 모든 Experience Cloud 애플리케이션에서 사용자 경험을 통합하고 개선하기 위해 도메인 및 인터페이스 헤더를 업데이트했습니다. 이러한 개선 사항은 작지만 중요한 방식으로 경험을 간소화하도록 설계되었습니다. 이러한 개선 사항은 현재 워크플로우를 변경하지 않습니다.

업데이트 내용은 다음과 같습니다.

* 새 애플리케이션 URL: `experience.adobe.com/<application name>`:
   * 모든 제품이 결국 이 URL 패턴을 채택합니다. 한 달 동안 새 URL이 유효한지 확인합니다.
   * 브라우저 지원: 지원되는 브라우저에는 [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] 및 [!DNL Opera](최신 버전)이(가) 포함됩니다. **참고:** Experience Cloud 인터페이스는 이러한 브라우저를 지원하지만 개별 애플리케이션은 일부 브라우저를 지원하지 않을 수 있습니다. (예: [Analytics](https://docs.adobe.com/content/help/ko-KR/analytics/admin/sys-reqs.html)는 [!DNL Opera]를 지원하지 않으며, [Target](https://docs.adobe.com/help/ko-KR/target/using/implement-target/before-implement/supported-browsers.html)은 [!DNL Safari]를 지원하지 않습니다.)
   * ([!DNL Safari] 전용) 도메인 변경으로 인해 [!DNL Safari]에 쿠키 문제가 발생할 수 있습니다. _개인 정보 보호 환경설정에서_&#x200B;사이트 간 추적 방지[!DNL Safari]를 선택 해제하면 도메인(및 모든 사이트 간 경험)에서 쿠키가 활성화되고 Experience Cloud가 이 새로운 도메인에서 작동할 수 있습니다.
* 조직 간 또는 다른 애플리케이션으로 쉽게 전환할 수 있습니다.
* 향상된 제품 도움말: [!UICONTROL Experience League]는 제품에 통합되어 있으므로 도움말 검색에 커뮤니티 포럼 및 비디오 컨텐츠의 결과도 포함됩니다. 이러한 변경 사항을 통해 더 많은 컨텐츠를 간편하게 이용하고 Experience Cloud를 최대한 활용할 수 있습니다. 또한 **[!UICONTROL 도움말]** > **[!UICONTROL 피드백]**&#x200B;을 클릭하여 문제를 보고하거나 Adobe와 아이디어를 공유할 수 있습니다.

다음 앱은 새로운 experience.adobe.com 도메인을 사용합니다.

| 앱 또는 서비스 | 도메인 |
| -----------| ---------- |
| Experience Cloud 홈 페이지 | `experience.adobe.com/home` |
| Adobe Target | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| 여정 관리 | `experience.adobe.com/journeys` |
| Adobe Analytics | `experience.adobe.com/analytics` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Adobe Campaign 제어판 | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places Service | `experience.adobe.com/places` |
| Software Distribution | `experience.adobe.com/downloads` |
| 관리 도구(베타) | `experience.adobe.com/admin` |

>[!NOTE]
>
>[!UICONTROL Marketing Cloud Assets] 선택기의 기존 필터인 **[!UICONTROL 보드 및 컬렉션]**&#x200B;이 중단되었습니다.

## ![아이콘](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

[!DNL Experience Platform] 및 애플리케이션 서비스(예: [!DNL Experience Platform Launch,] [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services] 및 보안 공지)를 위한 릴리스 노트입니다.

릴리스 날짜: **2020년 6월 10일**

[!DNL Adobe Experience Platform]에는 다음과 같은 새로운 기능이 포함되어 있습니다.

* **데이터 과학 작업 공간:** 이제 [!DNL JupyterLab Launcher]실시간 머신 러닝(알파)을 위한 [!DNL Python] 노트북 기초가 포함됩니다.
* **세분화:** 날짜 기능에 대한 멤버십 갱신일 필드가 추가되어 사용자가 연도 없이 날짜를 평가할 수 있습니다.
* **소스:** [!DNL Apache HDFS] 및 [!DNL Couchbase]를 위한 새로운 소스 커넥터입니다.

이러한 기능에 대한 자세한 내용은 [Experience Platform 릴리스 노트](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)를 참조하십시오.

### 추가 환경 플랫폼 릴리스 정보

* [Experience Platform Launch 릴리스 노트](https://docs.adobe.com/content/help/ko-KR/launch/using/intro/release-notes/current.html)
* [보안 게시판 및 권고](https://helpx.adobe.com/kr/security.html) (모든 Adobe 제품)

### 새로운 경험 플랫폼 교육 과정 및 자습서 {#tutorials-plat}

| 컨텐츠 | 컨텐츠 유형 | 설명 |
| -----------| ---------- | ---------- |
| [Adobe Experience Platform 소개](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1) | 교육 과정 | Adobe Experience Platform을 사용하면 모든 채널에서 실행할 수 있는 강력한 실시간 고객 프로파일과 AI 기반의 인사이트로 데이터를 변환하여 최적의 경험을 제공할 수 있습니다. 이 소개 수준 교육 과정은 경험 플랫폼의 기능, 활용 사례, Adobe Experience Cloud와의 관계, 기본 아키텍처, 인터페이스 및 프로젝트 역할에 대한 개요를 제공합니다. |
| [웹 SDK 및 Edge Network 소개](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/introduction-to-web-sdk-and-edge-network.html) | 비디오 자습서 | Adobe Experience Platform SDK 및 Edge Network에 대한 개요입니다. Experience Platform Web SDK는 고객이 하나의 JavaScript 라이브러리, 하나의 비콘 유형, 하나의 데이터 스트림, 하나의 서버측 대상 및 모든 Adobe 애플리케이션 및 타사 대상으로 데이터를 전송할 수 있도록 하는 클라이언트측 JavaScript 라이브러리입니다. |
| [웹 SDK 및 Edge Network 데모](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/demo-of-web-sdk-and-edge-network.html) | 비디오 자습서 | 한 번의 클릭으로 Experience Platform, Analytics, Audience Manager 및 Target에 데이터를 Adobe에 전송하여 Adobe Experience Platform 웹 SDK 및 Edge Network의 활용 사례를 살펴보십시오. |
| [실시간 고객 데이터 플랫폼 데모](https://docs.adobe.com/content/help/en/platform-learn/tutorials/rtcdp/demo.html) | 비디오 자습서 | 실시간 CDP를 사용하여 여러 소스에서 데이터를 수집하는 방법을 살펴볼 수 있습니다. 이러한 데이터를 하나의 실시간 고객 프로파일에 통합하여 해당 데이터를 활성화함으로써 개인화된 고객 경험을 제작할 수 있습니다. |

## ![아이콘](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Adobe Experience Platform을 사용하여 모든 개인의 요구 사항을 실시간으로 지능적으로 예측하여 경험 채널에서 규모에 맞게 개별 고객 여정을 편성합니다.

### 최신 릴리스

최신 릴리스 업데이트는 [Journey Orchestration 릴리스 노트](https://docs.adobe.com/content/help/ko-KR/journeys/using/release-notes/release-notes.html)를 참조하십시오.

### 새로운 Journey Orchestration 교육 과정 및 자습서 {#jo-tutorials}

| 컨텐츠 | 컨텐츠 유형 | 설명 |
| -----------| ---------- | ---------- |
| [관리자를 위한 Journey Orchestration 시작하기](https://experienceleague.adobe.com/?recommended=JourneyOrchestration-A-1-2020.2) | 교육 과정 | Journey Orchestration을 구성 및 사용하는 방법을 살펴볼 수 있습니다. 이 교육 과정에서는 주요 개념과 여정의 오케스트레이션을 활성화하는 데 필요한 구성 단계를 다룹니다. 오케스트레이션된 여정을 제작, 게시 및 분석하는 방법을 알아봅니다. |
| [비즈니스 사용자를 위한 Journey Orchestration 시작하기](https://experienceleague.corp.adobe.com/?recommended=JourneyOrchestration-U-1-2020.1) | 교육 과정 | Journey Orchestration을 구성 및 사용하는 방법을 살펴볼 수 있습니다. 이 교육 과정에서는 주요 개념을 다룹니다. 오케스트레이션된 여정을 만들고, 게시하며, 보고하고, 분석하는 방법을 배웁니다. |

### Journey Orchestration을 위한 추가 리소스

[설명서](https://docs.adobe.com/content/help/ko-KR/journeys/using/journey-orchestration-home.html) - [릴리스 노트](https://docs.adobe.com/content/help/ko-KR/journeys/using/release-notes/release-notes.html) - [방법 비디오](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![아이콘](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

릴리스 날짜: **2020년 6월 18일**

* [Adobe Analytics의 새로운 기능](#aa-features)
* [Customer Journey Analytics의 새로운 기능](#cust-journey)
* [Media Analytics](#media-aa)의 새로운 기능
* [Adobe Analytics의 수정 사항](#aa-fixes)
* [Analytics 관리자에 대한 중요 공지](#aa-notices)
* [새로운 Adobe Analytics 교육 과정 및 자습서](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics의 새로운 기능 {#aa-features}

| 기능 | [일반 가용성](https://docs.adobe.com/content/help/ko-KR/analytics/landing/an-releases.html) - 대상 날짜 | 설명 |
| -----------| ---------- |-------|
| 속성 IQ: 알고리즘 속성 | 2020년 6월 18일 | Analysis Workspace의 [!UICONTROL 알고리즘 속성] 모델은 통계 기술을 사용하여 선택한 지표에 대한 크레딧의 최적 할당을 동적으로 결정합니다. Adobe Analytics Ultimate 고객이 사용할 수 있습니다. [추가 정보...](https://docs.adobe.com/content/help/ko-KR/analytics/analyze/analysis-workspace/attribution/algorithmic.html) |
| 속성 IQ: 사용자 지정 전환 확인 창 | 2020년 6월 18일 | 이제 보고 기간 전 최대 90일로부터 터치포인트를 포함하도록 [!UICONTROL 속성 IQ]에서 모든 속성 모델을 구성할 수 있습니다. 이렇게 하면 일반적으로 이전 달에 발생한 상호 작용을 처리하여 보고 기간 초에 발생하는 이벤트의 속성 정확도가 높아집니다. Adobe Analytics Foundation, Select, Prime, Premium, Premium Attribution, Premium Complete 및 Ultimate 고객이 사용할 수 있습니다. [추가 정보...](https://docs.adobe.com/content/help/ko-KR/analytics/analyze/analysis-workspace/attribution/models.html#lookback-windows) |
| 공유 작업 공간 프로젝트에 대한 프로젝트 역할 | 2020년 6월 18일 | 이제 작업 공간 프로젝트를 공유할 때 원하는 프로젝트 경험에 따라 수신자를 세 개의 프로젝트 역할 중 하나로 배치할 수 있습니다(편집, 복제 및 보기). [추가 정보...](https://docs.adobe.com/content/help/ko-KR/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| 보기 전용 작업 공간 프로젝트 | 2020년 6월 18일 | 작업 공간 프로젝트는 &quot;볼 수 있음&quot;으로만 사용자에게 공유할 수 있습니다. 보기 수신자가 공유 프로젝트를 열면 왼쪽 레일과 제한된 상호 작용 없이 더 제한적인 프로젝트 경험을 받게 됩니다. [추가 정보...](https://docs.adobe.com/content/help/ko-KR/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| 작업 공간 프로젝트 공동 편집 기능 | 2020년 6월 18일 | 편집 가능 역할에 추가된 수신자는 공유된 프로젝트에 대해 저장할 수 있습니다. 이 범위는 관리자와 관리자가 아닌 사용자 모두에게 적용됩니다. [추가 정보...](https://docs.adobe.com/content/help/ko-KR/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| 작업 공간에서 업데이트된 빈 패널 | 2020년 6월 18일 | 이제 작업 공간의 빈 패널에는 패널과 시각화가 포함되어 있으므로 자신에게 가장 적합한 분석 워크플로우를 선택하는 더 원활한 방법을 제공합니다. |
| 중국 RDC에서 사용 가능한 자사 도메인 | 2020년 6월 18일 | 중국 본토에서 사용할 자사 도메인을 요청하도록 `.cn` 도메인으로 고객을 활성화합니다. (중국 성능 최적화 SKU 구입 시 사용 가능한 설명서) |
| 작업 공간의 Quick Insights 패널 | 2020년 6월 25일 | Quick Insights는 Analysis Workspace의 비분석가 및 새 사용자에게 비즈니스 관련 질문에 빠르고 쉽게 답변할 수 있는 방법을 배울 수 있도록 지침을 제공합니다. [추가 정보...](https://docs.adobe.com/content/help/ko-KR/analytics/analyze/analysis-workspace/panels/quickinsight.html) |
| 작업 공간의 Analytics for Target 패널 | 2020년 6월 25일 | Analytics for Target(A4T) 패널을 사용하면 Analysis Workspace에서 자신 있게 Adobe Target 활동 및 경험을 분석할 수 있습니다. [추가 정보...](https://docs.adobe.com/content/help/ko-KR/analytics/analyze/analysis-workspace/panels/a4t-panel.html) |
| [!UICONTROL Workspace 정보] 페이지 | 2020년 6월 18일 | [!UICONTROL Workaspace 정보] 페이지에서는 Analysis Workspace 환경, Adobe Analytics 관리자에 대한 정보(지원이 필요한 경우) 및 제품 내 피드백을 제공하는 방법을 제공합니다. **[!UICONTROL Workspace]** > **[!UICONTROL 도움말]** > **[!UICONTROL Workspace 정보]**&#x200B;에서 찾아볼 수 있습니다. |

### Customer Journey Analytics의 새로운 기능 {#cust-journey}

| 기능 | [일반 가용성](https://docs.adobe.com/content/help/ko-KR/analytics/landing/an-releases.html) - 대상 날짜 | 설명 |
| -----------| ---------- |-----|
| 개체 배열 지원 | 2020년 6월 18일 | 이제 CJA 고객은 Adobe Experience Platform 데이터 세트 스키마 내의 개체 배열에 표시되는 차원 및 지표를 보고할 수 있습니다. [추가 정보...](https://docs.adobe.com/content/help/ko-KR/analytics-platform/using/cja-usecases/object-arrays.html) |
| 속성 IQ: [!UICONTROL 알고리즘 속성] | 2020년 6월 18일 | [!UICONTROL Analysis Workspace]의 [!UICONTROL 알고리즘 속성] 모델은 통계 기술을 사용하여 선택한 지표에 대한 크레딧의 최적 할당을 동적으로 결정합니다. Adobe Analytics Ultimate 고객이 사용할 수 있습니다. [추가 정보...](https://docs.adobe.com/content/help/ko-KR/analytics-platform/using/cja-workspace/attribution/algorithmic.html) |
| 속성 IQ: 사용자 지정 전환 확인 창 | 2020년 6월 18일 | 이제 보고 기간 전 최대 90일로부터 터치포인트를 포함하도록 [!UICONTROL 속성 IQ]에서 모든 속성 모델을 구성할 수 있습니다. 이렇게 하면 일반적으로 이전 달에 발생한 상호 작용을 처리하여 보고 기간 초에 발생하는 이벤트의 속성 정확도가 높아집니다. [추가 정보...](https://docs.adobe.com/content/help/ko-KR/analytics-platform/using/cja-workspace/attribution/models.html) |
| 공유 [!UICONTROL 작업 공간] 프로젝트를 위한 프로젝트 역할 | 2020년 6월 18일 | 이제 [!UICONTROL 작업 공간] 프로젝트를 공유할 때 원하는 프로젝트 경험에 따라 수신자를 세 개의 프로젝트 역할 중 하나로 배치할 수 있습니다(편집, 복제 및 보기). [추가 정보...](https://docs.adobe.com/content/help/ko-KR/analytics-platform/using/cja-workspace/curate-share/share-projects.html) |
| 보기 전용 [!UICONTROL 작업 공간] 프로젝트 | 2020년 6월 18일 | [!UICONTROL 작업 공간 ]프로젝트는 _[!UICONTROL 볼 수 있음]_으로만 사용자에게 공유할 수 있습니다. 보기 수신자가 공유 프로젝트를 열면 왼쪽 레일과 제한된 상호 작용 없이 더 제한적인 프로젝트 경험을 받게 됩니다.[추가 정보...](https://docs.adobe.com/content/help/ko-KR/analytics-platform/using/cja-workspace/curate-share/view-only-projects.html) |
| [!UICONTROL 작업 공간] 프로젝트 공동 편집 기능 | 2020년 6월 18일 | _[!UICONTROL 편집 가능]_역할에 추가된 수신자는 공유된 프로젝트에 대해 저장할 수 있습니다.[추가 정보...](https://docs.adobe.com/content/help/ko-KR/analytics-platform/using/cja-workspace/curate-share/share-projects.html) |
| 작업 공간의 [!UICONTROL Quick Insights] 패널 | 2020년 6월 25일 | Quick Insights는 [!UICONTROL Analysis Workspace]의 비분석가 및 새 사용자에게 비즈니스 관련 질문에 빠르고 쉽게 답변할 수 있는 방법을 배울 수 있도록 지침을 제공합니다. [추가 정보...](https://docs.adobe.com/content/help/ko-KR/analytics-platform/using/cja-workspace/panels/quickinsight.html) |
| [!UICONTROL Workspace 정보] 페이지 | 2020년 6월 18일 | [!UICONTROL Workaspace 정보] 페이지에서는 Analysis Workspace 환경, Adobe Analytics 관리자에 대한 정보(지원이 필요한 경우) 및 제품 내 피드백을 제공하는 방법을 제공합니다. **[!UICONTROL Workspace]** > **[!UICONTROL 도움말]** > **[!UICONTROL Workspace 정보]**&#x200B;에서 찾아볼 수 있습니다. |

<!-->Support for [!UICONTROL Anomaly Detection] - July ??, 2020 - [!UICONTROL Anomaly Detection] provides a statistical method to determine how a given metric has changed in relation to previous data. [Learn more...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/virtual-analyst/anomaly-detection/anomaly-detection.html)<-->

### [!UICONTROL Media Analytics]의 새로운 기능 {#media-aa}

업데이트 날짜: **2020년 6월 18일**

| 기능 | [일반 가용성](https://docs.adobe.com/content/help/ko-KR/analytics/landing/an-releases.html) - 대상 날짜 | 설명 |
| -----------| ---------- | ---------- |
| [지원되는 장치 및 플랫폼](https://docs.adobe.com/content/help/ko-KR/media-analytics/using/supported-devices.html) | 2020년 6월 18일 | 이제 AEP SDK가 포함된 미디어 실행 확장자는 다음과 같은 OTT 장치를 지원합니다.<ul><li>Apple TV(tvOS)</li><li>Fire TV(Fire OS)</li><li>Android TV</li></ul> |  | [지원되는 장치 및 플랫폼](https://docs.adobe.com/content/help/ko-KR/media-analytics/using/supported-devices.html) | 2020년 6월 18일 | 이제 AEP SDK가 포함된 미디어 실행 확장자는 다음과 같은 OTT 장치를 지원합니다.<ul><li>Apple TV(tvOS)</li><li>Fire TV(Fire OS)</li><li>Android TV</li></ul> |
| [플레이어 상태 추적](https://docs.adobe.com/content/help/ko-KR/media-analytics/using/player-state-tracking/player-state-overview.html) | 2020년 5월 29일 | [!UICONTROL Media Analytics] 고객은 전체 화면, 자막, 음소거, PIP(Picture-in-Picture) 및 인포커스에 대한 표준 솔루션 변수 세트를 사용하여 재생 중 뷰어 상호 작용을 캡처할 수 있습니다. 또한 사용자 정의 플레이어 상태를 생성할 수 있는 유연성을 가지게 됩니다. 이제 플레이어 상태 추적 변수를 [!UICONTROL Analysis Workspace] 보고에서 확인할 수 있습니다. 이 기능을 사용하려면 다음 중 하나가 필요합니다. <ul><li>Media [!DNL JavaScript] SDK 3.0 이상</li><li>[!DNL Adobe Experience Platform] (AEP) SDK와 함께 사용하는 경우:</li><li>[!UICONTROL Media Analytics 확장 프로그램] (웹용): 오디오 및 비디오 v1.0 이상용 [!UICONTROL Adobe Media Analytics](3.x SDK)</li><li>[!UICONTROL Media Analytics 확장 프로그램] (모바일용): 오디오 및 비디오 v2.0 이상용 [!UICONTROL Adobe Media Analytics]</li><li>[!UICONTROL 미디어 컬렉션]</li></ul> |

### Adobe Analytics의 수정 사항 {#aa-fixes}

* 멀티바이트 검색이 있는 세그먼트가 특정 보고서 세트와 일치하지 않는 문제를 수정했습니다. 이제 올바른 문자열과 일치합니다. (AN-220043)
* [!UICONTROL Reports &amp; Analytics]의 [!UICONTROL 항목 필터]가 제대로 작동하지 않는 문제를 수정했습니다. (AN-206132)
* [!UICONTROL 예약된 프로젝트] UI의 느린 응답 시간을 수정했습니다. (AN-214837)
* Analytics 보고 API 2.0에서 날짜 범위 오류가 발생하는 문제를 수정했습니다. (AN-215087)
* 인스턴스/방문/방문자가 [!UICONTROL 체류 시간] 지표에 대한 분모로 계산되지 않는 사례를 수정했습니다. 이 문제는 차원에 대한 값이 없는 히트(예: Pagename)가 같은 초 뒤에 올 때 발생합니다. (AN-211074)
* 사용자가 공유된 [!UICONTROL 작업 공간] 프로젝트에 액세스할 수 없는 문제를 수정했습니다. (AN-217561)
* 키가 [!UICONTROL 분류 규칙 빌더]로 분류되지 않는 문제를 수정했습니다. (AN-221538)
* [!UICONTROL 서버 호출 사용량]이 사용 데이터를 보고하지 않는 문제를 수정했습니다. (AN-210452)
* 게시된 Adobe Analytics 세그먼트에 Audience Manager의 데이터가 누락되는 문제를 수정했습니다. (AN-220208, AN-220659)
* 데이터가 표시되지만 [!UICONTROL 데이터 피드]가 &quot;Data Warehouse 데이터 없음&quot;이라고 기록되는 보고서 관련 문제를 수정했습니다. (AN-220784, AN-220858)
* `experiencecloud.com` 도메인에서 [!UICONTROL Ad Hoc Analysis] 시작을 막는 문제를 수정했습니다. (AN-219680, AN-221629)
* Ctrl(또는 Command) + C 핫키 사용과 관련된 문제를 수정했습니다. (AN-221101, AN-221537)
* [!UICONTROL Activity Map] 사용 페이지의 문제를 수정했습니다. (AN-222029, AN-221242)
* [!UICONTROL 폴아웃] 시각화 중간에 터치포인트를 추가할 수 없는 문제를 수정했습니다. (AN-221648)

#### 추가 Adobe Analytics 수정 사항

AN-218269; AN-218455; AN-218492; AN-219888; AN-220447; AN-220546; AN-220788; AN-220866; AN-221165; AN-221545; AN-221712; AN-221832; AN-221853; AN-222000; AN-222505; AN-222559

### [!DNL Analytics] 관리자에 대한 중요 공지 {#aa-notices}

| 공지 | 추가 또는 업데이트 날짜 | 설명 |
| -----------| ---------- | ---------- |
| 통합 제품 도메인으로 마이그레이션 | 시행일: 2020년 5월 28일 | 2020년 1월에 시작된 Adobe Analytics용 통합 제품 도메인으로의 마이그레이션은 2020년 5월 28일에 완료되었습니다. Adobe Analytics에서는 아키텍처에서 모든 `omniture.com` 도메인 참조를 제거하지만 `omniture.com`을 타사 쿠키로 허용리스트 설정하는 것이 중요합니다. 전체 아키텍처 마이그레이션이 (곧) 완료되면 릴리스 노트를 통해 알려 드릴 예정이며 이 허용리스트 단계는 더 이상 필요하지 않습니다. 허용리스트 설정해야 할 권장 IP 주소 및 도메인 전체 목록은 [다음](https://helpx.adobe.com/kr/analytics/kb/adobe-ip-addresses.html)과 같습니다.<br>조직에서 타사 쿠키를 차단하는 경우 고객 지원 센터에 문의하여 Adobe Analytics에 다시 액세스하십시오. |
| 새 Adobe Analytics 기본 랜딩 페이지 | 시행일: 2020년 6월 18일 | 2020년 6월 18일에 Adobe Analytics의 기본 랜딩 페이지가 [!UICONTROL 보고서]에서 [!UICONTROL 작업 공간]으로 변경됩니다. 이 변경 사항은 이전에 사용자 지정 랜딩 페이지를 설정하지 않은 모든 사용자에게 발생합니다. |
| 타사 기술 허용리스트 | 2020년 3월 12일(유효 날짜) | Adobe Analytics는 기능 롤아웃 관리 및 제품 내 지원을 위한 타사 기술을 활용하기 시작했습니다. 모든 기능에 액세스하려면 필수 네트워크 방화벽 허용리스트에 다음 URL을 추가해야 합니다.<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul> |
| [!UICONTROL Analysis Workspace ]가용성을 위한 중복성 개선 | 2020년 5월 21일 | [!UICONTROL Analysis Workspace]의 가용성을 보장하기 위해 중복성을 향상시키기 위해 보조 CDN(Content Delivery Network)을 추가하고 있습니다. 필요한 네트워크 방화벽 허용리스트에 다음 URL을 추가해야 합니다.<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| [!UICONTROL Workspace]에서 [!UICONTROL 시작/종료 수]를 계산하는 방법 변경 | 2020년 4월 7일 | 2020년 3월 현재 [!UICONTROL Analysis Workspace]에서 _없음_ 값이 [!UICONTROL 시작/종료]와 상호 작용하는 방식을 변경했습니다. 이제 _Analysis Workspace_&#x200B;에서 [!UICONTROL 없음]을 켜거나 끌 수 있으므로 시작 또는 종료 후에 _없음_&#x200B;을 적용하지만 기존에는(eVars의 경우) 시작 또는 종료 이전에 적용되었습니다. 예를 들어, 방문의 첫 번째 히트에는 eVar에 대한 값이 없다고 가정하지만 두 번째 히트에는 값이 있다고 가정합니다. [!UICONTROL Reports &amp; Analytics]에서는 첫 번째 히트가 시작에 대해 _지정되지 않음_&#x200B;으로 표시되지만 [!UICONTROL Analysis Workspace]에서는 두 번째 히트에 대한 값으로 표시됩니다. |
| **[!UICONTROL 대시보드 아카이브]**&#x200B;의 EOL | 2020년 3월 27일 | [!UICONTROL Reports &amp; Analytics]의 **[!UICONTROL 대시보드 관리]** 아래에 있는 **[!UICONTROL 아카이브 보기]** 설정은 2020년 10월부터 더 이상 사용할 수 없습니다. |
| 수명 종료 - Analytics 이전 API | 2020년 1월 9일 | 2020년 11월에 다음 Analytics 이전 API 서비스가 종료됩니다. 이러한 서비스를 사용하여 구축된 현재의 통합 기능은 작동하지 않습니다. <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>이전 OAuth 인증(OAuth 및 JWT)</li></ul>질문에 대한 답변과 진행 방법에 대한 지침을 제공하는 데 도움이 되도록 [이전 API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)를 제공했습니다. 이러한 서비스를 사용하는 API 통합은 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 또는 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)로 마이그레이션할 수 있습니다. 이전 OAuth 계정은 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 통합 계정으로 마이그레이션할 수 있으며, 이 계정은 1.4 Analytics API 및 2.0 Analytics API에 모두 액세스하는 데 사용할 수 있습니다. |
| 런던 및 싱가포르의 산호세 FTP Broker 종료 | 2020년 7월 | 런던 및 싱가포르의 고객을 위해 런던 또는 싱가포르와 산호세 데이터 센터 [ftp.omniture.com](ftp://ftp.omniture.com/) 간의 데이터 브로커링을 더 이상 지원하지 않습니다.<br/><ul><li>런던의 경우 [ftp3.omniture.com](ftp://ftp3.omniture.com/) 사용</li><li>싱가포르의 경우 [ftp4.omniture.com](ftp://ftp4.omniture.com/) 사용</li></ul> |
| Ad Hoc Analysis 생산 중단 | 2018년 8월 6일 | Adobe는 Ad Hoc Analysis를 종료할 예정이라고 발표했습니다. 수명 종료 날짜는 확정된 후 공유될 예정입니다. 자세한 내용은 [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)를 참조하십시오. |

#### 새로운 Analytics 교육 과정 및 자습서 {#tutorials-analytics}

Analytics 및 Customer Journey Analytics의 새 강좌, 자습서 비디오 및 문서입니다.

| 컨텐츠 | 컨텐츠 유형 | 설명 |
| -----------| ---------- | ---------- |
| [사용자를 위한 Customer Journey Analytics 시작하기](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-U-1-2020.1) | 교육 과정 | 이 과정에서는 CJA(Customer Journey Analytics)를 사용하여 다양한 데이터 소스의 데이터를 분석하는 방법을 알아봅니다. Adobe Analytics와 고객 경로 분석 간의 차이점과 Customer Journey Analytics에서 데이터를 처리하는 방법에 대해 학습합니다. 이 교육 과정을 이수하면 크로스채널 시각화를 만들고 사용자 정의하여 고객을 더욱 깊이 있게 이해할 수 있습니다. |
| [관리자를 위한 Customer Journey Analytics 시작하기](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1) | 교육 과정 | [!UICONTROL Journey Orchestration]을 구성 및 사용하는 방법을 살펴볼 수 있습니다. 이 교육 과정에서는 경로 지정을 활성화하는 데 필요한 주요 개념 및 구성 단계를 다룹니다. 오케스트레이션된 여정을 만들고, 게시하며, 보고하고, 분석하는 방법을 배웁니다. |
| [데이터 엔지니어를 위한 Customer Journey Analytics 시작하기](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-D-1-2020.1) | 교육 과정 | 이 교육 과정에서는 Customer Journey Analytics으로 수신 데이터와 분석 담당자의 보고서에 미치는 영향에 대해 알아봅니다. 이 교육 과정은 Adobe Experience Platform에 대한 일반적인 지식을 바탕으로 합니다. |
| [관리자를 위한 Customer Journey Analytics 시작하기](https://video.tv.adobe.com/v/34349?captions=kor) | 비디오 자습서 | 관리자를 위한 Customer Journey Analytics 소개 비디오입니다. |
| [Analytics 구현 가이드](https://experienceleague.adobe.com/?recommended=Analytics-D-1-2019.1) | 교육 과정 | 이 교육 과정에서는 Adobe Analytics 구현을 시작하고, Analytics 개념을 이해하며, 계획을 만들고, Experience Platform Launch를 사용하여 Adobe Analytics를 구현하는 방법을 알아봅니다. |
| [리더를 위한 Adobe Analytics 기초](https://experienceleague.adobe.com/?recommended=Analytics-L-1-2020.1) | 교육 과정 | 이 교육 과정에서는 Analytics 기본 사항과 분석 Analysis Workspace가 비즈니스를 변경하는 방법에 대해 학습합니다. Adobe Sensei를 통해 인사이트를 확보하고 고객 추천을 살펴보며 2019년 Summit에서 업계 전문가들로부터 주요 내용을 살펴볼 수 있는 방법을 살펴볼 수 있습니다. |
| [Analysis Workspace 시작하기](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2020.1.workspace) | 교육 과정 | Analysis Workspace를 사용하는 방법을 알아봅니다. 간단한 프로젝트를 제작하고 날짜 범위를 정의하며 세그먼트를 적용하고 프로젝트에서 공유 및 공동 작업하는 방법을 살펴봅니다. |
| [Adobe Analytics 대시보드 스코어카드 빌더](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-scorecard-builder.html) | 비디오 자습서 | 이 비디오에서는 Adobe Analytics 대시보드(모바일 앱)에서 보기 위해 [!UICONTROL Analysis Workspace]에서 [!UICONTROL 스코어카드]를 만들고 공유하는 방법을 알아봅니다. |
| [Adobe Analytics 대시보드 앱 내 경험](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-in-app-experience.html) | 비디오 자습서 | 이 비디오에서는 Adobe Analytics 대시보드(모바일 앱)를 사용하여 사용자가 만들었거나 사용자와 공유한 [!UICONTROL 스코어카드]에 액세스하고 보는 방법을 알아봅니다. |

#### AppMeasurement {#appm}

AppMeasurement 릴리스에 대한 최신 업데이트는 JavaScript용 [AppMeasurement 릴리스 노트를 참조하십시오](https://docs.adobe.com/content/help/ko-KR/analytics/implementation/appmeasurement-updates.html).

#### Analytics 도움말 리소스

* [Adobe Analytics 자습서](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics 제품 설명서](https://docs.adobe.com/content/help/ko-KR/analytics/landing/home.html)

## ![아이콘](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Audience Manager의 새로운 기능, 수정 사항, 설명서 및 자습서.

업데이트 날짜: **2020년 6월 10일**

### 사용자 인터페이스 업데이트

Audience Manager는 경험을 향상하고 다른 Experience Cloud 애플리케이션과의 통합을 위해 도메인 및 헤더 막대를 업데이트하고 있습니다.

* 조직 간 또는 다른 애플리케이션으로 쉽게 전환할 수 있습니다.
* 도움말 메뉴의 주요 문서 및 컨텍스트 관련 비디오를 비롯한 사용자 도움말이 개선되었습니다.
* Experience Platform 및 파일 지원 티켓에 대한 피드백 제공 기능.
* 새롭고 간편해진 URL 패턴. 책갈피를 새 URL(`experience.adobe.com/audience-manager`)로 업데이트했습니다.

이 업데이트는 Adobe ID를 사용하여 로그인하는 사용자만 사용할 수 있습니다. Adobe ID 로그인으로 전환하려면 [Experience Cloud 사용자 및 제품 관리](https://docs.adobe.com/content/help/ko-KR/core-services/interface/manage-users-and-products/admin-getting-started.html)를 참조하십시오.

### Adobe Audience Manager의 새로운 기능 및 수정 사항

| 기능 | 설명 |
| -----------| ---------- |  
| [IAB TCF v2.0용 Audience Manager 플러그인 ](https://docs.adobe.com/content/help/ko-KR/audience-manager/user-guide/overview/data-privacy/consent-management/aam-iab-plugin.html) | Adobe는 Privacy by Design에 주력하여 IAB TCF용 Audience Manager 플러그인을 2020년 6월 10일부터 IAB TCF(Transparency &amp; Consent Framework) 버전 2.0으로 업그레이드했습니다. IAB TCF용 Audience Manager 플러그인을 구현한 고객이 이 기능을 계속 사용하려면 2020년 8월 15일까지 버전 2.0으로 업그레이드해야 합니다. 2020년 8월 15일 이후에는 버전 1.1이 더 이상 지원되지 않습니다. |

**수정 사항**

* 특정 지역의 법적 요구 사항을 반영하도록 [!UICONTROL Audience Marketplace 약관]이 업데이트되었습니다. (AAM-54518)
* 책갈피에서 [!UICONTROL 특성] 페이지에 액세스하면 404 오류가 발생하는 문제를 수정했습니다. (AAM-54768)
* [!UICONTROL 알고리즘 모델]을 검색하는 동안 대상 업데이트 API가 시간 초과되는 문제를 해결했습니다. (AAM-54342)
* 이제 사용자는 [!UICONTROL Smart Personas]를 위한 모델 분류 정확도 지표를 볼 수 있습니다. (AAM-54847)
* 특성 표현식을 추가한 후 Enter 키를 누르면 식이 저장되는 대신 제거되는 문제가 해결되었습니다. (AAM-54210)
* VIEW_MODELS 권한이 없는 사용자에 대해 [!UICONTROL 특성] API의 GET 메서드 호출이 실패하는 문제가 해결되었습니다. (AAM-53104)
* 사용자가 [!UICONTROL 폴더 특성]가 포함된 [!UICONTROL 알고리즘 모델]을 삭제할 수 없는 문제를 해결했습니다. (AAM-50192)
* 이제 긴 트레이트 표현식이 여러 줄에 걸쳐 표시됩니다. (AAM-54972)
* 읽기 전용 권한이 있는 사용자가 알고리즘 모델 페이지에서 [!UICONTROL 새로 만들기] 버튼을 볼 수 있었던 문제를 수정했습니다. (AAM-54889)
* CSV 다운로드가 완료된 후 [!UICONTROL 일반] 및 [!UICONTROL 트렌드] 보고서 로드 표시기가 계속 회전하는 문제를 해결했습니다. (AAM-54571)
* 사용자가 [!UICONTROL 세그먼트 빌더 ]의 세그먼트에 일괄 특성을 추가할 수 없던 문제를 수정했습니다. (AAM-55033)
* 인터페이스에서 여러 액세스 가능성이 개선되었습니다. (AAM-47269, AAM-48966, AAM-48976, AAM-49369, AAM-49023, AAM-49042).

### 새로운 Audience Manager 교육 과정 및 자습서 {#tutorials-aam}

| 컨텐츠 | 컨텐츠 유형 | 설명 |
| -----------| ---------- | ---------- |  
| [Audience Manager 소개](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.1) | 교육 과정 | 이 교육 과정에서는 Audience Manager의 기본 사항과 이를 사용하여 해결할 수 있는 문제를 소개합니다. 일반적인 사용 사례와 주요 Audience Manager 용어 및 개념에 대해 알아봅니다. |
| [Audience Manager의 ID 소개](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/introduction-to-identity-in-audience-manager.html) | 비디오 자습서 | 내부 프로필 및 프로필 병합과 ID 동기화 등 Adobe Audience Manager가 ID를 관리하는 방법을 알아봅니다. |
| [LinkedIn 사용자 기반 대상 이해 및 구성](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/data-activation/people-based-destinations/understanding-and-configuring-the-linkedin-pbd.html) | 교육 과정 | 이 비디오에서는 LinkedIn에 대한 사용자 기반 대상을 만드는 개념과 단계를 안내합니다. 사용자 기반 대상에 대한 추가 비디오 및 설명서를 기반으로 합니다. |
| [규칙 기반 특성 만들기](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/creating-rule-based-traits.html) | 비디오 자습서 | Audience Manager 인터페이스에서 [!UICONTROL Trait Builder]를 사용하여 규칙 기반 특성을 만들어 Audience Manager 프로필로 실시간 활동을 캡처하는 방법을 알아봅니다. |
| [IAB TCF 2.0용 Audience Manager 플러그인 활성화](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#enabling-iab-tcf) | 비디오 자습서 | IAB TCF용 Audience Manager 플러그인을 활성화하는 방법을 알아봅니다. Adobe Experience Platform Launch를 사용하면 이 플러그인을 쉽게 활성화할 수 있습니다. |
| [IAB TCF 2.0용 Audience Manager 플러그인 데모](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#demo) | 비디오 자습서 | 이 비디오에서는 Experience Cloud ID 서비스 및 솔루션의 쿠키 및 비콘이 IAB 사용자 선택 사항의 영향을 받는 방식을 확인할 수 있습니다. |

## ![아이콘](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe Experience Manager(AEM)의 새로운 기능, 수정 및 업데이트입니다. 안정성, 보안 및 성능 향상을 위해 최신 패치를 배포하려는 경우 온-프레미스 배포를 사용하는 것이 좋습니다.

### 제품 업데이트

* **AEM 6.5.5.0**

   AEM 6.5, 서비스 팩 5(2020년 6월 04일 릴리스된 6.5.5.0)은 새로운 기능, 주요 고객 요청 개선 사항, 향상된 성능, 안정성 및 보안 기능을 포함한 중요한 업데이트로, 2019년 4월 AEM 6.5의 공식 출시 이후 릴리스되었습니다.

   * [릴리스 노트](https://docs.adobe.com/content/help/ko-KR/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
   * [AEM Forms 릴리스 결과물](https://helpx.adobe.com/kr/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.1**

   AEM 6.4, 서비스 팩 8, 누적 수정 팩(2020년 6월 04일에 릴리스된 6.4.8.1)은 2020년 3월 AEM 6.4, 서비스 팩 8(6.4.8.0)의 공식 출시 이후 여러 가지 내부 및 고객 수정 사항을 포함하는 중요한 업데이트입니다.

   * [릴리스 노트](https://docs.adobe.com/content/help/ko-KR/experience-manager-64/release-notes/cfp-release-notes.html)
   * [AEM Forms 릴리스 결과물](https://helpx.adobe.com/kr/aem-forms/kb/aem-forms-releases.html)

### 사용자 도움말

* **AEM을 클라우드 서비스로 사용**

   클라우드 서비스로서의 AEM 관련 새로운 기능

   주요 특장점:

   * AEM Sites Commerce Integration Framework.
   * 향상된 스마트 태그 및 UI 안내 교육 경험의 새로운 기능
   * Adobe Xd에 대한 Adobe Asset Link 지원
   * AEM Assets Dynamic Media 3D 지원.
   * 새롭게 향상된 셀프 서비스 기능을 통해 Adobe에서 샌드박스 작업에 대한 의존도를 줄일 수 있습니다.
      * Cloud Manager의 향상된 셀프 서비스 샌드박스 지원을 통해 자격이 부여된 사용자는 샌드박스 내의 모든 환경을 삭제하고 크레딧을 받을 수 있습니다.
      * 자동 최대 절전 모드 샌드박스 환경을 사용하면 비활성 기간 후 자동으로 &quot;최대 절전 모드 해제&quot; 샌드박스가 자동으로 적용됩니다. 고객은 &quot;최대 절전 모드 해제&quot;를 트리거할 수 있습니다.
   * 클라우드 가속 지원을 위한 전환 툴

   온-프레미스 서비스에서 클라우드 서비스로 전환하는 데 소요되는 시간과 비용을 줄이기 위한 목표로, 이번 달에 두 개의 전환 툴이 출시되었습니다. 이러한 툴은 전환 프로세스 동안 일부 주요 작업을 자동화하여 전반적인 노력을 줄일 수 있도록 고안되었습니다. 

   1. [컨텐츠 전송 툴](https://docs.adobe.com/content/help/ko-KR/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html)(SD에서 사용 가능)을 사용하면 컨텐츠 전송 활동을 간소화하고 확장 가능한 컨텐츠를 만들 수 있습니다. 사용자에게 친숙한 UI를 사용하는 이 툴은 AEM을 클라우드 서비스로 전환하는 기존 고객 및 파트너(온-프레미스/AMS)를 위한 셀프 서비스입니다.
   1. [AMS Dispatcher Converter](https://github.com/adobe/aem-cloud-service-dispatcher-converter)(오픈 소스) 도구를 사용하여 AMS Dispatcher 구성을 Cloud Service Dispatcher 구성으로 자동 변환합니다.

   [클라우드 서비스 2020.6.0으로서의 AEM 릴리스 노트](https://docs.adobe.com/content/help/ko-KR/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)

   전환 툴:

   https://github.com/adobe/aem-cloud-service-dispatcher-converter

   https://docs.adobe.com/content/help/ko-KR/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html

* **핵심 구성 요소**

   핵심 구성 요소 2.9.0은 [Adobe 클라이언트 데이터 레이어](https://github.com/adobe/adobe-client-data-layer) 및 새로운 진행률 표시줄 구성 요소와 통합되었으며, 이제 [저작 설명서](https://docs.adobe.com/content/help/ko-KR/experience-manager-core-components/using/introduction.html) 및 [개발자 세부 사항 및 프로젝트 다운로드와 함께 GitHub에서 사용](https://github.com/adobe/aem-core-wcm-components)할 수 있습니다.

* **클라우드 서비스로서의 AEM로 이동**

   [클라우드 서비스로서의 AEM으로 이동](https://docs.adobe.com/content/help/ko-KR/experience-manager-cloud-service/moving/home.html)은 기존 AEM 고객이 클라우드 서비스로 이동하는 권장 전환 여정에 대해 설명합니다. 이 설명서의 목적은 고객에게 정보, 지침 및 모범 사례를 제공하여 이러한 전환을 준비하고 체계적이고 예측 가능한 방식으로 이 여정을 만들 수 있도록 하는 것입니다.

   클라우드 전환 툴 중 하나로써 콘텐츠 전송 도구가 출시되었습니다. [컨텐츠 전송 툴](https://docs.adobe.com/content/help/ko-KR/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/overview-content-transfer-tool.html)은 Adobe에서 개발되었으며, 기존 컨텐츠를 소스 AEM 인스턴스(온-프레미스 또는 AMS)에서 대상 AEM Cloud 서비스 인스턴스로 이동하는 데 사용할 수 있습니다.

   코드 리팩토링 툴 중 하나로써 AEM Dispatcher Converter가 릴리스되었습니다. [AEM Dispatcher Converter](https://docs.adobe.com/content/help/ko-KR/experience-manager-cloud-service/moving/refactoring-tools/dispatcher-transformation-utility-tools.html)는 기존 AEM Dispatcher 구성을 Cloud Service Dispatcher 구성으로 AEM으로 변환하는 툴이며 현재 사용이 가능합니다.

* **접근성 및 WCAG 2.1 지침**

   WCAG 2.1 지침 관련 업데이트:

   * [클라우드 서비스로서의 Adobe Experience Manager 및 웹 액세스 가능성 지침](https://docs.adobe.com/content/help/ko-KR/experience-manager-cloud-service/onboarding/accessibility/web-accessibility.html)
   * [WCAG 2.1에 대한 빠른 안내서](https://docs.adobe.com/content/help/ko-KR/experience-manager-cloud-service/onboarding/accessibility/quick-guide-wcag.html)
   * [액세스 가능한 컨텐츠 만들기(WCAG 2.1 적합성)](https://docs.adobe.com/content/help/ko-KR/experience-manager-cloud-service/sites/authoring/fundamentals/accessible-content.html)

* **AEM 뉴스레터**

   AEM Newsletter by Experience League는 AEM을 빠르게 활용하여 즉시 가치를 실현할 수 있도록 고안되었습니다. 최신 뉴스레터는 다음과 같습니다.

   * [볼륨 31](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.31.html): Experience Manager는 이제 클라우드 서비스로 사용할 수 있습니다.
   * Experience Insider Newsletter [구독](https://adobeeventsonline.com/AEM/2017/NL/Optin/).
   * Adobe Experience Manager 6.5 학습 및 지원 페이지의 [AEM 리소스](https://helpx.adobe.com/kr/support/experience-manager/6-5.html) 섹션의 뉴스레터 아카이브.

### **커뮤니티**

* **AEM 커뮤니티 토론**

   이제 모든 AEM 발표와 내부 및 외부 블로거들에 대한 흥미로운 참조를 한 곳에서 볼 수 있습니다. AEM Community의 [토론 섹션](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)을 참조하십시오.

### 새로운 Experience Manager 교육 과정 및 자습서

| 컨텐츠 | 컨텐츠 유형 | 설명 |
| -----------| ---------- | ---------- |
| [비즈니스 사용자를 위한 Adobe Asset Link 시작하기](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.asset.link) | 교육 과정 | 이 교육 과정에서는 Adobe Asset Link의 기능과 기능을 사용하여 Adobe Experience Manager Assets에 저장된 컨텐츠를 통해 크리에이티브 디자인을 가속화하는 방법을 살펴볼 수 있습니다. 이 교육 과정은 adobe asset link 실행 방법, 기본 자산 작업, 검색 및 검색 옵션, 다른 사용자와 효율적으로 공동 작업하는 방법 등 모든 것을 다룹니다. |
| [비즈니스 사용자를 위한 AEM Assets 시작하기](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.assets) | 교육 과정 | 비즈니스 사용자를 위한 AEM Assets를 시작하는 방법을 알아봅니다. AEM Assets, 공동 작업 기능, 자산 검색, 구성, 자산 및 해당 표현물 다운로드의 기본 사항을 살펴보십시오. |
| [비즈니스 사용자를 위한 AEM Sites 시작하기](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.sites) | 교육 과정 | AEM Sites의 핵심 기능 및 기능을 사용하여 조직의 웹 페이지를 관리하는 방법을 알아봅니다. 이 교육 과정에서는 AEM Sites 소개, 작성에 대한 기본 개념, 고급 제작 기능 및 페이지 관리 기능에 대한 모든 내용을 다룹니다. |
| [AEM 프로젝트 구조](https://docs.adobe.com/content/help/ko-KR/experience-manager-cloud-service/implementing/developing/aem-project-content-package-structure.html) | 문서 | AEM Cloud Service와 호환되도록 Adobe Experience Manager Maven 프로젝트에 필요한 변경 사항에 대해 설명합니다. |
| [Sling 모델](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#sling-models) | 비디오 자습서 | Sling 모델 웹 콘솔을 사용하여 AEM을 클라우드 서비스 SDK의 로컬 빠른 시작으로서 디버깅하는 방법에 대해 학습합니다. |
| [AEM Web Console 구성 요소](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#components) | 비디오 자습서 | 구성 요소 웹 콘솔을 사용하여 AEM을 클라우드 서비스 SDK의 로컬 빠른 시작으로 디버깅하는 것에 대한 학습이 제공됩니다. |
| [로그를 사용하여 AEM SDK의 로컬 빠른 시작 디버깅](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | 비디오 자습서 | 번들 웹 콘솔을 사용하여 AEM을 클라우드 서비스 SDK의 로컬 빠른 시작으로 디버깅하는 것에 대한 학습이 제공됩니다. |
| [클라우드 서비스 SDK의 로컬 빠른 시작을 위한 AEM의 원격 디버깅](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/remote-debugging.html) | 비디오 자습서 | IDE에서 원격 Java 디버깅에 대해 알아보고 AEM에서 라이브 코드 실행을 단계별로 진행하여 정확한 실행 흐름을 파악할 수 있습니다. |
| [스마트 태그 설정](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/metadata/smart-tags-technical-video-setup.html) | 비디오 자습서 | Adobe I/O를 사용하여 Adobe Experience Manager(AEM)를 스마트 컨텐츠 서비스와 통합하기 위한 단계별 지침 |
| [문서 일괄 생성](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/interactive-communications/batch-generation-interactive-communications.html) | 문서 | 배치 API를 사용하여 템플릿에서 여러 대화형 커뮤니케이션을 생성하는 방법에 대해 알아봅니다. |
| [AEM Forms에서 인쇄 채널 문서 만들기](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/ic-print-channel-tutorial/introduction.html) | 문서 | 인쇄 채널용 대화형 통신을 만드는 데 필요한 단계를 알아봅니다. |
| [Adobe Asset Link 정보](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/launch-adobe-asset-link.html) | 비디오 자습서 | 가장 익숙한 Creative Cloud 데스크탑 앱을 종료하지 않고도 Adobe Experience Manager Assets(AEM Assets)에 저장된 컨텐츠에 액세스하는 방법에 대해 학습합니다. |
| [Asset Link 패널 개요](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/panel-overview.html) | 비디오 자습서 | Adobe Asset Link는 크리에이티브 사용자가 InDesign, Photoshop 및 Illustrator의 앱 내 패널을 사용하여 AEM Assets에 저장되어 있는 자산을 검색, 체크 아웃 및 확인할 수 있는 기능을 제공합니다. Adobe Asset Link 패널의 UI 및 기능에 대해 소개합니다. |
| [자산 검색](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/asset-search.html) | 비디오 자습서 | 크리에이티브 사용자는 키워드를 사용하여 AEM Assets에 저장된 자산을 검색하거나 특정 위치에서 검색을 수행할 수 있습니다. |
| [파일 버전 관리 및 주석](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/file-versioning-and-comments.html) | 비디오 자습서 | Adobe Asset Link 패널을 사용하면 패널 내에서 축소판, 기본 메타데이터 및 버전과 같은 AEM Assets에 대한 파일 세부 정보에 액세스할 수 있습니다. |
| [체크인 체크아웃](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/check-in-check-out.html) | 비디오 자습서 | AEM Assets를 사용하면 작업 중인 크리에이티브 앱에서 바로 AEM Assets를 확인할 수 있으며 즉시 편집을 시작할 수 있습니다. |
| [AEM Assets에 대한 렌디션만 배치하는 경우](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/for-placement-only.html) | 비디오 자습서 | AEM assets를 위한 FPO(For Placement Only) 변환을 만들고 사용하는 방법을 살펴봅니다. |
| [복사 배치](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/place-copy.html) | 비디오 자습서 | 복사 배치 작업을 사용하여 AEM Assets에서 자산을 사용하는 방법을 알아봅니다. |
| [다운로드 및 업로드](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/download-and-upload.html) | 비디오 자습서 | Asset Link 패널을 사용하여 자산 파일을 AEM Assets에서 다운로드 및 업로드하는 방법을 알아봅니다. |
| [파일 및 컬렉션](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/files-and-collections.html) | 비디오 자습서 | Asset Link 패널에서 AEM Assets 파일 및 컬렉션에 빠르고 쉽게 액세스하는 방법을 알아봅니다. |
| [다운로드](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/sharing/download.html) | 비디오 자습서 | 사용 및 공유를 위해 자산 및 해당 표현물을 로컬 시스템에 다운로드하는 방법을 학습합니다. |

### 추가 리소스

* [AEM을 클라우드 서비스로 사용](https://docs.adobe.com/content/help/ko-KR/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 학습 및 지원 홈](https://helpx.adobe.com/kr/support/experience-manager/6-5.html)
* [AEM 6.4 학습 및 지원 홈](https://helpx.adobe.com/kr/support/experience-manager/6-4.html)
* [AEM 6.3 학습 및 지원 홈](https://helpx.adobe.com/kr/support/experience-manager/6-3.html)
* [AEM 6.2 학습 및 지원 홈](https://helpx.adobe.com/kr/support/experience-manager/6-2.html)
* [Cloud Manager 사용 안내서](https://helpx.adobe.com/kr/experience-manager/cloud-manager/user-guide.html)
* [이전 버전의 AEM 설명서](https://helpx.adobe.com/kr/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic 도움말 홈](https://docs.adobe.com/content/help/ko-KR/dynamic-media-classic/using/home.html)
* [Dynamic Media 릴리스 노트](https://docs.adobe.com/content/help/ko-KR/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Livefyre 릴리스 노트](https://docs.adobe.com/content/help/ko-KR/livefyre/using/release-notes/c-rn.html)

## ![아이콘](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign은 온라인 및 오프라인 마케팅 채널 간에 직관적이고, 자동화된 방식으로 일대일 메시지를 제공합니다. 이제 고객이 습관 및 선호도에 따라 결정된 작업 환경을 통해 원하는 사항을 예측할 수 있습니다.

### 새 제품 릴리스

[Adobe Campaign Classic 20.2 릴리스](https://docs.adobe.com/content/help/ko-KR/campaign-classic/using/release-notes/latest-release.html)에는 다음이 포함되어 있습니다.

* _이모티콘 지원_ - _Azure Synapse FDA Connector_ - _새로운 개인 정보 보호 규정_
* Campaign 컨트롤 패널: [활성 프로필 모니터링](https://docs.adobe.com/content/help/ko-KR/control-panel/using/performance-monitoring/active-profiles-monitoring.html)

### 새로운 Campaign 교육 과정 및 자습서

| 컨텐츠 | 컨텐츠 유형 | 설명 |
| -----------| ---------- | ---------- |  
| [비즈니스 사용자를 위한 Adobe Campaign Standard 시작하기](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard) | 교육 과정 | 인터페이스 탐색, 전달 작업, 수신자 데이터 만들기 및 관리 방법을 알아봅니다. |
| [Adobe Campaign 클라이언트 설치 및 설정](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard) | 비디오 | Adobe Campaign 클라이언트 콘솔을 다운로드 및 설치하고, 여러 환경에 대한 연결을 만들고 관리하며, Adobe Campaign 클라이언트 콘솔에 대한 액세스를 확인하는 방법을 알아봅니다 |

### 도움말 리소스

* Adobe Campaign Standard: [도움말 센터](https://docs.adobe.com/content/help/ko-KR/campaign-standard/using/campaign-standard-home.html) - [릴리스 노트](https://docs.adobe.com/content/help/ko-KR/campaign-standard/using/release-notes/release-notes.html) - [사용 방법 비디오](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [릴리스 계획](https://docs.adobe.com/content/help/ko-KR/campaign-standard/using/release-notes/release-planning.html) [- 최신 설명서 업데이트](https://docs.adobe.com/content/help/ko-KR/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [도움말 센터](https://docs.adobe.com/content/help/en/campaign-classic/using/campaign-classic-home.html) - [릴리스 노트](https://docs.adobe.com/content/help/ko-KR/campaign-classic/using/release-notes/latest-release.html) - [사용 방법 비디오](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [최신 설명서 업데이트](https://docs.adobe.com/content/help/ko-KR/campaign-classic/using/documentation-updates.html)
* Adobe Campaign 제어판: [설명서](https://docs.adobe.com/content/help/ko-KR/control-panel/using/control-panel-home.html) - [릴리스 노트](https://docs.adobe.com/content/help/ko-KR/control-panel/using/release-notes.html) - [Campaign Standard](https://docs.adobe.com/content/help/ko-KR/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html)/[Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html) 방법 비디오

## ![아이콘](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

* [Advertising Cloud DSP의 새로운 기능](#adcloud-dsp)
* [Advertising Cloud Search의 새로운 기능](#adcloud-search)

### Advertising Cloud DSP의 새로운 기능 {#adcloud-dsp}

업데이트 날짜: **2020년 6월 23일**

| 기능 | 설명 |
| -----------| ---------- |
| 도메인 마이그레이션 | (6월 22일 릴리스) Advertising Cloud DSP가 https://www.tubemogul.com 에서 [https://advertising.adobe.com](https://advertising.adobe.com)으로 마이그레이션되었습니다. |
| Adobe Analytics 통합 | (6월 18일 릴리스) 이제 DSP는 Analytics으로 보내는 데이터에서 AMO 비용 지표를 선택적으로 표시하지 않을 수 있습니다. 지표를 표시하지 않으려면 Adobe 계정 관리자에게 문의하십시오. |
| 사용자 기반 장치 그래프 | (6월 22일 릴리스) 이제 셀프 서비스 DSP 고객은 모든 새로운 캠페인에서 사용자 기반 타깃팅 및 빈도 관리를 위해 장치 그래프(Adobe Experience Cloud Device Co-op 또는 LiveRamp)를 활용할 수 있습니다. 이렇게 하면 자신이 소유한 장치를 통해 대상에 연결하고 광고 노출을 제한할 수 있습니다. |
| CCPA 판매 중지 | (6월 22일 릴리스) 이제 [!UICONTROL 대상 > 세그먼트]에서 만들 수 있는 새로운 CCPA 판매 중지 세그먼트를 사용하여 CCPA 판매 중지 요청을 Advertising Cloud에 전달할 수 있습니다. 또한 a) [!UICONTROL 대상 > 세그먼트]에서 또는 b) Advertising Cloud Trafficking API를 사용하여 고객이 계정에 대해 판매 중지 요청을 제출한 월별 ID의 보고서를 검색할 수 있습니다. 자세한 내용은 https://docs.adobe.com/content/help/en/advertising-cloud/all/privacy/ad-cloud-ccpa-opt-out-of-sale.html 을 참조하십시오. |
| DoubleVerify 정품 브랜드 안전성 | (6월 22일 릴리스) 이제 광고주는 DoubleVerify로 입찰 후 차단 규칙을 모방하도록 포괄적인 브랜드 안전 필터를 사용하여 단일 DoubleVerify 세그먼트 ID 사전 입찰을 타깃팅할 수 있습니다. 이제 [!UICONTROL 설정 > 광고주]에서 광고주 설정의 미디어 품질 타깃팅 섹션에서 이렇게 할 수 있습니다. 서비스에 대해 자세히 알아보려면 programmaticsales@doubleverify.com으로 문의하십시오. 이 기능에 대한 추가 비용이 적용됩니다. |
| CPA/ROAS 최적화 | (5월 20일 릴리스) 더 이상 캠페인 관리자가 예산을 과다 할당하지 않도록 패키지 내에서 새 배치를 제한할 필요가 없습니다. 이제 배치는 CPM 또는 CPA/ROAS 성능에 따라 동적 예산 할당을 받습니다. |
| [!UICONTROL Campaign] Home  | (6월 3일 릴리스) 제공된 캠페인 예산과 경과 시간을 기반으로 하는 새로운 캠페인 수준 간격 지표를 사용할 수 있습니다. |
| [!UICONTROL 배치] | (6월 22일 릴리스) 배치 설정을 간소화하기 위해 사이트 다양성 및 플레이어 크기 필터가 제거되었습니다. |
| 배치 예측 | (6월 3일 릴리스) 배치 수준 최적화를 사용하는 CTV 및 비디오 배치의 경우 배치 설정에는 여러 광고 길이(15초 및 30초)에 대한 예측이 포함됩니다. 또한, VAST 및 VPAID 인벤토리에 대한 예측도 포함됩니다. |
| [!UICONTROL 인벤토리] | (6월 22일 베타 릴리스) 새로운 거래 ID 양식을 사용하면 이미 협상한 비공개 거래를 신속하게 설정할 수 있습니다. |
|  | (6월 22일 베타 릴리스) 이제 VAST 인벤토리에서 대화형 프리롤을 사용할 수 있습니다. 단일 대화형 프리롤 광고 및 배치를 설정하여 광고 및 배치 수를 줄일 수 있습니다. |
| ACTV 대상 렌즈 | (6월 18일 릴리스) 대상 렌즈를 사용하면 보조 대상 읽기를 만들고 계획, 주문 및 보고 워크플로우에 적용할 수 있습니다. 이렇게 하면 (1) 보조 대상에 대한 빠른 인사이트를 얻을 수 있고 (2) 기본 대상에서 유연한 거래가 가능하며 (3) 여러 대상의 &quot;렌즈&quot;를 통해 캠페인 실행을 측정할 수 있습니다. |

### [!UICONTROL Advertising Cloud Search]{#adcloud-search}의 새로운 기능

| 기능 | 설명 |
| -----------| ---------- |
| [!UICONTROL 캠페인] | Microsoft Advertising(이전 Bing Ads)은 2020년 9월 30일 이후 평균 위치 지표를 더 이상 사용하지 않습니다. 이를 위한 준비 사항으로 7월 11일부터 모든 제한 유형의 위치 기반 제약 조건이 무시되고 위치 기반 조건도 무시됩니다. |
| [!UICONTROL Advertising Insights] | (6월 13일 릴리스) 다음 인사이트가 제거되었습니다.<br/><br/><ul><li>대상 타겟 성과(최신 버전)</li><li>과거 성과(최신 버전)</li><li>일치 유형(최신 버전)</li><li>설정 감사(최신 버전)</li><li>포트폴리오 사전 게시(이전)</li></ul><br/>나머지 인사이트는 이전 버전이며 _Legacy_ 레이블이 이름에서 제거되었습니다. 또한, 라이브/편집 모드가 제거되었습니다. |

## ![아이콘](/assets/magento.png) [!DNL Magento] {#magento}

Magento 릴리스 노트에 대해서는 다음을 참조하십시오.

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![아이콘](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage]는 리드 관리를 위한 완전한 애플리케이션이며, 복잡한 구매 여정의 모든 단계에서 고객 경험을 전환하여 고객 경험을 혁신하고자 하는 B2B 마케터입니다.

### 핵심 Marketo Engage 업데이트

최신 릴리스 정보는 [!DNL Marketo][릴리스 노트](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720)를 참조하십시오.

### 예정된 기능

다음 기능은 분기 전체에 걸쳐 릴리스됩니다.

| 기능 | 설명 |
|------|---------|
| [!DNL Bizible] | <ul><li>새로운 계정 기반 세분화</li><li>대시보드별 필터 저장</li><li>Bizible 대시보드를 PDF로 내보내기</li></ul> |
| 영업 연결 | Compose Window 및 Command Center 업데이트/개선 사항 |

### 공지

**Marketo Engage Success Center:** 2020년 2월 출시. Success Center는 Product Docs 및 Community를 검색하고 사용 방법 가이드를 실행하고 채택률 컨텐츠에 액세스하는 등 다양한 작업을 할 수 있는 제품 내 도움말 센터입니다. 참고: 이 기능은 ANZ에서 베타 버전으로 출시되며, 해당 분기 후반에 북미에 출시될 예정입니다.

### 사용 중단

* **자산 API &quot;_method&quot; 매개 변수:** 2020년 9월 이후, 자산 API 끝점은 `_method`를 사용하여 쿼리 매개 변수를 URI 길이 제한을 무시하도록 POST 본문에 전달하지 않습니다.
* **Internet Explorer 지원 중단:** 2020년 7월 31일부터 Marketo Engage 사용자 인터페이스는 이제 Internet Explorer에서 지원되지 않습니다.

누적 릴리스 노트와 내역 릴리스 노트는 [Marketo 릴리스 노트](https://docs.marketo.com/x/CgA6Ag)를 참조하십시오.
