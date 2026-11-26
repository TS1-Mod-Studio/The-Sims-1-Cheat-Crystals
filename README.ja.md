# The Sims 1 – チートクリスタル

[English](README.md) | [Polski](README.pl.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Español](README.es.md) | [Italiano](README.it.md) | [Português (Brasil)](README.pt-BR.md)  
[Nederlands](README.nl.md) | [Dansk](README.da.md) | [Svenska](README.sv.md) | [Norsk (bokmål)](README.nb.md) | [Suomi](README.fi.md)  
**日本語** | [한국어](README.ko.md) | [ไทย](README.th.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md)

![バージョン](https://img.shields.io/badge/%E3%83%90%E3%83%BC%E3%82%B8%E3%83%A7%E3%83%B3-1.0.0-23734f)
![ゲーム](https://img.shields.io/badge/%E3%82%B2%E3%83%BC%E3%83%A0-The%20Sims%20Legacy%20Collection-23734f)
![オブジェクト](https://img.shields.io/badge/%E3%82%AA%E3%83%96%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88-7-23734f)
![言語](https://img.shields.io/badge/%E8%A8%80%E8%AA%9E-17-23734f)

アニメーション付きのオブジェクト7種類です。各クリスタルは §1 で、購入モードの「その他 → すべて (∞)」にあります。区画に置き、シムを選んでクリスタルをクリックするとメニューが開きます。

![チートクリスタル](TS1-Cheat-Crystals-preview.png)

## ダウンロード

**[チートクリスタルをダウンロード – GitHub Releases](../../releases/latest)**

最新リリースの Assets 欄から ZIP ファイルをダウンロードしてください。7種類すべての IFF ファイルと17言語の説明書が含まれています。SHA-256 ファイルでアーカイブの整合性を確認できます。

`TS1-Cheat-Crystals-*-multi.zip`

## クリスタルの種類と使い方

<details>
<summary><strong>📘 スキルのクリスタル</strong></summary>

6種類のスキルを個別にレベル0～10に設定するか、すべて最大または0に設定できます。「最大」はレベル10です。

ファイル: `TS1SkillsCrystal.iff`

</details>

<details>
<summary><strong>📊 欲求のクリスタル</strong></summary>

全欲求の最大・最小・50%設定、8種類のうち1つの回復、体力の全消費、欲求の固定・解除ができます。固定中は増減が打ち消され、有効にした時点の値を保ちます。セーブを読み込んだら再度有効にしてください。「部屋」の値はゲーム側でも再計算されるため、一時的に変動する場合があります。

ファイル: `TS1NeedsCrystal.iff`

</details>

<details>
<summary><strong>💰 所持金のクリスタル</strong></summary>

世帯の所持金を §100、§1,000、§10,000、§50,000、§100,000 ずつ増減できます。§1,000,000 の追加や残高のリセットも可能です。下限は §0、上限は §9,999,999 です。リセットを完了するには一時停止を解除してください。

ファイル: `TS1FundsCrystal.iff`

</details>

<details>
<summary><strong>💗 人間関係のクリスタル</strong></summary>

友情、敵対、片思い、恋愛、世帯に関する操作ができます。1人、2人、5人、10人の友人または中立の知り合いを追加できます。双方の日常／生涯の関係値は友人で75／75、知り合いで0／0です。知り合いは連絡先の全一覧に表示されます。既存の住人から選び、対象者が足りなければ追加した実際の人数を表示します。新しいシムの作成や区画への呼び出しは行いません。恋愛は条件を満たす成人のシムが対象です。

ファイル: `RelationshipCrystal.iff`

</details>

<details>
<summary><strong>💼 キャリアのクリスタル</strong></summary>

20種類の職業とレベル1～10を選べます。職業を変えるとレベル1から始まります。現在の世帯で選択中の成人の人間シムが勤務外に使用できます。昇進ボーナスは支給されません。

ファイル: `TS1CareerCrystal.iff`

</details>

<details>
<summary><strong>⭐ 名声のクリスタル</strong></summary>

名声を0～5の範囲で0.5つ星ずつ設定し、スターの仕事を始めたり辞めたりできます。開始時に通常の仕事は置き換わります。0つ星にするとエージェントは残り、スターの仕事を辞めるといなくなります。

ファイル: `TS1FameCrystal.iff`

</details>

<details>
<summary><strong>🔮 魔法のクリスタル</strong></summary>

マジコインと31種類の材料を個別またはまとめて追加できます。数量は1、5、10、25、100です。現在の世帯で選択中の人間シム（子どもを含む）の持ち物に追加されます。各項目の上限は32,767です。杖や呪文は追加されません。

ファイル: `TS1MagicCrystal.iff`

</details>

## インストール

1. ゲームを終了し、ZIPを展開します。
2. 普段起動するゲームのインストール先で、`sims.exe` があるフォルダーを開きます。Windows の「ドキュメント」は使用しません。
3. 展開した `Downloads` 内の `TS1CheatCrystals` を、ゲーム側の `Downloads` にコピーします。`Downloads` がなければ作成します。正しい例は `<sims.exe のあるフォルダー>\Downloads\TS1CheatCrystals\TS1FundsCrystal.iff` です。`Downloads` を二重に作らないでください。クリスタル1種類につき IFF が1つあるので、必要なファイルだけコピーできます。
4. 同じクリスタルは、以前のフォルダーも含めて1コピーだけにします。ファイル名を変えてもオブジェクトの識別子は同じです。以前のフォルダーは `TS1CrystalVariants`、`TS1RelationshipCrystal`、`TS1CareerCrystal`、`TS1FameCrystal`、`TS1MagicCrystal` です。改変版がすでにある場合は、残したい版を確認してから上書きしてください。
5. ゲームを再起動し、購入モードで確認します。`README` はゲームのフォルダーにコピーする必要はありません。

## 削除

欲求を固定している場合は解除します。使用した区画のクリスタルを売却し、セーブしてゲームを終了します。`Downloads\TS1CheatCrystals` または選んだ IFF を削除します。削除しても、セーブした所持金や人間関係などの変更は元に戻りません。

## 対応環境と言語

全拡張パックを含む The Sims Legacy Collection 向けです。旧版、他のプラットフォーム、本編のみの環境は未確認です。名声には Superstar、魔法には Makin’ Magic が必要です。メニュー、説明、ダイアログは17言語に対応し、ゲームの言語設定に従います。

`sims.exe` は変更しません。

## フィードバックと不具合報告

不具合や提案がある場合は [Issue を作成](../../issues) してください。ゲームのバージョン、言語、MOD のバージョン、対象のクリスタル、再現手順を記載してください。

## 免責事項

ファンが制作した非公式 MOD であり、Electronic Arts や Maxis とは関係ありません。
