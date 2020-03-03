---
title: Adobe Experience Cloud 릴리스 노트
description: Experience Cloud 릴리스 노트 템플릿
doc-type: release notes
last-update: February 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 9ed727b23cbc90965f44c4bb914728bbc2394d6b

---


# Adobe Experience Cloud 릴리스 노트 - 2020년 3월

Adobe Experience Cloud의 새로운 기능 및 수정 사항.

>[!NOTE]
>예정된 릴리스에 대한 이메일 알림을 받으려면 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)
에 가입하십시오. 릴리스 후 게시된 새 정보는 발행 날짜로 표시됩니다.

**릴리스 날짜: 2020년 3월**

(특정 제품 릴리스 날짜는 다를 수 있음)

* [Adobe 시스템 상태](#status)
* [Experience Cloud 인터페이스 및 핵심 서비스](#ecloud) (업데이트: **2020년 2월 26일**)
* [Experience Platform](#platform)
* [Mobile Services 및 Mobile SDK](#mobile)
* [!DNL Analytics](#analytics) (업데이트: 2020년 2월 21일)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (솔루션 도움말 링크)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (솔루션 도움말 링크)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)

도움말 홈을 찾고 계십니까? [Adobe Experience Cloud 설명서](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html)를 참조하십시오.

## Adobe 시스템 상태 {#status}

[!UICONTROL Adobe 시스템 상태]는 Adobe 클라우드 제품 및 서비스 중단, 중단 및 유지 관리 이벤트에 대한 자세한 정보, 상태 업데이트 및 이메일 알림을 제공합니다. [status.adobe.com](https://status.adobe.com/)에서 관련 정보를 확인하십시오.

**새로운 기능**

* Adobe ID를 사용하면 제품, 지역, 이벤트 및 언어 환경 설정에 따라 이벤트 알림을 구독할 수 있습니다. 구독 환경 설정을 구성하는 사용자는 관련 제품 인시던트 및 유지 관리 이벤트가 열리거나 업데이트되거나 종료되는 즉시 이런 이벤트에 대한 알림을 받게 됩니다. [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)에서 시작해 보십시오.

**현재 사용할 수 있는 새로운 기능 및 향상된 기능**

| 기능 | 설명 |
| -----------| ---------- |
| 제품 이벤트에 대한 신속한 인지도 | <ul><li>향후 서비스 유지 관리에 대해 30일 전에 정보를 받습니다. 이 기능을 사용하면 비즈니스 운영에 미치는 잠재적 영향을 평가할 수 있으므로 필요한 경우 완화 계획을 구현할 수 있습니다.</li><li>고급 알림은 웹/모바일/태블릿 지표와 이메일 알림을 통해 사용할 수 있습니다.</li></ul> |
| 기본 설정 언어를 기반으로 경험 개인화 | <ul><li>이메일 알림의 기본 설정 언어를 선택합니다. 자체 구독 기능은 현재 19개 언어로 제공됩니다.</li></ul> |
| 향상된 구독 및 알림 사용자 경험 | <ul><li>구독하려는 모든 제품에 대해 단 한 번의 클릭으로 지역 및 이벤트 기본 설정을 지정할 수 있습니다.</li><li>_잠재적_ 문제가 _사소한_ 문제 또는 _주요_ 문제로 승격되면 알림을 받습니다.</li><li>제품 또는 이벤트 상태가 업데이트되면 브라우저 페이지가 자동으로 새로 고쳐집니다.</li></ul> |

## Experience Cloud 인터페이스 및 핵심 서비스 {#ecloud}

릴리스 업데이트: **2016년 2월 26일**

관리 및 핵심 서비스(고객 특성, 대상, 트리거, 쿠키 등)를 비롯한 Experience Cloud 인터페이스의 새로운 기능 및 수정 사항.

| 기능 | 설명 |
| -----------| ---------- |
| 관리 도구 - 사용자 세부 정보 보기 | 관리자는 새로운 관리 도구에서 모든 Experience Cloud 사용자의 정렬 및 필터링 가능한 목록과 세부 정보를 볼 수 있습니다. 사용자 세부 정보에는 사용자의 제품 액세스, 역할 및 마지막으로 액세스한 정보가 포함됩니다. 자세한 내용은 [Experience Cloud 관리 도구](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html) 도움말을 참조하십시오. |

### 통합 제품 도메인

Adobe는 모든 Experience Cloud 애플리케이션에서 사용자 경험을 통합하고 개선하기 위해 도메인 및 인터페이스 헤더를 업데이트하고 있습니다. 이러한 개선 사항은 작지만 중요한 방식으로 경험을 간소화하도록 설계되었습니다. 이러한 개선 사항은 현재 워크플로우를 변경하지 않습니다.

업데이트 내용은 다음과 같습니다.

* 새로운 솔루션 URL: `experience.adobe.com/<application name>`:
   * 모든 제품이 결국 이 URL 패턴을 채택합니다. 한 달 동안 새 URL이 유효한지 확인합니다.
   * 브라우저 지원: 지원되는 브라우저에는 [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] 및 [!DNL Opera](최신 버전)이(가) 포함됩니다. **참고:** Experience Cloud 인터페이스는 이러한 브라우저를 지원하지만 개별 솔루션은 모든 브라우저를 지원하지 않을 수 있습니다. (예: [Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html)는 [!DNL Opera]를 지원하지 않으며, [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html)은 [!DNL Safari]를 지원하지 않습니다.)
   * ([!DNL Safari] 전용) 도메인 변경으로 인해 [!DNL Safari]에 쿠키 문제가 발생할 수 있습니다. _개인 정보 보호 환경설정에서_&#x200B;사이트 간 추적 방지[!DNL Safari]를 선택 해제하면 도메인(및 모든 사이트 간 경험)에서 쿠키가 활성화되고 Experience Cloud가 이 새로운 도메인에서 작동할 수 있습니다.
* 조직 간 또는 다른 애플리케이션으로 쉽게 전환할 수 있습니다.
* 향상된 제품 도움말: [!UICONTROL Experience League]는 제품에 통합되어 있으므로 도움말 검색에 커뮤니티 포럼 및 비디오 컨텐츠의 결과도 포함됩니다. 이러한 변경 사항을 통해 더 많은 컨텐츠를 간편하게 이용하고 Experience Cloud를 최대한 활용할 수 있습니다. 또한 **[!UICONTROL 도움말]** > **[!UICONTROL 피드백]**&#x200B;을 클릭하여 문제를 보고하거나 Adobe와 아이디어를 공유할 수 있습니다.
* 향상된 알림: 이제 [!UICONTROL 알림] 드롭다운 메뉴에 두 개의 탭이 있습니다. 각각 고유한 제품 알림과 글로벌 제품 공지를 위한 탭입니다.

**참고:** [!UICONTROL 피드] 페이지는 2020년 1월부로더 이상 사용되지 않습니다. 제품 내 사용 중단 알림을 찾으십시오.

제품 설명서는 [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html)를 참조하십시오.

## Experience Platform {#platform}

Experience Platform, Experience Platform Launch, Idendity Service 및 보안 게시판의 릴리스 정보입니다.

* [Experience Platform 릴리스 노트](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [보안 게시판 및 권고](https://helpx.adobe.com/security.html)(모든 Adobe 제품)

### Experience Platform Launch {#launch}

릴리스 노트 및 제품 설명서는 [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html)를 참조하십시오.

## Mobile Services 및 Mobile SDK {#mobile}

모바일 컨텐츠.

## [!DNL Analytics] {#analytics}

Adobe Analytics의 새로운 기능 및 수정 내용:

* [Adobe Analytics의 새로운 기능, 향상된 기능 및 수정 내용](#aa-features)
* [Analytics 관리자에 대한 중요 공지](#aa-notices)
* [AppMeasurement](#appm) (업데이트: 2020년 2월 21일)

제품 설명서는 [Adobe Analytics 도움말 홈](https://docs.adobe.com/content/help/en/analytics/landing/home.html)을 참조하십시오.

### Adobe Analytics의 새로운 기능, 향상된 기능 및 수정 내용 {#aa-features}

* **분석 작업 공간의 여러 보고서 세트**:이제 여러 보고서 세트의 데이터를 하나의 분석 작업 공간 프로젝트로 가져와 나란히 볼 수 있습니다. 2020년 3월 12일부터 몇 주 동안 모든 고객에게 이 기능이 제공됩니다. [추가 정보...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Experience Cloud 고객 최적화**:이 기능을 사용하면 세그먼트를 8시간 이내에 Experience Cloud에 게시할 수 있습니다(이전 48시간 처리 시간이 아니라). [추가 정보...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-publish.html)

#### 수정 사항

* 고객이 .xls 보고서를 다운로드하지 못하는 보고 및 분석 문제를 해결했습니다.(AN-206541, AN-204008)
* 새 셸의 롤아웃은 Experience Cloud 조직 전환과 관련된 몇 가지 고객 문제를 해결했습니다.(AN-200844, AN-186920)

### [!DNL Analytics] 관리자에 대한 중요 공지 {#aa-notices}

| 알림 | 추가한 날짜 또는 업데이트한 날짜 | 설명 |
| -----------| ---------- | ---------- |
| &quot;전환 수준&quot; 설정의 EOL | 2020년 3월 3일 | 관리 도구 > [보고서](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) 세트 > 일반 계정 설정에서 작동하지 않는 전환 수준 설정이 2020년 3월 12일 UI에서 제거됩니다. |
| 대시보드 아카이브 EOL | 2020년 3월 3일 | 보고 및 분석의 대시보드 관리 아래의 &quot;보관 보기&quot; 설정은 2020년 3월 12일부터 더 이상 사용할 수 없습니다. |
| 새 Adobe Analytics 도메인 | 2019년 12월 18일 | 2020년 1월 16일부터 Adobe Analytics가 새 도메인으로 이동합니다. `https://experience.adobe.com/analytics.`<br>**참고&#x200B;**: 이 변경 사항은 Adobe ID 또는 Enterprise ID로 Analytics에 액세스하는 모든 사용자에게 적용됩니다.<ul><li>도메인 변경으로 인해 Safari에서 Analytics를 로드할 때 쿠키 문제가 발생할 수 있습니다. Safari 개인 정보 보호 기본 설정에서 _사이트 간 추적 방지_&#x200B;를 선택 해제하면 도메인(및 모든 사이트 간 경험)에서 쿠키가 활성화되고 Analytics가 이 새로운 Adobe Experience Cloud 도메인에서 작동할 수 있습니다. 이 경우 Safari 사용자만 영향을 받기 때문에 다른 브라우저는 문제 없이 사용할 수 있습니다.</li><li>도메인 변경으로 인해 일부 고객은 [특정 경우](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html)에 [!UICONTROL Activity Map]이 중단될 수 있습니다.</li></ul> |
| 수명 종료 - Analytics 이전 API | 2020년 1월 9일 | 2020년 11월에 다음 Analytics 이전 API 서비스가 종료됩니다. 이러한 서비스를 사용하여 구축된 현재의 통합 기능은 작동하지 않습니다. <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>이전 OAuth 인증(OAuth 및 JWT)</li></ul>질문에 대한 답변과 진행 방법에 대한 지침을 제공하는 데 도움이 되도록 [이전 API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)를 제공했습니다. 이러한 서비스를 사용하는 API 통합은 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 또는 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)로 마이그레이션할 수 있습니다. 이전 OAuth 계정은 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 통합 계정으로 마이그레이션할 수 있으며, 이 계정은 1.4 Analytics API 및 2.0 Analytics API에 모두 액세스하는 데 사용할 수 있습니다. |
| **[!UICONTROL 아카이브 보기]** 옵션 EOL | 2019년 10월 30일 | 대시보드 관리자(**[!UICONTROL 구성 요소 > 대시보드]**)에 있는 **[!UICONTROL 아카이브 보기]** 옵션의 종료 날짜를 2020년 1월로 발표합니다. |
| **[!UICONTROL IP 로그인 제한 적용]** 옵션 EOL | 2019년 10월 30일 | **[!UICONTROL 관리자 > 회사 설정 > 보안]** 메뉴에서 IP 로그인 허용 목록(**[!UICONTROL IP 로그인 제한 적용]**) 기능에 대한 종료 날짜를 2020년 1월로 발표합니다. |
| TLS 1.1 지원 종료 | 2019년 10월 3일 | 2020년 3월 31일까지 Adobe Analytics는 TLS 1.1에 대한 지원을 제거합니다. 이러한 변경은 최고 수준의 보안 표준을 유지하고 고객 데이터의 보안을 향상시키기 위한 지속적인 노력의 일환입니다. |
| 런던 및 싱가포르의 산호세 FTP Broker 종료 | 2020년 7월 | 런던 및 싱가포르의 고객을 위해 런던 또는 싱가포르와 산호세 데이터 센터 간의 데이터 브로커링을 더 이상 지원하지 않습니다[ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>런던의 경우 [ftp3.omniture.com](ftp://ftp3.omniture.com/) 사용</li><li>싱가포르의 경우 [ftp4.omniture.com](ftp://ftp4.omniture.com/) 사용</li></ul> |
| Analytics 사용자의 `createDate` 필드 관련 향후 변경 사항 | 2019년 8월 30일 | 2019년 10월 또는 11월에 Analytics 사용자의 `createDate` 필드가 미국 태평양 표준시에서 시간대 정보가 있는 올바른 형식의 날짜 및 시간 값으로 업데이트되었습니다.(AN-183468) |

### [!DNL AppMeasurement] {#appm}

[JavaScript 릴리스 노트의 AppMeasurement](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html)를 참조하십시오. 버전 2.19.0은 2020년 2월 21일에 릴리스되었습니다.

## Audience Manager {#aam}

Audience Manager에 수정 사항 및 기능이 추가되었습니다.

### Audience Manager의 새로운 기능, 개선 사항 및 수정 사항 {#aam-features}

| 기능 | 설명 |
|----|----|
|  |  |
|  |  |

### 수정 사항 및 향상된 기능 {#aam-fixes-and-improvements}

AAM에 대한 수정 사항.

## Experience Manager {#aem}

Adobe Experience Manager(AEM)의 새로운 기능, 수정 내용 및 업데이트. 안정성, 보안 및 성능 향상을 위해 최신 패치를 배포하려는 경우 온-프레미스 배포를 사용하는 것이 좋습니다.

### 추가 리소스

* [AEM을 클라우드 서비스로 사용](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
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

### 추가 리소스

* Adobe Campaign Standard: [설명서](https://helpx.adobe.com/support/campaign/standard.html) - [릴리스 노트](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [기능 비디오](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [릴리스 계획](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [설명서](https://helpx.adobe.com/support/campaign/classic.html) - [릴리스 노트](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [기능 비디오](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign 제어판: [설명서](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [릴리스 노트](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

2020년 2월 10일에 업데이트됨, 2월 8일 릴리스 기준

## [!DNL Magento] {#magento}

Magento 릴리스 노트에 대해서는 다음을 참조하십시오.

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## [!DNL Marketo] {#marketo}

[!DNL Marketo Engage]는 리드 관리를 위한 완전한 솔루션이며, 복잡한 구매 여정의 모든 단계에서 고객 경험을 전환하여 고객 경험을 혁신하고자 하는 B2B 마케터입니다.

### 핵심 Marketo Engage 업데이트

릴리스 날짜: 2020년 2월 21일

* Microsoft _Flow Action **의**Microsoft Dynamics_&#x200B;변경 담당자: 리드를 변경하거나 Marketo Engage에서 직접 담당자에게 문의하십시오.
* **API 호출에 대한 개선 사항:**
   * 사용자 관리 API
   * 사용자 지정 개체 스키마 API
   * 랜딩 페이지 리디렉션 규칙 API
* **양식 설명자 캐싱:** 랜딩 페이지 및 양식 개선 사항.

자세한 내용은 [!DNL Marketo]2020년 2월[ 릴리스 노트](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720)를 참조하십시오.

### 예정된 기능

다음 기능은 분기 전체에 걸쳐 릴리스됩니다.

| 기능 | 설명 |
|------|---------|
| [!DNL Bizible] | <ul><li>새로운 계정 기반 세분화</li><li>대시보드별 필터 저장</li><li>Bizible 대시보드를 PDF로 내보내기</li></ul> |
| 영업 연결 | Compose Window 및 Command Center 업데이트/개선 사항 |

### 공지

**Marketo Engage Success Center:** 2020년 2월 출시. Success Center는 Product Docs 및 Community를 검색하고 사용 방법 가이드를 실행하고 채택률 컨텐츠에 액세스하는 등 다양한 작업을 할 수 있는 제품 내 도움말 센터입니다. 참고: 이 기능은 ANZ에서 베타 버전으로 출시되며, 해당 분기 후반에 북미에 출시될 예정입니다.

### 사용 중단

* **자산 API &quot;_method&quot; 매개 변수:** 2020년 9월 이후, 자산 API 끝점은 이제 &quot;_method&quot;를 사용하여 쿼리 매개 변수를 URI 길이 제한을 무시하도록 POST 본문에 전달하지 않습니다.
* **Internet Explorer 지원 중단:** 2020년 7월 31일부터 Marketo Engage 사용자 인터페이스는 이제 Internet Explorer에서 지원되지 않습니다.

누적 릴리스 노트와 내역 릴리스 노트는 [Marketo 릴리스 노트](https://docs.marketo.com/x/CgA6Ag)를 참조하십시오.