---
title: Adobe Experience Cloud 릴리스 노트
description: 2019 년 7 월 Experience Cloud 릴리스 노트
doc-type: 릴리스 노트
last-update: 2019년 7월
author: mfrei
translation-type: tm+mt
source-git-commit: 91126cc2d75b6c50afe429a1b4313309ab76108a

---


# 미리 체험하기 - Adobe Experience Cloud 릴리스 노트

Adobe Experience Cloud의 새로운 기능 및 수정 사항.

>[!IMPORTANT]
>
>이 페이지에는 출시 전 컨텐츠가 포함되어 있으며 계획된 출시 전에 변경될 수 있습니다.

>[!NOTE]
>
>예정된 릴리스에 대한 이메일 알림을 받으려면 [Adobe 우선 제품 업데이트](https://www.adobe.com/subscription/priority-product-update.html)에 가입하십시오. 업무일 기준으로 릴리스 3-5일 전에 공지를 받게 됩니다. 릴리스 후 게시된 새 정보는 발행 날짜로 표시됩니다.

**릴리스 날짜: 2019년 7월 18일**

* [Experience Cloud 핵심 서비스 및 관리](#experiencecloud)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Target Standard/Premium 19.6.1](#target)
* [Magento](#magento)

## Core services and administration {#experiencecloud}

[!UICONTROL 플랫폼] 핵심 서비스 및 제품 관리를 포함한 Experience Cloud 인터페이스의 릴리스 노트입니다.

* [Experience Cloud ID 서비스](#ecid)
* [Mobile Services 및 Mobile SDK](#mobile)
* [Experience Platform Launch](#launch)
* [보안 게시판 및 권고 조치](#security)

### Experience Cloud ID 서비스 {#ecid}

**수정 사항 및 업데이트**

* `cookieDomain` 구성 업데이트: `cookieDomain` 라이브러리가 `initConfig` 설정되지 않은 경우 라이브러리에서는 최상위 쿠키 도메인을 자동으로 할당합니다. (CORE-29223)
* Fixed an issue for `getVisitorValue` in `localVisitor`. (CORE-31287)
* Fixed an inconsistency of `MCOPTOUT` value in parent visitor versus iframe child visitor from `getVisitorValue` method. (CORE-29719)
* Jquery 3.2.1의 취약성 문제가 해결되었습니다. (CORE-31183)
* Opt-in update: added `optIn.off` to unsubscribe from events.
* Fixed an issue related to `setTimeout` function. (CORE-30623)

See [Experience Cloud ID Service](https://marketing.adobe.com/resources/help/en_US/mcvid/mcvid-release-notes.html) for cumulative release notes.

### Mobile Services 및 Mobile SDK {#mobile}

iOS 및 Android는 다음과 같이 업데이트되었습니다.

**iOS**

* Adobe Target: All requests now include the client and the `sessionId` in the URL query parameters.
* Adobe Target: 메모리 누수가 수정되었습니다.
* The double encoding of the visitor ID URL, which contains characters such as _%25_, was being flagged in security reviews. 이 문제가 수정되었습니다.

**Android**

* Target: 이제 모든 요청이 URL 쿼리 매개 변수에 클라이언트 및 sessionid를 포함합니다.
* 메시지가 빈 클릭스루 URL로 인해 트리밍되면 Android 앱이 충돌하던 문제가 해결되었습니다.
* The double encoding of the visitor ID URL, which contains characters such as _%25_, was being flagged in security reviews. 이 문제가 수정되었습니다.

제품 설명서는 [Mobile Services](https://docs.adobe.com/content/help/en/mobile-services/using/home.html)를 참조하십시오.

Mobile SDK에 대한 자세한 내용은 [Experience 솔루션용 Android SDK 4.x](https://docs.adobe.com/content/help/en/mobile-services/android/overview.html) 및 [Experience Cloud 솔루션용 iOS SDK 4.x](https://docs.adobe.com/content/help/en/mobile-services/ios/overview.html)를 참조하십시오.

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) (links to product help) for release notes and product documentation.

### Security bulletins and advisories {#security}

See [Security bulletins and advisories](https://helpx.adobe.com/security.html) for important information regarding security vulnerabilities that could affect specific versions of Adobe products.

## [!DNL Analytics] {#analytics}

* [Adobe Analytics의 새로운 기능 및 수정 내용](#aa-features)
* [Analytics 관리자에 대한 중요 공지](#aa-notices)

### 의 새로운 기능:[!DNL Analytics]{#aa-features}

제품 설명서의 경우 [Analytics 도움말 홈](https://docs.adobe.com/content/help/en/analytics/landing/home.html)을 참조하십시오.

| 구성 요소 | 설명 |
| -----------| ---------- |   
| 분석 작업 공간 - 집단 분석 개선 사항 | 새 집단 분석 설정이 추가되었습니다. <ul><li>%만 표시</li><li>가장 가까운 전체 %</li><li>상단의 평균 % 행 표시</li></ul> |
| Analysis Workspace | In the left rail, users now have the option to _Show items from last 18 months_. 이전에는 lookback 기간이 최대 6 개월이었습니다. 따라서 최대 18 개월 전, 전년도의 페이지 또는 캠페인과 비교할 수 있습니다. |
| Analytics 데이터 피드 | Users can now see the history for all feeds that are enabled with the _Make Feed Visible to Customer_ flag. |

#### [!DNL Analysis Workspace] 수정 사항

* 차원을 분류할 때 멀티바이트 문자가 거꾸로 표시되는 문제를 해결했습니다. (AN-180112)
* 시각화 오류 문제를 수정했습니다. 시각화 오류가 발생하면 빨간색 오류 막대가 표시됩니다.(AN-175542)
* 현지화된 환경에서 차원 이름이 영어로 표시되는 문제가 해결되었습니다.(AN-178695)

#### [!DNL Reports & Analytics] 수정 사항

* 실시간 드릴다운 보고서의 라인 그래프가 비어 있는 문제를 해결했습니다. (AN-181690)

### [!DNL Analytics] 관리자에 대한 중요 공지{#aa-notices}

| 알림 | 추가한 날짜 업데이트한 날짜 | 설명 |
| -----------| ---------- | ---------- |
| 분류 규칙 빌더 제한 | 2019년 6월 5일에 추가됨 | These limits are not new, but have been added to the documentation [here](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html). |
| 새로운 세그먼트 연산자 제한 | 2019년 5월 31일에 추가됨 | 2019년 7월 18일부터 세그먼트 연산자 &quot;임의 항목 포함&quot;, &quot;임의 항목을 포함하지 않음&quot;, &quot;모두 포함&quot; 및 &quot;모두 포함하지 않음&quot;은 입력 필드당 100 단어로 제한됩니다. 이 날짜 이후로 모든 신규 세그먼트와 수정된 세그먼트에 제한이 적용됩니다. 제한을 초과하는 기존 세그먼트는 계속 지원되지만 입력 필드가 감소될 때까지 수정하거나 저장할 수 없습니다. 이 제한은 쿼리 성능을 향상시키기 위한 지속적인 노력의 일환으로 적용됩니다. |
| **[!UICONTROL 활성화된 날짜]** 및 **[!UICONTROL 숫자 2 분류]** 에 대해 예정된 지원 변경 사항 | 업데이트 날짜: 2019년 5월 28일 | 숫자 2와 활성화된 날짜 분류를 가져오는 기능이 코드 베이스에서 제거되었습니다. 이 변경 사항은 2019년 7월 유지 관리 릴리스에 적용됩니다. 가져온 파일에 숫자 또는 활성화된 날짜 열이 있는 경우 해당 셀은 자동으로 무시되며, 해당 파일의 다른 모든 데이터는 정상적으로 가져와집니다. <br/>기존 분류는 여전히 표준 분류 워크플로우를 통해 내보낼 수 있으며, 보고에서 계속 사용할 수 있습니다. |
| _보고서 총계_ 계산과 관련한 변경 예정 | 업데이트됨: 2019년 7월 9일 | **2019년 6월 18일** 에 Adobe Analytics는 모든 차원 및 지표에서 _보고서 총계_ 를 동일하게 변경할 예정입니다. 이를 통해 일부 보고서(예: Prop 또는 고객 특성 보고서)의 총계가 변경됩니다. 본 변경에 앞서 일부 보고서 총계는 보고서에서 _미지정_ 으로 표시되는지의 여부와 관계없이, 총계의 _미지정_ 라인 항목에 일관성 없이 포함되거나 제외됩니다. <br/>2019년 6월 18일부터, _미지정_ 항목은 보고서의 라인 항목으로 표시되지 않는 경우에도 보고서 총계에 항상 표시됩니다. Additionally, segments using _exists_ or _does not exist_ logic may see different results for some dimensions after this change, specifically dimensions where _Unspecified_ has a special name such as the &quot;Typed/Bookmarked&quot; line item for Referrer Type dimension or the &quot;Other&quot; line item for the Device Type dimension. 본 변경은 Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder 및 Reporting API에 적용됩니다. |
| [!DNL Analysis Workspace] 에서 CSV 다운로드로 업데이트 | 2019년 4월 10일 | 2019년 4월 11일부터, [!DNL Analysis Workspace]의 **[!UICONTROL CSV 다운로드]** (및 **[!UICONTORL 클립보드로 복사]**)가 변경되어 내보낸 데이터의 형식을 제거할 수 있습니다.  <ul><li>천 단위 구분 기호가 더 이상 포함되지 않습니다. 소수점 구분 기호는 계속해서 포함되며, **[!UICONTROL 구성 요소 &gt; 보고서 설정 &gt; 천 단위 구분 기호]** 에 정의된 형식을 따릅니다. 참고: 쉼표를 소수점 구분 기호로 사용하는 숫자 값은 내보낸 CSV에서 계속 따옴표로 표시됩니다.</li><li>통화 기호가 표시되지 않습니다.</li><li>퍼센트 기호가 표시되지 않습니다. 백분율은 10진수 형식입니다. 예를 들어, 75%는 0.75로 표시됩니다.</li><li>시간은 초 단위로 표시됩니다.</li><li>집단 테이블은 원시값만 표시합니다. 백분율이 제거됩니다.</li><li>숫자가 올바르지 않으면 빈 셀이 표시됩니다.</li></ul> |
| [!DNL Analysis Workspace] 디버거 명령 변경 예정 | 2019년 4월 4일 | **2019년 6월 13일** 에 [!DNL Analysis Workspace] 디버거를 켜는 콘솔 명령이 adobeTools.debug.includeOberonXml로 변경됩니다. adobe.tools.debug.includeOberonXml은 이 날짜 이후에 작동이 중지됩니다. |
| 모바일 브라우저 버전 번호 | 2019년 2월 7일 | 2019년 1월 8일부터 모바일 브라우저 버전 번호의 자르기 레벨이 2에서 1로 변경되었습니다. 1월 8일부터는 버전에 첫 두 개 레벨만 표시됩니다(예: _Firefox 64.0.2_가 이제 _Firefox 64.0_으로 보고됨). |
| [!DNL Ad Hoc Analysis] 판매 종료 | 2019년 1월 29일 | 2018년 8월 6일, Adobe는 [!DNL Ad Hoc Analysis] 판매 종료 의사를 발표했습니다. 수명 종료 날짜는 확정된 후 공유될 예정입니다.<br/>이 기간 동안의 Java 호환 버전 등 자세한 정보는 [Discover Workspace](https://adobe.ly/discoverworkspace)를 참조하십시오. |
| Short [!DNL Analytics] report links | 2019년 1월 14일 | Any short [!DNL Analytics] report links that have not been visited within one year will be cleaned up and deleted starting on Thursday, January 17, 2019, on a rolling schedule. |
| TLS 1.0 지원 종료 | 업데이트 날짜: 2019년 1월 10일 | 2019년 2월 11일부터 Adobe Analytics 보고에서는 더 이상 TLS(Transport Layer Security) 1.0 암호화를 지원하지 않습니다. 이 변경은 가장 높은 보안 표준을 유지하고 고객 데이터의 안전을 홍보하기 위해 진행 중인 노력의 일환입니다. If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/>[!DNL Analytics] 2019년 2월 20일부터 Adobe 데이터 수집에서는 더 이상 TLS 1.0을 지원하지 않습니다. 이 변경으로, Adobe에서는 더 이상 TLS 1.1 이상을 지원하지 않는 이전 장치 또는 웹 브라우저를 사용하는 최종 사용자의 Analytics 데이터를 수집하지 않습니다. 이렇게 해도 고객 데이터 또는 보고에 큰 영향을 주지는 않습니다. (웹 사이트에서 TLS 1.0을 지원하지 않는 경우는 영향을 받지 않습니다.) <br/>2019년 4월 11일부터 Adobe Analytics Reporting API는 더 이상 TLS 1.0 암호화를 지원하지 않습니다. API에 액세스하는 고객은 자신들에게 영향이 없는지 확인해야 합니다. <ul><li>기본 설정으로 Java 7을 사용하는 API 클라이언트는 [TLS 1.2를 지원하도록 수정](https://www.java.com/en/configure_crypto.html)해야 합니다. (_클라이언트 종단점에 대한 기본 TLS 프로토콜 버전을 TLS 1.0에서 TLS 1.2로 변경_ 을 참조하십시오.) </li><li>Java 8을 사용하는 API 클라이언트는 기본값 설정이 TLS 1.2이므로 영향을 받지 않습니다.</li><li> 다른 프레임워크를 사용하는 API 클라이언트의 경우 TLS 1.2 지원에 대한 자세한 내용을 알려면 해당 공급업체에 문의해야 합니다.</li></ul> |
| 데이터 피드: post_product_list 열 - 크기 변경 | 2019년 1월 9일 | Adobe는 2019년 2월 7일부터 post_product_list 열 크기를 64KB에서 16MB로 늘렸습니다. 이러한 변경으로 인해 처리 중에 post_product_list에 추가된 머천다이징 eVar 값이 제품 및 수익 값을 자르지 않아도 됩니다. post_product_list 값을 수집하는 프로세스가 있는 경우 해당 프로세스가 길이에서 최대 16MB의 값을 처리할 수 있는지 확인하거나 데이터 수집 실패를 방지하기 위해 16KB에서 값을 자릅니다. |
| 비활성 [!DNL Analytics Live Stream] 종단점에 영향을 주는 관리 변경 사항 | 2018년 12월 20일 | 2019년 2월 1일부터 90일 동안 활성 소비자 연결이 없는 [!DNL Live Stream] 종단점은 비활성화될 수 있습니다. 고객 지원 담당자에게 연락하여 [!DNL Live Stream] 종단점에 대해 문의하고, 필요한 경우 다시 활성화할 수 있습니다. 또한 소비자 프로세스가 서비스 설계에 의도한 대로 지속적 연결을 유지하도록 하고, 연결이 끊기거나 중단되는 경우 다시 연결하도록 구현되어 있는지 확인하십시오. |
| TLS 1.0에 대한 지원 종료로 인해 Adobe [!DNL Report Builder] 업데이트 | 2018년 9월 7일 | TLS 1.0에 대한 지원 종료로 인해 Adobe는 [!DNL Report Builder] 사용자가 2019년 2월 이전에 버전 v5.6.21을 다운로드하도록 권장했습니다. 이 날짜 이후, 이전 버전의 [!DNL Report Builder]는 더 이상 작동하지 않습니다. |

### AppMeasurement {#appm}

2019 년 7 월 15 일 릴리스

**JavaScript 2.15.0**

* Appmeasurememt에 DIL 7.2를 추가했습니다. (AN-175142)
* Experience Cloud ID 서비스 optin 이 true로 설정되고 mid가 페이지 다시 로드 없이 s. t () 호출에 생성되지 않는 문제가 해결되었습니다. (CORE-30890)

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

### Data Workbench {#aa-dwb}

* [로그 (x, b)](https://marketing.adobe.com/resources/help/en_US/insight/client/c_syntx_mtrc_exp.html) 지표 구문 설명서에 대한 도움말 정의를 업데이트했습니다. (AN-180527)

[Data Workbench 릴리스 노트](https://marketing.adobe.com/resources/help/en_US/insight/whatsnew/)에서 최신 정보를 확인하십시오.

## Audience Manager {#aam}

**수정 사항 및 개선 사항**

* [!UICONTROL 세그먼트 개요] 페이지에서 세그먼트 저장소 폴더의 너비가 이제 유연합니다. 이렇게 하면 이름이 긴 세그먼트를 구별할 수 있습니다. (AAM-48400)
* [!UICONTROL 알고리즘 모델에서]도달 및 정확도 **조정** 슬라이더를 이동하는 것이 모델의 도달 또는 정확도에 영향을 주지 않는 문제가 해결되었습니다. (AAM-47996)
* Analytics 대상에서 데이터 내보내기 제어 및/또는 타사 데이터 공유 정책과 충돌하는 세그먼트의. csv 파일을 다운로드할 수 있는 문제가 해결되었습니다. (AAM-48100)
* 고객이 Audience Manager 사용자 인터페이스에 로그인할 때 임의의 &quot;액세스 거부&quot; 오류가 발생하는 문제가 해결되었습니다. (AAM-47632)

## Experience Manager {#aem}

Adobe Experience Manager(AEM)의 새로운 기능, 수정 내용 및 업데이트. 안정성, 보안 및 성능 향상을 위해 최신 패치를 배포하려는 경우 온-프레미스 배포를 사용하는 것이 좋습니다.

### 제품 릴리스

다음 제품에 대한 새로운 기능 정보:

#### Cloud Manager 2019.6.0

The latest Cloud Manager release (2019.6.0) contains a new [Product Update Wizard](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/product-update-wizard/overview-productupdate-wizard.html) to help customers successfully run an AEM update.

* [Cloud Manager 2019.6.0 릴리스 노트](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

#### XML Documentation 3.4

이제 XML Documentation 3.4 솔루션을 사용할 수 있습니다.

***릴리스 노트***

* AEM 6.5에 대한 지원이 추가되었습니다.
* 편집자 변경 사항:
   * 맵 수준 미리 보기를 참조하십시오.
   * Tables - provided an option to copy an `entry` or a `complete` row within a table using copy and paste.
   * 표 - 열에서 여러 셀을 선택 또는 묶거나 병합하는 옵션을 제공했습니다.
   * 표 - 웹 편집기의 작성 모드에서 표 열 속성을 설정하는 방법이 제공됩니다.
   * 표 - 표준 테이블에서 열 비율 및 크기를 조정하는 방법을 제공했습니다.
   * 표 - 작성자 보기에서 행과 열을 선택합니다.
   * 표 - 표 셀 정렬을 위해 웹 편집기에서 활성화된 스타일과 속성 (정렬, 경사) 를 사용할 수 있습니다.
   * 컨텐츠 복사 및 붙여넣기, 컨텐츠 드래그 앤 드롭 등 전체 태그 보기에 대한 버그 수정
   * 편집기 탭에서 주제 제목 표시
   * 웹 편집기에서 성능 문제가 해결되었습니다.
* 번역하는 동안 번역된 컨텐츠로 기준선 전송
* 번역 작업 과정에서 조건 사전 설정을 전송합니다.
* 기준선에서 맵의 모든 종속 항목에 레이블을 적용하는 기능이 추가되었습니다.
* 모든 종속 항목이 있는 맵을 ZIP로 다운로드하는 단추를 제공했습니다.
* 향상된 XHTML-DITA 변환 기능
   * 생성된 Ditamap의 이름이 이제 업로드된 zip 파일의 이름과 동일합니다.
   * 추가 HTML 요소 및 속성에 대한 지원을 추가했습니다.
   * 동시 HTML-ZIP 파일 통합 지원
   * The sub-folder hierarchy where the zip is uploaded (*under input path as configured in h2d_io.xml*), is retained for the generated output (*under the configured output path*).
* 감사 로그를 제공하여 어떤 버전 및 버전으로 복귀했는지 확인했습니다.
* AEM 사이트 재생성:
   * 하위 맵에 대한 재생성 비활성화
   * 재생성 사용 사례에 대해 게시물 생성 워크플로우가 활성화되었습니다.
   * 청크 항목에 대한 재생성 옵션을 비활성화하고, chunked 속성이 적용되는 상위 항목에 대한 옵션을 사용할 수 있도록 합니다.
* 이제 DITA 검색이 AEM 자산 검색에서 작동합니다.
* 결과: 번역 출력 폴더에 저장된 임시 파일을 가져오지 않습니다.
* 기준선 탭:
   * 기준선을 열 때의 성능이 개선되었습니다.
   * 날짜별로 토픽을 선택하여 클라이언트 타임스탬프 작업
* 레이블 삭제를 위한 API.

#### 제품 유지 관리

**AEM 6.2 SP1-CFP20**

2019 년 6 월 6 일 발표된 AEM 6.2 서비스 팩 1-누적 수정 팩 20 (6.2.1.20) 는 2016 년 12 월 AEM 6.2 SP 1의 일반 출시 이후에 출시된 주요 고객 수정 사항을 포함하는 중요한 업데이트입니다.

* [릴리스 노트](https://helpx.adobe.com/experience-manager/release-notes--aem-6-2-cumulative-fix-pack.html)
* [AEM Forms CFP 릴리스](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.3.3.5**

2019 년 7 월 3 일에 발표된 AEM 6.3.3.5는 2017 년 4 월 공식 출시 이후 출시된 주요 고객 수정 사항을 포함하는 중요한 업데이트입니다.

* [릴리스 노트](https://helpx.adobe.com/experience-manager/6-3/release-notes/sp3-release-notes.html)
* [AEM Forms CFP 릴리스](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.4.5.0**

2019 년 7 월 3 일에 발표된 AEM 6.4.5.0는 2018 년 4 월 일반 AEM 6.4 출시 이후 출시된 주요 고객 수정 사항을 포함하는 중요한 업데이트입니다.

* [릴리스 노트](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
* [AEM Forms CFP 릴리스](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.5.1.0**

2019 년 7 월 3 일에 발표된 AEM 6.5.1.0는 2019 년 4 월 일반 AEM 6.5 출시 이후 출시된 주요 고객 수정 사항을 포함하는 중요한 업데이트입니다.

* [릴리스 노트](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
* [AEM Forms CFP 릴리스](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### 사용자 도움말

**AEM 캐시 무효화 업데이트**

An important AEM patch for the AEM 6.5 clientlibs cache invalidation is available by way of the [AEM 6.5.1.0 update](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html) or this [KB article](https://helpx.adobe.com/experience-manager/kb/avoid-crx-quickstart-deletion-in-aem-6-5.html).

### 추가 리소스

* [AEM 6.5 학습 및 지원 홈](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 학습 및 지원 홈](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 학습 및 지원 홈](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 학습 및 지원 홈](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager 사용 안내서](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [이전 버전의 AEM 설명서](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Scene7 Publishing System 릴리스 노트](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre 릴리스 노트](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign은 온라인 및 오프라인 마케팅 채널 간에 직관적이고, 자동화된 방식으로 일대일 메시지를 제공합니다. 이제 고객이 습관 및 선호도에 따라 결정된 작업 환경을 통해 원하는 사항을 예측할 수 있습니다.

릴리스 노트에 대해서는 다음을 참조하십시오.

* Adobe Campaign Classic [19.1.2](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – build 9029
* Adobe Campaign Standard [19.2.3](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-3---june-2019)
* Adobe Campaign Standard [19.2.4](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-4---june-2019)
* Adobe Campaign Standard [19.2.7](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-7---july-2019)

제품 설명서의 경우 다음을 참조하십시오.

* Adobe Campaign Standard: [설명서](https://helpx.adobe.com/support/campaign/standard.html) - [ 릴리스 노트](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [ 기능 비디오](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [설명서](https://helpx.adobe.com/support/campaign/classic.html) - [릴리스 노트](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [ 기능 비디오](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## [!DNL Target] {#target}

See [Target release notes (pre-release)](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) for the latest release infomration about Target.

## Magento {#magento}

Magento Commerce 및 Autonomy 오픈 소스 릴리스 노트에 대한 자세한 내용은 다음을 참조하십시오.

* [Autonomy Open Source 2.3.2 릴리스 노트](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2OpenSource.html)
* [Magento Commerce 2.3.2 릴리스 노트](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2Commerce.html)
