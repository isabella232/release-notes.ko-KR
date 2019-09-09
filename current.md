---
title: Adobe Experience Cloud 릴리스 노트
description: Experience Cloud 릴리스 노트 템플릿
doc-type: 릴리스 노트
last-update: 2019 년 9 월
author: mfrei
translation-type: tm+mt
source-git-commit: 3b26af48364509946706cd183c1261ea8c15eab2

---


# 조기 액세스 - 2019 년 9 월 - Experience Cloud 릴리스 노트

Adobe Experience Cloud의 새로운 기능 및 수정 사항.

>[!IMPORTANT]
>
>이 페이지에는 시험판 컨텐츠가 포함되어 있으며 2019 년 9 월 12 일 릴리스 이전에 변경될 수 있습니다.

>[!NOTE]
>
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. 업무일 기준으로 릴리스 3-5일 전에 공지를 받게 됩니다. 릴리스 후 게시된 새 정보는 발행 날짜로 표시됩니다.

## 릴리스 날짜: 2019년 9월 12일

* [Experience Cloud 인터페이스](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (솔루션 도움말에 링크)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (솔루션 도움말에 링크)

## Experience Cloud 인터페이스 {#ecloud}

Experience Cloud 인터페이스 및 제품 관리에 대한 릴리스 노트입니다.

* 권장 HTTP 헤더를 포함하도록 보안 취약성 문제가 해결되었습니다. (MCUI-9942)
* Analytics 로그인 회사 간 전환 문제를 해결했습니다. (MCUI-10049)

제품 설명서의 [경우 Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html)를 참조하십시오.

## Experience Platform {#platform}

경험 플랫폼, 경험 플랫폼 시작, ID 서비스 및 보안 게시판의 릴리스 노트

* [Experience Platform Launch](#launch)
* [Mobile Services 및 Mobile SDK](#mobile)
* [보안 게시판 및 권고 조치](https://helpx.adobe.com/security.html) (모든 Adobe 제품)

### Experience Platform Launch {#launch}

릴리스 노트 및 제품 설명서는 [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) 를 참조하십시오.

### Mobile Services 및 Mobile SDK {#mobile}

Release Date: **September 26th**

**iOS (4.18.8)**

* SDK 데이터가 모든 Analytics 호출에서 쌍을 이루는 watchos 앱과 동기화되는 버그를 수정했습니다.
* 푸시 클릭스루 페이로드가 인앱 메시지의 특성으로 사용될 수 없던 버그를 수정했습니다.
* iOS 10 이상에서 더 이상 사용되지 않는 uilocalnotification API 대신 사용자 알림 프레임워크 API로 업데이트되었습니다.
* iOS 12 이상에서 더 이상 사용되지 않는 uiwebview가 아닌 wkwebview로 업데이트되었습니다.

**Android 4.17.10**

* BCP 47 언어 태그에 대한 지원을 추가했습니다.

**Unity**

* Ios 용 4.18.7 및 Android 용 4.17.9로 업데이트된 플러그인

## [!DNL Analytics] {#analytics}

Adobe Analytics의 새로운 기능 및 수정 내용:

* [Adobe Analytics의 새로운 기능, 향상된 기능 및 수정 내용](#aa-features)
* [Analytics 관리자에 대한 중요 공지](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Adobe Analytics의 새로운 기능, 향상된 기능 및 수정 내용 {#aa-features}

| 기능 | 설명 |
| -----------| ---------- |  
| **경로 IQ: 크로스 디바이스 분석** | 2019 년 9 월 Adobe Analytics는 Analytics Ultimate 고객이 Journey IQ 라는 강력한 새로운 기능을 이용할 수 있도록 지원합니다. 크로스 디바이스 분석 CDA (Cross-Device Analytics) 는 Adobe Analytics를 장치 중심에서 인간 중심 분석 도구로 혁신합니다. CDA를 사용하여 다음과 같은 질문에 답변할 수 있습니다. <ul><li>얼마나 많은 사람들이 내 브랜드와 상호 작용하고 있습니까? 어떤 유형의 디바이스를 사용하고 있습니까? 어떻게 오버랩됩니까?</li><li>사람들이 모바일 장치에서 작업을 시작한 다음 나중에 데스크탑 PC로 이동하여 작업을 완료하는 빈도 한 장치에 랜딩되는 캠페인 클릭스루가 다른 곳에서 전환을 가져오는가?</li><li>크로스 디바이스 여정을 고려하면 캠페인 효과에 대한 이해가 어떻게 달라집니까? 단계 분석은 어떻게 변경됩니까?</li><li>사용자가 한 장치에서 다른 장치로 이동하는 가장 일반적인 경로는 무엇입니까? 어디에서 중단됩니까? 고객의 성공적인 참여</li><li>여러 디바이스를 가진 사용자의 행동은 단일 장치를 사용하는 사용자와 어떻게 다릅니까?</li></ul><br/>자세한 내용은 [adobe.ly/aacda](https://spark.adobe.com/page/8ZpjsX6Lp5XTM/)를 참조하십시오. |
| **업데이트된 분류 아키텍처** | 9 월부터 분류 아키텍처에 대한 업데이트는 몇 개월 동안 고객으로 마이그레이션됩니다. 9 월 릴리스에는 적은 수의 조기 채택자에 대한 마이그레이션이 포함됩니다.<br/>업데이트는 업로드하는 데 걸리는 시간 (규칙 로직 포함) 를 가져오기/인제스트하여 보고하는 데 걸리는 시간을 크게 줄입니다. |

#### 수정 사항

* 기본 Experience Cloud 메뉴에서 [!UICONTROL 액세스할] [!UICONTROL 수 없는] 핵심 서비스에 대한 문제를 수정했습니다. (AN-184294)
* 스크롤 막대가 없고 스크롤 바가 없는 [!UICONTROL 분석 작업 공간에서] 왼쪽 레일의 왼쪽 레일이 흔들리는 문제가 수정되었습니다. (AN-183904)
* 오류 보고와 관련된 문제가 해결되었습니다. 빨간색 오류 표시기보다 더 구체적인 오류 메시지가 표시됩니다. 특히, 부담이 많거나, 오류가 많거나, 너무 복잡한 보고서 요청을 작성하여 문제가 발생하는 경우를 이해하는 데 도움이 됩니다. (AN -184135) [자세히...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/optimizing-performance.html)
* 형식으로 폴아웃 보고서를 성공적으로 다운로드할 `.pdf/.xls/.rtf` 수 없는 문제를 해결했습니다. (AN-183165)
* Experience Cloud를 통해 로그인하고 다른 Experience Cloud 솔루션으로 전환하거나 다른 로그인 회사로 전환하는 문제가 해결되었습니다. (AN-183376)
* 예약된 프로젝트의 자산 전송이 제대로 작동하지 않는 문제를 해결했습니다. 그룹은 이제 [!UICONTROL 관리 콘솔에서] 관리되므로, 자산을 더 이상 전송할 때 사용자 간에 복사하지 않습니다. (AN-183751)
* 소유자가 삭제된 예약된 보고서를 삭제하는 문제를 해결했습니다. 이제 예약 소유자가 더 이상 존재하지 않는 경우 알림이 관리자 (삭제 작업을 수행한 경우) 에게 전달됩니다. (AN-181000)

### [!DNL Analytics] 관리자에 대한 중요 공지 {#aa-notices}

| 알림 | 추가한 날짜 또는 업데이트한 날짜 | 설명 |
| -----------| ---------- | ---------- |
| 분석 작업 공간 자유 형식 테이블 합계 업데이트 | 2019 년 9 월 12 일 | 2019 년 10 월에 자유 형식 테이블 합계 행이 적용된 [보고서 필터](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) 회계를 시작합니다. 현재까지 합계가 세그멘테이션에 대해서만 계산되었습니다. 이 변경 사항에 따라 종속 시각화는 내보낸 CSV 및 PDF 데이터뿐만 아니라 업데이트 (예: 연결된 [!UICONTROL 요약 번호] 시각화) 를 업데이트합니다. |
| Analytics 사용자의 `createDate` 향후 필드 변경 사항 | 2019년 30월 8일 | 2019 년 10 월 또는 11 월에 Analytics 사용자의 `createDate` 필드는 미국 태평양 표준시에서 올바른 형식의 날짜/시간 값으로 시간대 정보가 표시됩니다. (AN-183468) |
| 이전 시간대 오프셋 지원 | 2019년 8월 8일 | 이제 Analytics는 타임스탬프가 지정된 히트에 대해 시간대 오프셋을 자동으로 처리합니다. 8월 8일에 이 변경사항이 적용되면, 내역 처리를 위해 데이터에 로드되는 시스템은 데이터를 보내기 전에 더 이상 시간대 오프셋을 조정하지 않아도 됩니다. |
| 분류 규칙 빌더 제한 | 2019년 6월 5일에 추가됨 | 이러한 제한 사항은 새로운 것이 아니지만 여기에 설명서가 [추가되었습니다](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| 새로운 세그먼트 연산자 제한 | 2019년 5월 31일에 추가됨 | 2019년 7월 18일부터 세그먼트 연산자 _임의 항목 포함_, _임의 항목 포함하지 않음_, _모두 포함_ 및 _모두 포함하지 않음_&#x200B;은 입력 필드당 100단어로 제한됩니다. 이 날짜 이후로 모든 신규 세그먼트와 수정된 세그먼트에 제한이 적용됩니다. 제한을 초과하는 기존 세그먼트는 계속 지원되지만 입력 필드가 감소될 때까지 수정하거나 저장할 수 없습니다. 이 제한은 쿼리 성능을 향상시키기 위한 지속적인 노력의 일환으로 적용됩니다. |
| **[!UICONTROL 날짜 활성화]** 및 **[!UICONTROL 숫자 2 분류에 대한 변경 사항 지원]** | 업데이트 날짜: 2019년 5월 28일 | 숫자 2와 활성화된 날짜 분류를 가져오는 기능이 코드 베이스에서 제거되었습니다. 이 변경 사항은 2019 년 7 월 유지관리 릴리스에서 적용되었습니다. 가져온 파일에 숫자 또는 활성화된 날짜 열이 있는 경우 해당 셀은 자동으로 무시되며, 해당 파일의 다른 모든 데이터는 정상적으로 가져와집니다. <br/>기존 분류는 여전히 표준 분류 워크플로우를 통해 내보낼 수 있으며, 보고에서 계속 사용할 수 있습니다. |
| _보고서 총_ 계산 변경 | 업데이트 날짜: 2019년 7월 9일 | On **June 18, 2019**, Adobe Analytics made _Report Total_ calculations consistent across all dimensions and metrics. 이로 인해 일부 보고서 (일반적으로 prop 또는 고객 속성 보고서) 의 총계가 변경되었습니다. 본 변경에 앞서 일부 보고서 총계는 보고서에서 _미지정_ 으로 표시되는지의 여부와 관계없이, 총계의 _미지정_ 라인 항목에 일관성 없이 포함되거나 제외됩니다. <br/>2019년 6월 18일부터, _미지정_ 항목은 보고서의 라인 항목으로 표시되지 않는 경우에도 보고서 총계에 항상 표시됩니다. 또한 _exists_ 또는 _does not exist_ 로직을 사용하는 세그먼트는 이 변경 후 일부 차원에 대해 다른 결과를 볼 수 있습니다. 특히 _Unspecified_&#x200B;에 레퍼러 유형 차원에 대한 "Typed/Bookmarked" 라인 항목 또는 장치 유형 차원에 대한 "Other" 라인 항목 등의 특수 이름이 있는 차원입니다. 본 변경은 Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder 및 Reporting API에 적용됩니다. |
| Analysis Workspace에서 CSV 다운로드로 업데이트 | 2019년 4월 10일 | Starting on April 11, 2019, several changes were made to **[!UICONTROL CSV downloads]** (and **[!UICONTORL Copy to Clipboard]**) from Analysis Workspace to remove formatting from exported data.  <ul><li>천 단위 구분 기호가 더 이상 포함되지 않습니다. 소수점 구분 기호는 계속해서 포함되며, **[!UICONTROL 구성 요소 &gt; 보고서 설정 &gt; 천 단위 구분 기호]**&#x200B;에 정의된 형식을 따릅니다. 참고: 쉼표를 소수점 구분 기호로 사용하는 숫자 값은 내보낸 CSV에서 계속 따옴표로 표시됩니다.</li><li>통화 기호가 표시되지 않습니다.</li><li>퍼센트 기호가 표시되지 않습니다. 백분율은 10진수 형식입니다. 예를 들어, 75%는 0.75로 표시됩니다.</li><li>시간은 초 단위로 표시됩니다.</li><li>집단 테이블은 원시값만 표시합니다. 백분율이 제거됩니다.</li><li>숫자가 올바르지 않으면 빈 셀이 표시됩니다.</li></ul> |
| Analysis Workspace 디버거 명령 변경 예정 | 2019년 4월 4일 | **2019년 6월 13일**&#x200B;에 Analysis Workspace 디버거를 켜는 콘솔 명령이 adobeTools.debug.includeOberonXml로 변경됩니다. adobe.tools.debug.includeOberonXml은 이 날짜 이후에 작동이 중지됩니다. |
| 모바일 브라우저 버전 번호 | 2019년 2월 7일 | 2019년 1월 8일부터 모바일 브라우저 버전 번호의 자르기 레벨이 2에서 1로 변경되었습니다. 1월 8일부터는 버전에 첫 두 개 레벨만 표시됩니다(예: _Firefox 64.0.2_&#x200B;가 이제 _Firefox 64.0_&#x200B;으로 보고됨). |
| [!DNL Ad Hoc Analysis] 판매 종료 | 2019년 1월 29일 | 2018년 8월 6일, Adobe는 [!DNL Ad Hoc Analysis] 판매 종료 의사를 발표했습니다. 수명 종료 날짜는 확정된 후 공유될 예정입니다.<br/>이 기간 동안 호환되는 Java 버전을 포함하여 자세한 내용은 [ [! DNL Discover 작업 영역]](https://adobe.ly/discoverworkspace)를 참조하십시오. |
| 짧은 [!DNL Analytics] 보고서 링크 | 2019년 1월 14일 | 1년 안에 방문하지 않은 짧은 [!DNL Analytics] 보고서 링크는 롤링 일정에서 2019년 1월 17일 목요일부터 정리되고 삭제됩니다. |
| 데이터 피드: post_product_list 열 - 크기 변경 | 2019년 1월 9일 | Adobe는 2019년 2월 7일부터 post_product_list 열 크기를 64KB에서 16MB로 늘렸습니다. 이러한 변경으로 인해 처리 중에 post_product_list에 추가된 머천다이징 eVar 값이 제품 및 수익 값을 자르지 않아도 됩니다. post_product_list 값을 수집하는 프로세스가 있는 경우 해당 프로세스가 길이에서 최대 16MB의 값을 처리할 수 있는지 확인하거나 데이터 수집 실패를 방지하기 위해 16KB에서 값을 자릅니다. |
| 비활성 [!DNL Analytics Live Stream] 종단점에 영향을 주는 관리 변경 사항 | 2018년 12월 20일 | 2019년 2월 1일부터 90일 동안 활성 소비자 연결이 없는 [!DNL Live Stream] 종단점은 비활성화될 수 있습니다. 고객 지원 담당자에게 연락하여 [!DNL Live Stream] 종단점에 대해 문의하고, 필요한 경우 다시 활성화할 수 있습니다. 또한 소비자 프로세스가 서비스 설계에 의도한 대로 지속적 연결을 유지하도록 하고, 연결이 끊기거나 중단되는 경우 다시 연결하도록 구현되어 있는지 확인하십시오. |
| TLS 1.0에 대한 지원 종료로 인해 Adobe [!DNL Report Builder] 업데이트 | 2018년 9월 7일 |
| TLS 1.0 지원 종료 | 업데이트 날짜: 2019년 1월 10일 | TLS 1.0 은 |

### [!DNL AppMeasurement] {#appm}

Javascript 용 [appmeasurement 릴리스 노트를 참조하십시오](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

Audience Manager의 새로운 기능, 개선 사항 및 수정 사항

### 새로운 기능 및 향상된 기능 {#aam-features}

| 기능 | 설명 |
| -----------| ---------- |  
| **[People-based destinations](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html)** | [!DNLPEople 기반 대상은] 이메일 주소와 같이 해시된 식별자를 사용하여 Facebook와 같이 사용자 기반 환경에서 퍼스트 파티 대상 세그먼트를 활성화하는 데 도움이 되는 유료 Audience Manager 추가 기능입니다. |
| **[Twitter 맞춤 대상을 셀프 서비스 장치 기반 대상으로 구성](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/device-based/twitter-tailored-audiences.html)** | Twitter 대상을 셀프 서비스 구성 모델로 마이그레이션합니다. 이 문서에서는 기존 Twitter 통합에서 마이그레이션 후 작업을 계속 진행하기 위해 수행해야 하는 작업에 대해 설명합니다. |
| **[Audience Marketplace 요금 청구 예제](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/audience-marketplace/audience-marketplace-for-data-buyers/marketplace-buyer-billing.html#billing-examples)** | 활성화 및 모델링 사용 사례를 통해 세그먼트에 대한 청구가 작동하는 방식을 자세히 설명하는 사례 3 이 추가되었습니다. |

**수정 사항 및 향상된 기능**

* 사용자가 수동으로 세그먼트를 매핑할 수 있도록 Adobe Analytics 대상을 편집할 수 없던 버그가 수정되었습니다. (AAM-49323)
* 중복 대상 Marketplace 피드가 단일 데이터 소스 ID에서 발생한 버그를 수정했습니다. 데이터 소스와 [!DNL Marketplace] 피드 사이에 1:1 매핑이 있어야 합니다. (AAM-48504)
* 트레이트 및 세그먼트 제작 워크플로우가 향상되었습니다. 이제, 트레이트 또는 세그먼트를 저장하도록 데이터 소스를 필터링하여 비-Audience Manager 데이터 소스를 제외합니다 (예: Adobe Analytics의 보고서 세트 데이터 소스). (AAM-35899)
* Data Sources API에서 쿼리 매개 변수를 `ExcludeReportSuites=true` 설정하면 Adobe Analytics에서 보고서 세트 데이터 소스가 제외되지 않는 문제를 해결했습니다. (AAM-48545)
* Adobe Audience Manager 사용자 인터페이스의 접근성과 관련하여 몇 가지 개선 사항이 있었습니다. (AAM -49024) 및 (AAM -49031)

## Experience Manager {#aem}

Adobe Experience Manager(AEM)의 새로운 기능, 수정 내용 및 업데이트. 안정성, 보안 및 성능 향상을 위해 최신 패치를 배포하려는 경우 온-프레미스 배포를 사용하는 것이 좋습니다.

### 제품 릴리스

**Cloud Manager 2019.8.0**

Cloud Manager 릴리스 2019.8.0 에서는 사소한 버그가 다양하게 수정되고, 빌드 성능을 향상시키며, 선택적 컨텐츠 패키지에 대한 지원이 추가되었습니다.

* [Cloud Manager 2019.8.0 릴리스 노트](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### 제품 유지 관리

**AEM 유지 관리 릴리스 로드맵**

여기에 게시된 [AEM 유지 관리 릴리스 로드맵을 참조하십시오](https://helpx.adobe.com/experience-manager/maintenance-releases-roadmap.html).

### 사용자 도움말

**Asset Link 1.1 베타 버전**

* [Adobe Asset Link 베타 버전 정보](https://helpx.adobe.com/enterprise/using/adobe-asset-link-prerelease.html)
* [베타 버전에서 Adobe 에셋 링크에 대한 AEM 구성](https://helpx.adobe.com/enterprise/using/configure-aem-for-aal-prerelease.html)

**AEM Desktop App 2.0**

MAC 용 AEM 데스크탑 앱 2.0는 2019 년 8 월 30 일에 출시되었습니다. Windows 용 AEM 데스크탑 앱 2.0는 9 월 초에 출시될 예정입니다.

여기에서 문서에 액세스하고 [](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/introduction.html)다운로드하십시오.

**자산 스마트 태그**

여기에서 만료된 [후 인증서를 업데이트하는 방법을 알아봅니다](https://helpx.adobe.com/experience-manager/6-5/assets/using/config-smart-tagging.html#Obtainpubliccertificate).

**AEM 6.5 Screens 사용자 안내서**

_이제 네트워크 배포 가이드라인에_ 대한 새 설명서를 사용할 수 있습니다. [ 사용 안내서](https://helpx.adobe.com/experience-manager/6-5/screens/user-guide.html)를 참조하십시오.

**자동화된 양식 변환 서비스**

AEM Forms 자동화된 양식 변환 서비스에 대한 설명서를 이제 사용할 수 있습니다. 자동화된 양식 변환 서비스 [소개를](https://helpx.adobe.com/experience-manager/Automated-Forms-Conversion-Service/introduction-to-automated-form-conversion-service.html)참조하십시오.

### 커뮤니티

**AEM Skill Builder 웨비나**

* [Adobe Experience Manager Sites](https://forums.adobe.com/thread/2647742)

   | 웨비나 | 날짜 |
   | -----------| ---------- |  
   | _웹 경험 제작_ | 2019 년 8 월 27 일 |
   | _컨텐츠 검색 및 탐색_ | 2019 년 9 월 3 일 |
   | _손쉽게 진화하는 콘텐츠 관리_ | 2019 년 9 월 10 일 |
   | _유연한 경험_ | 2019 년 9 월 17 일 |
   | _다국어, 다중 국가 생성 및 관리 - 글로벌 웹 사이트 구조를 디자인합니다._ | 2019 년 9 월 24 일 |

* [Adobe Experience Manager Assets](https://forums.adobe.com/thread/2647743)

   | 웨비나 | 날짜 |
   | -----------| ---------- |  
   | _폴더 구조 및 검색_ | 2019 년 8 월 29 일 |
   | _메타데이터_ | 2019 년 9 월 5 일 |
   | _Brand Portal_ | 2019 년 9 월 12 일 |
   | _Dynamic Media_ | 2019 년 9 월 19 일 |
   | _자산 링크_ | 2019 년 9 월 26 일 |

* [Adobe Experience Manager Forms](https://forums.adobe.com/thread/2647744)

   | 웨비나 | 날짜 |
   | -----------| ---------- |  
   | 양식 101_ | 2019 년 9 월 4 일 |
   | _양식에 양식을 연결하고 워크플로우를 구축하며 전자 서명과 양식 통합_ | 2019 년 9 월 11 일 |
   | _모바일 반응형 웹 및 인쇄용 인터랙티브 커뮤니케이션 제작_ | 2019 년 9 월 25 일 |

* [Adobe Experience Manager Cloud Manager](https://forums.adobe.com/thread/2647745)

   | 웨비나 | 날짜 |
   | -----------| ---------- |  
   | _테스트 모범 사례 - 클라우드 관리자를 사용하여 실행, 모니터링, 감사 및 통찰력 구축_ | 2019 년 9 월 18 일 |
   | _클라우드 관리자를 사용한 Dispatcher 구성_ | 2019 년 10 월 16 일 |
   | _클라우드 관리자 및 타사 도구를 사용하여 워크플로우 만들기_ | 2019 년 11 월 13 일 |

### 추가 리소스

* [AEM 6.5 학습 및 지원 홈](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 학습 및 지원 홈](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 학습 및 지원 홈](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 학습 및 지원 홈](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager 사용 안내서](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [이전 버전의 AEM 설명서](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic 도움말 홈](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Dynamic Media 릴리스 노트](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre 릴리스 노트](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

### 제품 사용 종료

[!DNL Digital Publishing Suite Classic] (DPSC) 2019 년 8 월 31 일에 사용이 종료됩니다. For more information, see the [[!DNL Digital Publishing Suite Classic] End-of-Life FAQ](https://helpx.adobe.com/digital-publishing-suite/help/eol-statement-for-dpsc.html).

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

### Adobe Campaign Classic

* [Campaign Classic 19.1.4 업데이트](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9032) - Build 9032
* [Campaign Classic 19.1.5 업데이트](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9033) - Build 9033

### Adobe Campaign [!UICONTROL Control Panel]

관리 사용자는 도메인에 대한 SSL 인증서가 만료되기 전에 알림을 받을 수 있는 새로운 기능을 추가했습니다. 자세한 내용은 [상세 문서](https://helpx.adobe.com/campaign/kb/control-panel-subdomains-certificates.html)를 참조하십시오.

또한 이제 관리 사용자는 Sftp 서버에 액세스하기 위해 추가된 SSH 키를 삭제할 수 있습니다.

[!UICONTROL 제어판]은 AWS에서 호스팅되는 Adobe Campaign Classic 고객과 Adobe Campaign Standard 고객 모두 사용할 수 있습니다. [!UICONTROL 제어판에]대한 업그레이드는 필요하지 않습니다.

### 추가 리소스

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
