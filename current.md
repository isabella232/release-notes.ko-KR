---
title: Adobe Experience Cloud 릴리스 노트
description: Experience Cloud 릴리스 노트 템플릿
doc-type: release notes
last-update: May 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 8ed0b98440cd68357d792abaec2a99dccbfa47dc
workflow-type: tm+mt
source-wordcount: '4766'
ht-degree: 38%

---


# 빠른 액세스 - Adobe Experience Cloud 릴리스 노트 - 2020년 5월

![배너](/assets/experience-cloud-banner-3.png)

이 페이지에서는 새로운 기능, 수정 사항 및 중요 정보를 제공합니다 [!DNL Adobe Experience Cloud]. 솔루션 출시 날짜는 다를 수 있습니다. 최신 업데이트를 자주 확인하십시오.

>[!IMPORTANT]
>
>이 페이지에는 릴리스 전 내용이 포함되어 있으며 2020년 5월 21일 이전에 변경될 수 있습니다. 그 후에 게시된 새로운 정보는 추가된 날짜에 기록된다.

>[!NOTE]
>
>예정된 릴리스에 대한 이메일 알림을 받으려면 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)
에 가입하십시오.

**릴리스 날짜: 2020년 5월**

최신 업데이트: **2020년 5월 16일**

* [Adobe 시스템 상태](#status)
* [Experience Cloud 인터페이스](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/ko-KR/target/using/release-notes/target-release-notes.html)(Target 도움말 페이지 링크)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/kr/primetime/user-guide.html)(Primetime 도움말 페이지 링크)

