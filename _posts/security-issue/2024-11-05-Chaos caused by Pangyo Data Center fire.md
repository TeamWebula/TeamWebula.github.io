---
title: "Chaos caused by Pangyo Data Center fire"
description: "Spreading malicious code disguised as KakaoTalk update file"
author: bde574786
date: 2024-11-05 06:06:00 +0900
categories: [최근 보안 이슈]
tags: [Recent Issue]
image: assets/posts/security-issue/2024-11-05/img-001.png
---

2022년 10월 15일, 판교 데이터센터 화재로 인해 카카오 서비스 장애가 발생하자, 이를 악용한 사이버 공격이 보고되었다.

<br>
## **Attack Process Details**

1. **공문서 및 파일로 위장**
    - 공격자들은 카카오톡 갱신 파일이나 서비스 복구에 필요한 업데이트 파일로 위장한 악성코드를 배포했다. 사용자들이 데이터 센터 화재로 인해 불안한 상황을 틈타, 신뢰할 만한 공문서나 파일인 척 접근하도록 유도한 것이다.
2. **소셜 미디어 및 이메일 활용**
    - 악성 파일은 주로 이메일이나 소셜 미디어, 그리고 메시지 애플리케이션을 통해 전파되었다. 특히 카카오톡을 이용하여 "카카오톡을 즉시 복구할 수 있다"는 메시지를 전송하였고, 마치 공식적인 복구 방법인 것처럼 조작하여 사용자들을 혼란에 빠뜨렸다.
3. **악성코드 실행 및 정보 탈취**
    - 사용자가 파일을 다운로드하고 실행하면, 악성코드가 컴퓨터에 설치되어 동작하게 된다. 이 악성코드는 주로 사용자 정보를 탈취하거나 추가적인 악성 프로그램을 다운로드 및 설치하도록 유도하는 역할을 한다. 특히 개인정보나 금융 정보를 노리는 공격이었다.
4. **피해 확산**
    - 사회적 혼란을 이용해 배포된 악성코드는 다수의 사용자에게 퍼져나갔고, 개인정보 유출, 계정 도용, 금융 피해 등 다양한 2차 피해를 초래했다.

과학기술정보통신부와 한국인터넷진흥원(KISA)은 카카오톡 설치 파일(KakaoTalkUpdate.zip 등)로 위장한 악성 프로그램이 해킹 메일을 통해 유포되고 있음을 확인하고, 해당 유포 사이트를 긴급 차단했다. 또한, 장애 관련 문자메시지(SMS)를 통해 피싱 사이트에 로그인을 유도하여 사용자 계정 정보를 탈취하는 사이버 공격 가능성도 높아졌다.

<br>
## **How to Respond**

이와 같은 공격에 대응하기 위해서는 다음과 같은 대처가 필요하다.

1. **공식 채널 확인**
    - 서비스 장애나 혼란 상황이 발생하면 반드시 서비스 제공자의 공식 채널(홈페이지, 고객센터 등)을 통해 확인하는 것이 중요하다.
2. **출처가 불분명한 파일 실행 금지**
    - 신뢰할 수 없는 출처에서 파일을 다운로드하거나 실행하지 않도록 유의해야 한다.
3. **보안 소프트웨어 사용**
    - 최신 보안 소프트웨어와 백신 프로그램을 설치해 잠재적인 악성코드 위협을 예방할 수 있다.

<br>
## Reference

[https://www.dailian.co.kr/news/view/1163070](https://www.dailian.co.kr/news/view/1163070)