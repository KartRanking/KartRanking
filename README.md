# KartRanking

카트라이더 리그 개인전 8인제 TrueSkill 랭킹. (랭킹 ver. 0.3)


- 방법: [TrueSkill](https://trueskill.org/). 이 방법은 각 선수의 기량을 평균 mu, 표준편차 sigma의 정규분포로 나타내고 베이지안 추론을 통해 추정된 mu와 sigma에 기반하여 순위를 매김. 점수는 mu - 3 sigma로 하여 "어떤 선수의 기량이 99%의 확률로 이 점수 이상이다"를 나타냄. 이 분석에서 각 선수는 mu=3000, sigma=1000로 시작함 (시작값은 스케일에만 영항을 미치고 선수들 사이의 상대적인 위치에는 영향을 미치지 않음).
예를 들어, 박도현의 추정된 mu는 이재혁의 그것보다 높지만 박도현이 지금까지 치른 경기 수가 적어 불확실성이 크기 때문에 그만큼 점수를 깎으므로 박도현이 이재혁보다 밑에 있게 됨.

- 자료: 2016년 듀얼레이스 1 이후 모든 개인전 8인전 방송 경기 (2017 케스파 컵과 듀얼레이스 X 포함, 티밍이 있었던 글로벌 슈퍼매치 제외)

- 최근 경기: 2019년 시즌 2 결승전

__팀전 랭킹, 팀전 개인별 랭킹, 트랙 별 랭킹 준비 중!!!__

| 순위 | 이름 | 점수 | mu | sigma |
|:---:|:---:|---:|---:|---:|
| 1 | 문호준 | 3364 | 3593 | 76 |
| 2 | 이재혁 | 3283 | 3515 | 77 |
| 3 | 박도현 | 3268 | 3543 | 92 |
| 4 | 유창현 | 3262 | 3493 | 77 |
| 5 | 박인수 | 3260 | 3491 | 77 |
| 6 | 유영혁 | 3172 | 3398 | 76 |
| 7 | 정승하 | 3142 | 3380 | 79 |
| 8 | 신동이 | 3139 | 3461 | 107 |
| 9 | 황인호 | 3104 | 3333 | 76 |
| 10 | 김승태 | 3094 | 3327 | 78 |
| 11 | 전대웅 | 3075 | 3306 | 77 |
| 12 | 김정제 | 3062 | 3296 | 78 |
| 13 | 배성빈 | 3027 | 3265 | 79 |
| 14 | 신종민 | 2992 | 3234 | 80 |
| 15 | 최영훈 | 2954 | 3185 | 77 |
| 16 | 송용준 | 2950 | 3199 | 83 |
| 17 | 김승래 | 2943 | 3171 | 76 |
| 18 | 이재인 | 2934 | 3218 | 95 |
| 19 | 이준성 | 2931 | 3162 | 77 |
| 20 | 김기수 | 2923 | 3183 | 87 |
| 21 | 이중선 | 2917 | 3171 | 85 |
| 22 | 김응태 | 2904 | 3157 | 84 |
| 23 | 박현수 | 2892 | 3136 | 81 |
| 24 | 임재원 | 2851 | 3088 | 79 |
| 25 | 손우현 | 2847 | 3172 | 108 |
| 26 | 한승철 | 2820 | 3069 | 83 |
| 27 | 이준용 | 2806 | 3048 | 81 |
| 28 | 최윤서 | 2805 | 3140 | 111 |
| 29 | 김주원 | 2788 | 3098 | 103 |
| 30 | 황선민 | 2785 | 3138 | 118 |
| 31 | 문민기 | 2734 | 3289 | 185 |
| 32 | 김이준 | 2683 | 3003 | 107 |
| 33 | 양민규 | 2665 | 2975 | 103 |
| 34 | 김경훈 | 2640 | 2999 | 120 |
| 35 | 박효민 | 2597 | 3023 | 142 |
| 36 | 김지민 | 2588 | 2956 | 123 |
| 37 | 권순민 | 2570 | 2887 | 106 |
| 38 | 한상현 | 2567 | 2997 | 143 |
| 39 | 윤정현 | 2533 | 3170 | 212 |
| 40 | 이승교 | 2531 | 2876 | 115 |
| 41 | 전강인 | 2530 | 2931 | 134 |
| 42 | 이건욱 | 2526 | 2952 | 142 |
| 43 | 김진석 | 2524 | 2847 | 108 |
| 44 | 최준호 | 2449 | 2873 | 141 |
| 45 | 강진우 | 2448 | 2988 | 180 |
| 46 | 문진형 | 2447 | 2879 | 144 |
| 47 | 박지호 | 2436 | 2822 | 129 |
| 48 | 박병선 | 2432 | 3026 | 198 |
| 49 | 오성현 | 2432 | 3034 | 201 |
| 50 | 정해섭 | 2427 | 3008 | 194 |
| 51 | 사상훈 | 2407 | 2843 | 145 |
| 52 | 우성민 | 2399 | 3000 | 201 |
| 53 | 정승민 | 2386 | 2727 | 114 |
| 54 | 조성제 | 2376 | 2954 | 193 |
| 55 | 이태경 | 2370 | 2893 | 174 |
| 56 | 박현수B | 2311 | 2705 | 131 |
| 57 | 온유민 | 2311 | 2944 | 211 |
| 58 | 이은택 | 2261 | 2818 | 185 |
| 59 | 강석인 | 2233 | 2876 | 214 |
| 60 | 김유창 | 2189 | 2857 | 223 |
| 61 | 김상수 | 2178 | 2825 | 215 |
| 62 | 노준엽 | 2138 | 2634 | 165 |
| 63 | 박민우 | 2130 | 2756 | 209 |
| 64 | 김경모 | 2085 | 2866 | 260 |
| 65 | 심우혁 | 2063 | 2714 | 217 |
| 66 | 박천원 | 2045 | 2702 | 219 |
| 67 | 최성수 | 2031 | 2704 | 224 |
| 68 | 한주성 | 2028 | 2676 | 216 |
| 69 | 배재민 | 2009 | 2515 | 169 |
| 70 | 박창규 | 1963 | 2635 | 224 |
| 71 | 이강호 | 1911 | 2551 | 214 |
| 72 | 이다빈 | 1901 | 2517 | 205 |
| 73 | 김대진 | 1885 | 2565 | 227 |
| 74 | 조원호 | 1883 | 2574 | 230 |
| 75 | 현록빈 | 1845 | 2461 | 206 |
| 76 | 최민석 | 1843 | 2483 | 213 |
| 77 | 강현 | 1836 | 2636 | 267 |
| 78 | 박민호 | 1821 | 2497 | 225 |
| 79 | 임성준 | 1769 | 2448 | 226 |
| 80 | 김선일 | 1580 | 2228 | 216 |
| 81 | 전진우 | 1578 | 2433 | 285 |
| 82 | 조다훈 | 1544 | 2190 | 216 |

* 박현수: 샌드박스 소속.
* 박현수B: 범스 소속으로 나왔던 박현수.

## 지난 경기들


__2019년 이전에는 Elo rating을 사용함.__

* 2019 시즌 2
  * [2019 시즌 2 결승전](./rounds/2019_2_6.md)
  * [2019 시즌 2 16강 최종전](./rounds/2019_2_5.md)
  * [2019 시즌 2 16강 승/패자전](./rounds/2019_2_4.md)
  * [2019 시즌 2 16강 1회전](./rounds/2019_2_3.md)
  * [2019 시즌 2 32강 패자부활전](./rounds/2019_2_2.md)
  * [2019 시즌 2 32강 1회전](./rounds/2019_2_1.md)
* 2019 시즌 1
  * [2019 시즌 1 결승전](./rounds/2019_1_6.md)
  * [2019 시즌 1 16강 최종전](./rounds/2019_1_5.md)
  * [2019 시즌 1 16강 승/패자전](./rounds/2019_1_4.md)
  * [2019 시즌 1 16강 1회전](./rounds/2019_1_3.md)
  * [2019 시즌 1 32강 패자부활전](./rounds/2019_1_2.md)
  * [2019 시즌 1 32강 1회전](./rounds/2019_1_1.md)
* [듀얼 레이스 X](./rounds/2018_2.md)
* [듀얼 레이스 3](./rounds/2018_1.md)
* [2017 KeSPA Cup](./rounds/2017_2.md)
* [듀얼 레이스 2](./rounds/2017_1.md)
* [듀얼 레이스](./rounds/2016_1.md)



* TrueSkill은 Microsoft의 자산으로 비상업적 이용만 가능합니다.

* 의견 및 게시글 환영합니다. 
    - 연락처: kart.rider.ranking a t  g m a i l (dot) c o m 
    - 또는 [이 페이지의 issue tracker](https://github.com/hiddenidol/KartRanking/issues)(github 계정 필요)
* 이 페이지의 자료를 사용 시 다음을 명시해 주세요.
```
https://github.com/hiddenidol/KartRanking
github: @hiddenidol
```
