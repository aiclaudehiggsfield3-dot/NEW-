# S01 · 오프닝 — 맞닿는 손 (Seedance 2.0 영상 프롬프트)

## 컷 정보

| 항목 | 값 |
|---|---|
| 원본 | youtu.be/Xaqpvy-ZbMg, 0:00–0:07 (≈8s), [M] 기억 레이어 오프닝 |
| 역할 | 얼굴 없이 손만으로 관계를 보여 주는 첫 컷. 엔딩 S50(깍지)과 수미상관 |
| 동작 요약 | 손끝이 4cm 떨어진 두 손 → 천천히 다가감 → 손끝이 가볍게 닿고 멈춤 |
| 카메라 요약 | 콘크리트 높이 로우앵글 CU, 역광 석양, 아주 느린 푸시인 |

## Higgsfield 설정

| 설정 | 값 |
|---|---|
| 모델 | Seedance 2.0 |
| 시작 프레임 (Start frame) | `S01_start.png` (First Frame 이미지, `prompts/S01_start_frame.md`로 생성) |
| 끝 프레임 (End frame) | 비움 |
| 화면비 | 16:9 |
| 해상도 | 720p |
| 길이 | 8초 (프롬프트의 타임코드가 8초 기준. 길이를 바꾸면 ACTION 타임코드를 비율대로 조정) |
| 모드 | std (고품질) 또는 fast (저렴, 움직임 테스트용) |
| 오디오 생성 | 켜면 바이올린+강물 소리 생성. 실제 음악을 따로 입힐 거면 끄고 AUDIO 블록은 그대로 둬도 됨 |
| 이미지 태그 | 프롬프트의 `@image1` = 시작 프레임 이미지. 화면에서 태그 이름이 다르면 그 이름으로 교체 |

## 프롬프트

```
SCENE CONTEXT
Golden-hour close-up on a riverside concrete ledge. A young man's hand rests on the left side of the frame and a young woman's hand on the right side; they slowly reach toward each other until their fingertips meet. The river and a low setting sun sit behind them.

ACTIVE REFERENCES
@image1: first frame of this shot. Man's hand on frame left wearing a thin polished silver chain bracelet on the wrist, the rolled cuff of a white cotton shirt at the lower left edge; woman's slimmer bare hand on frame right with natural short nails, the edge of a white eyelet cotton sleeve at the lower right edge; both hands resting palm-down on the pale grey concrete, fingertips 4 cm apart. 100% matches the reference.

LOCATION MAP
Foreground: rough pale grey concrete ledge surface, fine grain and small pits catching the low sun, runs horizontally across the lower third.
Midground: the two hands, sharp, centered, the gap between the fingertips on the vertical center line.
Background: wide river surface glittering with orange sun sparkles, far city skyline dissolved into soft amber bokeh, the low sun sitting just above the horizon directly behind the gap between the fingertips. Warm golden haze density 15% over the river, visible from 20 meters depth.
Camera sits low at ledge height on the shadow side, facing into the sun.

FIRST FRAME / BLOCKING
Both hands already in frame from the first frame, resting flat on the concrete, fingertips 4 cm apart, the man's hand from frame left, the woman's hand from frame right. The bright sun glow fills the gap between the fingertips. Horizon line in the upper third.

FORMAT MODE
One continuous shot, the camera does not cut on its own.

OPTICS
Close-up on the two hands, 29° FOV portrait compression, shallow depth of field: focus plane locked on the fingertips, the concrete texture falls off softly within 20 cm, the river and skyline become large round warm bokeh discs. Gentle warm lens flare veil from the sun, soft highlight bloom.

CAMERA
Low-angle, lens 5 cm above the concrete, tilted 10° upward toward the hands, 40 cm from the fingertips, operator axis perpendicular to the river. Locked-off tripod feel with a very slow, steady push-in at 0.04 km/h across the whole shot, ending 8 cm closer. Focus stays on the fingertips the entire time. Soft film-like tonal latitude, highlights rolling off smoothly around the sun.

ACTION
0.0s to 2.0s — both hands rest still on the concrete, fingers relaxed; only the sun sparkles on the river move behind them.
2.0s to 3.0s — the man's hand begins to glide toward frame center at 0.02 km/h, the heel of his palm keeping light contact with the concrete while his fingertips hover just above it.
3.0s to 5.5s — the woman's hand answers, gliding toward frame center at the same slow speed, her index and middle fingertips leading; each hand travels about 2 cm.
5.5s to 6.5s — the fingertips meet lightly, just touching, the woman's fingers curl slightly at the contact.
6.5s to 8.0s — both hands hold still in that light touch; the silver bracelet catches a small glint of sun.
Camera motion: only the slow push-in. Subject motion: only the two hands.

PERFORMANCE
The hands carry the emotion: the man's index finger lifts a few millimeters and pauses for half a second before he moves, a small hesitation; the woman's fingertips tremble very faintly just before contact, then relax into the touch. Skin at pore-level realism: fine creases over the knuckles, faint veins on the backs of the hands, a warm capillary flush where the sun shines through the fingertips.

PHYSICS
Hands have natural weight: the palm heels drag with light friction on the rough concrete, knuckles and tendons shift realistically, soft contact shadows under each palm stretch long toward the camera and shorten as the fingertips meet. The bracelet chain slides and settles by gravity when the wrist moves. Exactly five fingers on each hand, natural proportions throughout.

LIGHTING
Single source: the low setting sun behind the hands, backlight at about 5° above the horizon. Warm rim light outlines the fingers and makes the skin edges glow translucent orange; the tops of the hands receive soft fill from the bright sky. White balance 5600K so the sun renders as deep amber-gold. Exposure set for the skin midtones, sun glow allowed to bloom.

COLOR GRADE
Warm film look: honey-amber highlights on the skin rims and river sparkle, soft lifted blacks in the concrete shadows, gentle peach midtones on the hands, the white sleeve cotton glowing warm cream in the backlight, a faint dusty violet in the upper sky. Low contrast, creamy roll-off.

WARDROBE
Man: rolled cuff of a clean white cotton shirt at the lower left edge, thin polished silver chain bracelet. Woman: edge of a white eyelet cotton sleeve at the lower right edge, no jewelry. Sleeves stay in place, lit warm by the sun.

AUDIO
Soft solo violin melody, slow and emotional, quietly entering; faint river water ambience underneath. Instrumental only.

STYLE
Photoreal cinematic music-video opening, romantic and reflective, fine film grain, soft halation around highlights.

OUTPUT SETTINGS
16:9, 720p, 8 seconds, real-time speed, 24 fps cinematic motion.

POSITIVE LOCKS
Only two hands in frame, the man's from frame left with the silver bracelet and white shirt cuff, the woman's from frame right with the white eyelet sleeve. Each hand keeps five well-formed fingers. Focus stays on the fingertips. The sun stays directly behind the gap between the fingertips for the whole shot. Ends on fingertips lightly touching and holding still.
```

