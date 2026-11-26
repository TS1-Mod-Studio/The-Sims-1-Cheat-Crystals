# The Sims 1 – 作弊水晶

[English](README.md) | [Polski](README.pl.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Español](README.es.md) | [Italiano](README.it.md) | [Português (Brasil)](README.pt-BR.md)  
[Nederlands](README.nl.md) | [Dansk](README.da.md) | [Svenska](README.sv.md) | [Norsk (bokmål)](README.nb.md) | [Suomi](README.fi.md)  
[日本語](README.ja.md) | [한국어](README.ko.md) | [ไทย](README.th.md) | [简体中文](README.zh-CN.md) | **繁體中文**

![版本](https://img.shields.io/badge/%E7%89%88%E6%9C%AC-1.0.0-23734f)
![遊戲](https://img.shields.io/badge/%E9%81%8A%E6%88%B2-The%20Sims%20Legacy%20Collection-23734f)
![物件](https://img.shields.io/badge/%E7%89%A9%E4%BB%B6-7-23734f)
![語言](https://img.shields.io/badge/%E8%AA%9E%E8%A8%80-17-23734f)

這套模組為 The Sims 新增七種具動畫效果的物件。每顆水晶售價 §1，可在購買模式的「雜項 → 全部 (∞)」找到。將水晶放在地段上，選取一位模擬市民，再按一下水晶開啟選單。

![作弊水晶](TS1-Cheat-Crystals-preview.png)

## 下載

**[下載作弊水晶 – GitHub Releases](../../releases/latest)**

請從最新發行版本的 Assets 區域下載 ZIP 檔案，其中包含全部七個 IFF 檔案及17種語言的說明。可使用 SHA-256 檔案驗證壓縮檔的完整性。

`TS1-Cheat-Crystals-*-multi.zip`

## 水晶及其功能

<details>
<summary><strong>📘 技能水晶</strong></summary>

個別設定六項技能為0至10級，或把所有技能設為最高或歸零。「最高」即10級。

檔案: `TS1SkillsCrystal.iff`

</details>

<details>
<summary><strong>📊 需求水晶</strong></summary>

將所有需求設為最高、最低或50%，補滿八項需求的其中一項，耗盡精力，或凍結及解除凍結。凍結會抵銷數值的升降，維持啟用時的數值。載入存檔後，需重新啟用凍結。遊戲也會重新計算「房間」數值，因此可能短暫變動。

檔案: `TS1NeedsCrystal.iff`

</details>

<details>
<summary><strong>💰 資金水晶</strong></summary>

為目前家庭增加或扣除 §100、§1,000、§10,000、§50,000 或 §100,000，或增加 §1,000,000、將資金歸零。餘額最低為 §0，最高為 §9,999,999。完成歸零操作須先解除暫停。

檔案: `TS1FundsCrystal.iff`

</details>

<details>
<summary><strong>💗 關係水晶</strong></summary>

管理友誼、敵對、暗戀、愛情和家庭成員。可新增1、2、5或10位新朋友或普通熟人。朋友雙方的日常／長期關係值為75／75，普通熟人則為0／0。請在完整聯絡人清單中查找普通熟人。人選來自現有鄰里居民，符合條件的人數不足時會顯示實際新增人數。不會建立新的模擬市民或將他們召到地段上。戀愛功能僅適用於符合條件的成年模擬市民。

檔案: `RelationshipCrystal.iff`

</details>

<details>
<summary><strong>💼 職業水晶</strong></summary>

可選擇20種職業及1至10級，轉換職業會從1級開始。適用於目前家庭中選取的成年模擬市民，須在工作以外的時間使用。調整職業不會發放升遷獎金。

檔案: `TS1CareerCrystal.iff`

</details>

<details>
<summary><strong>⭐ 名望水晶</strong></summary>

以半顆星為單位將名望設定在0至5顆星之間，也可開始或結束明星生涯。開始明星生涯會取代普通工作。設為0顆星會保留經紀人，結束明星生涯則會移除經紀人。

檔案: `TS1FameCrystal.iff`

</details>

<details>
<summary><strong>🔮 魔法水晶</strong></summary>

可個別或成組新增魔法幣及31種材料，數量可選1、5、10、25或100。物品放入目前家庭中選取的模擬市民（包含兒童）的隨身物品欄。每一項上限為32,767。不提供魔杖或法術。

檔案: `TS1MagicCrystal.iff`

</details>

## 安裝

1. 關閉遊戲並解壓縮 ZIP。
2. 開啟你平常啟動的遊戲安裝資料夾，也就是包含 `sims.exe` 的資料夾。請勿使用「文件」資料夾。
3. 將解壓縮後 `Downloads` 裡的 `TS1CheatCrystals` 複製到遊戲的 `Downloads` 裡。若尚無 `Downloads`，請先建立。正確路徑的範例為 `<包含 sims.exe 的資料夾>\Downloads\TS1CheatCrystals\TS1FundsCrystal.iff`。避免出現 `Downloads\Downloads`。每顆水晶各有一個 IFF 檔案，只需複製想使用的水晶。`README` 可留在其他地方。
4. 每種水晶在遊戲中只保留一份。請檢查舊資料夾 `TS1CrystalVariants`、`TS1RelationshipCrystal`、`TS1CareerCrystal`、`TS1FameCrystal` 與 `TS1MagicCrystal`。改檔名仍會發生物件識別碼衝突。若已有修改版，請先確認要保留哪個版本再覆寫。
5. 重新啟動遊戲，在購買模式選擇「雜項 → 全部 (∞)」。

## 解除安裝

如果凍結了需求，請先解除凍結。在使用過的地段賣掉水晶，儲存後關閉遊戲，再刪除 `Downloads\TS1CheatCrystals` 或選定的 IFF 檔。刪除水晶後，存檔已記錄的資金、關係、技能等變更會保留。

## 相容性與語言

本模組適用於包含所有擴充套件的 The Sims Legacy Collection。舊版、其他平台及只安裝主程式的環境未經驗證。名望功能需要 Superstar，魔法功能需要 Makin’ Magic。選單、說明及對話方塊提供17種語言，並隨遊戲的語言設定切換。

此套件不修改 `sims.exe`。

## 意見回饋與錯誤回報

發現問題或有建議？請[建立 Issue](../../issues)，並註明遊戲版本、語言、模組版本、相關水晶及問題重現步驟。

## 免責聲明

這是由玩家製作的非官方模組，與 Electronic Arts 或 Maxis 無關。
