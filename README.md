# 노코드 자동화 기초: 워크플로우 설계

Make · Zapier 등 노코드 자동화 도구로 **Trigger → (조건 분기) → Action** 워크플로우를 직접 구현하고, 도구를 비교 분석한 뒤 자유 주제 자동화까지 설계·구현한 과제입니다.

## 폴더 구조

```text
.
├── README.md                          # 이 문서 (개요 · 제출물 체크리스트)
├── project1-tool-comparison/          # [프로젝트 1] 자동화 도구 비교 구현
│   ├── README.md                      #   워크플로우 명세 + 도구별 구현 과정
│   ├── comparison-report.md           #   비교 분석 보고서
│   ├── make/screenshots/              #   Make 구성 · 실행 결과 캡처
│   └── zapier/screenshots/            #   Zapier 구성 · 실행 결과 캡처
├── project2-free-topic/               # [프로젝트 2] 자유 주제 자동화
│   ├── README.md                      #   업무 정의 · 도구 선정 이유 · 설계 문서
│   └── screenshots/                   #   구현 · 실행 결과 캡처
├── bonus/                             # [보너스] 선택
│   ├── ai-action/                     #   생성형 AI Action 추가
│   └── failure-handling/              #   실패 알림 · 재시도 전략
└── docs/
    ├── concepts.md                    # Trigger / Action / Filter·Router 개념 정리
    └── security-checklist.md          # 제출 전 민감정보 마스킹 점검표
```

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
