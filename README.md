# 2025-EWHA-CAPSTONE-DROPTHE8BIT
2025-1 캡스톤디자인과창업프로젝트 8팀

## 🛠️ 프로젝트 Convention

## ✅ Branch

### Branch 생성

#### 🔹 `feature`
- 형식: `feature/엔티티명`
- 예시: `feature/kakaoLogin`

#### 🔹 기타 브랜치
- 형식: `issue_name/issue_number-이슈명`
- 예시: `chore/12-env-setting`

### Branch 전략

| Branch 이름 | 용도 |
|-------------|------|
| `main` | 실제 배포용 CI/CD 브랜치 |
| `develop` | 개발용 CI/CD 브랜치 |
| `feature` | 기능 개발 브랜치 |
| `chore` | 기본 설정, 의존성, yml 등 기타 작업 브랜치 |
| `fix` | 버그 수정 브랜치 |
| `refactor` | 리팩토링 브랜치 (기능 변화 없음) |
| `reconstruct` | 프로젝트 구조 재정립 브랜치 |
| `test` | 테스트 코드 작성 브랜치 |

---
## ✅ PR

### PR Template

```md
## 연관 이슈

close #이슈번호

<br/>

## 개요

<!-- 이 PR을 간략하게 설명해주세요. -->

<br/>

## ✅ 작업 내용

- [ ] 작업 내용 1
- [ ] 작업 내용 2
- [ ] 작업 내용 3

<br/>

### 📝 논의사항

<!-- 이 PR에 대한 논의하고 싶은 사항이나, 더 해야할 작업, 리뷰어에게 특별히 확인 요청하고 싶은 부분 등을 적어주세요. -->
```
### PR Title 규칙
- 형식: `[issue_name] content`  
    - 예시: `[chore] 환경 세팅`

### PR 세부사항
- 기본 merge 대상 브랜치: `develop`
- 병합 전 최소 1명 이상의 리뷰 승인(Approve) 필수

---

## ✅ Commit

### Commit 메시지 전략

- 형식: `[issue_name] content #issue_number`  
  예시: `[chore] 환경 세팅 #12`

| 커밋 유형 | 설명 |
|-----------|------|
| `build` | 빌드 및 외부 종속성 관련 변경 |
| `chore` | 기타 수정 (예: `.gitignore`) |
| `ci` | CI 설정 또는 스크립트 변경 |
| `comment` | 주석 추가/업데이트 |
| `docs` | 문서 수정 (예: `README.md`) |
| `feat` | 새로운 기능 추가 |
| `fix` | 버그 수정 |
| `hotfix` | 긴급 수정 |
| `move` | 파일/경로 이동 또는 이름 변경 |
| `release` | 릴리즈 관련 |
| `refactor` | 리팩토링 (기능 변화 없음) |
| `style` | 코드 스타일 변경 (포매팅 등) |
| `test` | 테스트 코드 추가/수정 |
| `ui` | UI/스타일 변경 (예: `.css`) |


