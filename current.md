---
title: Adobe Experience Cloud 릴리스 노트
description: Experience Cloud 릴리스 노트 템플릿
doc-type: 릴리스 노트
last-update: 2019년 8월
author: mfrei
translation-type: tm+mt
source-git-commit: 6e1d9c4b083968fe1632d1309900058c90206fe1

---


# 미리 체험하기 - Adobe Experience Cloud 릴리스 노트

Adobe Experience Cloud의 새로운 기능 및 수정 사항.

>[!IMPORTANT]
>
>이 페이지에는 출시 전 컨텐츠가 포함되어 있으며 계획된 출시 전에 변경될 수 있습니다.

>[!NOTE]
>
>예정된 릴리스에 대한 이메일 알림을 받으려면 [Adobe 우선 제품 업데이트](https://www.adobe.com/subscription/priority-product-update.html)에 가입하십시오. 업무일 기준으로 릴리스 3-5일 전에 공지를 받게 됩니다. 릴리스 후 게시된 새 정보는 발행 날짜로 표시됩니다.

**릴리스 날짜: 2019년 8월**

* [Experience Platform 및 관리](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (솔루션 도움말에 링크)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (솔루션 도움말에 링크)

## [!UICONTROL Experience Platform] 및 관리 {#platform}

[!UICONTROL Experience Platform], Experience Cloud 인터페이스, 제품 관리, Experience Platform Launch, Identity Service 및 보안 게시판에 대한 릴리스 정보입니다.

* [Experience Cloud 인터페이스](#core-services)
* [Experience Platform Launch](#launch)
* [보안 게시판 및 권고 조치](https://helpx.adobe.com/security.html) (모든 Adobe 제품)

### Experience Cloud 인터페이스 {#core-services}

* Experience Cloud 로그인 시 일부 사용자의 세션이 로그아웃되는 중요한 문제를 해결했습니다. (MCUI-6908)
* 성능을 개선하고 지연을 줄이도록 Experience Cloud 로그인을 업데이트했습니다. (MCUI-6854, MCUI-6869, MCUI-6883)
* 인터페이스 외관이 업데이트되었습니다. (MCUI-6861, MCUI-6911, MCUI-6862)
* [!UICONTROL Trigger] 정의에서 _Like_ 절을 잘못 해석하는 Experience Cloud [!UICONTROL Triggers] 문제를 수정했습니다. (MCUI-6611)

제품 설명서의 [경우 Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html)를 참조하십시오.

### Experience Platform Launch {#launch}

릴리스 노트 및 제품 설명서는 [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) 를 참조하십시오.

## [!DNL Analytics] {#analytics}

Adobe Analytics의 새로운 기능 및 수정 내용:

* [Adobe Analytics의 새로운 기능, 향상된 기능 및 수정 내용](#aa-features)
* [Analytics 관리자에 대한 중요 공지](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Adobe Analytics의 새로운 기능, 향상된 기능 및 수정 내용 {#aa-features}

| 기능 | 설명 |
| -----------| ---------- |  
| SameSite 쿠키 설정 지원 | [SameSite 쿠키 설정](https://web.dev/samesite-cookies-explained)이 Analytics에서 설정된 모든 쿠키 집합에 추가됩니다. 이 변경 사항에 따라 SameSite 쿠키 필드를 요구하는 Chrome 변경 사항을 준수하게 됩니다. Analytics 쿠키는 기본적으로 `none`(으)로 설정됩니다. 자사 도메인(예: stats.domain.com)을 독점적으로 사용하는 경우, Adobe ClientCare를 자사 수집 도메인에 대해 `lax`(으)로 설정할 수 있습니다. |
| 작업 영역: 드롭다운 필터의 항목 제한을 50개에서 200개로 늘림 | 드롭다운 필터에 배치할 수 있는 항목 제한을 50개에서 200개로 늘렸습니다. 이 개선 사항은 필터에 모든 국가(195) 추가, 모든 미국 주 및 도(52) 추가와 같은 다양한 활용 사례를 포용합니다. |
| 기여도 IQ에 대해 A 4 T 활동 노출 및 활동 전환이 활성화됨 | 기여도 IQ에 대해 두 개의 A4T(Analytics for Target) 지표(활동 노출 횟수 및 활동 전환율)를 활성화했습니다. 현재까지 Analysis Workspace에서 이러한 지표는 Reports &amp; Analytics와 비교하여 부풀려졌습니다. 이러한 변화를 통해 사용자는 이제 "동일한 터치" 기여도 모델을 적용하여 보고 및 분석과 함께 분석 작업 공간을 가져올 수 있습니다. |

#### 수정 사항

* 전체 화면 모드에 있는 동안 실시간 보고서의 텍스트 표시 문제를 해결했습니다. (AN-183168)

### [!DNL Analytics] 관리자에 대한 중요 공지{#aa-notices}

| 알림 | 추가한 날짜 또는 업데이트한 날짜 | 설명 |
| -----------| ---------- | ---------- |
| 이전 시간대 오프셋 지원 | 2019 년 8 월 8 일 | 이제 Analytics는 타임스탬프가 지정된 히트에 대한 시간대 오프셋을 자동으로 처리합니다. 8 월 8 일에 이 변경 사항을 따르면, 내역 처리를 위해 데이터에 로드되는 시스템은 데이터를 보내기 전에 더 이상 시간대 오프셋을 조정하지 않아도 됩니다. |
| 분류 규칙 빌더 제한 | 2019년 6월 5일에 추가됨 | 이러한 제한 사항은 새로운 것이 아니지만 여기에 설명서가 [추가되었습니다](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| 새로운 세그먼트 연산자 제한 | 2019년 5월 31일에 추가됨 | 2019년 7월 18일부터 세그먼트 연산자 _임의 항목 포함_, _임의 항목 포함하지 않음_, _모두 포함_ 및 _모두 포함하지 않음_&#x200B;은 입력 필드당 100단어로 제한됩니다. 이 날짜 이후로 모든 신규 세그먼트와 수정된 세그먼트에 제한이 적용됩니다. 제한을 초과하는 기존 세그먼트는 계속 지원되지만 입력 필드가 감소될 때까지 수정하거나 저장할 수 없습니다. 이 제한은 쿼리 성능을 향상시키기 위한 지속적인 노력의 일환으로 적용됩니다. |
| **[!UICONTROL 활성화된 날짜]** 및 **[!UICONTROL 숫자 2 분류]**&#x200B;에 대해 예정된 지원 변경 사항 | 업데이트 날짜: 2019년 5월 28일 | 숫자 2와 활성화된 날짜 분류를 가져오는 기능이 코드 베이스에서 제거되었습니다. 이 변경 사항은 2019년 7월 유지 관리 릴리스에 적용됩니다. 가져온 파일에 숫자 또는 활성화된 날짜 열이 있는 경우 해당 셀은 자동으로 무시되며, 해당 파일의 다른 모든 데이터는 정상적으로 가져와집니다. <br/>기존 분류는 여전히 표준 분류 워크플로우를 통해 내보낼 수 있으며, 보고에서 계속 사용할 수 있습니다. |
| _보고서 총계_ 계산과 관련한 변경 예정 | 업데이트 날짜: 2019년 7월 9일 | **2019년 6월 18일**&#x200B;에 Adobe Analytics는 모든 차원 및 지표에서 _보고서 총계_ 를 동일하게 변경할 예정입니다. 이를 통해 일부 보고서(예를 들어 Prop 또는 고객 특성 보고서)의 총계가 변경됩니다. 본 변경에 앞서 일부 보고서 총계는 보고서에서 _미지정_ 으로 표시되는지의 여부와 관계없이, 총계의 _미지정_ 라인 항목에 일관성 없이 포함되거나 제외됩니다. <br/>2019년 6월 18일부터, _미지정_ 항목은 보고서의 라인 항목으로 표시되지 않는 경우에도 보고서 총계에 항상 표시됩니다. 또한 _exists_ 또는 _does not exist_ 로직을 사용하는 세그먼트는 이 변경 후 일부 차원에 대해 다른 결과를 볼 수 있습니다. 특히 _Unspecified_&#x200B;에 레퍼러 유형 차원에 대한 "Typed/Bookmarked" 라인 항목 또는 장치 유형 차원에 대한 "Other" 라인 항목 등의 특수 이름이 있는 차원입니다. 본 변경은 Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder 및 Reporting API에 적용됩니다. |
| [!DNL Analysis Workspace] 에서 CSV 다운로드로 업데이트 | 2019년 4월 10일 | 2019년 4월 11일부터, [!DNL Analysis Workspace]의 **[!UICONTROL CSV 다운로드]** (및 **[!UICONTORL 클립보드로 복사]**)가 변경되어 내보낸 데이터의 형식을 제거할 수 있습니다.  <ul><li>천 단위 구분 기호가 더 이상 포함되지 않습니다. 소수점 구분 기호는 계속해서 포함되며, **[!UICONTROL 구성 요소 &gt; 보고서 설정 &gt; 천 단위 구분 기호]**&#x200B;에 정의된 형식을 따릅니다. 참고: 쉼표를 소수점 구분 기호로 사용하는 숫자 값은 내보낸 CSV에서 계속 따옴표로 표시됩니다.</li><li>통화 기호가 표시되지 않습니다.</li><li>퍼센트 기호가 표시되지 않습니다. 백분율은 10진수 형식입니다. 예를 들어, 75%는 0.75로 표시됩니다.</li><li>시간은 초 단위로 표시됩니다.</li><li>집단 테이블은 원시값만 표시합니다. 백분율이 제거됩니다.</li><li>숫자가 올바르지 않으면 빈 셀이 표시됩니다.</li></ul> |
| [!DNL Analysis Workspace] 디버거 명령 변경 예정 | 2019년 4월 4일 | **2019년 6월 13일**&#x200B;에 [!DNL Analysis Workspace] 디버거를 켜는 콘솔 명령이 adobeTools.debug.includeOberonXml로 변경됩니다. adobe.tools.debug.includeOberonXml은 이 날짜 이후에 작동이 중지됩니다. |
| 모바일 브라우저 버전 번호 | 2019년 2월 7일 | 2019년 1월 8일부터 모바일 브라우저 버전 번호의 자르기 레벨이 2에서 1로 변경되었습니다. 1월 8일부터는 버전에 첫 두 개 레벨만 표시됩니다(예: _Firefox 64.0.2_&#x200B;가 이제 _Firefox 64.0_&#x200B;으로 보고됨). |
| [!DNL Ad Hoc Analysis] 판매 종료 | 2019년 1월 29일 | 2018년 8월 6일, Adobe는 [!DNL Ad Hoc Analysis] 판매 종료 의사를 발표했습니다. 수명 종료 날짜는 확정된 후 공유될 예정입니다.<br/>이 기간 동안의 Java 호환 버전 등 자세한 정보는 [Discover Workspace](https://adobe.ly/discoverworkspace)를 참조하십시오. |
| 짧은 [!DNL Analytics] 보고서 링크 | 2019년 1월 14일 | 1년 안에 방문하지 않은 짧은 [!DNL Analytics] 보고서 링크는 롤링 일정에서 2019년 1월 17일 목요일부터 정리되고 삭제됩니다. |
| TLS 1.0 지원 종료 | 업데이트 날짜: 2019년 1월 10일 | 2019년 2월 11일부터 Adobe Analytics 보고에서는 더 이상 TLS(Transport Layer Security) 1.0 암호화를 지원하지 않습니다. 이 변경은 가장 높은 보안 표준을 유지하고 고객 데이터의 안전을 홍보하기 위해 진행 중인 노력의 일환입니다. If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/server-side-forwarding/ssf-requirements.html).<br/>[!DNL Analytics] 2019년 2월 20일부터 Adobe 데이터 수집에서는 더 이상 TLS 1.0을 지원하지 않습니다. 이 변경으로, Adobe에서는 더 이상 TLS 1.1 이상을 지원하지 않는 이전 장치 또는 웹 브라우저를 사용하는 최종 사용자의 Analytics 데이터를 수집하지 않습니다. 이렇게 해도 고객 데이터 또는 보고에 큰 영향을 주지는 않습니다. (웹 사이트에서 TLS 1.0을 지원하지 않는 경우는 영향을 받지 않습니다.) <br/>2019년 4월 11일부터 Adobe Analytics Reporting API는 더 이상 TLS 1.0 암호화를 지원하지 않습니다. API에 액세스하는 고객은 자신들에게 영향이 없는지 확인해야 합니다. <ul><li>기본 설정으로 Java 7을 사용하는 API 클라이언트는 [TLS 1.2를 지원하도록 수정](https://www.java.com/en/configure_crypto.html)해야 합니다. (_클라이언트 종단점에 대한 기본 TLS 프로토콜 버전을 TLS 1.0에서 TLS 1.2로 변경_ 을 참조하십시오.) </li><li>Java 8을 사용하는 API 클라이언트는 기본값 설정이 TLS 1.2이므로 영향을 받지 않습니다.</li><li> 다른 프레임워크를 사용하는 API 클라이언트의 경우 TLS 1.2 지원에 대한 자세한 내용을 알려면 해당 공급업체에 문의해야 합니다.</li></ul> |
| 데이터 피드: post_product_list 열 - 크기 변경 | 2019년 1월 9일 | Adobe는 2019년 2월 7일부터 post_product_list 열 크기를 64KB에서 16MB로 늘렸습니다. 이러한 변경으로 인해 처리 중에 post_product_list에 추가된 머천다이징 eVar 값이 제품 및 수익 값을 자르지 않아도 됩니다. post_product_list 값을 수집하는 프로세스가 있는 경우 해당 프로세스가 길이에서 최대 16MB의 값을 처리할 수 있는지 확인하거나 데이터 수집 실패를 방지하기 위해 16KB에서 값을 자릅니다. |
| 비활성 [!DNL Analytics Live Stream] 종단점에 영향을 주는 관리 변경 사항 | 2018년 12월 20일 | 2019년 2월 1일부터 90일 동안 활성 소비자 연결이 없는 [!DNL Live Stream] 종단점은 비활성화될 수 있습니다. 고객 지원 담당자에게 연락하여 [!DNL Live Stream] 종단점에 대해 문의하고, 필요한 경우 다시 활성화할 수 있습니다. 또한 소비자 프로세스가 서비스 설계에 의도한 대로 지속적 연결을 유지하도록 하고, 연결이 끊기거나 중단되는 경우 다시 연결하도록 구현되어 있는지 확인하십시오. |
| TLS 1.0에 대한 지원 종료로 인해 Adobe [!DNL Report Builder] 업데이트 | 2018년 9월 7일 | TLS 1.0에 대한 지원 종료로 인해 Adobe는 [!DNL Report Builder] 사용자가 2019년 2월 이전에 버전 v5.6.21을 다운로드하도록 권장했습니다. 이 날짜 이후, 이전 버전의 [!DNL Report Builder]는 더 이상 작동하지 않습니다. |

### AppMeasurement {#appm}

2019년 8월 8일에 [!UICONTROL AppMeasurement] 2.16.0이 릴리스됩니다.

| 기능 | 설명 |
| -----------| ---------- |
| 종료 링크에 대한 `sendBeacon` 지원 | [!UICONTROL AppMeasurement]에 종료 링크에 대한 `sendBeacon` 지원 기능을 구현했습니다. 이를 통해 종료 링크 추적 기능이 개선되고 트래픽이 증가할 수 있습니다. |
| ECID/fid 값 | 이제 OptIn 설정이 변경되더라도 ECID/fid 값이 첫 번째 히트에 캐시됩니다. |
| DIL 9.3 | 대상 관리 모듈의 DIL 9.3 업데이트 |
| 스크롤 도달 추적 | s.ActivityMap.trackScrollReach에 스위치를 노출하여 스크롤 도달 추적을 켜거나 끕니다. |
| 방문자 ID 서비스 4.4.0 | 방문자 ID 서비스 4.4.0을 사용하도록 AppMeasurement를 업그레이드했습니다. |

#### 수정 사항

* isReadyToTrack이 true가 되기 전에 발생한 AppMeasurement 큐의 버그를 수정했습니다.

다음 플랫폼에 대한 [AppMeasurement 릴리스 내역](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)이 필요하면 AppMeasurement 릴리스 내역을 참조하십시오.

* JavaScript
* iOS
* Android
* Flash-Flex
* OSX
* Windows Phone, XBOX, Silverlight 및 .NET
* [!DNL BlackBerry]
* Java
* PHP
* Symbian

## Audience Manager {#aam}

**수정 사항 및 향상된 기능**

* 이제 관리 권한이 있는 사용자 계정에만 관리 탭이 표시됩니다(AAM-48557).
* 이제 목록 사용자 API가 전체 사용자 세부 사항을 반환합니다(AAM-48662).
* 이제 트레이트 폴더 목록의 크기를 조정할 수 있습니다(AAM-48800).
* 여러 UI 액세스 가능성이 최적화되었습니다(AAM-48865, AAM-48933).
* 관리 및 Data Sources 페이지에 대한 로드가 최적화되었습니다(AAM-48514).

## [!DNL Campaign] {#ac}

Adobe Campaign은 온라인 및 오프라인 마케팅 채널 간에 직관적이고, 자동화된 방식으로 일대일 메시지를 제공합니다. 이제 고객이 습관 및 선호도에 따라 결정된 작업 환경을 통해 원하는 사항을 예측할 수 있습니다.

### Adobe Campaign Standard

[Campaign Standard 19.3 릴리스](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)

| 기능 | 설명 |
| -----------| ---------- |  
| 외부 API 활동(공개 베타) | 세분화된 개인화를 위해 외부 API 활동을 사용하면 REST API 호출을 통해 외부 시스템의 데이터를 워크플로우로 가져올 수 있습니다. REST 엔드포인트는 고객 관리 시스템, Adobe I/O 런타임 또는 Adobe Experience Cloud REST 엔드포인트(예: 데이터 플랫폼, Target, Analytics, Campaign)일 수 있습니다. 이 기능은 현재 공개 베타 버전에 제공됩니다. 자세한 내용은 [자세한 설명서](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) 및 [사용 방법 비디오를](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html)참조하십시오. |
| 워크플로우 세그먼트에 대한 보고서 | 이 기능을 사용하여 마케터가 세그먼트 코드별로 게재 성능을 분류할 수 있습니다. 워크플로우를 만들고 세그멘테이션 활동을 사용하여 세그먼트를 게재 모집단에 할당할 때, 이제 이러한 세그먼트는 동일한 게재로 분류될 수 있습니다. 이렇게 하면 단일 게재 내의 여러 세그먼트를 기반으로 한 열기/클릭 통계를 표시할 수 있습니다. 자세한 내용은 [자세한 설명서](https://docs.adobe.com/content/help/en/campaign-standard/using/reporting/customizing-reports/creating-a-report-workflow-segment.html) 및 [사용 방법 비디오를](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/reporting/report-on-workflow-segments.html)참조하십시오. |

### Adobe Campaign Classic

[Campaign Classic 19.1.3 업데이트](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - Build 9031

### Adobe Campaign 제어판

[새 제어판 기능에는](https://helpx.adobe.com/campaign/kb/control-panel-instance-settings.html) 캠페인 Classic 이 데이터/파일 전송을 위해 연결하는 URL를 추가하는 기능이 포함됩니다.

[!UICONTROL 제어판]은 AWS에서 호스팅되는 Adobe Campaign Classic 고객과 Adobe Campaign Standard 고객 모두 사용할 수 있습니다. 업그레이드하지 않아도 제어판에 액세스할 수 있습니다.

### 추가 리소스

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)