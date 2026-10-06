# COPYTRADING

GitHub Pages로 즉시 공개할 수 있는 COPYTRADING MVP.

## 배포
1. 이 폴더의 내용물을 GitHub Repository의 `main`에 업로드
2. Repository → Settings → Pages → Source: **GitHub Actions**
3. `main`에 push하면 `.github/workflows/deploy.yml`이 자동 배포

기본 주소:
`https://YOUR-GITHUB-ID.github.io/copytrading/`

## 포함 기능
- 투자자 리더보드
- 실시간 데모 수익률/시계
- 투자자 상세/포트폴리오
- 증권사 선택 및 계좌 연결 데모
- 로그인 데모
- 공개 권한 설정
- 관리자 화면
- 반응형 UI

## 실제 서비스 확장
GitHub Pages는 정적 프런트엔드입니다. 실제 계좌/금융 데이터를 다루려면 별도 백엔드와 공식 증권사 API 또는 승인된 금융데이터 연계가 필요합니다.
