---
title: Adobe Experience Cloud 릴리스 노트
description: 2019 년 6 월 Experience Cloud 릴리스 노트
doc-type: 릴리스 노트
last-update: 2019 년 6 월
author: mfrei
translation-type: tm+mt
source-git-commit: 1f156e4fcbd0d39b27f2c254e2117ad2e4e0b793

---


# 조기 사용 - Adobe Experience Cloud 릴리스 노트

Adobe Experience Cloud의 새로운 기능 및 수정 사항.

>[!IMPORTANT]
>이 페이지에는 출시 전 컨텐츠가 포함되어 있으며 계획된 출시 전에 변경될 수 있습니다.

>[!NOTE]
>예정된 릴리스에 대한 이메일 알림을 받으려면 [Adobe 우선 제품 업데이트](https://www.adobe.com/subscription/priority-product-update.html)에 가입하십시오. 업무일 기준으로 릴리스 3-5일 전에 공지를 받게 됩니다. 릴리스 후 게시된 새 정보는 발행 날짜로 표시됩니다.

**릴리스 날짜: 2019 년 6 월**

* [Adobe Experience Platform](#platform)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [캠페인](#ac)
* [Mobile Services](#mobile)
* [Advertising Cloud](#adcloud)
* [Target Standard/Premium 19.6.1](#target)
* [Magento](#magento)
* [Primetime](#primetime)

## Adobe Experience Platform {#platform}

### Adobe Experience Platform 릴리스 노트

* 경험 플랫폼에 대한 최신 업데이트를 보려면 Adobe. io에서 [Experience Platform 릴리스 노트를](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes-20190515.md) 참조하십시오.

### Experience Platform Launch

* 최신 정보는 [Experience Platform Launch](https://docs.adobelaunch.com/) 를 참조하십시오.

## Analytics {#analytics}

Adobe Analytics의 새로운 기능 및 수정 내용:

* [Adobe Analytics의 새로운 기능 및 수정 내용](#aa-features)
* [Analytics 관리자에 대한 중요 공지](#aa-notices)

제품 설명서의 경우 [Analytics 도움말 홈](https://marketing.adobe.com/resources/help/en_US/reference/)을 참조하십시오.

### Adobe Analytics의 새로운 기능 및 수정 내용 {#aa-features}

| 기능 | 설명 |
| -----------| ---------- |  
| **세그먼테이션** | 세그멘테이션의 차원 새로운 기여도 모델:<ul><li>반복 (기본값): 차원에 대한 인스턴스 + 지속적인 값을 포함합니다.</li><li>instance: 차원에 대한 인스턴스를 포함합니다.</li><li>반복되지 않는 인스턴스: 차원에 대한 고유 인스턴스 (반복되지 않음) 를 포함합니다.</li></ul> |
| **세그먼테이션** | 새 세그먼트 연산자: **[!UICONTROL 와 같으며 같지]** **[!UICONTROL 않습니다]**. |
| **디버거** | Adobe ID로 로그인하면 이제 Experience Cloud 디버거에서 처리된 히트를 검색할 수 있는 옵션이 제공됩니다. 처리 후 히트는 [!UICONTROL 처리 규칙] 및 VISTA 규칙을 거친 후 서버 호출로서 [!UICONTROL 처리 규칙] 및 VISTA 규칙의 유효성을 확인할 수 있습니다. **** 참고: A 4 T (보충 지원) 를 사용하는 경우 후처리 데이터가 돌아오는 데 몇 분 정도 걸릴 수 있습니다. |
| **Analysis Workspace:** | 왼쪽 레일 검색에 즉시 새로운 필터가 추가되었습니다. 현재 보이는 항목 (차원, 지표, 승인됨 등), 계산된 지표, 고객 속성, Evar, prop, 비디오 등의 새로운 필터 가 추가되었습니다. |

**Analysis Workspace 공간 수정 사항**

* 시각화의 현지화 일본어 날짜 관련 문제를 [!DNL Analysis Workspace] 해결했습니다. (AN-180114)
* 차원 항목을 복사하여 붙여넣은 후 발생하는 문제를 수정했습니다. 이후에 항목을 검색하면 오류가 발생했습니다. (AN-177394)
* 자유 형식 테이블 내의 세그먼트 패널에 편집 옵션이 누락되는 문제가 해결되었습니다. (AN-171703)
* 대규모 수신자와 **[!UICONTROL 공유할 때 랜딩 페이지]** 기능이 작동하지 않던 문제가 해결되었습니다. (AN-163922)
* 문자열이 실시간 보고서에서 세로로 잘렸던 문제를 수정했습니다. (AN-175980)

**기타 Analytics 수정 사항**

* 관리 사용자가 성공 이벤트를 활성화할 **[!UICONTROL 수]** 없는 문제를 해결했습니다. (AN-176689)
* **[!UICONTROL 종료 비율]** 지표로 경고를 만들 때 발생하던 문제를 수정했습니다. (AN-177476)

### Analytics 관리자에 대한 중요 공지 {#aa-notices}

| 알림 | 추가한 날짜 업데이트한 날짜 | 설명 |
| -----------| ---------- | ---------- |
| 분류 규칙 빌더 제한 | 2019 년 6 월 5 일에 추가된 날짜 | 이러한 제한 사항은 새로운 것이 아니지만 여기에 설명서가 [추가되었습니다](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html). |
| 새 세그먼트 연산자 제한 | 2019 년 5 월 31 일에 추가된 날짜 | 2019 년 7 월 18 일부터, 세그먼트 연산자에 &quot;contains any of&quot;, &quot;contains any of&quot;, &quot;contains all of&quot; 및 &quot;does not contain all of words are limited to 100 words per input field. 이 날짜 이후로 모든 신규 세그먼트와 수정된 세그먼트에 한도가 적용됩니다. 한계를 초과하는 기존 세그먼트는 계속 지원되지만 입력 필드가 감소될 때까지 수정하거나 저장할 수 없습니다. 이러한 제한은 쿼리 성능을 향상시키기 위한 지속적인 노력의 일환으로 적용됩니다. |
| **[!UICONTROL Date-Enabled]** 및 **[!UICONTROL Numeric 2 분류에 대한 향후 지원 변경 사항]** | 업데이트 날짜: 2019년 5월 28일 | 숫자 2와 활성화된 날짜 분류를 가져오는 기능이 코드 베이스에서 제거되었습니다. 이 변경 사항은 2019 년 7 월 유지관리 릴리스에서 적용됩니다. 가져온 파일에 숫자 또는 활성화된 날짜 열이 있는 경우 해당 셀은 자동으로 무시되며, 해당 파일의 다른 모든 데이터는 정상적으로 가져와집니다. <br/>기존 분류는 여전히 표준 분류 워크플로우를 통해 내보낼 수 있으며, 보고에서 계속 사용할 수 있습니다. |
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

**수정 사항, 개선 사항 및 중단 사항**

* 이제 Audience Manager는 사용 제한에 대해 활성 알고리즘 모델을 카운트합니다.
* 해당 모델을 사용하는 트레이트에 알고리즘 모델 도달이 표시되지 않는 문제를 해결했습니다.
* 트레이트 폴더 컨텐츠를 표시하지 않고 폴더 이름에 대괄호가 포함된 문제를 해결했습니다.
* 특성 유형을 하나만 선택할 때 트레이트 정렬이 실패하는 문제를 해결했습니다.
* 트레이트 폴더 트리가 새 하위 폴더를 만들거나 업데이트할 [!UICONTROL 때마다 모든 특성] 보기로 축소되는 문제를 해결했습니다.
* 파트너 삭제를 시도할 때 view_ Datasources 권한이 필요한 문제를 해결했습니다.
* 세그먼트 페이지의 [!UICONTROL 검색] 상자가 선택된 [!UICONTROL 폴더 대신] 모든 폴더에서 검색되는 문제를 해결했습니다.
* 새로운 알고리즘 모델을 만들 때 헤더 컨트롤을 통해 트레이트 [!UICONTROL 제외] 테이블을 정렬하는 문제를 해결했습니다.
* 빈 간격 날짜가 있는 보고서를 실행할 때 Audience Manager가 충돌하는 문제를 해결했습니다.

## Experience Manager {#aem}

Adobe Experience Manager(AEM)의 새로운 기능, 수정 내용 및 업데이트. 안정성, 보안 및 성능 향상을 위해 최신 패치를 배포하려는 경우 온-프레미스 배포를 사용하는 것이 좋습니다.

### 제품 릴리스

**Cloud Manager 2019.5.0**

최신 Cloud Manager 릴리스 (2019.5.0) 는 몇 가지 버그 수정 사항을 제공하긴 하지만 상당한 기능 변경 사항을 포함하지 않습니다.

* [Cloud Manager 2019.5.0 릴리스 노트](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

**AEM용 XML 설명서**

XML 설명서 솔루션에 대한 3.3 릴리스를 현재 사용할 수 있습니다. 다음 릴리스 노트를 참조하십시오.

***고급 맵 기능***
* 저장소 보기에서 드래그하여 놓거나 가로 막대형 및 요소 카탈로그를 사용하여 주제 참조를 추가합니다.
* nav title, chunk, like nav 제목, 형식, 범위 등에 메타데이터를 추가합니다.
* 주제 참조를 클릭하면 편집기에서 주제가 열립니다 (체크아웃되지 않은 경우 미리 보기 모드 사용 및 체크아웃으로 편집을 비활성화함 사용).
* 토픽 헤드 및 토픽 그룹을 추가합니다.
* frontmatter (주제, 서체, 책 목록, 고지 사항 등) 와 배경 (주제, 부록, 용어집 등) 로 책맵을 추가합니다.
* 작성 모드에서는 끊어진 링크가 강조 표시되고, 탐색 표시가 표시되고, 전체 태그 보기가 사용할 수 있습니다.
* 맵 수준 속성을 설정하는 기능.
* 제목/책갈피 설정 기능.
* Rel 헤더 추가, 열, 맵에서 항목 드래그/드롭 항목을 Rel 테이블로 드래그, 링크, 범위 및 기타 링크에 대한 기타 매개 변수를 설정하는 기능을 사용하여 reltables에 대한 지원을 셀 내에서 재정렬합니다.
* 이전에 삽입할 도구 모음 widget, 뒤에 삽입 및 요소 삽입.
* 조건이 항목에 적용되는 경우 강조 표시됩니다.
* 한 번에 여러 맵을 편집할 수 있습니다 (각 맵은 동일한 브라우저에서 탭으로 열림).
* 맵 패널 및 저장소 보기에서 마우스를 놓을 때 전체 토픽 제목과 파일 이름을 표시합니다.

***전체 태그 보기***

* 두 요소 사이에 새 태그를 삽입합니다.
* 태그를 복사하여 붙여넣습니다.
* 허용되는 위치에 태그를 드래그하여 놓고 파일 내에서 삽입할 수 없습니다.
* 태그를 확장하거나 축소합니다.

***향상된 DITA 별 검색 기능***

* 선택한 컨텐츠를 다시 색인화하는 일련화 도구를 제공했습니다.
* 사용자가 사용하고 `contains``exact match` 검색할 수 있습니다. 또한 다음 매개 변수를 사용하여 검색할 수도 있습니다. :
   * 자산 메타데이터를 참조하십시오. 예: `file name`, `title`또는 고객이 정의한 사용자 지정 메타데이터.
   * DITA 속성 이름 및 값. 예, `platform=winOS`.
   * DITA 요소 이름 및 해당 값. 예, `author = Joe Smith`.
   * DITA 요소 이름 및 적용된 속성. 예를 들어 product = spacebase 속성 이름/값 쌍이 적용된 표가 여기에 적용됩니다.
   * DITA 주제 및 맵 메타데이터.
   * DITA 정보 유형. For exam [ple, map, topic, concept.
   * 루트 폴더 경로를 참조하십시오.
   * 문서 상태.
   * 체크아웃 상태.
   * 날짜 범위를 수정했습니다.
   * CQ 태그.
* 위의 검색 매개 변수 중 하나 이상을 결합하여 복잡한 쿼리를 만들 수 있습니다.

***검토 기능 변경 사항***

* 검토자용 팁:
   * 3.3 빌드로 업그레이드하기 전에 모든 주석을 가져와 진행 중인 검토에 대한 변경 사항을 통합할 수 있습니다.
   * 편집기에 대해 여러 탭이 열려 있지 않은지 확인합니다.
   * 전체 태그 보기가 활성화되어 있지 않은지 확인합니다.
   * 검토 진행 중에 작성자 모드와 소스 모드 간을 전환하지 마십시오.
* 검토할 내 컨텐트의 버전을 지정하는 기능
* 기준선, 날짜, 레이블 또는 현재 활성 버전을 기반으로 선택한 항목 버전을 선택하거나, 검토를 만드는 동안 각 주제에 대한 버전을 지정할 수 있습니다.
* 검토용 주제/맵을 여러 번 보내고 작성자는 편집기의 검토 패널에 있는 모든 검토 작업에 액세스할 수 있습니다.
* 개시자는 검토자에 대해 최신 버전의 콘텐트를 푸시할 수 있습니다. 검토자는 새 컨텐츠를 검토할 때 알림을 받게 됩니다.
* 작성자는 편집기의 검토 패널에서 모든 버전의 컨텐츠에 대한 검토 주석을 볼 수 있습니다. 작성자는 버전 번호별로 주석을 필터링할 수 있습니다.
* 작성자 사용자는 검토 중이었던 편집기에서 이전 버전의 컨텐츠에서 주석을 보고 가져올 수 있습니다.

***기타***

* 저장소 보기에서 새 폴더, 주제 또는 맵을 만듭니다.
* 자산 UI에서 보기 - &quot;자산 UI에서 보기&quot; 와 폴더 및 주제 모두에 대한 메뉴 옵션을 추가합니다. 이 옵션은 자산 UI를 엽니다. 여기서 사용자는 왼쪽의 컨텐츠 트리를 보고 맨 위에는 모든 자산 메뉴가 있는 모든 파일이 표시됩니다.
* 검토 대시보드는 이제 검토 수준 및 검토 작업 수준에서 검토를 추적하는 타일로 DITA 프로젝트에 사용할 수 있습니다.
* IDML를 DITA로 변환하는 기능이 추가되었습니다.
* 지정된 모든 버전에 지정된 레이블을 적용하려면 API를 제공합니다.
* XHTML/DOCX에서 DITA 로의 변환이 완료된 후 이벤트를 활성화합니다. 이 이벤트를 사용하여 변환된 컨텐츠 또는 구현해야 하는 기타 모든 사용자 지정 논리에 특수 속성을 추가할 수 있습니다.
* 기본 성능 탭 기능이 개선되었습니다. 사용자는 먼저 모든 기존 기준선에서 스크립트를 실행해야 합니다.
* XHTML에서 DITA 로의 변환이 향상되었습니다.
* 게시 최적화를 위한 DITA-OT 오프로드.
* 목록 보기의 유형 열에서 정렬을 수정했습니다.
* Word에서 계단식 스타일을 DITA로 변환하는 기능이 지원됩니다.

### 커뮤니티

**[Cloud Manager Skill Builder 웨비나 시리즈](https://cloudmanagerskillbuilder.experienceleague.adobeevents.com/)**

Adobe Experience Manager Management의 일상적인 활동을 간소화하는 데에도 관심이 있으십니까? 클라우드 관리자는 조직이 Devops 변환을 시작하든 기존 devops 프로세스를 강화할 전략을 모색하고 있는지 상관없이 클라우드 민첩성을 구현하는 Adobe Experience Manager의 1 세대 클라우드 기본 기능을 제공합니다.

[이번 월별 시리즈에서는](https://cloudmanagerskillbuilder.experienceleague.adobeevents.com/)Adobe 제품 팀에서 클라우드 관리자 기능을 사용하여 클라우드에서 Adobe Experience Manager 관리를 간소화하는 방법에 대해 직접 배울 수 있습니다.

다음을 학습합니다.
* 클라우드 관리자를 시작하는 방법 및 CI/CD 파이프라인 설정 방법
* 자동 크기 조절 및 투명한 서비스 제공 방식을 사용하고 클라우드에서 Adobe Experience Manager 환경 관리를 간소화할 수 있는 방법
* 클라우드 관리자 API를 사용하고 기존의 devops 프로세스를 통합하는 방법

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

### Campaign Classic 19.1 봄 릴리스

| 기능 | 설명 |
| ------------- | ----------- |
| 제어판 | 관리자 사용자로 작업의 효율성을 높이려면 저장소 모니터링, IP 주소 허용 및 각 인스턴스에 대한 SSH 키 설치를 통해 SFTP 서버의 설정을 관리합니다. 참고 패널은 오늘부터 AWS를 통해 호스팅되는 고객에게만 제공됩니다. [Experience Cloud를 통해 로그인합니다](https://experiencecloud.adobe.com/campaign/controlpanel/). <br> 자세한 내용은 [자세한 설명서](https://helpx.adobe.com/campaign/kb/control-panel.html) 및 [사용 방법 비디오를](https://helpx.adobe.com/campaign/kt/acc/using/acc-control-panel-video-use.html)참조하십시오. |
| 감사 추적 | 관리자는 Adobe Campaign Classic 인스턴스 내에서 수행한 변경 사항을 모니터링하고 관리하여 생산성을 높입니다. 감사 추적은 소스 스키마, 워크플로우 및 옵션에서 수행한 작업을 기록합니다. 요소를 생성, 수정 또는 삭제했는지 여부를 빠르게 확인할 수 있습니다.<br>자세한 내용은 [자세한 설명서](https://docs.campaign.adobe.com/doc/AC/en/PRO_Production_procedures_Audit_trail.html) 및 [사용 방법 비디오를](https://helpx.adobe.com/campaign/kt/acc/using/acc-audit-trail-feature-video-use.html)참조하십시오. |
| Guardrail, Robustness 및 Scalability | 일련의 향상된 기능이 Campaign Classic에 추가되었습니다. 캠페인 Classic 릴리스 노트에 Guardrail, Robustness 및 [확장 기능이 개선되었습니다](https://docs.campaign.adobe.com/doc/AC/en/RN.html). |
| 보안 SMS 메시징 (TLS) | 보안 SMS는 이제 확장된 일반 SMPP 커넥터를 통해 지원됩니다. 이를 통해 공급자에 암호화된 연결을 허용할 수 있습니다. <br>[ 자세한 내용은 상세 문서를 참조하십시오](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html). |
| 호환성 매트릭스 업데이트 | 이 새 버전에서는 Adobe Campaign 이 이제 다음의 데이터베이스 시스템을 지원합니다. [호환성 표 참조](https://helpx.adobe.com/campaign/kb/compatibility-matrix.html) <ul><li>Oracle 18 c</li><li>MySQL 5.7 (FDA)</li><li>SQL Server 2017</li><li>Teradata 16 (FDA)</li><li>Postgresql 11</li></ul> |

수정 사항 및 개선 사항은 [Adobe Campaign Classic 릴리스 노트](http://docs.campaign.adobe.com/doc/AC/en/RN.html)를 참조하십시오.

### Campaign Standard 19.2 봄 릴리스

| 기능 | 설명 |
| ------------- | ----------- |
| 제어판 | 관리 사용자로 작업의 효율성을 높이려면 인스턴스의 용량을 쉽게 모니터링하고 인스턴스의 설정을 관리할 수 있습니다 (SFTP 서버 관리 시작). <br> 자세한 내용은 [자세한 설명서](https://helpx.adobe.com/campaign/kb/control-panel.html) 및 [사용 방법 비디오를](https://helpx.adobe.com/campaign/kt/acs/using/acs-control-panel-video-use.html)참조하십시오. |
| 로컬 알림 | 로컬 알림 메시지를 사용하면 인터넷 또는 전경의 모바일 애플리케이션에 액세스하지 않고도 모바일 애플리케이션에서 새로운 데이터를 사용할 수 있게 되면 사용자에게 알릴 수 있습니다. 로컬 알림은 특정 시간 및 이벤트에 따라 모바일 응용 프로그램에서 트리거됩니다.<br>[자세한 내용은 상세 문서를 참조하십시오](https://helpx.adobe.com/campaign/standard/channels/using/customizing-an-in-app-message.html#customizing-a-local-notification-message-type). |
| 향상된 워크플로우 - 외부 신호 활동에 페이로드를 추가할 수 있습니다. | 다른 워크플로우나 REST API 호출에서 정의된 조건이 성공적으로 충족되면 페이로드를 사용하여 워크플로우를 시작하여 외부 시스템과 통합합니다. 여기에는 이 기능에 대한 테스트를 실행할 수 있는 새 테스트 활동이 포함되어 있습니다. <br>자세한 내용은 [자세한 설명서](https://helpx.adobe.com/campaign/standard/channels/using/customizing-an-in-app-message.html#customizing-a-local-notification-message-type) 및 [사용 방법 비디오를](https://helpx.adobe.com/campaign/kt/acs/using/acs-external-signal-activity-feature-video-use.html)참조하십시오. |
| 랜딩 페이지 개선 - Google recaptcha | Google recaptcha를 활용하면 고객의 행동 없이 랜딩 페이지에서 스팸을 방지할 수 있습니다. <br>[자세한 내용은 상세 문서를 참조하십시오](https://helpx.adobe.com/campaign/standard/channels/using/designing-a-landing-page.html#setting-google-recaptcha). |

제품 설명서의 경우 다음을 참조하십시오.

* Adobe Campaign Standard: [설명서](https://helpx.adobe.com/support/campaign/standard.html) - [ 릴리스 노트](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [ 기능 비디오](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [설명서](https://helpx.adobe.com/support/campaign/classic.html) - [릴리스 노트](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [ 기능 비디오](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Mobile Services {#mobile}

* 모든 Adobe 서버에서 TLS 1.0 이 비활성화되었습니다. SSL를 통해 Adobe 서비스에 연결할 Android 4. x 장치의 경우, SDK가 핸드셰이크를 설정할 때 TLS 1.1/TLS 1.2가 강제로 적용됩니다.

## Advertising Cloud {#adcloud}

업데이트 날짜: 2019년 5월 6일, 6월 8일 릴리스

| 제품 | 기능 | 설명 |
| -----------| ---------- | ----------  |
| 캠페인 검색, 레이블 분류 및 제한 | 키보드 단축키 | <b>이제 Shift 키를 누른 상태로 여러</b> 개의 연속 행을 선택할 <b>수 있으며 연속되지</b> 않은 여러 행을 선택할 수 있습니다. |
|  | 페이지 모두를 선택하고 모두를 선택합니다. | 데이터 테이블에서 맨 위 확인란을 선택하여 모든 행을 선택하는 경우 새 기본값은 페이지에서 모든 행을 선택하는 것입니다 (25 행, 50 행, 100 행, 200 행 또는 연속 스크롤 기준). 사용할 수 있는 모든 행을 선택할 수 있는 옵션이 있습니다. |
| 기본 보기, 사용자 정의 보기 및 독립형 열 사용자 정의 설정 | 열 순서 다시 지정 | 새로운 위쪽 및 아래쪽 단추를 사용하여 열 순서를 변경할 수 있습니다. 이전 경우처럼 열을 드래그하여 놓아 순서를 변경할 수 있습니다. |

## Target Standard/Premium 19.6.1(2019년 6월 25일) {#target}

최신 릴리스 정보에 대해서는 Adobe Target 릴리스 노트를 참조하십시오.

[Target 릴리스 노트(사전 릴리스)](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)

[Target 릴리스 노트(현재)](https://docs.adobe.com/content/help/en/target/using/release-notes/release-notes.html)

## Magento {#magento}

Magento는 유연한 쇼핑 카트 시스템과 해당 온라인 스토어의 외관, 컨텐츠 및 기능을 제어하는 기능과 함께 온라인 가맹점을 제공하는 전자 상거래 플랫폼입니다. Magento는 오픈 소스 버전 및 전체 기능 상거래 버전으로 사용할 수 있습니다.

Magento Commerce는 Adobe Commerce Cloud의 일부이며, B2C 및 B2B 환경을 위한 엔터프라이즈 등급의 무제한 확장 가능성과 오픈 소스 유연성이 포함된 전자 상거래 솔루션을 제공합니다.에서 보냅니다.

오픈 소스 및 커머스 에디션에 대한 릴리스 노트는 [릴리스 정보](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html) 페이지에서 확인할 수 있습니다.

## Primetime {#primetime}

Adobe Primetime은 미디어 회사가 개인화된 시청 환경을 제공하며 수익을 창출할 수 있도록 도와주는 멀티스크린 TV 플랫폼입니다.

[Primetime 릴리스 노트](http://help.adobe.com/en_US/primetime/release_notes/index.html)
[Primetime 도움말 홈](http://help.adobe.com/en_US/primetime/)
