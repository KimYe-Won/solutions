
## 🔀 브랜치 운영 규칙 (중요)

본 스터디는 **main 브랜치 직접 작업을 금지**하고,  
**개인 브랜치 → PR → merge** 방식으로만 운영합니다.

### 1) 기본 원칙
- `main` 브랜치
  - 공용 기준 브랜치
  - 직접 작업 ❌
  - 직접 push ❌
- 개인 브랜치
  - 모든 작업은 개인 브랜치에서만 수행
  - PR을 통해서만 `main`에 반영

---

### 2) 개인 브랜치 사용 규칙 (현재 운영 방식)

각 스터디원은 **본인 이름의 단일 브랜치**를 사용합니다.

예시:
```text
hosung
alice
bob
````

> 초기 운영 및 테스트 단계에서는
> 브랜치 관리를 단순화하기 위해 **단일 개인 브랜치 방식**을 사용합니다.

---

### 3) 개인 브랜치 생성 방법

```bash
git checkout main
git pull origin main
git checkout -b hosung
git push -u origin hosung
```

이후 모든 작업은 항상 아래 상태에서 진행합니다.

```bash
git checkout hosung
```

---

### 4) PR 생성 규칙

* PR 생성 시 설정

  * base: `main`
  * compare: 개인 브랜치 (예: `hosung`)
* 리뷰 승인 후에만 `main`에 반영 가능
* `main` 브랜치에 직접 push하는 행위는 금지합니다.

---

### 5) PR 머지 후 필수 동기화 루틴

PR이 `main`에 머지된 이후,
다음 작업을 시작하기 전에 **반드시 아래 과정을 수행합니다.**

```bash
git checkout main
git pull origin main
git checkout hosung
git merge main
```

> 이 과정을 생략하면
> 다음 PR에서 변경 내역이 꼬이거나 불필요한 diff가 발생할 수 있습니다.

---

