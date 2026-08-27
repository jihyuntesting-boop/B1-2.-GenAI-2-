# 🌙 BLOOM — AI 브랜드 광고 프로젝트

AI 도구를 활용하여 제작한 **BLOOM 수면 개선 아로마 디퓨저 브랜드 광고 영상** 프로젝트입니다.

## 📌 프로젝트 개요

- **브랜드:** BLOOM (블룸)
- **제품:** AI 수면 개선 아로마 디퓨저
- **타겟:** 25~35세 1인 가구 직장인
- **광고 길이:** 9초
- **메인 영상:** 16:9
- **보너스 영상:** 9:16 숏폼
- **핵심 메시지:**  
  **“잠들기 위해 애쓰지 마세요. 향이 알아서 재워줄 테니까.”**

## 🎬 광고 콘셉트

불면으로 잠들지 못하는 상황에서 BLOOM이 등장하고,
사용자의 수면 리듬에 맞춰 향을 조절하여 편안한 수면으로 이어지는 과정을
짧은 영상 안에 표현했습니다.

### 스토리 흐름

**불면 → BLOOM 등장 → 편안한 수면 → 브랜드 인지**

영상의 색감도 **차가운 쿨톤에서 따뜻한 웜톤으로 전환**하여
불면에서 편안한 수면으로 변화하는 감정을 시각적으로 표현했습니다.

## 🎞️ Storyboard

| Scene | 내용 | 길이 |
|---|---|---:|
| Scene 1 | 잠들지 못하는 밤 | 2초 |
| Scene 2 | BLOOM 등장 및 분위기 전환 | 2초 |
| Scene 3 | 편안하게 잠든 모습 | 3초 |
| Scene 4 | 로고 + 슬로건 + CTA | 2초 |
| **Total** | | **9초** |

## 🤖 사용한 AI 도구

| 분야 | 사용 도구 | 활용 |
|---|---|---|
| 기획·카피 | ChatGPT | 브랜드 콘셉트, 카피, 스토리보드, 프롬프트 설계 |
| 이미지 생성 | DALL-E 3 | 씬별 키비주얼 제작 |
| 영상 생성 | Runway / Pika | 이미지 기반 모션 생성 |
| 음성 생성 | ElevenLabs | 광고 나레이션 및 음성 생성 |
| BGM 생성 | Suno | 광고용 배경음악 제작 |
| 최종 편집 | CapCut | 영상 연결, 자막, 오디오, 화면 비율 편집 |

## 🛠️ 제작 과정

```text
기획
 ↓
ChatGPT
 ↓
씬별 이미지 생성
 ↓
DALL-E 3
 ↓
이미지 → 영상 변환
 ↓
Runway / Pika
 ↓
음성 + BGM 생성
 ↓
ElevenLabs + Suno
 ↓
통합 편집
 ↓
CapCut
 ↓
16:9 / 9:16 최종 출력
```

## 📱 최종 영상

### 16:9 Main

- 해상도: 1920 × 1080
- 길이: 9초
- 코덱: H.264 / AAC

### 9:16 Short-form

- 해상도: 1080 × 1920
- 길이: 9초
- 코덱: H.264 / AAC
- 활용 플랫폼: YouTube Shorts / Instagram Reels / TikTok

## 📂 파일 구조

```text
BLOOM_AI_Advertising/
│
├── README.md
├── BLOOM_AI_Advertising_Storyboard.md
├── BLOOM_AI_Advertising_Storyboard.pdf
│
├── BLOOM_ad_16x9.mp4
├── BLOOM_ad_9x16.mp4
│
├── assets/
│   ├── s1_img.png
│   ├── s1_motion.mp4
│   ├── s1_audio.mp3
│   ├── s2_img.png
│   ├── s2_motion.mp4
│   ├── s2_audio.mp3
│   ├── s3_img.png
│   ├── s3_motion.mp4
│   ├── s3_audio.mp3
│   ├── s4_img.png
│   ├── s4_outro.mp4
│   └── s4_audio.mp3
│
└── bonus/
    └── BLOOM_ad_9x16.mp4
```

## 📄 상세 문서

전체 스토리보드, 씬별 프롬프트, 프롬프트 수정 전·후 비교,
AI 도구 선택 이유 및 경쟁 도구 비교 내용은 아래 문서에서 확인할 수 있습니다.

**[BLOOM_AI_Advertising_Storyboard.md](./BLOOM_AI_Advertising_Storyboard.md)**

## ✨ 핵심 결과

본 프로젝트는 AI를 활용하여

**기획 → 이미지 생성 → 영상 생성 → 음성·BGM 생성 → 편집 → 플랫폼별 출력**

까지의 전체 광고 제작 과정을 구현했습니다.

특히 9초라는 짧은 시간 안에 **문제 제시 → 해결 → 브랜드 인지**의
기승전결을 구성하고, 마지막 2초에 **BLOOM 로고 + 슬로건 + CTA**를 배치하여
브랜드 인지를 강화했습니다.

> **BLOOM — 향이 재워주는 밤**  
> **“지금, 블룸하세요.”**
