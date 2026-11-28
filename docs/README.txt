# PRJ-0021 다채널 재고 동기화 — 모바일 컨셉 산출물

## 포함 파일
- `PRJ-0001_API-설계서_v1.0.docx`
- `PRJ-0001_UI-설계서_v1.0.docx`
- `PRJ-0001_기능정의서_v1.0.docx`
- `PRJ-0001_디자인-시스템_v1.0.docx`
- `mobile-concept.html`

## 실행
`mobile-concept.html`을 브라우저에서 열면 별도 빌드 없이 모바일 컨셉을 확인할 수 있습니다.

## 범위 및 주의
이 산출물은 GitHub `jeong-jihyun/multichannel-inventory-sync`의 README, `inventory_sync/core.py`, `inventory_sync/cli.py`, `sample/config.json`, `sample/stock.csv`, `tests/test_all.py`, `docs/design.md`, `CLAUDE.md`를 기준으로 작성했습니다.
현재 구현은 SQLite 기반 Python 엔진입니다. 실제 쇼핑몰 API 인증·재고 수정·웹훅 수신, SaaS 계정/결제, 실제 HTTP API, UI는 구현되어 있지 않습니다. HTML은 브라우저 내 상태 변경을 보여주는 독립형 컨셉 프로토타입이며 실제 서버나 판매 채널과 통신하지 않습니다.
