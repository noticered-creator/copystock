# COPYTRADING Architecture

Frontend → API/Auth → PostgreSQL
                         ↓
Official Broker API / Authorized Provider
                         ↓
Data Collector → Portfolio Calculator → Redis → WebSocket → Live Ranking

보안:
- HTTPS
- 민감 토큰 암호화
- 계좌번호/인증정보 비공개
- RBAC
- Audit Log
- Rate Limiting
- 환경변수/Secret Manager
