# 자바스크립트로 알아보는 알고리즘

## 목차

### 주제별 알고리즘

- Math

  - Bit Manipulation - set/get/update/clear bits, 2의 곱 / 나누기, 음수로 만들기 etc.
  - 팩토리얼
  - 피보나치 수
  - 소수 판별 (trial division 방식)
  - 유클리드 호제법 - 최대공약수 (GCD)
  - 최소 공배수 - LCM
  - 에라토스테네스의 체 - 특정수 이하의 모든 소수 찾기
  - 2의 거듭제곱 판별법 - 어떤 수가 2의 거듭제곱인지 판별 (naive 와 bitwise 알고리즘)
  - 파스칼 삼각형
  - 자연수 분할
  - 리우 후이 π 알고리즘 - N-각형을 기반으로 π 근사치 구하기

- Sets

  - 카티지언 프로덕트
  - 곱집합
  - Fisher–Yates 셔플
  - 유한 시퀀스의 무작위 순열
  - 멱집합
  - 집합의 모든 부분집합
  - 순열 (반복 유,무)
  - 조합 (반복 유,무)
  - 최장 공통 부분수열 (LCS)
  - 최장 증가 수열
  - Shortest Common Supersequence (SCS)
  - 배낭 문제 - "0/1" 과 "Unbound"
  - 최대 구간합 - "브루트 포스" 과 "동적 계획법" (Kadane's) 버전
  - 조합 합
  - 특정 합을 구성하는 모든 조합 찾기

- Strings

  - 해밍 거리
  - 심볼이 다른 위치의 갯수
  - 편집 거리
  - 두 시퀀스 간위 최소 편집거리
  - 커누스-모리스-프랫 알고리즘 (KMP 알고리즘)
  - 부분 문자열 탐색 (패턴 매칭)
  - Z 알고리즘 - 부분 문자열 탐색 (패턴 매칭)
  - 라빈 카프 알고리즘
  - 부분 문자열 탐색
  - 최장 공통 부분 문자열
  - 정규 표현식 매칭

- Searches

  - 선형 탐색
  - 점프 탐색 (or Block Search)
  - 정렬된 배열에서 탐색
  - 이진 탐색
  - 정렬된 배열에서 탐색
  - 보간 탐색
  - 균등한 분포를 이루는 정렬된 배열에서 탐색

- Sorting
  - 거품 정렬
  - 선택 정렬
  - 삽입 정렬
  - 힙 정렬
  - 병합 정렬
  - 퀵 정렬
  - 제자리(in-place)와 제자리가 아닌(non-in-place) 구현
  - 셸 정렬
  - 계수 정렬
  - 기수 정렬
- Trees
  - 깊이 우선 탐색 (DFS)
  - 너비 우선 탐색 (BFS)
- Graphs
  - 깊이 우선 탐색 (DFS)
  - 너비 우선 탐색 (BFS)
  - 크루스칼 알고리즘
  - 최소 신장 트리 찾기 (MST) 무방향 가중 그래프
  - 다익스트라 알고리즘
  - 한 점에서 다른 모든 점까지 최단 거리 찾기
  - 벨만-포드 알고리즘
  - 한 점에서 다른 모든 점까지 최단 거리 찾기
  - 플로이드-워셜 알고리즘
  - 모든 종단 간의 최단거리 찾기
  - 사이클 탐지
  - 유방향, 무방향 그래프 (DFS 와 Disjoint Set 에 기반한 버전)
  - 프림 알고리즘
  - 무방향 가중치 그래프에서 최소 신장 트리 (MST) 찾기
  - 위상 정렬
  - DFS 방식
  - 단절점
  - 타잔의 알고리즘 (DFS 기반)
  - 단절선
  - DFS 기반 알고리즘
  - 오일러 경로 와 오일러 회로
  - Fleury의 알고리즘
  - 모든 엣지를 한번만 방문
  - 해밀턴 경로
  - 모든 꼭짓점을 한번만 방문
  - 강결합 컴포넌트
  - Kosaraju의 알고리즘
  - 외판원 문제
  - 각 도시를 다 방문하고 다시 출발점으로 돌아오는 최단 경로 찾기
- Uncategorized
  - 하노이 탑
  - 정방 행렬 회전
  - 제자리(in-place) 알고리즘
  - 점프 게임
  - 백트래킹, 동적계획법 (top-down + bottom-up), 탐욕 알고리즘 예제
  - Unique 경로
  - 백트래킹, 동적계획법, 파스칼 삼각형에 기반한 예제
  - 빗물 담기 문제
  - trapping rain water problem (동적계획법, 브루트포스 버전)
  - N-Queens 문제
  - 기사의 여행 문제

### 패러다임별 알고리즘

- 브루트 포스(Brute Force)
  - 가능한 모든 경우를 탐색한 뒤 최적을 찾아내는 방식
  - 선형 탐색
  - 빗물 담기 문제
  - trapping rain water problem
  - 최대 구간합
  - 외판원 문제
  - 각 도시를 다 방문하고 다시 출발점으로 돌아오는 최단 경로 찾기
- 탐욕 알고리즘(Greedy)
  - 점프 게임
  - 쪼갤수 있는 배낭 문제
  - 다익스트라 알고리즘
  - 모든 점 까지의 최단거리 찾기
  - 프림 알고리즘
  - 무방향 가중치 그래프에서 최소 신창 트리 (MST) 찾기
  - 크루스칼 알고리즘
  - 무방향 가중치 그래프에서 최소 신창 트리 (MST) 찾기
- 분할 정복법(Divide and Conquer)
  - 이진 탐색
  - 하노이 탑
  - 파스칼 삼각형
  - 유클리드 호제법
  - 최대공약수 계산 (GCD)
  - 병합 정렬
  - 퀵 정렬
  - 트리 깊이 우선 탐색 (DFS)
  - 그래프 깊이 우선 탐색 (DFS)
  - 점프 게임
  - 순열 (반복 유,무)
  - 조합 (반복 유,무)
- 동적 계획법(Dynamic Programming)
  - 피보나치 수
  - 점프 게임
  - Unique Paths
  - 빗물 담기 문제
  - trapping rain water problem
  - 편집 거리
  - 두 시퀀스 간의 최소 편집 거리
  - 최장 공통 부분 수열 (LCS)
  - 최장 공통 부분 문자열
  - 최장 증가 수열
  - Shortest Common Supersequence
  - 0/1 배낭 문제
  - 자연수 분할
  - 최대 구간합
  - 벨만-포드 알고리즘
  - 모든 점 까지의 최단 거리 찾기
  - 플로이드-워셜 알고리즘
  - 모든 종단 간의 최단거리 찾기
  - 정규 표현식 매칭
- 백트래킹(Backtracking)
  - 점프 게임
  - Unique Paths
  - 해밀턴 경로
  - 모든 점을 한번씩 방문
  - N-Queens 문제
  - 기사의 여행
  - 조합 합
  - 특정 합을 구성하는 모든 조합 찾기

## 출처

- [한글 번역판](https://github.com/trekhleb/javascript-algorithms/blob/master/README.ko-KR.md) of [JavaScript Algorithms and Data Structures](https://github.com/trekhleb/javascript-algorithms) by [@trekhleb](https://trekhleb.dev/)
