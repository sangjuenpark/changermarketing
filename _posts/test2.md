---
layout: post
permalink: /digital-marketing-google-searchconsoletest2/
title: 'test2-'
date: 2020-04-05 13:30:00 +09:00
feature: '/img/posts/04/04-thumbnail.jpg'
background: '/img/posts/04/04-background.jpg'
categories:
  - marketing
tags:
 - 마케팅
 - 도메인
 - 소셜섹터
 - 디지털마케팅
 - 검색엔진
 - 구글
content_id: '2020405_searchconsole'
description: '구글 검색엔진에 사이트 노출 시키는 방법.'
---

## 구글 검색엔진에 사이트 노출 시키는 방법



처음 소셜섹터 마케터로 들어가 일을 하다 보면 신규 사업을 시작하거나 또는 아직 초기 단계라 홈페이지를 구축부터 해야 되는 경우가 있기도 하다. 힘들게 도메인도 구매하고 사이트를 만들기 위한 기획부터 디자인까지 해서 사이트를 런칭했는데 사이트가 검색엔진에 노출이 안 되는 경우가 있기도 하다. (물론 요새는 사이트 대행 업체, 제작서비스 업체에서 제작부터 검색엔진 노출까지 한번에 처리하는 경우가 많다.) 필자가 근무하고 있는 회사에서도 ‘캠페이너스’ [campaignus](https://campaignus.do/) 웹사이트 제작 도구로 코딩을 몰라도 블로그 만들 듯 마우스 클릭만으로 웹사이트를 구축할 수 있다. (구글애널리틱스와 연동하여 방문자 데이터 분석까지도 알 수 있다)



본 포스팅은 검색 노출에 대한 부분이니 향후 캠페이너스 서비스 및 구글애널리틱스는 다음에 상세히 설명하도록 하겠다.



다시 본론으로 돌아와 한국에서 많이 쓰이는 검색엔진에 사이트를 노출 시키는 방법을 간단히 알아보고자 한다. 현재 아래 이미지를 보면 국내 검색엔진에서 네이버, 구글, 다음 순으로 검색엔진의 점유율을 차지하고 있다. 향후에는 구글의 검색엔진 영향력이 더욱 확대되어 검색엔진 점유율의 비율은 점차 구글이 높아질 수 있다.

![search engine](/img/posts/04/search engine.jpg)



한국에서 가장 많이 쓰이는 3대 검색엔진 (구글, 네이버, 다음)에 사이트를 노출 시키는 방법은 크게 다음과 같다.



### 구글

구글에 사이트를 노출 시키기 위해서는 [구글 서치 콘솔 사이트](https://search.google.com/search-console/about?hl=ko) 에 접속해야 한다.

![search console](/img/posts/04/search console.jpg)

처음 사이트가 등록되어 있지 않다면 아래와 같은 이미지가 나오게 될 것이다.

혹시 다른 사이트들이 등록되어 있다면 개요 위 상단을 클릭하면 속성 추가가 있을 것이다.

속성추가를 누르면 아래와 같이 도메인을 등록하는 화면이 나오게 된다. 해당 영역에 본인 도메인 주소를 입력하면 된다. Ex) changermarketing.com

![search console1](/img/posts/04/search console1.jpg)

아래 본인의 TXT 레코트를 본인 도메인의 DNS 설정에 복사해서 이용하면 된다.

도메인을 구입한 곳 EX) 카페24, 고도몰, 호스팅케이알 등으로 이동하여 등록한 도메인의 DNS를 수정하는 메뉴에 복사한 DNS를 붙여넣기 하면 된다.

*DNS: Domain Name System은 사람이 읽을 수 있는 도메인 이름을 머신이 읽을 수 있도록 IP 주소로 변환합니다.

![search console2](/img/posts/04/search console2.jpg)

필자는 마개이너 스터디를 통해 CLOUDFLARE를 이용하여 DNS를 관리하므로 아래와 같은 형태이다. 해당 DNS 입력창에 TXT를 선택하고 복사한 코드를 등록하면 된다. (마개이너 스터디에 다시 한번 감사하며 이 포스팅을 올린다)

![search console dns](/img/posts/04/search console dns.jpg)



등록이 다 되었으면, 다시 소유권 확인하게 되면 아래와 같은 이미지가 나오면 정상적으로 된 것이다.

 ![search console3](/img/posts/04/search console3.jpg)

조금이라도 구글 검색 로봇이 우리 사이트를 구글 검색에 잘 노출 될 수 있도록 Sitemaps에 본인 도메인을 입력하고 제출하는 과정도 필요하다.

새 사이트맵에 https://도메인/sitemap.xml을 제출하고 기다리면 된다.

 ![search console4](/img/posts/04/search console4.jpg)

이후 시간이 지나 구글에 본인 사이트를 검색하면 구글에 노출이 된다. 허나 사이트가 보편적인 검색어,키워드일 경우 다소 노출이 쉽지 않기에 검색이 잘 안 될 수 있다.

 ![search console5](/img/posts/04/search console5.jpg)

추가로, 도메인 각 하위 주소를 구글 서치콘솔에 URL 검사로 제출하면 구글에 노출되는데 도움이 된다.

 ![search console6](/img/posts/04/search console6.jpg)

### 참고사항

#### 구글애널리틱스&구글서치콘솔 연동

구글서치콘솔을 연결하면 구글애널리틱스 획득 보고서에서도 구글서치콘솔 데이터를 볼 수 있다.

허나 구글애널리틱스에서 제공되는 구글 서치콘솔 데이터는 수집 및 한계가 있기에 구글 서치콘솔에서 데이터를 확인하는게 더 정확하다.

구글 서치콘솔 보고서에는 구글에서 어떤 검색어로 유입되었는지도 확인이 가능하다.

 ![search console7](/img/posts/04/search console7.jpg)

**다만, 아직 구글애널리틱스에서 보고서에서 구글서치콘솔의 도메인 속성으로 연결 지원이 되지 않는 불편함이 있다. 이에 구글애널리틱스에서 구글서치콘솔의 데이터를 보려면 URL접두어를 이용하여 연결해야 한다.**

(사이트가 http, https 버전, 별도의 모바일 url이 있다면 각각 등록해야 하는 불편함이 있다)

 ![search console8](/img/posts/04/search console8.jpg)

HTML 파일을 등록하는 방법도 있지만, 구글애널리틱스 및 구글 태그관리자가 정상적으로 설치되어 있으면 보다 쉽게 소유권 확인이 가능하다.

보다 자세한 사항은 [구글 도움말](https://support.google.com/webmasters/answer/9008080?hl=ko)을 참고하면 된다.

  ![search console9](/img/posts/04/search console9.jpg)

이번 포스팅에는 구글에 내 사이트를 검색노출 시키는 방법을 알아봤다. 생각보다 이미지 첨부가 많아 포스팅이 길어지게 되어 다음 포스팅에는 네이버, 다음 사이트에 검색 노출 시키는 방법을 알아보려 한다. 그럼 이만~
