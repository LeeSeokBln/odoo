# 🚲 실습 사례: City Bike

이제 실습할 시간입니다!

아래에서 여러분이 준비해야 할 실습 사례를 확인할 수 있습니다.

시작하려면 [새 데이터베이스를 생성](https://www.youtube.com/watch?v=XxsHacB4VeE\&utm_source=chatgpt.com)하고, 고객에게 첫 번째 \*\*MVP(최소 기능 제품)\*\*를 시연할 수 있도록 설정하세요.

이번 데모에서는 다음 앱에 중점을 두어야 합니다.

CRM

고객 관계 관리

판매

Sales

청구서

Invoicing

다만 고객의 모든 요구사항을 충족하려면 다른 앱도 추가로 사용해야 할 수 있습니다.

## 안녕하세요, 저는 디미트라(Dimitra)입니다!

저는 1년 전 CityBike를 설립했습니다.

현재 저희 회사에는 영업사원 3명, 생산 담당 직원 4명, 회계 담당자 1명을 포함하여 총 10명의 직원이 근무하고 있습니다.

저희 회사는 벨기에에 있으며, 직원 중 한 명은 스페인어만 구사할 수 있습니다.

저희는 맞춤형 전기자전거를 재판매하는 전문 업체로, [총 5가지 모델](https://docs.google.com/document/d/1Eba3LSPOrslFCYk22RUKvQCc0lxpTjWafhHLFz3_kXQ/edit?tab=t.0\&utm_source=chatgpt.com)을 판매하고 있습니다.

각 자전거는 고유한 디자인을 가지고 있지만, 공통된 자재를 사용합니다.

자전거 외에도 앞바구니, 자전거 헬멧, 휴대폰 거치대, 장갑, 전조등, 후미등 등 다양한 액세서리를 판매합니다.

현재 저희는 QuickBooks와 Google Suite(스프레드시트)를 사용하여 회사 업무를 관리하고 있습니다.

[E-Bike Testsieger: Welche Marken haben die Nase vorn?](https://images.openai.com/static-rsc-4/Z1_dh3bdUbkNP9HloFJkhXnQgWBQogsTrk4oNMvuyFvae6jsU9z_xVaR5cxDFsg-QSBGeS8Ul_CiYMAPoFOJszdcJ2HLB9OdsvdsnJ2bQK91SGnmWutywKxwRlXASgx1_P9ZPgrMQMVjRJwyZOWZmXsoAYevx3ODm-mmqPzmYp0?purpose=inline)

## 1. 영업 기회 관리 (Handling Opportunities)

저희에게는 잠재 고객에게 적극적으로 연락하는 [영업팀](https://www.youtube.com/watch?v=27UYtZJ9HKI\&utm_source=chatgpt.com)이 있습니다.

잠재 고객은 전화, [이메일](https://www.odoo.com/ko_KR/documentation/13.0/applications/sales/crm/acquire_leads/generate_from_email.html?utm_source=chatgpt.com), 또는 [회사 웹사이트](https://www.odoo.com/ko_KR/documentation/13.0/applications/sales/crm/acquire_leads/generate_from_website.html?utm_source=chatgpt.com)의 문의 양식을 통해 저희에게 연락할 수 있습니다.

잠재 고객과 접촉한 후에는 영업팀이 고객의 구매 가능성을 평가하고, [견적서](https://www.odoo.com/ko_KR/slides/slide/your-first-quotation-7405?fullscreen=1\&utm_source=chatgpt.com)를 발송하며, 가격을 협상합니다.

또한 저희 회사에는 지역 기업을 대상으로 콜드콜(사전 접촉 없이 진행하는 영업 전화)을 담당하는 인턴이 한 명 있습니다.

이 인턴은 자신이 CRM에 업로드한 잠재 고객 목록에만 접근할 수 있어야 하며, 그 외의 정보에는 접근할 수 없어야 합니다.

이를 위해 적절한 [접근 권한](https://www.odoo.com/ko_KR/documentation/18.0/applications/general/users/access_rights.html?highlight=access+rights\&utm_source=chatgpt.com) 설정이 필요합니다.

## 2. 판매 관리 (Managing Sales)

저희 회사의 [가격 정책](https://www.odoo.com/ko_KR/slides/slide/pricelists-multiple-prices-per-product-615?fullscreen=1\&utm_source=chatgpt.com)은 복잡하며, 다음과 같은 여러 요소에 따라 달라집니다.

- 고객 유형
- 선택한 제품
- 연중 시기

특히 7월과 12월에는 제품 가격이 10% 인상됩니다.

저는 견적서가 명확하고 시각적으로 보기 좋았으면 합니다.

일반적으로 견적 이메일을 보낼 때 각 자전거의 기술 사양서를 첨부하고 있습니다.

그런데 이 작업에 시간이 너무 많이 소요됩니다.

[기술 사양서 첨부 작업을 자동화할 수 있을까요?](https://www.odoo.com/ko_KR/slides/slide/product-documents-9175?utm_source=chatgpt.com)

또한 견적서에서 저희가 판매하는 두 가지 제품 유형을 명확하게 구분하는 것도 중요합니다.

- 자전거(Bikes)
- 액세서리(Accessories)

## 3. 청구서 관리 (Invoicing)

계약이 체결되면 고객에게 청구서를 발행하고, 총금액의 50%를 계약금(선금)으로 요청합니다.

[나머지 잔금은 제품이 발송될 때 지급해야 합니다.](https://www.odoo.com/ko_KR/documentation/13.0/applications/sales/sales/invoicing/invoicing_policy.html?utm_source=chatgpt.com)

고객이 추가 제품을 요청하는 경우에는 별도의 청구서를 발행합니다.

현재 저희 영업팀은 고객의 청구서 결제 여부를 확인하고, 미납 고객에게 연락하는 데 너무 많은 시간을 소비하고 있습니다.

고객이 결제 기한을 지키지 않는 문제는 저희 회사의 주요 골칫거리입니다.

다음과 같은 알림을 발송하여 [이 과정을 자동화할 수 있을까요?](https://www.youtube.com/watch?v=50qy2ygS7eM\&utm_source=chatgpt.com)

1. 결제 기한 5일 전: 고객에게 결제 알림 이메일 자동 발송
2. 결제 기한 15일 후: 고객에게 연체료 부과 안내 자동 발송

추가로 저희는 벨기에 국내뿐 아니라 해외 기업에도 제품을 판매하고 있습니다.

해외 기업에 대한 판매는 [세금 면제 대상](https://www.odoo.com/ko_KR/documentation/18.0/applications/finance/accounting/taxes/fiscal_positions.html?utm_source=chatgpt.com)이므로, 이에 맞는 세금 처리도 필요합니다.

## 4. 보고 및 분석 (Reporting)

현재 저는 여러 플랫폼과 Excel을 번갈아 사용하느라 너무 많은 시간을 낭비하고 있습니다.

저는 회사 전체의 현황을 한눈에 파악할 수 있는 360도 통합 관리 환경을 원합니다.

또한 보고 및 분석 기능이 더욱 개선되었으면 합니다.

예를 들어, \*\*[영업사원별 월간 청구 금액](https://www.odoo.com/ko_KR/documentation/18.0/applications/essentials/reporting.html?highlight=reporting\&utm_source=chatgpt.com)\*\*을 추적하고 싶습니다.

Odoo가 이러한 요구사항을 어떻게 충족할 수 있을지 알아보는 데 큰 관심이 있습니다.

## 실습에서 구현해야 할 요구사항 요약

원문 요구사항을 실제 Odoo 데모 구현 항목으로 정리하면 다음과 같습니다.

| 구분    | 구현해야 할 기능                  |
| ----- | -------------------------- |
| 기본 설정 | 벨기에 회사, 직원 10명, 스페인어 사용자   |
| 제품    | 전기자전거 5종 및 액세서리 등록         |
| CRM   | 전화·이메일·웹사이트를 통한 잠재 고객 관리   |
| CRM   | 영업 기회 평가, 견적 발송, 가격 협상     |
| 접근 권한 | 인턴은 본인이 등록한 잠재 고객만 조회      |
| 판매    | 고객 유형·제품·시기에 따른 가격표        |
| 판매    | 7월·12월 가격 10% 인상           |
| 견적서   | 자전거 기술 사양서 자동 첨부           |
| 견적서   | 자전거와 액세서리 항목 구분            |
| 청구    | 계약 시 50% 선금 청구             |
| 청구    | 출하 시 나머지 50% 청구            |
| 청구    | 추가 제품에 대한 별도 청구서           |
| 자동화   | 만기 5일 전 결제 안내              |
| 자동화   | 만기 15일 후 연체료 안내            |
| 세금    | 해외 기업에 대한 면세 처리            |
| 보고서   | 영업사원별 월간 청구 금액 분석          |
| 통합 관리 | 회사 전체 실적을 한눈에 볼 수 있는 보고 환경 |

핵심: 이번 과제는 단순히 기능을 설명하는 것이 아니라, 새로운 Odoo 데이터베이스에 위 요구사항을 실제로 설정하고 고객에게 작동하는 MVP를 시연하는 것입니다.