도움이 필요하십니까? Adobe 커리큘럼 과정, 기술 문서, 빠른 답변, 커뮤니티 통찰력 및 강사 중심의 트레이닝을 찾으려면 [[!DNL Adobe Experience League]를](https://experienceleague.adobe.com/#home) 방문하십시오.

## ![아이콘](/assets/adobe.png) Adobe 시스템 상태 {#status}

[!UICONTROL Adobe 시스템 상태]는 Adobe 클라우드 제품 및 서비스 중단, 중단 및 유지 관리 이벤트에 대한 자세한 정보, 상태 업데이트 및 이메일 알림을 제공합니다. [status.adobe.com](https://status.adobe.com/)에서 관련 정보를 확인하십시오.

릴리스 날짜: **2020년 5월 21일**

**새로운 기능**

* Adobe ID를 사용하면 제품 서비스 및 추가 기능 수준까지 세부적으로 이벤트 알림을 구독할 수 있습니다. 이제 자동 구독 프로세스를 통해 보다 신속하게 구독을 설정할 수 있으므로 제품 이용 권한에 따라 제품 및 제품을 선택할 것을 권장합니다. 이렇게 하면 받는 이메일의 수가 감소하고 받은 편지함에서 보다 관련성 높은 알림을 전달할 수 있습니다. [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)에서 시작해 보십시오.

**현재 사용할 수 있는 새로운 기능 및 향상된 기능**

| 기능 | 설명 |
| -----------| ---------- |
| 향상된 구독 및 알림 사용자 경험 | <ul><li>[!DNL Marketo Engage] 이제 선택한 제품 제공 목록을 기반으로 지역 위치가 필터링됩니다.</li><li>[!DNL Marketo Engage] 이메일 알림은 사용자의 지역, 위치 및 환경 설정과 관련이 있습니다.</li></ul> |
| 이벤트 구독 확인 | <ul><li>이제 지속적인 단일 이벤트 업데이트를 구독하면 이메일 확인을 받을 수 있습니다.</li></ul> |
| 전역 탐색 유용성 개선 사항 | <ul><li>최상위 탐색 메뉴 `Adobe.com` 에서 일관된 사용자 경험 제공</li></ul> |

## ![아이콘](/assets/ec_appicon_24.png) Experience Cloud 인터페이스 {#ecloud}

Experience Cloud 인터페이스에 대한 일반 업데이트.

**통합 제품 도메인**

Adobe는 모든 Experience Cloud 애플리케이션에서 경험을 통합하고 개선하기 위해 도메인 및 인터페이스 헤더를 업데이트하고 있습니다. 이러한 개선 사항은 작지만 중요한 방식으로 경험을 간소화하도록 설계되었습니다. 이러한 개선 사항은 현재 작업 과정을 변경하지 않습니다.

업데이트 내용은 다음과 같습니다.

* 새 애플리케이션 URL: `experience.adobe.com/<application name>`:
   * 모든 제품이 결국 이 URL 패턴을 채택합니다. 한 달 동안 새 URL이 유효한지 확인합니다.
   * 브라우저 지원: 지원되는 브라우저에는 [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] 및 [!DNL Opera](최신 버전)이(가) 포함됩니다. **참고:** Experience Cloud 인터페이스는 이러한 브라우저를 지원하지만 개별 애플리케이션은 모든 브라우저를 지원하지 않을 수 있습니다. (예: [Analytics](https://docs.adobe.com/content/help/ko-KR/analytics/admin/sys-reqs.html)는 [!DNL Opera]를 지원하지 않으며, [Target](https://docs.adobe.com/help/ko-KR/target/using/implement-target/before-implement/supported-browsers.html)은 [!DNL Safari]를 지원하지 않습니다.)
   * ([!DNL Safari] 전용) 도메인 변경으로 인해 [!DNL Safari]에 쿠키 문제가 발생할 수 있습니다. _개인 정보 보호 환경설정에서_&#x200B;사이트 간 추적 방지[!DNL Safari]를 선택 해제하면 도메인(및 모든 사이트 간 경험)에서 쿠키가 활성화되고 Experience Cloud가 이 새로운 도메인에서 작동할 수 있습니다.
* 조직 간 또는 다른 애플리케이션으로 쉽게 전환할 수 있습니다.
* 향상된 제품 도움말: [!UICONTROL Experience League]는 제품에 통합되어 있으므로 도움말 검색에 커뮤니티 포럼 및 비디오 컨텐츠의 결과도 포함됩니다. 이러한 변경 사항을 통해 더 많은 컨텐츠를 간편하게 이용하고 Experience Cloud를 최대한 활용할 수 있습니다. 또한 **[!UICONTROL 도움말]** > **[!UICONTROL 피드백]**&#x200B;을 클릭하여 문제를 보고하거나 Adobe와 아이디어를 공유할 수 있습니다.

다음 앱은 새 experience.adobe.com 도메인을 사용합니다.

| 앱 또는 서비스 | 도메인 |
| -----------| ---------- |
| Experience Cloud 홈 페이지 | `experience.adobe.com/home` |
| Adobe Target | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| 고객 여정 관리 | `experience.adobe.com/journeys` |
| 고객 여정 분석 | `experience.adobe.com/platform/analytics` |
| Adobe Campaign 제어판 | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places Service | `experience.adobe.com/places` |
| Software Distribution | `experience.adobe.com/downloads` |
| 관리 도구(베타) | `experience.adobe.com/admin` |

## ![아이콘](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

[!DNL Experience Platform Launch,] [!UICONTROL Journey Orchestration], [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services], 및 보안 공지를 비롯한 [!DNL Experience Platform,]를 위한 릴리스 노트입니다.

### 인터페이스 개선 사항

Updated: **May 15, 2020**

[!DNL Adobe Experience Platform] 는 경험을 향상시키고 다른 Experience Cloud 애플리케이션과 통합할 수 있도록 도메인 및 헤더 막대에 대한 업데이트를 출시하고 있습니다. 업데이트 내용은 다음과 같습니다.

* 조직 간 또는 다른 애플리케이션으로 쉽게 전환할 수 있습니다.
* 도움말 메뉴의 주요 아티클 및 컨텍스트 관련 설명서를 비롯한 사용자 도움말이 개선되었습니다.
* 경험 플랫폼 및 파일 지원 티켓에 대한 피드백을 제공하는 기능

See [Experience Platform release notes](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md) for more information.

### 고객 속성 - 새 설명서

Updated: **May 15, 2020**

* [CPA에 대한 고객 속성](https://docs.adobe.com/content/help/en/core-services/interface/customer-attributes/ccpa.html) 지원(캘리포니아 소비자 개인 정보 보호법)
* [GDPR에 대한 고객 속성](https://docs.adobe.com/content/help/en/core-services/interface/customer-attributes/gdpr.html) 지원(개인 정보 보호 규정)

### 여정 편성 {#journey}

Adobe Experience Platform을 사용하여 모든 개인의 요구 사항을 실시간으로 지능적으로 예측하여 경험 채널에서 규모에 맞게 개별 고객 여정을 편성합니다.

* [설명서](https://docs.adobe.com/content/help/ko-KR/journeys/using/journey-orchestration-home.html)
* [릴리스 노트](https://docs.adobe.com/content/help/ko-KR/journeys/using/release-notes/release-notes.html)
* [방법 비디오](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### 추가 환경 플랫폼 릴리스 정보

* [Experience Platform Launch 릴리스 노트](https://docs.adobe.com/content/help/ko-KR/launch/using/intro/release-notes/current.html).
* [Experience Platform 릴리스 노트](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [보안 게시판 및 권고](https://helpx.adobe.com/kr/security.html) (모든 Adobe 제품)

## ![아이콘](/assets/analytics.png) [!DNL Analytics] {#analytics}

* [고객 경로 분석의 새로운 기능](#cust-journey)
* [Adobe Analytics의 새로운 기능](#aa-features)
* [Analytics 관리자에 대한 중요 공지](#aa-notices)
* [AppMeasurement](#appm)
* [새로운 Analytics 자습서](#tutorials-analytics)

### 고객 경로 분석의 새로운 기능 {#cust-journey}

| 기능 | 설명 |
| -----------| ---------- |
| [!UICONTROL 고객 경로 분석]: 글로벌 가용성 | EMEA 및 APAC 지역의 [!UICONTROL 고객이 고객 경로] 분석을 사용할 수 있도록 합니다. |
| [!UICONTROL 고객 경로 분석]: Adobe [!UICONTROL Experience Platform 샌드박스 지원] | CJA 연결을 빌드할 특정 [!UICONTROL Adobe Experience Platform 샌드박스를] 선택할 수 있습니다. [추가 정보...](https://docs.adobe.com/content/help/ko-KR/analytics-platform/using/cja-connections/create-connection.html) |

### Adobe Analytics의 새로운 기능 {#aa-features}

<!-- Bulk Ingest: Enables you to ingest batches of Analytics data. Useful for server-side and offline data. Learn more...
First-Party Domains Available in China RDC: Enables customers with a cn domain to request a 1st-party domain for use inside of Mainland China. Learn more... -->

| 기능 | 설명 |
| -----------| ---------- |
| Adobe Experience [!UICONTROL Platform Edge Network에 대한 분석 지원] | 단일 태그를 사용하여 Adobe Analytics, Adobe Target, Adobe Audience Manager, Adobe Experience Platform Data Lake, Unified Profile 및 Experience Cloud ID Service와 같은 여러 Adobe 솔루션으로 데이터를 전송할 수 있습니다. [추가 정보...](https://docs.adobe.com/content/help/ko-KR/experience-platform/edge/home.html) |
| [!UICONTROL Adobe Analytics 대시보드] | [!UICONTROL Adobe Analytics 대시보드는] 사용자가 언제 어디서나 Adobe Analytics에서 얻은 인사이트에 액세스할 수 있는 모바일 앱입니다. 이 앱은 주요 지표에 대한 이동 중에 액세스하려는 경영진에게 적합합니다. 선별된 대화형 스코어카드에 액세스할 수 있으며 iOS와 Android 운영 체제 모두에서 사용할 수 있습니다. [추가 정보...](https://docs.adobe.com/content/help/en/analytics/analyze/mobapp/home.html) |
| [!UICONTROL 작업 영역][!UICONTROL : 빈 상태에서 자유 형식 테이블 자동 작성] | Previously, you could not drop components directly into a blank project or blank panel; you had to add a [!UICONTROL Freeform Table] first. You can now drop components directly into a blank project or panel, and a [!UICONTROL Freeform Table] is automatically built for you in a recommended format. 또한, 빈 자유 형식 테이블로 함께 드롭될 때 혼합 구성 요소 유형(예: 차원 및 지표)이 처리되는 방식이 개선되었습니다. |

#### Adobe Analytics 수정 사항

* Fixed an issue that caused missing [!DNL Analytics] segment data in Audience Manager. (AN-206221)
* [!UICONTROL Data Sources] 처리 시 잘못된 날짜를 표시하는 문제가 해결되었습니다. (AN-213604)
* 분류 파일이 FTP에 제대로 업로드되지 않는 문제가 해결되었습니다. (AN-214102)
* API 메서드`Segments.Get`가 전체 응답을 반환하지 않는 문제가 해결되었습니다. (AN-206210)
* [!DNL Workspace] PDF 다운로드에서 테이블 라인 항목이 특수 문자로 변환되던 문제가 해결되었습니다. (AN-196153)
* Adobe Analytics API 1.4 호출`visattrcustomeridcustomerattributes`이 제대로 작동하지 않는 문제가 해결되었습니다. (AN-186873)
* 보고서에 데이터가 표시되지만 [!UICONTROL 데이터 피드]에서 누락되는 문제가 해결되었습니다. (AN-211923)
* [!UICONTROL 제품 프로필] 권한을 복사할 수 없는 문제가 해결되었습니다. (AN-211113)
* Fixed an issue where users with Federated IDs were not able to log in to [!UICONTROL Report Builder]. (AN-207750)
* [!UICONTROL AdWords] 데이터가 [!UICONTROL Advertising Analytics]에 표시되지 않는 문제가 해결되었습니다. (AN-213249)
* 분류 데이터가 트렌드 보기에 표시되지 않는 문제가 해결되었습니다. (AN-212761)
* [!UICONTROL 세그먼트 관리자]에서 잘못 게시된 세그먼트 카운트가 발생하는 문제가 해결되었습니다. (AN-213374)
* 계산된 지표 편집기에서 **[!UICONTROL 위쪽 트렌드 표시..]** 옵션 [!UICONTROL 이 필터를] 적용할 때 작동하지 않던 문제를 수정했습니다. (AN-214223)
* 분류 가져오기 및 내보내기 [!UICONTROL 와] 관련된 여러 문제를 수정했습니다. (AN-213488, AN-215309, AN-216345, AN-215307, AN-216671)
* 분류 규칙 빌더 [!UICONTROL 와 관련된 여러 문제를 수정했습니다]. (AN-213826, AN-213550, AN-213095)
* Data Sources 처리 관련 [!UICONTROL 문제가] 해결되었습니다. (AN-218083, AN-213604, AN-214102, AN-215485, AN-215339, AN-212911,-217551, AN-217947, AN-219018, AN-214691, AN-218401)
* FTP 연결 문제가 해결되었습니다. (AN-115525)
* 여러 [!DNL Analytics] 데이터 피드 [!UICONTROL 문제를] 수정했습니다. (AN-176769, AN-160480, AN-211923, AN-204286, AN-21297, AN-214528, AN-215080, AN-217784, AN-219093, AN-218817, AN-217798, AN-218267, AN-21 8382)
* 데이터 웨어하우스 [!UICONTROL 요청 관련 문제를] 수정했습니다. (AN-181836)
* 값이 특수 문자로 변환되는 PDF에서 다운로드한 [!UICONTROL 작업] 공간 프로젝트의 문제가 해결되었습니다. (AN-196153)
* Fixed an issue with being unable to copy [!UICONTROL Product Profile] permissions in [!UICONTROL Admin Console]. (AN-211113)
* 계산된 지표의 시간 형식이 음수 값에 대해 끊긴 문제를 수정했습니다. (AN-210900)
* 사용자가 정적 행 지표에서 속성 모델 [!UICONTROL 을] 변경할 수 없는 문제를 수정했습니다. (AN-207872)
* 예약된 보고서 [!UICONTROL 빌더가 대기 중인] 상태로 고정되는 문제를 수정했습니다. (AN-215317)
* ExactTarget [!UICONTROL 데이터 커넥터를 수정했습니다]. (AN-210794)
* 벌크 통합 API의 [!UICONTROL 지연 문제를 수정했습니다]. (AN-210165)
* 사용자가 Federated ID로 [!UICONTROL 리포트 빌더] 에 로그인할 수 없는 문제를 해결했습니다. (AN-207750)
* 데이터가 표시되지 않는 광고 [!UICONTROL 분석] 문제 [!DNL Google AdWords] 를 해결했습니다. (AN-213249)
* 작업 공간 프로젝트 [!UICONTROL 보기] 이벤트 [!UICONTROL 가 로그에] 표시되지 않는 문제를 해결했습니다. (AN-214134)
* 작업 공간에서 날짜 범위를 변경하고 [!UICONTROL 모든 패널에] 적용을 선택하면 **[!UICONTROL 발생하는 문제]**&#x200B;를 수정했습니다. 일부 패널에서는 날짜가 변경되지 않았습니다. (AN-214944)
* 경고를 만들거나 편집할 수 없는 문제가 해결되었습니다. (AN-215920)
* 요일 첫날로 인해 [!UICONTROL 작업 공간] 의 모든 동적 날짜 범위에 잘못된 날짜가 표시되던 문제를 수정했습니다. 간헐적으로 월요일에서 일요일로 전환하는 경우 (AN-218835)

#### 추가 Adobe Analytics 수정 사항

AN-101871, AN-115525; AN-123869; AN-152580; AN-160480; AN-178128; AN-186907; AN-199299; AN-201342; AN-201397; AN-204286; AN-204518; AN-206045; AN-206948; AN-208607; AN-209486; AN-210743; AN-211550; AN-211539; AN-211826; AN-211943; AN-212130; AN-212151; AN-212653; AN-212673; AN-212709; AN-212833; AN-212961; AN-212977; AN-213095; AN-213422; AN-213450; AN-213490; AN-213752; AN-213827; AN-214094; AN-214153; AN-214214; AN-214234; AN-214253;  AN-214255; AN-214343; AN-214355; AN-214401; AN-214427; AN-214528; AN-214642; AN-214691; AN-214772; AN-214793; AN-214924; AN-215017; AN-215080; AN-215212; AN-215312; AN-215377; AN-215402; AN-215545; AN-215905; AN-215963; AN-216447; AN-216676; AN-216880; AN-216999; AN-217245; AN-218450; AN-218899; AN-219487; AN-219677

### [!DNL Analytics] 관리자에 대한 중요 공지 {#aa-notices}

| 공지 | 추가 또는 업데이트 날짜 | 설명 |
| -----------| ---------- | ---------- |
| [!UICONTROL Workspace]에서 [!UICONTROL 시작/종료 수]를 계산하는 방법 변경 | 2020년 4월 7일 | 2020년 3월 현재 [!UICONTROL Analysis Workspace]에서 _없음_ 값이 [!UICONTROL 시작/종료]와 상호 작용하는 방식을 변경했습니다. Because you can now turn _Nones_ on and off in [!UICONTROL Analysis Workspace], we apply the _None_ value after the entry or exit, whereas (for eVars) it used to be applied before entry or exit. 예를 들어 방문의 첫 번째 히트에 eVar에 대한 값이 없지만 두 번째 히트는 값이 있다고 가정해 봅시다. In [!UICONTROL Reports &amp; Analytics] the first hit will show as _Unspecified_ for the Entry, but in [!UICONTROL Analysis Workspace] it will show up as the value on the second hit. |
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
| [분석 작업 공간의 교육 자습서 템플릿](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/training-tutorial-template-in-analysis-workspace.html) | 분석 [!UICONTROL 작업 공간] 교육 자습서에서는 작업 공간에서 첫 번째 프로젝트를 빌드하기 위한 일반적인 용어와 단계를 [!UICONTROL 설명합니다]. |
| [트렌드에 대한 이전 월 및 연도 비교 추가](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/calendar-and-date-ranges/adding-prior-month-and-year-comparisons-to-trends.html) | 분석 작업 공간의 모든 지표에 대한 월별 및 연간 트렌드 비교를 만들기 위해 사용자 지정 날짜 범위를 적용하는 방법을 [!UICONTROL 알아봅니다]. |
| [분석 작업 공간에 대한 어두운 모드 확장](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/dark-mode-extension-for-analysis-workspace.html) | Dark Reader Chrome 확장 기능을 활성화하여 분석 작업 공간이 어둡게 표시됩니다. |
| [사용자 정의 팔레트 정의를 위한 색상 스포이드 익스텐션](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/color-eyedropper-extension-for-defining-custom-palettes.html) | ColorPick EyeDrop Chrome 확장 기능을 사용하여 [!UICONTROL Workspace 프로젝트에서 사용자 정의 색상 팔레트에 필요한 16진수 값을 손쉽게 찾는 방법을] 살펴봅니다. |

#### Analytics 도움말 리소스

* [Adobe Analytics 자습서](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics 제품 설명서](https://docs.adobe.com/content/help/ko-KR/analytics/landing/home.html)

## ![아이콘](/assets/audience-manager.png) Audience Manager{#aam}

Audience Manager의 새로운 기능, 수정 사항, 설명서 및 자습서

### 사용자 인터페이스 업데이트

Audience Manager는 경험을 향상시키고 다른 Experience Cloud 애플리케이션과 통합할 수 있도록 도메인 및 헤더 막대에 대한 업데이트를 출시하고 있습니다.

* 조직 간 또는 다른 애플리케이션으로 쉽게 전환할 수 있습니다.
* 도움말 메뉴의 주요 아티클 및 컨텍스트 관련 비디오를 비롯한 사용자 도움말이 개선되었습니다.
* 경험 플랫폼 및 파일 지원 티켓에 대한 피드백을 제공하는 기능
* 새롭고 간편해진 URL 패턴 책갈피를 새 url로 업데이트합니다. `experience.adobe.com/audience-manager`.

이 업데이트는 Adobe ID를 사용하여 로그인하는 사용자만 사용할 수 있습니다. Adobe ID 로그인으로 전환하려면 Experience [Cloud 사용자 및 제품 관리를 참조하십시오](https://docs.adobe.com/content/help/ko-KR/core-services/interface/manage-users-and-products/admin-getting-started.html).

### Adobe Audience Manager의 새로운 기능 및 수정 사항

| 기능 | 설명 |
| -----------| ---------- |  
| [BAAAM(벌크 관리 도구)](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html#download) | 다음과 같은 새로운 벌크 관리 도구 워크시트를 업로드했습니다. <br><br><ul><li>특성 계층 구조에 하위 폴더를 나열할 수 있습니다(AAM-51528).</li><li>CRM ID(장치 간 ID)에 연결된 트레이트를 묻는 메시지가 나타나면 지표를 검색합니다(AAM-52135).</li><li>한국어 문자의 언어 인코딩 문제를 수정했습니다(AAM-AAM-54006).</li></ul> |

**수정 사항**

* 트렌드 보고서가 많은 트레이트가 있는 폴더에 대해 시간 초과되는 문제를 해결했습니다. (AAM-54457)
* 고객이 트레이트 생성/편집 워크플로우에서 [!UICONTROL 표현식 빌더를] 볼 수 없었던 문제를 수정했습니다. (AAM-54255)
* 고객이 UI를 읽을 수 있기 전에 UI의 오류 메시지가 잠깐 동안 표시되던 문제를 수정했습니다. 이 문제는 대상에 매핑된 세그먼트를 삭제하려고 할 때 발생했습니다. (AAM-54031)
* Audience Marketplace를 더 이상 사용하지 않는 고객이 [!UICONTROL 매월] 송장 발행 이메일을 수신하던 문제가 해결되었습니다. (AAM-54602)
* UI에서 다른 위치에서 특정 트레이트를 클릭하면 트레이트가 아닌 끊어진 링크가 표시되는 문제가 해결되었습니다. (AAM-54768)
* 트레이트 표현식 편집 모드에서 Enter 키를 누르면 페이지가 새로 고쳐지고 트레이트 표현식이 손실되는 문제가 해결되었습니다. (AAM-54210)
* 인터페이스에서 여러 액세스 가능성이 개선되었습니다. (AAM-47781, AAM-49075, AAM-49360, AAM-49361, AAM-49376, AAM-50432, AAM-52550,AAM-54660).

### 새로운 Audience Manager 자습서 {#tutorials-aam}

| 컨텐츠 | 설명 |
| -----------| ---------- |  
| [Audience Manager의 기본 용어 및 개념 이해](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-basic-terms-and-concepts-in-audience-manager.html) | 이 비디오에서는 신호, 트레이트, 세그먼트 등을 비롯하여 Audience Manager에서 시작하는 일부 기본 용어 및 개념을 다룹니다. |
| [Audience Manager의 데이터 흐름 이해](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-the-data-flow-in-audience-manager.html) | 이 비디오에서는 애플리케이션 내부, 전체 및 외부 데이터 흐름을 설명함으로써 Adobe Audience Manager를 파악하는 데 도움이 됩니다. |
| [Audience Manager - DMP 개요](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-overview-of-a-dmp.html) | 크로스채널 개인화를 통해 발생하는 주요 당면 과제와 Adobe Audience Manager를 통해 고객 여정의 효과를 높일 수 있는 방법을 살펴볼 수 있습니다. 또한 Audience Manager에서 온보드 데이터 유형을 파악하고 Audience Manager와 통합된 광고 기술 환경 시스템 파트너를 식별할 수 있습니다. |
| [Audience Manager 사용 사례](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-use-cases.html) | 이 비디오에서는 네 가지 일반적인 Audience Manager 사용 사례를 식별하고 이와 관련된 모범 사례를 설명합니다. |
| [Audience Manager의 장치 간 지표 이해](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/understanding-cross-device-metrics-in-audience-manager.html) | 이 비디오에서는 장치 프로파일과 장치 간 프로파일의 차이에 대해 설명하고 UI의 숫자가 이러한 다른 프로필 유형과 일치하는 위치를 보여줍니다. |
| [Audience Manager의 예측 대상 이해](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html) | 이 비디오에서는 Adobe Audience Manager 예측 대상이 무엇인지에 대해 토론하고, 고객 성공 방법에 대한 세부 정보를 제공하고, 활용 사례를 설명합니다. |
| [Audience Manager에서 예측 대상에 대한 구성 및 보고](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/configure-and-report-on-predictive-audiences.html) | 이 비디오에서는 Audience Manager 인터페이스의 예측 대상 구성을 살펴봅니다. 모델의 결과를 보여주는 보고서도 볼 수 있습니다. |

## ![아이콘](/assets/aem.png) Experience Manager {#aem}

Adobe Experience Manager(AEM)의 새로운 기능, 수정 및 업데이트입니다. 안정성, 보안 및 성능 향상을 위해 최신 패치를 배포하려는 경우 온-프레미스 배포를 사용하는 것이 좋습니다.

### 제품 업데이트

* **AEM을 클라우드 서비스로 사용**

   * 자산 처리 개선 및 수정 사항. 자산 재처리 대화 상자에서는 사용자에게 더 많은 제어, 특정 처리 프로필 선택 및 사후 처리 작업 흐름을 트리거해야 하는지 여부를 지정할 수 있습니다.
   * 향상된 다이내믹 미디어 자산 처리 성능

### 사용자 도움말

* **자동 양식 변환 서비스 - 릴리스 AFC-2020.03.1**

   최신 커넥터를 설치할 때 새로운 옵션을 사용할 수 있습니다.

   **[!UICONTROL 논리 섹션 자동 검색]**: [논리 섹션 [!UICONTROL 자동 감지] 옵션을 사용하여 페이지 수준 패널(페이지 번호 기반 패널)을] 삭제하고 논리 패널만 만들 수 있습니다. 또한, 이전에 논리 섹션이 있는 섹션에 속하지 않은 필드와, 인접한 두 페이지에 걸쳐 분산되어 있는 논리 섹션의 필드가 하나의 논리 섹션으로 되어 있습니다. 예를 들어 논리 섹션의 일부 필드가 1페이지의 끝에 있고, 일부 필드가 2페이지의 시작 부분에 있는 경우, 이러한 모든 필드는 하나의 논리 섹션으로 분류됩니다.

* **Dynamic Media에서 지원되지 않는 이미지 형식**

   Dynamic Media에서 지원되지 않는 래스터 이미지 파일 포맷의 하위 유형에 대한 [!UICONTROL 정보입니다].

   Dynamic [Media에서 지원되지 않는 래스터 이미지 형식을 참조하십시오](https://docs.adobe.com/content/help/en/experience-manager-65/assets/administer/assets-formats.html#unsupported-image-formats-dynamic-media).

* **컨텐츠 조각**

   컨텐츠 조각 사용자 지정 및 확장 [,](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html)컨텐츠 조각 [구성 요소 구성 등과 함께 AEM Assets HTTP API의](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-customizing.html)컨텐츠 조각 지원에 대한 [정보입니다](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-configuring-components-rendering.html).

* **AEM Experience League 커뮤니티**

   AEM [Experience League 커뮤니티와 연결](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/ct-p/adobe-experience-manager-community): 동료 학습자 및 AEM 전문가에게 질문하고, 스레드를 탐색하고, 팁과 전문 지식을 공유합니다!

* **AEM 뉴스레터**

   AEM Newsletter by [!UICONTROL Experience League] 는 바로 값 구현을 시작할 수 있도록 AEM을 빠르게 시작하는 데 도움이 되도록 디자인되었습니다. 최신 뉴스레터는 다음과 같습니다.

   * [볼륨 30](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html): 이제 Adobe Experience Manager를 클라우드 서비스로 이용할 수 있습니다.
   * [Experience Insider Newsletter에 가입하십시오](https://adobeeventsonline.com/AEM/2017/NL/Optin/) .
   * Adobe Experience Manager 6.5 학습 및 지원 페이지의 [AEM 리소스](https://helpx.adobe.com/kr/support/experience-manager/6-5.html) 섹션에서 뉴스레터 보관을 봅니다.

### 새로운 Experience Manager 자습서

| 컨텐츠 | 설명 |
| -----------| ---------- |  
| [로컬 AEM 런타임 설정](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) can be run locally using the [!UICONTROL AEM as a Cloud Service] SDK&#39;s [!UICONTROL Quickstart Jar]. This allows developers to deploy to, and test custom code, configuration, and content prior to committing it to source control, and deploying it to a [!UICONTROL AEM as a Cloud Service] environment. |
| [AEM 자산 시작하기](https://video.tv.adobe.com/v/33624?captions=kor) | 비즈니스 사용자를 위한 AEM 자산 시작하기에 대한 소개 비디오입니다. |
| [메타데이터 폴더 스키마](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-folder-schemas.html) | 메타데이터 폴더 스키마를 사용하면 에셋에서 직접 이뤄지는 것이 아니라 에셋 폴더 자체와 관련된 메타데이터를 관리하고 검토할 수 있습니다. |
| [태깅](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/tagging.html) | 태그는 자산의 폴더 계층 구조에서 자산을 관리하기 위한 필수 도구입니다. 태그 지정 분류 설정은 사용자가 AEM에서 자산을 검색하고 구성할 수 있도록 하는 데 매우 중요합니다. |
| [메타데이터 프로필](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-profiles.html) | 메타데이터 프로필을 사용하면 자산 폴더 내의 자산에 기본 메타데이터를 자동으로 적용할 수 있습니다. 이렇게 하면 AEM 사용자의 메타데이터 관리 부담이 줄어들고 메타데이터 일관성이 향상됩니다. |
| [메타데이터 스키마](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-schemas.html) | 메타데이터 스키마는 AEM에 자산 메타데이터를 표시하는 인터페이스를 정의합니다. 이 비디오에서는 자산을 적용하는 데 사용되는 접근 방식의 조합을 살펴봅니다. |

### Journey Orchestration용

* [클라우드 서비스 릴리스 노트로 AEM](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)
* [클라우드 서비스 설명서로 AEM 사용](https://docs.adobe.com/content/help/ko-KR/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 학습 및 지원 홈](https://helpx.adobe.com/kr/support/experience-manager/6-5.html)
* [AEM 6.4 학습 및 지원 홈](https://helpx.adobe.com/kr/support/experience-manager/6-4.html)
* [AEM 6.3 학습 및 지원 홈](https://helpx.adobe.com/kr/support/experience-manager/6-3.html)
* [AEM 6.2 학습 및 지원 홈](https://helpx.adobe.com/kr/support/experience-manager/6-2.html)
* [Cloud Manager 사용 안내서](https://helpx.adobe.com/kr/experience-manager/cloud-manager/user-guide.html)
* [AEM Cloud Manager 릴리스 노트](https://docs.adobe.com/content/help/ko-KR/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [이전 버전의 AEM 설명서](https://helpx.adobe.com/kr/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic 도움말 홈](https://docs.adobe.com/content/help/ko-KR/dynamic-media-classic/using/home.html)
* [Dynamic Media 릴리스 노트](https://marketing.adobe.com/resources/help/ko_KR/s7/release_notes/index.html)
* [Livefyre 릴리스 노트](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## ![아이콘](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign은 온라인 및 오프라인 마케팅 채널 간에 직관적이고, 자동화된 방식으로 일대일 메시지를 제공합니다. 이제 고객이 습관 및 선호도에 따라 결정된 작업 환경을 통해 원하는 사항을 예측할 수 있습니다.

### Campaign Standard

* [Adobe Campaign Standard 20.3 릴리스](https://docs.adobe.com/content/help/ko-KR/campaign-standard/using/release-notes/release-notes.html)

### Campaign Classic

* [Adobe Campaign Classic 20.1.3](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html#release-20-1-3-build-9124)
* [Adobe Campaign Classic 19.1.4](https://docs.adobe.com/content/help/ko-KR/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### 캠페인 제어판

| 기능 | 설명 |
| -----------| ---------- |  
| GPG 키 관리 | Campaign에서 전송된 데이터를 암호화하고 들어오는 데이터를 해독하기 위해 마케팅 인스턴스에 GPG 키를 설치 및/또는 생성합니다. |
| CNAME 하위 도메인을 위한 인증서 관리 | 이제 제어판에서 CNAME 메서드로 위임된 하위 도메인의 SSL 인증서를 갱신할 수 있습니다. |

### 새 캠페인 자습서

* 새로운 Campaign Standard 자습서

| 컨텐츠 | 설명 |
| -----------| ---------- |  
| [제어판 - Google TXT 레코드 관리](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/google-txt-record-management.html) | 캠페인 제어판에서 GMAIL 주소로 이메일을 전송하는 데 사용되는 모든 하위 도메인에 Google TXT 사이트 확인 레코드를 추가하는 방법을 알아봅니다. |
| [외부 API 활동을 사용하여 워크플로우 구성 및 실행](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) | 외부 API 활동을 사용하여 외부 REST API 끝점을 호출하는 방법을 알아봅니다. |
| (ACS) [Android용 푸시 알림 시작하기-자습서](https://docs.adobe.com/content/help/en/campaign-standard-learn/getting-started-with-push-notifications-android/introduction.html) | 이 자습서에서는 Campaign Standard 및 Android 앱을 사용하여 푸시 알림을 설정하는 데 필요한 단계에 대해 설명합니다. |

* 새 Campaign Classic 자습서

| 컨텐츠 | 설명 |
| -----------| ---------- |  
| [Snowflake의 빅데이터 관리](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Adobe Campaign Classic에서 Snowflake 커넥터를 활용하는 방법을 이해합니다. |
| [제어판 - Google TXT 레코드 관리](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/google-txt-record-management.html) | 캠페인 제어판에서 GMAIL 주소로 이메일을 전송하는 데 사용되는 모든 하위 도메인에 Google TXT 사이트 확인 레코드를 추가하는 방법을 알아봅니다. |

### 캠페인 도움말 리소스

* Adobe Campaign Standard: [도움말 센터](https://docs.adobe.com/content/help/ko-KR/campaign-standard/using/campaign-standard-home.html) - [릴리스 노트](https://docs.adobe.com/content/help/ko-KR/campaign-standard/using/release-notes/release-notes.html) - [사용 방법 비디오](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [릴리스 계획](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-planning.htmll) [] - 최신 문서 업데이트최신 문서 업데이트(https://docs.adobe.com/content/help/en/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [도움말 센터](https://docs.adobe.com/content/help/en/campaign-classic/using/campaign-classic-home.html) - [릴리스 노트](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [사용 방법 비디오](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [최신 설명서 업데이트] (https://docs.adobe.com/content/help/en/campaign-classic/using/documentation-updates.html)
* Adobe Campaign 제어판: [설명서](https://docs.adobe.com/content/help/ko-KR/control-panel/using/control-panel-home.html) - [릴리스 노트](https://docs.adobe.com/content/help/ko-KR/control-panel/using/release-notes.html)

## ![아이콘](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

* [Advertising Cloud DSP의 새로운 기능](#adcloud-dsp)
* [Advertising Cloud Search의 새로운 기능](#adcloud-search)

### Advertising Cloud DSP의 새로운 기능 {#adcloud-dsp}

| 기능 | 설명 |
| -----------| ---------- |
| [!UICONTROL 캠페인 클래식] 및 [!UICONTROL 캠페인 베타] | 각 캠페인에 대해 선택적으로 구성할 수 있는 위조 및 브랜드 안전성에 대한 IAS 측정 설정은 VAST 및 VPAID 인벤토리에 대한 측정 옵션을 포함합니다. |
| [!UICONTROL 캠페인 베타] | 데이터 시각화 및 페이지 로드 시간이 개선되었습니다. |
|  | 이제 모든 페이지에서 현재 필터 및 보기를 기반으로 하는 Excel 보고서를 다운로드할 수 있습니다. |
|  | (5월 22일 릴리스) 새 지표에는 모든 시간 지표, 현재 간격 배달, 날짜별 OTS가 포함됩니다. |
| [!UICONTROL 블랙리스트] | 이제 예측 시스템에서 광고주 또는 계정 수준 블랙 리스트를 자동으로 사용합니다. 사용자는 더 이상 블랙리스트를 배치 설정에 붙여넣을 필요가 없습니다. |
| [!UICONTROL 재고 거래] | (닫힌 베타) 간소화된 새로운 양식을 통해 거래 ID 받은 편지함에서 사용할 수 없는 SSP(공급측 플랫폼) 거래를 신속하게 설정, 편집 및 해결할 수 있습니다. |
|  | 거래 ID 받은 편지함에서 프로그래머틱 보장된 거래 패키지를 수락하면 이제 각 거래 ID에 대한 기본 배치를 생성해야 한다는 경고가 표시됩니다. |

### Advertising [!UICONTROL Cloud Search의 새로운 기능] {#adcloud-search}

| 기능 | 설명 |
| -----------| ---------- |
| [!UICONTROL 캠페인] | (Google 광고 계정; 베타 서비스) 5월 말부터 Adobe Advertising Cloud Search는 추적 및 보고를 위해 Google Gmail 디스플레이 캠페인 및 Google Smart Shopping 캠페인의 데이터를 Google 전환과 동기화할 수 있습니다. 또한 이 서비스를 사용하면 캠페인 및 광고 그룹 보기에서 기존 캠페인에 대한 캠페인 설정과 광고 그룹 설정을 편집할 수 있습니다. 서비스는 선택 사항입니다. 서비스를 일반적으로 이용할 수 있게 되면 추가 비용이 부과됩니다.<br>베타 프로그램, 향후 범위 등 서비스에 대한 자세한 내용은 Adobe 계정 관리자에게 문의하십시오. |

## ![아이콘](/assets/magento.png) [!DNL Magento] {#magento}

Magento 릴리스 노트에 대해서는 다음을 참조하십시오.

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![아이콘](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage]는 리드 관리를 위한 완전한 애플리케이션이며, 복잡한 구매 여정의 모든 단계에서 고객 경험을 전환하여 고객 경험을 혁신하고자 하는 B2B 마케터입니다.

### 핵심 Marketo Engage 업데이트

최신 릴리스 정보는 [!DNL Marketo] 릴리스 노트를 [참조하십시오](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) .

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
