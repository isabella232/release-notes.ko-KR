---
title: Adobe Experience Cloud 릴리스 노트
description: Experience Cloud 릴리스 노트 템플릿
doc-type: 릴리스 노트
last-update: 2019년 5월
author: mfrei
translation-type: tm+mt
source-git-commit: c8db350233cea9b83993e4723601b01a8e301f87

---


# Adobe Experience Cloud 릴리스 노트

Adobe Experience Cloud의 새로운 기능 및 수정 사항.

>[!NOTE]
>예정된 릴리스에 대한 이메일 알림을 받으려면 [Adobe 우선 제품 업데이트](https://www.adobe.com/subscription/priority-product-update.html)에 가입하십시오. 업무일 기준으로 릴리스 3-5일 전에 공지를 받게 됩니다. 릴리스 후 게시된 새 정보는 발행 날짜로 표시됩니다.

**릴리스 날짜: 2019 년 5 월**

* [Adobe Experience Platform](#platform)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [캠페인](#ac)
* [Advertising Cloud](#adcloud)
* [Target Standard/Premium 19.5.1](#target)
* [Magento](#magento)
* [Primetime](#primetime)

## Adobe Experience Platform {#platform}

### Adobe Experience Platform 릴리스 노트

버전 1.0, 2019 년 5 월 15 일

* 경험 플랫폼에 대한 최신 업데이트를 보려면 Adobe. io에서 [Experience Platform 릴리스 노트를](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes-20190515.md) 참조하십시오.

### Experience Platform Launch

* 최신 정보는 [Experience Platform Launch](https://docs.adobelaunch.com/) 를 참조하십시오.

### Experience Cloud ID 서비스

**2019년 5월 13일** 릴리스

* Visitor API 4.3.0 지원
* ITP 2.1 지원.
* secureCookie 구성 관련 문제를 해결했습니다.

## Analytics {#analytics}

Adobe Analytics의 새로운 기능 및 수정 내용:

* [Adobe Analytics의 새로운 기능 및 수정 내용](#aa-features)
* [Analytics 관리자에 대한 중요 공지](#aa-notices)

제품 설명서의 경우 [Analytics 도움말 홈](https://marketing.adobe.com/resources/help/en_US/reference/)을 참조하십시오.

### Adobe Analytics의 새로운 기능 및 수정 내용 {#aa-features}

| 기능 | 설명 |
| -----------| ---------- |  
| [!DNL AppMeasurement Version 2.14.0] <ul><li>여러 개의 히트가 보류 중일 때 추적기 매개 변수 상태 관리에 대한 문제가 해결되었습니다. (AN -176931, AN -176629, DTM -12758)</li><li>Visitor. js 4.3.0를 포함하도록 appmeasurement를 업데이트했습니다 (AN -180049).</li></ul> |
| [!DNL Analysis Workspace]: 새 _반복 인스턴스 포함_ 흐름 시각화 설정 | _반복 인스턴스 포함_ 흐름 설정은 페이지 다시 로드와 같은 반복된 인스턴스를 포함하거나 제외하는 옵션을 제공합니다. 또한 모든 흐름 시각화는 이제 인스턴스만 기반으로 합니다. |
| [!DNL Ad Hoc Analysis]: Java 11과의 호환성 | Ad Hoc Analysis는 이제 Java 11과 호환됩니다. Java 11에서 애드혹 분석을 실행하는 [](https://marketing.adobe.com/resources/help/en_US/dsc/adhoc-java.html)방법을 학습합니다. |
| **데이터 수집:** 새 s_ ecid 쿠키 | 데이터 수집에서 방문자의 ECID를 저장하는 새로운 자사 서버 쿠키인 s_ecid가 추가되었습니다. |

**Analysis Workspace 공간 수정 사항**

* **[!UICONTROL 페이지 체류 시간에 영향을 주는 문제가 해결되었습니다]**. [!DNL Analysis Workspace] 보고서는 체류 시간 버킷을 계산할 때 더 이상 페이지 이름을 사용하지 않고, 계산할 세부 및 그룹화된 적중 수를 활성화합니다. **[!UICONTROL ]****[!UICONTROL ]** (AN-140479)
* 성능을 개선하기 [!DNL Analysis Workspace] 위한 더 큰 노력의 일환으로 라인 시각화 성능 문제를 해결했습니다. (AN-174878)
* 다운로드한 .csv 파일에서 UTF-8 인코딩이 없는 문제가 해결되었습니다. (AN-178393)
* 프로젝트 성능 저하 [!DNL Analysis Workspace] 문제가 해결되었습니다. (AN-177710)
* y축의 작은 세분 기간 범위로 라인 시각화가 표시되는 문제가 해결되었습니다. (AN-176467)

**기타 Analytics 수정 사항**

* [!DNL Audience Analytics]: 대상 이름이 변경된 [!DNL Audience Manager (AAM)] 후에 발생하던 문제를 수정했습니다. 업데이트된 이름은 대상 분석에서 반영되지 않았습니다. (AN-176237)
* 사용자가 [! DNL Analytics 세그먼트 [!DNL Audience Manager]. 이 문제는 기존 AAM 폴더 이름에 대문자와 소문자가 혼용되어 발생한 것입니다. 이제 모든 폴더가 동기화되도록 대/소문자를 구분하지 않고 처리합니다. (AN-177934)
* 사용자가를 (를) [!DNL Analytics] 통해 로그인했을 때 세션이 시간 [!DNL Experience Cloud] 초과되는 문제가 해결되었습니다. 세션을 재개할 때 사용자가 결함이 있는 URL로 리디렉션됩니다. (AN-176812)
* 요청의 시간대 오프셋 문제를 [!DNL Data Warehouse] 수정했습니다. (AN-177585)

### Analytics 관리자에 대한 중요 공지 {#aa-notices}

| 알림 | 추가한 날짜 업데이트한 날짜 | 설명 |
| -----------| ---------- | ---------- |
| **[!UICONTROL Date-Enabled]** 및 **[!UICONTROL Numeric 2 분류에 대한 향후 지원 변경 사항]** | 업데이트 날짜: 2019년 5월 28일 | Numeric 2 및 날짜 지원 분류를 가져오는 기능이 코드베이스에 제거됩니다. 이 변경 사항은 2019 년 7 월 유지관리 릴리스에서 적용됩니다. 가져온 파일에 숫자 또는 활성화된 날짜 열이 있는 경우 해당 셀은 자동으로 무시되며, 해당 파일의 다른 모든 데이터는 정상적으로 가져와집니다. <br/>기존 분류는 여전히 표준 분류 워크플로우를 통해 내보낼 수 있으며, 보고에서 계속 사용할 수 있습니다. |
| _보고서 총계_ 계산과 관련한 변경 예정 | 업데이트 날짜: 2019년 5월 2일 | **2019년 6월 13일** 에 Adobe Analytics는 모든 차원 및 지표에서 _보고서 총계_를 동일하게 변경할 예정입니다. 이를 통해 일부 보고서(예: Prop 또는 고객 특성 보고서)의 총계가 변경됩니다. 본 변경에 앞서 일부 보고서 총계는 보고서에서 _미지정_으로 표시되는지의 여부와 관계없이, 총계의 _미지정_ 라인 항목에 일관성 없이 포함되거나 제외됩니다. <br/>2019년 6월 13일부터, _미지정_ 항목은 보고서의 라인 항목으로 표시되지 않는 경우에도 보고서 총계에 항상 표시됩니다. 또한 _존재하는_ 논리 또는 _존재하지 않는_ 논리를 사용하는 세그먼트는 이러한 변경 이후 일부 차원에 대해 다른 결과가 나타날 수 있습니다. 본 변경은 Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder 및 Reporting API에 적용됩니다. |
| CSV 다운로드로 업데이트 [!DNL Analysis Workspace] | 2019년 4월 10일 | 2019 년 4 월 11 일부터 내보낸 데이터에서 서식을 제거하기 위해 **[!UICONTROL CSV 다운로드]** (및 **[!UICONTORL 클립보드에 복사]**) [!DNL Analysis Workspace] 가 몇 가지 변경되었습니다.  <ul><li>천 단위 구분 기호는 더 이상 포함되지 않습니다. 소수점 구분 기호는 계속해서 포함되며, **[!UICONTROL 구성 요소 &gt; 보고서 설정 &gt; 천 단위 구분 기호]** 에 정의된 형식을 따릅니다. 참고: 쉼표를 소수점 구분 기호로 사용하는 숫자 값은 내보낸 CSV에서 계속 따옴표로 표시됩니다.</li><li>통화 기호가 표시되지 않습니다.</li><li>퍼센트 기호가 표시되지 않습니다. 백분율은 10진수 형식입니다. 예를 들어, 75%는 0.75로 표시됩니다.</li><li>시간은 초 단위로 표시됩니다.</li><li>집단 테이블은 원시값만 표시합니다. 백분율이 제거됩니다.</li><li>숫자가 올바르지 않으면 빈 셀이 표시됩니다.</li></ul> |
| 예정된 [!DNL Analysis Workspace] 디버거 명령 변경 | 2019년 4월 4일 | [!DNL Analysis Workspace] 디버거를 켜려는 콘솔 명령은 2019 **년 6 월 13 일에 Adobetools. debug. includeoberonxml로 변경됩니다**. adobe.tools.debug.includeOberonXml은 이 날짜 이후에 작동이 중지됩니다. |
| 모바일 브라우저 버전 번호 | 2019년 2월 7일 | 2019년 1월 8일부터 모바일 브라우저 버전 번호의 자르기 레벨이 2에서 1로 변경되었습니다. 1월 8일부터는 버전에 첫 두 개 레벨만 표시됩니다(예: _Firefox 64.0.2_가 이제 _Firefox 64.0_으로 보고됨). |
| Life of Life [!DNL Ad Hoc Analysis] | 2019년 1월 29일 | 2018 년 8 월 6 일, Adobe는 사용 종료 의사를 [!DNL Ad Hoc Analysis]발표했습니다. 수명 종료 날짜는 확정된 후 공유될 예정입니다.<br/>이 기간 동안의 Java 호환 버전 등 자세한 정보는 [Discover Workspace](https://adobe.ly/discoverworkspace)를 참조하십시오. |
| 짧은 Analytics 보고서 링크 | 2019년 1월 14일 | 1년 안에 방문하지 않은 짧은 Analytics 보고서 링크는 롤링 일정에서 2019년 1월 17일, 목요일부터 정리되고 삭제됩니다. |
| TLS 1.0 지원 종료 | 업데이트 날짜: 2019년 1월 10일 | 2019년 2월 11일부터 Adobe Analytics 보고에서는 더 이상 TLS(Transport Layer Security) 1.0 암호화를 지원하지 않습니다. 이 변경은 가장 높은 보안 표준을 유지하고 고객 데이터의 안전을 홍보하기 위해 진행 중인 노력의 일환입니다. 2019 년 2 월 11 일 이후에 Adobe Analytics 보고에 연결할 수 없는 경우 브라우저를 [최신 버전으로 업그레이드해야](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html)합니다.<br/> 2019년 2월 20일부터 Adobe Analytics 데이터 수집에서는 더 이상 TLS 1.0을 지원하지 않습니다. 이 변경으로, Adobe에서는 더 이상 TLS 1.1 이상을 지원하지 않는 이전 장치 또는 웹 브라우저를 사용하는 최종 사용자의 Analytics 데이터를 수집하지 않습니다. 이렇게 해도 고객 데이터 또는 보고에 큰 영향을 주지는 않습니다. (웹 사이트에서 TLS 1.0을 지원하지 않는 경우는 영향을 받지 않습니다.) <br/>2019년 4월 11일부터 Adobe Analytics Reporting API는 더 이상 TLS 1.0 암호화를 지원하지 않습니다. API에 액세스하는 고객은 자신들에게 영향이 없는지 확인해야 합니다. <ul><li>기본 설정으로 Java 7을 사용하는 API 클라이언트는 [TLS 1.2를 지원하도록 수정](https://www.java.com/en/configure_crypto.html)해야 합니다. (_클라이언트 종단점에 대한 기본 TLS 프로토콜 버전을 TLS 1.0에서 TLS 1.2로 변경_을 참조하십시오.) </li><li>기본 설정은 TLS 1.2 이기 때문에 Java 8를 사용하는 API 클라이언트는 영향을 받으면 안 됩니다.</li><li> 다른 프레임워크를 사용하는 API 클라이언트의 경우 TLS 1.2 지원에 대한 자세한 내용을 알려면 해당 공급업체에 문의해야 합니다.</li></ul> |
| 데이터 피드: post_product_list 열 - 크기 변경 | 2019년 1월 9일 | Adobe는 2019년 2월 7일부터 post_product_list 열 크기를 64KB에서 16MB로 늘렸습니다. 이 변경 사항은 처리 중에 post_ product_ list에 머천다이징 evar 값이 제품 및 매출 값이 잘리지 않도록 합니다. post_product_list 값을 수집하는 프로세스가 있는 경우 해당 프로세스가 길이에서 최대 16MB의 값을 처리할 수 있는지 확인하거나 데이터 수집 실패를 방지하기 위해 16KB에서 값을 자릅니다. |
| 비활성 [!DNL Analytics Live Stream] 끝점에 영향을 주는 관리 변경 사항 | 2018년 12월 20일 | 2019 년 2 월 1 일부터 90 일 동안 활성 소비자 연결이 없는 [!DNL Live Stream] 끝점이 비활성화될 수 있습니다. 고객 지원 센터에 연락하여 엔드포인트에 대해 문의하고 [!DNL Live Stream] 필요한 경우 다시 활성화할 수 있습니다. 또한 소비자 프로세스가 서비스 설계에 의도한 대로 지속적 연결을 유지하도록 하고, 연결이 끊기거나 중단되는 경우 다시 연결하도록 구현되어 있는지 확인하십시오. |
| TLS 1.0에 대한 지원 종료로 인해 Adobe [!DNL Report Builder] 업데이트 | 2018년 9월 7일 | TLS 1.0 지원 종료로 [!DNL Report Builder] 인해 사용자가 2019 년 2 월 이전에 버전 v 5.6.21를 다운로드할 것을 권장합니다. 그 이후에는 이전 버전이 더 이상 [!DNL Report Builder] 작동하지 않습니다. |

## Audience Manager {#aam}

| 기능 | 설명 |
| -----------| ---------- |  
| [IP 주소 난독화](https://marketing.adobe.com/resources/help/en_US/aam/ip-obfuscation.html) | 회사에서 글로벌 개인 정보 보호 규정으로 인해 여러 국가의 IP 주소를 난독 처리하려고 할 수 있습니다. Audience Manager를 사용하면 글로벌 또는 국가별로 방문자 IP 주소를 난독 처리할 수 있습니다. |
| [사용자 지정 파트너 통합 - Oracle Data Cloud](https://marketing.adobe.com/resources/help/en_US/aam/custom-partner-integrations.html) | 이 페이지에 Audience Manager와 데이터 파트너 간의 사용자 지정 통합 목록이 표시됩니다. Audience Manager는 인바운드 데이터 파일을 통해 Oracle Data Cloud for Audience Marketplace의 쿠키 및 모바일 ID 데이터를 통합합니다. 이 페이지에 설명된 사용자 지정 통합 사양은 모바일 ID(IDFA 및 Android 장치 ID)가 포함된 인바운드 데이터 파일만을 참조합니다. |

**수정 사항, 개선 사항 및 중단 사항**

* 대상에 대한 일반 보고서에 두 개의 열을 새로 추가했습니다. 이제 대상의 세그먼트 매핑에 대한 시작 날짜와 종료 날짜를 확인할 수 있습니다. (AAM-44781)

## Experience Manager {#aem}

Adobe Experience Manager(AEM)의 새로운 기능, 수정 내용 및 업데이트. 안정성, 보안 및 성능 향상을 위해 최신 패치를 배포하려는 경우 온-프레미스 배포를 사용하는 것이 좋습니다.

### 제품 릴리스

**AEM 6.5**

2019년 4월 8일부터 사용 가능한 AEM 6.5는 AEM 6.4 코드베이스에 대한 업그레이드 릴리스입니다. AEM 6.5에 대한 최신 업데이트를 통해 비즈니스를 더욱 빠르게 성장시킬 수 있는 흥미로운 개선 사항에 즉시 액세스할 수 있습니다.

* [Adobe Experience Manager 6.5의 새로운 기능](https://www.adobe.com/marketing/experience-manager/new.html)
* [Adobe Experience Manager 6.5 릴리스 노트](https://helpx.adobe.com/experience-manager/6-5/release-notes.html)

**Cloud Manager 2019.4.0**

최신 Cloud Manager 릴리스(2019.4.0이 2019년 4월 18일에 릴리스됨)는 프랑스어, 독일어 및 일본어로 현지화된 사용자 인터페이스를 추가합니다. 또한 배포 단계가 개선되었습니다.

* [Cloud Manager 2019.4.0 릴리스 노트](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### 제품 유지 관리

**AEM 6.4.4.0**

2019년 4월 4일에 릴리스된 AEM 6.4 서비스 팩 4(6.4.4.0)는 2018년 4월, AEM 6.4의 공식 출시 이후 릴리스된 주요 고객 수정 사항을 포함하는 중요한 업데이트입니다.

[AEM 6.4 서비스 팩 릴리스 노트](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
[AEM 양식 릴리스](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM S3 Connector**

2019년 6월 24일에 서명 버전 2에 대한 지원 종료 이후, S3 데이터 저장소 커넥터를 사용하는 AEM 인스턴스를 사용할 수 없을 수 있습니다. AEM 고객으로서, 사용 중인 S3 데이터 저장소 커넥터의 버전을 확인하는 것이 좋습니다. 필요한 경우 최신 버전으로 업데이트하십시오.

자세한 내용은 [Amazon S3용 AWS 서명 버전 2 사용 중단의 영향](https://helpx.adobe.com/experience-manager/kb/the-impact-of-aws-signature-version-2-deprecation-for-amazon-s3.html)을 참조하십시오.

### 사용자 도움말

**AEM Sites 코드베이스 현대화**

최신 AEM 기술을 활용하여 AEM Sites 코드베이스를 현대화하는 방법을 알아봅니다. [기존 Adobe Experience Manager Sites 코드 베이스 현대화](https://expleague.azureedge.net/labs/L761/index.html)

**AEM 리치 텍스트 편집기 - 자세히 알아보기**

AEM에서 리치 텍스트 편집기 사용 및 다양한 구성에 대한 권장 지침을 알아봅니다.

[AEM RTE(리치 텍스트 편집기) 자세히 알아보기](https://helpx.adobe.com/experience-manager/kt/eseminars/gems/AEM-Rich-Text-Editor-RTE-Deep-Dive1.html)를 참조하십시오.

### 추가 리소스

* [AEM 6.5 학습 및 지원 홈](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 학습 및 지원 홈](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 학습 및 지원 홈](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 학습 및 지원 홈](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager 사용 안내서](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [이전 버전의 AEM 설명서](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Scene7 Publishing System 릴리스 노트](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre 릴리스 노트](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## 캠페인 {#ac}

Adobe Campaign은 온라인 및 오프라인 마케팅 채널 간에 직관적이고, 자동화된 방식으로 일대일 메시지를 제공합니다. 이제 고객이 습관 및 선호도에 따라 결정된 작업 환경을 통해 원하는 사항을 예측할 수 있습니다.

* Campaign Classic 18.10.4 - Build 8983
* Campaign Classic 18.10.5 - Build 8984

수정 사항 및 개선 사항은 [Adobe Campaign Classic 릴리스 노트](http://docs.campaign.adobe.com/doc/AC/en/RN.html)를 참조하십시오.

제품 설명서의 경우 다음을 참조하십시오.

* Adobe Campaign Standard: [설명서](https://helpx.adobe.com/support/campaign/standard.html) - [ 릴리스 노트](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [ 기능 비디오](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [설명서](https://helpx.adobe.com/support/campaign/classic.html) - [릴리스 노트](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [ 기능 비디오](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Advertising Cloud {#adcloud}

| 기능 | 설명 |
| -----------| ---------- |  
| 검색 도구 | (Google 광고 계정이 있는 광고주) Advertising Cloud에서는 Advertising Cloud 전환 추적 서비스를 사용하는 Google 광고 캠페인을 추적하여 모든 변환 데이터를 Google 광고에 선택적으로 업로드할 수 있습니다. 일별 업로드에는 광고주 수준의 속성 모델을 사용하여 정의된 변환 값이 포함됩니다. 업로드된 모든 변환에는 &quot;Adobe_ACS_&quot; 접두사가 추가됩니다(예: &quot;Subscriptions&quot; 변환의 경우 &quot;Adobe_ACS_Subscriptions&quot;). <br/> **참고:** 이 업로드에는 피드 파일에서 Advertising Cloud에 업로드되는 변환 데이터가 포함되지 않습니다. |
| 캠페인 검색 | **검색** &gt; **캠페인** &gt; **캠페인의** 메뉴는 이제 계정 아래의 캠페인과 함께 계층적 상태입니다. 캠페인 아래의 광고 그룹; 키워드 (하위 메뉴가 있음), 광고, 제품 그룹 (라이브 보기만), 배치 (하위 메뉴가 있는 경우), 광고 그룹 아래의 자동 타겟이 있습니다.<br/>라이브 뷰에서 대상 및 확장자는 자체 하위 메뉴가 있는 계정과 동일한 수준에 있습니다. |

## Target Standard/Premium 19.5.1 {#target}

이 릴리스에는 다음과 같은 기능, 변경 사항 및 개선 사항이 포함되었습니다.

(괄호 안의 문제 번호는 내부 Adobe용입니다.)

### 기능 업데이트

| 기능/향상 | 설명 |
| --- | --- |
| SPA VEC(Single Page App Visual Experience Composer) | SPA VEC에는 작업을 보다 빠르고 효율적으로 수행할 수 있도록 다음과 같은 개선 사항이 포함되어 있습니다.<ul><li>이제 VEC에서 웹 사이트 로드를 취소하여 활동 편집을 차단 해제할 수 있습니다. 이 개선 사항은 활동을 약간 편집하거나, 설정을 검토하거나, 사용자 지정 코드를 추가하고 사이트가 로드될 때까지 기다리지 않으려는 경우에 유용합니다. (TGT-33872)</li><li>페이지가 VEC에 로드되기 전에 또는 페이지가 완전히 로드되지 않은 경우에도 여러 작업을 수행할 수 있습니다(예: 사용자 지정 코드가 더 이상 작동하지 않음). 사이트가 로드되기 전에 편집할 수 없는 작업은 Target UI에서 비활성화됩니다. (TGT-33851 및 TGT-34149)</li></ul> |
| AP(자동화된 개인화) 및 자동 타겟 활동 | AP 또는 자동 타겟 활동을 작성하는 동안 컨트롤로 사용할 환경을 선택할 수 있습니다. 이 기능을 사용하면 활동에 구성된 트래픽 할당 비율에 따라 전체 제어 트래픽을 특정 환경으로 라우팅할 수 있습니다. 그런 다음 제어 환경에 대해 개인화된 작업 성능을 평가할 수 있습니다. (TGT-26572) |
| 권장 사항 | 최근에 본 항목 로직을 생성하는 동안 이전에 구입한 추천 항목 전환을 사용할 수 있습니다. (TGT-34030) |

### 개선 사항, 수정 사항 및 변경 사항

* VEC 내에서 페이지 로드를 취소하면 도구 모음 아이콘이 적절하게 표시됩니다. 페이지가 완전히 로드될 때까지 특정 작업을 수행할 수 없는 경우 연관된 도구 모음 아이콘이 비활성화됩니다. (TGT-33811)
* 이제 일반 폴더 계층 구조를 탐색하는 대신 자산 선택기에서 오퍼 폴더를 통해 보다 쉽게 나열하고 탐색할 수 있습니다. (TGT-33725)

다음 제품에 대한 최신 릴리스 정보가 필요하면 [Adobe Target 릴리스 노트](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)를 참조하십시오.

* Target Standard 및 Target Premium
* Recommendations Classic 

## Magento {#magento}

Magento는 유연한 쇼핑 카트 시스템과 해당 온라인 스토어의 외관, 컨텐츠 및 기능을 제어하는 기능과 함께 온라인 가맹점을 제공하는 전자 상거래 플랫폼입니다. Magento는 오픈 소스 버전 및 전체 기능 상거래 버전으로 사용할 수 있습니다.

Magento Commerce는 Adobe Commerce Cloud의 일부이며, B2C 및 B2B 환경을 위한 엔터프라이즈 등급의 무제한 확장 가능성과 오픈 소스 유연성이 포함된 전자 상거래 솔루션을 제공합니다.에서 보냅니다.

오픈 소스 및 커머스 에디션에 대한 릴리스 노트는 [릴리스 정보](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html) 페이지에서 확인할 수 있습니다.

## Primetime {#primetime}

Adobe Primetime은 미디어 회사가 개인화된 시청 환경을 제공하며 수익을 창출할 수 있도록 도와주는 멀티스크린 TV 플랫폼입니다.

[Primetime 릴리스 노트](http://help.adobe.com/en_US/primetime/release_notes/index.html)
[Primetime 도움말 홈](http://help.adobe.com/en_US/primetime/)