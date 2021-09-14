---
title: 최신 릴리스 정보
description: Experience Cloud 제품 및 서비스의 최신 릴리스 정보, 새로운 기능 및 새로운 설명서에 대해 알아봅니다. Experience Cloud, Creative Cloud for enterprise 및 Document Cloud와 관련된 새로운 도움말과 튜토리얼을 찾아보십시오.
doc-type: release notes
last-update: September 2021
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: fcba6592d43896676fff4a62d15756823c8a1b20
workflow-type: tm+mt
source-wordcount: '6343'
ht-degree: 34%

---

# Adobe Experience Cloud 릴리스 정보 - 2021년 9월

![배너](assets/experience-cloud-banner-3.png)

[!DNL Experience Cloud] 애플리케이션과 서비스는 매월 업데이트됩니다. 이 페이지는 [!DNL Experience Cloud] 및 [!DNL Experience Platform]의 최신 릴리스 업데이트, 설명서 및 튜토리얼을 찾을 수 있는 중앙 위치입니다. [!DNL Creative Cloud for Enterprise] 및 [!DNL Document Cloud]에 대한 새로운 설명서도 찾을 수 있습니다.

>[!NOTE]
>
>월별 [Adobe 우선 순위 제품 업데이트](https://www.adobe.com/kr/subscription/priority-product-update.html) 를 구독하면 이 페이지의 업데이트에 대한 이메일 알림을 받을 수 있습니다. 이 페이지는 한 달 동안 유지되므로 Adobe 엔터프라이즈 제품 및 Experience League 설명서에 대한 업데이트를 정기적으로 확인하십시오.

최신 업데이트: **2021년 9월 14일**

* [[!DNL Experience League] 라이브 이벤트](#events)
* [[!DNL Experience Cloud Central Interface Components] &amp; 관리](#ecloud)
* [Adobe [!UICONTROL 시스템 상태]](#status)
* [[!DNL Adobe Analytics]](#analytics) 및 [Customer Journey Analytics](#cust-journey)
* [[!DNL Adobe Audience Manager]](#aam) (업데이트 날짜: 2021년  **9월 14일**)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Document Cloud]](#doc-cloud)
* [[!DNL Creative Cloud for enterprise]](#creative-cloud)

도움이 필요하십니까? [Adobe Experience League](https://experienceleague.adobe.com/?lang=ko-KR/#home) 에서 제품 및 기술 문서, Adobe에서 제공하는 교육 과정, 비디오 튜토리얼, 빠른 답변, 커뮤니티 통찰력 및 강사 중심의 트레이닝을 확인할 수 있습니다.

## ![](/assets/experience-league.png) [!DNL Experience League] IconLive 이벤트 {#events}

[!DNL Experience League] Live Events는 Adobe 기술을 제공하는 데 유용한 Adobe 전문가 및 특별 게스트와 논의하고 있습니다. 다음 일정을 참조하여 라이브 또는 이전에 기록된 이벤트를 시청하십시오.

| 이벤트 날짜 | 이벤트 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2021년 9월 23일 | [휴일 캠페인을 돋보이게 하는 전문가 팁](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw) | 라이브 비디오 이벤트 | 휴일 쇼핑을 시작하기에 결코 이른 적이 없는 것처럼, 난폭하게 성공적인 휴일 마케팅 캠페인을 계획하는 것은 결코 이른 일이 아니다. Adobe Campaign을 사용하면 조직의 휴일 계획을 모두 실현하는 캠페인을 디자인, 계획 및 실행할 수 있습니다.<br>하지만 여러분은 한 해를 완전히 마칠 캠페인을 실행하는 모든 팁을 알고 있나요? 이 라이브 토론에는 몇 십억의 전문 지식을 가진 세 명의 Adobe 전문가들이 나와 있습니다. [세부 사항...](https://www.youtube.com/watch?v=bsU1lAv0xes) |
| 2021년 8월 26일 | [다음 대상 세그먼트를 더 똑똑하게 만들기](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-02.html?lang=en) | 이벤트 기록 | 모든 훌륭한 마케팅 캠페인의 성공은 고객을 정확하게 타겟팅하는 데 달려 있습니다. 새로운 Adobe Experience Platform [!UICONTROL 세그먼트 빌더]를 사용하면 여러 채널에서 프로필 데이터와 시간 기반 사용자 행동을 사용하여 다음 대상 세그먼트를 작성할 수 있습니다. 메시지를 가장 많이 들어야 하는 사람에게 메시지를 보낼 수 있는 더 나은 방법은 없습니다. |
| 2021년 7월 29일 | [즐겨찾는 세 가지 Adobe Analytics 구현 팁](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-01.html?lang=en) | 이벤트 기록 | Summit에서 무대 위에 있는 그를 봤잖아요. Adobe 인사이더 투어에서 그가 전문가의 조언을 공유한다고 들었는데요. Adobe Analytics 구현에서 그와 함께 작업할 수 있다는 이점이 있을 것입니다. 이제 Eric Matisof가 가장 좋아하는 세 가지 Adobe Analytics 구현 팁을 이 독점 Experience League Live 토론에 제공합니다. |

{style=&quot;table-layout:auto&quot;}

자세한 비디오는 YouTube의 [Adobe Experience League 채널](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw)을 참조하십시오.

## ![아이콘](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components]  및 관리 {#ecloud}

이번 달에는 업데이트하지 않았습니다. 업데이트를 자주 확인하십시오.

**관리  [!DNL Experience Cloud Central UI Components] 및 관리에 대한 추가 도움말 리소스**

* [중앙 인터페이스 구성 요소](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=ko-KR) 및 사용자 관리에 대한 관리 도움말
* [장소 - 위치 서비스](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=ko-KR)에 대한 도움말 및 릴리스 정보
* [인물 - 고객 속성 및 대상 라이브러리](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=ko-KR)에 대한 도움말.

## ![아이콘](/assets/adobe.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] Adobe 제품 및 서비스 중단, 중단 및 유지 관리 이벤트에 대한 자세한 정보, 상태 업데이트 및 이메일 알림을 제공합니다. [status.adobe.com](https://status.adobe.com/)에서 관련 정보를 확인하십시오.

([2020년 5월 21일](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=ko-KR) 릴리스 노트에서 [!DNL Adobe System Status]에 대한 최신 릴리스 정보를 확인하십시오.)

## ![아이콘](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

릴리스 날짜: **2021년 15월 9일**

* [Adobe Analytics의 새로운 기능](#aa-features)
* [Customer Journey Analytics의 새로운 기능](#cust-journey)
* [Adobe Analytics의 수정 사항](#aa-fixes)
* [Analytics 관리자에 대한 중요 공지](#aa-notices)
* [Analytics 교육 과정 및 튜토리얼](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics의 새로운 기능 {#aa-features}

| 기능 | 설명 | [일반 가용성](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=en) - 대상 날짜 |
| ----------- | ---------- | ------- |
| 이번 달에는 새로운 기능 없음 | N/A |

{style=&quot;table-layout:auto&quot;}

### Customer Journey Analytics의 새로운 기능 {#cust-journey}

| 기능 | 설명 | [일반 가용성](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=en) - 대상 날짜 |
| ----------- | ---------- | ----- |
| 지표 중복 제거 | 이제 Customer Journey Analytics(CJA)에서 지표의 인스턴스를 중복 제거할 수 있습니다. 동일한 값이 열(자신 또는 다른 열)에 표시되면 지표가 증가하지 않도록 할 수 있습니다. 중복 제거는 주요 지표를 과다 카운트하지 않도록 하고 데이터에 대한 신뢰도를 높입니다. | 2021년 9월 16일 |
| 보고를 위한 일광 절약 시간 지원 | CJA의 모든 데이터는 UTC에 저장됩니다(특정 시간대가 아님). [!UICONTROL 이제 ] CJA에서 데이터 보기를 사용하면 일광 절약 시간을 기반으로 1시간 증가 또는 감소를 고려하여 데이터를 이동할 수 있습니다. | 2021년 9월 16일 |
| [!UICONTROL 사용자 지정 달력] | 데이터 보기에 대해 다른 달력 유형(예: [!UICONTROL 소매 4-4-5])을 선택할 수 있도록 해줍니다. 동일한 연결을 기반으로 여러 데이터 보기를 만들어 동일한 데이터를 다른 달력 형식으로 볼 수 있습니다. | 2021년 9월 16일 |
| 부울 필드 지원 | 이제 CJA에서 부울 필드를 지원합니다. | 2021년 9월 16일 |
| 새 [!UICONTROL 연결] 정보 경험 | 이 [!UICONTROL 연결] UI 개선 사항을 통해 데이터를 보고에 사용할 준비가 되었는지 여부와 시기를 알 수 있습니다. 데이터 처리와 관련된 문제를 추적할 수도 있습니다. [자세히 알아보기](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-connections/manage-connections.html?lang=ko-KR) | 2021년 9월 20일 |

{style=&quot;table-layout:auto&quot;}

### Adobe Analytics의 수정 사항 및 CJA {#aa-fixes}

* 새로 Analytics 프로비저닝 회사에 있는 관리자가 첫 번째 보고서 세트를 만들 수 없는 문제를 해결했습니다. (AN-265842, AN-269752)
* 데이터 피드가 배달되지 않는 문제가 해결되었습니다. (AN-268758, AN-268737, AN-268568, AN-268759, AN-264728)
* [!DNL Target] UI의 [!UICONTROL A4T] 보고서에서 향상도와 신뢰도를 계산하지 않는 문제를 해결했습니다. (AN-264841)
* AppMeasurement 라이브러리가 iOS 장치에서 인앱 브라우저에 로드되지 않는 문제를 해결했습니다. (AN-247942)
* 보고서 세트 설정에 Activity Map 설정이 표시되지 않는 문제를 해결했습니다. (AN-267243)
* (CJA) 이제 CJA가 보고에서 통화 코드 대신 통화 기호를 사용하는 문제가 수정되었습니다.(AN-268881)

#### Adobe Analytics의 추가 수정 사항

-224899; AN-239753; AN-256295; AN-262122; AN-262449; AN-263969; AN-264665; AN-265223; AN-265260; AN-265519; AN-265579; AN-; AN-266199; AN-266354; AN-266968; AN-267564; AN-267624; AN-267711; AN-267781; AN-268170; AN-268267; AN-268334; AN-268402; AN-268551; AN-268675; AN-269000; AN-269050; AN-269059; AN-269305; AN-269531

### [!DNL Analytics] 관리자에 대한 중요 공지 {#aa-notices}

| 공지 | 추가 또는 업데이트 날짜 | 설명 |
| ----------- | ---------- | ---------- |
| Adobe [!UICONTROL Data Connectors] 의 EOL | 2020년 8월 3일 | Adobe [!UICONTROL Data Connectors] 는 더 이상 실행 불가능하거나 지원되지 않는 레거시 기술을 기반으로 합니다. [Adobe Exchange Partner Program](https://partners.adobe.com/exchangeprogram/experiencecloud)에서 새로운 표준을 사용할 수 있습니다. 이 표준을 사용하여 모든 통합이 지속적으로 제공되고 지원될 수 있습니다. 공식적인 서비스 종료 날짜는 **2021년 8월 19일**&#x200B;입니다. [자세히 알아보기...](https://experienceleague.adobe.com/docs/analytics/import/dataconnectors/data-connectors-eol.html?lang=ko-KR) |
| 전체 프로세싱[!UICONTROL  데이터 소스] 서비스 중단 | 2021년 4월 12일 | Adobe는 **2021년 7월 31일**&#x200B;에 전체 처리 데이터 소스에 대한 사용을 중단합니다. 2021년 3월 25일부터 이 유형의 새로운 가져오기는 더 이상 생성되지 않습니다. 이 유형의 데이터를 가져오려면 [Bulk Data Insertion API](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) 를 사용해 주십시오. |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

AppMeasurement 릴리스(버전 2.22.2)에 대한 최신 업데이트는 [JavaScript용 AppMeasurement 릴리스 정보](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=en)를 참조하십시오.

### 새로운 Analytics 교육 과정 및 튜토리얼 {#tutorials-analytics}

[!DNL Analytics] 및 [!UICONTROL Customer Journey Analytics]의 새 교육 과정, 튜토리얼 및 기사입니다.

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2021년 9월 | [Adobe Analytics의 기본 지표](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/foundational-metrics-in-adobe-analytics.html) | 비디오 | Adobe Analytics의 기본 방문자 지표와 이러한 지표가 어떻게 상호 관련되는지를 개념적으로 설명합니다. 보고에서 [!UICONTROL 페이지 보기 횟수], [!UICONTROL 방문 횟수] 및 [!UICONTROL 고유 방문자]를 사용해야 할 경우에 대한 몇 가지 사용 사례를 알아봅니다. |
| 2021년 9월 | [[!UICONTROL 테이블 및 시각화 데이터 소스 설정]](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/table-and-visualization-data-source-settings.html?lang=en) | 비디오 | 설정을 통해 표와 시각화가 어떻게 함께 연결되어 있는지 확인하고, 다양한 분석 사용 사례에 대해 이러한 설정을 구성하는 방법을 알아봅니다. |
| 2021년 9월 | [SFTP를 통해 Data Warehouse 요청 전송](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/data-warehouse/send-data-warehouse-request-via-sftp.html?lang=en) | 비디오 | SFTP를 통해 [!UICONTROL Data Warehouse] 요청을 보내는 방법을 알아봅니다. [!UICONTROL Data ] Warehouse는 데이터를 필터링하여 실행할 수 있는 저장소 및 사용자 지정 보고서에 대한 Analytics 데이터 사본을 참조합니다. 고유한 질문에 따라 원시 데이터의 고급 데이터 관계를 표시하도록 보고서를 요청할 수 있습니다. |
| 2021년 9월 | [로그인 문제를 방지하기 위해 연결된 IMS ID 확인](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/user-management/check-linked-ims-id-to-prevent-login-issues.html?lang=en) | 비디오 | Adobe Analytics에서 잘못된 IMS ID나 연결된 ID가 누락되면 사용자에 대한 로그인 문제가 발생할 수 있습니다. 사용자는 연결된 IMS ID를 직접 확인하고 문제가 발생하면 고객 지원에 연락하여 일반적인 문제 해결 단계를 수행하는 번거로운 작업을 줄일 수 있습니다. |
| 2021년 9월 | [데이터 피드 작업 다시 실행](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/data-feeds/rerun-a-data-feed-job.html?lang=en) | 비디오 | Adobe Analytics의 [!UICONTROL 데이터 피드] UI를 사용하면 데이터 피드 관리가 훨씬 쉬워집니다. 데이터 피드를 관리할 수 있는 액세스 권한이 있는 경우 고객 지원 팀에서 최근 데이터 피드 파일을 다시 보내지 않고 데이터 피드 인터페이스를 사용하여 직접 데이터 피드 작업을 다시 실행할 수 있습니다. |
| 2021년 9월 | [데이터 피드 ID 찾기](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/data-feeds/find-your-data-feed-id.html?lang=en) | 비디오 | 데이터 피드 배달에 실패했거나 데이터 피드 파일 재전송을 요청하는 경우 Adobe에 문의해야 하는 경우가 있습니다. 고객이 [!UICONTROL 데이터 피드] ID를 제공하는 경우 고객 지원 팀이 이러한 요청을 처리하는 것이 편리해집니다. |
| 2021년 9월 | [사용 가능한 계정 기능 보기](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/company-settings/view-your-accounts-available-features.html?lang=en) | 비디오 | [!DNL Analytics]의 [!UICONTROL Admin] 섹션 아래에 있는 [!UICONTROL 기능 액세스 수준] 설정을 보면 [!DNL Analytics] 패키지 및 회사에 부여된 기능에 대한 액세스 수준을 볼 수 있습니다. 이 보기는 Activity Map, Advertising Analytics, 경고의 예외 항목 탐지 등에 사용할 수 있습니다. |
| 2021년 9월 | [다가오는 트래픽 스파이크 관리](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/traffic-management/manage-an-upcoming-traffic-spike.html?lang=en) | 비디오 | Adobe은 트래픽이 높은 이벤트가 성공했는지 확인하기 위해 클라이언트와 파트너 관계를 맺으려고 합니다. 트래픽 스파이크 예약은 해당 파트너 프로세스의 시작점입니다. [!UICONTROL 스파이크 예약] 섹션에서는 임시 트래픽 스파이크에 대한 Adobe에 경고를 표시하여 해당 리소스를 처리하도록 할당할 수 있습니다. |
| 2021년 9월 | [이메일 도메인 제한 적용 - 기술 비디오](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/company-settings/enforce-email-domain-restrictions.html?lang=en) | 비디오 | [!UICONTROL 보안 관리자]를 사용하면 보고 데이터에 대한 액세스를 제어할 수 있습니다. 강력한 암호, 암호 만료일, IP 로그인 제한 및 이메일 도메인 제한 옵션이 제공됩니다. [!UICONTROL 이메일 도메인 제한 ] 적용 은 Analytics가 책갈피, 다운로드 가능한 보고서 및 경고를 보내는 이메일 주소 및 도메인을 필터링합니다. 이메일 필터 목록은 최대 100개의 항목을 지원하며, 각 항목은 이메일 주소 또는 전체 이메일 도메인일 수 있습니다. |
| 2021년 9월 | [사용자 에셋을 다른 사용자에게 전송](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/user-management/transfer-user-assets-to-a-different-user.html?lang=en) | 비디오 | [!UICONTROL 사용자 관리] 페이지에서는 사용자와 그룹을 관리하고 보고서, 도구 및 보고서 세트에 대한 액세스 권한을 제어할 수 있습니다. 대시보드, 달력 이벤트 및 책갈피와 같은 사용자 계정 항목을 Adobe Analytics의 [!UICONTROL 사용자 관리]를 통해 다른 사용자 계정에 할당할 수 있습니다. |
| 2021년 9월 | [[!UICONTROL Analytics에서 보트 규칙 구성]](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-bot-rules-in-analytics.html?lang=en) | 비디오 | [!UICONTROL 보트 규칙을 사용하면 알려진 스파이더 및 보트에서 생성한 트래픽을 보고서 세트에서 제거할 수 있습니다. ] 보트 트래픽을 제거하면 웹 사이트에서 사용자 활동을 보다 정확하게 측정할 수 있습니다. 보트 규칙이 정의되면 들어오는 모든 트래픽이 정의된 규칙과 비교됩니다. 이러한 규칙 중 하나와 일치하는 트래픽은 보고서 세트에서 수집되지 않고 트래픽 지표에 포함되지 않습니다. |
| 2021년 9월 | [Analytics 관리 로그 개요](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/logs/overview-of-analytics-admin-logs.html?lang=en) | 비디오 | 로그 파일은 사용자가 로그인하는 시점, 사용자의 사용, 액세스, 보고서 세트 및 관리 변경을 확인하는 데 도움이 됩니다. 관리자 로그는 관리자가 [!UICONTROL 관리 도구]에서 수행한 모든 변경 사항을 보고합니다. 로그는 세 로그 중 하나에서 사용자 정의 보고서에 대한 게이트웨이를 제공합니다. |
| 2021년 9월 | [Analysis Workspace 성능 지표 보기](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/view-analysis-workspace-performance-metrics.html?lang=en) | 비디오 | 다양한 요소가 Analysis Workspace 내에 있는 프로젝트의 성능에 영향을 줄 수 있습니다. [!UICONTROL 성능] 옵션을 사용하면 네트워크, 브라우저, 프로젝트 요소 등 프로젝트의 성능에 영향을 주는 요소를 볼 수 있습니다. |
| 2021년 9월 | [타임스탬프 옵션 설정 활성화](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/enable-the-timestamp-optional-setting.html?lang=en) | 비디오 | [!UICONTROL 타임스탬프 ] 옵션을 사용하면 타임스탬프가 지정된 데이터와 지정되지 않은 데이터를 동일한 글로벌 보고서 세트에서 혼합할 수 있습니다. 보고서 세트를 만들지 않고 오프라인 추적을 사용하도록 모바일 앱에서 전역 보고서 세트로 타임스탬프가 지정된 데이터를 보내고 앱을 업그레이드할 수 있습니다. |
| 2021년 9월 | [데이터 피드 인증 키 다운로드](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/data-feeds/download-the-data-feed-authentication-key.html?lang=en) | 비디오 | 데이터 피드를 만들면 Adobe에서 원시 데이터 파일을 보낼 위치와 각 파일에 포함할 내용을 알 수 있습니다. 데이터 피드에 대한 SFTP 지원은 Analytics에서 사용할 수 있습니다. 유효한 RSA 또는 DSA 공개 키를 포함하려면 SFTP 호스트, 사용자 이름 및 대상 사이트가 필요합니다. 피드를 만들 때 적절한 공개 키를 다운로드할 수 있습니다. |
| 2021년 9월 | [시각화 범례 맞춤화](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/customize-visualization-legends.html?lang=en) | 비디오 | 시각화에서 범례 사용자 지정(시리즈 레이블 편집이라고도 함)은 보고서를 보는 모든 사람이 시각화를 보다 쉽게 이해할 수 있도록 하는 좋은 방법입니다. |
| 2021년 9월 | [Analysis Workspace의 Dimension-그래프 라이브 연결](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/dimension-graph-live-linking.html?lang=en) | 비디오 | 우리는 이것을 뭐라고 불러야 할지 잘 모르지만, 멋져요! 이제 차원 값에서 선 그래프를 생성할 때 다른 차원 값을 선택하고 그래프를 동적으로 변경할 수 있습니다. 자세한 내용은 비디오를 참조하십시오. |

{style=&quot;table-layout:auto&quot;}

### Analytics 도움말 리소스

* [Adobe Analytics 제품 설명서 및 튜토리얼](https://experienceleague.adobe.com/docs/analytics.html)

## ![아이콘](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager의 새로운 기능 - 업데이트됨 **2021년 9월 14일**:

| 기능 | 설명 |
| ------- | ------- |
| 모바일 ID 데이터 수집 동의 | 모바일 ID 데이터 수집 동의에 대한 지원을 추가했습니다. 이 업데이트를 활용하려면 고객이 [AEP Mobile SDK iOS Core 2.8.0](https://aep-sdks.gitbook.io/docs/foundation-extensions/mobile-core/mobile-core-release-notes#november-4-2020) 이상으로 업그레이드해야 합니다. |

## ![아이콘](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

릴리스 업데이트 정보와 Experience Platform 및 플랫폼 서비스([!UICONTROL Journey Orchestration], [!UICONTROL Offer decisioning] 및 [!UICONTROL Mobile SDK])에 대한 새 설명서를 포함합니다.

**2021년 8월 25일** Experience Platform의 기존 기능에 대한 업데이트는 다음과 같습니다.

* **[!UICONTROL 대상]:** 대상, 세그먼트  를 기존 대상에 원활하게 활성화할 수 있는 마케터의 유용성 개선 사항.
* **[!UICONTROL 가시성 통찰력]:**  이제 Platform에서 실행되는 워크플로우와 관련된 중요한 경고를 구독할 수 있습니다.
* **[!UICONTROL 실시간 고객 프로필]:** 이제 Experience Platform에서 프로필을 검색할 때 병합 정책별로 검색하여 선택한 병합 정책을 기반으로 20개의 샘플 프로필을 미리 볼 수 있습니다.
* **[!UICONTROL 소스]:** 파일 수집 카테고리의 이름이 로컬 시스템으로 변경되었으므로 로컬 파일 업로드 커넥터를 사용하여 로컬 파일을 Platform으로 직접 가져올 수 있습니다.

자세한 내용은 [Experience Platform 릴리스 노트](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=ko-KR)를 참조하십시오.

### Experience Platform 튜토리얼 및 교육 과정 {#tutorials-platform}

Experience Platform 및 서비스를 위해 게시된 새로운 비디오, 튜토리얼 또는 교육 과정

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2021년 9월 | [[!UICONTROL 경고]](https://experienceleague.adobe.com/docs/platform-learn/tutorials/admin/use-alerts.html) | 비디오 | Adobe Experience Platform에서 경고를 구독하고 관리하는 방법을 알아봅니다.  경고: 다양한 프로세스를 모니터링하여 플랫폼 구현이 원활하게 실행되고 있는지 확인합니다. |
| 2021년 9월 | [제품 프로필](https://experienceleague.adobe.com/docs/platform-learn/tutorials/admin/managing-product-profiles.html) | 비디오 | 제품 프로필을 만들고 사용자, 개발자, 관리자 및 권한을 할당하는 방법을 알아보십시오. |
| 2021년 9월 | [ [!UICONTROL Admin Console 소개]](https://experienceleague.adobe.com/docs/platform-learn/tutorials/admin/admin-console.html) | 비디오 | Experience Platform에 대한 액세스 제어 계층 워크플로우에 대한 개요 |

{style=&quot;table-layout:auto&quot;}

### Journey Orchestration {#journey-orch}

Journey Orchestration에 대한 기능, 수정 내용 및 새로운 도움말 컨텐츠입니다.

**2021년 8월**

* **동적 헤더:**  이제 HTTP 헤더 매개 변수로 동적 데이터를 전달할 수 있습니다. 이러한 매개 변수는 타임스탬프 또는 추적 ID와 같이 여정 작업 HTTP 호출을 받는 통합 시스템에서 사용할 수 있습니다. [자세히 보기...](https://experienceleague.adobe.com/docs/journeys/using/action-journeys/action-third-party/url-configuration.html?lang=en)
* **동적 URL 경로:**  이제 사용자 지정 작업에 대한 동적 URL 경로를 설정할 수 있습니다. [자세히 보기...](https://experienceleague.adobe.com/docs/journeys/using/action-journeys/action-third-party/url-configuration.html?lang=en)

자세한 내용은 [Journey Orchestration 릴리스 노트](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=ko-KR)를 참조하십시오.

#### 새로운 Journey Orchestration 튜토리얼 및 교육 과정 {#tutorials-ajo}

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2021년 8월 | [여정 작성 소개](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-journeys/introduction-to-building-a-journey.html) | 비디오 | 여정 캔버스에서 여정을 작성하는 기본적인 방법을 이해합니다. |
| 2021년 8월 | [고객 프로필 데이터 설정 - 개요](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/data-configuration/set-up-data-overview.html) | 비디오 | Journey Optimizer용 고객 프로필 데이터를 설정하는 데 필요한 실시간 고객 프로필 데이터 및 단계에 대해 알아봅니다. |
| 2021년 8월 | [맵 ID](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/data-configuration/map-identities.html) | 비디오 | 스키마 필드에 ID 레이블을 지정하는 방법과 적절한 시점, 네임스페이스를 만드는 방법, 특정 ID를 기본 ID로 만들어야 할 시점, ID 데이터를 수집 및 확인하는 방법을 알아봅니다. |
| 2021년 8월 | [사용 사례 - 버스트 메시지](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-journeys/use-case-burst-message.html) | 비디오 | 버스트 메시지에 적용할 수 있는 사용 사례를 이해합니다. 버스트 메시지에 대한 여정을 구성하는 방법 및 적용할 모범 사례를 알아봅니다. |

{style=&quot;table-layout:auto&quot;}

#### Journey Orchestration을 위한 추가 리소스

[도움말 센터](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html)  -  [릴리스 정보](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html)  -  [방법 비디오](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=ko)  -  [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html)

### [!UICONTROL Offer Decisioning] {#offer-decisioning}

**표시 흐름:** 오퍼를 만들 때 표현을 추가하고 구성하는 방법이 개선된 사용자 경험을 위해 업데이트되었습니다

* 자세한 내용은 [[!UICONTROL Offer decisioning] 릴리스 노트](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html)를 참조하십시오.

#### [!UICONTROL Offer decisioning]에 대한 추가 리소스

[도움말 센터](https://experienceleague.adobe.com/docs/offer-decisioning/using/offer-decisioning-home.html?lang=ko)  -  [릴리스 정보](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html#new)  -  [방법 비디오](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=ko)  -  [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/documentation-updates.html)

### Adobe 모바일 SDK

Adobe Experience Platform Mobile SDK에 대한 [릴리스 노트 및 변경 로그](https://aep-sdks.gitbook.io/docs/release-notes)를 참조하십시오.

## ![아이콘](/assets/experience_platform_appicon_24.png) Journey Optimizer {#journey-opt}

**2021년 8월** Journey Optimizer 업데이트에는 다음이 포함됩니다.

| 기능 | 설명 |
| -----------| ---------- |
| [!UICONTROL 전송 시간 최적화] | Adobe Journey Optimizer을 사용하는 모든 고객을 위해 최적의 시간에 푸시 또는 이메일을 자동으로 전송합니다. |
| 스키마 관계 활용 | 이제 비즈니스 이벤트를 구성할 때 스키마 간의 관계를 활용할 수 있습니다. |
| [!UICONTROL 다시 시도 기간] | 이제 사전 설정별로 다시 시도 기간을 정의하여 더 이상 필요하지 않은 경우 다시 시도 시도가 더 이상 수행되지 않도록 할 수 있습니다. |
| [!UICONTROL 제외 목록] | 이제 사용자 인터페이스에서 CSV 파일 업로드를 통해 벌크 모드로 전자 메일 주소 및 도메인을 하나씩 제외 목록에 추가할 수 있습니다. |

자세한 내용은 [Journey Optimizer 릴리스 노트](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html)를 참조하십시오.

### Journey Optimizer를 위한 추가 리소스

[도움말 센터](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html)  -  [릴리스 정보](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html)  -  [방법 비디오](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html)

## ![아이콘](/assets/aem.png) Experience Manager {#aem}

Adobe는 릴리스 정보를 최신 상태로 유지하기 위해 [Experience Manager 릴리스 업데이트 및 로드맵](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html) 페이지를 방문할 것을 권장합니다.

### Experience Manager 제품 릴리스

* **[!DNL Experience Manager as a Cloud Service]**

   Experience Manager as a Cloud Service의 새로운 기능은 무엇입니까?

   추가된 기능의 요약이 필요하면 [2021년 8월 릴리스 개요](https://video.tv.adobe.com/v/336277) 비디오를 재생하십시오.

   * **[!DNL Experience Manager Assets as a Cloud Service]**

      _새로운 기능_

      * 디지털 자산을 링크로 공유할 때 URL을 클립보드에 바로 복사할 수 있습니다. 개선 사항을 통해 자산을 빠르고 쉽게 공유할 수 있습니다.
      * TXT 파일을 업로드하면 자산 마이크로서비스가 자동으로 축소판을 생성합니다. PNG 축소판은 사용자가 파일을 열지 않고 일정하게 내용이나 파일을 식별하는 데 도움이 되는 TXT 파일의 표현입니다. 이 기능은 구성이 필요하지 않으며 기본적으로 작동합니다.

      _Experience Manager 자산 사전 릴리스 채널의 새로운 기능_

      * 이제 검색 결과에 표시된 자산을 [!UICONTROL 열] 보기 및 [!UICONTROL 카드] 보기에서 정렬할 수 있습니다. 정렬은 **[!UICONTROL 이름]**, **[!UICONTROL 작성됨]**, **[!UICONTROL 수정됨]** 또는 **[!UICONTROL 없음]** 열에서 작동합니다.
   * **Experience Manager Forms as a Cloud Service**

      _새로운 기능_

      * [!UICONTROL 이제 ] 용 Experience Manager Archetypeproject [!DNL AEM Forms as a Cloud Service] 에 Microsoft® Dynamics 및 Salesforce.com용  [양식 데이터 모델이 포함되어 있습니다](https://experienceleague.adobe.com/docs/experience-manager-forms-cloud-service/forms/setup-environment/setup-local-development-environment.html?lang=en#forms-cloud-service-local-development-environment).
      * Acroform 기반 레코드 문서: [!DNL AEM Forms as a Cloud Service]에서는 XFA 기반 양식 템플릿 외에 [Adobe Acrobat 양식 PDF(Acroform PDF)](https://experienceleague.adobe.com/docs/experience-manager-forms-cloud-service/forms/create-an-adaptive-form/generate-document-of-record-for-non-xfa-based-adaptive-forms.html?lang=en)레코드 문서]에 대한 템플릿으로 사용할 수 있습니다.[!UICONTROL 
      * Microsoft® Azure 데이터 저장소 커넥터: 이제 [양식 데이터 모델을 Microsoft® Azure Storage](https://experienceleague.adobe.com/docs/experience-manager-forms-cloud-service/forms/use-form-data-model/configure-azure-storage.html?lang=en)에 연결할 수 있습니다. 이 기능을 사용하면 적응형 양식 데이터를 Microsoft® Azure Storage에 BLOB으로 검색하고 저장할 수 있습니다.

      _Forms의 베타 기능_

      * [!UICONTROL 통합 스토리지 커넥터]. [!UICONTROL Unified Storage Connector]를 사용하여 고객 관리 리포지토리에서 처리 중인 데이터를 외부화합니다. 예를 들어 다음 작업을 수행할 수 있습니다.
         * [!UICONTROL Forms Portal] 저장 및 재개 기능을 활성화하고 고객 관리 데이터 저장소에 적응형 양식 초안을 저장합니다.
         * 고객 관리 저장소에 중요한 개인 데이터(SPD)가 포함된 인프로세스 Experience Manager [!UICONTROL 워크플로우] 데이터(Experience Manager [!UICONTROL 워크플로우 변수] 데이터)를 저장합니다.
      * [!DNL AEM Forms as a Cloud Service] - 통신. [Communication ](https://experienceleague.adobe.com/docs/experience-manager-forms-cloud-service/forms/aem-forms-cloud-service-communications.html?lang=en) APIshelp에서는 XDP 템플릿과 XML 데이터를 결합하여 다양한 형식으로 인쇄 문서를 생성합니다. 이 서비스를 사용하면 동기화 모드에서 문서를 생성할 수 있습니다. API를 사용하면 다음을 수행하는 데 도움이 되는 애플리케이션을 만들 수 있습니다.
         * XML 데이터로 템플릿 파일을 채워 문서를 생성합니다.
         * 비대화형 PDF 인쇄 스트림을 포함하여 다양한 형식의 출력 양식을 생성합니다.
         * XFA 양식 PDF 및 Adobe Acrobat Form에서 인쇄 PDF 파일을 생성합니다.

         Beta 프로그램에 등록하려면 [formscsbeta@adobe.com](mailto:formscsbeta@adobe.com)에 문의하십시오.
      _Forms 사전 릴리스 채널에서 사용할 수 있는 새로운 기능_

      * [!UICONTROL 적응형 양식]에서 Adobe Sign 역할을 사용하십시오. 비즈니스 및 엔터프라이즈 서비스 수준용 Adobe Sign은 선택적으로 [!UICONTROL 계약] 수신자의 역할을 확장하여 워크플로우 요구 사항에 더 잘 맞게 [!UICONTROL 서명자] 이외의 역할을 확장합니다. 이제 [계약의 각 수신자가 적응형 양식](https://experienceleague.adobe.com/docs/experience-manager-forms-cloud-service/forms/create-an-adaptive-form/use-adobe-sign/working-with-adobe-sign.html?lang=en#addsignerstoanadaptiveform)에서 자신의 역할을 구성할 수 있도록 설정하고, [!UICONTROL 서명자]가 기본 역할일 수 있습니다.
      * [!UICONTROL 응용 Forms용 Analytics]. 이제 Adobe [!UICONTROL Analytics for Adaptive Forms]을 통해 최종 사용자 동작을 캡처하고 추적하여 최종 사용자 통찰력을 수집할 수 있습니다. 최종 사용자 경험을 향상시키기 위해 데이터를 기반으로 현명한 결정을 내릴 수 있습니다.
      * AEM Forms을 Microsoft® Dynamics 및 [Salesforce.com](https://www.salesforce.com/?bc=DF)과 쉽게 연결할 수 있습니다. 이 서비스는 기본 데이터 소스 구성을 제공합니다. 또한 Microsoft® Dynamics 및 Salesforce.com용 데이터 모델을 제공하므로 개발자가 적응형 양식](https://experienceleague.adobe.com/docs/experience-manager-forms-cloud-service/forms/use-form-data-model/configure-msdynamics-salesforce.html?lang=en)에 대한 데이터 소스로 Microsoft® Dynamics 및 Salesforce.com을 보다 빠르고 쉽게 구성할 수 있습니다.[
   * **[!DNL Experience Manager Screens as a Cloud Service]**

      _새로운 기능_

      * [!DNL Experience Manager Screens as a Cloud Service] 이제에서 기본 재생 모니터링을 지원합니다. 이제 플레이어는 각 ping이 있는 다양한 재생 지표를 보고합니다(기본값 30초). 이 지표를 기반으로 다양한 에지 사례(멈춤 경험, 빈 화면, 예약 문제 등)를 감지할 수 있습니다. 이 기능을 사용하면 팀이 플레이어가 컨텐츠를 제대로 재생하는지 원격으로 모니터링할 수 있습니다. 또한 필드의 빈 화면이나 손상된 경험에 대한 반응성을 개선하며 최종 사용자에게 손상된 경험을 표시하는 위험을 감소시킵니다.
[기본 재생 모니터링](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/screens-as-cloud-service/manage-player-registration/installing-screens-cloud-player.html?lang=en#playback-monitoring)을 참조하십시오.
      * 의 비디오에 대한 축소판 지원은 이제 [!DNL Experience Manager Screens as a Cloud Service]에서 지원됩니다. 컨텐츠 작성자는 이미지가 자리 표시자로 사용될 수 있도록 비디오의 축소판을 정의할 수 있습니다. 적절한 팀이 실제 비디오를 마무리하는 동안 컨텐츠 재생 및 타깃팅을 제대로 테스트할 수 있습니다. 비디오를 재생하지 못할 경우에 이미지를 사용할 수도 있습니다.
[비디오에 대한 축소판 지원](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/screens-as-cloud-service/core-product-features/thumbnail-support-videos.html?lang=en)을 참조하십시오.
   * **[!DNL Cloud Manager]**

      _새로운 기능_

      * 이제 [!DNL Experience Manager Project Archetype used by Cloud Manager] 버전이 버전 30으로 업데이트되었습니다.
      * 이제 [!DNL Cloud Manager] 랜딩 페이지의 프로그램 카드 및 관련 경험이 새로 고침됩니다.
      * 이제 [!UICONTROL 코드 품질 단계 로그]에 OakPal 검색 프로세스에 대한 자세한 로깅 정보가 포함됩니다.
      * 이제 [!UICONTROL 활동] 페이지 메뉴 옵션에는 완료된 코드 생성기 실행을 위해 **[!UICONTROL 로그 다운로드]**&#x200B;에 대한 옵션이 포함됩니다. 이 옵션을 선택하면 빌드 단계의 로그가 다운로드됩니다.
      * 이제 [!UICONTROL Program] 카드를 선택하면 [!UICONTROL Cloud Manager 개요] 페이지로 이동합니다.
      * 이제 Cloud Service 고객은 [!DNL Cloud Manager]에서 SLA(서비스 수준 계약) 보고서를 볼 수 있습니다. 이 기능은 다음 몇 개월 동안 점진적으로 제공됩니다.
[SLA 보고](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/sla-reporting.html?lang=en)를 참조하십시오.
      * `IndexType` 및 `IndexDamAssetLucene` 품질 규칙의 유형과 심각도가 변경되었습니다. 이제 이러한 규칙은 둘 다 Blocker 심각성의 버그입니다.
      * 비동기 및 Tika 구성을 다루는 새로운 Oak 색인 품질 규칙이 도입되었습니다.
      * 프로그램당 최대 SSL 인증서를 50개로 늘립니다.
      * 사용자가 [!DNL Cloud Manager] UI를 통해 여러 리포지토리를 생성 및 관리할 수 있는 셀프 서비스 기능입니다.
      * SonarQube가 불필요하게 GIT 내역 데이터를 읽고 있었습니다. 큰 코드 베이스에서 이 기능은 불필요한 빌드 성능 처벌을 초래할 수 있습니다.
      * 이제 파이프라인당 Maven 종속성 캐시를 무효화하는 데 사용할 수 있는 API가 있습니다.
      * [!DNL Experience Manager Project Archetype used by Cloud Manager] 버전이 버전 29로 업데이트되었습니다.








### 커뮤니티

* [Experience League의 최신 Adobe Experience Manager 콘텐츠 목록 | 2021년 9월](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/m-p/421751#M29908)

   최신 문서의 전체 목록은 [여기](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/m-p/421751#M29908)에 있습니다.

* [Adobe Experience ](https://www.linkedin.com/company/adobe-experience-cloud/) Cloud Communities는 Adobe 사용자가 고객을 위해 게임 변경 디지털 경험을 만들고, 참여시키고, 권한을 부여하는 하트비트입니다.

   모든 구성원 목록을 보려면 [Adobe 블로그](https://blog.adobe.com/en/publish/2021/09/02/introducing-the-2021-adobe-community-advisors.html#gs.a6braz)를 방문하십시오.

* [Experience Manager에 대한 새로운 기능 요청/제안을 제출하는 방법은 무엇입니까?](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/announcing-the-new-process-to-submit-experience-manager-feature/td-p/380425)

   Experience Manager 기능 요청을 제출하는 새로운 프로세스는 Live Now입니다. [아이디어 생성](https://experienceleaguecommunities.adobe.com/t5/forums/postpage/board-id/adobe-experience-manager-ideas) | [자세히 알아보기](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/announcing-the-new-process-to-submit-experience-manager-feature/td-p/380425) | [제출 가이드라인](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/guidelines-for-submitting-a-new-experience-manager-aem-idea/m-p/382376#M27427)

### 새로운 Experience Manager 교육 과정 및 튜토리얼 {#tutorials-aem}

지난 달에 게시된 새로운 비디오, 튜토리얼 및 교육 과정입니다.

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2021년 9월 | [Experience Manager 백엔드 개발자 기초 사항](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2019.1.backend) | 교육 과정 | Adobe Experience Manager을 사용하여 백엔드 개발에 대해 자세히 살펴보십시오. Java™ API, Sling 모델 및 단위 테스트 작업에 대한 모범 사례를 알아봅니다. |
| 2021년 9월 | [ [!UICONTROL Assets Essentials 시작]](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/getting-started.html) | 비디오 | [!UICONTROL Assets Essentials]이 직관적이고 사용자에게 친숙한 사용자 인터페이스를 제공하여 자산 및 관련 정보를 쉽게 찾고 기억할 수 있도록 하는 방법을 알아봅니다. |
| 2021년 9월 | [프로비저닝  [!UICONTROL Assets Essentials]](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/provisioning.html) | 비디오 | [!DNL Cloud Manager]를 사용하여 [!UICONTROL Assets Essentials]을 배포하고 사용자 액세스를 프로비저닝하는 방법을 알아봅니다. |
| 2021년 9월 | [Creative Cloud 및  [!UICONTROL Assets Essentials]](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/creative-cloud.html?lang=en) | 비디오 | [!UICONTROL Assets Essentials]을 Adobe Creative Cloud 라이브러리와 통합하는 방법을 알아봅니다. |

{style=&quot;table-layout:auto&quot;}

### Experience Manager 릴리스 정보 {#aem-links}

릴리스 정보 및 Experience Manager에 대한 다른 릴리스 정보 링크는 여기를 참조하십시오.

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

## ![아이콘](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign은 온라인 및 오프라인 마케팅 채널 간에 직관적이고, 자동화된 방식으로 일대일 메시지를 제공합니다. 이제 고객이 습관 및 선호도에 따라 결정된 작업 환경을 통해 원하는 사항을 예측할 수 있습니다.

### 최신 Campaign 제품 릴리스

릴리스된 최신 기능, 개선 사항 및 수정 사항에 대해 자세히 알아보십시오.

* [Campaign v8 릴리스 정보](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/release-notes.html)
* [Campaign Classic v7 릴리스 정보](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html)
* [Campaign Standard 릴리스 정보](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html)

### 새로운 [!UICONTROL Campaign] 교육 과정 및 튜토리얼 {#tutorials-campaign}

| 게시일 | 이름 | 애플리케이션 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2021년 9월 | [[!UICONTROL Campaign 컨트롤 패널] 문제 해결](https://experienceleague.adobe.com/docs/campaign-learn/control-panel/troubleshooting.html) | Campaign V8 | [!UICONTROL Campaign 컨트롤 패널] 문제를 해결하는 방법을 알아봅니다. |
| 2021년 9월 | [데이터베이스 모니터링](https://experienceleague.adobe.com/docs/campaign-learn/control-panel/performance-monitoring/monitor-databases.html) | Campaign V8 | [!UICONTROL Campaign 컨트롤 패널]를 사용하여 인스턴스의 데이터베이스 사용을 모니터링하는 방법을 알아봅니다. |
| 2021년 9월 | [IP 허용 목록에 추가하다 주소](https://experienceleague.adobe.com/docs/campaign-learn/control-panel/instance-settings/allowlist-ip-address.html) | Campaign V8 | Campaign Classic 인스턴스의 허용 목록에 IP 범위를 추가하는 방법과 [!UICONTROL Campaign 컨트롤 패널]을 사용하여에서 IP 범위를 제거하는 허용 목록에 추가하다 방법을 알아봅니다. |
| 2021년 9월 | [IP 허용 목록에 추가하다 범위](https://experienceleague.adobe.com/docs/campaign-learn/control-panel/sftp-management/allowlist-ip-range.html) | Campaign V8 | [!UICONTROL Campaign 컨트롤 패널]허용 목록에 추가하다에서 IP 주소 범위를에 추가하는 방법을 알아봅니다. |
| 2021년 9월 | [URL 권한 추가](https://experienceleague.adobe.com/docs/campaign-learn/control-panel/instance-settings/add-url-permissions.html) | Campaign V8 | Adobe Campaign Classic 인스턴스에서 외부 URL로 연결을 설정하는 방법을 알아봅니다. |
| 2021년 9월 | [SFTP 서버에 연결](https://experienceleague.adobe.com/docs/campaign-learn/control-panel/sftp-management/connect-to-sftp-server.html) | Campaign V8 | [!UICONTROL Campaign 컨트롤 패널]에 저장한 키를 사용하여 클라이언트 SFTP 애플리케이션을 통해 SFTP 서버에 연결하는 방법을 알아봅니다. |
| 2021년 9월 | [SSH 키 생성](https://experienceleague.adobe.com/docs/campaign-learn/control-panel/sftp-management/generate-ssh-key.html) | Campaign V8 | 터미널을 사용하여 SSH 키를 생성하는 방법과 [!UICONTROL Campaign 컨트롤 패널]에 키의 공개 버전을 저장하는 방법을 알아봅니다. |
| 2021년 9월 | [Campaign 컨트롤 패널 - 서버 용량 모니터링](https://experienceleague.adobe.com/docs/campaign-learn/control-panel/sftp-management/monitor-server-capacity.html) | Campaign V8 | SFTP 서버의 스토리지 용량을 모니터링하는 방법을 알아봅니다. |
| 2021년 9월 | [Campaign 컨트롤 패널 - Campaign 컨트롤 패널 시작](https://experienceleague.adobe.com/docs/campaign-learn/control-panel/get-started.html) | Campaign V8 | 이 문서에서는 [!UICONTROL Campaign 컨트롤 패널]에 액세스하는 방법과 [!UICONTROL Campaign 컨트롤 패널]에서 사용할 수 있는 사전 요구 사항을 설명합니다. |
| 2021년 9월 | [Adobe Campaign 문제 해결 - 개요](https://experienceleague.adobe.com/docs/campaign-standard-learn/troubleshooting/overview.html?lang=en) | Campaign Standard | 이 섹션은 Adobe Campaign Standard에서 발생할 수 있는 문제를 해결하는 데 도움이 되도록 Adobe 고객 지원 센터에서 제공합니다. |
| 2021년 9월 | [0ID 레코드가 없습니다.](https://experienceleague.adobe.com/docs/campaign-classic-learn/troubleshooting/login-and-client-console/fixing-zero-id.html?lang=en) | Campaign Classic | 0(0) ID 문제를 수정하는 방법을 알아봅니다. |
| 2021년 9월 | [로드 밸런서 문제](https://experienceleague.adobe.com/docs/campaign-classic-learn/troubleshooting/administration/load-balancer-issues.html?lang=en) | Campaign Classic | 인스턴스 다시 시작 시 로드 밸런서 문제를 해결하는 방법을 알아봅니다. |
| 2021년 9월 | [Analytics에 캠페인 레이블 보내기](https://experienceleague.adobe.com/docs/campaign-classic-learn/troubleshooting/integrations/missing-campaign-label.html?lang=en) | Campaign Classic | Analytics에서 누락된 캠페인 레이블을 수정하는 방법을 알아봅니다. |
| 2021년 9월 | [전자 메일을 트리거하는 메시지 사용 안 함](https://experienceleague.adobe.com/docs/campaign-classic-learn/troubleshooting/deliveries-and-channels/disabled-messages-sending-emails.html?lang=en) | Campaign Classic | 비활성화된 메시지에서 전자 메일을 중지하는 방법을 알아봅니다. |
| 2021년 9월 | [게시 오류 수정](https://experienceleague.adobe.com/docs/campaign-classic-learn/troubleshooting/deliveries-and-channels/publishing-permissions-issues.html?lang=en) | Campaign Classic | 관리자가 아닌 사용자의 게시 오류를 수정하는 방법을 알아봅니다. |
| 2021년 9월 | [공개 리소스 URL을 http에서 https로 변경하는 단계별 방법](https://experienceleague.adobe.com/docs/campaign-standard-learn/troubleshooting/change-public-resource-url.html?lang=en) | Campaign Standard | 공개 리소스 URL을 http에서 https로 변경하는 방법을 알아봅니다 |
| 2021년 9월 | [배달 XML 데이터 가져오기](https://experienceleague.adobe.com/docs/campaign-classic-learn/troubleshooting/workflows/query-delivery-output-names.html?lang=en) | Campaign Classic | 배달 XML 데이터를 가져오는 방법을 알아봅니다. |
| 2021년 9월 | [Experience Manager에 연결하는 중에 발생하는 오류](https://experienceleague.adobe.com/docs/campaign-standard-learn/troubleshooting/error-aem-connection.html?lang=en) | Campaign Standard/Experience Manager | Campaign Standard에서 Experience Manager으로 연결하는 동안 서비스 `nms:delivery`의 오류 `GetAEMContentList`을 해결하는 방법을 알아봅니다. |
| 2021년 9월 | [콘솔 로그인 오류를 수정합니다.](https://experienceleague.adobe.com/docs/campaign-classic-learn/troubleshooting/login-and-client-console/console-login-errors.html?lang=en) | Campaign Classic | 콘솔 로그인 중에 발생한 오류를 수정하는 방법을 알아봅니다. |
| 2021년 9월 | [프로필을 보는 도중 발생하는 기술 오류 문제를 해결하는 방법](https://experienceleague.adobe.com/docs/campaign-standard-learn/troubleshooting/technical-error-while-viewing-profile.html?lang=en) | Campaign Standard | 콘솔 로그인 중에 발생한 오류를 수정하는 방법을 알아봅니다. |
| 2021년 9월 | [캠페인 워크플로우에서 무조건적 정지](https://experienceleague.adobe.com/docs/campaign-classic-learn/troubleshooting/workflows/unconditional-stop-workflow.html?lang=en) | Campaign Classic | 워크플로우에서 무조건적 정지를 올바르게 수행하는 방법을 알아봅니다. |

{style=&quot;table-layout:auto&quot;}

### Campaign 도움말 리소스

* Adobe Campaign v8: [도움말 센터](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=ko-KR) - [릴리스 정보](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html) - [구현 안내서](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html)
* Adobe Campaign Standard: [Campaign Standard 설명서](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html) - [릴리스 노트](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [방법 비디오](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html) - [릴리스 계획](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Campaign Classic v7 설명서](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html) - [릴리스 노트](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [방법 비디오](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html)
* Adobe Campaign 제어판: [설명서](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=ko) - [릴리스 정보](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=ko-KR) - [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=ko) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=ko) 방법 비디오

## ![아이콘](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

[!DNL Adobe Advertising Cloud]의 릴리스 정보.

* [ [!DNL Advertising Cloud DSP]의 새로운 기능](#adcloud-dsp)
* [ [!DNL Advertising Cloud Search]의 새로운 기능](#adcloud-search)

### [!DNL Advertising Cloud DSP]의 새로운 기능 {#adcloud-dsp}

최신 업데이트: **2021년 8월 12일, 8월 11일 릴리스**

| 기능 | 설명 |
| ------- | ----------- |
| 배치에 대한 [!UICONTROL 사전 입찰 가시성] | 이제 Oracle Advertising(Moat)의 [!UICONTROL 사전 입찰 가시성] 필터를 배치에 사용할 수 있습니다. |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud Search]의 새로운 기능 {#adcloud-search}

최신 업데이트: **2021년 8월 20일, 8월 21일 릴리스**

| 기능 | 설명 |
| ------- | ----------- |
| — | 새로운 베타 Advertising Cloud JavaScript 태그는 ECID(Adobe Experience Cloud ID) 서비스 및 기존 `ef_id` 및 `gsurferid` 를 사용하여 전환을 측정합니다. 새 태그는 [자사 Experience Cloud s_ecid 쿠키](https://experienceleague.adobe.com/docs/core-services/interface/administration/ec-cookies/cookies-first-party.html)를 생성하고 다른 Experience Cloud 제품과의 긴밀한 통합을 제공합니다.<br><br>ITP 매핑이 있는 기존 Advertising Cloud JavaScript 태그는 2021년 9월에 더 이상 사용되지 않습니다.<br><br>자세한 내용과 구현 지침에 대해서는 Adobe 계정 관리자에게 문의해 주십시오. |
| [!UICONTROL 포트폴리오] | 모든 사용자는 자동화된 가중치 권장 사항이 포함된 새로운 [!UICONTROL Objectives Beta]를 사용할 수 있습니다. 새로운 인터페이스에는 목표 생성 및 초기 목표 가중치 설정에 대한 추가 지침이 포함되어 있습니다. 가중치 권장 사항은 지원 메트릭에만 사용할 수 있습니다. |

{style=&quot;table-layout:auto&quot;}

## ![아이콘](/assets/magento.png) [!DNL Commerce] (Magento) {#magento}

Adobe Commerce 릴리스 정보에 대한 다음 링크를 참조하십시오.

* [Adobe 상거래 및 Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Adobe Commerce용 Cloud Suite](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

## ![아이콘](/assets/target.png) [!DNL Target] {#target}

최근 업데이트: **2021년 8월 3일**

최신 릴리스 정보는 [[!DNL Target] 릴리스 정보](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=ko-KR)를 참조하십시오.

## ![아이콘](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] 는 리드 관리를 위한 완전한 애플리케이션이며, 복잡한 구매 여정의 모든 단계에서 고객 경험을 전환하여 고객 경험을 혁신하고자 하는 B2B 마케터입니다.

### 주요 Marketo Engage 업데이트

최신 릴리스 일정 정보 및 릴리스 정보는 [!DNL Marketo Engage] [릴리스 일정](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=ko-KR)을 참조하십시오.

## ![아이콘](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe [!DNL Workfront]는 아이디어 공유, 콘텐츠 생성, 복잡한 프로세스 관리 및 최상의 작업 수행을 위한 통합 작업 관리 애플리케이션입니다.

모든 제품에 대한 최신 정보를 보려면 [[!DNL Workfront] 릴리스](https://one.workfront.com/s/product-releases) 페이지를 참조하십시오.

## ![아이콘](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Adobe Document Cloud용으로 게시된 새로운 비디오, 튜토리얼 또는 교육 과정

### Document Cloud 과정 및 튜토리얼 {#tutorials-doc-cloud}

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2021년 9월 | [태그가 지정되지 않은 PDF에 양식 필드 추가](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/accessibility-series/accessibilitysession6.html) | 비디오 | 이 온디맨드 세션은 수동 양식 필드와 추가 양식 필드 속성을 만드는 데 더 깊이 있습니다. |
| 2021년 9월 | [태그가 지정된 PDF에 양식 필드 추가](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/accessibility-series/accessibilitysession5.html) | 비디오 | 이 온디맨드 세션은 이전에 태그가 지정된 PDF에 양식 필드를 추가하는 데 중점을 둡니다. |
| 2021년 9월 | [스캔한 문서 및 복잡한 목록](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/accessibility-series/accessibilitysession4.html) | 비디오 | 이 온디맨드 세션은 스캔한 문서 및 복잡한 목록과 같이 사람들이 자주 접하게 되는 더 복잡한 문제를 해결합니다. |
| 2021년 9월 | [복잡한 표](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/accessibility-series/accessibilitysession3.html) | 비디오 | 이 온디맨드 세션은 접근성을 위해 PDF를 수정하는 데 있어 가장 일반적이고 어려운 문제 중 하나(복잡한 표)를 해결합니다. |
| 2021년 9월 | [액세스할 수 없는 PDF 수정](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/accessibility-series/accessibilitysession2.html) | 비디오 | 이 온디맨드 세션에서는 소개 웨비나에 표시된 Acrobat Pro DC 도구를 사용하여 Word 문서를 변환하고 몇 가지 기본 태깅 문제를 수정하는 워크플로우를 알아봅니다. |
| 2021년 9월 | [PDF 접근성 소개](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/accessibility-series/accessibilitysession1.html) | 비디오 | 이 온디맨드 세션에서 PDF에 액세스할 수 있도록 하는 것이 무엇을 의미하는지, PDF에서 쉽게 작업할 수 있도록 Acrobat Pro DC을 설정하는 방법, 소스 문서에서 PDF로 변환 프로세스를 알아봅니다. |
| 2021년 9월 | [휴대폰에서 PPT 파일을 PDF로 변환](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/phone.html) | 비디오 | 이 60초 비디오 자습서에서는 휴대폰에서 전자 메일 PowerPoint 첨부 파일을 PDF로 변환하는 방법을 알아봅니다. 파일이 반환되면 해당 파일을 보고 공유 를 탭하여 팀에 전송하십시오. PowerPoint를 휴대폰에 연결하지 않아도 됩니다. |
| 2021년 9월 | [즉시 사진 PDF 만들기](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/photo.html) | 비디오 | 이 60초 비디오 자습서에서는 JPG 다발을 Acrobat 아이콘으로 드래그하여 놓아 PDF를 만드는 방법을 살펴봅니다. 다중 페이지 PDF를 만들려면 [예]를 클릭합니다. 그런 다음 더 많은 JPG 파일을 페이지 패널로 드래그하여 PDF에 페이지를 추가할 수 있습니다. |
| 2021년 9월 | [여러 PDF 파일을 한 번에 검색](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/search.html) | 비디오 | 이 60초 비디오 자습서에서는 PDF 파일에서 검색을 시작한 다음 고급 검색을 열고 PDF 파일의 전체 폴더를 검색하는 방법을 살펴봅니다. |
| 2021년 9월 | [Acrobat 웹을 사용하여 PDF 편집](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/edit.html) | 비디오 | 이 60초 비디오 자습서에서는 PDF를 다운로드하지 않고도 텍스트 및 이미지를 간단한 편집으로 편집하는 방법을 배웁니다. |
| 2021년 9월 | [파일을 하나의 PDF로 결합](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/combine-to-one-pdf.html) | 비디오 | 이 60초 비디오 자습서에서는 여러 가지 유형의 파일을 하나의 PDF에 결합하여 문서를 빠르게 만드는 방법을 알아봅니다. |
| 2021년 9월 | [Acrobat 접근성 시리즈](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/accessibility-series/accessibility-series.html) | 비디오 | 이 6파트로 구성된 온디맨드 웨비나 시리즈에서는 접근성의 기본 사항에서 PDF 파일에 대한 태깅을 자세히 살펴보겠습니다. 각 세션에는 따라 따라야 할 실습 파일이 포함되어 있습니다. |

{style=&quot;table-layout:auto&quot;}

Document Cloud 도움말은 다음을 참조하십시오.

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=ko-KR)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=ko-KR)
* [Document Cloud 학습 및 지원](https://helpx.adobe.com/kr/support/document-cloud.html)

## ![아이콘](/assets/creative-cloud-24.png) Creative Cloud for enterprise {#creative-cloud}

최신 튜토리얼은 [Creative Cloud for Enterprise Tutorials](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=ko-KR)를 참조하십시오.
