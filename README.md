# 네오봇 수학 에너지 주행 — 출발 저장소

연수용 출발점입니다. 원본: https://github.com/i20091119-ai/2026.neobot (주행 부분만 추림)

## 시작
1. github.com/i20091119-ai/2026.aistarter → Use this template → 이름 `neobot-내이름`
2. Claude Code로 열기 → "CLAUDE.md 읽고 이 앱 구조 설명해 줘"
3. `js/my-problems.js`에 내 반 문제 10개
4. "계획부터 보여 줘" → 허락 → 수정 → 확인
5. "커밋하고 푸시해 줘" → Settings → Pages → Branch: main → Save
6. 주소: `https://아이디.github.io/neobot-내이름/`

## 로봇 연결
동글 USB → 로봇 ① Coding 모드 → 크롬·엣지로 열기 → 로봇 연결 → CP210x 선택. 엔트리 연결 프로그램 종료.
안 되면 `test.html`.

## 파일
| 파일 | 역할 |
|---|---|
| index.html | 첫 화면 |
| drive.html + js/drive.js | 주행 — 에너지·코인·속도 규칙 |
| js/my-problems.js | ★ 내 문제 |
| js/problems.js | 학년별 기본 문제 (초1~중3) |
| js/neobot.js | 로봇 통신 (수정 금지) |
| PROTOCOL.md | 명령 구조 |
| CLAUDE.md | Claude Code 규칙 |
