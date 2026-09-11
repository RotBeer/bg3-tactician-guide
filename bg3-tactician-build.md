# 발더스게이트 3 — 전술가 공략 노트 (명예 기준 운용)

> [README](README.md) · [본문](bg3-tactician-build.md) · [용어 사전](GLOSSARY.md) · [정정 내역](CORRECTIONS.md) · [출처](SOURCES.md)

> **난이도**: 전술가(Tactician) — 단, **판단 기준은 명예(Honour) 모드**에 맞춥니다.
> **제약**: 힘 영약 등 긴 휴식마다 관리해야 하는 버프 제외 / 아이템 의존도 최소 / **멀티클래스 없음 — 4명 전원 순수 12**
>
> 표기 등급 **✔** bg3.wiki 확인 · **▲** 2차 출처(게임 내 확인 권장) · **※** 미검증 — 자세한 규칙은 [README](README.md#검증-등급)

---

## 목차

1. [최종 파티 구성](#1-최종-파티-구성)
2. [Tav — Hexblade Warlock 12](#2-tav--hexblade-warlock-12)
3. [Shadowheart — Light Domain Cleric 12](#3-shadowheart--light-domain-cleric-12)
4. [Gale — Evocation Wizard 12](#4-gale--evocation-wizard-12)
5. [Karlach vs Lae'zel — Battle Master Fighter 12](#5-karlach-vs-laezel--battle-master-fighter-12)
6. [레벨업 로드맵](#6-레벨업-로드맵)
7. [캐릭터별 아이템](#7-캐릭터별-아이템)
8. [영구 능력치 보너스](#8-영구-능력치-보너스)
9. [명예 기준 운영](#9-명예-기준-운영)
10. [보스별 메모](#10-보스별-메모-)
11. [출발 체크리스트](#11-출발-체크리스트)
12. [아이템 획득 상세 절차](#12-아이템-획득-상세-절차)

---

## 1. 최종 파티 구성

| 슬롯 | 캐릭터 | 빌드 | 역할 | 주 능력치 |
|---|---|---|---|---|
| 1 | **Tav** | Warlock (Hexblade) 12 — 검의 계약 + Shadow Blade | 근접 폭딜 + 자체 생존 | CHA 매력 |
| 2 | Shadowheart | Cleric (Light Domain) 12 | 광역 광휘딜 + 명중 방해 + 회복 | WIS 지혜 |
| 3 | Gale | Wizard (Evocation) 12 | 제어 + 주문 방해 + 광역 | INT 지능 |
| 4 | **Karlach** | Fighter (Battle Master) 12 | 안정적 근접 딜 + 전선 | STR 힘 |

**구조적 장점**

- **주 능력치가 4명 전부 다릅니다** → 장비 경쟁 0. 주운 아이템의 주인이 자동으로 정해집니다
- **멀티클래스가 없습니다** → 레벨업할 때 고민할 게 없고, 리스펙 실수도 안 납니다
- **긴 휴식마다 관리할 버프가 없습니다** → 영약 루틴 없음, 소환물 유지 없음
- 전선 2(Tav, Karlach) / 후열 2(Shadowheart, Gale)

> **BG3에는 종족별 고정 능력치 보너스가 없습니다** ✔ — 정식 출시 때 삭제되었고, 대신 **+2/+1을 원하는 능력치에 자유 배치**합니다. 종족은 **능력치가 아니라 종족 특성만 보고** 고르면 됩니다.

---

## 2. Tav — Hexblade Warlock 12

> **구성**: 순수 Warlock 12 / 패트론 **The Hexblade** / 계약 **Pact of the Blade** / 무기는 **Shadow Blade 주문**

### 2-1. Hexblade가 주는 것 ✔

| Lv | 능력 | 효과 |
|---|---|---|
| 1 | **Hex Warrior** (수동) | **중형 갑옷 · 방패 · 군용 무기 숙련.** 그리고 Bind Hexed Weapon을 얻어 **숙련 무기 공격 시 힘/민첩 대신 매력** 사용 |
| 1 | **Bind Hexed Weapon** (행동) | **주 손 무기**에 결속. 피해가 마법 피해가 되고, 버리거나 던질 수 없음. **명중 시 일정 확률로 주술 칼날의 저주 적용** |
| 1 | **Hexblade's Curse** (보너스 행동, **짧은 휴식 회복**) | 저주 대상에게 **+숙련 보너스 피해**, **치명타 기준 1 감소(19+)**, 대상 사망 시 **워락 레벨 + 매력 보정**만큼 HP 회복 |
| 6 | **Accursed Spectre** (반응) | 저주 대상 처치 시 악령 소환. 구조물·원소·우즈·식물·언데드 제외 |
| 10 | **Armour of Hexes** (반응) | 저주 대상이 나를 공격할 때 **50% 확률로 무효화** |

> ### ❗ Hexblade는 추가 공격을 주지 않습니다 ✔
> **추가 공격은 검의 계약에서 나옵니다.** 계약을 다른 걸로 고르면 12레벨까지 공격 1회입니다.

### 2-2. 검의 계약(Pact of the Blade)이 필수인 이유

Hexblade와 검의 계약은 **중복이 아니라 상호 보완**입니다.

| 출처 | 주는 것 | |
|---|---|---|
| **Hex Warrior** (Hexblade 1) | 숙련 무기 공격에 **매력** 사용 / 중형 갑옷·방패·군용 무기 숙련 | ✔ |
| **Pact of the Blade** (3) | 무기 **소환**, 소환 무기는 **매력 보정으로 피해** | ✔ |
| **Deepened Pact** (Warlock 5, 검의 계약 보유 시) | **추가 공격** | ▲ |
| **Lifedrinker** (12레벨 결속) | 근접 피해 **+매력 보정**. 검의 계약이 선행 조건 | ▲ |

> ▲ `Deepened Pact`가 워락 5레벨에 자동 부여되는지, `Thirsting Blade` 결속을 따로 찍어야 하는지는 자료마다 다릅니다. **레벨 5 찍을 때 결속 목록을 직접 확인하세요.**

### 2-3. Shadow Blade (그림자 검) — 이 빌드의 무기 ✔

| 항목 | 값 |
|---|---|
| 레벨 / 시전 | **2레벨 환영계, 보너스 행동** |
| 지속 | **긴 휴식까지** |
| 피해 | **2d8 정신 피해** + 힘/민첩 보정 |
| 상위 시전 | 3~4레벨 슬롯 → **3d8** / 5~6레벨 슬롯 → **4d8** |
| 특수 | **약한 빛(dim light) 또는 어둠 속 대상을 공격할 때 이점** |
| 무기 분류 | 숏소드 — 근접 / 단순 / 한손 |
| 습득 | 소서러 · 워락 · 위저드 **3레벨** |

**왜 이게 정답인가**

1. **무기가 곧 주문입니다.** 좋은 무기를 찾을 필요가 없습니다 — "아이템 의존도 최소" 조건에 가장 잘 맞습니다
2. **어둠과 이중으로 맞물립니다.** 어둠 속 적 → 적은 나를 못 봐서 **불리**, 나는 Shadow Blade 효과로 **이점**. **약한 빛만으로도 이점 조건이 성립**하므로 던전·야간·그림자 저주 지역에서는 Darkness조차 불필요합니다
3. **정신(Psychic) 피해**라 저항하는 적이 드뭅니다
4. **슬롯 소모가 긴 휴식당 1회뿐**입니다

**슬롯 레벨 대응표**

| 워락 Lv | 계약 슬롯 | Shadow Blade |
|---|---|---|
| 3~4 | 2레벨 | 2d8 |
| 5~6 | 3레벨 | **3d8** |
| 7~8 | 4레벨 | 3d8 |
| **9~12** | **5레벨** | **4d8** |

> ▲ **게임 내 확인**: Shadow Blade를 `Bind Pact Weapon`으로 결속할 수 있는지 확인하세요.
> - **가능** → 피해 보정이 **매력**. 민첩은 AC용으로만
> - **불가** → 피해 보정이 **민첩**으로 남음. 이 경우 DEX를 16으로 올리세요
>
> 명중 굴림은 어느 쪽이든 `Hex Warrior`로 매력입니다 ✔ (Shadow Blade는 단순 무기 = 숙련 대상)

### 2-4. 종족

**종족 능력치 보너스는 존재하지 않습니다** ✔ — 특성만 보고 고르세요.

| 종족 | 특성 | 평가 |
|---|---|---|
| **Half-Orc** | Savage Attacks (치명타 시 무기 주사위 추가) / Relentless Endurance (긴휴식 1회, HP 0 대신 1) | **딜 + 생존 1순위.** 저주의 19+ 치명타와 곱연산 |
| **Drow** | 우월한 암시야 **24m**, 무료 Faerie Fire, 액트1 고블린 진영 무혈 통과 | **어두운 곳에서 싸우는 빌드라 실사용 편의는 최고** |
| Asmodeus Tiefling | **화염 저항**, 암시야 12m, 무료 Darkness(5레벨) ✔ | Darkness를 슬롯 없이 |
| Wood Half-Elf | 이동속도 +1.5m, 은신 이점 | 무난 |

### 2-5. 능력치

```
STR 8   DEX 14   CON 16   INT 8   WIS 10   CHA 17
```

- 명중은 Hex Warrior로 **매력** ✔ → 힘은 완전히 버립니다
- **DEX 14**: 중형 갑옷 최대 민첩 보정이 +2 ✔
- 2-3의 ▲에서 **Shadow Blade 결속 불가로 확인되면 DEX 16**
- CHA 17 → 4레벨 +2 → **19** → Hag's Hair +1 → **20** → Mirror of Loss +2 → **22**

### 2-6. 결속 / 주문 / 재주

**결속(Invocation)**

| Lv | 결속 |
|---|---|
| 2 | **Agonizing Blast** (Eldritch Blast에 +매력) / **Devil's Sight** (마법 어둠 속 시야) |
| 5 | Repelling Blast, 또는 2-2의 ▲ 확인 후 추가 공격 관련 결속 |
| 7·9 | Fiendish Vigor 등 자유 |
| 12 | **Lifedrinker** ▲ — 근접 피해 +매력 |

**주문**

| Lv | 주문 | 용도 |
|---|---|---|
| 2 | **Shadow Blade** | **주무기. 최우선** |
| 2 | **Darkness** | 밝은 실외 대비 |
| 1 | Armour of Agathys | 임시 HP + 냉기 반사 |
| 3 | **Counterspell** | 적 캐스터 봉쇄 |
| 3 | **Hunger of Hadar** | 광역 제어 + 지속 피해 |

**소마법**: Eldritch Blast, **Minor Illusion**(적을 모아 Fireball 유도), Friends

**재주**

| Lv | 재주 |
|---|---|
| 4 | **Ability Improvement — CHA +2 (17→19)** |
| 8 | **Savage Attacker** (피해 주사위 재굴림 — 4d8이라 이득이 큼) |
| 12 | **Alert** 또는 **War Caster** |

### 2-7. 전투 루프

```
긴 휴식 직후  Shadow Blade 시전 — 가능한 최고 슬롯. 다음 긴 휴식까지 유지
1턴          보너스 행동 → Hexblade's Curse (보스에게)
             행동      → 접근 + 공격
2턴~         행동 → 공격 ×2   (밝은 실외면 선행으로 Darkness)
```

**타격당 피해 구성 (12레벨)**

```
Shadow Blade 4d8 (평균 18) + 매력 5 + Lifedrinker 5 + 저주 숙련 4  ≈ 32
+ Resonance Stone 보유 시 정신 피해분 2배
+ 치명타 19+ (Half-Orc면 주사위 1개 추가)
```

---

## 3. Shadowheart — Light Domain Cleric 12

### 3-1. Light Domain 능력 ✔

| Lv | 능력 | 효과 |
|---|---|---|
| 1 | **Warding Flare** | 공격자에게 **불리** 부여 → 빗나가게 만듦 |
| 2 | **Channel Divinity** | **1회 / 짧은 휴식 또는 긴 휴식마다 회복** |
| 2 | **Radiance of the Dawn** (Channel Divinity) | 주변 적에게 **2d10 + 캐릭터 레벨** 광휘 피해 |
| 6 | **Improved Warding Flare** | **아군을 노리는 공격자**에게도 불리 부여 |
| 6 | Channel Divinity **2회** | |
| 8 | **Potent Spellcasting** | **클레릭 소마법 피해에 +지혜 보정** |

> **Channel Divinity가 짧은 휴식마다 회복된다는 점이 중요합니다** ✔. Radiance of the Dawn을 아낄 이유가 없습니다. 12레벨이면 **2d10 + 12**가 주변 적 전체에 들어갑니다.
>
> **Potent Spellcasting(8레벨)** 때문에 후반에는 Sacred Flame이 **+5 피해**를 받습니다. 소마법을 실제로 쓰게 됩니다.

### 3-2. 영역 주문 (항상 준비됨) ✔

| 클레릭 Lv | 주문 |
|---|---|
| 1 | Light, Burning Hands, **Faerie Fire** |
| 3 | Flaming Sphere, Scorching Ray |
| 5 | Daylight, **Fireball** |
| 7 | Guardian of Faith, Wall of Fire |
| 9 | Destructive Wave, **Flame Strike** |

**항상 준비된 상태**라 준비 슬롯을 잡아먹지 않습니다. 클레릭이 딜러를 겸할 수 있는 이유입니다.

### 3-3. ⚠ 갑옷 — Light Domain은 중갑을 못 입습니다 ✔

| 구분 | 내용 |
|---|---|
| 클레릭 기본 숙련 | 단순 무기 + 플레일/모닝스타, **경갑 · 중형 갑옷 · 방패** |
| **중갑을 주는 영역** | Life, Nature, Tempest, War |
| **중갑이 없는 영역** | Death, Knowledge, **Light**, Trickery |

→ **DEX 14를 반드시 확보**하고 반판금(AC 15) + 방패(+2)로 **AC 19**를 맞추세요.

### 3-4. 왜 Life가 아니라 Light인가

BG3는 **"맞고 회복"보다 "안 맞기 + 먼저 지우기"**가 효율이 훨씬 좋습니다.

| | **Light Domain** | Life Domain |
|---|---|---|
| 방어 | Warding Flare → 6레벨부터 **아군 보호까지** | 회복량 증가 |
| 화력 | Radiance of the Dawn + **Fireball / Scorching Ray / Flame Strike** 상시 준비 | 없음 |
| 소마법 | **8레벨부터 +지혜 보정** | — |
| 갑옷 | 중형 (DEX 14 필요) | **중갑** |

Light는 클레릭을 세컨드 딜러로 만듭니다. 특히 액트2 그림자 저주 지역 전체와 언데드/그림자 계열에 **광휘 피해가 특효**입니다.

### 3-5. 능력치 / 소마법 / 주문 / 재주

```
STR 8   DEX 14   CON 16   INT 10   WIS 17   CHA 8
```

**소마법**
- **Guidance** — 모든 능력 판정 +1d4. **전투 밖에서 상시 사용.** 자물쇠·설득·손재주 성공률이 통째로 달라집니다
- **Sacred Flame** — 민첩 내성, 엄폐 무시. 8레벨부터 +지혜 보정
- **Light** — 적에게 걸어 **밝게 빛남** 부여 → Callous Glow Ring과 연계

**주문**

| Lv | 필수 | 상황용 |
|---|---|---|
| 1 | **Bless** — 아군 3명 명중/내성 +1d4. 전투 시작 고정 | Healing Word, Command |
| 2 | **Spiritual Weapon** — 보너스 행동 공격, 집중 아님 | Silence, Blindness |
| 3 | **Spirit Guardians** (클레릭 **5레벨** ✔) — 주변 적에게 매 턴 광휘 + 이동 절반 | Revivify |
| 4 | **Freedom of Movement** — 마비/속박 면역 | Death Ward |
| 5 | Mass Cure Wounds | Greater Restoration |

**운영**: 1턴 **Bless** → 2턴 **Spirit Guardians** 켜고 적진 한가운데로 걸어 들어가기. 잡몹 전투는 이것만으로 정리됩니다. Warding Flare(반응)는 보스의 큰 한 방에 아껴두세요.

**재주**: 4 **War Caster** → 8 **Ability Improvement (WIS)** → 12 **Resilient: CON**

---

## 4. Gale — Evocation Wizard 12

### 4-1. Evocation School 능력 ✔

| Lv | 능력 | 효과 |
|---|---|---|
| 2 | **Evocation Savant** | **방출계 주문 두루마리 학습 비용이 주문 레벨당 25gp로 반값** |
| 2 | **Sculpt Spells** | **아군은 자동으로 내성에 성공하고 피해를 전혀 받지 않음** |
| 6 | **Potent Cantrip** | 적이 내성에 성공해도 **소마법 피해 절반은 들어감** (부가 효과만 무효) |
| 10 | **Empowered Evocation** | **모든 방출계 주문 피해 굴림에 +지능 보정** |

> **Sculpt Spells가 Evocation을 고르는 이유입니다** ✔. 아군은 **절반이 아니라 0** 피해입니다. 전선이 2명인 이 조합에서 다른 학파를 고르면 Fireball을 사실상 못 씁니다.

### 4-2. 왜 위저드인가

**위저드는 두루마리를 먹어 주문을 영구 습득합니다** ✔. 액트3 Sorcerous Sundries에서 골드로 쓸어 담으면 전 주문 보유 캐스터가 됩니다. **장비가 아니라 골드로 강해지는 클래스**라 "아이템 의존도 낮게"라는 조건에 맞습니다. 게다가 방출계는 학습 비용이 반값입니다.

소서러는 행동 경제(쌍둥이/신속)가 낫지만 아는 주문이 적고 되돌리기 어렵습니다. 위저드는 **긴 휴식마다 준비 주문을 자유 교체**할 수 있어 실수 복구가 쉽습니다.

### 4-3. 능력치 / 소마법 / 주문 / 재주

```
STR 8   DEX 16   CON 16   INT 17   WIS 10   CHA 8
```
CON 16은 집중 유지 굴림 때문에 필수입니다.

**소마법**: Fire Bolt, **Ray of Frost**(이동속도 감소), Minor Illusion, Mage Hand
> Potent Cantrip(6레벨) 덕에 소마법이 빗나가도 절반은 들어갑니다 ✔

**주문**

| Lv | 주문 |
|---|---|
| 1 | **Shield**(반응 AC +5 — 생존 핵심), **Magic Missile**, Grease |
| 2 | **Web**, Misty Step, Scorching Ray, Hold Person |
| 3 | **Fireball**, **Counterspell**, **Hypnotic Pattern**, Slow, Haste(9-1 참고) |
| 4 | **Evard's Black Tentacles**, **Greater Invisibility**, Dimension Door |
| 5 | **Hold Monster**, Cone of Cold |
| 6 | **Chain Lightning**, **Globe of Invulnerability**, Disintegrate |

**재주**: 4 **War Caster** → 8 **Ability Improvement (INT)** → 12 **Lucky**

---

## 5. Karlach vs Lae'zel — Battle Master Fighter 12

### 5-1. 결론: **Karlach** ✔

> **이전 판본에서 Lae'zel을 추천한 근거("기스양키 종족 능력치가 힘 계열")는 사실이 아니었습니다.**
> **BG3에는 종족별 고정 능력치 보너스가 없습니다** ✔ — 정식 출시 때 삭제되었습니다.
> 그 전제를 빼고 다시 비교하면 결론이 뒤집힙니다.

| | **Karlach** (Zariel Tiefling) | Lae'zel (Githyanki) |
|---|---|---|
| 능력치 보너스 | **없음 (종족 무관)** ✔ | **없음 (종족 무관)** ✔ |
| **방어 특성** | **화염 저항 — 영구, 상시** ✔ | 없음 |
| **암시야** | **12m** ✔ | **없음** ✔ |
| 기동 | — | **Misty Step 1회/긴휴식** (5레벨) ✔ |
| 유틸 | Thaumaturgy | Astral Knowledge (능력치 1개 관련 전 기술 숙련, 1회/긴휴식) ✔ |
| 추가 피해 | Searing Smite(3레벨) + **Branding Smite**(5레벨), 각 1회/긴휴식 ✔ | Jump(3레벨), 투명 Mage Hand ✔ |
| 무기·방어구 숙련 | — | 경갑·중형 + 숏소드/롱소드/대검 ✔ |
| 합류 | 에메랄드 숲 이후 | **게임 시작 직후** |

**판단 근거 3가지**

1. **기스양키의 무기·방어구 숙련은 파이터에게 완전히 무의미합니다.** 파이터가 이미 단순+군용 무기 전부, 경갑·중형·**중갑**, 방패를 갖고 시작합니다 ✔
2. **기스양키에게는 암시야가 없습니다** ✔. 액트2 전체가 그림자 저주 지역이고 지하 암흑계·야간 전투가 많습니다
3. **화염 저항은 영구·상시**입니다. BG3에서 가장 흔한 피해 타입이고 Grym·Steel Watcher·Gortash·악마 계열 전부에 걸립니다. Misty Step 1회/긴휴식보다 누적 가치가 큽니다

**Lae'zel을 고를 상황**: 액트1 초반부터 전선이 필요할 때(가장 먼저 합류), 또는 적 후열 캐스터 접근이 반복적으로 문제일 때. 파티 밖 동료도 레벨이 자동으로 따라오므로 **구간별 교체가 최선**입니다.

### 5-2. Fighter 진행 ✔

| Lv | 획득 |
|---|---|
| 1 | 전투 방식 선택 / 숙련: 단순+군용 무기, 경갑·중형·**중갑**, 방패 |
| 2 | **Action Surge** — 추가 행동 1회, 짧은 휴식 회복 |
| 3 | **Battle Master** — 우월성 주사위 **4개(d8)**, 기동 3개 |
| **4** | **재주** |
| 5 | **Extra Attack** — 공격 2회 |
| **6** | **재주** |
| 7 | 우월성 주사위 **5개(d8)**, 기동 +2 |
| **8** | **재주** |
| 10 | 우월성 주사위 **5개(d10)**, 기동 +2 |
| **11** | **Improved Extra Attack — 주 손 공격 후 2회 추가 = 총 3회** |
| **12** | **재주** |

> **파이터 11의 3번째 공격이 이 슬롯의 전부입니다** ✔. 멀티클래스하면 통째로 날아가므로 **순수 12가 정답**입니다. 재주도 4개(4/6/8/12)로 클래스 중 최다입니다 ✔.
> **우월성 주사위는 짧은 휴식마다 회복됩니다** ✔ — 아끼지 마세요.

### 5-3. 기동(Manoeuvre) ✔

| 기동 | 효과 |
|---|---|
| **Precision Attack** | 우월성 주사위를 **명중 굴림에 더함**. 내성 굴림이 필요 없어 **항상 유효** |
| Trip Attack | +1d8, 넘어짐 — **힘 내성** |
| Menacing Attack | +1d8, 공포 — **지혜 내성** |

> **기동 내성 DC = 8 + 숙련 보너스 + 힘/민첩 중 높은 쪽** ✔
> 힘 20이면 DC 8+4+5 = **17**. 충분히 통합니다. Precision Attack은 DC가 필요 없어 언제나 1순위입니다.

### 5-4. 능력치 / 전투 방식 / 재주

```
STR 17   DEX 14   CON 16   INT 8   WIS 10   CHA 8
```

**전투 방식: Great Weapon Fighting** — 양손 무기 피해 주사위의 **1과 2를 재굴림** ✔

**재주**

| Lv | 재주 |
|---|---|
| 4 | **Great Weapon Master** (Precision Attack이 -5를 상쇄) |
| 6 | Ability Improvement — STR 17→19 |
| 8 | Ability Improvement — STR→20 |
| 12 | **Alert** (선제권 +5) |

**무기**: 아무 Greatsword / Glaive. **아이템 의존 0.**

---

## 6. 레벨업 로드맵

### Tav — Warlock (Hexblade) 12

| Lv | 획득 / 선택 |
|---|---|
| 1 | 패트론 **The Hexblade** / 소마법 Eldritch Blast + Minor Illusion |
| 2 | 결속 **Agonizing Blast**, **Devil's Sight** |
| **3** | 계약 **Pact of the Blade** / 주문 **Shadow Blade**, **Darkness** ← **빌드 가동** |
| 4 | 재주 **ASI — CHA +2 (→19)** |
| **5** | **추가 공격** / 3레벨 슬롯 → **Shadow Blade 3d8** / Counterspell 또는 Hunger of Hadar |
| 6 | **Accursed Spectre** |
| 7 | 4레벨 슬롯 / 결속 +1 |
| 8 | 재주 **Savage Attacker** |
| **9** | **5레벨 슬롯 → Shadow Blade 4d8** / 결속 +1 |
| 10 | **Armour of Hexes** |
| 11 | **Mystic Arcanum** (6레벨 주문 1개) |
| 12 | 재주 **Alert** / 결속 **Lifedrinker** ▲ |

### 전체 변곡점

| 캐릭터 | Lv | 내용 |
|---|---|---|
| Tav | **3** | 검의 계약 + Shadow Blade — 빌드 가동 |
| Tav | **5** | 추가 공격 + 3d8 |
| Shadowheart | **5** | Spirit Guardians ✔ |
| Gale | **5** | Fireball + Counterspell |
| Gale | **6** | Potent Cantrip / Sculpt Spells 체감 |
| Tav | **9** | Shadow Blade 4d8 |
| Karlach | **11** | 공격 3회 ✔ |

---

## 7. 캐릭터별 아이템

> 퍼즐/보스가 얽힌 것은 **[12번 항목](#12-아이템-획득-상세-절차)**에 절차를 따로 정리했습니다 (★ 표시).

### 7-1. Tav — Hexblade Warlock (CHA)

**핵심 — 아이템 0으로 성립**

| | |
|---|---|
| 주무기 | **Shadow Blade** (주문) |
| 명중 | **Darkness + Devil's Sight**, 또는 약한 빛만으로도 성립 |
| 방어 | Hex Warrior의 중형 갑옷 + 방패 숙련 |

**있으면 좋은 것**

| 액트 | 아이템 | 효과 | 획득 | |
|---|---|---|---|---|
| 1 | **Hag's Hair** ★ | **능력치 +1, 상한 무시** | 에델 아줌마 | ✔ |
| 1 | **Adamantine Scale Mail** ★ | **AC 16 + 민첩(최대 +2) / 중형 갑옷 / 치명타 피격 불가 / 모든 피해 -1 / 근접 피격 시 공격자 비틀거림 2턴** | Grymforge 용광로 | ✔ |
| 2 | **Mirror of Loss** ★ | CHA +2 (상한 24) | Gauntlet of Shar | ✔ |
| 2 | **Resonance Stone** | 주변 대상에게 **정신 피해 취약** → Shadow Blade 2배 | 마인드 플레이어 군체, 괴사 실험실 남서쪽 | ✔ |
| 3 | **Helm of Balduran** ★ | **AC +1, 내성 +1 / 전투 중 매 턴 시작 2HP 회복 / 치명타 피격 불가 / 기절 면역** | Dragon's Sanctum 제단 | ✔ |
| 3 | **Belm** (시미터) | +2. 오프핸드 추가 공격용 | Lower City, Elerrathin's Home 지하 (자물쇠 DC 18) | ▲ |
| — | Cloak of Protection | AC +1, 모든 내성 +1 | 상인 구매 | ▲ |

> **⚠ Resonance Stone**: **소지자 본인도 정신 피해에 취약**해집니다 ✔. Tav가 직접 들지 말고 Karlach가 들거나 적 무리에 던져두세요. **회차에 따라 안 나올 수 있습니다.**
>
> **⚠ 갑옷**: Adamantine **Splint**(판금, AC 18)는 **중갑 숙련이 필요**합니다 ✔. 순수 워락은 못 입으니 **Scale Mail(중형)**을 쓰세요. Helldusk Armour도 중갑이라 불가합니다.

### 7-2. Shadowheart — Light Domain Cleric (WIS)

| 액트 | 아이템 | 효과 | 획득 | |
|---|---|---|---|---|
| 1 | **Hellrider's Pride** (장갑) | 힘 내성 +1 / **다른 대상을 치유하면 그 대상이 2턴간 타격·관통·참격 저항** | Zevlor (Secluded Chamber) — 루팅 / 훔치기 / Kagha 퀘스트 보상 | ✔ |
| 1 | **Blood of Lathander** (메이스) ★ | **+3** / 20ft 성스러운 빛 — 전투 중 악마·언데드는 **건강 내성 DC 14** 실패 시 **실명** / **HP 0이 될 때 1회·긴휴식: 본인 2d6 + 9m 내 아군 1d6 회복** / **Sunbeam 6레벨 주문 1회·긴휴식** | [12-1](#12-1-blood-of-lathander-라샌더의-피) | ✔ |
| 1~ | 반판금 + 방패 | AC 19 | 상인 | |
| 2 | **Callous Glow Ring** | **밝게 빛나는 대상에게 +2 광휘 피해** | **Gauntlet of Shar** — Balthazar 근처 금고방 화려한 상자 | ✔ |
| 2 | **Mirror of Loss** ★ | WIS +2 | Gauntlet of Shar | ✔ |

> **Hellrider's Pride는 Bless가 아니라 물리 피해 저항을 겁니다** ✔. Healing Word 한 번으로 전선 캐릭터의 물리 피해를 절반으로 만드는 장갑입니다 — 실제 가치는 더 높습니다.
>
> **Blood of Lathander는 파티 전원 부활이 아닙니다** ✔. **착용자 본인**이 쓰러질 때 1회 살아나고, 주변 아군은 1d6만 회복합니다. 그래도 **Sunbeam(6레벨) 무료 1회**와 **언데드 광역 실명**이 붙어 액트2에서 최상급입니다.
>
> 메이스 피해는 **힘 보정**이라 STR 8이면 -1입니다. 때리려고 드는 무기가 아니라 **아우라·Sunbeam·자기 부활**을 위한 무기입니다.

### 7-3. Gale — Evocation Wizard (INT)

| 액트 | 아이템 | 효과 | 획득 | |
|---|---|---|---|---|
| 1~ | 주문 두루마리 전부 | **영구 습득.** 방출계는 학습 비용 반값 | 상인 / 전리품 | ✔ |
| 2 | **Mirror of Loss** ★ | INT +2 | Gauntlet of Shar | ✔ |
| 3 | **Amulet of Greater Health** ★ | **건강 23 고정 + 건강 내성 이점** | House of Hope, Archive **가장 왼쪽 받침대** — 손재주 **DC 20**으로 함정 해제 | ✔ |
| 3 | **Markoheshkir** (쿼터스태프) ★ | **+2 / 주문 내성 DC +1 · 주문 명중 +1 / Arcane Battery(다음 주문 슬롯 무소모, 긴휴식) / Kereska's Favour(원소 강화, 짧은휴식)** | Ramazith's Tower — **See Invisibility로 레버 노출 + Arcana DC 20**으로 무적의 구체 해제 | ✔ |
| 3 | Sorcerous Sundries 두루마리 싹쓸이 | | 구매 | |

### 7-4. Karlach — Battle Master Fighter (STR)

| 액트 | 아이템 | 효과 | 획득 | |
|---|---|---|---|---|
| 1 | 아무 Greatsword / Glaive | **의존도 0** | 전리품 | |
| 1 | **Adamantine Splint Armour** ★ | **AC 18 / 치명타 피격 불가 / 모든 피해 -2 / 근접 피격 시 공격자 비틀거림 3턴 / 은신 불리** | Grymforge 용광로 (**중갑 숙련 필요** — 파이터는 보유) | ✔ |
| 2 | **Risky Ring** | **모든 공격 굴림에 이점 / 모든 구원 굴림에 불리** | Araj Oblodra — 문라이즈 타워(액트2) 또는 Crimson Draughts 선술집(액트3) | ✔ |
| 2 | **Mirror of Loss** ★ | STR +2 | Gauntlet of Shar | ✔ |
| 3 | Helldusk Armour ★ | AC 21 (중갑) | House of Hope — Raphael 처치 | ▲ |

> **Risky Ring은 "반응 사용 불가"가 아니라 "구원 굴림 불리"입니다** ✔. 파티에 내성 보정 오라가 없으므로 **제어 마법에 걸릴 위험이 커집니다.** GWM 명중이 안정되면 빼는 것도 고려하세요.

### 7-5. 공용 소모품

| 아이템 | 용도 | |
|---|---|---|
| **Scroll of Revivify** | **항상 5장 이상 상비** | |
| **Elixir of Bloodlust** | 처치 시 추가 행동. 집중 불필요 → Haste의 안전한 대안 | ▲ |
| Arrow of Many Targets | 보스전 1라운드 광역 | |
| 기름통 / 연막탄 | 아이템 없이 만드는 제어 | |

> 상인 재고는 긴 휴식마다 갱신됩니다. 손재주로 훔친 뒤 긴 휴식하면 평판이 초기화됩니다.

---

## 8. 영구 능력치 보너스

| 항목 | 시점 | 효과 | |
|---|---|---|---|
| **Hag's Hair** | 액트1 | 능력치 **+1**, **상한을 무시**하는 등급의 보너스 | ✔ |
| **Mirror of Loss** | 액트2 | 능력치 **+2** (상한 **24**). **하수인 포함 파티원 각자 1회** | ✔ |
| **Patriar's Memory** | 액트2 | **매력 +1** (Mirror of Loss와 별개) | ✔ |
| **Withers 리스펙** | 상시 | 종족 제외 전부 변경, 100골드 | |

**배분**: Tav → CHA / Shadowheart → WIS / Gale → INT / Karlach → STR

> **⚠ Mirror of Loss는 실패하면 영구히 못 받습니다.** 절차와 판정은 **[12-5](#12-5-mirror-of-loss-상실의-거울--⚠-실패하면-영구-손실)**를 반드시 읽고 시도하세요.

---

## 9. 명예 기준 운영

### 9-1. Haste(가속) — 기본 루틴에서 제외, 보스전 한정 ✔

**확인된 사실**: **Lethargic**(무기력 — 1턴 행동·이동 불가)은
- 집중이 깨져 Haste가 조기 종료될 때 **그리고**
- **지속시간이 자연 만료될 때에도** 붙습니다 ✔

즉 **Haste는 언젠가 반드시 1턴을 돌려줘야 하는 대출**입니다.

| 상황 | 판단 |
|---|---|
| 잡몹 전투 | **쓰지 마세요** |
| 보스전 | 아래 3개가 동시에 충족될 때만 |
| 조건 1 | Gale이 적 사거리 **밖**에 안전할 것 |
| 조건 2 | 지속시간 내 전투를 **끝낼 수 있을 것** (전투가 끝나면 무기력이 안 옴) |
| 조건 3 | 대상은 **Tav 또는 Karlach** |

**대안**: Elixir of Bloodlust, 또는 그 슬롯에 Hypnotic Pattern / Evard's Black Tentacles.

### 9-2. 전투 5원칙

1. **전투는 전투 시작 전에 끝난다** — 체인 해제 → 은신으로 고지 선점 → 선공권 확보
2. **Shove(밀치기)가 최강 주문이다** — 보너스 행동이라 공짜. 여러 보스가 낙사합니다
3. **제어 > 피해** — Hypnotic Pattern / Web / Evard's Black Tentacles / Hunger of Hadar / Spirit Guardians
4. **집중 주문은 한 캐릭터당 하나** — Bless(Shadowheart) + Hypnotic Pattern(Gale) + Darkness(Tav)
5. **Minor Illusion으로 모으고 Fireball** — Sculpt Spells 덕에 아군은 **0 피해** ✔

### 9-3. 표준 턴 루틴

```
긴 휴식 직후 (전투 전)
     Tav: Shadow Blade 시전 — 가능한 최고 슬롯

1턴  Shadowheart: Bless
     Gale: Hypnotic Pattern 또는 Fireball
     Tav: Hexblade's Curse(보너스 행동) → 접근 + 공격
     Karlach: 돌진 + 공격

2턴  Shadowheart: Spirit Guardians 켜고 전진
     Gale: Fireball / Counterspell 대기
     Tav: 공격 ×2
     Karlach: 공격 ×3 + Precision Attack

3턴~ 정리 / 남은 캐스터 우선 제거
```

**Tav 고정 규칙 2개**
1. **Shadow Blade는 긴 휴식 직후 한 번만.** 전투마다 다시 켜면 슬롯 낭비입니다
2. **Hexblade's Curse는 보스전 첫 보너스 행동.** 짧은 휴식마다 회복됩니다 ✔

**Darkness 판단**
- Shadow Blade는 **약한 빛만으로도 이점 조건 성립** ✔ → 던전·야간·그림자 저주 지역에서는 불필요
- 밝은 실외 + 적 원거리 화력이 셀 때만 깔아 **적 공격에 불리**까지 얹으세요
- 파티원은 어둠 속을 못 봅니다. **Tav 혼자 들어가는 공간**으로만

---

## 10. 보스별 메모 ✔

> 전부 bg3.wiki 원문 대조본입니다. **이전 판본의 이 항목은 기억 기반이었고 절반 이상이 틀렸습니다.**

### 액트 1

**Phase Spider Matriarch**
- 전투 전에 **알집 3무더기를 미리 파괴**하세요. `Matriarch's Call`(2턴마다 재사용)로 근처 알을 전부 부화시킵니다
- **불화살로 알집을 태우면 근처 거미줄도 같이 사라집니다**
- 거미줄 다리는 불로 파괴 가능 — 위에 서 있을 때 태우면 **낙하 피해 약 45**
- ⚠ **전술가/명예에서는 구덩이로 밀어 떨어뜨릴 수 없습니다** — 즉시 순간이동으로 돌아옵니다
- 그녀의 피해는 대부분 **독**이고 본인은 **독 면역**입니다. 독 저항을 미리 걸고, 광역 독 분사를 피하려 파티를 벌려 세우세요
- `Ethereal Jaunt` — 턴당 22m 순간이동. 추격하지 말고 진형을 유지하세요

**Nere**
- ⚠ **붕괴 지점에서 처음 교신한 뒤 빠른 이동이나 긴 휴식을 2회 이상 하면 네레가 죽습니다.** 지체하지 마세요
- 정신 지배 계열(Dunnol, Fonmara)을 **먼저** 제거
- `Shield of Screams` — +3 AC + 피격자에게 정신 피해 반사
- ⚠ **명예 모드 `Psionic Visage`** — 물리 피해 면역 분신 생성. **마력탄(Magic Missile) 두루마리**로 빠르게 정리
- 용암이 인접하지만 **네레는 운동 +9 · Muscular라 밀치기 DC 24**. 밀어 넣기는 비현실적이니 잡졸에게만 쓰세요

**Grym** — [12-2](#12-2-adamantine-forge-아다만틴-용광로) 참고
- **정면 싸움 금지.** 용암 위에 세워 `Superheated`(타격 취약) → **레버를 원거리로 쏴서** 망치 내려찍기

### 액트 2

**Ketheric Thorm**
- ★ **무적의 근원은 밤의 노래(Aylin)입니다.** 최종 대면 전에 **샤의 시련장에서 아일린을 죽이거나 구해야** 합니다. 안 하면 아무리 때려도 안 죽습니다
- 액트2에서 **총 3회** 싸웁니다 — 문라이즈 옥상 → 마인드 플레이어 군체 → Apostle of Myrkul
- 맹세파기자 팔라딘이라 **스마이트 + 오라 + 언데드 소환**. `Deadly Orders`로 아군에게 집중 공격을 지시합니다
- 보스지만 **무장 해제·넘어뜨리기가 통합니다**

**Apostle of Myrkul**
- ⚠ **물리 저항**: 참격·관통·비마법 타격 + **사령·냉기 저항**. 독 면역, 매혹·공포·넘어짐·무력화 면역
  - → **Tav의 Shadow Blade(정신)와 Shadowheart의 광휘가 이 전투의 주력**입니다. Karlach의 대검(참격)은 반감됩니다
- **네크로마이트를 먹어치워 강력한 주문을 얻습니다.** 먹기 전에 잡졸을 정리하세요
- `Call of the Damned` — 3d10 사령 + **9m 끌어당김**(힘 내성)
- `Reaper's Scythe` — 2d12+7 참격 + 3d6 사령 + 넉백(힘 내성)
- `Gaze of the Dead` — 보너스 행동, 30m, 4d8 사령 + 공포(건강 내성). **명예에서는 전설 행동으로 1회 추가**

### 액트 3

**Cazador Szarr**
- ⚠ **"의식 원 위에 서지 말 것"은 틀렸습니다. 반대로 올라가서 점거해야 합니다**
  - 갇힌 뱀파이어 스폰 **7명**이 의식 공급원입니다. 카자도르가 하나씩 흡수할 때마다 **이동 +1m, 임시 HP +10, 공격·주문에 +1d10 사령**
  - **파티원이 원을 점거하면 그 혜택을 대신 받고 카자도르에게서 빼앗습니다.** 아스타리온 원은 턴당 보너스 행동, Violet 원은 +5 AC, Yousen 원은 턴당 3d8 회복
- ⚠ **3턴 안에 방해하지 않으면** 카자도르가 승천하고 **아스타리온이 영구 사망**합니다. 아스타리온부터 풀어주세요
- ★ **햇빛 과민증(Sunlight Hypersensitivity)** — 햇빛 계열 주문이 안개 형태를 흩고 공격에 불리를 겁니다
  - → **Shadowheart의 `Daylight`(빛 영역, 클레릭 5레벨 상시 준비)가 이 전투의 정답 카드**입니다
- 잡졸: 박쥐 6(**매 라운드 6 추가**), Chatterteeth, 타락한 구르 사냥꾼 3, 포식자 늑대인간 4 → `Spirit Guardians` · `Wall of Fire`로 관리
- `Call Lightning` 3d10을 **슬롯 소모 없이 10턴간** 반복합니다. 뭉쳐 있지 마세요

**Orin**
- ⚠ **"변신 + 은신 반복"은 틀렸습니다.** 신전 전투에서는 **처음부터 끝까지 슬레이어 형태**이고, 은신은 다크어지 1:1 결투에서만 나옵니다
- ★ **핵심은 `Unstoppable` 중첩(7~12)입니다. 이게 피해 한 번을 1로 깎습니다**
  - → **마력탄(Magic Missile)처럼 여러 번 때리는 주문으로 중첩을 벗기세요.** 한 방이 큰 공격은 낭비입니다
  - → **바알의 사신(Reaper) 6명을 죽여야 중첩이 재충전되지 않습니다.** 처음엔 `Sanctuary`로 보호받습니다
- Magic Resistance(내성에 이점) + Immutable Form(변신 계열 면역)
- 명예 전설 행동 `Murderous Retort` — 라운드 1회 즉시 반격

**Gortash**
- ⚠ **역장 커튼은 두 종류이고 반대로 다뤄야 합니다**
  - `Micromodron Force Curtain` → 고르타쉬에게 **피해 면역·저항 부여**. **파괴하세요**
  - `Deranged Force Curtain`(고장난 것) → 오히려 **그의 방어를 깎습니다**. **건드리지 마세요**
- ⚠ **HP 75%에서 `Invoke the Black Hand` 발동** → **임시 HP 150 + 천둥·화염·역장 면역 + Avatar of Tyranny(힘 +4, 추가 공격)**. 준비 없이 트리거하지 마세요
- Steel Watcher는 선제권 +6에 **자폭(Self-Detonate)**. 적 무리 쪽으로 유인해 터뜨리세요
- 고르타쉬 본인이 **각성(Alert)** 보유 — 선제권 +10, 기습 불가. **우리도 선제권을 올려야 합니다**(Karlach의 Alert)
- 전술가에서는 **전설 저항 — 다음 3회 내성 굴림 +10**
- 천둥 저항 / 석화 면역. **실명·마비·넘어짐·기절은 통합니다**
- ★ 집무실에서는 **밖으로 유인**하고 출입구에 **`Hunger of Hadar`(Tav)** 같은 지역 봉쇄를 깔아두세요. 접근은 **`Greater Invisibility`(Gale)**

**Raphael** — [12-4](#12-4-house-of-hope-절망의-집) 참고
- ⚠ **"기둥 4개를 부숴야 본체에 피해가 들어간다"는 틀렸습니다. 기둥은 무적 장치가 아니라 버프 장치입니다**
  - 기둥 1개당 **+1d12 화염 피해, 민첩 +3, 소울 충전 1, `Consume Souls` 시 3d6 회복**
  - 4개 다 살아 있으면 **민첩 +12, 화염 +4d12, AC 27**
- ⚠ **단, 기둥을 파괴하면 그 대가로 소울 충전 1개를 주고 `Ascended Fiend` 변신이 앞당겨집니다.** 변신 후에는 **모든 주문이 화염 저항·면역을 무시**합니다. 준비된 상태에서 파괴 타이밍을 잡으세요
- ⚠ **광휘 피해는 `Infernal Retribution`을 유발해 시전자에게 `Burning`을 겁니다** → **Shadowheart의 광휘 주력은 이 전투에서 역효과**입니다. 화염·물리·정신으로 돌리세요
- 잡졸: Korrilla + 복수의 캠비온 6 (+ 계약에서 풀어준 경우 Yurgir)
- 명예 전설 행동 `Beguiling Rebuke`(지혜 내성 매혹 — 매혹되면 라파엘을 공격 못 함) / `Soul Ascension`
- 사전 준비: **회복 수도꼭지로 유사 긴 휴식** + 버프, **기둥 옆에 연막화약통 배치**

**Ansur** — [12-3](#12-3-helm-of-balduran-발두란의-투구) 참고. **투구만 원하면 싸우지 않아도 됩니다**

**Netherbrain**
- 구조: **카르서스의 왕관까지 올라가 주문을 전달 → 정신 속으로 진입 → 내부에서 최종전**. 포탈은 **파티원·소환수·오르페우스/황제만** 통과
- ⚠ **승리 조건은 "플랫폼이 전부 파괴되기 전에 잡는 것"입니다**
  - `Orb of Negation` — 30m 내를 소멸시키고 **1라운드 뒤 그 아래 플랫폼을 파괴**
  - → **`Globe of Invulnerability`(Gale, 6레벨)로 위험한 플랫폼을 보호**할 수 있습니다
- ⚠ **`Retributive Brainquake`(반응)** — **매 턴 첫 피격 시** 30m에 10d6 정신 피해 + `Mindbroken`. 공격 횟수와 무관하게 라운드 1회
- ⚠ **명예 전용 `Aegis of the Absolute`** — **그 라운드에 받은 모든 피해 타입에 다음 턴까지 면역**. 피해 타입을 돌려가며 때려야 합니다
- 전술가 시작 HP **450**. 모픽 풀 지배 시도에서 **자연 20**이 떴으면 `Against All Odds`로 **-20%**
- 잡졸: 지배된 레드 드래곤, 일리시드 비술사 4, 촉수 4, **4턴 뒤 노틸로이드 소환**
- ★ **포탈 진입 전 `Feather Fall`**을 걸면 느린 근접 캐릭터도 바로 뛰어내릴 수 있습니다. `Dimension Door` / `Misty Step`으로 표시된 플랫폼에서 탈출하세요

---

## 11. 출발 체크리스트

**캐릭터 생성**
- [ ] Tav: Half-Orc(또는 Drow) / Warlock / 패트론 **The Hexblade** / CHA 17
- [ ] 소마법 Eldritch Blast + Minor Illusion

**게임 켜고 먼저 확인할 3가지** ▲
- [ ] Warlock 5 결속 목록에 **Thirsting Blade**가 있는지 (없으면 Deepened Pact 자동)
- [ ] **Shadow Blade를 Bind Pact Weapon으로 결속 가능한지** → 불가면 DEX 16
- [ ] **Lifedrinker**가 검의 계약 선행을 요구하는지

**액트 1**
- [ ] Warlock 3 — **Pact of the Blade + Shadow Blade + Darkness** ← 빌드 가동
- [ ] Warlock 5 — **추가 공격 + Shadow Blade 3d8**
- [ ] Shadowheart → **Light Domain** 리스펙 (**DEX 14 필수** — 중갑 못 입음)
- [ ] Gale → **Evocation** 리스펙
- [ ] Karlach → **Battle Master Fighter** 리스펙
- [ ] Zevlor → **Hellrider's Pride** (Shadowheart)
- [ ] 에델 아줌마 → **Hag's Hair = Tav의 CHA**
- [ ] Grymforge → **Adamantine Scale Mail(Tav) + Splint(Karlach)** — 미스랄 광석 2개
- [ ] Rosymorn Monastery → Dawnmaster's Crest → Creche Y'llek → **Blood of Lathander**

**액트 2**
- [ ] Gauntlet of Shar → **Mirror of Loss 4명 전원** (⚠ 12-5 먼저 읽기)
- [ ] Gauntlet of Shar → **Callous Glow Ring** (Balthazar 근처 금고방)
- [ ] Araj Oblodra → **Risky Ring** (Karlach)
- [ ] 마인드 플레이어 군체 → **Resonance Stone**
- [ ] Warlock 9 도달 → **Shadow Blade 4d8**

**액트 3**
- [ ] Wyrmway 시련 4개 → **Helm of Balduran**
- [ ] Ramazith's Tower → **Markoheshkir** (See Invisibility + Arcana DC 20)
- [ ] Elerrathin's Home 지하 (자물쇠 DC 18) → **Belm**
- [ ] Helsik에게 의식 재료 구매 → **House of Hope** → Amulet of Greater Health
- [ ] Sorcerous Sundries 두루마리 싹쓸이 (Gale)

---

## 12. 아이템 획득 상세 절차

### 12-1. Blood of Lathander (라샌더의 피)

**성능** ✔

| 항목 | 내용 |
|---|---|
| 종류 | **+3 메이스** (한손), 1d6+3 타격 + **힘 보정** |
| **Lathander's Light** | 20ft 성스러운 빛. 전투 중 빛 안의 **악마·언데드**는 **건강 내성 DC 14** 실패 시 **실명** |
| **Lathander's Blessing** | **긴 휴식당 1회.** HP가 0이 될 때 **본인 2d6 회복**, **9m 내 아군은 1d6 회복** |
| **Sunbeam** | **6레벨 주문으로 시전, 긴 휴식 회복** (연속 턴 재시전 불가) |
| Concussive Smash | 무기 동작 — 피해 + 현혹, 짧은 휴식 회복 |

> **파티 전원 부활이 아닙니다.** 착용자 본인의 자기 부활 1회 + 주변 소량 회복입니다. 그래도 **Sunbeam 무료 1회**와 **언데드 광역 실명**만으로 액트2 최상급입니다.

**위치**: Mountain Pass → **Rosymorn Monastery**(퍼즐) → 그 아래 **Creche Y'llek**(메이스 본체)

**1단계** — Dawnmaster's Crest 획득 (로산 수도원) ✔

스테인드글라스 창 4개 + 제단 4개가 있는 방.

1. **Ceremonial Sword(의식용 검)는 이미 북쪽 제단에 있습니다.** 건드리지 마세요
2. 나머지 3개를 수도원 곳곳에서 수집 — Battleaxe, Warhammer, Mace
3. **배치**

   | 무기 | 제단 |
   |---|---|
   | Ceremonial Sword | 북쪽 (이미 놓여 있음) |
   | **Ceremonial Battleaxe** | **남서쪽** |
   | **Ceremonial Warhammer** | **북동쪽** |
   | **Ceremonial Mace** | **남동쪽** |

4. 가짜 벽이 열리고, 숨겨진 공간의 주머니 안에 **Dawnmaster's Crest**

> **스킵**: 의식용 검 제단 옆 패널을 수동 감지로 발견 → **Sleight of Hand DC 30**. **Guidance 필수.**

**2단계** — Creche Y'llek에서 회수 ✔

1. 메이스 받침대의 **소켓에 Dawnmaster's Crest를 먼저 끼웁니다** → 보안 해제
2. 그 다음 메이스를 집습니다

> ### ⚠ 문장 없이 집으면
> - **4턴 안에** 수도원 밖으로 탈출하거나 **Lathander Solar Machine 4대를 전부 파괴**해야 합니다
> - 실패하면 수도원 붕괴
> - **크레쉬의 기스양키 전원이 적대로 전환**됩니다

---

### 12-2. Adamantine Forge (아다만틴 용광로)

**성능** ✔

| 장비 | 효과 | 숙련 |
|---|---|---|
| **Adamantine Splint Armour** | **AC 18** / 치명타 피격 불가 / **모든 피해 -2** / 근접 피격 시 공격자 **비틀거림 3턴** / 은신 불리 | **중갑** |
| **Adamantine Scale Mail** | **AC 16 + 민첩(최대 +2)** / 치명타 피격 불가 / **모든 피해 -1** / 근접 피격 시 **비틀거림 2턴** / 은신 불리 | **중형** |

> **Tav(순수 워락)는 중갑 숙련이 없으므로 Scale Mail**, **Karlach(파이터)는 Splint**를 가져가세요.

**위치**: Underdark → **Grymforge**

**1단계** — Mithral Ore 2개 ✔

- 광맥은 게임 전체에 **2개**뿐이며 둘 다 **Ancient Forge 웨이포인트 근처**
- **곡괭이가 아니라 활로 광맥을 쏘면** 광석이 드러납니다
- 1번: 용광로 옆 계단에서 보이는 바위 — 쏘면 **마그마 메피트 스폰**
- 2번: Ancient Forge 지점에서 아래로 내려가면 적들 너머

> 광석 1개당 장비 1개. **2개면 Scale Mail + Splint 둘 다** 제작 가능합니다.

**2단계** — Mould(주형) ✔

그림포지 전역에 **6종**: Splint Armour, Scale Mail, Shield, Longsword, Scimitar, Mace

**3단계** — 제작 ✔

1. **Mould Chamber**(중앙 기둥의 팔) → 주형 삽입
2. **Crucible**(중앙 기둥 본체) → Mithral Ore 투입
3. 남쪽 **Forge Lever** 당기기 → 망치 내려찍힘, 플랫폼 하강

**4단계** — Grym ✔

첫 제작 시 수호 골렘 Grym 등장. **정면 싸움 금지.**

1. Grym을 **용암 위에 서게** 유도 → **Superheated** = **타격 피해 취약**
2. 그 상태에서 **Forge Lever를 원거리로 쏴서** 망치를 떨어뜨림
3. 반복하면 정상 전투 없이 처치

> Karlach의 **화염 저항**이 이 구간에서 그대로 값을 합니다.

---

### 12-3. Helm of Balduran (발두란의 투구)

**성능** ✔

| 항목 | 내용 |
|---|---|
| **AC +1, 모든 구원 굴림 +1** | |
| **전투 중 매 턴 시작마다 2 HP 회복** | 전투 밖에서는 발동 안 함 |
| **공격자가 치명타를 낼 수 없음** | |
| **기절 면역** | ※ Stunning Gaze에는 안 걸린다는 버그 보고 있음 |

**위치**: **The Dragon's Sanctum** — 앤서 옆 **돌 제단 위** ✔

**절차** ✔

1. Wyrm's Rock 아래 **Wyrmway**에서 **시련 4개** 통과 → Dragon's Sanctum 개방
   - **Courage(용기) / Insight(통찰) / Strategy(전략) / Justice(정의)**
2. 앤서의 방 진입

**★ 앤서와 싸우지 않고 투구만 먹는 법 ✔**

1. 용과 **거리를 유지**하며 측면으로 우회
2. **힘 높은 캐릭터 1명을 체인 해제**
3. **점프로 제단까지 건너가** 투구를 집습니다
4. 제단은 압력판이라, 투구를 들면 **환영 벽이 열리며 Wyrm's Rock Prison 쪽 통로**로 빠져나올 수 있습니다

> 앤서를 잡으면 Balduran's Giantslayer(대검)를 추가로 얻습니다 ▲. 명예 기준이면 **투구만 먹고 나오는 쪽**을 권합니다.

---

### 12-4. House of Hope (절망의 집)

**절차**

1. **Raphael의 계약을 거부**
2. **Devil's Fee**의 상인 **Helsik**에게서 의식 재료 구매
3. 지정 장소에서 의식 → 전송

**Amulet of Greater Health** ✔

| 항목 | 내용 |
|---|---|
| 효과 | **건강 23 고정** + **건강 내성 굴림 이점** |
| 위치 | **Archive의 가장 왼쪽 받침대** |
| 회수 | **Sleight of Hand DC 20**으로 함정 해제 — 또는 같은 무게의 물건을 올려 바꿔치기 |

> **Orphic Hammer, Soul-Sworn Contract, Hope는 건드리지 않은 상태**여야 한다는 조건이 붙습니다 ✔

> Raphael 전투는 **Soul Pillar 4개를 먼저 파괴**해야 본체에 피해가 들어갑니다. 전투 없이 보물만 챙기고 나오는 것도 가능합니다.

---

### 12-5. Mirror of Loss (상실의 거울) — ⚠ 실패하면 영구 손실

**위치**: 액트2, **Gauntlet of Shar**

**절차** ✔

1. **용도 파악** — **Religion DC 20** 또는 **Arcana DC 25** 판정, 또는 관련 쪽지를 읽기
2. **샤에게 기도** — **Religion DC 25** 성공 시 **능력치 +2**
3. 기억을 최대 6개까지 희생
4. 희생한 능력치에 **긴 휴식까지 -2 (Stolen Vigour)** 패널티

| 항목 | 내용 |
|---|---|
| 보너스 | 능력치 **+2**, 상한 **24** |
| 대상 | **하수인 포함 파티원 각자 1회씩** |
| 별도 | **Patriar's Memory** — 매력 +1 (거울 보너스와 별개) |

> ### ⚠ **Religion DC 25에 실패하면 그 캐릭터는 영구히 +2를 못 받습니다** ✔
> 반드시 아래를 갖추고 시도하세요.
> - **종교(Religion) 숙련이 있는 캐릭터**로 시도 (Shadowheart)
> - **Guidance(+1d4)** 선행
> - 판정 보조 수단이 더 있으면 추가로

