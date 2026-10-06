# Backend 준비 영역

권장: Node.js/NestJS + PostgreSQL + Redis + WebSocket + BullMQ.

주요 도메인:
users, investors, broker_connections, accounts, holdings,
portfolio_snapshots, market_quotes, ranking_snapshots,
disclosure_policies, disclosure_permissions, followers, audit_logs, sync_jobs.

증권사 비밀번호를 저장하거나 웹사이트를 스크래핑하지 않고,
공식 API/승인된 데이터 연계 방식을 사용합니다.
