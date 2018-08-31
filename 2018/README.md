# NYPC 2018 예선

## 문제 목록
체크된 문제는 만점, 체크 안된 문제는 0점이거나 부분점수
### 연습 문제
- [x] 78 89 80 67 (100p)
- [x] HELLO NEXON (100p)
### 실제 문제
- [x] 아이템 구매 (100p)
- [x] 승리팀 찾기 (100p)
- [x] 줄임말 (100p)
- [] 우물왕 김배찌 (100p)
- [x] 최고의 동접 구간을 찾아라! (100p)
- [] 버튼 게임 (100p)
- [] 이진 트리 (100p)
- [x] 캐릭터 경험치 (100p)
- [] 전염병 역학 조사 (100p)
- [] 강력한 한방, 필살기 (100p)
- [] 회전 격자판 (150p)
- [] 블록 숫자 (150p)
- [] Flood-it (150p)
- [] 쉴드 생성기 (200p)
- [] 퍼즐 콤보 (200p)
- [] 피파 온라인 드리블 튜토리얼 (200p)
- [] 종이접기 (200p)
- [] 봇탐지 (250p)
- [] 금 줄 게임 (250p)
- [] 보라색 영역 (250p)

#### 아이템 구매
왜인지는 모르겠는데 대회 끝나고 나니까 코드가 사라졌다.. 그냥 간단하게 반복문으로 구현했던 것같다.
#### 승리팀 찾기 (`winner.cpp`)
구조체에 입력받은 뒤 빨리 들어온 순서대로 정렬해서 아이템전이면 0번에 있는 팀이 이기고 스피드 전이면 각각 숫위별 점수를 계산하면 된다.
#### 줄임말 (`julimmal.py`)
파이썬으로 쉽게 풀 수 있었다. 띄어쓰기 기준으로 나눠서 각 첫번째 글자를 출력하면 된다.
#### 우물왕 김배찌 (`point.cpp`)
수학을 잘 못해서 그냥 각 점들 좌표값의 평균구해서 출력해봤더니 6점 받았다.
#### 최고의 동접 구간을 찾아라! (`multi.cpp`)
각 시간을 모두 초로 환산해서 배열에 카운트하면서 최대값 구하면 된다.
#### 버튼 게임 (`button.cpp`)
간단하게 DP로 풀었더니 TLE 때문에 부분 점수 받았다.
#### 이진 트리 (`binarytree.cpp`)
N=k인 TC만 풀었다.2<sup>k</sup> % 1000000007을 구하면 된다.
#### 캐릭터 경험치 (`exp.cpp`)
조금 까다로웠던 DP였다. 최대 경험치까지 구한 다음에 재귀함수로 경로 찾아서 출력 하면된다.
#### 전염병 역학 조사 (`disease.cpp`)
Network Flow로 풀릴 것같았는데 다 까먹어서 못풀었다. TC 1만 풀었다.
#### 강력한 한방, 필살기
구현을 어떻게 할지 감도 안와서 포기했다..
#### 회전 격자판 (`grid.cpp`)
처음 봤을떄는 이렇게 쉬운 문제가 150점이나?? 했는데 T의 범위를 보고 이해했다. TC 1만 풀어서 100점 받았다.
#### 블록 숫자 (`block.cpp`)
재귀 함수로 풀었다. TC 1 먼저 풀고 나머지 TC도 풀리게 해보려고 했는데 너무 까다로워서 실패했다.
#### Flood-it (`floodit.py`)
흔한 ?? 문제인데 알고리즘 이름이 기억 안난다.. 많은 사람들이 이 문제를 보자마자 바로 떠올릴 그 알고리즘으로 풀었다.
#### 쉴드 생성기
구현을 어떻게 할지 감도 안와서 포기했다..
#### 퍼즐 콤보 (`puzzle.py`)
문제 그대로 구현해서 70점짜리 TC 1만 풀었다.
#### 이 뒤로는 아무 문제도 풀지 못했습니다..