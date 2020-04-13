---
title: Adobe Experience Cloud 릴리스 노트
description: Experience Cloud 릴리스 노트 템플릿
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 80852c2797ad1a26b6c4a806fa2cf3ef59f84707

---


# 빠른 액세스 - Adobe Experience Cloud 릴리스 노트 - 2020년 4월

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

(특정 솔루션 릴리스 날짜는 매우 다양합니다.)

* [Adobe 시스템 상태](#status)
* [Experience Cloud 인터페이스 및 핵심 서비스](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/ko-KR/target/using/release-notes/target-release-notes.html) (솔루션 도움말 페이지에 대한 링크)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/kr/primetime/user-guide.html) (솔루션 도움말 페이지에 대한 링크)

도움말 홈을 찾고 계십니까? [Adobe Experience Cloud 설명서](https://docs.adobe.com/content/help/ko-KR/experience-cloud/user-guides/home.html)를 참조하십시오.

## ![아이콘](/assets/adobe.png) Adobe 시스템 상태 {#status}

[!UICONTROL Adobe 시스템 상태]는 Adobe 클라우드 제품 및 서비스 중단, 중단 및 유지 관리 이벤트에 대한 자세한 정보, 상태 업데이트 및 이메일 알림을 제공합니다. [status.adobe.com](https://status.adobe.com/)에서 관련 정보를 확인하십시오.

**새로운 기능**

* Adobe ID를 사용하면 제품 서비스 및 추가 기능 수준까지 세부적으로 이벤트 알림을 구독할 수 있습니다. 또한 최신 릴리스에서 자체 구독 프로세스에서는 제품 이용 권한을 기반으로 제품 및 서비스를 선택할 것을 권장합니다. 따라서 구독을 만드는 데 필요한 의사 결정 또는 클릭 수를 줄여 구독 프로세스를 간소화해야 하며, 가장 중요한 것은 받은 편지함에 보다 관련성이 높은 알림을 전달하는 것입니다. [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)에서 시작해 보십시오.

**현재 사용할 수 있는 새로운 기능 및 향상된 기능**

| 기능 | 설명 |
| -----------| ---------- |
| 이용 권한을 기반으로 개인화된 구독 | <ul><li>사용자의 DX 권한에 따라 미리 선택된 구독 권장 사항</li><li>빠른 시각화를 위해 제품 목록 맨 위에 권장 구독이 강조 표시됩니다.</li><li>받은 이메일 알림은 사용자의 제품 권한에 관련됩니다.</li></ul> |
| 간편한 구독 관리 | <ul><li>**[!UICONTROL 구독]** 관리에는 제품 및 이벤트 구독을 모두 관리할 수 있는 새로운 사용자 경험이 있습니다.</li><li>제품 및 이벤트 구독을 별도로 보고 편집할 수 있는 새로운 옵션입니다.</li><li>삭제 **[!UICONTROL 옵션을]** 사용하면 제품 또는 이벤트 구독의 구독을 취소할 수 있습니다.</li><li>한 번의 클릭으로 **[!UICONTROL 모든]** 구독 취소 옵션을 제품 구독에 사용할 수 있습니다.</li><li>UX는 웹/모바일/태블릿 표면 및 로컬라이제이션(19개 언어)에서 지원됩니다.</li></ul> |

## ![아이콘](/assets/ec_appicon_24.png) Experience Cloud 인터페이스 및 핵심 서비스 {#ecloud}

관리 및 핵심 서비스(고객 속성, 대상, 트리거, 쿠키 등)를 비롯한 Experience Cloud 인터페이스의 새로운 기능 및 수정 사항:

* Experience Cloud [!UICONTROL 피드] 페이지는 더 이상 사용되지 않습니다. (EXC-8505)
* 새로운 브랜딩 요소를 반영하도록 Experience Cloud 로그인 페이지가 업데이트되었습니다. (EXC-10747)

제품 설명서는 [Experience Cloud](https://docs.adobe.com/content/help/ko-KR/core-services/interface/experience-cloud.html) 도움말을 참조하십시오.

### 통합 제품 도메인

Adobe는 모든 Experience Cloud 애플리케이션에서 사용자 경험을 통합하고 개선하기 위해 도메인 및 인터페이스 헤더를 업데이트하고 있습니다. 이러한 개선 사항은 작지만 중요한 방식으로 경험을 간소화하도록 설계되었습니다. 이러한 개선 사항은 현재 워크플로우를 변경하지 않습니다.

업데이트 내용은 다음과 같습니다.

* 새로운 솔루션 URL: `experience.adobe.com/<application name>`:
   * 모든 제품이 결국 이 URL 패턴을 채택합니다. 한 달 동안 새 URL이 유효한지 확인합니다.
   * 브라우저 지원: 지원되는 브라우저에는 [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] 및 [!DNL Opera](최신 버전)이(가) 포함됩니다. **참고:** Experience Cloud 인터페이스는 이러한 브라우저를 지원하지만 개별 솔루션은 모든 브라우저를 지원하지 않을 수 있습니다. (예: [Analytics](https://docs.adobe.com/content/help/ko-KR/analytics/admin/sys-reqs.html)는 [!DNL Opera]를 지원하지 않으며, [Target](https://docs.adobe.com/help/ko-KR/target/using/implement-target/before-implement/supported-browsers.html)은 [!DNL Safari]를 지원하지 않습니다.)
   * ([!DNL Safari] 전용) 도메인 변경으로 인해 [!DNL Safari]에 쿠키 문제가 발생할 수 있습니다. _개인 정보 보호 환경설정에서_&#x200B;사이트 간 추적 방지[!DNL Safari]를 선택 해제하면 도메인(및 모든 사이트 간 경험)에서 쿠키가 활성화되고 Experience Cloud가 이 새로운 도메인에서 작동할 수 있습니다.
* 조직 간 또는 다른 애플리케이션으로 쉽게 전환할 수 있습니다.
* 향상된 제품 도움말: [!UICONTROL Experience League]는 제품에 통합되어 있으므로 도움말 검색에 커뮤니티 포럼 및 비디오 컨텐츠의 결과도 포함됩니다. 이러한 변경 사항을 통해 더 많은 컨텐츠를 간편하게 이용하고 Experience Cloud를 최대한 활용할 수 있습니다. 또한 **[!UICONTROL 도움말]** > **[!UICONTROL 피드백]**&#x200B;을 클릭하여 문제를 보고하거나 Adobe와 아이디어를 공유할 수 있습니다.

## ![아이콘](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

[!UICONTROL Experience Platform], [!UICONTROL Experience Platform Launch], [!UICONTROL Identity Service,] Journey Orchestration, 모바일 서비스 및 보안 게시판의 릴리스 정보입니다.

### 여정 편성 {#journey}

Adobe Experience Platform을 사용하여 모든 개인의 요구 사항을 실시간으로 지능적으로 예측하여 경험 채널에서 규모에 맞게 개별 고객 여정을 편성합니다.

* [설명서](https://docs.adobe.com/content/help/ko-KR/journeys/using/journey-orchestration-home.html)
* [릴리스 노트](https://docs.adobe.com/content/help/ko-KR/journeys/using/release-notes/release-notes.html)
* [방법 비디오](https://docs.adobe.com/content/help/ko-KR/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services 및 Mobile SDK {#mobile}

Android 4.18.2(2020년 4월 3일):

* 앱 메시지:보안상의 이유로 [!UICONTROL SDK에서] 만든 WebViews는 이제 `setAllowFileAccess` false _로 설정됩니다_.

iOS 4.19.2(2020년 3월 24일):

* 일반:일부 [!DNL Target] 코드 누수가 수정되었습니다.

Unity 4.19.0(2020년 3월 10일):

* iOS [!UICONTROL 버전 4.19] .0 및 4.18.0 이상을 사용하도록 Unity 플러그인을 [!DNL Android]업데이트했습니다.
* 레퍼러 API에서 제공하는 URL을 처리할 [!DNL Android] 수 있도록 새 획득 방법이 [!DNL Google Play] 노출되었습니다.

### 추가 경험 플랫폼 릴리스 정보

* [Experience Platform Launch 릴리스 정보를 참조하십시오](https://docs.adobe.com/content/help/ko-KR/launch/using/intro/release-notes/current.html).
* [Experience Platform 릴리스 노트](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [보안 게시판 및 권고](https://helpx.adobe.com/kr/security.html)(모든 Adobe 제품)

## ![아이콘](/assets/analytics.png) [!DNL Analytics] {#analytics}

릴리스 날짜: **2020년 4월 16일**

* [Adobe Analytics의 새로운 기능, 향상된 기능 및 수정 내용](#aa-features)
* [Analytics 관리자에 대한 중요 공지](#aa-notices) (업데이트: 2020년 4월 7일)
* [AppMeasurement](#appm)
* [새로운 Analytics 자습서](#tutorials-analytics)

### Adobe Analytics의 새로운 기능, 향상된 기능 및 수정 내용 {#aa-features}

| 기능 | 설명 |
| -----------| ---------- |
| [!UICONTROL 고객 여정 분석]:데이터 [!UICONTROL 세트 채우기 자동화] | 이 새로운 옵션을 사용하면 고객 경로 분석에서 연결에 대한 모든 내역 데이터를 가져올 [!UICONTROL 수 있습니다]. (따라야 할 설명서) |
| Adobe Experience Edge [!UICONTROL 분석 지원] | 이제 Experience Edge로 전송된 데이터를 Analytics [!UICONTROL 로 전달할] 수 있습니다. |
| [!UICONTROL 작업 영역]:빈 상태에서 자유 형식 테이블 자동 작성 | 이전에는 구성 요소를 빈 프로젝트 또는 빈 패널에 직접 드롭할 수 없었습니다.자유 형식 테이블을 먼저 추가해야 했습니다. 이제 구성 요소를 빈 프로젝트 또는 패널에 직접 놓을 수 있으며 자유 형식 테이블이 권장 형식으로 자동으로 만들어집니다. 또한 빈 자유 형식 테이블로 함께 드롭될 때 혼합 구성 요소 유형(예: 차원 및 지표)이 처리되는 방식이 개선되었습니다. |

#### 분석 수정 사항

* Audience Manager에서 Analytics 세그먼트 데이터가 누락되었던 문제를 수정했습니다. (AN-206221)
* Data Sources 처리에서 [!UICONTROL 잘못된 날짜를] 표시하는 문제를 수정했습니다. (AN-213604)
* 분류 파일이 FTP에 제대로 업로드되지 않는 문제를 해결했습니다. (AN-214102)
* API 메서드에서 전체 응답을 반환하지 `Segments.Get` 않는 문제를 수정했습니다. (AN-206210)
* PDF 다운로드에서 테이블 라인 항목이 특수 문자로 변환되던 문제를 [!DNL Workspace] 수정했습니다. (AN-196153)
* Adobe Analytics API 1.4 호출이 제대로 작동하지 `visattrcustomeridcustomerattributes` 않는 문제를 수정했습니다. (AN-186873)
* 보고서에 데이터가 표시되지만 데이터 피드에서 누락되는 문제를 [!UICONTROL 수정했습니다]. (AN-211923)
* 제품 프로필 권한을 복사할 수 없는 [!UICONTROL 문제를] 수정했습니다. (AN-211113)
* Federated ID를 가진 사용자가 Report Builder에 로그인할 수 없던 문제를 해결했습니다. (AN-207750)
* AdWords 데이터가 [!UICONTROL 광고 분석에] 표시되지 않는 문제를 [!UICONTROL 수정했습니다]. (AN-213249)
* 트렌드 보기에 분류 데이터가 표시되지 않는 문제를 해결했습니다. (AN-212761)
* 세그먼트 관리자에서 잘못된 게시된 세그먼트 카운트가 발생하는 문제를 [!UICONTROL 수정했습니다]. (AN-213374)

#### 추가 Analytics 수정

AN-212151;AN-214343;AN-215017;AN-115525;AN-123869;AN-101871;AN-152580;AN-160480;AN-199299;AN-209486;AN-212961;AN-211539;AN-213095;AN-212653;AN-211826;AN-206948;AN-208607;AN-204286;AN-214401;AN-212130;AN-211943;AN-212709;AN-212833;AN-211550;AN-212977;AN-213422;AN-213450;AN-214528;AN-213827;AN-214094;AN-214153;AN-214234;AN-214355;AN-214427;AN-214642;AN-214691;AN-214924;AN-215080;AN-215212

### [!DNL Analytics] 관리자에 대한 중요 공지 {#aa-notices}

| 공지 | 추가 또는 업데이트 날짜 | 설명 |
| -----------| ---------- | ---------- |
| Change to how [!UICONTROL Entries/Exits] are calculated in [!UICONTROL Workspace] | 2020년 4월 7일 | In [!UICONTROL Analysis Workspace], as of March 2020, we have changed how the _None_ value interacts with [!UICONTROL Entries/Exits]. Because you can now turn _Nones_ on and off in [!UICONTROL Analysis Workspace], we apply the _None_ value after the entry or exit, whereas (for eVars) it used to be applied before. 예를 들어, 방문의 첫 번째 히트에 eVar에 대한 값이 없다고 가정하지만 두 번째 히트는 값이 없다고 가정합니다. In [!UICONTROL Reports &amp; Analytics] it will show up as _Unspecified_ for the Entry, but in [!UICONTROL Analysis Workspace] it will show up as the value on the second hit. |
| **[!UICONTROL 전환 수준]** 설정의 EOL | 2020년 3월 3일 | The non-functioning [Conversion Level](https://docs.adobe.com/content/help/ko-KR/analytics/admin/admin-tools/general-acct-settings-admin.html) setting in **[!UICONTROL Admin Tools]** > **[!UICONTROL Report Suites]** > **[!UICONTROL General Account Settings]** will be removed from the interface on March 12, 2020. |
| **[!UICONTROL 대시보드 아카이브]**&#x200B;의 EOL | 2020년 3월 27일 | [!UICONTROL Reports &amp; Analytics]의 **[!UICONTROL 대시보드 관리]** 아래에 있는 **[!UICONTROL 아카이브 보기]** 설정은 2020년 10월부터 더 이상 사용할 수 없습니다. |
| TLS 1.1 지원 종료 | 2019년 10월 3일 | 2020년 3월 31일까지 Adobe Analytics는 TLS 1.1에 대한 지원을 제거합니다. 이러한 변경은 최고 수준의 보안 표준을 유지하고 고객 데이터의 보안을 향상시키기 위한 지속적인 노력의 일환입니다. |
| 새 Adobe Analytics 도메인 | 2019년 12월 18일 | 2020년 1월 16일부터 Adobe Analytics가 새 도메인으로 이동합니다. `https://experience.adobe.com/analytics.`<br>**참고&#x200B;**: 이 변경 사항은 Adobe ID 또는 Enterprise ID로 Analytics에 액세스하는 모든 사용자에게 적용됩니다.<ul><li>도메인 변경으로 인해 Safari에서 Analytics를 로드할 때 쿠키 문제가 발생할 수 있습니다.  개인 정보 보호 기본 설정에서 _사이트 간 추적 방지_&#x200B;를 선택 해제하면 도메인(및 모든 사이트 간 경험)에서 쿠키가 활성화되고 Analytics가 이 새로운 Adobe Experience Cloud 도메인에서 작동할 수 있습니다. [!DNL Safari] 이 경우 [!DNL Safari] 사용자만 영향을 받기 때문에 다른 브라우저는 문제 없이 사용할 수 있습니다.</li><li>도메인 변경으로 인해 일부 고객은 [특정 경우](https://docs.adobe.com/content/help/ko-KR/analytics/analyze/activity-map/activity-map.html)에 [!UICONTROL Activity Map]이 중단될 수 있습니다.</li></ul> |
| 수명 종료 - Analytics 이전 API | 2020년 1월 9일 | 2020년 11월에 다음 Analytics 이전 API 서비스가 종료됩니다. 이러한 서비스를 사용하여 구축된 현재의 통합 기능은 작동하지 않습니다. <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>이전 OAuth 인증(OAuth 및 JWT)</li></ul>질문에 대한 답변과 진행 방법에 대한 지침을 제공하는 데 도움이 되도록 [이전 API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)를 제공했습니다. 이러한 서비스를 사용하는 API 통합은 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 또는 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)로 마이그레이션할 수 있습니다. 이전 OAuth 계정은 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 통합 계정으로 마이그레이션할 수 있으며, 이 계정은 1.4 Analytics API 및 2.0 Analytics API에 모두 액세스하는 데 사용할 수 있습니다. |
| 런던 및 싱가포르의 산호세 FTP Broker 종료 | 2020년 7월 | 런던 및 싱가포르의 고객을 위해 런던 또는 싱가포르와 산호세 데이터 센터 [ftp.omniture.com](ftp://ftp.omniture.com/) 간의 데이터 브로커링을 더 이상 지원하지 않습니다.<br/><ul><li>런던의 경우 [ftp3.omniture.com](ftp://ftp3.omniture.com/) 사용</li><li>싱가포르의 경우 [ftp4.omniture.com](ftp://ftp4.omniture.com/) 사용</li></ul> |
| Ad Hoc Analysis 생산 중단 | 2018년 8월 6일 | Adobe는 Ad Hoc Analysis를 종료할 예정이라고 발표했습니다. 수명 종료 날짜는 확정된 후 공유될 예정입니다. 자세한 내용은 [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)를 참조하십시오. |

### [!DNL AppMeasurement] {#appm}

[JavaScript 릴리스 노트의 AppMeasurement](https://docs.adobe.com/content/help/ko-KR/analytics/implementation/appmeasurement-updates.html)를 참조하십시오. 버전 2.20.0은 2020년 2월 5일에 릴리스되었습니다.

### 새로운 Analytics 자습서 {#tutorials-analytics}

| 컨텐츠 | 설명 |
| -----------| ---------- |
| [Adobe Analytics를 사용한 Adobe Labs(기술 미리 보기)](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/analytics-basics/adobe-labs-technology-previews.html) | Adobe Labs(기술 미리 보기)를 사용하면 신생 기술에 참여하거나 중요한 통찰력을 얻을 수 있으며 향후 [!DNL Analytics] 기능 개발 및 우선 순위에 영향을 줄 수 있습니다. |
| [향상된 Experience Cloud 대상 게시](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/experience-cloud/improved-experience-cloud-audience-publishing.html) | Experience Cloud 대상 [!UICONTROL 게시가 개선되었습니다]. 이제 대상자(세그먼트)를 게시하여 6배 더 빠르게 사용할 수 있도록 할 수 있습니다. 이렇게 하면 트래픽 및 세그먼트 크기에 따라 현재 지연 시간이 48시간에서 약 8시간으로 단축됩니다. |
| [분석 작업 공간의 여러 보고서 세트](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/multiple-report-suites-in-analysis-workspace.html) | 패널 수준에서 보고서 세트를 선택하여 단일 [!UICONTROL Workspace] 프로젝트에서 여러 보고서 세트를 분석할 수 있습니다. 이렇게 하면 여러 데이터 세트에서 나란히 패널 분석을 수행할 수 있습니다. |

제품 [설명서는 Adobe Analytics](https://docs.adobe.com/content/help/ko-KR/analytics/landing/home.html) 도움말 홈을 참조하십시오.

## ![아이콘](/assets/audience-manager.png) Audience Manager {#aam}

Adobe Audience Manager의 새로운 기능 및 수정 사항:

| 기능 | 설명 |
| -----------| ---------- |  
| [주요 고객 지원 문제](../support-issues/support-issues-overview.md) | 고객 지원 팀에서 가장 자주 받는 질문에 대한 답변이 포함된 새로운 섹션이 설명서 포털에 추가되었습니다. |

* Audience Lab의 테스트 [!UICONTROL 복제] 및 [!UICONTROL 할당 템플릿] 단추가 [!UICONTROL 작동하지 않는] 문제를 해결했습니다. (AAM-53388)
* 대상이 UUID를 [!UICONTROL 내보내도록] 구성되면 일치 비율 및 세그먼트 지정 가능 대상이  0으로 표시되는 문제를 수정했습니다. 이제 [!UICONTROL 일치 비율] 및 [!UICONTROL 세그먼트 지정 가능] 대상이 100%로 표시됩니다. (AAM-51615)
* 특수 문자가 포함된 트레이트 이름이 HTML로 두 번 인코딩되는 문제를 해결했습니다. (AAM-54001)
* 일부 사용자가 [!DNL Audience Manager] 사용자 인터페이스에서 다른 Adobe Experience Cloud 솔루션으로 전환할 수 없는 문제를 수정했습니다. (AAM-52917)
* 일부 사용자가 사람 기반 대상에 대해 SHA256 데이터 소스를 만들지 못하게 하는 문제를 해결했습니다. (AAM-53525)
* 인터페이스 전반에서 다양한 접근성 향상 (AAM-48986, AAM-49009, AAM-48984, AAM-48939, AAM-48940, AAM-48964, AAM-49032,AAM-49360)

## ![아이콘](/assets/aem.png) Experience Manager {#aem}

Adobe Experience Manager(AEM)의 새로운 기능, 수정 및 업데이트입니다. 안정성, 보안 및 성능 향상을 위해 최신 패치를 배포하려는 경우 온-프레미스 배포를 사용하는 것이 좋습니다.

### 사용자 도움말

* **AEM 뉴스레터**

   최신 Adobe Experience [Manager 뉴스레터를 참조하십시오](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html).

* **클라우드 서비스로 AEM 사용 - Dynamic Media Cloud 서비스 구성**

   Dynamic Media Cloud 서비스를 구성할 때 새로운 옵션을 사용할 수 있습니다.

   **선택적 게시** - 이 옵션을 선택하면 에셋이 보안 미리 보기만을 위해 자동으로 게시되며 공개 도메인에 전달을 위해 DMS7에 게시하지 않고도 AEM에 명시적으로 게시할 수 있습니다.

   Dynamic [Media Cloud 서비스 구성을 참조하십시오](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/config-dm.html#configuring-dynamic-media-cloud-services).

* **다이내믹 미디어 - 스마트 이미징**

   추가된 스마트 이미징 최적화를 설명하는 이미지 에셋 예를 비롯한 전체 스마트 이미징 도움말 항목이 새로운 정보로 업데이트되었습니다.

   스마트 [이미징을 참조하십시오](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/imaging-faq.html).

* **다이내믹 미디어 구성 - Scene7 모드**

   이제 도구 > 클라우드 서비스에 있는 Dynamic Media 구성 페이지에서 모든 컨텐츠 동기화 옵션을 **[!UICONTROL 사용할 수 있습니다]**.

   다이내믹 [미디어 구성 만들기를 참조하십시오](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/config-dms7.html#configuring-dynamic-media-cloud-services).

* **AEM Assets 브랜드 포털은 AEM Assets를 클라우드 서비스로 지원합니다.**

   이제 AEM Assets의 자산을 클라우드 서비스로 AEM Assets 브랜드 포털에 게시할 수 있습니다.

   브랜드 [포털과 함께 AEM 자산 구성](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html) 및 브랜드 포털에 [자산 게시를 참조하십시오](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/publish-to-brand-portal.html).

* **Adobe Asset Link 2.0 릴리스**

   Adobe Asset Link 2.0은 여러 AEM 환경에서 작업을 지원하고 AEM을 클라우드 서비스로 지원합니다. AEM 파섹

   See [Adobe Asset Link](https://helpx.adobe.com/kr/enterprise/using/adobe-asset-link.html).

### 새로운 Experience Manager 튜토리얼

| 컨텐츠 | 설명 |
| -----------| ---------- |  
| [로컬 디스패처 도구 설정](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/dispatcher-tools.html) | 로컬에서 Dispatcher 구성, 유효성 검사 및 시뮬레이션을 [!UICONTROL 활성화하는 방법에 대해] 알아봅니다. |
| [AEM 프로젝트용 개발 도구 설정](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/development-tools.html) | AEM(Adobe Experience Manager) 개발을 위해서는 최소한의 개발 도구를 설치하고 개발자 시스템에 설정해야 합니다. 이러한 도구는 AEM 프로젝트의 개발 및 빌드를 지원합니다. |
| [로컬 AEM 런타임 설정](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | AEM(Adobe Experience Manager)은 AEM을 클라우드 서비스 SDK의 QuickStart Jar로 사용하여 로컬에서 실행할 [!UICONTROL 수 있습니다]. 이를 통해 개발자는 소스 제어에 커밋하기 전에 사용자 지정 코드, 구성 및 컨텐츠를 배포하고 테스트하여 클라우드 서비스 환경으로 AEM에 배포할 수 있습니다. |
| [탐색](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/authoring/navigation.html) | AEM 자산 탐색에 대한 기본 사항을 살펴보십시오. |
| [버전](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/collaboration/versions.html) | AEM에서 자산 버전을 만들고 유지 관리하는 방법을 알아봅니다. |
| [AEM - [!DNL Magento] Commerce Integration [!UICONTROL Framework를 사용한 통합]](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/getting-started.html) | 이 비디오에서는 AEM과 AEM 간의 통합 설정을 안내합니다 [!DNL Magento]. |
| [AEM 아키텍처 스택 소개](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-architecture.html) | CIF 프로젝트 원형에서는 CIF 코어 구성 요소를 사용하는 고객 프로젝트의 시작점으로 최소한의 AEM(Adobe Experience Manager) CIF 프로젝트를 만듭니다. |
| [OSGi 소개](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-osgi.html) | Adobe Experience Manager의 기반이 되는 Java 애플리케이션을 위한 다이내믹한 모듈식 아키텍처인 OSGi를 소개합니다. |
| [JCR 파섹](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-jcr.html) | Adobe Experience Manager에서 사용하는 [JCR(Java Content Repository) 소개 |
| [Sling 소개](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-sling.html) | Adobe Experience [!DNL Sling]Manager의 기본 기술 스택에 포함된 오픈 소스 RESTful 웹 프레임워크에 대한 소개입니다. |
| [작성자 및 게시 계층 소개](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-author-publish.html) | Adobe Experience Manager [!UICONTROL 의] 아키텍처의 일부로 작성자  및 게시 계층에 대한 소개입니다. |
| [Dispatcher 소개](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-dispatcher.html) | AEM 아키텍처의 일부로 디스패처의 기능 및 기능에 대한 소개입니다. |
| [구성 요소 개발 소개](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/component-development.html) | Adobe Experience Manager Sites를 사용한 구성 요소 개발에 대한 개요입니다. 대화 상자, [!UICONTROL Sling 모델], [!UICONTROL HTL]스크립트 [!UICONTROL 및]클라이언트측 라이브러리에 대한 소개가 [!UICONTROL 포함되어 있습니다]. |
| [AEM 프로젝트 원형](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/developing/aem-project-archetype.html) | AEM Project에는 구현에 대한 모든 코드와 구성이 포함되어 있습니다. The AEM [!UICONTROL Project Archetype] creates a minimal, best-practices-based Adobe Experience Manager project as a starting point for your own AEM projects. |
| [핵심 구성 요소 이해](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/core-components-feature-video-understand.html) | AEM [!UICONTROL 코어] 구성 요소는 Adobe Experience Manager와 함께 사용할 표준 세트 구성 요소입니다. |
| [AEM Quickstart Jar 사용](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/developing/quickstart-jar.html) | AEM Quickstart jar를 사용하여 몇 분 만에 Adobe Experience Manager의 로컬 인스턴스를 설치하고 실행하는 방법을 [!UICONTROL 살펴봅니다]. |

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

### 새로운 Campaign Standard 자습서 {#tutorials-acs}

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

[!DNL Marketo Engage]는 리드 관리를 위한 완전한 솔루션이며, 복잡한 구매 여정의 모든 단계에서 고객 경험을 전환하여 고객 경험을 혁신하고자 하는 B2B 마케터입니다.

### 핵심 Marketo Engage 업데이트

자세한 내용은 [!DNL Marketo] 릴리스 노트를 [](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) 참조하십시오.

### 예정된 기능

다음 기능은 분기 전체에 걸쳐 릴리스됩니다.

| 기능 | 설명 |
|------|---------|
| [!DNL Bizible] | <ul><li>새로운 계정 기반 세분화</li><li>대시보드별 필터 저장</li><li>Bizible 대시보드를 PDF로 내보내기</li></ul> |
| 영업 연결 | Compose Window 및 Command Center 업데이트/개선 사항 |

### 공지

**Marketo Engage Success Center:** 2020년 2월 출시. Success Center는 Product Docs 및 Community를 검색하고 사용 방법 가이드를 실행하고 채택률 컨텐츠에 액세스하는 등 다양한 작업을 할 수 있는 제품 내 도움말 센터입니다. 참고: 이 기능은 ANZ에서 베타 버전으로 출시되며, 해당 분기 후반에 북미에 출시될 예정입니다.

### 사용 중단

* **자산 API &quot;_method&quot; 매개 변수:** 2020년 9월 이후, 자산 API 끝점은 더 이상 URI 길이 제한을 우회하기 `_method` 위해 POST 본문에 쿼리 매개 변수를 전달하지 않습니다.
* **Internet Explorer 지원 중단:** 2020년 7월 31일부터 Marketo Engage 사용자 인터페이스는 이제 Internet Explorer에서 지원되지 않습니다.

누적 릴리스 노트와 내역 릴리스 노트는 [Marketo 릴리스 노트](https://docs.marketo.com/x/CgA6Ag)를 참조하십시오.
