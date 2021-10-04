---
title: 최신 릴리스 정보
description: ' [!DNL Experience Cloud] 제품 및 서비스에 대한 최신 릴리스 노트, 새로운 기능 및 새 설명서에 대해 알아봅니다.  [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise], and [!DNL Document Cloud]에 대한 새로운 도움말 및 자습서를 찾으십시오.'
doc-type: release notes
last-update: October 2021
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 2ad6cb4ae1ae0c9a9414df7c1360a3d4d428f1e5
workflow-type: tm+mt
source-wordcount: '5271'
ht-degree: 39%

---

# Adobe Experience Cloud 릴리스 노트 - 2021년 10월

![배너](assets/experience-cloud-banner-3.png)

[!DNL Experience Cloud] 애플리케이션과 서비스는 매달 업데이트됩니다. 이 페이지는 [!DNL Experience Cloud] 및 [!DNL Experience Platform]의 최신 릴리스 업데이트, 설명서 및 튜토리얼을 찾을 수 있는 중앙 위치입니다. [!DNL Creative Cloud for enterprise] 및 [!DNL Document Cloud]에 대한 새로운 설명서도 찾을 수 있습니다.

>[!NOTE]
>
>월별 [Adobe 우선 순위 제품 업데이트](https://www.adobe.com/kr/subscription/priority-product-update.html) 를 구독하면 이 페이지의 업데이트에 대한 이메일 알림을 받을 수 있습니다. 이 페이지는 한 달 동안 유지되므로 Adobe 엔터프라이즈 제품 및 Experience League 설명서에 대한 업데이트를 정기적으로 확인하십시오.

최신 업데이트: **2021년 10월 1일**

* [[!DNL Experience League] 라이브 이벤트](#events)
* [[!DNL Experience Cloud Central Interface Components] 및 관리](#ecloud)
* [Adobe [!UICONTROL 시스템 상태]](#status)
* [[!DNL Adobe Analytics]](#analytics) 및 [Customer Journey Analytics](#cust-journey)
* [[!DNL Adobe Audience Manager]](#aam)
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

## ![아이콘](/assets/experience-league.png) [!DNL Experience League] 라이브 이벤트 {#events}

[!DNL Experience League] 라이브 이벤트는 Adobe 기술을 제공하는 데 중요한 역할을 하는 Adobe 전문가 및 특별 게스트와 함께하는 토론입니다. 다음의 일정을 확인하여 실시간으로 참여하거나 이전에 녹화된 이벤트를 시청하세요.

| 이벤트 날짜 | 이벤트 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2021년 9월 23일 | [연말연시 캠페인을 돋보이게 할 수 있는 전문가의 팁](https://www.youtube.com/watch?v=bsU1lAv0xes) | 라이브 비디오 이벤트 | 연말연시 선물 준비를 미리 시작할수록 좋은 것처럼, 대성공을 거둬야 하는 연말연시 마케팅 캠페인을 위한 계획도 미리 시작할수록 좋습니다. Adobe Campaign을 통해 귀사에서 연말연시에 이루기를 소망하는 모든 것을 담은 캠페인을 설계하고 계획하고 실행할 수 있습니다.<br>하지만, 여러분은 한 해를 완전히 끝낸 캠페인을 실행하기 위한 모든 팁을 알고 있나요? Sandra와 함께 라이브 토론을 할 수 있습니다. 세 명의 Adobe 전문가들, 그들은 단지 그것을 하는 데 있어 수십 억 정도의 전문 지식을 가지고 있습니다. |
| 2021년 8월 26일 | [보다 스마트한 향후 대상 세그먼트 구축하기](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-02.html?lang=ko) | 이벤트 녹화본 | 모든 훌륭한 마케팅 캠페인의 성공 여부는 대상자를 정확하게 타기팅하느냐에 달려 있습니다. 새로운 Adobe Experience Platform [!UICONTROL 세그먼트 빌더]를 통해 채널 전반의 프로필 데이터 및 시간 기반 사용자 행동을 사용하여 향후 대상 세그먼트를 구축할 수 있습니다. 캠페인의 메시지가 정말 닿아야 할 사람들에게 닿도록 하는 데 이보다 더 좋은 방법은 없습니다. |
| 2021년 7월 29일 | [내가 가장 좋아하는 세 가지 Adobe Analytics 구현 팁](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-01.html?lang=ko) | 이벤트 녹화본 | Summit 무대에서 만난 적 있는 분입니다. Adobe Insider Tours에서 전문가 조언을 들려줬던 분입니다. 자체 Adobe Analytics 구현과 관련하여 이 분과 협력하는 혜택을 얻은 적이 있을 수도 있습니다. 이제 이 독점 Experience League Live 토론에서 Eric Matisoff 씨가 자신이 가장 좋아하는 세 가지 Adobe Analytics 구현 팁을 소개합니다. |

{style=&quot;table-layout:auto&quot;}

자세한 비디오는 YouTube의 [Adobe Experience League 채널](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw)을 참조하십시오.

## ![아이콘](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] 및 관리 {#ecloud}

| 기능 | 설명 |
| ------- | ------- |
| 통합 검색 | 통합 검색은 검색 인덱스에 객체 유형을 계속 추가합니다. 이 업데이트에서 전역 검색은 이제 Experience League 컨텐츠과 다음 Journey Optimizer 개체 유형에서 검색합니다. <ul><li>데이터 세트</li><li>대상</li><li>쿼리</li><li>스키마</li><li>세그먼트</li><li>소스</li><li>오퍼</li><li>구성 요소</li><li>메시지</li><li>여정</li></ul> |
| 제품 사용 데이터 동의 | 처음 로그인하면 Adobe이 Experience Cloud 제품 사용 데이터를 기반으로 자습서, 안내서, 빠른 팁, 권장 사항, 학습 비디오 등과 같은 유용한 개인화된 콘텐츠를 제공하는 방법에 대한 환경 설정을 제출하라는 메시지가 표시됩니다. 이 요청에는 <https://experience.adobe.com/preferences>에서 이러한 데이터의 수집 및 사용에 대한 기본 설정에 대한 업데이트도 포함되어 있습니다. |
| Experience Cloud [!UICONTROL 트리거] 탐색 | [Experience Cloud ](https://experienceleague.adobe.com/docs/core-services/interface/services/activation/triggers.html?lang=en) 트리거는 제공된 사용자에 대한 헤더의 애플리케이션 전환기에서 직접 탐색에 사용할 수 있습니다. |
| **알림:** 계획된 인터페이스 탐색 업데이트 | 2021년 11월에 _[!UICONTROL Go to Launch / Data Collection]_ 탐색 기능이 <https://experience.adobe.com/implement>에서 제거됩니다. |

{style=&quot;table-layout:auto&quot;}

**[!DNL Experience Cloud Central UI Components] 및 관리**&#x200B;에 대한 추가 도움말 리소스

* [중앙 인터페이스 구성 요소](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=ko-KR) 및 사용자 관리에 대한 관리 도움말
* [장소 - 위치 서비스](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=ko-KR)에 대한 도움말 및 릴리스 정보
* [인물 - 고객 속성 및 대상 라이브러리](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)에 대한 도움말

## ![아이콘](/assets/adobe.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status]는 Adobe 제품 및 서비스 중단, 중단 및 유지 관리 이벤트에 대한 자세한 정보, 상태 업데이트 및 이메일 알림을 제공합니다. [status.adobe.com](https://status.adobe.com/)에서 관련 정보를 확인하십시오.

([!DNL Adobe System Status]에 대한 최신 릴리스 정보는 [2020년 5월 21일](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=ko-KR) 릴리스 정보를 참조하십시오.)

## ![아이콘](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

릴리스 날짜: **2021년 10월 7일**

* [Adobe Analytics의 새로운 기능](#aa-features)
* [Customer Journey Analytics의 새로운 기능](#cust-journey)
* [Adobe Analytics의 수정 사항](#aa-fixes)
* [Analytics 관리자에 대한 중요 공지](#aa-notices)
* [Analytics 교육 과정 및 튜토리얼](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics의 새로운 기능 {#aa-features}

| 기능 | 설명 | [일반 가용성](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=ko) - 대상 날짜 |
| ----------- | ---------- | ------- |
| Analytics 대시보드에 대한 시각화 | Analytics [!UICONTROL 대시보드]는 경영진 및 의사 결정자가 자신의 데이터를 더 잘 이해할 수 있도록 해주는 세 가지 새로운 시각화를 도입했습니다. 새로운 [!UICONTROL 도넛], [!UICONTROL 라인] 및 [!UICONTROL 가로] 막대 차트를 사용하면 세부 사항 보기를 열지 않고도 개별 차원 항목에 대한 데이터를 보다 쉽게 볼 수 있습니다. (참조할 설명서 링크) | 2021년 10월 7일 |
| [!UICONTROL 미디어 재생 시간] | Adobe 스트리밍 미디어 재생 [!UICONTROL 체류 시간]은(는) 뷰어 참여에 대한 중요한 통찰력을 제공하고 미디어 조직이 시간대 지정 기능이 포함된 고급 체류 시간 분석을 통해 분당 사용자 참여로 보다 깊고 세분화된 통찰력을 얻을 수 있도록 합니다. 특정 시점에 미디어 스트림을 보는 데 걸린 시간을 관찰할 수 있습니다. 새로운 5분, 15분 및 30분 세부기간을 포함하여 재생 기간을 다양한 세부기간으로 분할할 수 있습니다. [자세히 알아보기](https://experienceleague.adobe.com/docs/media-analytics/using/media-reports/media-workspace-panels/media-playback-time-spent.html?lang=en) | 2021년 10월 18일 |
| 빠른 [!UICONTROL 세그먼트 빌더] | 비즈니스 사용자가 간소화된 인라인 프로젝트 워크플로우에서 기본 세그먼트를 신속하게 적용할 수 있습니다. [!UICONTROL 세그먼트 빌더]로 이동할 필요가 없습니다. [자세히 알아보기](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/components/segments/quick-segments.html?lang=en) | 2021년 10월 21일 |
| Analysis Workspace 왼쪽 레일 검색 개선 | 왼쪽 레일 검색은 1) 구성 요소 최신성 및 관련성을 계속 고려하는 것 외에도 광범위한 일치 항목 위에 정확히 일치하는 항목을 우선 순위를 지정합니다. 2) 검색 결과를 보다 쉽게 이해할 수 있도록 일치된 문자를 강조 표시합니다. 3) 차원과 관련된 분류를 쉽게 찾을 수 있습니다. 4) 마지막으로 필요한 특정 구성 요소를 보다 쉽게 찾을 수 있도록 와일드카드(`*`) 검색을 지원합니다. 참고: 와일드카드 검색이 차원 항목 수준에서 아직 작동하지 않습니다. | 2021년 10월 21일 |
| Analysis Workspace 다크 테마 | 어두운 테마는 표시 옵션으로 사용할 수 있습니다. | 2021년 10월 21일 |

{style=&quot;table-layout:auto&quot;}

### Customer Journey Analytics의 새로운 기능 {#cust-journey}

| 기능 | 설명 | [일반 가용성](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=en) - 대상 날짜 |
| ----------- | ---------- | ----- |
| Report Builder 지원 | Report Builder은 Customer Journey Analytics 데이터를 사용하여 사용자 지정 보고서를 쉽게 만들고, 편집하고, 새로 고칠 수 있는 Microsoft® [!DNL Excel] 추가 기능입니다. Report Builder 및 Excel을 사용하면 간단하지만 유연한 드래그 앤 드롭 UI를 사용하여 복잡한 데이터 요청을 쉽게 작성할 수 있습니다. Customer Journey Analytics Report Builder을 사용하면 다음 작업을 수행할 수 있습니다.<ul><li>기존 워크시트 셀을 참조하여 완벽한 행 순서, 날짜 범위 또는 필터를 가져옵니다</li><li>달력, 셀 참조 또는 날짜 수학을 사용하여 사용자 지정 날짜 만들기</li><li>익숙한 Excel 서식 도구를 사용하여 표 및 시각화 디자인</li><li>macOS, 웹용 Microsoft 365 및 Microsoft Windows에서 사용 가능</li></ul> | 2021년 10월 7일 |
| Analytics 대시보드에 대한 시각화 | Analytics [!UICONTROL 대시보드]는 경영진 및 의사 결정자가 자신의 데이터를 보다 잘 이해할 수 있도록 해주는 세 가지 새로운 시각화를 도입했습니다. 새로운 도넛, 선 및 가로 막대형 차트를 사용하면 세부 사항 보기를 열지 않고도 개별 차원 항목에 대한 데이터를 더 쉽게 볼 수 있습니다. (참조할 설명서 링크) | 2021년 10월 7일 |
| Customer Journey Analytics 감사 로그(API만 해당) | 감사 로그는 보안 규정 준수와 데이터 및 사용자 작업 감사 시 중요한 부분입니다. | 2021년 10월 7일 |
| 빠른 [!UICONTROL 필터 빌더] | 비즈니스 사용자가 간소화된 인라인 프로젝트 워크플로우에서 기본 세그먼트를 신속하게 적용할 수 있습니다. [!UICONTROL 필터 빌더]로 이동할 필요가 없습니다. [자세히 알아보기](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-components/cja-filters/quick-filters.html?lang=en) | 2021년 10월 21일 |
| Analysis Workspace 왼쪽 레일 검색 개선 | 왼쪽 레일 검색은 1) 구성 요소 최신성 및 관련성을 계속 고려하는 것 외에도 광범위한 일치 항목 위에 정확히 일치하는 항목을 우선 순위를 지정합니다. 2) 검색 결과를 보다 쉽게 이해할 수 있도록 일치된 문자를 강조 표시합니다. 3) 차원과 관련된 분류를 쉽게 찾을 수 있습니다. 4) 마지막으로 필요한 특정 구성 요소를 보다 쉽게 찾을 수 있도록 와일드카드(`*`) 검색을 지원합니다. 참고: 와일드카드 검색이 차원 항목 수준에서 아직 작동하지 않습니다. | 2021년 10월 21일 |
| Analysis Workspace 다크 테마 | 어두운 테마는 표시 옵션으로 사용할 수 있습니다. | 2021년 10월 21일 |

{style=&quot;table-layout:auto&quot;}

### Adobe Analytics 및 CJA의 수정 사항 {#aa-fixes}

* Customer Journey Analytics에서 예약된 보고서 오류가 수정되었습니다. (AN-271721)
* [!UICONTROL 작업 공간]에서 [!UICONTROL 검색 구성 요소]가 정확히 일치하지 않는 문제가 해결되었습니다. (AN-253937; AN-271707)

#### Adobe Analytics의 추가 수정 사항

AN-256136; AN-265420; AN-268455; AN-269768; AN-270276; AN-270287; AN-271601; AN-271969; AN-272056; AN-272111; AN-272457

### [!DNL Analytics] 관리자에 대한 중요 공지 {#aa-notices}

| 공지 | 추가 또는 업데이트 날짜 | 설명 |
| ----------- | ---------- | ---------- |
| 3개의 Analytics API 서비스에 대한 EOL | 2021년 9월 16일 | **2021년 10월 28일**&#x200B;에 다음 Analytics 이전 API 서비스가 종료됩니다. 이들 서비스를 사용하여 구축한 현재 모든 통합은 해당 날짜부터 더 이상 작동하지 않습니다.<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>이전 OAuth 인증(OAuth 및 JWT)</li></ul>Adobe는 질문에 답변하고 진행 방법에 대한 지침을 제공하기 위해 [이전 API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) 를 제공했습니다. 이들 서비스를 사용하는 API 통합은 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 또는 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)로 마이그레이션할 수 있습니다. 이전 OAuth 계정은 [Adobe I/O](https://developer.adobe.com/console) Analytics 통합 계정으로 마이그레이션할 수 있으며, 이 계정은 1.4 Analytics API 및 2.0 Analytics API에 모두 액세스하는 데 사용할 수 있습니다. |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

AppMeasurement 릴리스(버전 2.22.2)에 대한 최신 업데이트는 [JavaScript용 AppMeasurement 릴리스 정보](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=ko-KR)를 참조하십시오.

### Analytics 교육 과정 및 튜토리얼 {#tutorials-analytics}

[!DNL Analytics] 및 [!UICONTROL Customer Journey Analytics]의 최신 강좌, 자습서 및 기사입니다.

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2021년 10월 | [시각화를 사용하여 데이터 스토리 전달](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2021.1.visualizations) | 교육 과정 | 누가 데이터에서 인사이트를 얻으려고 테이블 뒤에 표를 검색하시겠습니까? 너 말고! 이 교육 과정에서는 시각화를 프로젝트에 추가하고 데이터를 시각화하는 방법, 각 시각화가 보여 주는 항목 등 시각화에 대한 기본 사항을 알아봅니다. 필요한 데이터를 정확하게 얻기 위해 설정을 구성하는 방법을 배웁니다. 또한 몇 가지 팁과 사용 사례를 통해 일반 분석에 실용적인 시각화를 만들 수도 있습니다. |

{style=&quot;table-layout:auto&quot;}

### Analytics 도움말 리소스

* [Adobe Analytics 제품 설명서 및 튜토리얼](https://experienceleague.adobe.com/docs/analytics.html)

## ![아이콘](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager의 새로운 기능 - **2021년 9월 14일** 업데이트:

| 기능 | 설명 |
| ------- | ------- |
| 모바일 ID 데이터 수집 동의 | 모바일 ID 데이터 수집 동의에 대한 지원이 추가되었습니다. 이 업데이트의 혜택을 받으려면 고객은 [AEP Mobile SDK iOS Core 2.8.0](https://aep-sdks.gitbook.io/docs/foundation-extensions/mobile-core/mobile-core-release-notes#november-4-2020) 이상으로 업그레이드해야 합니다. |

## ![아이콘](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

릴리스 업데이트 정보와 Experience Platform 및 [!UICONTROL Mobile SDK]에 대한 새 설명서를 포함합니다.

**2021년 9월 29일**

| 기능 | 설명 |
| ------- | ------- |
| [[!UICONTROL 데이터 랜딩 영역]](https://experienceleague.adobe.com/docs/experience-platform/sources/connectors/cloud-storage/data-landing-zone.html) | [!UICONTROL 데이터 랜딩 ] 영역 [!DNL Platform]은 샌드박스당 하나의 보안 및 임시 저장소 [!UICONTROL 가 파일을 Experience Platform으로 가져올 수 있도록 해주는 프로비전된 ] Azure Blob Store입니다. |
| 스트리밍 소스는 [데이터 준비](https://www.adobe.com/go/monitor-streaming-dataflows-en)에 대해 지원됩니다 | 이제 스트리밍 소스가 데이터 준비를 지원하며, 비 XDM 호환 소스 데이터를 대상 XDM 스키마에 매핑하기 위한 JSON 소스 스키마를 제공할 수 있습니다. |
| [만료되지 않은 자격 증명](https://experienceleague.adobe.com/docs/experience-platform/query/ui/credentials.html) | [!UICONTROL 쿼리 서비스] 사용자에 대한 만료되지 않은 자격 증명은 24시간마다 자격 증명을 갱신하는 대신 외부 클라이언트에 대한 영구 연결을 허용합니다. |
| [[!UICONTROL 대상 SDK]](https://www.adobe.com/go/destination-sdk-overview-en) | [!UICONTROL 대상 SDK]를 사용하여 [!DNL Platform]와 통합하고 지속적으로 증가하는 대상 카탈로그에 기여합니다. 이 기능에 대한 액세스는 Experience Platform 활성화 고객만 사용할 수 있습니다. |

모든 자세한 내용은 [Experience Platform 릴리스 정보](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html)를 참조하십시오.

### Experience Platform 튜토리얼 및 교육 과정 {#tutorials-platform}

Experience Platform 및 서비스를 위해 게시된 최신 비디오, 자습서 또는 교육 과정

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2021년 10월 | [[!DNL Platform] 관리](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-A-1-2021.1.admin) | 교육 과정 | 권한 및 샌드박스 관리를 포함한 Experience Platform 관리 활동에 대해 알아봅니다. |

{style=&quot;table-layout:auto&quot;}

### Adobe 모바일 SDK

Adobe Experience Platform Mobile SDK에 대한 [릴리스 정보 및 변경 로그](https://aep-sdks.gitbook.io/docs/release-notes)를 참조하십시오.

## ![아이콘](/assets/experience_platform_appicon_24.png) Journey Optimizer {#journey-opt}

[Journey Optimizer 릴리스 정보](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html)에서 최신 기능, 개선 사항 및 수정 사항에 대해 알아봅니다.

### Journey Optimizer 자습서 및 강좌 {#tutorials-ajo}

최신 Journey Optimizer 자습서:

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2021년 10월 | [데이터 엔지니어를  [!DNL Journey Optimizer] 위한 데이터 구성 및 관리](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.2) | 교육 과정 | Journey Optimizer에서 여정 관리에 필요한 데이터를 구성하고 관리하는 방법을 알아봅니다. |
| 2021년 10월 | [여정 관리자  [!DNL Journey Optimizer] 및 관리자용 시작하기](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.1) | 교육 과정 | 첫 번째 여정을 만들기 위해 알아야 할 모든 것을 배웁니다. |
| 2021년 10월 | [ [!DNL Journey Optimizer] 여정 관리자용 구성](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-A-1-2021.1) | 교육 과정 | [!DNL Journey Optimizer] 아키텍처 및 통합 지점을 이해합니다. [!DNL Journey Optimizer] 구성 방법을 알아봅니다. |

{style=&quot;table-layout:auto&quot;}

### [!DNL Journey Optimizer]에 대한 추가 리소스

[도움말 센터](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html) - [릴리스 정보](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [방법 비디오](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html)

## ![아이콘](/assets/experience_platform_appicon_24.png) [!DNL Journey Orchestration] {#journey-orch}

Experience Platform을 사용하여 모든 개인의 요구 사항을 실시간으로 지능적으로 예측하여 경험 채널에서 규모에 맞게 고객 여정을 조율할 수 있습니다.

### 최신 [!DNL Journey Orchestration] 제품 릴리스

[[!DNL Journey Orchestration]  릴리스 정보](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html)에서 최신 기능, 개선 사항 및 수정 사항에 대해 알아봅니다.

#### [!DNL Journey Orchestration]에 대한 추가 리소스

[도움말 센터](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html) - [릴리스 정보](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [사용 방법 비디오](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html)

## ![아이콘](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL Offer ] Decisioning은 Adobe Experience Platform과 통합된 서비스입니다. [!UICONTROL Offer Decisioning] 를 사용하여 적절한 시기에 모든 접점에서 고객에게 최상의 혜택과 경험을 제공하십시오.

### 최신 Offer decisioning 제품 릴리스

[Offer decisioning 릴리스 노트](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html)의 최신 기능, 개선 사항 및 수정 사항에 대해 자세히 알아보십시오.

#### [!UICONTROL Offer Decisioning]을 위한 추가 리소스

[도움말 센터](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started/starting-offer-decisioning.html?lang=ko) - [릴리스 정보](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [사용 방법 비디오](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html)

## ![아이콘](/assets/aem.png) Experience Manager {#aem}

Adobe는 릴리스 정보를 최신 상태로 유지하기 위해 [Experience Manager 릴리스 업데이트 및 로드맵](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html) 페이지를 방문할 것을 권장합니다.

### 커뮤니티

* [Adobe 개발자 라이브](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)  | 2021년 10월 4-5일, 7시 00분 PDT

   Adobe 개발자 라이브는 다양한 배경과 단일 목적을 가진 Adobe 개발자와 경험 작성자를 통합하여 놀라운 종단 간 경험을 만듭니다. 이 이틀간의 컨퍼런스는 중요한 개발자 업데이트, 기술 세션 및 커뮤니티 네트워킹 기회를 제공합니다.

   Adobe Experience Cloud, Document Cloud 및 Creative Cloud의 Adobe 제품 팀에서는 업계 전반에 걸쳐 디자인, 컨텐츠 제작 워크플로우, 문서 서비스 및 고객 경험 관리를 제공하는 최신 기술 향상 및 개발자 도구를 소개합니다.

   Adobe에 20개의 Experience Manager 세션이 계획되어 있습니다. 그 말을 퍼뜨려라!

   * [전체 세션 목록](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-october-2021-complete-session-list/m-p/423041#M120517)
   * [무료 등록 - RSVP에 로그인](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)
   * [Adobe 개발자 라이브 커뮤니티](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/registration-for-adobe-developers-live-is-now-open-october-4-5/td-p/422127)

### 새로운 Experience Manager 교육 과정 및 튜토리얼 {#tutorials-aem}

지난 달에 게시된 새로운 비디오, 튜토리얼 및 교육 과정입니다.

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2021년 10월 | [XML 설명서 시작하기](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.xmldocs) | 교육 과정 | Adobe Experience Manager용 XML 설명서를 사용하여 컨텐츠를 작성, 구성, 작성 및 게시하는 방법을 알아봅니다. |
| 2021년 10월 | [및 Assets Essentials [!DNL Workfront] 를 사용하여 크리에이티브 워크플로우 관리](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.2.assets.essentials) | 교육 과정 | Adobe [!DNL Workfront] 및 Experience Manager 방법을 알아봅니다. |
| 2021년 10월 | [AEM Assets Essentials 시작하기](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.assets.essentials) | 교육 과정 | AEM Assets Essentials로 조직의 자산 관리를 간소화하는 방법을 알아봅니다. |
| 2021년 10월 | [[!UICONTROL 컨텐츠 전송 도구]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/content-transfer-tool.html?lang=en) | 비디오 | [!UICONTROL 컨텐츠 전송 도구]를 사용하여 컨텐츠를 AEM 6.3+에서 Cloud Service으로 AEM에 마이그레이션하는 방법을 알아봅니다. |
| 2021년 10월 | [[!UICONTROL 대량 가져오기 서비스]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/bulk-import-service.html?lang=en) | 비디오 | AEM as a Cloud Services [!UICONTROL 대량 가져오기 서비스]를 사용하여 비 AEM 소스에서 자산을 가져오는 방법을 알아봅니다. |
| 2021년 10월 | [통신(출력 서비스)](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/communications.html?lang=en) | 비디오 | AEM Forms as a Cloud Service이 통신 사용 사례를 지원하는 방법을 알아봅니다. |
| 2021년 10월 | [디지털 등록](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/digital-enrollment.html?lang=en) | 비디오 | AEM Forms as a Cloud Service이 디지털 등록 사용 사례를 지원하는 방법에 대해 알아봅니다. |
| 2021년 10월 | [Cloud  [!UICONTROL Acceleration ] Manager 도구 사용](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/using.html) | 비디오 | [!UICONTROL Cloud Acceleration Manager] 도구 사용에 대한 내레이션이 있는 연습입니다. |
| 2021년 10월 | [Cloud  [!UICONTROL Acceleration Manager 탐색]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/navigating.html) | 비디오 | Experience Manager을 Cloud Service으로 위한 [!UICONTROL Cloud Acceleration Manager]의 탐색 경험을 탐색합니다. |
| 2021년 10월 | [자산 워크플로우 마이그레이션 도구](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/asset-workflow-migration-tool.html) | 비디오 | [!UICONTROL 자산 워크플로우 마이그레이션] 도구를 사용하여 기존 AEM Assets 워크플로우를 Cloud Service으로 마이그레이션하는 방법을 알아봅니다. |
| 2021년 10월 | [[!UICONTROL 인덱스 변환기]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/index-converter.html) | 비디오 | [!UICONTROL Index Converter]에서 기존 AEM 색인 정의를 Cloud Service 호환으로 자동 변환하는 방법을 알아봅니다. |
| 2021년 10월 | [[!UICONTROL Dispatcher 변환기]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/dispatcher-converter.html) | 비디오 | [!UICONTROL Dispatcher Converter]에서 기존 AEM Dispatcher 구성을 Cloud Service 호환으로 자동 업데이트하는 방법을 알아봅니다. |
| 2021년 10월 | [[!UICONTROL 코드 리포지토리 현대화]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-repository-modernizer.html) | 비디오 | [!UICONTROL Core Repository Modernizer]가 기존 AEM Maven 프로젝트를 Cloud Service 호환으로 자동 업데이트하는 방법을 알아봅니다. |
| 2021년 10월 | [[!UICONTROL 코드 리팩터링 도구]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-refactoring-tools.html) | 비디오 | AEM [!UICONTROL 코드 리팩터링 도구]를 통해 기존 AEM 프로젝트를 Cloud Service 호환으로 AEM으로 자동 변환하는 방법을 알아봅니다. |
| 2021년 10월 | [[!UICONTROL 컨텐츠 전송 도구]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/content-transfer-tool.html) | 비디오 | [!UICONTROL 컨텐츠 전송 도구]를 사용하여 컨텐츠를 AEM 6.5에서 Cloud Service으로 효율적으로 이동하는 방법을 알아봅니다. |
| 2021년 10월 | [Cloud  [!UICONTROL Acceleration Manager의 구현 단계]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/implementation-phase.html) | 비디오 | 주요 구현 단계를 검토 및 이해하거나 [!UICONTROL Cloud Acceleration Manager]를 사용하여 Cloud Service으로 AEM으로 이동합니다. |
| 2021년 10월 | [준비 및  [!UICONTROL 모범 사례 분석기]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/readiness-and-best-practice-analyzer.html) | 비디오 | [!UICONTROL 우수 사례 분석기]를 통해 AEM On-Prem 또는 Adobe Managed Services에서 Cloud Service으로 Experience Manager으로 이동할 수 있는 방법을 알아봅니다. |
| 2021년 10월 | [Cloud Acceleration Manager 소개](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/introduction.html) | 비디오 | [!UICONTROL Cloud Acceleration Manager]를 통해 Cloud Service으로 빠르고 쉽게 Experience Manager으로 이동할 수 있는 방법을 알아봅니다. |
| 2021년 10월 | [AEM Forms as a Cloud Service - AEM CS로 이동](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/introduction.html?lang=en) | 비디오 | AEM Forms as a Cloud Service에서 지원하는 사용 사례 및 기능에 대해 알아봅니다. |
| 2021년 10월 | [AEM as a Cloud Service 문제 해결](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/troubleshooting.html?lang=en) | 비디오 | AEM SDK, AEM as a Cloud Service과 빌드 및 배포 프로세스의 문제를 해결하고 디버깅하는 방법을 알아봅니다. |
| 2021년 10월 | [AEM  [!UICONTROL Assets Microservices]  - AEM으로 Cloud Service으로 이동](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/asset-compute-microservices.html?lang=en) | 비디오 | AEM Assets as a Cloud Service의 asset compute 마이크로서비스로서 기존 AEM Workflow에서 이 역할을 대체하여 자산에 대한 렌디션을 자동으로 효율적으로 생성할 수 있도록 하는 방법을 알아봅니다. |
| 2021년 10월 | [검색 및 색인 지정](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/search-and-indexing.html?lang=en) | 비디오 | AEM as a Cloud Service 검색 색인으로서, AEM 6 인덱스 정의를 Cloud Service 호환으로 AEM으로 변환하는 방법 및 Cloud Service으로 AEM에 인덱스를 배포하는 방법에 대해 알아봅니다. |
| 2021년 10월 | [[!UICONTROL Dispatcher]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/dispatcher.html?lang=en) | 비디오 | AEM[!UICONTROL Dispatcher] for AEM as a Cloud Service에 대해 알아보십시오. AEM 6용 [!UICONTROL Dispatcher], [!UICONTROL Dispatcher] 변환 도구 및 Dispatcher 도구 SDK를 사용하는 방법에 주목해야 합니다. |
| 2021년 10월 | [[!UICONTROL Cloud Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/cloud-manager.html?lang=en) | 비디오 | Cloud Manager for AEM as a Cloud Service에 대해 알아보고, Cloud Manager for AEM on AMS(Adobe 관리 서비스)와의 차이점을 파악합니다. |
| 2021년 10월 | [AEM as a Cloud Service에 온보딩](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/onboarding.html?lang=en) | 비디오 | [!UICONTROL Cloud Manager]를 사용하여 환경을 설정하는 과정을 거쳐 계약 단계에서 처음부터 AEM으로 온보딩하는 방법에 대해 알아봅니다. |
| 2021년 10월 | [저장소 현대화](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/repository-modernization.html?lang=en) | 비디오 | 저장소 현대화, 변경 가능 및 변경할 수 없는 컨텐츠, 패키지 구조 및 repository modernizer CLI 도구에 대해 알아봅니다. |
| 2021년 10월 | [[!UICONTROL AEM 현대화 도구]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-modernization-tools.html?lang=en) | 비디오 | AEM [!UICONTROL 현대화 도구]를 사용하여 기존 AEM 프로젝트 및 컨텐츠를 Cloud Service 호환으로 AEM과 업그레이드하는 방법을 알아봅니다. |
| 2021년 10월 | [AEM 현대화 도구](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/introduction.html?lang=en) | 비디오 | AEM을 Cloud Service 구현으로 다르게 생각하는 방법을 알아봅니다. |
| 2021년 10월 | [모범 사례 분석기 및 Cloud Acceleration Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/bpa-and-cam.html?lang=en) | 비디오 | BPA(Best Practice Analyzer) 및 CAM(Cloud Acceleration Manager)이 AEM as a Cloud Service으로 마이그레이션하기 위한 사용자 정의 가이드를 제공하는 방법을 알아봅니다. |
| 2021년 10월 | [버전 기록 유지 관리](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/versions.html) | 비디오 | Adobe Workfront 및 Experience Manager [!UICONTROL Assets Essentials]을 통해 [!DNL Workfront] 문서 및 Assets Essentials 자산의 버전을 유지 관리하는 방법을 알아봅니다. |
| 2021년 10월 | [문서 보내기 및 자산 연결](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/link-send.html?lang=en) | 비디오 | Workfront 문서를 Assets Essentials에게 보내고, Assets Essentials 자산을 Workfront에 연결하는 방법을 알아봅니다. |
| 2021년 10월 | [통합 구성](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/configure.html?lang=en) | 비디오 | Adobe Workfront 및 Assets Essentials 통합을 구성하는 방법을 알아봅니다. |
| 2021년 10월 | [디지털 서명은 무엇입니까](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html?lang=en) | 비디오 | 전 세계에서 가장 엄격한 법적 규정을 준수하고 서명자의 신원을 최대한 보증하는 인증서 기반 디지털 서명에 대해 알아봅니다. |
| 2021년 10월 | [Adobe Analytics의 세그먼트 빌더](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-builder-overview.html?lang=en#) | 비디오 | Adobe Analytics에서 세그먼테이션을 사용하여 데이터를 분류하고 분류합니다. 이 비디오에서는 [!UICONTROL 세그먼트 빌더]를 살펴보고 기본 개요를 제공합니다. |
| 2021년 10월 | [메타데이터 매핑](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/map-metadata.html?lang=en) | 비디오 | Workfront 필드와 Assets Essentials 속성 간의 메타데이터 매핑을 구성하고, 매핑된 값을 표시하도록 Assets Essentials을 구성하는 방법을 알아봅니다. |

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

Adobe Campaign을 위한 최신 자습서 및 교육 과정

| 게시일 | 이름 | 유형 | 설명 |
| -----------| ---------- | ---------- | ---------- |
| 2021년 10월 | [비즈니스 사용자를 위한 Adobe Campaign V8을 사용하여 고급 캠페인 만들기](https://experienceleague.adobe.com/?recommended=Campaign-U-1.2021.1.v8) | 교육 과정 | Adobe Campaign V8을 사용하여 고급 마케팅 캠페인을 구성하고 실행하는 방법을 알아봅니다. 사전 요구 사항에 대해 알아보고, 고급 캠페인, 게재 및 구독을 빌드 및 구성합니다. |
| 2021년 10월 | [워크플로우에서 SOAP API 사용 - 소개](https://experienceleague.adobe.com/docs/campaign-learn/use-soap-apis/introduction.html?lang=en) | 튜토리얼 | API를 통해 받은 데이터를 기반으로 Adobe Campaign Soap API를 사용하고 고급 배달 워크플로우를 만드는 방법을 알아봅니다. |
| 2021년 10월 | [이벤트 만들기](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/journey-configuration/create-events.html?lang=en) | 튜토리얼 | 이벤트를 구성하고, 스트리밍 종단점 및 이벤트에 대한 페이로드를 지정하는 방법을 알아봅니다. |
| 2021년 10월 | [데이터 소스 구성](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/journey-configuration/configure-data-sources.html?lang=en) | 튜토리얼 | 데이터 소스의 의미와 Experience Platform 및 외부 데이터 소스를 구성하는 방법을 살펴봅니다. |
| 2021년 10월 | [사용 사례 - 버스트 메시지](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-journeys/use-case-burst-message.html?lang=en) | 튜토리얼 | 버스트 메시지에 적용할 수 있는 사용 사례를 이해합니다. 버스트 메시지에 대한 여정을 구성하는 방법 및 적용할 모범 사례를 알아봅니다. |

{style=&quot;table-layout:auto&quot;}

### Campaign 도움말 리소스

* Adobe Campaign v8: [도움말 센터](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html) - [릴리스 정보](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html) - [구현 안내서](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html)
* Adobe Campaign Standard: [Campaign Standard 설명서](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html) - [릴리스 정보](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [사용 방법 비디오](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html) - [릴리스 계획](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Campaign Classic v7 설명서](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html) - [릴리스 정보](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [사용 방법 비디오](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html) - [최신 설명서 업데이트](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html)
* Adobe Campaign 제어판: [설명서](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html) - [릴리스 정보](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=ko) - [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html) 방법 비디오

## ![아이콘](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

[!DNL Adobe Advertising Cloud]의 릴리스 정보.

* [ [!DNL Advertising Cloud DSP]의 새로운 기능](#adcloud-dsp)
* [ [!DNL Advertising Cloud Search]의 새로운 기능](#adcloud-search)

### [!DNL Advertising Cloud DSP]의 새로운 기능 {#adcloud-dsp}

마지막 업데이트: **2021년 9월 28일**

| 기능 | 설명 |
| ------- | ----------- |
| 캠페인 관리 보기 | 이제 [!UICONTROL 캠페인], [!UICONTROL 패키지], [!UICONTROL 배치] 및 [!UICONTROL 광고] 보기에 대한 사용자 지정 열 세트에서 &quot;[!UICONTROL 생성 날짜]&quot; 열을 사용할 수 있습니다. [!UICONTROL 만든 날짜]로 [!UICONTROL 배치] 및 [!UICONTROL 광고] 보기를 필터링할 수도 있습니다. |
| 프로그램 방식의 보장 거래 | (8월 릴리스) 이제 프로그램 방식으로 보장되는(PG) 거래를 위한 기본 배치에 대한 [!UICONTROL 최대 입찰]을 편집할 수 있습니다. 그러나 PG 계약에는 항상 고정된 CPM이 있으므로 국제 클라이언트만 통화 교환 비용을 계산하려면 [!UICONTROL 최대 입찰]을 편집해야 합니다. |
|  | (8 9월 릴리스) 이제 &quot;[!DNL FreeWheel Programmatic Guaranteed]&quot; 권한을 가진 사용자는 [!UICONTROL Ads] 보기 또는 [!UICONTROL 배치] 보기에서 [!DNL FreeWheel Programmatic Creative API]에 광고를 제출할 수 있습니다. 여전히 [!UICONTROL 거래] 보기에서 광고를 제출할 수 있습니다. |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud Search]의 새로운 기능 {#adcloud-search}

마지막 업데이트: **2021년 9월 28일**

| 기능 | 설명 |
| ------- | ----------- |
| Advertising Insights | 추가 인사이트는 베타 모드에서 사용할 수 있습니다. |

{style=&quot;table-layout:auto&quot;}

## ![아이콘](/assets/magento.png) [!DNL Commerce] (Magento) {#magento}

Adobe Commerce 릴리스 정보에 대한 다음 링크를 참조하십시오.

* [Adobe Commerce 및 Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Adobe Commerce용 클라우드 제품군](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

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
| 2021년 10월 | [디지털 서명이란 무엇입니까?](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html?lang=en) | 비디오 | Adobe Sign을 사용하여 전 세계 디지털 ID를 사용하는 방법을 알아봅니다. |
| 2021년 10월 | [새 보낸 사람을 위한 Adobe Sign 시작하기](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/new-sender.html) | 비디오 | Adobe Sign을 처음 사용하는 경우 이 자습서를 시작하는 것이 좋습니다. 이 포괄적인 자습서에서는 Adobe Sign을 사용하여 신속하게 시작하고 실행할 수 있는 모든 기본 사항에 중점을 둡니다. |
| 2021년 10월 | [PDF 주석을 InDesign에 로드](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/indesign.html) | 비디오 | 이 60초 비디오 자습서에서는 Acrobat 공유 검토 후 PDF 주석을 다시 InDesign에 로드하는 방법을 알아봅니다. 이 디지털 워크플로우는 기록 시간 내에 개정을 완료하는 데 도움이 됩니다. |
| 2021년 10월 | [ [!DNL Intesi Group] (자격이 있는)에서 디지털 ID 가져오기](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-qualified.html) | 비디오 | [!DNL Intesi] 그룹에서 인증된 디지털 서명 인증서를 가져오는 방법을 알아봅니다. 등록되고 ID가 확인되면 [!DNL Intesi] 그룹은 Adobe Sign 클라우드 서명을 적용하는 데 사용되는 디지털 ID를 문제로 보냅니다. |
| 2021년 10월 | [를 사용하여 서명 [!DNL Intesi Group]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-sign.html) | 비디오 | Interesi Group 디지털 ID를 사용하여 ID를 인증하고 문서에서 원격 디지털 서명(클라우드 서명)을 인증하는 방법을 알아봅니다. |
| 2021년 10월 | [ [!DNL Intesi Group] (고급)에서 디지털 ID 가져오기](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-advanced.html) | 비디오 | Interesi Group에서 고급 디지털 서명 인증서를 가져오는 방법을 알아봅니다. 등록되고 ID가 확인되면 Inteesi Group은 Adobe Sign 클라우드 서명을 적용하는 데 사용되는 디지털 ID를 사용하여 문제를 해결합니다. |
| 2021년 10월 | [를 사용하여 서명 [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-sign.html) | 비디오 | [!DNL Digidentity] 디지털 ID를 사용하여 ID를 인증하고 문서에서 원격 디지털 서명(클라우드 서명)을 인증하는 방법을 알아봅니다. |
| 2021년 10월 | [에서 디지털 ID 가져오기 [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-reg.html) | 비디오 | [!DNL Digidentity]에서 디지털 서명 인증서를 가져오는 방법을 알아봅니다. 등록되고 ID가 확인되면 [!DNL Digidentity]은(는) Adobe Sign 클라우드 서명을 적용하는 데 사용되는 디지털 ID에 문제가 됩니다. |
| 2021년 10월 | [두 PDF 간의 차이점 감지](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/compare.html) | 비디오 | 잘못된 버전의 파일을 사용하여 작업하는 실수를 하지 마십시오. 두 PDF 파일 간의 차이점을 빠르고 정확하게 감지하여 문서 검토 워크플로우를 향상시킬 수 있습니다. |
| 2021년 10월 | [Microsoft® Edge를 사용하여 탐색하는 동안 PDF 컨텐츠 만들기](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/edge.html) | 비디오 | Microsoft® Edge용 Adobe Acrobat 확장을 사용하여 웹 페이지를 PDF에 신속하게 보관하는 방법을 알아보십시오. 이 Windows 전용 도구는 연구 프로젝트와 웹 기반 정보를 오프라인으로 보는 데 유용합니다. |
| 2021년 10월 | [Outlook에서 전자 메일 메시지와 첨부 파일을 PDF로 변환](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/outlook.html) | 비디오 | 프로젝트를 위해 Outlook에서 전자 메일 메시지와 첨부 파일을 PDF에 보관하는 방법을 알아봅니다. 첨부 파일을 PDF로 자동으로 변환하여 보다 전문적이고 안전한 방식으로 정보를 전달하는 방법을 알아봅니다. 이 도구는 Windows에서만 사용할 수 있습니다. |

{style=&quot;table-layout:auto&quot;}

Document Cloud 도움말은 다음을 참조하십시오.

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=ko-KR)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=ko-KR)
* [Document Cloud 학습 및 지원](https://helpx.adobe.com/kr/support/document-cloud.html)

## ![아이콘](/assets/creative-cloud-24.png) Creative Cloud for enterprise {#creative-cloud}

최신 튜토리얼은 [Creative Cloud for Enterprise Tutorials](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=ko-KR)를 참조하십시오.
