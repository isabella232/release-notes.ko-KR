---
title: Adobe Experience Cloud 릴리스 노트
description: 2019년 7월 Experience Cloud 릴리스 노트
doc-type: 릴리스 노트
last-update: 2019년 7월
author: mfrei
translation-type: ht
source-git-commit: 700dc5c07df31cf744588cd79f6d51c05234c0a0

---


# Adobe Experience Cloud 릴리스 노트

Adobe Experience Cloud의 새로운 기능 및 수정 사항.

>[!NOTE]
>
>예정된 릴리스에 대한 이메일 알림을 받으려면 [Adobe 우선 제품 업데이트](https://www.adobe.com/subscription/priority-product-update.html)에 가입하십시오. 업무일 기준으로 릴리스 3-5일 전에 공지를 받게 됩니다. 릴리스 후 게시된 새 정보는 발행 날짜로 표시됩니다.

**릴리스 날짜: 2019년 7월 18일**

* [Experience Cloud 핵심 서비스 및 관리](#experiencecloud)
* [!DNL Analytics](#analytics) - **(7월 15일에 업데이트됨)**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Target Standard/Premium 19.6.1](#target)
* [Magento](#magento)

## 핵심 서비스 및 관리 {#experiencecloud}

[!UICONTROL 플랫폼] 핵심 서비스 및 제품 관리를 포함한 Experience Cloud 인터페이스의 릴리스 노트입니다.

* [Experience Cloud ID 서비스](#ecid)
* [Mobile Services 및 Mobile SDK](#mobile)
* [Experience Platform Launch](#launch)
* [보안 게시판 및 권고 조치](#security)

### Experience Cloud ID 서비스 {#ecid}

**수정 사항 및 업데이트**

* `cookieDomain` 구성 업데이트: `initConfig`에서 `cookieDomain`이 설정되지 않은 경우 라이브러리에서는 최상위 쿠키 도메인을 자동으로 할당합니다. (CORE-29223)
* `localVisitor`에서 `getVisitorValue`에 대한 문제가 수정되었습니다. (CORE-31287)
* 상위 방문자 수와 iframe 하위 방문자 수의 `MCOPTOUT` 값 불일치가 `getVisitorValue` 방법에서 수정되었습니다. (CORE-29719)
* jQuery 3.2.1의 취약성 문제가 수정되었습니다. (CORE-31183)
* 옵트인 업데이트: 이벤트에서 가입을 해지하기 위해 `optIn.off`를 추가했습니다.
* `setTimeout` 함수와 관련된 문제가 수정되었습니다. (CORE-30623)

누적 릴리스 노트는 [Experience Cloud ID Service](https://marketing.adobe.com/resources/help/ko_KR/mcvid/mcvid-release-notes.html)를 참조하십시오.

### Mobile Services 및 Mobile SDK {#mobile}

iOS 및 Android는 다음과 같이 업데이트되었습니다.

**iOS**

* Adobe Target: 이제 모든 요청에 클라이언트와 `sessionId` 매개 변수가 URL 쿼리 매개 변수에 포함됩니다.
* Adobe Target: 메모리 누수가 수정되었습니다.
* 방문자 ID 서비스: `visitorAppendToURL` 및 `visitorGetUrlVariablesAsync` API는 더 이상 반환 값을 이중 인코딩하지 않습니다. 이중 인코딩으로 해당 API의 반환 값에 특정 보안 검토에 의한 플래그가 지정되었습니다.

**Android**

* Target: 이제 모든 요청에 클라이언트와 sessionId가 URL 쿼리 매개 변수에 포함됩니다.
* 인앱 메시징: 메시지가 빈 클릭 광고 URL로 인해 트리거되면 Android 앱이 충돌하던 문제가 수정되었습니다.
* 방문자 ID 서비스: `Visitor.appendToURL` 및 `Visitor.getUrlVariablesAsync` API는 더 이상 반환 값을 이중 인코딩하지 않습니다. 이중 인코딩으로 해당 API의 반환 값에 특정 보안 검토에 의한 플래그가 지정되었습니다.

제품 설명서는 [Mobile Services](https://docs.adobe.com/content/help/en/mobile-services/using/home.html)를 참조하십시오.

Mobile SDK에 대한 자세한 정보는 [Experience Solutions용 Android SDK 4.x](https://docs.adobe.com/content/help/en/mobile-services/android/overview.html) 및 [Experience Cloud Solutions용 iOS SDK 4.x](https://docs.adobe.com/content/help/en/mobile-services/ios/overview.html)를 참조하십시오.

### Experience Platform Launch {#launch}

릴리스 노트 및 제품 설명서는 [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) (제품 도움말에 대한 링크)를 참조하십시오.

### 보안 게시판 및 권고 조치 {#security}

특정 버전의 Adobe 제품에 영향을 줄 수 있는 보안 취약점에 대한 중요 정보는 [보안 게시판 및 권고 조치](https://helpx.adobe.com/kr/security.html)를 참조하십시오.

## [!DNL Analytics] {#analytics}

* [Adobe Analytics의 새로운 기능 및 수정 내용](#aa-features)**(7월 15일에 업데이트됨)**
* [Analytics 관리자에 대한 중요 공지](#aa-notices)

### [!DNL Analytics] {#aa-features} 의 새로운 기능

제품 설명서는 [Analytics 도움말 홈](https://docs.adobe.com/content/help/en/analytics/landing/home.html)을 참조하십시오.

| 구성 요소 | 설명 |
| -----------| ---------- |   
| Analysis Workspace - Cohort Analysis 개선 사항 | 새로운 [집단 분석 설정](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/visualizations/cohort-table/t-cohort.html)이 추가되었습니다. <ul><li>백분율만 표시</li><li>백분율 반올림</li><li>평균 백분율 행 표시</li></ul> |
| Analysis Workspace | 왼쪽 레일에서 이제 사용자는 _지난 18개월 동안의 항목을 표시_&#x200B;할 수 있습니다. 이전에는 되돌아보기 기간이 최대 6개월이었습니다. 이를 통해 최대 18개월 전, 전년도의 페이지 또는 캠페인과 더욱 쉽게 비교할 수 있습니다. |
| 새 Analysis Workspace 템플릿 | Analysis Workspace에 ["Magento: 마케팅 및 상거래"](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/starter-projects.html)라는 새로운 템플릿을 추가했습니다. Magento 전자 상거래 고객을 위해 특별히 고안되었지만 모든 소매업체는 이를 통해 상거래 활동에 대한 고유한 통찰력을 얻을 수 있습니다. |

#### [!DNL Analysis Workspace] 수정 사항

* 차원을 분류할 때 멀티바이트 문자가 거꾸로 표시되는 문제가 수정되었습니다. (AN-180112)
* 시각화 오류 문제가 수정되었습니다. 시각화 오류가 발생하면 이제 빨간색 오류 막대가 표시됩니다.(AN-175542)
* 현지화된 환경에서 차원 이름이 영어로 표시되는 문제가 수정되었습니다.(AN-178695)

#### [!DNL Analytics] 수정 사항

* 실시간 드릴다운 보고서의 라인 그래프가 비어 있는 문제가 수정되었습니다. (AN-181690)
* 일부 상황에서 데이터 피드 내역의 일부가 관리 콘솔 UI에 표시되지 않는 문제가 수정되었습니다. (AN-176219)

### [!DNL Analytics] 관리자에 대한 중요 공지{#aa-notices}

| 알림 | 추가한 날짜 또는 업데이트한 날짜 | 설명 |
| -----------| ---------- | ---------- |
| 분류 규칙 빌더 제한 | 2019년 6월 5일에 추가됨 | 이 제한은 새롭지 않지만, [여기](https://marketing.adobe.com/resources/help/ko_KR/reference/classification_rule_builder.html) 문서에 추가되었습니다. |
| 새로운 세그먼트 연산자 제한 | 2019년 5월 31일에 추가됨 | 2019년 7월 18일부터 세그먼트 연산자 "임의 항목 포함", "임의 항목을 포함하지 않음", "모두 포함" 및 "모두 포함하지 않음"은 입력 필드당 100 단어로 제한됩니다. 이 날짜 이후로 모든 신규 세그먼트와 수정된 세그먼트에 제한이 적용됩니다. 제한을 초과하는 기존 세그먼트는 계속 지원되지만 입력 필드가 감소될 때까지 수정하거나 저장할 수 없습니다. 이 제한은 쿼리 성능을 향상시키기 위한 지속적인 노력의 일환으로 적용됩니다. |
| **[!UICONTROL 활성화된 날짜]** 및 **[!UICONTROL 숫자 2 분류]**&#x200B;에 대해 예정된 지원 변경 사항 | 업데이트 날짜: 2019년 5월 28일 | 숫자 2와 활성화된 날짜 분류를 가져오는 기능이 코드 베이스에서 제거되었습니다. 이 변경 사항은 2019년 7월 유지 관리 릴리스에 적용됩니다. 가져온 파일에 숫자 또는 활성화된 날짜 열이 있는 경우 해당 셀은 자동으로 무시되며, 해당 파일의 다른 모든 데이터는 정상적으로 가져와집니다. <br/>기존 분류는 여전히 표준 분류 워크플로우를 통해 내보낼 수 있으며, 보고에서 계속 사용할 수 있습니다. |
| _보고서 총계_ 계산과 관련한 변경 예정 | 업데이트 날짜: 2019년 7월 9일 | **2019년 6월 18일**&#x200B;에 Adobe Analytics는 모든 차원 및 지표에서 _보고서 총계_ 를 동일하게 변경할 예정입니다. 이를 통해 일부 보고서(예를 들어 Prop 또는 고객 특성 보고서)의 총계가 변경됩니다. 본 변경에 앞서 일부 보고서 총계는 보고서에서 _미지정_ 으로 표시되는지의 여부와 관계없이, 총계의 _미지정_ 라인 항목에 일관성 없이 포함되거나 제외됩니다. <br/>2019년 6월 18일부터, _미지정_ 항목은 보고서의 라인 항목으로 표시되지 않는 경우에도 보고서 총계에 항상 표시됩니다. 또한 _exists_ 또는 _does not exist_ 로직을 사용하는 세그먼트는 이 변경 후 일부 차원에 대해 다른 결과를 볼 수 있습니다. 특히 _Unspecified_&#x200B;에 레퍼러 유형 차원에 대한 "Typed/Bookmarked" 라인 항목 또는 장치 유형 차원에 대한 "Other" 라인 항목 등의 특수 이름이 있는 차원입니다. 본 변경은 Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder 및 Reporting API에 적용됩니다. |
| [!DNL Analysis Workspace] 에서 CSV 다운로드로 업데이트 | 2019년 4월 10일 | 2019년 4월 11일부터, [!DNL Analysis Workspace]의 **[!UICONTROL CSV 다운로드]** (및 **[!UICONTORL 클립보드로 복사]**)가 변경되어 내보낸 데이터의 형식을 제거할 수 있습니다.  <ul><li>천 단위 구분 기호가 더 이상 포함되지 않습니다. 소수점 구분 기호는 계속해서 포함되며, **[!UICONTROL 구성 요소 &gt; 보고서 설정 &gt; 천 단위 구분 기호]**&#x200B;에 정의된 형식을 따릅니다. 참고: 쉼표를 소수점 구분 기호로 사용하는 숫자 값은 내보낸 CSV에서 계속 따옴표로 표시됩니다.</li><li>통화 기호가 표시되지 않습니다.</li><li>퍼센트 기호가 표시되지 않습니다. 백분율은 10진수 형식입니다. 예를 들어, 75%는 0.75로 표시됩니다.</li><li>시간은 초 단위로 표시됩니다.</li><li>집단 테이블은 원시값만 표시합니다. 백분율이 제거됩니다.</li><li>숫자가 올바르지 않으면 빈 셀이 표시됩니다.</li></ul> |
| [!DNL Analysis Workspace] 디버거 명령 변경 예정 | 2019년 4월 4일 | **2019년 6월 13일**&#x200B;에 [!DNL Analysis Workspace] 디버거를 켜는 콘솔 명령이 adobeTools.debug.includeOberonXml로 변경됩니다. adobe.tools.debug.includeOberonXml은 이 날짜 이후에 작동이 중지됩니다. |
| 모바일 브라우저 버전 번호 | 2019년 2월 7일 | 2019년 1월 8일부터 모바일 브라우저 버전 번호의 자르기 레벨이 2에서 1로 변경되었습니다. 1월 8일부터는 버전에 첫 두 개 레벨만 표시됩니다(예: _Firefox 64.0.2_&#x200B;가 이제 _Firefox 64.0_&#x200B;으로 보고됨). |
| [!DNL Ad Hoc Analysis] 판매 종료 | 2019년 1월 29일 | 2018년 8월 6일, Adobe는 [!DNL Ad Hoc Analysis] 판매 종료 의사를 발표했습니다. 수명 종료 날짜는 확정된 후 공유될 예정입니다.<br/>이 기간 동안의 Java 호환 버전 등 자세한 정보는 [Discover Workspace](https://adobe.ly/discoverworkspace)를 참조하십시오. |
| 짧은 [!DNL Analytics] 보고서 링크 | 2019년 1월 14일 | 1년 안에 방문하지 않은 짧은 [!DNL Analytics] 보고서 링크는 롤링 일정에서 2019년 1월 17일 목요일부터 정리되고 삭제됩니다. |
| TLS 1.0 지원 종료 | 업데이트 날짜: 2019년 1월 10일 | 2019년 2월 11일부터 Adobe Analytics 보고에서는 더 이상 TLS(Transport Layer Security) 1.0 암호화를 지원하지 않습니다. 이 변경은 가장 높은 보안 표준을 유지하고 고객 데이터의 안전을 홍보하기 위해 진행 중인 노력의 일환입니다. 2019년 2월 11일 이후에도 Adobe Analytics 보고에 연결할 수 없는 경우 브라우저를 [최신 버전](https://marketing.adobe.com/resources/help/ko_KR/sc/user/requirements.html)으로 업그레이드해야 합니다.<br/>[!DNL Analytics] 2019년 2월 20일부터 Adobe 데이터 수집에서는 더 이상 TLS 1.0을 지원하지 않습니다. 이 변경으로, Adobe에서는 더 이상 TLS 1.1 이상을 지원하지 않는 이전 장치 또는 웹 브라우저를 사용하는 최종 사용자의 Analytics 데이터를 수집하지 않습니다. 이렇게 해도 고객 데이터 또는 보고에 큰 영향을 주지는 않습니다. (웹 사이트에서 TLS 1.0을 지원하지 않는 경우는 영향을 받지 않습니다.) <br/>2019년 4월 11일부터 Adobe Analytics Reporting API는 더 이상 TLS 1.0 암호화를 지원하지 않습니다. API에 액세스하는 고객은 자신들에게 영향이 없는지 확인해야 합니다. <ul><li>[Java 7을 기본 설정으로 사용하는 API 클라이언트는 TLS 1.2](https://www.java.com/en/configure_crypto.html)를 지원하도록 수정해야 합니다. (_클라이언트 종단점에 대한 기본 TLS 프로토콜 버전을 TLS 1.0에서 TLS 1.2로 변경_ 을 참조하십시오.) </li><li>Java 8을 사용하는 API 클라이언트는 기본값 설정이 TLS 1.2이므로 영향을 받지 않습니다.</li><li> 다른 프레임워크를 사용하는 API 클라이언트의 경우 TLS 1.2 지원에 대한 자세한 내용을 알려면 해당 공급업체에 문의해야 합니다.</li></ul> |
| 데이터 피드: post_product_list 열 - 크기 변경 | 2019년 1월 9일 | Adobe는 2019년 2월 7일부터 post_product_list 열 크기를 64KB에서 16MB로 늘렸습니다. 이러한 변경으로 인해 처리 중에 post_product_list에 추가된 머천다이징 eVar 값이 제품 및 수익 값을 자르지 않아도 됩니다. post_product_list 값을 수집하는 프로세스가 있는 경우 해당 프로세스가 길이에서 최대 16MB의 값을 처리할 수 있는지 확인하거나 데이터 수집 실패를 방지하기 위해 16KB에서 값을 자릅니다. |
| 비활성 [!DNL Analytics Live Stream] 종단점에 영향을 주는 관리 변경 사항 | 2018년 12월 20일 | 2019년 2월 1일부터 90일 동안 활성 소비자 연결이 없는 [!DNL Live Stream] 종단점은 비활성화될 수 있습니다. 고객 지원 담당자에게 연락하여 [!DNL Live Stream] 종단점에 대해 문의하고, 필요한 경우 다시 활성화할 수 있습니다. 또한 소비자 프로세스가 서비스 설계에 의도한 대로 지속적 연결을 유지하도록 하고, 연결이 끊기거나 중단되는 경우 다시 연결하도록 구현되어 있는지 확인하십시오. |
| TLS 1.0에 대한 지원 종료로 인해 Adobe [!DNL Report Builder] 업데이트 | 2018년 9월 7일 | TLS 1.0에 대한 지원 종료로 인해 Adobe는 [!DNL Report Builder] 사용자가 2019년 2월 이전에 버전 v5.6.21을 다운로드하도록 권장했습니다. 이 날짜 이후, 이전 버전의 [!DNL Report Builder]는 더 이상 작동하지 않습니다. |

### AppMeasurement {#appm}

2019년 7월 15일 발표:

**JavaScript 2.15.0용 AppMeasurement**

* Activity Map 스크롤 도달 추적이 Activity Map 확장(AN -172949)에 추가됨
* Appmeasurement에 DIL 9.2를 추가했습니다. (AN-182472)

다음 플랫폼에서 Appmeasurement의 릴리스 내역을 확인하려면 [AppMeasurement 릴리스 내역](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)을 참조하십시오.

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

* [log (X, B)](https://marketing.adobe.com/resources/help/en_US/insight/client/c_syntx_mtrc_exp.html) 지표 구문 설명서에 대한 도움말 정의를 업데이트했습니다. (AN-180527)

최신 정보는 [Data Workbench 릴리스 노트](https://marketing.adobe.com/resources/help/en_US/insight/whatsnew/)를 참조하십시오.

## Audience Manager {#aam}

**수정 사항 및 개선 사항**

* [!UICONTROL 세그먼트 개요] 페이지에서 세그먼트 저장소 폴더의 너비가 이제 유연합니다. 이렇게 하면 이름이 긴 세그먼트를 구별할 수 있습니다. (AAM-48400)
* [!UICONTROL 알고리즘 모델]에서 **도달 및 정확도 조정** 슬라이더를 이동하는 것이 모델의 도달 또는 정확도에 영향을 주지 않는 문제가 수정되었습니다. (AAM-47996)
* Analytics 대상에서 데이터 내보내기 제어 및/또는 타사 데이터 공유 정책과 충돌하는 세그먼트의 .csv 파일을 다운로드하는 버튼 문제가 수정되었습니다. (AAM-48100)
* 고객이 Audience Manager 사용자 인터페이스에 로그인할 때 임의의 "액세스 거부" 오류가 발생하는 문제가 수정되었습니다. (AAM-47632)

## Experience Manager {#aem}

Adobe Experience Manager(AEM)의 새로운 기능, 수정 내용 및 업데이트. 안정성, 보안 및 성능 향상을 위해 최신 패치를 배포하려는 경우 온-프레미스 배포를 사용하는 것이 좋습니다.

### 제품 릴리스

다음 제품에 대한 새로운 기능 정보:

#### Cloud Manager 2019.6.0

최신 Cloud Manager 릴리스(2019.6.0)에는 고객이 AEM 업데이트를 성공적으로 실행할 수 있도록 지원하기 위한 새로운 [제품 업데이트 마법사](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/product-update-wizard/overview-productupdate-wizard.html)가 포함되어 있습니다.

* [Cloud Manager 2019.6.0의 릴리스 노트](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

#### XML Documentation 3.4

이제 XML Documentation 3.4 솔루션을 사용할 수 있습니다.

***릴리스 노트***

* AEM 6.5에 대한 지원이 추가되었습니다.
* 편집자 변경 사항:
   * 맵 수준 미리 보기.
   * 표 - 복사 및 붙여넣기를 사용하여 표 내에서 `entry` 또는 `complete` 행을 복사하는 옵션을 제공했습니다.
   * 표 - 열에서 여러 셀을 선택하고 묶거나 병합하는 옵션을 제공했습니다.
   * 표 - 웹 편집기의 작성자 모드에서 표 열 속성을 설정하는 방법을 제공했습니다.
   * 표 - 표준 표에서 열 속성 및 크기를 조정하는 방법을 제공했습니다.
   * 표 - 작성자 보기에서 행과 열을 선택합니다.
   * 표 - 표 셀 정렬을 위해 웹 편집기에서 스타일과 속성(정렬, 경사)을 활성화했습니다.
   * 콘텐츠 복사 및 붙여넣기, 콘텐츠 드래그 앤 드롭 등 전체 태그 보기에 대한 버그 수정.
   * 편집기 탭에서 주제 제목을 표시합니다.
   * 웹 편집기에서 성능 문제가 해결되었습니다.
* 번역하는 동안 번역된 콘텐츠로 기준선을 전송합니다.
* 번역 워크플로우에서 조건 사전 설정을 전송합니다.
* 기준선에서 맵의 모든 종속 항목에 레이블을 적용하는 기능이 추가되었습니다.
* 모든 종속 항목이 있는 맵을 zip로 다운로드하는 버튼을 제공했습니다.
* 다음으로 향상된 XHTML-DITA 변환 기능:
   * 생성된 DITAMAP의 이름이 이제 업로드된 zip 파일의 이름과 동일합니다.
   * 추가 HTML 요소 및 특성에 대한 지원을 추가했습니다.
   * 동시 html-zip 파일 통합에 대해 지원합니다.
   * zip이 업로드되는 하위 폴더 계층 구조(*h2d_io.xml에 구성된 대로 입력 경로 아래*)는 생성된 출력(*구성된 출력 경로*)에 대해 유지됩니다.
* 복귀한 사람과 버전 및 이유를 확인하도록 감사 로그를 제공했습니다.
* AEM Site 재생성:
   * 하위 맵에 대한 재생성을 비활성화합니다.
   * 재생성 사용 사례에 대해 활성화된 생성 워크플로우를 게시합니다.
   * 청크 항목에 대한 재생성 옵션을 비활성화하고, 청크 특성이 적용되는 상위 항목에 대한 옵션을 사용할 수 있도록 합니다.
* 이제 DITA 검색이 AEM Asset 검색에서 작동합니다.
* 결과: 번역 출력 폴더에 저장된 임시 파일을 가져오지 않습니다.
* 기준선 탭:
   * 기준선을 열 때의 성능이 개선되었습니다.
   * 날짜별로 항목을 선택하여 클라이언트 타임스탬프를 작업합니다.
* 레이블 삭제를 위한 API.

#### 제품 유지 관리

**AEM 6.2 SP1-CFP20**

2019년 6월 6일에 릴리스된 AEM 6.2 서비스 팩 1–Cumulative Fix Pack 20(6.2.1.20)는 2016년 12월 AEM 6.2 SP1의 공식 출시 이후 릴리스된 주요 고객 수정 사항이 포함된 중요한 업데이트입니다.

* [릴리스 노트](https://helpx.adobe.com/kr/experience-manager/release-notes--aem-6-2-cumulative-fix-pack.html)
* [AEM Forms CFP 릴리스](https://helpx.adobe.com/kr/aem-forms/kb/aem-forms-releases.html)

**AEM 6.3.3.5**

2019년 7월 3일에 릴리스된 AEM 6.3.3.5는 2017년 4월에 AEM 6.3의 공식 출시 이후 릴리스된 주요 고객 수정 사항을 포함하는 중요한 업데이트입니다.

* [릴리스 노트](https://helpx.adobe.com/kr/experience-manager/6-3/release-notes/sp3-release-notes.html)
* [AEM Forms CFP 릴리스](https://helpx.adobe.com/kr/aem-forms/kb/aem-forms-releases.html)

**AEM 6.4.5.0**

2019년 7월 3일 릴리스된 AEM 6.4.5.0은 2018년 4월 AEM 6.4의 공식 출시 이후 릴리스된 주요 고객 수정 사항이 포함된 중요한 업데이트입니다.

* [릴리스 노트](https://helpx.adobe.com/kr/experience-manager/6-4/release-notes/sp-release-notes.html)
* [AEM Forms CFP 릴리스](https://helpx.adobe.com/kr/aem-forms/kb/aem-forms-releases.html)

**AEM 6.5.1.0**

2019년 7월 3일 릴리스된 AEM 6.5.1.0은 2019년 4월 AEM 6.5의 공식 출시 이후 릴리스된 주요 고객 수정 사항이 포함된 중요한 업데이트입니다.

* [릴리스 노트](https://helpx.adobe.com/kr/experience-manager/6-5/release-notes/sp-release-notes.html)
* [AEM Forms CFP 릴리스](https://helpx.adobe.com/kr/aem-forms/kb/aem-forms-releases.html)

### 사용자 도움말

**AEM 캐시 무효화 업데이트**

AEM 6.5 clientlibs 캐시 무효화에 대한 중요한 AEM 패치 기능은 [AEM 6.5.1.0 업데이트](https://helpx.adobe.com/kr/experience-manager/6-5/release-notes/sp-release-notes.html) 또는 이 [KB 문서](https://helpx.adobe.com/kr/experience-manager/kb/avoid-crx-quickstart-deletion-in-aem-6-5.html)를 통해 사용할 수 있습니다.

### 추가 리소스

* [AEM 6.5 학습 및 지원 홈](https://helpx.adobe.com/kr/support/experience-manager/6-5.html)
* [AEM 6.4 학습 및 지원 홈](https://helpx.adobe.com/kr/support/experience-manager/6-4.html)
* [AEM 6.3 학습 및 지원 홈](https://helpx.adobe.com/kr/support/experience-manager/6-3.html)
* [AEM 6.2 학습 및 지원 홈](https://helpx.adobe.com/kr/support/experience-manager/6-2.html)
* [Cloud Manager 사용 안내서](https://helpx.adobe.com/kr/experience-manager/cloud-manager/user-guide.html)
* [이전 버전의 AEM 설명서](https://helpx.adobe.com/kr/experience-manager/aem-previous-versions.html)
* [Scene7 Publishing System 릴리스 노트](https://marketing.adobe.com/resources/help/ko_KR/s/release_notes/index.html)
* [Livefyre 릴리스 노트](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign은 온라인 및 오프라인 마케팅 채널 간에 직관적이고, 자동화된 방식으로 일대일 메시지를 제공합니다. 이제 고객이 습관 및 선호도에 따라 결정된 작업 환경을 통해 원하는 사항을 예측할 수 있습니다.

릴리스 노트에 대해서는:

* Adobe Campaign Classic [19.1.2](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – 빌드 9029
* Adobe Campaign Standard [19.2.3](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-3---june-2019)
* Adobe Campaign Standard [19.2.4](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-4---june-2019)
* Adobe Campaign Standard [19.2.7](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-7---july-2019)

제품 설명서의 경우 다음을 참조하십시오.

* Adobe Campaign Standard: [설명서](https://helpx.adobe.com/kr/support/campaign/standard.html) - [릴리스 노트](https://helpx.adobe.com/kr/campaign/standard/rn/using/release-notes.html) - [기능 비디오](https://helpx.adobe.com/kr/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/kr/support/campaign/classic.html) - [릴리스 노트](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [기능 비디오](https://helpx.adobe.com/kr/campaign/kt/acc/index/acc-videos.html)

## [!DNL Target] {#target}

Target에 대한 최신 릴리스 정보는 [Target 릴리스 노트(시험판)](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)를 참조하십시오.

## Magento {#magento}

Magento Commerce 및 AuMagento 오픈 소스 릴리스 노트에 대한 자세한 내용은 다음을 참조하십시오.

* [Magento Open Source 2.3.2 릴리스 노트](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2OpenSource.html)
* [Magento Commerce 2.3.2 릴리스 노트](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2Commerce.html)
