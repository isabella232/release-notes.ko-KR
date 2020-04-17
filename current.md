---
title: Adobe Experience Cloud 릴리스 노트
description: Experience Cloud 릴리스 노트 템플릿
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 16804e8f1eeb1d836b904c85a8c538077166242b

---


# Adobe Experience Cloud 릴리스 노트 - 2020년 4월

![배너](/assets/experience-cloud-banner-3.png)

[!DNL Adobe Experience Cloud]의 새로운 기능 및 수정 사항.

>[!IMPORTANT]
>
>이 페이지에는 출시 전 컨텐츠가 포함되어 있으며 계획된 출시 전에 변경될 수 있습니다.

>[!NOTE]
>
>예정된 릴리스에 대한 이메일 알림을 받으려면 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)
에 가입하십시오. 릴리스 후 게시된 새 정보는 발행 날짜로 표시됩니다.

**릴리스 날짜: 2020년 4월**

(특정 릴리스 날짜는 매우 다양합니다.)

* [Adobe 시스템 상태](#status)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) **(릴리스 날짜 변경 - 4월 15일 업데이트 참조)**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/ko-KR/target/using/release-notes/target-release-notes.html) (Target 도움말 페이지에 대한 링크)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/kr/primetime/user-guide.html) (Primetime 도움말 페이지 링크)

도움말 홈을 찾고 계십니까? [Adobe Experience Cloud 설명서](https://docs.adobe.com/content/help/ko-KR/experience-cloud/user-guides/home.html)를 참조하십시오.

## ![아이콘](/assets/adobe.png) Adobe 시스템 상태 {#status}

[!UICONTROL Adobe 시스템 상태]는 Adobe 클라우드 제품 및 서비스 중단, 중단 및 유지 관리 이벤트에 대한 자세한 정보, 상태 업데이트 및 이메일 알림을 제공합니다. [status.adobe.com](https://status.adobe.com/)에서 관련 정보를 확인하십시오.

**새로운 기능**

* Adobe ID를 사용하면 제품 서비스 및 추가 기능 수준까지 세부적으로 이벤트 알림을 구독할 수 있습니다. 또한 최신 릴리스의 자체 구독 프로세스에서는 제품 이용 권한에 따라 제품 및 서비스를 선택할 것을 권장합니다. 이 경우 구독을 만드는 데 필요한 의사 결정 또는 클릭 수를 줄여 구독 프로세스가 간소화되며, 무엇보다 가장 중요한 것은 받은 편지함에 더욱 관련성이 높은 알림이 전달된다는 것입니다. [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)에서 시작해 보십시오.

**현재 사용할 수 있는 새로운 기능 및 향상된 기능**

| 기능 | 설명 |
| -----------| ---------- |
| 이용 권한에 따라 개인화된 구독 | <ul><li>사용자의 DX 권한에 따라 미리 선택된 구독 권장 사항입니다.</li><li>권장 구독은 빠른 시각화를 위해 제품 목록 맨 위에 강조 표시됩니다.</li><li>받은 이메일 알림은 사용자의 제품 이용 권한과 관련된 것입니다.</li></ul> |
| 더욱 쉬워진 구독 관리 | <ul><li>**[!UICONTROL 구독 관리]**&#x200B;에는 제품 및 이벤트 구독을 모두 관리하는 새로운 사용자 환경이 있습니다.</li><li>제품 및 이벤트 구독을 별도로 보고 편집하는 새로운 옵션입니다.</li><li>**[!UICONTROL 삭제]** 옵션을 사용하면 제품 또는 이벤트 구독에서 구독을 취소할 수 있습니다.</li><li>원클릭 **[!UICONTROL 모든 구독 취소]** 옵션을 제품을 구독에 사용할 수 있습니다.</li><li>UX는 웹/모바일/태블릿 표면 및 지역화(19개 언어)에서 지원됩니다.</li></ul> |

## ![아이콘](/assets/ec_appicon_24.png) Experience Cloud 인터페이스 {#ecloud}

Experience Cloud 인터페이스의 새로운 기능 및 수정 사항:

* Experience Cloud [!UICONTROL 피드] 페이지는 더 이상 사용되지 않습니다. (EXC-8505)
* 새로운 브랜딩 요소를 반영하도록 Experience Cloud 로그인 페이지가 업데이트되었습니다. (EXC-10747)

제품 설명서는 [Experience Cloud](https://docs.adobe.com/content/help/ko-KR/core-services/interface/experience-cloud.html) 도움말을 참조하십시오.

### 통합 제품 도메인

Adobe는 모든 Experience Cloud 애플리케이션에서 사용자 경험을 통합하고 개선하기 위해 도메인 및 인터페이스 헤더를 업데이트하고 있습니다. 이러한 개선 사항은 작지만 중요한 방식으로 경험을 간소화하도록 설계되었습니다. 이러한 개선 사항은 현재 워크플로우를 변경하지 않습니다.

업데이트 내용은 다음과 같습니다.

* 새 응용 프로그램 URL: `experience.adobe.com/<application name>`:
   * 모든 제품이 결국 이 URL 패턴을 채택합니다. 한 달 동안 새 URL이 유효한지 확인합니다.
   * 브라우저 지원: 지원되는 브라우저에는 [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] 및 [!DNL Opera](최신 버전)이(가) 포함됩니다. **참고:** Experience Cloud 인터페이스는 이러한 브라우저를 지원하지만 개별 애플리케이션은 모든 브라우저를 지원하지 않을 수 있습니다. (예: [Analytics](https://docs.adobe.com/content/help/ko-KR/analytics/admin/sys-reqs.html)는 [!DNL Opera]를 지원하지 않으며, [Target](https://docs.adobe.com/help/ko-KR/target/using/implement-target/before-implement/supported-browsers.html)은 [!DNL Safari]를 지원하지 않습니다.)
   * ([!DNL Safari] 전용) 도메인 변경으로 인해 [!DNL Safari]에 쿠키 문제가 발생할 수 있습니다. _개인 정보 보호 환경설정에서_&#x200B;사이트 간 추적 방지[!DNL Safari]를 선택 해제하면 도메인(및 모든 사이트 간 경험)에서 쿠키가 활성화되고 Experience Cloud가 이 새로운 도메인에서 작동할 수 있습니다.
* 조직 간 또는 다른 애플리케이션으로 쉽게 전환할 수 있습니다.
* 향상된 제품 도움말: [!UICONTROL Experience League]는 제품에 통합되어 있으므로 도움말 검색에 커뮤니티 포럼 및 비디오 컨텐츠의 결과도 포함됩니다. 이러한 변경 사항을 통해 더 많은 컨텐츠를 간편하게 이용하고 Experience Cloud를 최대한 활용할 수 있습니다. 또한 **[!UICONTROL 도움말]** > **[!UICONTROL 피드백]**&#x200B;을 클릭하여 문제를 보고하거나 Adobe와 아이디어를 공유할 수 있습니다.

## ![아이콘](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Offers [!DNL Experience Platform,] , [!DNL Experience Platform Launch,] Journey Orchestration [!UICONTROL , PlacesPlacesPlaces, Mobile Services], Security 게시판을 비롯한 릴리스 노트입니다.

### 여정 편성 {#journey}

Adobe Experience Platform을 사용하여 모든 개인의 요구 사항을 실시간으로 지능적으로 예측하여 경험 채널에서 규모에 맞게 개별 고객 여정을 편성합니다.

* [설명서](https://docs.adobe.com/content/help/ko-KR/journeys/using/journey-orchestration-home.html)
* [릴리스 노트](https://docs.adobe.com/content/help/ko-KR/journeys/using/release-notes/release-notes.html)
* [방법 비디오](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services 및 Mobile SDK {#mobile}

Android 4.18.2(2020년 4월 3일):

* 인앱 메시지: 보안상의 이유로 SDK에서 만든 [!UICONTROL WebViews]는 이제 속성이 `setAllowFileAccess`_false_&#x200B;로 설정되어 있습니다.

iOS 4.19.2(2020년 3월 24일):

* 일반: [!DNL Target]코드에서 일부 누수가 수정되었습니다.

Unity 4.19.0(2020년 3월 10일):

* iOS 버전 4.19.0 및 4.18.0 또는 [!DNL Android]를 사용하도록 [!UICONTROL Unity 플러그인]을 업데이트했습니다.
* [!DNL Google Play]레퍼러 API에서 제공하는 URL을 처리할 수 있도록 [!DNL Android]에 대한 새 획득 방법이 노출되었습니다.

### 추가 환경 플랫폼 릴리스 정보

* [Experience Platform Launch 릴리스 노트](https://docs.adobe.com/content/help/ko-KR/launch/using/intro/release-notes/current.html).
* [Experience Platform 릴리스 노트](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [보안 게시판 및 권고](https://helpx.adobe.com/kr/security.html) (모든 Adobe 제품)

## ![아이콘](/assets/analytics.png) [!DNL Analytics] {#analytics}

>[!IMPORTANT]
>
>Adobe Analytics 4월 유지 관리 릴리스는 2020년 5월 21일로 옮겨졌습니다. 최신 Analytics 릴리스 정보는 [3월 릴리스 노트](c-legacy-releases/2020/03122020.md)를 참조하십시오.

* [Customer Journey Analytics](#cust-journey)
<!--* [New features in Adobe Analytics](#aa-features)-->
* [Analytics 관리자를 대상으로 한 중요 공지](#aa-notices)(업데이트 날짜: 2020년 4월 7일)
* [AppMeasurement](#appm)
* [새로운 Analytics 자습서](#tutorials-analytics)

### Customer Journey Analytics {#cust-journey}

| 기능 | 설명 |
| -----------| ---------- |
| [!UICONTROL Customer Journey Analytics]: 자동화된 데이터 세트 채우기 | 이 새 옵션을 사용하면 [!UICONTROL Customer Journey Analytics]에서 연결에 대한 모든 이전 데이터를 가져올 수 있습니다. [추가 정보](https://docs.adobe.com/content/help/ko-KR/analytics-platform/using/cja-connections/create-connection.html) |

<!--### New features in Adobe Analytics {#aa-features}

| Feature    | Description  |
| -----------| ---------- |
|Analytics support for [!UICONTROL Experience Edge] |You can now forward data that was sent to [!UICONTROL Experience Edge] to Analytics.|
 |[!UICONTROL Workspace]: Automatically build Freeform Tables from a blank state|Previously, you could not drop components directly into a blank project or blank panel; you had to add a freeform table first. You can now drop components directly into a blank project or panel, and a freeform table will automatically be built for you in a recommended format. Additionally, improvements were made to how mixed component types (e.g. dimensions & metrics) are handled when dropped into a blank freeform table together.|

#### Analytics fixes

* Fixed an issue that caused missing Analytics segment data in Audience Manager. (AN-206221)
* Fixed an issue with [!UICONTROL Data Sources] processing showing the wrong dates. (AN-213604)
* Fixed an issue with classification files not getting uploaded to FTP properly. (AN-214102)
* Fixed an issue with the API method `Segments.Get` not returning a full response. (AN-206210)
* Fixed an issue where table line items were converted to special characters in [!DNL Workspace] PDF download. (AN-196153)
* Fixed an issue with Adobe Analytics API 1.4 call `visattrcustomeridcustomerattributes` not working properly. (AN-186873)
* Fixed an issue with data appearing in reports but missing from the [!UICONTROL Data Feed]. (AN-211923)
* Fixed an issue with being unable to copy [!UICONTROL Product Profile] permissions. (AN-211113)
* Fixed an issue where users with Federated IDs were not able to log in to Report Builder. (AN-207750)
* Fixed an issue with [!UICONTROL AdWords] data not showing in [!UICONTROL Advertising Analytics]. (AN-213249)
* Fixed an issue where classification data did not display in the trended view. (AN-212761)
* Fixed an issue that caused an incorrect published segment count in the [!UICONTROL Segment Manager]. (AN-213374)

#### Additional Analytics fixes

AN-212151; AN-214343; AN-215017; AN-115525; AN-123869; AN-101871; AN-152580; AN-160480; AN-199299; AN-209486; AN-212961; AN-211539; AN-213095; AN-212653; AN-211826; AN-206948; AN-208607; AN-204286; AN-214401; AN-212130; AN-211943; AN-212709; AN-212833; AN-211550; AN-212977; AN-213422; AN-213450; AN-214528; AN-213827; AN-214094; AN-214153; AN-214234; AN-214355; AN-214427; AN-214642; AN-214691; AN-214924; AN-215080; AN-215212 -->

### [!DNL Analytics] 관리자에 대한 중요 공지 {#aa-notices}

| 공지 | 추가 또는 업데이트 날짜 | 설명 |
| -----------| ---------- | ---------- |
| [!UICONTROL Workspace]에서 [!UICONTROL 시작/종료 수]를 계산하는 방법 변경 | 2020년 4월 7일 | 2020년 3월 현재 [!UICONTROL Analysis Workspace]에서 _없음_ 값이 [!UICONTROL 시작/종료]와 상호 작용하는 방식을 변경했습니다. 이제 _Analysis Workspace_&#x200B;에서 [!UICONTROL 없음]을 켜거나 끌 수 있으므로 시작 또는 종료 후에 _없음_&#x200B;을 적용하지만 기존에는(eVars의 경우) 이전에 적용되었습니다. 예를 들어, 방문의 첫 번째 히트에는 eVar에 대한 값이 없다고 가정하지만 두 번째 히트에는 값이 있다고 가정합니다. [!UICONTROL Reports &amp; Analytics]에서는 시작에 대해 _지정되지 않음_&#x200B;으로 표시되지만 [!UICONTROL Analysis Workspace]에서는 두 번째 히트에 대한 값으로 표시됩니다. |
| **[!UICONTROL 전환 수준]** 설정의 EOL | 2020년 3월 3일 | [관리 도구](https://docs.adobe.com/content/help/ko-KR/analytics/admin/admin-tools/general-acct-settings-admin.html) > **[!UICONTROL 보고서 세트]** > **[!UICONTROL 일반 계정 설정]**&#x200B;에서 작동하지 않는 **[!UICONTROL 전환 수준]** 설정은 2020년 3월 12일에 인터페이스에서 제거됩니다. |
| **[!UICONTROL 대시보드 아카이브]**&#x200B;의 EOL | 2020년 3월 27일 | [!UICONTROL Reports &amp; Analytics]의 **[!UICONTROL 대시보드 관리]** 아래에 있는 **[!UICONTROL 아카이브 보기]** 설정은 2020년 10월부터 더 이상 사용할 수 없습니다. |
| TLS 1.1 지원 종료 | 2019년 10월 3일 | 2020년 3월 31일까지 Adobe Analytics는 TLS 1.1에 대한 지원을 제거합니다. 이러한 변경은 최고 수준의 보안 표준을 유지하고 고객 데이터의 보안을 향상시키기 위한 지속적인 노력의 일환입니다. |
| 새 Adobe Analytics 도메인 | 2019년 12월 18일 | 2020년 1월 16일부터 Adobe Analytics가 새 도메인으로 이동합니다. `https://experience.adobe.com/analytics.`<br>**참고&#x200B;**: 이 변경 사항은 Adobe ID 또는 Enterprise ID로 Analytics에 액세스하는 모든 사용자에게 적용됩니다.<ul><li>도메인 변경으로 인해 Safari에서 Analytics를 로드할 때 쿠키 문제가 발생할 수 있습니다.  개인 정보 보호 기본 설정에서 _사이트 간 추적 방지_&#x200B;를 선택 해제하면 도메인(및 모든 사이트 간 경험)에서 쿠키가 활성화되고 Analytics가 이 새로운 Adobe Experience Cloud 도메인에서 작동할 수 있습니다. [!DNL Safari] 이 경우 [!DNL Safari] 사용자만 영향을 받기 때문에 다른 브라우저는 문제 없이 사용할 수 있습니다.</li><li>도메인 변경으로 인해 일부 고객은 [특정 경우](https://docs.adobe.com/content/help/ko-KR/analytics/analyze/activity-map/activity-map.html)에 [!UICONTROL Activity Map]이 중단될 수 있습니다.</li></ul> |
| 수명 종료 - Analytics 이전 API | 2020년 1월 9일 | 2020년 11월에 다음 Analytics 이전 API 서비스가 종료됩니다. 이러한 서비스를 사용하여 구축된 현재의 통합 기능은 작동하지 않습니다. <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>이전 OAuth 인증(OAuth 및 JWT)</li></ul>질문에 대한 답변과 진행 방법에 대한 지침을 제공하는 데 도움이 되도록 [이전 API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)를 제공했습니다. 이러한 서비스를 사용하는 API 통합은 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 또는 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)로 마이그레이션할 수 있습니다. 이전 OAuth 계정은 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 통합 계정으로 마이그레이션할 수 있으며, 이 계정은 1.4 Analytics API 및 2.0 Analytics API에 모두 액세스하는 데 사용할 수 있습니다. |
| 런던 및 싱가포르의 산호세 FTP Broker 종료 | 2020년 7월 | 런던 및 싱가포르의 고객을 위해 런던 또는 싱가포르와 산호세 데이터 센터 [ftp.omniture.com](ftp://ftp.omniture.com/) 간의 데이터 브로커링을 더 이상 지원하지 않습니다.<br/><ul><li>런던의 경우 [ftp3.omniture.com](ftp://ftp3.omniture.com/) 사용</li><li>싱가포르의 경우 [ftp4.omniture.com](ftp://ftp4.omniture.com/) 사용</li></ul> |
| Ad Hoc Analysis 생산 중단 | 2018년 8월 6일 | Adobe는 Ad Hoc Analysis를 종료할 예정이라고 발표했습니다. 수명 종료 날짜는 확정된 후 공유될 예정입니다. 자세한 내용은 [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)를 참조하십시오. |

### [!DNL AppMeasurement] {#appm}

[JavaScript 릴리스 노트의 AppMeasurement](https://docs.adobe.com/content/help/ko-KR/analytics/implementation/appmeasurement-updates.html)를 참조하십시오. 버전 2.20.0은 2020년 2월 5일에 릴리스되었습니다.

### 새로운 Analytics 자습서{#tutorials-analytics}

| 컨텐츠 | 설명 |
| -----------| ---------- |
| [Adobe Analytics를 사용한 Adobe Labs(기술 미리 보기)](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/analytics-basics/adobe-labs-technology-previews.html) | Adobe Labs(기술 미리 보기)를 사용하면 신생 기술에 참여하거나 중요한 인사이트를 찾고 향후 [!DNL Analytics]기능 개발 및 우선순위에 영향을 줄 수 있습니다. |
| [향상된 Experience Cloud 대상자 게시](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/experience-cloud/improved-experience-cloud-audience-publishing.html) | [!UICONTROL Experience Cloud 대상자 게시]가 개선되었습니다. 이제 대상자(세그먼트)를 게시하여 6배 더 빠르게 사용하도록 할 수 있습니다. 이렇게 하면 트래픽 및 세그먼트 크기에 따라 현재 지연 시간이 48시간에서 약 8시간으로 단축됩니다. |
| [Analysis Workspace의 여러 보고서 세트](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/multiple-report-suites-in-analysis-workspace.html) | 패널 수준에서 보고서 세트를 선택하여 단일 [!UICONTROL Workspace] 프로젝트의 여러 보고서 세트를 분석할 수 있습니다. 이렇게 하면 여러 데이터 세트에서 나란히 패널 분석을 수행할 수 있습니다. |

제품 설명서에 대해서는 [Adobe Analytics 도움말 홈](https://docs.adobe.com/content/help/ko-KR/analytics/landing/home.html)을 참조하십시오.

## ![아이콘](/assets/audience-manager.png) Audience Manager{#aam}

Adobe Audience Manager의 새로운 기능 및 수정 사항:

| 기능 | 설명 |
| -----------| ---------- |  
| [주요 고객 지원 문제](https://docs.adobe.com/content/help/en/audience-manager/user-guide/top-support-issues/support-issues-overview.html) | 고객 지원 팀에서 가장 자주 받는 질문에 대한 답변이 포함된 새로운 섹션을 설명서 포털에 추가했습니다. |

* 모바일 디바이스 ID가 포함된 세그먼트에 대한 [주소 지정 가능한 고객](https://docs.adobe.com/content/help/ko-KR/audience-manager/user-guide/features/addressable-audiences.html)에 대해 부정확하게 보고하는 문제를 수정했습니다. 이 업데이트 후에, [주소 지정 가능한 고객](https://docs.adobe.com/content/help/ko-KR/audience-manager/user-guide/features/addressable-audiences.html)이 증가할 수도 있습니다.
* [!UICONTROL Audience Lab]의 [!UICONTROL 중복 테스트] 및 [!UICONTROL 중복 할당 템플릿] 단추가 작동하지 않는 문제가 해결되었습니다. (AAM-53388)
* 대상이 UUID를 내보내도록 구성되면 [!UICONTROL 일치율] 및 [!UICONTROL 세그먼트 주소 지정 가능 대상]이 0으로 표시되는 문제가 해결되었습니다. 이제 [!UICONTROL 일치율] 및 [!UICONTROL 세그먼트 주소 지정 가능 대상]이 100%로 표시됩니다. (AAM-51615)
* 특수 문자가 포함된 트레이트 이름이 HTML로 두 번 인코딩되는 문제가 해결되었습니다. (AAM-54001)
* Fixed an issue blocking some users from switching to other Adobe Experience Cloud applications from the [!DNL Audience Manager] user interface. (AAM-52917)
* 일부 사용자가 사람 기반 대상의 SHA256 데이터 소스를 만들지 못하는 문제가 해결되었습니다. (AAM-53525)
* 인터페이스에서 여러 액세스 가능성이 개선되었습니다. (AAM-48986, AAM-49009, AAM-48984, AAM-48939, AAM-48940, AAM-48964, AAM-49032,AAM-49360)

## ![아이콘](/assets/aem.png) Experience Manager {#aem}

Adobe Experience Manager(AEM)의 새로운 기능, 수정 및 업데이트입니다. 안정성, 보안 및 성능 향상을 위해 최신 패치를 배포하려는 경우 온-프레미스 배포를 사용하는 것이 좋습니다.

### 사용자 도움말

* **AEM 뉴스레터**

   최신 [Adobe Experience Manager 뉴스레터](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html)를 참조하십시오.

* **클라우드 서비스로서의 AEM - 다이내믹 미디어 클라우드 서비스 구성**

   다이내믹 미디어 클라우드 서비스를 구성할 때 새로운 옵션을 사용할 수 있습니다.

   **선택적 게시** - 이 옵션을 선택하면 자산이 보안 미리 보기 전용으로 자동으로 게시되며 공개 도메인에 전달을 위해 DMS7에 게시하지 않고도 AEM에 명시적으로 게시할 수 있습니다.

   [다이내믹 미디어 클라우드 서비스 구성](https://docs.adobe.com/content/help/ko-KR/experience-manager-cloud-service/assets/dynamicmedia/config-dm.html#configuring-dynamic-media-cloud-services)을 참조하십시오.

* **다이내믹 미디어 - 스마트 이미징**

   추가된 스마트 이미징 최적화를 설명하는 이미지 자산 예를 포함하여 전체 스마트 이미징 도움말 항목이 새로운 정보로 업데이트되었습니다.

   [스마트 이미징](https://docs.adobe.com/content/help/ko-KR/experience-manager-65/assets/dynamic/imaging-faq.html)을 참조하십시오.

* **다이내믹 미디어 구성 - Scene7 모드**

   이제 **[!UICONTROL 도구 > 클라우드 서비스]**&#x200B;에 있는 [다이내믹 미디어 구성] 페이지에서 새 모든 콘텐츠 동기화 옵션을 사용할 수 있습니다.

   [다이내믹 미디어 구성 만들기](https://docs.adobe.com/content/help/ko-KR/experience-manager-65/assets/dynamic/config-dms7.html#configuring-dynamic-media-cloud-services)를 참조하십시오.

* **AEM Assets Brand Portal에서 AEM Assets를 클라우드 서비스로 지원**

   이제 AEM Assets의 자산을 클라우드 서비스로 AEM Assets Brand Portal에 게시할 수 있습니다.

   [Brand Portal로 AEM Assets 구성](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html) 및 [Brand Portal에 자산 게시](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/publish-to-brand-portal.html)를 참조하십시오.

* **Adobe Asset Link 2.0 릴리스**

   Adobe Asset Link 2.0은 여러 AEM 환경에서 작업을 지원하고 AEM을 클라우드 서비스로 지원합니다. AEM은 Adobe Asset Link를 사용하여 자산이 폴더에 업로드되면 자산 처리 워크플로우 자동 실행을 구성해야 하는 마케터의 요구 사항을 지원합니다.

   [Adobe Asset Link](https://helpx.adobe.com/kr/enterprise/using/adobe-asset-link.html)를 참조하십시오.

### 새로운 Experience Manager 자습서

| 컨텐츠 | 설명 |
| -----------| ---------- |  
| [로컬 Dispatcher 도구 설정](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/dispatcher-tools.html) | [!UICONTROL Dispatcher]를 로컬에서 구성, 유효성 검사 및 시뮬레이션을 용이하게 하는 방법에 대해 알아봅니다. |
| [AEM 프로젝트용 개발 도구 설정](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/development-tools.html) | AEM(Adobe Experience Manager) 개발을 위해 최소한의 개발 도구 세트를 설치하고 개발자 시스템에 설정해야 합니다. 이러한 도구는 AEM 프로젝트의 개발 및 빌드를 지원합니다. |
| [로컬 AEM 런타임 설정](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | AEM(Adobe Experience Manager)은 AEM을 클라우드 서비스 SDK의 [!UICONTROL QuickStart Jar]로 사용하여 로컬에서 실행할 수 있습니다. 이 경우 개발자는 소스 제어에 커밋하기 전에 사용자 지정 코드, 구성 및 콘텐츠를 배포하고 테스트하고, AEM에 클라우드 서비스 환경으로 배포할 수 있습니다. |
| [탐색](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/authoring/navigation.html) | AEM Assets 탐색에 대한 기본 사항을 살펴보십시오. |
| [버전](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/collaboration/versions.html) | AEM에서 자산 버전을 만들고 유지 관리하는 방법을 알아봅니다. |
| [AEM - [!DNL Magento] [!UICONTROL Commerce Integration Framework]를 사용하여 통합](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/getting-started.html) | 이 비디오에는 AEM과 [!DNL Magento]간의 통합 설정을 안내합니다. |
| [AEM 아키텍처 스택 소개](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-architecture.html) | CIF 프로젝트 원형은 CIF 코어 구성 요소를 사용하여 고객 프로젝트의 시작점으로 최소 AEM(Adobe Experience Manager) CIF 프로젝트를 만듭니다. |
| [OSGi 소개](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-osgi.html) | Adobe Experience Manager의 기반이 되는 Java 애플리케이션의 동적 모듈식 아키텍처인 OSGi를 소개합니다. |
| [JCR(Java Content Repository) 소개](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-jcr.html) | Adobe Experience Manager에서 사용하는 JCR(Java Content Repository)을 소개합니다. |
| [Sling 소개](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-sling.html) | Adobe Experience Manager의 기본 기술 스택에 포함된 오픈 소스 RESTful 웹 프레임워크인 [!DNL Sling]을 소개합니다. |
| [작성자 및 게시 계층 소개](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-author-publish.html) | Adobe Experience Manager의 아키텍처의 일부로 [!UICONTROL 작성자] 및 [!UICONTROL 게시] 계층을 소개합니다. |
| [Dispatcher 소개](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-dispatcher.html) | AEM 아키텍처의 일부로 Dispatcher의 기능 및 특징을 소개합니다. |
| [구성 요소 개발 소개](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/component-development.html) | Adobe Experience Manager Sites를 사용한 구성 요소 개발에 대한 개요입니다. [!UICONTROL 대화 상자], [!UICONTROL Sling 모델], [!UICONTROL HTL스크립트], 및 [!UICONTROL 클라이언트측 라이브러리]에 대한 소개가 포함되어 있습니다. |
| [AEM 프로젝트 원형](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/developing/aem-project-archetype.html) | AEM Project에는 구현에 대한 모든 코드와 구성이 포함되어 있습니다. AEM [!UICONTROL 프로젝트 원형]은 고유한 AEM 프로젝트의 시작점으로 최소한의 우수 사례 기반 Adobe Experience Manager 프로젝트를 만듭니다. |
| [코어 구성 요소 이해](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/core-components-feature-video-understand.html) | AEM [!UICONTROL 코어 구성 요소]는 Adobe Experience Manager에서 사용할 표준 구성 요소 세트입니다. |
| [AEM Quickstart Jar 사용](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/developing/quickstart-jar.html) | [!UICONTROL AEM Quickstart jar]를 사용하여 몇 분 안에 Adobe Experience Manager의 로컬 인스턴스를 설치하고 실행하는 방법을 살펴봅니다. |

### 추가 도움말 리소스

* [AEM을 클라우드 서비스로 사용](https://docs.adobe.com/content/help/ko-KR/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 학습 및 지원 홈](https://helpx.adobe.com/kr/support/experience-manager/6-5.html)
* [AEM 6.4 학습 및 지원 홈](https://helpx.adobe.com/kr/support/experience-manager/6-4.html)
* [AEM 6.3 학습 및 지원 홈](https://helpx.adobe.com/kr/support/experience-manager/6-3.html)
* [AEM 6.2 학습 및 지원 홈](https://helpx.adobe.com/kr/support/experience-manager/6-2.html)
* [Cloud Manager 사용 안내서](https://helpx.adobe.com/kr/experience-manager/cloud-manager/user-guide.html)
* [이전 버전의 AEM 설명서](https://helpx.adobe.com/kr/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic 도움말 홈](https://docs.adobe.com/content/help/ko-KR/dynamic-media-classic/using/home.html)
* [Dynamic Media 릴리스 노트](https://marketing.adobe.com/resources/help/ko_KR/s7/release_notes/index.html)
* [Livefyre 릴리스 노트](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## ![아이콘](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign은 온라인 및 오프라인 마케팅 채널 간에 직관적이고, 자동화된 방식으로 일대일 메시지를 제공합니다. 이제 고객이 습관 및 선호도에 따라 결정된 작업 환경을 통해 원하는 사항을 예측할 수 있습니다.

### Campaign Standard

* [Adobe Campaign Standard 20.2](https://docs.adobe.com/content/help/ko-KR/campaign-standard/using/release-notes/release-notes.html)

### 새로운 Campaign Standard 자습서{#tutorials-acs}

| 컨텐츠 | 설명 |
| -----------| ---------- |  
| [프로필 대체 - 타깃팅된 프로필을 사용하여 이메일 메시지 테스트](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/communication-channels/email/profile-substitution.html) | 프로필 대체 기능을 사용하여 이메일 메시지를 테스트합니다. |

### 추가 캠페인 도움말 리소스

* Adobe Campaign Standard: [설명서](https://helpx.adobe.com/kr/support/campaign/standard.html) - [릴리스 노트](https://docs.adobe.com/content/help/ko-KR/campaign-standard/using/release-notes/release-notes.html) - [기능 비디오](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [릴리스 계획](https://helpx.adobe.com/kr/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [설명서](https://helpx.adobe.com/kr/support/campaign/classic.html) - [릴리스 노트](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [기능 비디오](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign 제어판: [설명서](https://docs.adobe.com/content/help/ko-KR/control-panel/using/control-panel-home.html) - [릴리스 노트](https://docs.adobe.com/content/help/ko-KR/control-panel/using/release-notes.html)

<!-- ## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Advertising Cloud release notes. -->

## ![아이콘](/assets/magento.png) [!DNL Magento] {#magento}

Magento 릴리스 노트에 대해서는 다음을 참조하십시오.

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![아이콘](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] 는 리드 관리를 위한 완벽한 애플리케이션이며 B2B 마케터는 복잡한 구매 경로의 모든 단계에서 고객의 경험을 혁신하고자 합니다.

### 핵심 Marketo Engage 업데이트

자세한 내용은 [!DNL Marketo] [릴리스 노트](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720)를 참조하십시오.

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
