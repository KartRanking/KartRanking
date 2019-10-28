# KartRanking

카트라이더 리그 개인전 8인제 Elo 랭킹. (ver. 0.2)

최근 경기: 2019년 시즌 2 승/패자전

| 순위 | 이름 | 점수 | 점수변화 |
|---:|:---:|---:|---:|
|  1 |   문호준 | 1811 |  -55 |
|  2 |   유창현 | 1808 |    0 |
|  3 |   박인수 | 1800 |   -7 |
|  4 |   전대웅 | 1789 |   20 |
|  5 |   황인호 | 1763 |   26 |
|  6 |   이재혁 | 1753 |    7 |
|  7 |   신동이 | 1738 |    0 |
|  8 |   박도현 | 1737 |   20 |
|  9 |   정승하 | 1736 |    0 |
| 10 |   김승래 | 1703 |   -8 |
| 11 |   송용준 | 1698 |    0 |
| 12 |   김승태 | 1694 |    0 |
| 13 |   유영혁 | 1679 |    1 |
| 14 |   문민기 | 1671 |    0 |
| 15 |   김기수 | 1660 |   36 |
| 16 |   최윤서 | 1659 |   46 |
| 17 |   박현수 | 1656 |   22 |
| 18 |   이준성 | 1656 |  -13 |
| 19 |   최영훈 | 1652 |   -8 |
| 20 |   손우현 | 1647 |    0 |
| 21 |   김정제 | 1646 |    0 |
| 22 |   양민규 | 1642 |   -1 |
| 23 |   김응태 | 1632 |    0 |
| 24 |   신종민 | 1625 |  -40 |
| 25 |   이건욱 | 1620 |    0 |
| 26 |   임재원 | 1616 |    0 |
| 27 |   배성빈 | 1612 |   -4 |
| 28 |   윤정현 | 1610 |    0 |
| 29 |   박병선 | 1604 |    0 |
| 30 |   조성제 | 1603 |    0 |
| 31 |   이중선 | 1598 |    0 |
| 32 |   한상현 | 1595 |    0 |
| 33 |   김경모 | 1595 |    0 |
| 34 |   이준용 | 1595 |    0 |
| 35 |   문진형 | 1593 |    0 |
| 36 |   이재인 | 1593 |    0 |
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

방법: Elo rating에 기반한 방법, https://fivethirtyeight.com/features/formula-one-racing/ 에서 F1 레이싱에 적용한 방법과 비슷한 방법을 사용함. 한 트랙이 끝나면 1위는 7승 0패, 2위는 6승 1패, ..., 8위는 0승 7패를 한 것으로 계산하여 점수를 한번에 업데이트. 한번에 변할 수 있는 점수의 양을 제어하는 파라미터 "K"가 있는데, 여기서는 50점제 1-3번째 경기인 선수는 10, 4-5번째 경기인 선수는 7, 6번째 이상인 선수는 5를 사용함. (v0.1에서는 1-3번째 경기인 선수는 16, 4번째 이후인 선수는 8을 사용했는데, 분석해 보니 점수의 변화폭이 너무 컸음.)

자료: 2016년 듀얼레이스 1 이후 모든 개인전 8인전 방송 경기 (2017 케스파 컵과 듀얼레이스 X 포함, 티밍이 있었던 글로벌 슈퍼매치 제외)


### 다음 라운드 승부예측 (16강 최종전, 100,000회의 몬테 카를로 시뮬레이션)

|   | 이재혁 | 전대웅 | 박도현 | 황인호 | 배성빈 | 신종민 | 최영훈 | 박현수 |
|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 1위 | 14.709 | 19.437 | 17.764 | 18.267 | 8.404 | 8.869 | 8.362 | 6.721 |
| 2위 | 14.63 | 16.961 | 14.936 | 16.128 | 10.531 | 11.155 | 10.721 | 9.106 |
| 3위 | 14.046 | 14.464 | 13.1 | 14.467 | 11.554 | 12.014 | 11.501 | 10.602 |
| 4위 | 13.394 | 13.116 | 12.151 | 13.14 | 12.549 | 12.537 | 12.325 | 11.813 |
| 5위 | 12.686 | 11.392 | 11.276 | 11.752 | 13.236 | 13.233 | 13.198 | 12.918 |
| 6위 | 11.462 | 9.943 | 10.962 | 10.418 | 13.85 | 13.713 | 14.049 | 14.497 |
| 7위 | 10.407 | 8.322 | 10.014 | 9.067 | 14.881 | 14.052 | 14.614 | 16.003 |  
| 8위 | 8.666 | 6.365 | 9.797 | 6.761 | 14.995 | 14.427 | 15.23 | 18.34 |
| 진출 | 56.779 | 63.978 | 57.951 | 62.002 | 43.038 | 44.575 | 42.909 | 38.242 |


