---
title: "The LockBit Takedown"
description: "Law enforcement ‘trolls’ ransomware gang"
author: bde574786
date: 2024-10-28 13:33:00 +0900
categories: [최근 보안 이슈]
tags: [빡공팟, 콘테스트 네뷸라, 최근 보안 이슈, Ransomware]
image: assets/posts/security-issue/2024-10-28/image-001.png
---

## **What is LockBit?**
**LockBit**은 **RaaS(Ransomware as a Service)**, 즉 랜섬웨어 서비스를 제공하는 업체로, 다른 해커나 범죄조직이 랜섬웨어 공격을 쉽게 할 수 있도록 플랫폼, 인프라, 도구를 제공한다. 2022년에 Conti라는 유명한 랜섬웨어 그룹이 해체된 이후, LockBit은 FIN7과 Evil Corp 같은 악명 높은 해커 집단뿐만 아니라 전 Conti 멤버들도 자신들의 서비스에 끌어들일만큼 빠르게 두각을 나타내었다. 보안 회사인 PRODAFT에 따르면, LockBit은 특히 전 Conti 멤버들을 위해 **LockBit Green**이라는 맞춤형 랜섬웨어 버전을 개발하기도 했다고 한다.

LockBit은 사업처럼 운영되며 홍보 활동도 적극적이다. 예를 들어, LockBit 로고를 몸에 문신으로 새긴 사람에게 1,000 달러를 지급하는 캠페인을 진행하기도 했고, 일반 IT 기업들처럼 자사 소프트웨어의 취약점을 찾아주는 해커들에게 보상금을 지급하는 버그 바운티 프로그램도 시작했다. LockBit의 플랫폼은 사용이 간편하고 각종 옵션을 사용자에게 맞게 쉽게 설정할 수 있는 것이 특징이다.

<br>
하지만 LockBit이 다른 RaaS 제공자와 차별화되는 가장 큰 이유는 독특한 수익 배분 방식에 있다. 보통 랜섬웨어 서비스 업체들은 피해자로부터 전체 금액을 먼저 수령한 후 그 중에서 일정 비율을 제휴자에게 지급하는 방식을 채택한다. 하지만 LockBit의 리더인 **LockBitSupp**는 사이버 범죄 커뮤니티에서도 논란이 많은 인물로 알려져 있다. 초기 접근 권한을 제공하는 브로커에게 돈을 지불하지 않아 러시아 기반의 유명한 두 해커 포럼인 XSS와 Exploit에서 차단당하기도 했다. 2022년에는 LockBit 3.0의 개발자와 보상금 지급  문제로 갈등을 빚으며, 그 결과 해당 소프트웨어의 소스 코드가 개발자에 의해 유출되는 일도 발생했다.

<br>
## **LockBit Takedown**
2024년 2월 20일, 영국 국가범죄수사국(NCA)는 카운트다운처럼 일련의 트윗을 게시한 후, 세계 최대의 랜섬웨어 서비스 제공업체인 LockBit의 인프라 전체를 장악했음을 알리는 영상을 공개했다. 이는 여러 국가의 법 집행 기관이 참여한 국제 공조 작전인 **크로노스 작전**이었다.

인프라 장악과 함께 200개 이상의 암호화폐 계정이 동결되고 제재가 가해졌으며, 34개의 서버와 14,000개의 계정이 폐쇄되었다. 이와 함께 폴란드와 우크라이나에서 LockBit의 제휴자 3명이 체포되었다. 또한, 피해자들이 값을 지불하여도 유출된 데이터를 삭제하겠다고 했던 약속이 지켜지지 않았던 사실도 밝혀지게 되었다.

기존의 랜섬웨어 사이트가 폐쇄될 때는 단순히 사이트가 오프라인 상태로 바뀌거나 법 집행 기관의 압수 공지가 표시되곤 했지만 2024년 2월의 LockBit 폐쇄는 특별하다. 법 집행 기관이 LockBit 사이트 자체를 언론 보도, 복호화 키 제공, 체포 및 기소 뉴스 공유 등에 활용하여 세계에서 가장 악명 높은 사이버 범죄 조직 중 하나를 조롱한 사례로 주목받았기 때문이다.

이러한 조치는 사이버 보안 커뮤니티 전반에서 큰 환영을 받았다. 법 집행 기관은 LockBit 사이트의 사용자 이름 목록까지 공개하며 “**우리는 그들이 누군지 알고 있으며, 계속 주시할 것이다.**”라고 경고하는 영상을 공개하였다.

<br>
## **How did it respond?**
LockBit은 폐쇄된 후 일주일 만에 다시 사이트를 열어 빠르게 재활성화되었다. 그러나 눈썰미 있는 보안 연구자들은 게시된 일부 랜섬웨어 피해자 목록이 재활용된 것임을 발견했다.

이후 LockBit은 사이버 보안 사이트인 Vx-underground에 장문의 성명을 보내 **5년간 돈에 파묻혀 살면서 매우 나태해졌다**라며 이를 **부주의와 무책임의 결과**라고 언급한 바 있다.

사이버 범죄 세계에서는 신뢰가 곧 평판이다. LockBit의 대응이 효과가 있을지는 미지수이지만, 이번 공개적인 폐쇄로 상당한 타격을 입은 것은 분명해보인다. RaaS의 미래가 어떻게 될지는 예측하기 어렵다. LockBit이 가장 큰 제공자이긴 하나, **Black Basta**나 **Rhysida** 같은 다른 RaaS도 존재한다. 게다가 여러 RaaS를 동시에 사용하는 경우가 많다.

GI-TOC(Global Initiative Against Transnational Organized Crime)가 위협 정보 전문가들과 인터뷰한 결과, 앞으로는 유출된 데이터의 가치가 중요해지며 새로운 데이터 브로커 시장이 형성될 것이라는 전망이 나왔다. 하지만, 현재 평균 몸값이 150만 달러에 달하는 만큼 랜섬웨어는 여전히 수익성이 높은 사업임은 분명해 보인다. 피해자들이 계속 돈을 지불하는 한 이 비즈니스 모델은 유지될 것이며, 법 집행 기관과 사이버 범죄자들 간의 끝없는 **두더지 잡기 싸움**은 계속될 것이다.

<br>
## **Reference**
[https://globalinitiative.net/analysis/the-lockbit-takedown-law-enforcement-trolls-ransomware-gang/](https://globalinitiative.net/analysis/the-lockbit-takedown-law-enforcement-trolls-ransomware-gang/)