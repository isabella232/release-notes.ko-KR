---
title: Adobe Experience Cloud 릴리스 노트
description: Experience Cloud 릴리스 노트 템플릿
doc-type: 릴리스 노트
last-update: 2019년 10월 일
author: mfrei
translation-type: tm+mt
source-git-commit: 59bbe7ddd5cbbcb653d6c44223b644257dd94cb4

---


# 조기 이용 - Experience Cloud 릴리스 노트 - 2019년 10월

Adobe Experience Cloud의 새로운 기능 및 수정 사항.

>[!IMPORTANT]
>
>이 페이지에는 출시 전 컨텐츠가 포함되어 있으며 계획된 출시 전에 변경될 수 있습니다.

>[!NOTE]
>
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. 릴리스 후 게시된 새 정보는 발행 날짜로 표시됩니다.

## 릴리스 날짜: 2019년 10월 10일

<!-- * [Experience Cloud interface](#ecloud) -->
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (솔루션 도움말 링크)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (솔루션 도움말 링크)

<!-- ## Experience Cloud interface {#ecloud}

Release notes for Experience Cloud interface and product administration.

* Fixed a security vulnerability to include recommended HTTP headers. (MCUI-9942)
* Fixed an issue in switching between Analytics login companies. (MCUI-10049)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html). -->

## Experience Platform {#platform}

Experience Platform, Experience Platform Launch, Idendity Service 및 보안 게시판의 릴리스 정보입니다.