### 경기 중 포인트 변화
#### 승자전
|    박인수 |    전대웅 |    이재혁 |    박도현 |    황인호 |    문호준 |    김기수 |    유영혁 |
| ------:| ------:| ------:| ------:| ------:| ------:| ------:| ------:|
| 1800 | 1789 | 1753 | 1737 | 1763 | 1811 | 1660 | 1679 |
| 1810 | 1769 | 1770 | 1714 | 1759 | 1815 | 1656 | 1685 |
| 1824 | 1760 | 1766 | 1732 | 1741 | 1824 | 1667 | 1676 |
| 1807 | 1777 | 1778 | 1699 | 1749 | 1817 | 1677 | 1673 |
| 1786 | 1793 | 1789 | 1690 | 1757 | 1816 | 1679 | 1664 |
| 1797 | 1773 | 1784 | 1701 | 1744 | 1820 | 1673 | 1686 |
| 1806 | 1774 | 1769 | 1701 | 1726 | 1833 | 1690 | 1682 |
| 1811 | 1760 | 1751 | 1711 | 1720 | 1846 | 1691 | 1698 |
| 1825 | 1752 | 1733 | 1691 | 1729 | 1843 | 1713 | 1699 |
| 1838 | 1739 | 1716 | 1722 | 1733 | 1835 | 1705 | 1709 |

#### 패자전
|    최영훈 |    최윤서 |    김승래 |    박현수 |    배성빈 |    양민규 |    이준성 |    신종민 |
| ------:| ------:| ------:| ------:| ------:| ------:| ------:| ------:|
| 1652 | 1659 | 1703 | 1656 | 1612 | 1642 | 1656 | 1625 |
| 1644 | 1633 | 1698 | 1659 | 1631 | 1618 | 1663 | 1639 |
| 1642 | 1660 | 1703 | 1675 | 1615 | 1603 | 1655 | 1642 |
| 1660 | 1653 | 1692 | 1676 | 1604 | 1582 | 1667 | 1650 |
| 1672 | 1628 | 1682 | 1677 | 1624 | 1563 | 1673 | 1647 |
| 1683 | 1635 | 1668 | 1668 | 1608 | 1594 | 1669 | 1655 |
| 1668 | 1621 | 1674 | 1649 | 1623 | 1595 | 1686 | 1657 |
| 1655 | 1659 | 1665 | 1652 | 1637 | 1609 | 1666 | 1654 |
| 1672 | 1643 | 1651 | 1649 | 1645 | 1630 | 1647 | 1656 |
| 1673 | 1639 | 1634 | 1662 | 1663 | 1614 | 1640 | 1663 |
| 1674 | 1655 | 1627 | 1658 | 1674 | 1592 | 1628 | 1680 |




* [2019 시즌 2 16강 1회전](./rounds/2019_2_3.md)
* [2019 시즌 2 32강 패자부활전](./rounds/2019_2_2.md)
* [2019 시즌 2 32강 1회전](./rounds/2019_2_1.md)
* [2019 시즌 1 결승전]
* [2019 시즌 1 16강 최종전]
* [2019 시즌 1 16강 승/패자전]
* [2019 시즌 1 16강 1회전]
* [2019 시즌 1 32강 패자부활전]
* [2019 시즌 1 32강 1회전]

* 아직 초기 버전이라 이번 오프시즌에 수정이 가해질 수 있음.
* 박현수: 샌드박스 소속.
* 박현수B: 범스 소속으로 나왔던 박현수.

* contact: kart.rider.ranking a t  g m a i l (dot) c o m
