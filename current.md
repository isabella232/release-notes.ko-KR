---
title: Adobe Experience Cloud 릴리스 노트
description: Experience Cloud 릴리스 노트 템플릿
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: b58151e366ba9aef341a8bd6742d6275d5cd8b30

---


# 조기 이용 - Adobe Experience Cloud 릴리스 노트 - 2020년 3월

Adobe Experience Cloud의 새로운 기능 및 수정 사항.

>[!IMPORTANT]
>이 페이지에는 출시 전 컨텐츠가 포함되어 있으며 계획된 출시 전에 변경될 수 있습니다.

>[!NOTE]
>예정된 릴리스에 대한 이메일 알림을 받으려면 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)
에 가입하십시오. 릴리스 후 게시된 새 정보는 발행 날짜로 표시됩니다.

**릴리스 날짜: 2020년 3월**

(특정 제품 릴리스 날짜는 다를 수 있음)

* [Adobe 시스템 상태](#status)
* [Experience Cloud 인터페이스 및 핵심 서비스](#ecloud)
* [Experience Platform](#platform)
* [여정 통합 운영](#journey)
* [Mobile Services 및 Mobile SDK](#mobile)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (솔루션 도움말 링크)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (솔루션 도움말 링크)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [새로운 설명서 및 자습서](#selfhelp)

도움말 홈을 찾고 계십니까? [Adobe Experience Cloud 설명서](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html)를 참조하십시오.

## Adobe 시스템 상태 {#status}

[!UICONTROL Adobe 시스템 상태]는 Adobe 클라우드 제품 및 서비스 중단, 중단 및 유지 관리 이벤트에 대한 자세한 정보, 상태 업데이트 및 이메일 알림을 제공합니다. [status.adobe.com](https://status.adobe.com/)에서 관련 정보를 확인하십시오.

**새로운 기능**

* Adobe ID를 사용하면 제품 제공 및 Add-On 수준으로 세부적으로 이벤트 알림을 구독할 수 있습니다. Experience Cloud 제품의 이 새로운 기능을 찾아보십시오. 여기서 자체 구독 프로세스에는 가입하려는 제품 및 서비스에 대한 하위 서비스가 표시됩니다. 이러한 향상된 기능을 통해 수신한 알림의 양을 대폭 줄이고 사용 중인 제품 및 기능과 보다 연관성 있는 알림을 만들 수 있습니다.  [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)에서 시작해 보십시오.

**현재 사용할 수 있는 새로운 기능 및 향상된 기능**

| 기능 | 설명 |
| -----------| ---------- |
| 제품 하위 서비스별 맞춤형 셀프 구독 | <ul><li>Adobe Experience Cloud 제품의 제품 및 애드온을 통한 자체 구독</li><li>수신한 이벤트 알림은 제품 및 제품 상품 선호도와 관련이 있습니다.</li></ul> |
| 사용자 선호도에 따라 개인화된 경험 | <ul><li>브라우저 설정을 기반으로 하는 표준 시간대 환경 설정은 이메일 알림에 사용됩니다.</li><li>선택한 모든 기본 설정이 포함된 구독/구독 취소 시 이메일 확인 메시지가 전송됩니다.</li></ul> |
| 이벤트 메시지 전달 향상 | <ul><li>이벤트 내역은 시간 이벤트 업데이트를 기반으로 정렬됩니다.</li><li>주요/부 종료 문제에 추가된 이벤트 확인 타임스탬프</li></ul> |

## Experience Cloud 인터페이스 및 핵심 서비스 {#ecloud}

관리 및 핵심 서비스(고객 특성, 대상, 트리거, 쿠키 등)를 비롯한 Experience Cloud 인터페이스의 새로운 기능 및 수정 사항.

| 기능 | 릴리스 날짜 | 설명 |
| ----|----|---- |
| 관리 도구 - 사용자 세부 정보 보기 | 2020년 2월 26일 | 관리자는 새로운 관리 도구에서 모든 Experience Cloud 사용자의 정렬 및 필터링 가능한 목록과 세부 정보를 볼 수 있습니다. 사용자 세부 정보에는 사용자의 제품 액세스, 역할 및 마지막으로 액세스한 정보가 포함됩니다. 자세한 내용은 [Experience Cloud 관리 도구](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html) 도움말을 참조하십시오. |

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

**참고:** 피드 [!UICONTROL 페이지는] 2020년 1월에 더 이상 사용되지 않습니다. 제품 내 사용 중단 알림을 찾으십시오.

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) help.

## Experience Platform {#platform}

Release notes for the [!UICONTROL Experience Platform,] [!UICONTROL Experience Platform Launch,] [!UICONTROL Identity Service,] and security bulletins.

* [Experience Platform 릴리스 노트](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [보안 게시판 및 권고](https://helpx.adobe.com/security.html)(모든 Adobe 제품)

### Experience Platform Launch {#launch}

릴리스 노트 및 제품 설명서는 [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html)를 참조하십시오.

## 여정 통합 운영 {#journey}

Adobe Experience Platform을 사용하면 고객 여정의 모든 접점에서 개인별 요구 사항을 실시간으로 지능적으로 예측하여 경험 채널에서 고객 여정을 규모에 맞게 조정할 수 있습니다.

1분기 릴리스가 게시되었습니다. [자세한 내용](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html#q1-release---march-2020)

### 추가 리소스

[설명서](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html) - [릴리스 노트](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [사용 방법 비디오](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## Mobile Services 및 Mobile SDK {#mobile}

**iOS v4.19.1**

* 일반 - Swift 열거형이 추적 호출을 [!UICONTROL 위한] 컨텍스트 데이터에 포함될 때 발생할 수 있는 충돌을 해결했습니다.
* [!DNL Target] - [!DNL Target] 이제 세션 ID가 Adobe Analytics `a.target.sessionId` 로 전송된 내부 [!UICONTROL Analytics-for-Target] 히트에서 컨텍스트 데이터 매개 변수로 추가됩니다.

**Android v4.18.1**

* [!DNL Target] - [!DNL Target] 세션 ID는 이제 Adobe Analytics로 전송된 내부 Analytics- [!UICONTROL for-Target 히트에서 컨텍스트 데이터 매개 변수 &quot;a.target.sessionId&quot;로] 추가됩니다.

## [!DNL Analytics] {#analytics}

릴리스 날짜: **2020년 3월 12일**

Adobe Analytics의 새로운 기능 및 수정 내용:

* [Adobe Analytics의 새로운 기능, 향상된 기능 및 수정 내용](#aa-features)
* [Analytics 관리자에 대한 중요 공지](#aa-notices)
* [AppMeasurement](#appm)

제품 설명서는 [Adobe Analytics 도움말 홈](https://docs.adobe.com/content/help/en/analytics/landing/home.html)을 참조하십시오.

### Adobe Analytics의 새로운 기능, 향상된 기능 및 수정 내용 {#aa-features}

* **분석 작업 공간의 여러[!UICONTROL 보고서 세트&#x200B;]**:이제 여러 보고서 세트의 데이터를 단일 분석 작업 공간[!UICONTROL 프로젝트로 가져와서]나란히 볼 수 있습니다. 이 기능은 여러 주 동안 모든 고객에게 제공됩니다.[추가 정보...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Experience Cloud 고객 최적화**:이 기능을 사용하면 세그먼트를 8시간 이내에 Experience Cloud에 게시할 수 있습니다(이전 48시간 처리 시간이 아니라). [추가 정보...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-publish.html)
* **분석 작업 공간 - 교육 자습서 템플릿**:이 새로운 표준 템플릿은 작업 공간에서 첫 번째 분석을 작성하는 일반적인 용어 및 단계를 안내합니다. 새 프로젝트 모달에서 표준 템플릿으로 사용할 수 [!UICONTROL 있으며] 목록에 다른 프로젝트가 없는 신규 사용자에게 현재 존재하는 샘플 프로젝트를 대체합니다.

#### 수정 사항

* 보고 및 분석에서 [!UICONTROL 보고서를] 다운로드할 수 없는 문제를 `.xls` 수정했습니다. 이 문제는 미국 달러 및 유로 외의 통화를 사용하는 고객에게 영향을 주었습니다. (AN-206541, AN-204008)
* 새 셸의 롤아웃은 Experience Cloud 조직 전환과 관련된 몇 가지 고객 문제를 해결했습니다.(AN-200844, AN-186920)
* 분류의 검색 필터에서 지정되지 않음(없음) _을_ 제외하고 지정되지 않음 _라인 항목(또는 기타 일부 보고 라인 항목)에 분류를 수행하면_ 분류에서 결과가 반환되지 않는 문제가 해결되었습니다.
* 분류된 차원을 사용할 때 시작 또는 종료 지표 합계가 분류에서 라인 항목 합계와 일치하지 않는 문제를 수정했습니다.
* Attribution IQ의 첫 번째 터치 및 마지막 터치 모델이 일부 기본 차원의 일부 라인 항목에 대한 크레딧을 올바로 계산하지 않았던 문제를 수정했습니다.
* 특정 날짜 차원을 다른 날짜 차원으로 분류하면 잘못된 결과가 반환되는 문제를 해결했습니다.
* 때로 분류된 차원 보고서에서 &quot;지정되지 않음&quot;에 적용될 때 시작 또는 종료 지표가 잘못 카운트되는 문제를 수정했습니다.

### [!DNL Analytics] 관리자에 대한 중요 공지 {#aa-notices}

| 알림 | 추가한 날짜 또는 업데이트한 날짜 | 설명 |
| -----------| ---------- | ---------- |
| 전환 수준 **[!UICONTROL 설정의]** EOL | 2020년 3월 3일 | 관리 도구 [> 보고서](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) 세트 **[!UICONTROL >]일반 계정[!UICONTROL 설정에서 작동하는]전환 수준** 설정은 2020년 3월 12일에 UI에서 제거됩니다. |
| 대시보드 **[!UICONTROL 아카이브 EOL]** | 2020년 3월 3일 | 보고 **[!UICONTROL 및 분석의]** 대시보드 **** 관리 아래에 있는 아카이브 [!UICONTROL 보기 설정은 2020년 3월] 12일부터 더 이상 사용할 수 없습니다. |
| TLS 1.1 지원 종료 | 2019년 10월 3일 | 2020년 3월 31일까지 Adobe Analytics는 TLS 1.1에 대한 지원을 제거합니다. 이러한 변경은 최고 수준의 보안 표준을 유지하고 고객 데이터의 보안을 향상시키기 위한 지속적인 노력의 일환입니다. |
| 새 Adobe Analytics 도메인 | 2019년 12월 18일 | 2020년 1월 16일부터 Adobe Analytics가 새 도메인으로 이동합니다. `https://experience.adobe.com/analytics.`<br>**참고&#x200B;**: 이 변경 사항은 Adobe ID 또는 Enterprise ID로 Analytics에 액세스하는 모든 사용자에게 적용됩니다.<ul><li>도메인 변경으로 인해 Safari에서 Analytics를 로드할 때 쿠키 문제가 발생할 수 있습니다.  개인 정보 보호 기본 설정에서 _사이트 간 추적 방지_&#x200B;를 선택 해제하면 도메인(및 모든 사이트 간 경험)에서 쿠키가 활성화되고 Analytics가 이 새로운 Adobe Experience Cloud 도메인에서 작동할 수 있습니다. [!DNL Safari] You can use other browsers without issue because this affects only [!DNL Safari] users.</li><li>도메인 변경으로 인해 일부 고객은 [특정 경우](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html)에 [!UICONTROL Activity Map]이 중단될 수 있습니다.</li></ul> |
| 수명 종료 - Analytics 이전 API | 2020년 1월 9일 | 2020년 11월에 다음 Analytics 이전 API 서비스가 종료됩니다. 이러한 서비스를 사용하여 구축된 현재의 통합 기능은 작동하지 않습니다. <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>이전 OAuth 인증(OAuth 및 JWT)</li></ul>질문에 대한 답변과 진행 방법에 대한 지침을 제공하는 데 도움이 되도록 [이전 API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)를 제공했습니다. 이러한 서비스를 사용하는 API 통합은 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 또는 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)로 마이그레이션할 수 있습니다. 이전 OAuth 계정은 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 통합 계정으로 마이그레이션할 수 있으며, 이 계정은 1.4 Analytics API 및 2.0 Analytics API에 모두 액세스하는 데 사용할 수 있습니다. |
| 런던 및 싱가포르의 산호세 FTP Broker 종료 | 2020년 7월 | For customers in London and Singapore, we will no longer support brokering of data between London or Singapore and the San Jose data center [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>For London, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>For Singapore, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |

### [!DNL AppMeasurement] {#appm}

[JavaScript 릴리스 노트의 AppMeasurement](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html)를 참조하십시오. 버전 2.20.0은 2020년 3월 5일에 릴리스되었습니다.

## Audience Manager {#aam}

Audience Manager의 새로운 기능 및 업데이트:

### Fixes and improvements {#aam-fixes-and-improvements}

* RBAC 권한 VIEW_ALL_DESTINATIONS가 누락되어 고객이 세그먼트 이름을 업데이트할 [!UICONTROL 수 없었던 버그를 수정했습니다]. 세그먼트를 [!UICONTROL 업데이트하는 데 VIEW_ALL] _DESTINATIONS 권한이 필요하지 않습니다. RBAC 권한에 대한 자세한 내용은 관리( [RBAC 컨트롤)를](https://docs.adobe.com/help/en/audience-manager/user-guide/features/administration/administration-overview.html#wild-card-permissions)참조하십시오. (AAM-52760)
* 데이터 탐색기 [신호를 기반으로](https://docs.adobe.com/help/en/audience-manager/user-guide/features/data-explorer/data-explorer-overview.html) 트레이트를 만들 때 일부 고객이 기본 정보 섹션에서 컨텐츠를 볼 수 없었던 데이터 탐색기의 버그를 [!UICONTROL 수정했습니다] . (AAM-53130)
* 일부 고객이 Audience Marketplace 인터페이스를 로드할 수 없는 [!UICONTROL 버그를] 수정했습니다. (AAM-52070)
* 설명이 없는 일부 [!UICONTROL 세그먼트로 인해] 사용자가 해당 세그먼트에 액세스하려고 하고 사용자가 해당 페이지에서 멀리 이동해야 하는 경우 인터페이스가 중지되는 세그먼트 API의 버그를 수정했습니다. (AAM-53071)
* 인터페이스 전체에서 여러 접근성 향상 (AAM-48952, AAM-48969, AAM-48979, AAM-48993, AAM-49048, AAM-49058,AAM 4 aam-49392)

## Experience Manager {#aem}

Adobe Experience Manager(AEM)의 새로운 기능, 수정 내용 및 업데이트. 안정성, 보안 및 성능 향상을 위해 최신 패치를 배포하려는 경우 온-프레미스 배포를 사용하는 것이 좋습니다.

### 제품 업데이트

* **AEM 6.5.4.0** AEM 6.5, 서비스 팩 4.0(2020년 3월 5일 릴리스된 6.5.4.0)은 새로운 기능, 주요 고객 개선 사항, 향상된 성능, 안정성 및 보안을 포함하는 중요한 업데이트로서, 2019년 4월 AEM 6.5의 일반 가용성 이후 릴리스되었습니다.
   * [Adobe Experience Manager 6.5, 서비스 팩 4의 새로운 기능](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html)
   * [릴리스 노트](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [AEM Forms 릴리스 자료](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.0**

   AEM 6.4, 서비스 팩 8.0(2020년 3월 5일 릴리스된 6.4.8.0)은 2018년 4월 AEM 6.4의 일반 가용성 이후 릴리스된 주요 고객 픽스를 포함하는 중요한 업데이트입니다.
   * [릴리스 노트](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [AEM Forms CFP 릴리스](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.8**

   AEM 6.3, 서비스 팩 3, 누적 수정 팩 8(2019년 3월 5일 릴리스된 6.3.8)은 2017년 4월 AEM 6.3의 일반 가용성 이후 릴리스된 주요 고객 픽스를 포함하는 중요한 업데이트입니다.
   * [릴리스 노트](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [AEM Forms CFP 릴리스](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Assets Brand Portal**

   AEM Assets 브랜드 포털 6.4, 서비스 팩 6(6.4.6 릴리스, 2020년 3월 5일)은 AEM 자산이 브랜드 포털로 구성된 방식을 [!UICONTROL 변경합니다.] 또한 릴리스에는 기타 개선 사항 및 버그 수정 사항이 포함되어 있습니다.
   * [릴리스 노트](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)

### 사용자 도움말

* **클라우드 서비스로 AEM 사용 - 역할 기반 권한**

   Cloud Manager에는 적절한 권한이 있는 미리 구성된 역할이 있습니다. 각 역할에는 각 역할과 연관된 특정 권한, 사전 구성된 작업 또는 권한이 있습니다. 역할 [기반 권한](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/what-is-required/role-based-permissions.html) 도움말 항목에서는 사용 가능한 기능과 이를 실행할 수 있는 역할을 식별합니다.

* **클라우드 서비스로 AEM - 발송자**

   Dispatcher [및 CDN](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#dispatcher-cdn) 및 [Explicit Dispatcher 캐시 무효화](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#explicit-invalidation) 섹션이 사용 가능한 옵션과 작동 방식을 명확히 하기 위해 업데이트되었습니다.

* **브랜드 포털에서 AEM 자산 구성**

   AEM Assets는 이제 [!UICONTROL Adobe I] /O를 통해 브랜드 포털로 구성되며, 브랜드 포털 임차인의 승인을 위해 IMS 토큰을 조달합니다. 이전에는 기존 OAuth 게이트웨이를 통해 클래식 인터페이스에서 [!UICONTROL 구성되었습니다.]
브랜드 [포털에서 AEM 자산 구성을 참조하십시오](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/publish/configure-aem-assets-with-brand-portal.html).

* **클라우드 서비스로 AEM 사용 - 다이내믹 미디어의 스마트 자르기**

   다이내믹 미디어 구성 요소에서 스마트 자르기 작업을 할 때 AEM에서 새 옵션을 클라우드 서비스로 사용할 수 있습니다.

   **종횡비 일치** 활성화 - Dynamic Media에서 원본 이미지의 종횡비와 가장 일치하는 스마트 자르기 변환을 선택하도록 하려면 이 옵션을 선택합니다.
스마트 [자르기 작업 시기를 참조하십시오](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/adding-dynamic-media-assets-to-pages.html#when-working-with-smart-crop).

### 커뮤니티

* **AEM Skilt Builder 웨비나**

   * AEM Sites - 2020년 3월 17일부터 콘텐츠 작성의 기본 구성 요소와 AEM Sites의 기본 개념 및 운영에 대해 학습합니다. [지금](https://aemskillbuilder-sites.experienceleague.adobeevents.com/register)등록하십시오.
   * AEM Assets - 2020년 3월 19일부터 디지털 자산 관리에 대한 전문 지식을 갖추고 브랜드 포털, 다이내믹 미디어, [!UICONTROL 에셋] 링크 [!UICONTROL 등에 대한 기본 사항을 살펴보십시오] . [지금](https://aemskillbuilder-assets.experienceleague.adobeevents.com/register)등록하십시오.

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

### Campaign Classic

* [Campaign Classic 19.1.4 업데이트](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### 추가 리소스

* Adobe Campaign Standard: [설명서](https://helpx.adobe.com/support/campaign/standard.html) - [릴리스 노트](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [기능 비디오](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [릴리스 계획](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [설명서](https://helpx.adobe.com/support/campaign/classic.html) - [릴리스 노트](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [기능 비디오](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign 제어판: [설명서](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [릴리스 노트](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

2020년 2월 10일에 업데이트됨, 2월 8일 릴리스 기준:

| 보기 | 기능 |
|------|---------|
| [!UICONTROL 포트폴리오] | You can now add [!DNL Yahoo!] Japan Display Network (YDN) campaigns to portfolios to optimize the campaign budgets and ad group-level bids. 같은 입찰이 한 광고 그룹의 모든 광고에 적용됩니다. 일본 디스플레이 네트워크 캠페인에 대한 데이터는 포트폴리오의 시뮬레이션에 포함됩니다. |
| [!UICONTROL 검색] > [!UICONTROL 일괄 시트] | 이제 일괄 시트를 사용하여 Google RSA(Responsive Search Ads)를 생성, 편집 및 삭제할 수 있습니다. 이전에는 **[!UICONTROL 검색]** > **[!UICONTROL 캠페인]**&#x200B;의 기본 캠페인 관리 인터페이스를 통해서만 지원할 수 있었습니다. |
| [!UICONTROL 검색] > [!UICONTROL 캠페인, 보고서] | Google Ads 강조 지표 `Impr. (Abs. Top) %` 및 `Impr. (Top) %`은(는) 이제 [!UICONTROL 캠페인 일일 노출 횟수 공유] 및 [!UICONTROL 키워드 일별 노출 횟수 공유] 보고서와 레이블 및 구속 조건 보기에서 쇼핑 제품 그룹을 제외한 모든 기본 보고서 및 엔티티 수준 캠페인 관리 보기로 사용할 수 있습니다. |

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

## 새로운 설명서 및 자습서 {#selfhelp}

새로운 기능 및 최근 자가 도움말 문서 및 비디오 <!--`https://jira.corp.adobe.com/secure/Dashboard.jspa?selectPageId=60327`-->

| 솔루션 | 컨텐츠 | 설명 |
|----------| -----------| ---------- |  
| [!UICONTROL AEM Commerce] | 비디오 - [여러 카테고리 및 제품 페이지 만들기](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/04-style-cif-component.md) | CIF 코어 구성 요소를 사용하여 고객 프로젝트의 시작점으로 AEM(Adobe Experience Manager) CIF 프로젝트를 최대화하는 방법을 알아봅니다. 테마 및 CSS 스타일링을 구성 요소에 적용하고 원형에서 생성된 새로운 AEM CIF 프로젝트를 검사할 수 있습니다. 또한 CIF 핵심 구성 요소에서 사용되는 CSS 및 JavaScript를 구성하는 방법도 살펴봅니다. |
| [!UICONTROL AEM 양식] | 아티클 - [OKTA를 사용하여 AEM 작성자 인증](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/single-sign-on-with-okta.html) | OKTA 포털에서 앱을 구성하는 방법과 새 응용 프로그램 등록에 일반적으로 사용하는 설정에 대해 알아봅니다. |
| [!UICONTROL AEM Commerce] | 자습서 - [CIF 핵심 구성 요소 사용자 정의](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/05-customize-cif-components.md) | 일반적으로 CIF 코어 구성 요소 및 AEM에서 제공하는 여러 가지 확장 지점을 검토하십시오. CIF 핵심 구성 요소는 Adobe Experience Manager(AEM) 및 Magento 솔루션을 통합하는 프로젝트를 가속화하는 데 사용할 수 있는 표준 상거래 구성 요소 집합을 제공합니다. |
| [!DNL Adobe Campaign] - 대상 | Video - [Create an audience...](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/creating-audiences-using-segment-builder.html) | Adobe Experience Platform 세그먼트 빌더를 사용하여 Campaign Standard에서 [!UICONTROL 대상을 만듭니다]. 대상 모듈을 통해 Adobe Campaign Standard 내에서 직접 이 기능에 액세스할 [!UICONTROL 수] 있습니다. |
| [!DNL Adobe Campaign] - 대상 | 비디오 - [마케팅 워크플로우에서 Adobe Experience Platform 대상자 활성화](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/activating-aep-audiences.html) | 대상 읽기 활동을 사용하여 [!UICONTROL 워크플로우 내에서 데이터 서비스] 쿼리 대상을 활성화하는 [!UICONTROL 방법을] 알아봅니다. |
| [!DNL Adobe Campaign] | 자습서 - [Android를 사용한 푸시 알림](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/getting-started-push-notifications/getting-started-with-push-notifications-android.html) | 개인화되고 세그먼트화된 푸시 알림을 iOS 및 Android 모바일 디바이스로 전송할 수 있습니다. 이 자습서는 Adobe Campaign에서 푸시 알림을 전송하고 Android 앱에서 이러한 알림을 받는 것과 관련된 단계를 안내합니다. |
| [!DNL Adobe Campaign] | 비디오 - [푸시 알림 만들기](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/creating-a-push-notification.html) | Adobe Campaign Standard에서 푸시 알림을 만듭니다. 개인화되고 세그먼트화된 푸시 알림을 iOS 및 Android 모바일 디바이스로 전송할 수 있습니다. |
| [!DNL Adobe Campaign] - AEP 데이터 커넥터 | 비디오 - [데이터 수집 작업의 상태 확인](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/checking-status-of-data-ingestion-jobs.html) | 데이터 통합 작업의 상태와 데이터가 Adobe Campaign Standard에서 Adobe Experience Platform으로 인제스트되었는지 확인하는 방법을 알아봅니다. |
| [!DNL Adobe Campaign] - AEP 데이터 커넥터 | 비디오 - [데이터 매핑 수정](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/modifying-data-mapping.html) | 상태를 확인하고 데이터 매핑을 수정하는 방법을 알아봅니다. |
| [!DNL Adobe Campaign] - AEP 데이터 커넥터 | 비디오 - [경험 이벤트 매핑](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-experience-events.html) | Adobe Experience Platform에서 경험 이벤트를 매핑하는 방법을 알아봅니다. |
| [!DNL Adobe Campaign] - AEP 데이터 커넥터 | 비디오 - [사용자 정의 리소스 매핑](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-custom-resources.html) | Adobe Campaign Standard와 Adobe Experience Platform 간에 서로 다른 데이터 유형을 매핑하는 방법을 알아봅니다. |
| [!DNL Adobe Campaign] - AEP 데이터 커넥터 | 비디오 - [Adobe Experience Platform 데이터 커넥터 이해](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/understanding-the-adobe-experience-platform-data-connector.html) | Adobe Experience Platform에서 XTK 데이터(Campaign에서 인제스트된 데이터)를 XDM(Experience Data Model) 데이터에 매핑하여 Adobe Experience Platform에서 데이터를 제공하는 방법을 알아봅니다. |
| [!DNL Adobe Campaign] - AEP 데이터 커넥터 | 비디오 - [시드 테이블 데이터 매핑](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-seed-table-data.html) | Adobe Experience Platform을 사용하여 시드 데이터를 매핑하고 프로파일을 테스트하는 방법을 알아봅니다. |
| [!DNL Adobe Campaign]- 대상 | 비디오 - [플랫폼 대상에 대한 게재의 타깃팅 차원 변경](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/changing-targeting-dimension.html) | Adobe Campaign Standard의 기본 프로필 테이블 외부에 있는 플랫폼 대상에 대한 게재의 타깃팅 차원을 변경하는 방법을 알아봅니다. |
| [!DNL Adobe Campaign] | 비디오 - [Snowflake의 빅데이터 관리](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Adobe Campaign Classic에서 Snowflake 커넥터를 활용할 수 있습니다. |
| [!DNL Adobe Campaign] - 대상 | 아티클 - [대상 대상(베타) - 개요](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/audience-destinations-overview.html) | Adobe Campaign Standard에서 마케팅 캠페인을 위해 Adobe Experience Platform의 중앙 집중식 및 통합 프로필 데이터를 활용하는 방법을 살펴볼 수 있습니다. |
| [!DNL Adobe Target] - Mobile SDK | 자습서 - [Adobe Target을 사용하여 앱 경험 개인화](https://docs.adobe.com/content/help/en/target-learn/mobile-sdk-v4-android/overview.html) | Android 앱에서 Adobe Target을 구현합니다. Mobile Services SDK 설정의 유효성을 확인하고 콘텐츠 사전 가져오기, 차단 요청 등과 같은 [!DNL Target] 요청을 구현합니다. |
| Adobe Analytics | 비디오 - [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-high-tech.html) | 2019년 Summit에서 첨단 기술 &quot;수퍼 세션&quot;에서 선별된 클립을 볼 수 있습니다. |
| Adobe Analytics | 비디오 - [고객 경로 분석의 계산된 지표 소개](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/introduction-to-calculated-metrics-in-customer-journey-analytics.html) | 고객 경로 분석에서 계산된 지표를 [!UICONTROL 만드는] 기본 [!UICONTROL 사항을 살펴봅니다]. |
| Adobe Analytics | 비디오 - [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-travel.html) | Summit 2019에서 여행 및 숙박 세션에서 선별된 클립을 볼 수 있습니다. |
| Adobe Analytics | 비디오 - [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-retail.html) | Summit 2019에서 소매 세션을 통해 선별된 클립을 확인할 수 있습니다. |
| Adobe Analytics | 비디오 - [고객 활용 사례:고객 경험에 대한 강조로 매출 증대](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/accent-group-invests-in-customer-experience-to-drive-sales.html) | 강조 그룹이 Adobe Experience Cloud를 사용하여 매끄러운 디지털 경험을 제작하는 방법을 살펴보십시오. |
| Adobe Analytics | 비디오 - [고객 활용 사례:ServiceNow, 잠재 고객과 교류하기 위한 올바른 인사이트 확보](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/servicenow-gets-the-right-insights-to-connect-with-prospects.html) | Adobe Advertising Cloud 및 Adobe Analytics를 사용하여 마케팅 채널에서 실행 가능한 데이터를 [!DNL ServiceNow] 얻고 유료 검색 광고의 ROI를 높이는 방법을 살펴볼 수 있습니다. |
| Adobe Analytics | 비디오 - [Adobe Analytics - 고객 인텔리전스를 위한 데이터 그 이상의 기능](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-analytics-customer-intelligence.html) | 데이터 기반의 마케팅과 분석 성숙도를 데이터에서 인사이트, 실행으로 전환하는 방법을 살펴볼 수 있습니다. |
| Adobe Analytics | 비디오 - [Adobe Sensei 및 Adobe Analytics - Extended 버전](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-sensei-and-adobe-analytics.html) | 예외 항목 탐지, 기여도 분석, [!DNL Sensei,] 지능형 [!UICONTROL 경고,] 클러스터링, [!UICONTROL 성향 IQ, 성향 IQ,]    [!UICONTROL 세그먼트 모델링 등 Adobe에서 제공하는 Adobe Analytics의 주요 기능을 볼 수 있습니다.] |
| Adobe Analytics | 비디오 - [Adobe Analysis Workspace를 통해 비즈니스 혁신](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/how-adobe-analysis-workspace-can-change-your-business.html) | 분석 작업 공간을 사용하여 애드혹 분석, 유연한 분석, 집단 분석 및 폴아웃 분석을 수행할 수 있는 방법을 [!UICONTROL 알아봅니다]. 또한 분석 작업 환경을 회사의 모든 사람과 공유할 수 있으며 드래그 앤 드롭 기능을 통해 모든 사람이 데이터를 손쉽게 분석하고 통찰력을 신속하게 얻을 수 있습니다. |
| Adobe Analytics | 비디오 - [고객 활용 사례:The Home Depot, 고객 경험 관리와 함께 혁신적인 제품 선보여](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/the-home-depot-innovates-with-customer-experience-management.html) | Adobe 솔루션을 [!DNL Home Depot] 사용하여 개인화된 맞춤형 쇼핑 경험을 통해 브랜드 충성도 및 고객 만족도를 높이는 방법을 살펴볼 수 있습니다. |
| Adobe Analytics | 프레젠테이션 - [고객 여정 분석 이해](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/understanding-customer-journey-analytics.html) | Adobe의 고객 여정 [!UICONTROL 분석을]기반으로 구축된 애플리케이션 서비스인 [!DNL Adobe Experience Platform]Adobe의 고객 여정 [!UICONTROL 분석을 통해 Adobe Experience Platform을] 활용할 수 있습니다. 이 기능을 사용하면 모든 [!DNL Adobe Experience Platform] 데이터 세트에 대해 멀티채널 분석을 수행할 수 있습니다. |
| Adobe Analytics | 비디오 - [CJA의 크로스 채널 속성](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/cross-channel-attribution-in-customer-journey-analytics.html) | 시각화를 사용하여 고객 경로 분석의 모든 채널에서 기여도를 표시(크레딧을 제공)하는 방법을 [!UICONTROL 알아봅니다]. |
| Adobe Analytics | 아티클 - [Adobe Analytics 학습 여정을 계속하기 위한 고객 팁](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/tips-and-tricks/customer-tips-for-continuing-your-adobe-analytics-learning-journey.html) | Adobe Analytics를 최대한 활용할 수 있는 방법에 대한 팁과 기법을 보유한 세 명의 Adobe 고객을 만나보십시오. |
| Adobe Analytics | 비디오 - [CJA에서 크로스 채널 시각화 만들기](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/creating-cross-channel-visualizations-in-customer-journey-analytics.html) | 고객 [!UICONTROL 경로 분석을] 통해 방문자당 데이터 병합을 포함하여 여러 채널에 걸쳐 여러 데이터 세트의 데이터를 포함하는 시각화를 만드는 방법을 살펴볼 수 있습니다. |
| Adobe Analytics | 비디오 - [계산된 지표를 Adobe Analytics에서 고객 여정 분석으로 이동](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/moving-your-calculated-metrics-from-adobe-analytics-to-customer-journey-analytics.html) | 고객 여정 분석에서 Analytics 관련 지표를 다시 만드는 데 [!UICONTROLC필요한] 팁을 [!UICONTROL 찾으십시오]. |
