# 에어K (Air K) AI 광고 🎬
### Codyssey AI Native — 멀티미디어 미션 B1-2 (1회차)

> 생성형 AI만을 주된 소스로 제작한 **17초 브랜드 인지(Awareness) 광고**.
> 기획 의도 → 프롬프트 → 결과물 → 통합 편집으로 이어지는 멀티모달 제작 파이프라인 전 과정을 직접 설계했습니다.

> ⚠️ **교육 목적의 가상 브랜드 광고입니다.** 에어K·네넴멤버십은 실재하지 않는 가상 브랜드이며, 상업적 사용이 아닙니다.

---

## 📺 광고 영상

👉 **[영상 보기](https://drive.google.com/file/d/1N4Vi_6R2ORnXK36wITcnpQydBv_y7OWC/view?usp=sharing)**

> 영상 파일(MP4)은 **GitHub 단일 파일 100MB 제한**으로 직접 업로드하지 않고 외부 링크로 제공합니다.
> (YouTube 일부공개 또는 Google Drive 공유 링크 권장)

---

## 🎯 프로젝트 개요

| 항목 | 내용 |
|---|---|
| 브랜드 | 에어K (Air K) — 가상 항공 브랜드 |
| 멤버십 | 네넴멤버십 — 가상 멤버십 |
| 광고 목적 | 브랜드 인지 (Awareness) |
| 타겟 | 네넴멤버십으로 일본 여행을 다니지만, 에어K로 가성비 일본 **소도시** 여행이 가능함을 모르는 20~40대 |
| 핵심 메시지 | **"짐은 가볍게, 일본 골목 깊숙이"** |
| USP | 네넴멤버십 하나로 일본 소도시까지 + 추가 위탁수하물 5kg 무료 |
| 영상 사양 | 17초 / 1080p / 30fps / H.264·AAC / 16:9 |
| 서사 구조 | 기승전결 (앱 발견 → 출발 → 여행 → 혜택 체감 → 브랜드 메시지) |

---

## 🛠️ 사용 도구

| 단계 | 주 도구 | 대체 도구 |
|---|---|---|
| 이미지 생성 | Gemini (Nano Banana2 / Pro), ChatGPT (DALL·E) | Imagen 4 |
| 영상 생성 | Google Flow (Omni Flash) | Pika, Kling, Runway |
| 나레이션 (TTS) | Google AI Studio — Gemini 3.1 Flash TTS | ElevenLabs, CLOVA Voice |
| 배경음악 (BGM) | Suno | Udio, YouTube Audio Library |
| 편집·합성 | CapCut | DaVinci Resolve |

---

## 🔁 제작 파이프라인

```
이미지 생성 → (Google Flow) 영상 변환 → 나레이션·BGM 별도 생성 → CapCut 통합 편집·믹싱 → 1080p MP4
```

- 텍스트가 핵심인 씬1은 영상 생성 대신 **이미지 + CapCut 줌인 키프레임**으로 처리
- 인물은 **캐릭터 레퍼런스를 고정**해 전 씬 동일하게 유지
- 오디오는 생성 도구(TTS·BGM)와 편집 도구(CapCut)의 **역할을 분리**

---

## 🔑 핵심 학습 — 멀티모달 제작 이슈 대응

- **화면 텍스트는 AI 영상보다 이미지+편집이 안정적** — 앱 UI 한글이 AI 영상에서 매 프레임 왜곡되어, 씬1을 이미지+CapCut 줌인으로 대체
- **동일 프롬프트도 도구마다 결과 차이가 큼** — 손+폰+카페 합성에서 Gemini보다 ChatGPT가 구도·한글 재현 우수 → 비교 후 채택
- **AI 영상 정책은 미성년자 콘텐츠에 보수적** — 배경에 아이가 포함된 이미지의 영상화를 거부 → "아이 없는 버전"으로 재생성
- **AI 영상은 물체 상호작용 물리 구현에 한계** — 쇼핑백 물리 통과 오류는 재생성, 캐리어 자동 이동은 광고적 재미로 수용
- **무료 플랜 제약은 우회 경로로 해결** — Suno 무료 다운로드 제한 → MP3 항목으로 직접 저장

> 상세 이슈·대응·프롬프트 수정 전/후 기록은 **[스토리보드 PDF](./aerok_storyboard_v2.3.pdf)** 참고

---

## 📁 파일 구성

```
.
├── README.md
├── aerok_storyboard_v2.2.pdf      # 기획 문서 (제출용 PDF)
├── assets/                        # 생성 이미지
└── AirK_ad_final.mp4 
```

---

## 📄 스토리보드 (기획 문서)

👉 **[기획 문서 PDF 보기](./aerok_storyboard_v2.3.pdf)**
👉 **[영상 보기](https://drive.google.com/file/d/1N4Vi_6R2ORnXK36wITcnpQydBv_y7OWC/view?usp=sharing)**

포함 내용: 브랜드 아이덴티티 · 캠페인 목표 · 씬별 상세(8개 필수 필드) · 입력 프롬프트 원문 · 프롬프트 수정 전/후 사례(3건) · 멀티모달 이슈 기록

---

<sub>Codyssey AI Native · 멀티미디어 미션 B1-2 (1회차) · 교육 목적 가상 광고</sub>