* [Experience Platform Launch](#launch)
* [보안 게시판 및 권고 조치](https://helpx.adobe.com/security.html) (모든 Adobe 제품)

### Experience Platform Launch {#launch}

릴리스 [노트 및 제품](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) 설명서는 Experience Platform Launch를 참조하십시오.

## [!DNL Analytics] {#analytics}

Adobe Analytics의 새로운 기능 및 수정 내용:

* [Adobe Analytics의 새로운 기능, 향상된 기능 및 수정 내용](#aa-features)
* [Analytics 관리자에 대한 중요 공지](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Adobe Analytics의 새로운 기능, 향상된 기능 및 수정 내용 {#aa-features}

| 기능 | 설명 |
| -----------| ---------- |  
| 개인 정보 서비스 API:CCPA | CCPA(California Consumer Privacy Act)는 미국 캘리포니아 거주자에 대한 개인정보 보호 권한과 소비자 보호를 강화합니다. 이 법은 2020년 1월 1일부터 시행한다.<br><br/>CPA는 캘리포니아 거주자에게 개인 데이터에 액세스하고 삭제할 수 있는 권리, 개인 데이터가 판매되거나 공개(및 개인)되었는지 여부, 그리고 개인 데이터의 판매를 거부할 수 있는 권리 등 새로운 데이터 개인정보 보호 권한을 제공합니다.<br><br/>In anticipation of the CCPA, the Privacy Service will support requests to opt out of the selling of personal data.<br><br/>The Privacy Service was formerly called the GDPR Service and retains all the previous functionality, now extended to support CCPA.<br/>CCPA in Analytics: (content forthcoming) <br><br/>[Privacy Service Overview](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| Privacy Reporting: Analytics Admin Console | Enabling Privacy Reporting for Analytics adds a set of reserved variables to a report suite.  The variables are designed to assist in the collection of consumer consent data at a hit level.<br/>New Dimensions:<br/><ul><li>동의 관리 옵트아웃</li><li>Consent Management Opt-In</li><li>Consent Management Variables: <!-- `[Link to new Consent Variables page in Analytics]()` --></li></ul> |
| Audio and Video Analytics: Privacy Support | Media Collection API에는 두 개의 새 변수가 추가되었습니다.<br/><ul><li>analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul>These are optional variables that can be used to capture the status of a consumer’s consent at the time of the hit. [Media Collection API DocumentationThe new Analytics Consent Management context data variables have been added to the Federated Analytics form. ](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/> 이제 이러한 변수를 페더레이션에 대한 옵트아웃 또는 판매 히트에 플래그를 지정하는 데 사용할 수 있습니다. [Download Federated Form](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |
| 분석 작업 공간:자유 형식 테이블 합계 업데이트 | Freeform tables now include two totals, a Table total and a Grand total. ******** 적용된 [보고서 필터에](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) 대한 테이블 합계 행 계정. 이전에는 세그먼테이션에 영향을 받은 총계만 있었습니다. [자세한](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/workspace-totals.html)<br/>내용 **[!UICONTROL 또한]** 합계 표시 **[!UICONTROL 및 총계]** 표시 **[!UICONTROL 옵션이 열 설정에]**&#x200B;추가되었습니다.<br/>자유 형식 합계에 대한 이 변경 사항이 적용되면 종속 시각화(예: 연결된 요약 번호 **[!UICONTROL 시각화]** )와 내보낸 CSV 및 PDF 데이터가 업데이트됩니다. |
| 분석 작업 공간:지정되지 않음/없음 제거 옵션 | The ability to easily remove ‘Unspecified (None)’ has been added as an option to report filters. |
| 분석 작업 공간:자주색 세부기간 구성 요소의 사용 중단 | 자주색 세부기간 시간 구성 요소(분, 시간, 일, 주, 월, 분기, 연도)는 더 이상 사용되지 않습니다. 자주색 시간 구성 요소는 항상 주황색 크기와 정확히 동일하게 작동했으므로 이 변경 사항은 경험을 단순화합니다. **이전에 자주색 시간 구성 요소 중 하나를 사용한 경우에는 작업을** 수행할 필요가 없습니다.<br/>이 변경 사항으로 자주색 **[!UICONTROL 시간]** 섹션도 날짜 범위로 **[!UICONTROL 변경되었습니다]**. |

#### 수정 사항

* 분석 작업 공간:왼쪽 레일에서 차원 항목을 검색할 때 잘못된 검색 결과가 표시되는 문제를 해결했습니다. (AN-185065)
* AAM(Adobe Audience Manager)에서 공유 세그먼트를 삭제하거나 게시 취소할 수 없는 문제가 해결되었습니다. AAM이 응답하지 않으면 세그먼트를 삭제하지 않는 문제가 수정되었습니다. (AN-185882, AN-185883, AN-184607)
* 애드혹 분석에서 세그먼트를 로드할 수 없는 시간 초과 문제를 해결했습니다. (AN-184654)
* 마지막으로 사용한 보고서 세트가 나중에 숨겨지거나 더 이상 이 보고서 세트에 액세스할 권한이 없을 때 발생하는 문제를 수정했습니다. 이 경우 Experience Cloud를 통해 더 이상 로그인할 수 없습니다. (AN-181777)
* 세그먼트를 기반으로 VRS를 만들기 어렵게 했던 세그먼트의 시간 초과 문제를 수정했습니다. (AN-179684)

### [!DNL Analytics] 관리자에 대한 중요 공지 {#aa-notices}

| 알림 | 추가한 날짜 또는 업데이트한 날짜 | 설명 |
| -----------| ---------- | ---------- |
| TLS 1.1 지원 종료 | 2019년 10월 3일 | 2020년 3월 31일까지 Adobe Analytics는 TLS 1.1에 대한 지원을 제거합니다.이러한 변경은 최고 수준의 보안 표준을 유지하고 고객 데이터의 보안을 향상시키기 위한 지속적인 노력의 일환입니다. |
| San Jose FTP Broker - London and Singapore 종료 | 2020년 7월 | 런던과 싱가포르 고객의 경우 Adobe는 더 이상 런던 또는 싱가포르와 San Jose 데이터 센터 [ftp.omniture.com](ftp://ftp.omniture.com/)간의 데이터 중재를 지원하지 않습니다.<br/><ul><li>London의 경우 [ftp3.omniture.com 사용](ftp://ftp3.omniture.com/)</li><li>싱가폴의 경우 [ftp4.omniture.com 사용](ftp://ftp4.omniture.com/)</li> |
| Analysis Workspace 자유 형식 테이블 합계 업데이트 | 2019년 9월 12일 | 2019년 10월에는 자유 형식 테이블 합계 행이 적용된 [보고서 필터에](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) 대한 회계를 시작합니다. 현재까지 합계가 세분화에 대해서만 계산되었습니다. 이 변경 사항에 따라 종속 시각화는 내보내기한 CSV 및 PDF 데이터뿐만 아니라 업데이트(예: 연결된 [!UICONTROL 요약 번호] 시각화)됩니다. |
| Analytics 사용자의 `createDate` 필드 관련 향후 변경 사항 | 2019년 8월 30일 | 2019년 10월 또는 11월에는 Analytics 사용자의 `createDate` 필드가 미국 태평양 표준시에서 시간대 정보가 있는 올바른 형식의 날짜/시간 값으로 업데이트됩니다. (AN-183468) |
| 이전 시간대 오프셋 지원 | 2019년 8월 8일 | 이제 Analytics는 타임스탬프가 지정된 히트에 대해 시간대 오프셋을 자동으로 처리합니다. 8월 8일에 이 변경사항이 적용되면, 내역 처리를 위해 데이터에 로드되는 시스템은 데이터를 보내기 전에 더 이상 시간대 오프셋을 조정하지 않아도 됩니다. |
| 분류 규칙 빌더 제한 | 2019년 6월 5일에 추가됨 | 이러한 제한은 새로운 것은 아니지만 [여기에서](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html)문서에 추가되었습니다. |
| 새로운 세그먼트 연산자 제한 | 2019년 5월 31일에 추가됨 | 2019년 7월 18일부터 세그먼트 연산자 _임의 항목 포함_, _임의 항목 포함하지 않음_, _모두 포함_ 및 _모두 포함하지 않음_&#x200B;은 입력 필드당 100단어로 제한됩니다. 이 날짜 이후로 모든 신규 세그먼트와 수정된 세그먼트에 제한이 적용됩니다. 제한을 초과하는 기존 세그먼트는 계속 지원되지만 입력 필드가 감소될 때까지 수정하거나 저장할 수 없습니다. 이 제한은 쿼리 성능을 향상시키기 위한 지속적인 노력의 일환으로 적용됩니다. |
| **[!UICONTROL 활성화된 날짜]** 및 **[!UICONTROL 숫자 2 분류]**&#x200B;에 대한 지원 변경 사항 | 업데이트 날짜: 2019년 5월 28일 | 숫자 2와 활성화된 날짜 분류를 가져오는 기능이 코드 베이스에서 제거되었습니다. 이 변경 사항은 2019년 7월 유지 관리 릴리스에 적용되었습니다. 가져온 파일에 숫자 또는 활성화된 날짜 열이 있는 경우 해당 셀은 자동으로 무시되며, 해당 파일의 다른 모든 데이터는 정상적으로 가져와집니다. <br/>기존 분류는 여전히 표준 분류 워크플로우를 통해 내보낼 수 있으며, 보고에서 계속 사용할 수 있습니다. |
| _보고서 총계_ 계산과 관련한 변경 | 업데이트 날짜: 2019년 7월 9일 | **2019년 6월 18일**&#x200B;에 Adobe Analytics는 모든 차원 및 지표에서 _보고서 총계_&#x200B;를 동일하게 변경했습니다. 이를 통해 일부 보고서(예: Prop 또는 고객 특성 보고서)의 총계가 변경되었습니다. 본 변경에 앞서 일부 보고서 총계는 보고서에서 _미지정_ 으로 표시되는지의 여부와 관계없이, 총계의 _미지정_ 라인 항목에 일관성 없이 포함되거나 제외됩니다. <br/>2019년 6월 18일부터, _미지정_ 항목은 보고서의 라인 항목으로 표시되지 않는 경우에도 보고서 총계에 항상 표시됩니다. 또한 _exists_ 또는 _does not exist_ 로직을 사용하는 세그먼트는 이 변경 후 일부 차원에 대해 다른 결과를 볼 수 있습니다. 특히 _Unspecified_&#x200B;에 레퍼러 유형 차원에 대한 "Typed/Bookmarked" 라인 항목 또는 장치 유형 차원에 대한 "Other" 라인 항목 등의 특수 이름이 있는 차원입니다. 본 변경은 Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder 및 Reporting API에 적용됩니다. |
| Analysis Workspace에서 CSV 다운로드로 업데이트 | 2019년 4월 10일 | 2019년 4월 11일부터, Analysis Workspace의 **[!UICONTROL CSV 다운로드]**(및 **[!UICONTORL 클립보드로 복사]**)가 변경되어 내보낸 데이터의 형식을 제거할 수 있습니다.  <ul><li>천 단위 구분 기호가 더 이상 포함되지 않습니다. 소수점 구분 기호는 계속해서 포함되며, **[!UICONTROL 구성 요소 &gt; 보고서 설정 &gt; 천 단위 구분 기호]**&#x200B;에 정의된 형식을 따릅니다. 참고: 쉼표를 소수점 구분 기호로 사용하는 숫자 값은 내보낸 CSV에서 계속 따옴표로 표시됩니다.</li><li>통화 기호가 표시되지 않습니다.</li><li>퍼센트 기호가 표시되지 않습니다. 백분율은 10진수 형식입니다. 예를 들어, 75%는 0.75로 표시됩니다.</li><li>시간은 초 단위로 표시됩니다.</li><li>집단 테이블은 원시값만 표시합니다. 백분율이 제거됩니다.</li><li>숫자가 올바르지 않으면 빈 셀이 표시됩니다.</li></ul> |
| Analysis Workspace 디버거 명령 변경 예정 | 2019년 4월 4일 | **2019년 6월 13일**&#x200B;에 Analysis Workspace 디버거를 켜는 콘솔 명령이 adobeTools.debug.includeOberonXml로 변경됩니다. adobe.tools.debug.includeOberonXml은 이 날짜 이후에 작동이 중지됩니다. |
| 모바일 브라우저 버전 번호 | 2019년 2월 7일 | 2019년 1월 8일부터 모바일 브라우저 버전 번호의 자르기 레벨이 2에서 1로 변경되었습니다. 1월 8일부터는 버전에 첫 두 개 레벨만 표시됩니다(예: _Firefox 64.0.2_&#x200B;가 이제 _Firefox 64.0_&#x200B;으로 보고됨). |
| [!DNL Ad Hoc Analysis] 판매 종료 | 2019년 1월 29일 | 2018년 8월 6일, Adobe는 [!DNL Ad Hoc Analysis] 판매 종료 의사를 발표했습니다. 수명 종료 날짜는 확정된 후 공유될 예정입니다.<br/>이 기간 동안의 Java 호환 버전 등 자세한 정보는 [[!DNL Discover Workspace]](https://adobe.ly/discoverworkspace)를 참조하십시오. |
| 짧은 [!DNL Analytics] 보고서 링크 | 2019년 1월 14일 | 1년 안에 방문하지 않은 짧은 [!DNL Analytics] 보고서 링크는 롤링 일정에서 2019년 1월 17일 목요일부터 정리되고 삭제됩니다. |
| 데이터 피드: post_product_list 열 - 크기 변경 | 2019년 1월 9일 | Adobe는 2019년 2월 7일부터 post_product_list 열 크기를 64KB에서 16MB로 늘렸습니다. 이러한 변경으로 인해 처리 중에 post_product_list에 추가된 머천다이징 eVar 값이 제품 및 수익 값을 자르지 않아도 됩니다. post_product_list 값을 수집하는 프로세스가 있는 경우 해당 프로세스가 길이에서 최대 16MB의 값을 처리할 수 있는지 확인하거나 데이터 수집 실패를 방지하기 위해 16KB에서 값을 자릅니다. |
| 비활성 [!DNL Analytics Live Stream] 종단점에 영향을 주는 관리 변경 사항 | 2018년 12월 20일 | 2019년 2월 1일부터 90일 동안 활성 소비자 연결이 없는 [!DNL Live Stream] 종단점은 비활성화될 수 있습니다. 고객 지원 담당자에게 연락하여 [!DNL Live Stream] 종단점에 대해 문의하고, 필요한 경우 다시 활성화할 수 있습니다. 또한 소비자 프로세스가 서비스 설계에 의도한 대로 지속적 연결을 유지하도록 하고, 연결이 끊기거나 중단되는 경우 다시 연결하도록 구현되어 있는지 확인하십시오. |
| TLS 1.0에 대한 지원 종료로 인해 Adobe [!DNL Report Builder] 업데이트 | 2018년 9월 7일 | TLS 1.0에 대한 지원 종료로 인해 Adobe는 [!DNL Report Builder] 사용자가 2019년 2월 이전에 버전 v5.6.21을 다운로드하도록 권장했습니다. 이 날짜 이후, 이전 버전의 [!DNL Report Builder]는 더 이상 작동하지 않습니다. |

### [!DNL AppMeasurement] {#appm}

JavaScript [용 AppMeasurement 릴리스 노트를](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)참조하십시오.

## Audience Manager {#aam}

Audience Manager의 새로운 기능, 개선 사항 및 수정 사항.

**수정 사항 및 향상된 기능**

* All customer accounts created after July 1st, 2019, will automatically be assigned a  license, providing them access to their reports. [!DNL Tableau] If your account was created before July 1st, 2019, and you still do not have access to your  reports, please contact Customer Care.[!DNL Tableau]
* We've removed incorrectly generated activity trait memberships for visitor profiles that did not have an ID synchronization with the trait data source (AAM-45371).
* We've removed invalid global device IDs from global data sources. See Global Data Sources to learn what valid device IDs should look like to be accepted by Audience Manager (AAM-41259).[](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/data-sources/global-data-sources.html)
* Fixed a bug causing the Segments page to stop responding when you attempt to delete a protected segment (AAM-49881).
* When editing destinations for Twitter Tailored Audiences, the Account selector is now active only if the destination does not have a  account assigned (AAM-49975).[!DNL Twitter Ads]
* Fixed a bug preventing users from disabling Audience Marketplace data feeds when subscriptions are disabled (AAM-49640).
* Audience Manager 사용자 인터페이스의 접근성과 관련하여 몇 가지 개선 사항이 있었습니다.

## Experience Manager {#aem}

Adobe Experience Manager(AEM)의 새로운 기능, 수정 내용 및 업데이트. 안정성, 보안 및 성능 향상을 위해 최신 패치를 배포하려는 경우 온-프레미스 배포를 사용하는 것이 좋습니다.

### 제품 유지 관리

* **AEM 6.3.3.6**

   AEM 6.3, 서비스 팩 3, 누적 수정 팩 6(2019년 9월 25일 릴리스된 6.3.6)는 2017년 4월 AEM 6.3의 일반 가용성 이후 릴리스된 주요 고객 픽스를 포함하는 중요한 업데이트입니다.
   * [릴리스 노트](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [AEM Forms CFP 릴리스](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.6.0**

   AEM 6.4, 서비스 팩 6.0(2019년 9월 19일에 릴리스된 6.4.6.0)은 2018년 4월 AEM 6.4의 일반 가용성 이후 릴리스된 주요 고객 픽스를 포함하는 중요한 업데이트입니다.
   * [릴리스 노트](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [AEM Forms CFP 릴리스](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.5.2.0** AEM 6.5, 서비스 팩 2.0(2019년 9월 19일 릴리스된 6.5.2.0)은 2019년 4월 AEM 6.5의 일반 가용성 이후 릴리스된 주요 고객 픽스를 포함하는 중요한 업데이트입니다.
   * [릴리스 노트](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [AEM Forms CFP 릴리스](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### 사용자 도움말

* **Scene7: Reprocess Assets workflow**

   You can now reprocess assets in a folder that already has an existing processing profile that you later changed.
See Reprocessing assets in a folder after you have edited its processing profile.[](https://helpx.adobe.com/experience-manager/6-5/assets/using/processing-profiles.html#Reprocessingassetsinafolderafteryouhaveediteditsprocessingprofile)

* **Integration of Dynamic Media Viewers with Adobe Analytics and Adobe Launch**

   The Dynamic Media Viewers extension for Adobe Launch, along with the release of Dynamic Media Viewers 5.13, lets customers of Dynamic Media, Adobe Analytics, and Adobe Launch use events and data specific for the Dynamic Media Viewers in their Adobe Launch configuration.
Adobe [Analytics 및 Adobe Launch와 Dynamic Media 뷰어 통합을 참조하십시오](https://helpx.adobe.com/experience-manager/6-5/assets/using/launch.html).

* **AEM desktop app**

   AEM desktop app 2.0 is now available for creatives, marketers, and line-of-business users, to work with AEM Assets.
AEM [데스크탑 앱 릴리스 정보를 참조하십시오.](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **핵심 구성 요소**
   * 핵심 구성 요소의 현지화 기능과 AEM 템플릿으로 작업하는 방법에 대해 알아봅니다.
      [예제를](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/get-started/localization.html)참조하십시오.
   * 코어 구성 요소 2.6.0은 경험 조각 구성 요소를 도입합니다. 이제 구성 요소를 [제작 설명서](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) 및 [개발자 세부 사항 및 GitHub에서 프로젝트 다운로드와 함께 사용할 수 있습니다](https://github.com/adobe/aem-core-wcm-components).

* **AEM Assets**
   * 시각적/유사성 검색 기능에 대한 새로운 설명서입니다.
유사한 [이미지](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html#visualsearch)찾기를 참조하십시오.
   * 연결된 자산 기능은 이제 이미지 파일 포맷 외에도 원격 DAM 배포에 사용할 수 있는 문서를 사용합니다.
AEM [Sites에서 연결된 자산을 사용하여 DAM 자산을 공유하십시오](https://helpx.adobe.com/experience-manager/6-5/assets/using/use-assets-across-connected-assets-instances.html).
   * 자산 검색 및 검색에 대한 새로운 컨텐츠 The Search assets in AEM topic is your one-stop-shop for information on using, configuring, troubleshooting, limitations, and tips.
__
AEM [에서 자산 검색을 참조하십시오](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html).

### 추가 리소스

* [AEM 6.5 학습 및 지원 홈](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 학습 및 지원 홈](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 학습 및 지원 홈](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 학습 및 지원 홈](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager 사용 안내서](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Older Versions of AEM Documentation](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic 도움말 홈](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Dynamic Media 릴리스 노트](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre 릴리스 노트](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign은 온라인 및 오프라인 마케팅 채널 간에 직관적이고, 자동화된 방식으로 일대일 메시지를 제공합니다. 이제 고객이 습관 및 선호도에 따라 결정된 작업 환경을 통해 원하는 사항을 예측할 수 있습니다.

### Adobe Campaign Classic

* [Campaign Classic 19.1.4 업데이트](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9032) - 빌드 9032
* [Campaign Classic 19.1.6 업데이트](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html#release-19-1-6-build-9035) - 빌드 9035

### 추가 리소스

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
