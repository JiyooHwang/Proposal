# 기획서 / 제안서 자동 생성기

기본 정보만 입력하면 정해진 포맷에 맞춰 기획서·제안서를 자동으로 만들어 주는 단일 HTML 도구입니다.
별도 설치·서버 없이 브라우저에서 바로 동작합니다.

---

## 🚀 바로 사용하기 (페이지 열어서 편집)

아래 링크 중 아무거나 클릭하면, 브라우저에서 도구가 바로 실행되어
**왼쪽 입력 폼 / 오른쪽 미리보기** 형태로 즉시 작성·편집할 수 있습니다.

- **▶ 라이브 프리뷰 (githack)** :
  https://raw.githack.com/JiyooHwang/Proposal/claude/modest-pascal-ZNq9l/index.html
- **▶ 라이브 프리뷰 (htmlpreview)** :
  https://htmlpreview.github.io/?https://github.com/JiyooHwang/Proposal/blob/claude/modest-pascal-ZNq9l/index.html

> `main` 브랜치로 병합한 뒤에는 위 URL의 `claude/modest-pascal-ZNq9l` 부분을 `main` 으로 바꾸면 됩니다.

### GitHub Pages 로 영구 배포하기 (선택)

1. GitHub 저장소 → **Settings → Pages** 진입
2. **Source** 를 `Deploy from a branch` 로 선택
3. Branch 를 `claude/modest-pascal-ZNq9l` (또는 `main`) / `/ (root)` 로 지정 후 Save
4. 1~2분 후 `https://jiyoohwang.github.io/Proposal/` 에서 접속 가능

### 로컬에서 사용

1. 저장소를 다운로드(`Code → Download ZIP`) 하거나 `git clone`
2. `index.html` 을 더블클릭 — 브라우저에서 바로 열립니다 (오프라인 가능).

---

## 📝 사용 방법

1. 왼쪽 폼에 기본 정보를 입력하면 오른쪽에 실시간으로 미리보기가 그려집니다.
2. 상단 버튼으로 다음 동작이 가능합니다.
   - **샘플 채우기** : 예시 데이터로 폼을 채워 결과 확인
   - **저장(JSON)** : 입력한 내용을 JSON 파일로 다운로드
   - **불러오기** : 저장된 JSON 을 다시 불러와 편집
   - **PDF/인쇄** : 브라우저 인쇄 기능으로 PDF 저장 또는 출력 (A4)
3. 입력 내용은 브라우저 로컬에 자동 저장되어 새로고침해도 유지됩니다.

## 입력 항목

- 문서 종류 (기획서 / 제안서 / 사업계획서 / 프로젝트 계획서)
- 제목, 작성자, 소속, 작성일
- 배경 / 목적
- 주요 목표, 주요 추진 내용
- 추진 기간 및 단계별 일정
- 총 예산 및 세부 내역
- 기대효과
- 결론 / 요청사항

## 출력 포맷

표지(제목·작성자·작성일) → 개요(표) → 목표 → 추진 내용 → 일정 → 예산 → 기대효과 → 결론 순으로 자동 구성됩니다.
