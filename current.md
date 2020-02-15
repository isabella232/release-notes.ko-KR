---
title: Adobe Experience Cloud 릴리스 노트
description: Experience Cloud 릴리스 노트 템플릿
doc-type: release notes
last-update: February 2020
author: mfrei
translation-type: tm+mt
source-git-commit: d61884a3de7bd7c8d32fb9dc88727e82083ca5c1

---


# 조기 이용 - Adobe Experience Cloud 릴리스 노트 - 2020년 2월

Adobe Experience Cloud의 새로운 기능 및 수정 사항.

>[!IMPORTANT]
>이 페이지에는 출시 전 컨텐츠가 포함되어 있으며 계획된 출시 전에 변경될 수 있습니다.

>[!NOTE]
>예정된 릴리스에 대한 이메일 알림을 받으려면 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)
에 가입하십시오. 릴리스 후 게시된 새 정보는 발행 날짜로 표시됩니다.

**릴리스 날짜: 2020년 2월 20일**

(특정 제품 릴리스 날짜는 매우 다양함)

최신 업데이트:2020년 2월 10일

* [Adobe 시스템 상태](#status)
* [Experience Cloud 인터페이스 및 핵심 서비스](#ecloud)
* [Experience Platform](#platform)
* [Mobile Services 및 Mobile SDK](#mobile)
* [!DNL Analytics](#analytics) **(2020년 1월 21일 업데이트됨)**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (솔루션 도움말 링크)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (솔루션 도움말 링크)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)

도움말 홈을 찾고 계십니까? [Adobe Experience Cloud 설명서](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html)를 참조하십시오.

## Adobe 시스템 상태 {#status}

[!UICONTROL Adobe 시스템 상태]는 Adobe 클라우드 제품 및 서비스 중단, 중단 및 유지 관리 이벤트에 대한 자세한 정보, 상태 업데이트 및 이메일 알림을 제공합니다. [status.adobe.com](https://status.adobe.com/)에서 관련 정보를 확인하십시오.

**새로운 기능**

* Adobe ID를 사용하여 제품, 지역, 이벤트 및 언어 기본 설정에 따라 이벤트 알림을 구독할 수 있습니다. 구독 기본 설정을 구성하는 사용자는 제품 사고 및 유지 관리 이벤트를 열어서 업데이트하거나 닫으면 즉시 알림을 받게 됩니다. [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)에서 시작해 보십시오.

**현재 사용할 수 있는 새로운 기능 및 향상된 기능**

| 기능 | 설명 |
| -----------| ---------- |
| 제품 이벤트에 대한 신속한 인식 | <ul><li>향후 서비스 유지 관리에 대해 30일 전에 알려주십시오. 이 기능을 사용하면 비즈니스 운영에 미치는 잠재적 영향을 평가할 수 있으므로 필요한 경우 완화 계획을 구현할 수 있습니다.</li><li>고급 알림은 웹/모바일/태블릿 지표와 이메일 알림을 통해 사용할 수 있습니다.</li></ul> |
| 원하는 언어를 기반으로 경험 개인화 | <ul><li>이메일 알림의 기본 언어를 선택합니다. 자체 구독 기능은 현재 19개 언어로 제공됩니다.</li></ul> |
| 향상된 구독 및 알림 사용자 환경 | <ul><li>가입하려는 모든 제품에 대해 한 번의 클릭으로 지역 및 이벤트 기본 설정을 지정할 수 있습니다.</li><li>잠재적 문제가 _사소한_ 문제 또는 주요 문제로 _승격되면_ 알림을 _받습니다_ .</li><li>제품 또는 이벤트 상태가 업데이트되면 브라우저 페이지가 자동으로 새로 고쳐집니다.</li></ul> |

## Experience Cloud 인터페이스 및 핵심 서비스 {#ecloud}

관리 및 핵심 서비스(고객 특성, 대상, 트리거, 쿠키 등)를 비롯한 Experience Cloud 인터페이스의 새로운 기능 및 수정 사항.

**수정 사항**

* **** 고객 속성:이제 고객 속성 UI에 Target에 동기화된 프로파일의 추가 상태가 표시됩니다. (MCUI-10231)
* **** 트리거 코어 서비스:사용 부족으로 포기 유형 트리거를 만들 때 성향 점수 &quot;30일 후에 돌아올 가능성&quot;이 제거되었습니다. (MCUI-10056)

### 통합 제품 도메인

Adobe는 모든 Experience Cloud 애플리케이션에서 사용자 경험을 통합하고 개선하기 위해 도메인 및 인터페이스 헤더를 업데이트하고 있습니다. 이러한 개선 사항은 작지만 중요한 방식으로 경험을 간소화하도록 설계되었습니다. 이러한 개선 사항은 현재 워크플로우를 변경하지 않습니다.

업데이트 내용은 다음과 같습니다.

* 새로운 솔루션 URL: `experience.adobe.com/<application name>`:
   * 모든 제품이 결국 이 URL 패턴을 채택합니다. 한 달 동안 새 URL이 유효한지 확인합니다.
   * Browser support: Supported browsers include [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari], and [!DNL Opera] (latest versions). **참고:** Experience Cloud 인터페이스는 이러한 브라우저를 지원하지만 개별 솔루션은 모든 브라우저를 지원하지 않을 수 있습니다. (예: [Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html)는 [!DNL Opera]를 지원하지 않으며, [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html)은 [!DNL Safari]를 지원하지 않습니다.)
   * ([!DNL Safari] 전용) 도메인 변경으로 인해 [!DNL Safari]에 쿠키 문제가 발생할 수 있습니다. Deselecting _Prevent cross-site tracking_ in the [!DNL Safari] Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Experience Cloud to function on this new domain.
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

**2020년 2월 4일:버전 4.19.0**

이 릴리스에서는 다음과 같은 업데이트가 수행되었습니다.

**** 라이프사이클:일부 이전 iOS 장치에서 보고된 비정상적인 세션 길이 데이터를 완화하도록 `pauseCollectingLifecycleData`새 API를 추가했습니다.

## [!DNL Analytics] {#analytics}

Adobe Analytics의 새로운 기능 및 수정 내용:

* [Adobe Analytics의 새로운 기능, 향상된 기능 및 수정 내용](#aa-features) (2020년 1월 21일 업데이트됨)
* [Analytics 관리자에 대한 중요 공지](#aa-notices)
* [AppMeasurement](#appm)

제품 설명서는 [Adobe Analytics 도움말 홈](https://docs.adobe.com/content/help/en/analytics/landing/home.html)을 참조하십시오.

### Adobe Analytics의 새로운 기능, 향상된 기능 및 수정 내용 {#aa-features}

<!--* **Support for multiple report suites in Workspace:** You can now bring in data from multiple report suites into a single project to view side by side. Beginning on Feb 20, 2020, the feature will roll out to all customers over the course of several weeks. [Learn more...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)-->
* **크로스**&#x200B;디바이스 분석을 사용하는 조직을 위한 새로운 작업 영역 템플릿:이 템플릿에서는 CDA가 방문 횟수를 합치는 데 얼마나 효과적인지를 보여주며 CDA 전용 차원 및 지표에 대해 교육합니다. CDA를 사용하는 보고서 세트가 필요합니다. 자세한 [내용은 장치 간](https://docs.adobe.com/content/help/en/analytics/components/cda/cda-setup.html) 분석 설정을 참조하십시오.
* **** 비공개 그래프를 사용하는 조직의 CDA 스티칭 지연은 하루로 줄어듭니다.Private Graph 기능이 향상되어 주별 일괄 처리에서 매일 새로 고쳐진 그래프로 그래프 생성 지연을 줄여 CDA 고객이 최신 ID 그래프와 링크에 더 액세스할 수 있습니다.
* **** Labs(기술 미리 보기):이 새로운 Analytics 기능을 사용하면 프로덕션에서 새로운 기능 프로토타입을 테스트하고 Adobe에 중요한 피드백을 제공할 수 있습니다. [추가 정보...](https://docs.adobe.com/content/help/en/analytics/analyze/tech-previews/overview.html)
* **작업 영역의 새로운 핫키:**<ul><li>모든 패널 축소/확장: `alt + m`</li><li>활성 패널 축소/확장: `alt + ctrl + m`</li><li>왼쪽 레일 검색: `ctrl + /`</li><li>다음 패널로 이동: `alt + Right Key`</li><li>이전 패널로 이동: `alt + Left Key`</li></ul>[추가 정보...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/fa-shortcut-keys.html)
* **기타 작업 영역 개선 사항:**<ul><li>패널이나 시각화가 작업 [!UICONTROL 영역으로]드롭되면 왼쪽 레일은 구성 요소로 자동 전환되므로 보다 매끄러운 작업 과정이 가능합니다.</li><li>이제 템플릿 구성 요소에 액세스할 수 있습니다(예: 태그, 즐겨찾기로 표시, 승인됨).</li><li>필터링된 지표 및 세그먼트 목록은 필요한 항목을 찾지 못할 경우 새 구성 요소를 추가하기 위한 `+` 단추를 제공합니다.</li></ul>
* 작업 **공간 디버거가** 도움말 메뉴에 추가되어 작업 공간 요청 디버깅에 보다 매끄럽게 사용할 수 있습니다. [추가 정보...](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/reporting-tricks.md)
* **** Chromium 기반 Microsoft Edge 브라우저:이 릴리스에는 보고를 위해 Chromium 기반 Microsoft Edge 브라우저(버전 79 이상)를 인식하기 위한 변경 사항이 포함되어 있습니다.

#### 수정 사항

* 실제로는 그렇지 않을 때 마케팅 채널 [!UICONTROL 차원이 데이터 웨어하우스와] 호환된다는 세그먼트 [!UICONTROL UI의]문제를 해결했습니다. 앞으로 세그먼트 빌더에서 [!UICONTROL 이러한] 차원을 더 이상 데이터 웨어하우스 [!UICONTROL 호환으로 표시하지 않습니다] . (AN-202297)
* Analytics에서 업데이트된 게시된 세그먼트 이름이 24시간 이내에 Audience Manager에서 업데이트되지 않는 문제를 해결했습니다. (AN-199974)

### [!DNL Analytics] 관리자에 대한 중요 공지 {#aa-notices}

| 알림 | 추가한 날짜 또는 업데이트한 날짜 | 설명 |
| -----------| ---------- | ---------- |
| 새 Adobe Analytics 도메인 | 2019년 12월 18일 | `https://experience.adobe.com/analytics.`<br>** 2020년 1월 16일부터 Adobe Analytics가 새 도메인으로 이동하기 시작했습니다. **참고:이 변경 사항은 Adobe ID 또는 Enterprise ID로 Analytics에 액세스하는 모든 사용자에게 적용됩니다.<ul><li>도메인 변경으로 인해 Safari에서 Analytics를 로드할 때 쿠키 문제가 발생할 수 있습니다. Deselecting _Prevent cross-site tracking_ in the Safari Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Analytics to function on this new Adobe Experience Cloud domain. 이 경우 Safari 사용자만 영향을 받기 때문에 다른 브라우저는 문제 없이 사용할 수 있습니다.</li><li>도메인 변경으로 인해 일부 고객은 [특정 경우](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html)에 [!UICONTROL Activity Map]이 중단될 수 있습니다.</li></ul> |
| 수명 종료 - Analytics 이전 API | 2020년 1월 9일 | 2020년 11월에 다음 Analytics 이전 API 서비스가 종료됩니다. 이러한 서비스를 사용하여 구축된 현재의 통합 기능은 작동하지 않습니다. <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>이전 OAuth 인증(OAuth 및 JWT)</li></ul>질문에 대한 답변과 진행 방법에 대한 지침을 제공하는 데 도움이 되도록 [이전 API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)를 제공했습니다. 이러한 서비스를 사용하는 API 통합은 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 또는 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)로 마이그레이션할 수 있습니다. 이전 OAuth 계정은 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 통합 계정으로 마이그레이션할 수 있으며, 이 계정은 1.4 Analytics API 및 2.0 Analytics API에 모두 액세스하는 데 사용할 수 있습니다. |
| **[!UICONTROL 아카이브 보기]** 옵션 EOL | 2019년 10월 30일 | 대시보드 관리자(**[!UICONTROL 구성 요소 > 대시보드]**)에 있는 **[!UICONTROL 아카이브 보기]** 옵션의 종료 날짜를 2020년 1월로 발표합니다. |
| **[!UICONTROL IP 로그인 제한 적용]** 옵션 EOL | 2019년 10월 30일 | **[!UICONTROL 관리자 > 회사 설정 > 보안]** 메뉴에서 IP 로그인 허용 목록(**[!UICONTROL IP 로그인 제한 적용]**) 기능에 대한 종료 날짜를 2020년 1월로 발표합니다. |
| TLS 1.1 지원 종료 | 2019년 10월 3일 | 2020년 3월 31일까지 Adobe Analytics는 TLS 1.1에 대한 지원을 제거합니다. 이러한 변경은 최고 수준의 보안 표준을 유지하고 고객 데이터의 보안을 향상시키기 위한 지속적인 노력의 일환입니다. |
| 런던 및 싱가포르의 산호세 FTP Broker 종료 | 2020년 7월 | 런던 및 싱가포르의 고객을 위해 런던 또는 싱가포르와 산호세 데이터 센터 간의 데이터 브로커링을 더 이상 지원하지 않습니다[ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>런던의 경우 [ftp3.omniture.com](ftp://ftp3.omniture.com/) 사용</li><li>싱가포르의 경우 [ftp4.omniture.com](ftp://ftp4.omniture.com/) 사용</li></ul> |
| Analytics 사용자의 `createDate` 필드 관련 향후 변경 사항 | 2019년 8월 30일 | 2019년 10월 또는 11월에 Analytics 사용자의 `createDate` 필드가 미국 태평양 표준시에서 시간대 정보가 있는 올바른 형식의 날짜 및 시간 값으로 업데이트되었습니다.(AN-183468) |

### [!DNL AppMeasurement] {#appm}

[JavaScript 릴리스 노트의 AppMeasurement](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html)를 참조하십시오. 버전 2.18.0은 2020년 2월 13일에 릴리스되었습니다.

## Audience Manager {#aam}

Audience Manager에 수정 사항 및 기능이 추가되었습니다.

### Audience Manager의 새로운 기능, 개선 사항 및 수정 사항 {#aam-features}

| 기능 | 설명 |
|----|----|
| [활동 사용량 보고](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/administration/activity-usage-reporting.html) | 활동 [!UICONTROL 사용량 보고서는] Audience Manager 인스턴스의 활동 사용량을 보고 추적하는 데 도움이 되며, 계약 약정과 활동 사용량이 어떻게 다른지 명확하게 파악할 수 있습니다. |

<!-- ### Fixes and Improvements {#aam-fixes-and-improvements}

* Fixes
* Fixes -->

## Experience Manager {#aem}

Adobe Experience Manager(AEM)의 새로운 기능, 수정 내용 및 업데이트. 안정성, 보안 및 성능 향상을 위해 최신 패치를 배포하려는 경우 온-프레미스 배포를 사용하는 것이 좋습니다.

### 제품 릴리스

* **Cloud Manager 2020.2.0**

   Cloud Manager 2020.2.0을 사용하면 클라우드 서비스로서 Adobe Experience Manager의 샌드박스 셀프 서비스 관리를 간소화할 수 있습니다.

   [릴리스 노트](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)를 참조하십시오.

### 사용자 도움말

* **클라우드 서비스로서의 AEM에 대한 자습서**

   클라우드 서비스로 AEM에 대한 [자습서를 빠르게 시작할 수 있습니다](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/overview.html).

* **AEM Forms 대화형 통신 배치 API**

   AEM Forms 인터랙티브한 커뮤니케이션의 일괄 처리 API를 통해 고객은 자동으로 또는 On-Demand 방식으로 다양한 인터랙티브한 커뮤니케이션을 제작할 수 있습니다. 고객은 인쇄 및 웹 출력을 동시에 생성할 수 있습니다.
배치 [API를 사용하여 여러 대화형 통신 생성을 참조하십시오](https://docs.adobe.com/content/help/en/experience-manager-65/forms/interactive-communications/generate-multiple-interactive-communication-using-batch-api.html).

* **JEE에서 지원되는 AEM Forms 플랫폼**

   JEE 고객의 AEM Forms에 대한 Oracle 19c 지원이 추가되었습니다.
JEE [에서 AEM Forms에 대해 지원되는 플랫폼을 참조하십시오](https://docs.adobe.com/content/help/en/experience-manager-65/forms/install-aem-forms/jee-installation/aem-forms-jee-supported-platforms.html).

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

### Campaign Classic 19.2.3

수정 사항 및 향상된 기능은 [Adobe Campaign Classic 릴리스 노트](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html)를 참조하십시오.

### Campaign Standard 20.1

수정 사항 및 향상된 기능은 [Adobe Campaign Standard 릴리스 노트](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)를 참조하십시오.

### 추가 리소스

* Adobe Campaign Standard: [설명서](https://helpx.adobe.com/support/campaign/standard.html) - [릴리스 노트](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [기능 비디오](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [릴리스 계획](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [설명서](https://helpx.adobe.com/support/campaign/classic.html) - [릴리스 노트](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [기능 비디오](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign 제어판: [설명서](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [릴리스 노트](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

2020년 2월 10일 업데이트(2월 8일 릴리스)

| 보기 | 기능 |
|------|---------|
| 포트폴리오 | 이제 Yahoo! YDN(Japan Display Network) 캠페인을 포트폴리오로 전환하여 캠페인 예산 및 광고 그룹 수준 입찰을 최적화합니다. 동일한 입찰이 광고 그룹의 모든 광고에 적용됩니다. YDN 캠페인에 대한 데이터는 포트폴리오의 시뮬레이션에 포함됩니다. |
| 검색 > 일괄 시트 | 이제 일괄 시트를 사용하여 Google RSA(Responsive Search Ads)를 생성, 편집 및 삭제할 수 있습니다. 이전에는 검색 > 캠페인의 표준 캠페인 관리 인터페이스를 통해서만 지원을 **[!UICONTROL 사용할]** 수 **[!UICONTROL 있었습니다]** |
| 검색 > 캠페인, 보고서 | Google Ads `Impr. (Abs. Top) %` 의 주요 지표 및 `Impr. (Top) %` 이제 쇼핑 제품 그룹, 캠페인 일일 노출 공유 및 키워드 일별 노출 [!UICONTROL 공유] 보고서, 레이블 및 제약 조건 보기에서만 모든 기본 보고서 및 엔티티 수준 캠페인 관리 [!UICONTROL 보기에서 사용할 수] 있습니다. |

## [!DNL Magento] {#magento}

Magento 릴리스 노트에 대해서는 다음을 참조하십시오.

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)
