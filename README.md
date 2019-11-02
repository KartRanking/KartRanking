# KartRanking

카트라이더 리그 개인전 8인제 Elo 랭킹. (ver. 0.2)

> I am someone who could not watch _American Idol_ without [whatnottosing.com](http://whatnottosing.com) and could not watch _Jeopardy!_ without [thejeopardyfan.com](https://thejeopardyfan.com). I started watching the KartRider league in 2018, and weirdly for a professional sporting event, could not find a good statistical analysis on it. They gave some simulated numbers on the preshow, but they were insufficient and misleading. So I made something that I would accompany watching the games.

- 방법: Elo rating에 기반한 방법, [fivethirtyeight.com 에서 F1 레이싱에 적용한 방법](https://fivethirtyeight.com/features/formula-one-racing/)과 비슷한 방법을 사용함. 매 트랙마다 1위는 7승 0패, 2위는 6승 1패, ..., 8위는 0승 7패를 한 것으로 계산하여 점수를 한번에 업데이트. 모형에는 점수의 변화량을 제어하는 비례상수 "K"가 있는데, 여기서는 50점제 1-3번째 경기인 선수는 10, 4-5번째 경기인 선수는 7, 6번째 이상인 선수는 5를 사용함. 
각 선수의 시작 점수는 1600점, sigma=400 (점수 차가 400점 나는 두 선수가 1:1로 붙었을 때 점수가 높은 선수가 이길 확률이 점수가 낮은 선수의 10배). 2019년 기준 1635점=32강 평균 수준, 1700점=16강 평균 수준, 1760점=결승전 평균 수준. 

- 자료: 2016년 듀얼레이스 1 이후 모든 개인전 8인전 방송 경기 (2017 케스파 컵과 듀얼레이스 X 포함, 티밍이 있었던 글로벌 슈퍼매치 제외)

- 최근 경기: 2019년 시즌 2 16강 최종전

| 순위 | 이름 | 점수 | 점수변화 |
|---:|:---:|---:|---:|
|  1 |   박인수 | 1838 |    0 |
|  2 |   문호준 | 1835 |    0 |
|  3 |   유창현 | 1808 |    0 |
|  4 |   이재혁 | 1782 |   66 |
|  5 |   황인호 | 1755 |   22 |
|  6 |   박도현 | 1741 |   19 |
|  7 |   신동이 | 1738 |    0 |
|  8 |   정승하 | 1736 |    0 |
|  9 |   유영혁 | 1709 |    0 |
| 10 |   김기수 | 1705 |    0 |
| 11 |   송용준 | 1698 |    0 |
| 12 |   배성빈 | 1696 |   22 |
| 13 |   김승태 | 1694 |    0 |
| 14 |   신종민 | 1675 |   -5 |
| 15 |   문민기 | 1671 |    0 |
| 16 |   최영훈 | 1666 |   -8 |
| 17 |   최윤서 | 1655 |    0 |
| 18 |   손우현 | 1647 |    0 |
| 19 |   박현수 | 1647 |  -11 |
| 20 |   김정제 | 1646 |    0 |
| 21 |   전대웅 | 1640 |  -99 |
| 22 |   김응태 | 1632 |    0 |
| 23 |   이준성 | 1628 |    0 |
| 24 |   김승래 | 1627 |    0 |
| 25 |   이건욱 | 1620 |    0 |
| 26 |   임재원 | 1616 |    0 |
| 27 |   윤정현 | 1610 |    0 |
| 28 |   박병선 | 1604 |    0 |
| 29 |   조성제 | 1603 |    0 |
| 30 |   이중선 | 1598 |    0 |
| 31 |   한상현 | 1595 |    0 |
| 32 |   김경모 | 1595 |    0 |
| 33 |   이준용 | 1595 |    0 |
| 34 |   문진형 | 1593 |    0 |
| 35 |   이재인 | 1593 |    0 |
| 36 |   양민규 | 1592 |    0 |
| 37 |   김주원 | 1592 |    0 |
| 38 |   김진석 | 1592 |    0 |
| 39 |   우성민 | 1591 |    0 |
| 40 |   강진우 | 1589 |    0 |
| 41 |   박효민 | 1586 |    0 |
| 42 |   김유창 | 1585 |    0 |
| 43 |   한승철 | 1585 |    0 |
| 44 |   온유민 | 1583 |    0 |
| 45 |   최준호 | 1579 |    0 |
| 46 |   김경훈 | 1574 |    0 |
| 47 |     강현 | 1572 |    0 |
| 48 |   오성현 | 1570 |    0 |
| 49 |   강석인 | 1567 |    0 |
| 50 |   김지민 | 1562 |    0 |
| 51 |   전강인 | 1561 |    0 |
| 52 |   권순민 | 1560 |    0 |
| 53 |   김상수 | 1559 |    0 |
| 54 |   심우혁 | 1558 |    0 |
| 55 |   최성수 | 1557 |    0 |
| 56 |   이태경 | 1555 |    0 |
| 57 |   황선민 | 1553 |    0 |
| 58 |   이은택 | 1550 |    0 |
| 59 |   김이준 | 1549 |    0 |
| 60 |   전진우 | 1547 |    0 |
| 61 |   정승민 | 1545 |    0 |
| 62 |   정해섭 | 1543 |    0 |
| 63 |   박민우 | 1541 |    0 |
| 64 |   박천원 | 1539 |    0 |
| 65 |   박민호 | 1536 |    0 |
| 66 |   이승교 | 1528 |    0 |
| 67 |   이강호 | 1525 |    0 |
| 68 |   최민석 | 1525 |    0 |
| 69 |   한주성 | 1523 |    0 |
| 70 |   김대진 | 1517 |    0 |
| 71 |  박현수B | 1513 |    0 |
| 72 |   노준엽 | 1512 |    0 |
| 73 |   박창규 | 1510 |    0 |
| 74 |   조원호 | 1506 |    0 |
| 75 |   이다빈 | 1500 |    0 |
| 76 |   사상훈 | 1494 |    0 |
| 77 |   현록빈 | 1477 |    0 |
| 78 |   임성준 | 1476 |    0 |
| 79 |   배재민 | 1463 |    0 |
| 80 |   박지호 | 1444 |    0 |
| 81 |   김선일 | 1439 |    0 |
| 82 |   조다훈 | 1424 |    0 |

* 박현수: 샌드박스 소속.
* 박현수B: 범스 소속으로 나왔던 박현수.

### 다음 라운드 승부예측 (2019 시즌 2 결승전)
* 방법: 매 트랙마다 각 선수에 대응하는 평균이 현재 Elo 점수이고 스케일이 400/sqrt(6)인 로지스틱 분포에서 숫자를 하나씩 추출하여 그 순서대로 순위를 부여, 그에 맞춰 Elo 점수와 경기 점수를 업데이트. 이를 경기 종료 조건이 될 때까지 반복.

* 평균점수: 1758, 표준편차: 56

|  | 박인수 | 문호준 | 유영혁 | 김기수 | 이재혁 | 황인호 | 박도현 | 배성빈 |
|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 1위 | 29.284 | 28.161 | 4.528 | 4.162 | 14.095 | 9.501 | 10.174 | 3.513 |
| 2위 | 20.77 | 20.899 | 6.782 | 6.497 | 15.392 | 11.705 | 10.812 | 5.67 |
| 3위 | 15.924 | 16.065 | 9.888 | 9.592 | 15.949 | 13.959 | 11.869 | 8.769 |
| 4위 | 11.878 | 12.074 | 12.14 | 11.663 | 14.832 | 14.774 | 12.06 | 10.967 |
| 5위 | 8.974 | 9.265 | 14.105 | 13.971 | 13.292 | 14.356 | 12.618 | 13.638 |
| 6위 | 6.487 | 6.567 | 16.179 | 16.441 | 11.154 | 13.755 | 12.755 | 16.091 |
| 7위 | 4.279 | 4.46 | 17.749 | 18.105 | 9.102 | 12.142 | 14.09 | 19.02 |  
| 8위 | 2.404 | 2.509 | 18.629 | 19.569 | 6.184 | 9.808 | 15.622 | 22.332 |
| 최종 2인 | 50.054 | 49.06 | 11.31 | 10.659 | 29.487 | 21.206 | 20.986 | 9.183 |
| 입상 | 65.978 | 65.125 | 21.198 | 20.251 | 45.436 | 35.165 | 32.855 | 17.952 |

현재 랭킹 포인트를 기반으로 볼 때 결승은 2강-1중강-2중-3약 체제이다. 
이번 시즌에도 압도적인 모습을 보인 박인수-문호준이 상위 2인에 들 가능성이 50% 근처인 2강, 
최종전에서 후반부까지 폼을 유지하는 모습을 보인 이재헉이 상위 2인에 들 가능성이 30% 가량인 1중강, 
최종전에서 꾸준한 모습을 보여준 황인호와 박도현이 상위 2인에 들 가능성 20% 가량의 2중, 
승자전에서 결승에 직행했지만 패자조로 내려간 선수들을 압도하지는 못했던 유영혁-김기수와 
패자전에서 막차를 타고 결승에 올라온 배성빈이 상위 2인에 들 가능성 약 10%의 3약. 

박인수-문호준은 이번 시즌에도 최후 2인에서 대결하게 될 것인가? 
이번 시즌 모든 경기에서 25점에 선착한 유일한 선수인 이재혁이 박인재 감독의 케어를 받아 80점제에서도 꾸준한 모습을 보일 수 있을 것인가?
늘 꾸준한 황인호가 이번에는 입상할 수 있을 것인가?
그동안 쌓은 커리어에 비해 압도적인 모습을 보여주지는 못하고 있는 유영혁이 결승에서는 뭔가 보여줄 수 있을 것인가?
한화생명의 막내 박도현-배성빈이 더욱 성장한 모습을 보일 것인가?
이번 시즌 가장 많이 성장한 김기수는 어디까지 성장한 모습으로 시즌을 마칠 것인가?
그리고... 마지막 1:1 결승전에서 승리해 우승 트로피를 거머쥘 1인은 누구인가? 

### 다음 경기 참가자의 랭킹 포인트 이력

#### 박인수

| 경기 | 점수 | 점수변동 |
|:---:|---:|---:|
| 2016 듀얼 레이스 32강 | 1587 |  |
| 2017 듀얼 레이스 2 16강 | 1561 | -26 |
| 2017 듀얼 레이스 2 16강 패자부활전 | 1606 | 45 |
| 2017 KeSPA Cup 32강 | 1629 | 23 |
| 2017 KeSPA Cup 16강 | 1615 | -14 |
| 2017 KeSPA Cup 16강 패자부활전 | 1686 | 71 |
| 2017 KeSPA Cup 16강 결승 | 1730 | 44 |
| 2018 듀얼 레이스 3 32강 | 1749 | 19 |
| 2018 듀얼 레이스 3 16강 1회전 | 1735 | -14 |
| 2018 듀얼 레이스 3 16강 승/패자전 | 1737 | 2 |
| 2018 듀얼 레이스 3 16강 최종전 | 1785 | 48 |
| 2018 듀얼 레이스 3 결승전 | 1766 | -19 |
| 2018 듀얼 레이스 X | 1823 | 57 |
| 2019 시즌 1 32강 | 1838 | 15 |
| 2019 시즌 1 16강 1회전 | 1854 | 16 |
| 2019 시즌 1 16강 승/패자전 | 1838 | -16 |
| 2019 시즌 1 결승전 | 1860 | 22 |
| 2019 시즌 2 32강 | 1807 | -53 |
| 2019 시즌 2 16강 1회전 | 1800 | -7 |
| 2019 시즌 2 16강 승/패자전 | 1838 | 38 |

#### 문호준

| 경기 | 점수 | 점수변동 |
|:---:|---:|---:|
| 2016 듀얼 레이스 32강 | 1711 |  |
| 2016 듀얼 레이스 결승 | 1695 | -16 |
| 2017 듀얼 레이스 2 16강 | 1765 | 70 |
| 2017 듀얼 레이스 2 결승 | 1696 | -69 |
| 2017 KeSPA Cup 32강 | 1747 | 51 |
| 2017 KeSPA Cup 16강 | 1779 | 32 |
| 2017 KeSPA Cup 16강 결승 | 1797 | 18 |
| 2018 듀얼 레이스 3 32강 | 1814 | 17 |
| 2018 듀얼 레이스 3 16강 1회전 | 1843 | 29 |
| 2018 듀얼 레이스 3 16강 승/패자전 | 1842 | -1 |
| 2018 듀얼 레이스 3 결승전 | 1891 | 49 |
| 2018 듀얼 레이스 X | 1878 | -13 |
| 2019 시즌 1 32강 | 1878 | 0 |
| 2019 시즌 1 16강 1회전 | 1891 | 13 |
| 2019 시즌 1 16강 승/패자전 | 1850 | -41 |
| 2019 시즌 1 결승전 | 1856 | 6 |
| 2019 시즌 2 32강 | 1866 | 10 |
| 2019 시즌 2 16강 1회전 | 1811 | -55 |
| 2019 시즌 2 16강 승/패자전 | 1835 | 24 |

#### 유영혁

| 경기 | 점수 | 점수변동 |
|:---:|---:|---:|
| 2016 듀얼 레이스 32강 | 1741 |  |
| 2016 듀얼 레이스 결승 | 1769 | 28 |
| 2017 듀얼 레이스 2 16강 | 1736 | -33 |
| 2017 듀얼 레이스 2 16강 패자부활전 | 1741 | 5 |
| 2017 듀얼 레이스 2 결승 | 1726 | -15 |
| 2017 KeSPA Cup 32강 | 1761 | 35 |
| 2017 KeSPA Cup 16강 | 1786 | 25 |
| 2017 KeSPA Cup 16강 결승 | 1789 | 3 |
| 2018 듀얼 레이스 3 32강 | 1817 | 28 |
| 2018 듀얼 레이스 3 16강 1회전 | 1819 | 2 |
| 2018 듀얼 레이스 3 16강 승/패자전 | 1811 | -8 |
| 2018 듀얼 레이스 3 결승전 | 1837 | 26 |
| 2018 듀얼 레이스 X | 1814 | -23 |
| 2019 시즌 1 32강 | 1763 | -51 |
| 2019 시즌 1 16강 1회전 | 1699 | -64 |
| 2019 시즌 1 16강 승/패자전 | 1643 | -56 |
| 2019 시즌 2 32강 | 1678 | 35 |
| 2019 시즌 2 16강 1회전 | 1679 | 1 |
| 2019 시즌 2 16강 승/패자전 | 1709 | 30 |

#### 김기수

| 경기 | 점수 | 점수변동 |
|:---:|---:|---:|
| 2019 시즌 1 32강 | 1607 |  |
| 2019 시즌 1 32강 패자부활전 | 1489 | -118 |
| 2019 시즌 2 32강 | 1624 | 135 |
| 2019 시즌 2 16강 1회전 | 1660 | 36 |
| 2019 시즌 2 16강 승/패자전 | 1705 | 45 |

#### 이재혁

| 경기 | 점수 | 점수변동 |
|:---:|---:|---:|
| 2017 듀얼 레이스 2 16강 | 1656 |  |
| 2017 듀얼 레이스 2 16강 패자부활전 | 1584 | -72 |
| 2017 KeSPA Cup 32강 | 1735 | 151 |
| 2017 KeSPA Cup 16강 | 1773 | 38 |
| 2017 KeSPA Cup 16강 결승 | 1748 | -25 |
| 2018 듀얼 레이스 3 32강 | 1770 | 22 |
| 2018 듀얼 레이스 3 16강 1회전 | 1817 | 47 |
| 2018 듀얼 레이스 3 16강 승/패자전 | 1785 | -32 |
| 2018 듀얼 레이스 3 16강 최종전 | 1773 | -12 |
| 2018 듀얼 레이스 3 결승전 | 1787 | 14 |
| 2018 듀얼 레이스 X | 1793 | 6 |
| 2019 시즌 1 32강 | 1729 | -64 |
| 2019 시즌 2 32강 | 1746 | 17 |
| 2019 시즌 2 16강 1회전 | 1753 | 7 |
| 2019 시즌 2 16강 승/패자전 | 1716 | -37 |
| 2019 시즌 2 16강 최종전 | 1782 | 66 |

#### 황인호

| 경기 | 점수 | 점수변동 |
|:---:|---:|---:|
| 2017 듀얼 레이스 2 16강 | 1617 |  |
| 2017 KeSPA Cup 32강 | 1623 | 6 |
| 2017 KeSPA Cup 16강 | 1651 | 28 |
| 2017 KeSPA Cup 16강 패자부활전 | 1666 | 15 |
| 2018 듀얼 레이스 3 32강 | 1656 | -10 |
| 2018 듀얼 레이스 3 16강 1회전 | 1660 | 4 |
| 2018 듀얼 레이스 3 16강 승/패자전 | 1645 | -15 |
| 2019 시즌 1 32강 | 1706 | 61 |
| 2019 시즌 1 16강 1회전 | 1721 | 15 |
| 2019 시즌 1 16강 승/패자전 | 1691 | -30 |
| 2019 시즌 1 16강 최종전 | 1729 | 38 |
| 2019 시즌 1 결승전 | 1734 | 5 |
| 2019 시즌 2 32강 | 1737 | 3 |
| 2019 시즌 2 16강 1회전 | 1763 | 26 |
| 2019 시즌 2 16강 승/패자전 | 1733 | -30 |
| 2019 시즌 2 16강 최종전 | 1755 | 22 |

#### 박도현

| 경기 | 점수 | 점수변동 |
|:---:|---:|---:|
| 2019 시즌 2 32강 | 1717 |  |
| 2019 시즌 2 16강 1회전 | 1737 | 20 |
| 2019 시즌 2 16강 승/패자전 | 1722 | -15 |
| 2019 시즌 2 16강 최종전 | 1741 | 19 |

#### 배성빈

| 경기 | 점수 | 점수변동 |
|:---:|---:|---:|
| 2017 KeSPA Cup 32강 | 1558 |  |
| 2018 듀얼 레이스 3 32강 | 1588 | 30 |
| 2019 시즌 1 32강 | 1634 | 46 |
| 2019 시즌 1 16강 1회전 | 1600 | -34 |
| 2019 시즌 1 16강 승/패자전 | 1594 | -6 |
| 2019 시즌 2 32강 | 1603 | 9 |
| 2019 시즌 2 32강 패자부활전 | 1616 | 13 |
| 2019 시즌 2 16강 1회전 | 1612 | -4 |
| 2019 시즌 2 16강 승/패자전 | 1674 | 62 |
| 2019 시즌 2 16강 최종전 | 1696 | 22 |

### 지난 경기 리뷰 (16강 최종전)

사실상 외부 요인이 1위와 8위를 가르고 나머지 결과는 대체로 예상을 크게 벗어나지 않았다. 신종민이 본인의 전략 트랙인 공동묘지 해골 손가락과 월드 이탈리아 피사의 사탑을 좋지 못한 순위로 마무리하며 결승전 막차 티켓을 배성빈이 차지.

|    이재혁 |    전대웅 |    박도현 |    황인호 |    배성빈 |    신종민 |    최영훈 |    박현수 |
| ------:| ------:| ------:| ------:| ------:| ------:| ------:| ------:|
| 1716 | 1739 | 1722 | 1733 | 1674 | 1680 | 1674 | 1658 |
| 1733 | 1719 | 1731 | 1743 | 1668 | 1678 | 1663 | 1663 |
| 1733 | 1701 | 1725 | 1758 | 1677 | 1672 | 1653 | 1678 |
| 1749 | 1683 | 1740 | 1747 | 1676 | 1676 | 1663 | 1667 |
| 1739 | 1667 | 1747 | 1757 | 1675 | 1695 | 1667 | 1656 |
| 1754 | 1671 | 1733 | 1767 | 1684 | 1678 | 1667 | 1646 |
| 1769 | 1655 | 1748 | 1755 | 1682 | 1687 | 1656 | 1651 |
| 1782 | 1640 | 1741 | 1755 | 1696 | 1675 | 1666 | 1647 |


## 지난 경기들

* 2019 시즌 2
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


## 이 모형을 믿을 수 있는가?
2019년 시즌 1 결승전 16트랙 내내 신종민을 제외한 참가 선수들의 점수에 대체로 큰 변동이 없을 정도로 경험이 풍부한 선수들의 실력을 잘 추정함. 신인임에도 시즌 1 승자전에서 강력한 모습을 보여 우승 후보로 급부상했던 신종민의 경우 그 경기와 2019 시즌 2 16강 1회전에서 좋지 않은 모습을 보였던 경기 후를 제외하면 대체로 안정적인 점수대를 유지하고 있음.

* 2019년 승부예측 성공률: 
  * 상위 라운드 진출자 64% (47/74)
  * 1위 38% (8/21)
  * 해당 인원보다 1명 더 선택할 수 있을 때 성공률: 
    * 상위 라운드 진출자 70% (52/74)
    * 1위 62% (13/20)    
  * 예선이나 연방, 비방용 대회 성적, 게임 내 주행 정보를 전혀 고려하지 않았다는 점을 생각할 때 꽤 괜찮은 것으로 보임.

* 의견 및 게시글 환영합니다. 
    - 연락처: kart.rider.ranking a t  g m a i l (dot) c o m 
    - 또는 [이 페이지의 issue tracker](https://github.com/hiddenidol/KartRanking/issues)(github 계정 필요)
* 이 페이지의 자료를 사용 시 다음을 명시해 주세요.
```
https://github.com/hiddenidol/KartRanking
github: @hiddenidol
```
