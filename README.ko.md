# The Sims 1 – 치트 수정

[English](README.md) | [Polski](README.pl.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Español](README.es.md) | [Italiano](README.it.md) | [Português (Brasil)](README.pt-BR.md)  
[Nederlands](README.nl.md) | [Dansk](README.da.md) | [Svenska](README.sv.md) | [Norsk (bokmål)](README.nb.md) | [Suomi](README.fi.md)  
[日本語](README.ja.md) | **한국어** | [ไทย](README.th.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md)

![버전](https://img.shields.io/badge/%EB%B2%84%EC%A0%84-1.0.0-23734f)
![게임](https://img.shields.io/badge/%EA%B2%8C%EC%9E%84-The%20Sims%20Legacy%20Collection-23734f)
![물건](https://img.shields.io/badge/%EB%AC%BC%EA%B1%B4-7-23734f)
![언어](https://img.shields.io/badge/%EC%96%B8%EC%96%B4-17-23734f)

움직이는 수정 일곱 가지를 The Sims에 추가합니다. 각 수정은 §1이며 구매 모드의 ‘기타 → 모두 (∞)’에 있습니다. 부지에 수정 하나를 놓은 다음 심을 선택하고 수정을 클릭하면 메뉴가 열립니다.

![치트 수정](TS1-Cheat-Crystals-preview.png)

## 다운로드

**[치트 수정 다운로드 – GitHub Releases](../../releases/latest)**

최신 릴리스의 Assets 항목에서 ZIP 파일을 다운로드하세요. 일곱 가지 IFF 파일과 17개 언어의 설명서가 포함되어 있습니다. SHA-256 파일로 압축 파일의 무결성을 확인할 수 있습니다.

`TS1-Cheat-Crystals-*-multi.zip`

## 수정과 기능

<details>
<summary><strong>📘 기술 수정</strong></summary>

기술 여섯 가지를 각각 0~10단계로 설정하거나 모두 최대 또는 0으로 설정할 수 있습니다. 최대는 10단계입니다.

파일: `TS1SkillsCrystal.iff`

</details>

<details>
<summary><strong>📊 욕구 수정</strong></summary>

전체 욕구를 최대, 최소 또는 50%로 설정할 수 있습니다. 욕구 여덟 가지 중 하나를 채우거나, 에너지를 소진하거나, 욕구 고정을 켜고 끌 수도 있습니다. 고정을 켜면 욕구가 오르거나 내릴 때 그 변화를 되돌려 처음 값을 유지합니다. 저장한 게임을 불러온 후 다시 켜야 합니다. ‘방’ 수치는 게임에서도 다시 계산하므로 잠시 변할 수 있습니다.

파일: `TS1NeedsCrystal.iff`

</details>

<details>
<summary><strong>💰 자금 수정</strong></summary>

현재 가족의 자금에 §100, §1,000, §10,000, §50,000, §100,000을 더하거나 뺄 수 있습니다. §1,000,000을 추가하거나 잔액을 0으로 설정할 수도 있습니다. 한도는 §0에서 §9,999,999까지입니다. 자금을 0으로 설정하려면 게임의 일시 정지를 해제하세요.

파일: `TS1FundsCrystal.iff`

</details>

<details>
<summary><strong>💗 관계 수정</strong></summary>

우정, 적대, 짝사랑, 연애, 가족 구성원 관련 기능이 있습니다. 새 친구나 중립적인 지인을 1명, 2명, 5명 또는 10명 추가할 수 있습니다. 두 심의 일일／장기 관계 점수는 친구가 75／75, 지인이 0／0입니다. 지인은 전체 연락처 목록에서 확인하세요. 기존 마을 주민 중에서 무작위로 고르며 알맞은 주민이 부족하면 실제로 추가한 인원을 표시합니다. 새 심을 만들거나 부지로 부르지 않습니다. 연애 기능은 조건을 충족하는 성인 심만 이용할 수 있습니다.

파일: `RelationshipCrystal.iff`

</details>

<details>
<summary><strong>💼 직업 수정</strong></summary>

직업 20가지와 1~10단계를 선택할 수 있습니다. 다른 직업을 선택하면 1단계부터 시작합니다. 현재 가족에서 선택한 성인 인간 심이 직장에 가 있지 않을 때 사용할 수 있습니다. 직업을 바꿔도 승진 보너스는 지급되지 않습니다.

파일: `TS1CareerCrystal.iff`

</details>

<details>
<summary><strong>⭐ 명성 수정</strong></summary>

명성을 별 0~5개 사이에서 반 개 단위로 설정하거나 스타 경력을 시작하고 끝낼 수 있습니다. 스타가 되면 기존 일반 직업을 대체합니다. 별을 0개로 설정해도 에이전트는 남지만, 스타 경력을 종료하면 에이전트도 사라집니다.

파일: `TS1FameCrystal.iff`

</details>

<details>
<summary><strong>🔮 마법 수정</strong></summary>

마법 동전과 재료 31종을 개별 또는 묶음으로 추가할 수 있습니다. 수량은 1, 5, 10, 25, 100 중에서 선택합니다. 현재 가족에서 선택한 인간 심(어린이 포함)의 소지품에 들어갑니다. 품목별 한도는 32,767개입니다. 마법 지팡이나 주문은 추가하지 않습니다.

파일: `TS1MagicCrystal.iff`

</details>

## 설치

1. 게임을 종료하고 ZIP 파일의 압축을 풉니다.
2. 평소 실행하는 게임의 설치 폴더를 엽니다. sims.exe가 있는 폴더이며, Windows의 ‘문서’ 폴더와는 다릅니다.
3. 압축을 푼 `Downloads` 폴더의 `TS1CheatCrystals를` 게임 설치 폴더의 Downloads에 복사합니다. Downloads가 없으면 새로 만듭니다. 올바른 경로의 예는 `<sims.exe가 있는 폴더>\Downloads\TS1CheatCrystals\TS1FundsCrystal.iff입니다.` `Downloads` 폴더가 두 겹으로 생기지 않도록 확인하세요. IFF 파일 하나가 수정 하나에 해당하므로 원하는 파일만 복사해도 됩니다. `README` 파일은 게임 폴더에 복사할 필요가 없습니다.
4. 게임 폴더에 각 수정의 사본을 하나만 남겨 두세요. 이전 폴더인 `TS1CrystalVariants`, `TS1RelationshipCrystal`, `TS1CareerCrystal`, `TS1FameCrystal`, `TS1MagicCrystal도` 확인합니다. 파일 이름을 바꿔도 물건의 식별자가 같으면 충돌합니다. 수정된 버전을 이미 사용 중이라면 어떤 버전을 유지할지 확인한 후 파일을 교체하세요.
5. 게임을 다시 시작하고 구매 모드에서 수정을 찾습니다.

## 삭제

욕구를 고정했다면 먼저 해제하세요. 사용한 부지에서 수정을 팔고 게임을 저장한 뒤 종료합니다. `Downloads\TS1CheatCrystals` 폴더나 특정 IFF 파일을 삭제하세요. 수정 파일을 삭제해도 이미 저장된 자금, 관계, 기술 등의 변화는 유지됩니다.

## 호환성 및 언어

모든 확장팩을 포함한 The Sims Legacy Collection용입니다. 구버전, 다른 플랫폼, 기본 게임만 설치한 환경은 검증하지 않았습니다. 명성 기능에는 Superstar, 마법 기능에는 Makin’ Magic이 필요합니다. 메뉴, 설명 및 대화 상자는 게임에서 설정한 언어에 맞춰 17개 언어로 표시됩니다.

이 패키지는 sims.exe를 수정하지 않습니다.

## 의견 및 버그 제보

버그를 발견했거나 제안이 있다면 [이슈를 등록](../../issues)해 주세요. 게임 버전, 언어, 모드 버전, 해당 수정과 문제 재현 방법을 적어 주세요.

## 안내

팬이 만든 비공식 모드이며 Electronic Arts 또는 Maxis와 관련이 없습니다.
