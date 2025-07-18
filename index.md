---
title: 2025 Summer School on Combinatorics and Algorithms
description: "14-18 July 2025, POSTECH"
--- 
# 2025 조합론 및 알고리듬 여름학교

[English](/en/)

![Group Photo 2025](/assets/2025combialgo.jpg)

- 날짜: 2025년 7월 14-18일
- 장소: POSTECH
  - 강의실: <span class="mi">1</span> [인공지능연구원](https://naver.me/xY47CR3o) 122호
  - 그룹 토의 및 연습실: <span class="mi">3</span> [제2공학관](https://naver.me/5qD7jmvo) Room 104 (Group 1~4), Room 106 (Group 5~8), Room 107 (Group 9~12), Room 109 (Group 13~16)
  - 저녁 시간 자유 토의실: <span class="mi">2</span> [무은재기념관](https://naver.me/xyTaSNCN) 303호, 304호, 305호, 309호


2025년 조합론 및 알고리듬 여름학교는 이론 컴퓨터 과학과 이산수학 분야의 선별된 주제를 학생들과 초기 경력 연구자들이 배우는 장소입니다. 이는 대학 강의에서 다루지 않지만 중요한 주제를 공부할 수 있는 좋은 기회가 될 것입니다. 


연사 및 프로그램 소개
---------------------
{% include program2025.md %}
  
일정 
---------------------  
{% include schedule2025.md %}

등록
--------------------- 
- [등록 홈페이지 https://indico.ibs.re.kr/e/combialgo2025](https://indico.ibs.re.kr/e/combialgo2025): 등록 마감 5월 31일.


## 조직위원

- [김은정](https://www.lamsade.dauphine.fr/~kim/) (KAIST 전산학부)
- [엄상일](https://dimag.ibs.re.kr/home/sangil/) (IBS 이산수학그룹)
- [오은진](https://sites.google.com/view/eunjinoh/) (포스텍 컴퓨터공학과)

## 역사

- [2024년 조합론 및 알고리듬 여름학교](/2024/)


## 정보 



<div id="map"></div>
<script language="javascript">
var map = L.map('map').setView([36.011,129.3222], 17);
L.tileLayer('https://{s}.tile.openstreetmap.de/{z}/{x}/{y}.png', {
    maxZoom: 19,
    attribution: '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors'
}).addTo(map);
L.control.scale().addTo(map);
function pm(label, lat, long, title,link) {
    var myIcon=L.divIcon({className:"mi", html:label });
    L.marker([lat, long],{icon:myIcon}).addTo(map)
    .bindPopup('<b><a href="'+link+'" target=_new>'+title+'</a></b>');
}
pm(1, 36.010656, 129.321426, '인공지능연구원', 'https://naver.me/xY47CR3o');
pm(2, 36.012041, 129.322353, '무은재기념관', 'https://naver.me/xyTaSNCN');
pm(3, 36.012441, 129.321948, '제2공학관', 'https://naver.me/5qD7jmvo');

</script>

![POSTECH Campus Map](/assets/postechmap2025.png)

- [교내 및 인근 식당 리스트](/assets/pdf/restaurants2025.pdf)

{% include logo.html %}


