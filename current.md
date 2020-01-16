---
title: Adobe Experience Cloud 릴리스 노트
description: Experience Cloud 릴리스 노트 템플릿
doc-type: release notes
last-update: January 2020
author: mfrei
translation-type: tm+mt
source-git-commit: e49bdb89cd3cf434a4932d1669d6f3a2df973769

---


# 조기 액세스 - Adobe Experience Cloud 릴리스 노트 - 2020년 1월

Adobe Experience Cloud의 새로운 기능 및 수정 사항.

>[!IMPORTANT]
>이 페이지에는 출시 전 컨텐츠가 포함되어 있으며 각 제품의 계획된 출시 전에 변경될 수 있습니다.

>[!NOTE]
>예정된 릴리스에 대한 이메일 알림을 받으려면 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)
에 가입하십시오. 릴리스 후 게시된 새 정보는 발행 날짜로 표시됩니다.

**릴리스 날짜: 2020년 1월 16일**

* [Adobe 시스템 상태](#status)
* [Experience Cloud 인터페이스 및 핵심 서비스](#ecloud)
* [Experience Platform](#platform)
* [Mobile Services 및 Mobile SDK](#mobile)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (솔루션 도움말 링크)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (솔루션 도움말 링크)
* [!DNL Advertising Cloud](#adcloud)

도움말 홈을 찾고 계십니까? [Adobe Experience Cloud 설명서](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html)를 참조하십시오.

## Adobe 시스템 상태 {#status}

[!UICONTROL Adobe 시스템 상태]는 Adobe 클라우드 제품 및 서비스 중단, 중단 및 유지 관리 이벤트에 대한 자세한 정보, 상태 업데이트 및 이메일 알림을 제공합니다. [status.adobe.com](https://status.adobe.com/)에서 관련 정보를 확인하십시오.

**새로운 기능**

* Adobe ID를 사용하면 제품, 지역 및 이벤트 환경 설정에 따라 이벤트 알림을 구독할 수 있습니다. 구독 환경 설정을 구성하는 사용자는 관련 제품 인시던트 및 유지 관리 이벤트가 열리거나 업데이트되거나 종료되는 즉시 이런 이벤트에 대한 알림을 받게 됩니다. [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)에서 시작해 보십시오.

**현재 사용할 수 있는 새로운 기능 및 향상된 기능**

| 기능 | 설명 |
| -----------| ---------- |
| 사전 이메일 알림 구독 | <ul><li>Experience Cloud, Creative Cloud, Document Cloud, Adobe Experience Platform 및 Adobe 서비스 지원</li><li>지역 및 이벤트 유형 환경 설정 지원</li></ul> |
| 알림 환경 설정 관리 | <ul><li>언제든지 알림 환경 설정 편집 및 저장</li><li>언제든지 알림 구독 취소</li></ul> |
| 개인화되고 더욱 신속한 이메일 전달 받기 | <ul><li>이벤트가 열리거나 업데이트되거나 종료되는 즉시 이벤트 알림이 전송됨</li><li>구성된 환경 설정과 일치하는 관련 이벤트 알림만 수신</li><li>계정 환경 설정에 구성된 언어를 기반으로 지역화된 알림 수신</li></ul> |
| 개인화된 제품 내 알림 받기 | <ul><li>알림 환경 설정 및 제품 권한과 일치하는 이벤트가 공지 패널에 표시됨</li></ul> |

## Experience Cloud 인터페이스 및 핵심 서비스 {#ecloud}

관리 및 핵심 서비스(고객 특성, 대상, 트리거, 쿠키 등)를 비롯한 Experience Cloud 인터페이스의 새로운 기능 및 수정 사항.

### 통합 제품 도메인

Adobe는 모든 Experience Cloud 애플리케이션에서 사용자 경험을 통합하고 개선하기 위해 도메인 및 인터페이스 헤더를 업데이트하고 있습니다. 이러한 개선 사항은 작지만 중요한 방식으로 경험을 간소화하도록 설계되었습니다. 이러한 개선 사항은 현재 워크플로우를 변경하지 않습니다.

업데이트 내용은 다음과 같습니다.

* 새 솔루션 URL: `experience.adobe.com/<application name>`:
   * 모든 제품은 결국 이 URL 패턴을 채택하게 됩니다. 한 달 동안 새 URL이 유효한지 확인합니다.
   * 브라우저 지원:지원되는 브라우저에는 [!DNL Microsoft Edge], [!DNL Google Chrome][!DNL Firefox]및 [!DNL Safari](최신 버전) [!DNL Opera] 이 포함됩니다. **** 참고:Experience Cloud 인터페이스는 이러한 브라우저를 지원하지만 개별 솔루션은 모든 브라우저를 지원하지 않을 수 있습니다. (예: Analytics [는](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) 지원되지 [!DNL Opera]않으며, [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) 은 [!DNL Safari]지원하지 않습니다.)
   * ([!DNL Safari] only) 도메인 변경으로 인해 쿠키 문제가 발생할 수 [!DNL Safari]있습니다. Unchecking _Prevent cross-site tracking_ in the [!DNL Safari] Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Experience Cloud to function on this new domain.
* 조직 간 또는 다른 애플리케이션으로 쉽게 전환할 수 있습니다.
* 향상된 제품 도움말: [!UICONTROL Experience League]는 제품에 통합되어 있으므로 도움말 검색에 커뮤니티 포럼 및 비디오 컨텐츠의 결과도 포함됩니다. 이러한 변경 사항을 통해 더 많은 컨텐츠를 간편하게 이용하고 Experience Cloud를 최대한 활용할 수 있습니다. Additionally, click **[!UICONTROL Help]**>**[!UICONTROL  Feedback]** to report issues or share your ideas with Adobe.
* 향상된 알림: 이제 [!UICONTROL 알림] 드롭다운 메뉴에 두 개의 탭이 있습니다. 각각 고유한 제품 알림과 글로벌 제품 공지를 위한 탭입니다.

**참고:** [!UICONTROL 피드] 페이지는 2020년 1월부로더 이상 사용되지 않습니다. 제품 내 사용 중단 알림을 찾으십시오.

제품 설명서는 [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html)를 참조하십시오.

### Experience Cloud 쿠키

Adobe는 Chrome 80(2020년 2월 출시)의 변경 사항에 대비하기 위해 쿠키의 `same-site` 설정을 조정하고 있습니다.

자사 데이터 수집에 CNAME을 사용하지 않지만 여러 도메인(익숙한 타사 도메인)에서 해당 CNAME을 사용하며 Experience Cloud(방문자) ID 서비스를 사용하는 경우에는 변경할 필요가 없습니다. Chrome 80 릴리스에서는 Chrome이 Analytics 방문자 ID 쿠키에 다른 도메인에서 해당 쿠키를 사용할 수 없게 하는 `Lax,`의 SameSite 값을 자동으로 제공합니다. 도메인에서 CNAME을 계속 사용하려면 Adobe 고객 지원 팀에 문의하고 CNAME에 대한 SameSite 값을 다음으로 변경하도록 요청해야 합니다. `None.`

Adobe에서는 Experience Cloud ID 서비스를 사용하든 사용하지 않든 간에 각 도메인에 대해 별도의 CNAME을 사용할 것을 권장합니다.

[자세히…](https://medium.com/adobetech/adobe-experience-cloud-cookie-updates-for-google-chrome-19ad67cf1598)

## Experience Platform {#platform}

Experience Platform, Experience Platform Launch, Idendity Service 및 보안 게시판의 릴리스 정보입니다.

* [Experience Platform 릴리스 노트](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [보안 게시판 및 권고](https://helpx.adobe.com/security.html)(모든 Adobe 제품)

### Experience Platform Launch {#launch}

릴리스 노트 및 제품 설명서는 [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html)를 참조하십시오.

## Mobile Services 및 Mobile SDK {#mobile}

2020년 1월 16일: 버전 4.18.0

* 고객 확보 - [!DNL Google Play] Install Referrer API를 지원하기 위해 새로운 API, `Analytics.processGooglePlayInstallReferrerUrl(final String url)`을 추가했습니다.

Install Referrer API에 대한 자세한 내용은 [InstallBroadcast를 아직 사용합니까? 2020년 3월 1일까지 Play Referrer API로 전환](https://android-developers.googleblog.com/2019/11/still-using-installbroadcast-switch-to.html)을 참조하십시오.

## [!DNL Analytics] {#analytics}

Adobe Analytics의 새로운 기능 및 수정 내용:

* [Adobe Analytics의 새로운 기능, 향상된 기능 및 수정 내용](#aa-features)
* [Analytics 관리자에 대한 중요 공지](#aa-notices)
* [AppMeasurement](#appm)

제품 설명서는 [Adobe Analytics 도움말 홈](https://docs.adobe.com/content/help/en/analytics/landing/home.html)을 참조하십시오.

### Adobe Analytics의 새로운 기능, 향상된 기능 및 수정 내용 {#aa-features}

| 기능 | 설명 |
| -----------| ---------- | 
| Analysis Workspace - 자유 형식 테이블 빌더 | 테이블 빌더를 활성화한 상태에서 많은 차원, 분류, 지표 및 세그먼트를 끌어다 놓아 보다 복잡한 비즈니스 질문에 대한 답변을 제공하는 표를 작성할 수 있습니다. 데이터는 즉시 업데이트되지 않습니다. 대신 **[!UICONTROL 작성]**을 클릭하면 업데이트되므로 구성할 테이블을 알고 있으면 시간을 절약할 수 있습니다. 또한 이 기능은 다음과 같은 기능을 제공합니다.<ul><li>**미리 보기**: 실제 데이터를 렌더링하기 전에 표의 형식을 미리 볼 수 있습니다.</li><li>**유연한 행 및 분류 설정**: 모든 차원 행에 대해 행 및 분류 수준을 설정할 수 있습니다. 이전에는 Workspace에 데이터가 반환될 때까지 변경할 수 없었던 기본값이 적용되었습니다.</li><li>**위치별 분석**: 차원 행을 _특정 항목별_(기본값) 대신 항상 _위치별 분석_&#x200B;으로 설정할 수 있습니다.</li><li>**수동 정적 행 순서 지정**: 테이블 행이 필요한 대로 정확하게 표시되도록 정적 행을 수동으로 정렬할 수 있습니다. 이전에는 지표 열 또는 사전순으로만 정적 행을 정렬할 수 있었습니다.</li></ul>관련 설명서는 이 기능이 1월 말에 릴리스되면 게시됩니다. |
| CDA(Cross-Device Analytics)에 대해 새로 [!UICONTROL 식별된 상태] 차원 | Adobe는 CDA 가상 보고서 세트에 [!UICONTROL 식별된 상태]라고 하는 새로운 차원을 추가합니다. 이 차원은 _식별됨_&#x200B;과 _식별되지 않음_&#x200B;의 두 개 값을 갖습니다. _식별됨_&#x200B;은 개인이 장치 그래프에서 식별되었음을 의미합니다. _식별되지 않음_&#x200B;은 개인이 장치 그래프에서 식별되지 않았음을 의미합니다.<br>즉, CDA 사용자는 이제 장치 그래프에 알려진 가상 보고서 세트 내의 사람 수를 설명하는 [!UICONTROL 장치 그래프 범위] 등의 계산된 지표를 만들 수 있습니다. 이 지표는 CDA 압축률 문제를 해결하는 데 유용합니다. 식별된 사람이 거의 없는 경우 결합 수준이 낮습니다. |
| VRS의 Data Warehouse API 지원 | 이제 Data Warehouse API를 통해 가상 보고서 세트를 사용할 수 있습니다. 이전에는 Data Warehouse UI를 통해서만 사용할 수 있었습니다. 이제 Data Warehouse API를 사용할 때 가상 보고서 세트를 보고 쿼리할 수 있지만, 가상 보고서 세트에 적용된 세그먼트가 Data Warehouse와 호환되는 경우에만 가능합니다. |
| 개인 정보 서비스 API: CCPA | CCPA(California Consumer Privacy Act)는 미국 캘리포니아 거주자를 위해 개인 정보 권한 및 소비자 보호를 개선합니다. 이 법은 2020년 1월 1일부터 시행되었습니다.<br><br/>CCPA는 개인 데이터가 판매되었거나 공개되었는지의 여부 및 그 대상을 확인하거나 개인 데이터 판매를 거절하기 위한 개인 데이터 액세스 및 삭제 권한과 같은 새로운 데이터 개인 정보 보호 권한을 캘리포니아 거주자에게 제공합니다.<br><br/>개인 정보 서비스는 개인 데이터 판매 거부 요청을 지원합니다.<br><br/>개인 정보 서비스는 이전에 GDPR 서비스라고 하였으며, 이전의 모든 기능을 유지하고 현재 CCPA를 지원하기 위해 확장되었습니다.<br/><br/>[Analytics의 CCPA](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[개인 정보 서비스 개요](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |

#### 수정 사항

* 경고 알림이 이집트의 전화 번호로 전달되지 않는 문제를 해결했습니다. (AN-197079)
* [!DNL DFA Data Connector]의 여러 문제를 수정했습니다. (AN-193281, AN-193075, AN-193484, AN-193737)
* [!UICONTROL Reports &amp; Analytics]: 제품 전환 단계 보고서가 잘리고 명확하지 않은 숫자가 표시되는 문제를 해결했습니다. (AN-186901)
* 사용자가 새 분류 아키텍처를 사용한 보고서 세트를 기반으로 한 Workspace 프로젝트의 보고서 세트를 전환하지 못했던 문제를 수정했습니다. (AN-199076)
* [!UICONTROL 계산된 지표]의 [!UICONTROL 누적] 기능이 제대로 작동하지 않는 문제를 해결했습니다. (AN-184257)

### [!DNL Analytics] 관리자에 대한 중요 공지 {#aa-notices}

| 알림 | 추가한 날짜 또는 업데이트한 날짜 | 설명 |
| -----------| ---------- | ---------- |
| 새 Adobe Analytics 도메인 | 2019년 12월 18일 | 2020년 1월 16일부터 Adobe Analytics가 새 도메인으로 이동합니다. `https://experience.adobe.com/analytics.`<br>**참고&#x200B;**: 이 변경 사항은 Adobe ID 또는 Enterprise ID로 Analytics에 액세스하는 모든 사용자에게 적용됩니다.<ul><li>도메인 변경으로 인해 Safari에서 Analytics를 로드할 때 쿠키 문제가 발생할 수 있습니다. Safari 개인 정보 보호 기본 설정에서 _사이트 간 추적 방지_&#x200B;를 선택 해제하면 도메인(및 모든 사이트 간 경험)에서 쿠키가 활성화되고 Analytics가 이 새로운 Adobe Experience Cloud 도메인에서 작동할 수 있습니다. 이 경우 Safari 사용자만 영향을 받기 때문에 다른 브라우저는 문제 없이 사용할 수 있습니다.</li><li>도메인 변경으로 인해 일부 고객은 [특정 경우](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html)에 [!UICONTROL Activity Map]이 중단될 수 있습니다.</li></ul> |
| 수명 종료 - Analytics 이전 API | 2020년 1월 9일 | 2020년 11월에 다음 Analytics 이전 API 서비스가 종료됩니다. 이러한 서비스를 사용하여 구축된 현재의 통합 기능은 작동하지 않습니다. <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>이전 OAuth 인증(OAuth 및 JWT)</li></ul>질문에 대한 답변과 진행 방법에 대한 지침을 제공하는 데 도움이 되도록 [이전 API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)를 제공했습니다. 이러한 서비스를 사용하는 API 통합은 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 또는 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)로 마이그레이션할 수 있습니다. 이전 OAuth 계정은 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 통합 계정으로 마이그레이션할 수 있으며, 이 계정은 1.4 Analytics API 및 2.0 Analytics API에 모두 액세스하는 데 사용할 수 있습니다. |
| **[!UICONTROL 아카이브 보기]**옵션 EOL | 2019년 10월 30일 | 대시보드 관리자(**[!UICONTROL 구성 요소 > 대시보드]**)에 있는**[!UICONTROL &#x200B;아카이브 보기]** 옵션의 종료 날짜를 2020년 1월로 발표합니다. |
| **[!UICONTROL IP 로그인 제한 적용]**옵션 EOL | 2019년 10월 30일 | **[!UICONTROL 관리자 > 회사 설정 > 보안]**메뉴에서 IP 로그인 허용 목록(**[!UICONTROL  IP 로그인 제한 적용]**) 기능에 대한 종료 날짜를 2020년 1월로 발표합니다. |
| TLS 1.1 지원 종료 | 2019년 10월 3일 | 2020년 3월 31일까지 Adobe Analytics는 TLS 1.1에 대한 지원을 제거합니다. 이러한 변경은 최고 수준의 보안 표준을 유지하고 고객 데이터의 보안을 향상시키기 위한 지속적인 노력의 일환입니다. |
| 런던 및 싱가포르의 산호세 FTP Broker 종료 | 2020년 7월 | 런던 및 싱가포르의 고객을 위해 런던 또는 싱가포르와 산호세 데이터 센터 간의 데이터 브로커링을 더 이상 지원하지 않습니다[ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>런던의 경우 [ftp3.omniture.com](ftp://ftp3.omniture.com/) 사용</li><li>싱가포르의 경우 [ftp4.omniture.com](ftp://ftp4.omniture.com/) 사용</li></ul> |
| Analytics 사용자의 `createDate` 필드 관련 향후 변경 사항 | 2019년 8월 30일 | 2019년 10월 또는 11월에 Analytics 사용자의 `createDate` 필드가 미국 태평양 표준시에서 시간대 정보가 있는 올바른 형식의 날짜 및 시간 값으로 업데이트되었습니다.(AN-183468) |

### [!DNL AppMeasurement] {#appm}

[JavaScript 릴리스 노트의 AppMeasurement](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)를 참조하십시오.

## Audience Manager {#aam}

Audience Manager에 수정 사항 및 기능이 추가되었습니다.

### Audience Manager의 새로운 기능, 개선 사항 및 수정 사항 {#aam-features}

| 기능 | 설명 |
| -----------| ---------- |
| [CCPA(California Consumer Privacy Act) 지원 및 개인 정보 보호 문서 검토](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html) | 2020년 1월 1일부터 시행된 [CCPA(California Consumer Privacy Act)](https://www.caprivacy.org/about)는 캘리포니아 거주자에게 개인 정보에 대한 새로운 권리를 제공하고 캘리포니아 주 내에서 사업을 하는 특정 업체에 데이터 보호 책임을 부과합니다. <br><br> Audience Manager는 데이터 액세스 및 삭제 요청에 대해 [Adobe Experience Platform 개인 정보 보호 서비스](https://www.adobe.io/apis/experienceplatform/home/services/privacy-service.html)와 같은 개인 정보 보호 도구를 통해 개인 정보 보호 규정에 따른 귀하의 의무를 준수하도록 도와줍니다. <br><br> 선언된 ID(예: CRM ID)를 옵트아웃하도록 현재 [옵트아웃 관리](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#opt-out-requests) 프로세스를 업데이트했습니다. 선언된 ID로 옵트아웃하는 경우 선언된 ID 및 마지막으로 연결된 장치가 Audience Manager 데이터 수집에서 옵트아웃됩니다. 이제 옵트아웃 요청은 이 기능을 지원하는 [대상 파트너](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#aam-partners-with-unsegmentation)에게 세그먼트 해제 요청을 일괄적으로 실시간으로 보냅니다. <br><br> 또한 Adobe는 앞서 언급한 규정을 준수하는 데 필요한 정보를 보다 쉽게 찾을 수 있도록 [데이터 보안](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-security.html), [데이터 개인 정보](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html) 및 [데이터 거버넌스](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-governance.html) 문서를 다시 디자인했습니다. |

### 수정 사항 및 향상된 기능 {#aam-fixes-and-improvements}

* **[!UICONTROL 통합 플랫폼]**을[!UICONTROL 카테고리]로 선택하면[!UICONTROL 기본 정보]섹션이 사라지고 워크플로우를 완료할 수 없는[!UICONTROL 대상 만들기]워크플로우의 문제를 해결했습니다. (AAM-52397, AAM-52414)
* Apple Safari 및 Mozilla Firefox 브라우저에서 대상 [!UICONTROL 만들기/편집] 페이지가 로드되지 않는 버그를 수정했습니다. (AAM-51784)

## Experience Manager {#aem}

Adobe Experience Manager(AEM)의 새로운 기능, 수정 내용 및 업데이트. 안정성, 보안 및 성능 향상을 위해 최신 패치를 배포하려는 경우 온-프레미스 배포를 사용하는 것이 좋습니다.

### 제품 유지 관리

* **AEM 6.5.3.0**
AEM 6.5, 서비스 팩 3.0(6.5.3.0, 2019년 12월 12일 릴리스)은 2019년 4월, AEM 6.5의 공식 출시 이후 릴리스된 주요 고객 수정 사항을 포함하는 중요한 업데이트입니다.
   * [릴리스 노트](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [AEM Forms CFP 릴리스](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.7.0**

   AEM 6.4, 서비스 팩 7.0(6.4.7.0, 2019년 12월 12일 릴리스)는 2018년 4월 AEM 6.4의 공식 출시 이후 릴리스된 주요 고객 수정 사항이 포함된 중요한 업데이트입니다.
   * [릴리스 노트](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [AEM Forms CFP 릴리스](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.7**

   AEM 6.3, 서비스 팩 3, Cumulative Fix Pack 7(6.3.3.7, 2019년 12월 12일 릴리스)은 2017년 4월 AEM 6.3의 공식 출시 이후 릴리스된 주요 고객 수정 사항이 포함된 중요한 업데이트입니다.
   * [릴리스 노트](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [AEM Forms CFP 릴리스](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Desktop App 2.0.1.1**

   AEM Desktop App 2.0.1.1은 Okta의 단일 사인온에 대한 업데이트와 환경 설정에서 임시 파일의 위치를 지정하는 기능을 제공합니다. AEM 6.3.x에 대한 지원은 이 릴리스의 Desktop App 2.x에 더 이상 사용되지 않습니다.
   * [릴리스 노트](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **Adobe Asset Link 1.1은 AEM 6.3.x에 대한 지원을 종료합니다.**

   AEM 6.3.x에 대한 지원 기능은 2019년 4월부터 Adobe Asset Link에서 더 이상 사용되지 않습니다. Adobe Asset Link 1.1은 2020년 1월 13일부터 AEM 6.3.x에 대한 지원을 제거합니다.
   * [Adobe Asset Link](https://helpx.adobe.com/enterprise/using/adobe-asset-link.html)

### 제품 릴리스

* **새로운 기능:클라우드 서비스로 AEM 사용**

   [Adobe Experience](https://www.adobe.com/marketing/experience-manager.html) Manager(AEM)는 이제 클라우드 서비스로 제공됩니다.

   * [소개](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/overview/introduction.html)
   * [릴리스 정보](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/home.html)
   * [설명서](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)

* **자동화된 양식 변환 서비스**

   PDF 양식을 멋진 모바일 전용 HTML 양식으로 자동 변환하는 서비스인 자동화된 양식 변환 서비스는 2019년 12월 12일에 일반 소비에 이용할 수 있습니다.

   * [소개](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html)
   * [서비스 구성](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/configure-service.html)
   * [PDF 양식을 적응형 양식으로 변환](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/convert-existing-forms-to-adaptive-forms.html)

### 사용자 도움말

* **3D 자산 미리 보기**

   AEM 6.5는 작성 프로세스의 일부로 3D 자산 업로드, 전달 및 대화형 미리 보기를 지원합니다. 대화형 3D 뷰어는 AEM의 자산 세부 사항 페이지에서 사용할 수 있습니다. 이 뷰어에는 특히 3D 자산을 궤도 회전, 확대/축소 및 이동할 수 있는 대화형 카메라 컨트롤 컬렉션이 포함되어 있습니다.
[3D 자산 미리 보기](https://docs.adobe.com/content/help/en/experience-manager-65/assets/using/previewing-3d-assets.html)를 참조하십시오.

* **핵심 구성 요소**

   핵심 구성 요소 2.8.0은 이제 [작성 설명서](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) 및 [GitHub에서 사용 가능한 개발자 세부 사항 및 프로젝트 다운로드](https://github.com/adobe/aem-core-wcm-components)와 함께 사용할 수 있습니다.

* **AEM 프로젝트 원형**

   [AEM 프로젝트 원형](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html) 중 [ui.frontend 모듈](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/uifrontend.html)은 AEM 프로젝트에 대한 프런트 엔드 개발을 보다 손쉽게 수행할 수 있는 유용하고 유연한 도구입니다.

### 추가 리소스

* [클라우드 서비스로 AEM 사용](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 학습 및 지원 홈](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 학습 및 지원 홈](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 학습 및 지원 홈](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 학습 및 지원 홈](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager 사용 안내서](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [이전 버전의 AEM 설명서](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic 도움말 홈](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Dynamic Media 릴리스 노트](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre 릴리스 노트](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign은 온라인 및 오프라인 마케팅 채널 간에 직관적이고, 자동화된 방식으로 일대일 메시지를 제공합니다. 이제 고객이 습관 및 선호도에 따라 결정된 작업 환경을 통해 원하는 사항을 예측할 수 있습니다.

### Campaign Classic 19.2

| 기능 | 설명 |
| ------------- | ----------- |
| CCPA(California Consumer Privacy Act) | CCPA는 2020년 1월 1일부터 시행된 데이터 보호 요구 사항을 통합하고 현대화한 캘리포니아 주의 새로운 개인 정보 보호 법입니다. CCPA는 캘리포니아에 거주하는 데이터 주체의 데이터를 보유하고 있는 Adobe Campaign 고객에게 적용됩니다. <br> Adobe Campaign은 이미 사용 가능한 개인 정보 보호 기능(동의 관리, 데이터 유지 설정 및 사용자 역할 포함) 외에도 CPA에 대한 준비를 용이하게 합니다. <ul><li>_액세스 권한_ 및 _삭제 권한_: Adobe는 GDPR에 추가된 기능을 활용하고 있습니다. [추가 정보](https://helpx.adobe.com/campaign/kb/acc-privacy.html#righttoaccess) </li><li>소비자가 개인 정보 판매를 옵트아웃했는지 여부를 추적할 수 있습니다. 이를 위해 [!UICONTROL 프로필] 테이블을 확장하고 **[!UICONTROL CPA에 대한 옵트아웃]**필드를 추가해야 합니다.[추가 정보](https://helpx.adobe.com/campaign/kb/acc-privacy.html#ccpa)</li></ul> [방법 비디오](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/privacy/privacy-overview.html)를 참조하십시오. |
| 워크플로우 실시간 모니터링 | 이제 미리 정의된 보기를 사용하여 인스턴스에 있는 모든 워크플로우의 실행 상태를 모니터링할 수 있습니다. <br> 자세한 내용은 [상태에 따라 워크플로우 필터링](https://docs.adobe.com/content/help/en/campaign-classic/using/automating-with-workflows/monitoring-workflows/monitoring-workflow-execution.html#filtering-workflows-status)을 참조하십시오. |
| AMP를 사용한 대화형 컨텐츠 | Adobe Campaign을 사용하면 새로운 대화형 [이메일용 AMP](https://amp.dev/about/email/) 형식을 사용해 볼 수 있습니다. 이 이메일 형식을 통해 마케터는 메시지 내에 AMP 구성 요소를 포함시켜 메시지 자체에서 직접 실행 가능한 풍부하고 동적인 대화형 컨텐츠로 이메일 경험을 향상시킬 수 있습니다. <br> 이 기능은 공개 베타로 출시됩니다. <br> 자세한 내용은 [상세 설명서](https://docs.adobe.com/content/help/en/campaign-classic/using/sending-messages/sending-emails/defining-interactive-content.html) 및 [자습서 비디오](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/sending-messages/email-channel/defining-interactive-email-content-with-amp.html)를 참조하십시오. |
| 보안 SMS 메시징(TLS) | 보안 SMS는 이제 확장된 일반 SMPP 커넥터를 통해 지원됩니다. 이를 통해 공급자에 암호화된 연결을 허용할 수 있습니다. <br> **경고**: 이 기능을 사용하려면 모든 서버에 최신 인증서가 필요합니다. 인증서가 잘못되었거나, 해지되었거나, 만료된 경우 전체 SMS 전송 기능에 영향을 주는 오류가 발생합니다. <br> 자세한 내용은 [상세 설명서](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html)를 참조하십시오. |

수정 사항 및 향상된 기능은 [Adobe Campaign Classic 릴리스 노트](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html)를 참조하십시오.

### Campaign Standard 19.4

| 기능 | 설명 |
| ------------- | ----------- |
| CCPA(California Consumer Privacy Act) | CCPA는 2020년 1월 1일부터 시행된 데이터 보호 요구 사항을 통합하고 현대화한 캘리포니아 주의 새로운 개인 정보 보호 법입니다. CCPA는 캘리포니아에 거주하는 데이터 주체의 데이터를 보유하고 있는 Adobe Campaign 고객에게 적용됩니다. <br> Adobe Campaign에서 이미 사용 가능한 개인 정보 보호 기능(동의 관리, 데이터 유지 설정 및 사용자 역할 포함) 외에도 Adobe는 CCPA에 대한 준비를 용이하게 하기 위해 이번에 추가 기능을 포함시킬 수 있는 기회를 드립니다. <ul><li> 액세스 권한 및 삭제 권한: Adobe는 GDPR에 추가된 기능을 활용하고 있습니다. [추가 정보](https://helpx.adobe.com/content/help/en/campaign/kb/acs-privacy.html#righttoaccess) </li><li> 개인 정보 보호 요청을 만들 때 개인 정보 보호 핵심 서비스에 규정 유형(GDPR 또는 CCPA)이 추가되었습니다. 이 방법은 모든 액세스 및 삭제 요청에 사용해야 합니다. 액세스 및 삭제 요청에 대한 Campaign API 및 인터페이스는 더 이상 사용되지 않습니다. [사용되지 않고 제거된 기능 문서](https://helpx.adobe.com/campaign/kb/acs-deprecated-and-removed-features.html)를 참조하십시오. </li><li> 소비자가 개인 정보 판매를 옵트아웃했는지 여부를 Adobe Campaign 사용자가 추적할 수 있도록 **CCPA 옵트아웃** 필드가 프로필 리소스에 추가되었습니다. [추가 정보](https://helpx.adobe.com/content/help/en/campaign/kb/acs-privacy.html#ccpa) </li></ul> [방법 비디오](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/privacy/privacy-overview.html)를 참조하십시오. |
| Microsoft Dynamics 365 통합(GA) | 이제 Adobe Campaign Standard와 Microsoft Dynamics 365의 통합 기능을 사용할 수 있습니다. 연락처 및 사용자 지정 엔티티 레코드를 Dynamics 365에서 Campaign으로 전송하고 이메일 이벤트 데이터를 Campaign에서 Dynamics 365로 가져와 판매/마케팅 정렬을 향상시킬 수 있습니다. <br> 이 통합을 설정하고 [방법 비디오](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/integrating/microsoft-dynamics365-connector/introduction.html)를 보려면 [상세 설명서](https://helpx.adobe.com/campaign/kb/acs-ms-dynamics.html)를 참조하십시오. |

수정 사항 및 향상된 기능은 [Adobe Campaign Standard 릴리스 노트](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)를 참조하십시오.

### Adobe Campaign 제어판

관리자 사용자가 제어판에서 하위 도메인을 위임하고 SSL 인증서를 갱신할 수 있는 새로운 기능이 추가되었습니다.

자세한 내용은 다음 페이지를 참조하십시오.

* 새 하위 도메인 설정 - [자세히 알아보기](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/setting-up-new-subdomain.html)
* 하위 도메인의 SSL 인증서 갱신 - [자세히 알아보기](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/renewing-subdomain-certificate.html)

>[!CAUTION]
>
>이러한 기능은 1월 말까지 베타 버전에서 제공되며, 예고 없이 자주 업데이트되고 수정될 수 있습니다.

### 추가 리소스

* Adobe Campaign Standard: [설명서](https://helpx.adobe.com/support/campaign/standard.html) - [릴리스 노트](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [기능 비디오](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [릴리스 계획](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [설명서](https://helpx.adobe.com/support/campaign/classic.html) - [릴리스 노트](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [기능 비디오](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign 제어판: [설명서](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [릴리스 노트](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

2020년 1월 11일 업데이트, 릴리스

| 보기 | 기능 |
|------|---------|
| 전환 추적 | 모든 Advertising Cloud 쿠키가 2월 4일에 릴리스되는 Google Chrome 80의 새로운 쿠키 제어 요구 사항을 충족하도록 업데이트되었습니다. 변경 사항은 방문자 지표에 영향을 주지 않고 기존 쿠키를 사용하여 Adobe 서버에서 구현되었습니다. 광고주 업데이트가 필요하지 않습니다. |
| Insights > 베타 경고, 검색 > 캠페인 | (검색 계정만을 위한 베타 기능) 새로운 베타 경고를 사용하면 지정된 기간 동안 검색 캠페인, 광고 그룹, 키워드 또는 광고가 성능 지표와 같은 특정 조건을 충족하는 경우를 식별하면 경고를 생성하는 경고 템플릿을 만들 수 있습니다. 경고는 단일 광고주에 대해 사용할 수 있습니다. |
| 보고서 | 이제 제품 목록 광고에 대한 데이터가 레이블 분류, 레이블 값, 입찰 규칙 및 제한 보고서에 포함되어 있습니다. |