## 검토 결과 (Seedance 프롬프트 체크리스트)

| 체크 항목 | 결과 |
|---|---|
| 블록 순서 (맥락·레퍼런스 → 공간·시간 → 동작·물리 → 스타일 → 기술 설정 → 잠금) | 통과 |
| 태그 규칙 (`@image1`은 실제로 화면에 있는 대상에만 사용) | 통과 |
| 맨 위에 스타일 접두 블록 없음 | 통과 |
| 스타일 요소가 각자 제자리 블록에 있음 (조명→LIGHTING, 색→COLOR GRADE, 연기·피부→PERFORMANCE, 의상→WARDROBE, 포맷→STYLE·OUTPUT) | 통과 (PERFORMANCE·WARDROBE 추가 후) |
| 긍정형 문장만 사용 | 통과 |
| 속도는 km/h, 대기는 %·미터 | 통과 (수정 후) |
| 감정을 근육 움직임으로 표현 | 통과 (PERFORMANCE 추가 후) |
| 좌우는 카메라 기준 | 통과 |
| FOV는 표의 값(29°) 사용 | 통과 |
| 화이트밸런스 켈빈 표기 | 통과 (5600K) |
| 색은 재질+빛+역할로 표현 | 통과 |
| 카메라는 그림자 쪽, 촬영 축 명시 | 통과 |
| 전경/중경/배경 레이어 | 통과 |
| 장비·감독 이름 없음 | 통과 |
| 수치끼리 모순 없음 (속도 × 시간 = 거리) | 통과 (수정 후) |

## 이번 검토에서 고친 점

1. **카메라 속도 모순:** 0.2 km/h로 8초면 약 44cm를 움직이는데 "8cm 전진"이라고 적혀 있었습니다. 8cm에 맞게 0.04 km/h로 고쳤습니다.
2. **손 동작 모순:** "손끝을 들어 올림"과 "콘크리트 위를 미끄러짐"이 부딪혔습니다. 손바닥 아랫부분은 닿은 채 미끄러지고, 손끝만 살짝 떠 있는 것으로 정리했습니다.
3. **속도 단위:** "초당 1cm"를 km/h로 바꾸고, 손마다 이동 거리(약 2cm)와 여자 손이 움직이기 시작하는 시점(3.0초)을 적었습니다.
4. **PERFORMANCE 추가:** 손의 망설임, 닿기 직전의 떨림, 피부 질감을 넣었습니다. 얼굴이 없는 컷이라 감정은 손끝 연기로만 전달됩니다.
5. **WARDROBE 추가:** 기존에는 소매가 정해져 있지 않아 모델이 마음대로 만들 수 있었습니다. 원작 기억 레이어의 "흰 옷" 규칙에 맞춰 남자는 흰 셔츠 소맷단, 여자는 흰 아일렛 소매로 정했습니다. First Frame 이미지 프롬프트에도 같은 내용을 넣었습니다.
6. **대기 표현:** 강 위의 황금빛 연무를 농도(%)와 거리(미터)로 적었습니다.
7. **출력 설정:** 길이 8초를 명시하고, 필름 포맷 이름("35mm")은 장비 이름으로 읽힐 수 있어 뺐습니다.
