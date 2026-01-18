# Coding Test Study (GitHub PR 기반 운영)

본 스터디는 **GitHub Organization + Fork → PR** 기반으로 운영되는 코딩 테스트 스터디입니다.  
목표는 “혼자서는 꾸준히 하기 어려운 코딩테스트 학습”을 **주간 루틴 + 리뷰 시스템**으로 끝까지 완주하는 것입니다.

---

## 1) 스터디 기본 조건

- 총 인원: 11명
- 그룹 구성
  - **GroupA (5명): 1·2팀 통합**
  - **GroupB (6명): 3팀**
- 주간 과제: **주당 5문제**
- 제출 방식: **Fork → PR**
- PR 병합 조건: **승인 3명 필수**
- 운영자 포함 누구든 **main 직접 push 금지** (PR로만 반영)

---

## 2) 제출 폴더 구조 (강제)

반드시 아래 경로로 제출합니다.

- GroupA  
  `submissions/groupA/{GitHubID}/Wxx/`

- GroupB  
  `submissions/groupB/{GitHubID}/Wxx/`

예시:
- `submissions/groupA/hoseong123/W01/boj_1234.java`
- `submissions/groupB/helloDev/W03/pgs_150368.py`

> 폴더 구조가 틀리면 CODEOWNERS 경로 규칙이 깨져 리뷰 자동 요청이 누락될 수 있습니다.

---

## 3) PR 리뷰 방식(핵심)

- PR이 올라오면 **그룹 전체(team)에 자동 리뷰 요청**이 갑니다.
- 그중 **아무나 3명이 승인하면 merge 가능합니다.**
- “랜덤으로 2명만 지정” 방식은 사용하지 않습니다.
- 리뷰가 특정인에게 쏠리지 않게, 매주 각자 최소 2개 이상 리뷰를 권장합니다.

---

## 4) 15주 커리큘럼

- 1주  자료구조
- 2주  브루트포스
- 3주  재귀 + 백트래킹
- 4주  분할정복 + 정렬
- 5주  이분탐색 + 파라메트릭 서치
- 6주  그리디
- 7주  다이나믹 프로그래밍
- 8주  그래프 + DFS/BFS
- 9주  최단 경로
- 10주 서로소 집합 + MST
- 11주 시뮬레이션
- 12주 실전 기출(삼성, 카카오)
- 13주 취약 유형(DP, 이분탐색)
- 14주 취약 유형(BFS/DFS, 시뮬레이션)
- 15주 취약 유형(구현, 그리디)
- 16주~ 랜덤 문제

---

## 5) 운영 규칙 요약

- 매주 5문제 풀이 후 PR 제출
- PR 제목 규칙 권장:  
  `[W01][GroupA] {GitHubID} - 5 problems`
- 리뷰 승인 3명 완료 후 merge
- merge는 squash merge 권장 (히스토리 깔끔하게 유지)

자세한 규칙/제출법은 아래 문서를 참고하세요.
- `docs/rules.md`
- `docs/how-to-submit.md`
- `docs/review-checklist.md`

---

## 6) 참고 레포

아래 레포의 운영 방식을 참고합니다.
https://github.com/2023-Coding-Test-Study/Coding-Test-Study
