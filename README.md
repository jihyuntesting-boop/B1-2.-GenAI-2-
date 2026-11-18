# 노코드 자동화 기초: 워크플로우 설계

Make · Zapier 등 노코드 자동화 도구로 **Trigger → (조건 분기) → Action** 워크플로우를 직접 구현하고, 도구를 비교 분석한 뒤 자유 주제 자동화까지 설계·구현한 과제입니다.

## 폴더 구조

```text
.
├── README.md
├── .gitignore
├── project1-tool-comparison/
│   ├── README.md
│   ├── comparison-report.md
│   ├── make/
│   │   └── screenshots/
│   │       ├── 01-scenario-overview.jpg
│   │       ├── 03-run-pass.jpg
│   │       └── 04-run-fail.jpg
│   └── zapier/
│       └── screenshots/
│           ├── 01-zap-overview.jpg
│           ├── 03-run-pass.jpg
│           ├── 04-run-fail.jpg
│           └── 05-history.jpg
├── project2-free-topic/
│   ├── README.md
│   └── screenshots/
│       ├── 01-scenario-overview.jpg
│       └── 03-trigger-auto-run-history.jpg
├── bonus/
│   ├── README.md
│   ├── ai-action/
│   └── failure-handling/
└── docs/
    ├── concepts.md
    └── security-checklist.md
```

## 진행 상태

| 항목 | 상태 |
|---|---|
| 프로젝트 1 – Make 구현·실행(pass/fail 두 경로) | ✅ |
| 프로젝트 1 – 2번째 도구(Zapier) 구현·실행(Path A/B 두 경로) | ✅ (14일 체험판 사용) |
| 프로젝트 1 – 비교 보고서 | ✅ 작성 (비교 7항목, 장단점, 유료 기능 사유) |
| 프로젝트 2 – Make 자동 실행(Active, Instant)·필터 통과/차단 | ✅ |
| 프로젝트 2 – Slack 전송 · 시트 이력 | ⏳ 미구현 (README "한계" 참고) |
| 보너스 | ⏳ 미수행 |

## 제출물 체크리스트

### 프로젝트 1 — 도구 비교 구현
- [ ] 동일 워크플로우를 2개 이상 도구로 구현 (Trigger 1+, Action 2+, 분기 1+)
- [ ] 도구별 워크플로우 구성 화면 캡처
- [ ] 도구별 실행 결과 캡처 (**분기 경로마다 1회 이상 실행**)
- [ ] 비교 분석 보고서 (비교 항목 5개 이상, 장단점, 적합 상황)

### 프로젝트 2 — 자유 주제
- [ ] 반복 업무 1개 정의
- [ ] 도구 1개 선정 + 선정 이유
- [ ] 워크플로우 설계 문서 (설명 + 다이어그램)
- [ ] 구현 화면 · 실행 결과 캡처
- [ ] Trigger 발생 시 **자동 실행** 확인

### 공통
- [ ] 스크린샷 · 문서에 API Key / 토큰 / 비밀번호 노출 없음 ([점검표](docs/security-checklist.md))
- [ ] 계정 이메일 일부 마스킹

### 보너스 (선택)
- [ ] AI 연동 Action (요약 · 분류 · 템플릿 메시지)
- [ ] 실패 알림 + 재시도/대체 경로

## 학습 목표

- Trigger와 Action의 개념 설명
- 조건 분기(Filter/Router)의 역할 설명
- 도구별 특징 비교, 업무에 맞는 도구 선택 근거 설명
- 자동화 흐름을 단계별로 설명

개념 정리는 [docs/concepts.md](docs/concepts.md) 참고.
