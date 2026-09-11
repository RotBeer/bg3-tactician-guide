# 발더스게이트 3 공략 노트

전술가(Tactician) 난이도를 **명예(Honour) 모드 기준**으로 운용하기 위한 파티 구성 문서입니다.

- **메인**: 주술 칼날(Hexblade) 워락
- **제약**: 긴 휴식마다 관리해야 하는 버프 제외 / 아이템 의존도 최소 / 멀티클래스 없음 — 4명 전원 순수 12

---

## 문서 구성

| 파일 | 내용 | 언제 보나 |
|---|---|---|
| **[index.html](index.html)** | **대시보드** — 같은 내용을 한 화면에 밀도 있게. 다크 모드 기본 | **플레이 중 (권장)** |
| [bg3-tactician-build.md](bg3-tactician-build.md) | 본문 — 파티 구성, 빌드, 레벨업, 아이템, 운영, 보스, 획득 절차 | 원문·검색·diff |
| [GLOSSARY.md](GLOSSARY.md) | 영문/한글 용어 대조 사전 | 게임 표기와 문서가 안 맞을 때 |
| [CORRECTIONS.md](CORRECTIONS.md) | 정정 내역 — 무엇이 왜 틀렸는지 | 정보 신뢰도를 확인할 때 |
| [SOURCES.md](SOURCES.md) | 출처 목록 | 원문을 직접 확인할 때 |

`index.html`과 `bg3-tactician-build.md`는 **같은 내용**입니다. 편집은 md에서 하고 html에 반영하세요.

### 대시보드 사용법

QHD(2560×1440) / FHD(1920×1080) 데스크톱 전용입니다. 모바일은 고려하지 않았습니다.

| 조작 | 동작 |
|---|---|
| `1` ~ `6` | 탭 전환 — 파티 / 레벨업 / 아이템 / 획득 절차 / 운영 / 보스 |
| `/` | 검색 포커스 — 현재 탭의 카드를 걸러냅니다 |
| `Esc` | 검색 해제 |
| `d` | 다크 ↔ 라이트 전환 (`localStorage`에 저장) |
| `#party` `#boss` … | 탭 딥링크 |
| `?theme=light` | 테마 강제 (스크린샷·공유용) |

---

## 작업 절차

```
LLM 질의 → 내용 확정 → 내용 검증 → md 작성 → (요청 시) html 수정
```

| 단계 | 하는 일 | 산출물 |
|---|---|---|
| **1. LLM 질의** | 조건을 명시해 질문한다. 난이도·제약·선호를 먼저 못 박는다 | — |
| **2. 내용 확정** | 방향과 범위를 결정한다. 이 단계에서 "안 쓸 것"도 같이 정한다 | 결정 사항 |
| **3. 내용 검증** | **bg3.wiki 원문과 대조**하고 각 항목에 등급을 매긴다. 2차 출처만으로는 확정하지 않는다 | ✔/▲/※ 등급 |
| **4. md 작성** | 본문은 build, 용어는 GLOSSARY, 정정은 CORRECTIONS, 출처는 SOURCES로 분리해 기록 | .md 파일 |
| **5. html 수정** | **요청이 있을 때만** 수행. 대시보드 레이아웃·테마 조정 후 **검증 에이전트로 시각 검증** | `index.html`, `assets/` |

> 3단계를 건너뛴 내용은 문서에 넣지 않습니다. 이 규칙이 생긴 경위는 [CORRECTIONS.md](CORRECTIONS.md) 참고.

### 5단계의 시각 검증

`index.html`을 고친 뒤에는 **HTML 소스를 보지 않고 렌더링 화면만 보는 검증 에이전트**를 붙입니다. 작성자가 자기 코드를 보면서 판단하면 "의도한 대로 보일 것"이라고 착각하기 때문입니다.

헤드리스 Chrome으로 캡처합니다. **한 번에 하나씩** 실행하고, PNG는 비동기로 쓰이므로 **다음 호출에서** 확인하세요.

```bash
"/c/Program Files/Google/Chrome/Application/chrome.exe" \
  --headless=new --no-sandbox --disable-gpu --hide-scrollbars \
  --force-device-scale-factor=1 --virtual-time-budget=3000 \
  --window-size=2560,1440 --user-data-dir="<임시경로>\pA" \
  --screenshot="<임시경로>\qhd-party.png" \
  "file:///C:/study/bal/index.html#party"
```

`--window-size`를 주면 **페이지 전체 높이**가 캡처되므로, 이미지 높이 ÷ 1440 으로 "몇 화면 분량인지"를 바로 측정할 수 있습니다.

---

## 검증 등급

문서 전체에서 아래 기호를 씁니다. **등급을 섞지 않는 것이 이 프로젝트의 규칙입니다.**

| 기호 | 의미 | 취급 |
|---|---|---|
| **✔** | **bg3.wiki 원문 확인** | 그대로 믿어도 됨 |
| **▲** | 빌드 가이드 등 2차 출처 | **게임 내 확인 권장** |
| **※** | 미검증 / 5판 규칙 기준 추정 | **반드시 게임 내 확인** |

▲ · ※ 항목을 게임에서 확인했다면 해당 줄의 등급을 ✔로 바꾸고, 값이 달랐다면 [CORRECTIONS.md](CORRECTIONS.md)에 한 줄 추가하세요.

---

## 용어 규칙

BG3 한글판 표기가 자료마다 갈립니다. 예를 들어 `Counterspell`은 "주문 방해"와 "마법 무효화"가, `Misty Step`은 "안개 걸음"과 "몽환의 발걸음"이 함께 쓰입니다.

그래서 이 문서는 **영문명을 기준 키로 삼고 한글을 병기**합니다.

> 게임 내 표기가 다르면 **[GLOSSARY.md](GLOSSARY.md)만 고치면** 문서 전체가 정리됩니다.

---

## 배포

GitHub Pages로 정적 사이트를 게시합니다. Jekyll이 `.md`를 자동으로 렌더링하므로 별도 빌드 단계가 없습니다.

```
main 브랜치 push → GitHub Pages 자동 빌드 → 공개 URL
```

- **진입점은 `index.html`** (대시보드). 이 README는 `README.html`로 접근합니다
- `index.html`은 front matter가 없어 Jekyll이 **그대로 복사**합니다 — 테마 영향을 받지 않습니다
- `.md` 문서의 테마·레이아웃 설정: `_config.yml` (cayman) + `assets/css/style.scss`
- `.md` 안의 상대 링크는 Pages가 `.html`로 자동 변환합니다. `index.html` 안에서는 `.html`을 직접 씁니다

### 갱신

```bash
git add -A
git commit -m "내용 수정"
git push
```

푸시 후 1~2분이면 반영됩니다.
