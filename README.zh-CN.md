# The Sims 1 – 作弊水晶

[English](README.md) | [Polski](README.pl.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Español](README.es.md) | [Italiano](README.it.md) | [Português (Brasil)](README.pt-BR.md)  
[Nederlands](README.nl.md) | [Dansk](README.da.md) | [Svenska](README.sv.md) | [Norsk (bokmål)](README.nb.md) | [Suomi](README.fi.md)  
[日本語](README.ja.md) | [한국어](README.ko.md) | [ไทย](README.th.md) | **简体中文** | [繁體中文](README.zh-TW.md)

![版本](https://img.shields.io/badge/%E7%89%88%E6%9C%AC-1.0.0-23734f)
![游戏](https://img.shields.io/badge/%E6%B8%B8%E6%88%8F-The%20Sims%20Legacy%20Collection-23734f)
![物品](https://img.shields.io/badge/%E7%89%A9%E5%93%81-7-23734f)
![语言](https://img.shields.io/badge/%E8%AF%AD%E8%A8%80-17-23734f)

这套模组为 The Sims 添加七种带动画的物品。每块水晶售价 §1，在购买模式的“杂项 → 全部 (∞)”中。将水晶放到用地上，选中一位模拟市民，再点击水晶打开菜单。

![作弊水晶](TS1-Cheat-Crystals-preview.png)

## 下载

**[下载作弊水晶 – GitHub Releases](../../releases/latest)**

请从最新发行版本的 Assets 区域下载 ZIP 文件，其中包含全部七个 IFF 文件和17种语言的说明。可使用 SHA-256 文件验证压缩包的完整性。

`TS1-Cheat-Crystals-*-multi.zip`

## 水晶及其功能

<details>
<summary><strong>📘 技能水晶</strong></summary>

将六项技能分别设为0至10级，或将所有技能升至最高或归零。“最高”即10级。

文件: `TS1SkillsCrystal.iff`

</details>

<details>
<summary><strong>📊 需求水晶</strong></summary>

将全部需求设为最高、最低或50%，补满八项需求中的任意一项，耗尽精力，或冻结及解冻需求。冻结后会抵消数值的升降，保持启用时的水平。读取存档后需要重新启用。“房间”也会由游戏重新计算，数值可能短暂波动。

文件: `TS1NeedsCrystal.iff`

</details>

<details>
<summary><strong>💰 资金水晶</strong></summary>

为当前家庭增加或扣除 §100、§1,000、§10,000、§50,000 或 §100,000，也可增加 §1,000,000 或将资金归零。余额最低为 §0，最高为 §9,999,999。请解除暂停以完成归零操作。

文件: `TS1FundsCrystal.iff`

</details>

<details>
<summary><strong>💗 关系水晶</strong></summary>

管理友情、敌对、暗恋、爱情及家庭成员。可添加1、2、5或10位新朋友或普通熟人。朋友双方的日常／长期关系值为75／75，普通熟人为0／0。请在完整联系人列表中查找普通熟人。系统从现有社区居民中选择，符合条件的人数不足时会显示实际添加人数。不会创建新市民或将他们召到用地上。恋爱功能仅适用于符合条件的成年市民。

文件: `RelationshipCrystal.iff`

</details>

<details>
<summary><strong>💼 职业水晶</strong></summary>

可选择20种职业和1至10级。换职业从1级开始。当前家庭中选中的成年模拟市民可在非上班时间使用，调整职业不会发放晋升奖金。

文件: `TS1CareerCrystal.iff`

</details>

<details>
<summary><strong>⭐ 名望水晶</strong></summary>

可按半星为单位将名望设为0至5星，或开始及结束明星生涯。开始明星生涯会取代普通工作。将名望设为0星会保留经纪人，结束明星生涯则会移除经纪人。

文件: `TS1FameCrystal.iff`

</details>

<details>
<summary><strong>🔮 魔法水晶</strong></summary>

可分别或成套添加魔法币和31种材料，数量可选1、5、10、25或100。物品进入当前家庭中选中的模拟市民（包括儿童）的随身物品栏。每种物品上限为32,767。不提供魔杖或法术。

文件: `TS1MagicCrystal.iff`

</details>

## 安装

1. 关闭游戏并解压 ZIP。
2. 打开你平时启动的这份游戏的安装目录，也就是含有 `sims.exe` 的目录。请勿使用“文档”文件夹。
3. 将解压所得 `Downloads` 中的 `TS1CheatCrystals` 复制到游戏的 `Downloads` 中。如没有 `Downloads`，请先创建。正确路径示例为 `<含 sims.exe 的目录>\Downloads\TS1CheatCrystals\TS1FundsCrystal.iff`。避免出现 `Downloads\Downloads`。每块水晶对应一个 IFF 文件，可只复制所需的水晶。`README` 留在游戏目录之外即可。
4. 每种水晶在游戏中只保留一份。请检查旧目录 `TS1CrystalVariants`、`TS1RelationshipCrystal`、`TS1CareerCrystal`、`TS1FameCrystal` 和 `TS1MagicCrystal`。改名也无法解决物品标识冲突。已有改版时，请确认要保留的版本再替换。
5. 重新启动游戏，在购买模式中选择“杂项 → 全部 (∞)”。

## 卸载

如果冻结了需求，请先解冻。在使用过的用地上卖掉水晶，保存并退出游戏，再删除 `Downloads\TS1CheatCrystals` 或其中选定的 IFF 文件。删除水晶不会撤销存档中已有的资金、关系、技能等变化。

## 兼容性与语言

此模组面向附带全部扩展包的 The Sims Legacy Collection。旧版、其他平台及仅安装基础游戏的环境未经验证。名望功能需要 Superstar，魔法功能需要 Makin’ Magic。菜单、说明和对话框支持17种语言，并随游戏语言设置切换。

此包不修改 `sims.exe`。

## 反馈与错误报告

发现问题或有建议？请[提交 Issue](../../issues)，并注明游戏版本、语言、模组版本、相关水晶及问题复现步骤。

## 免责声明

这是由玩家制作的非官方模组，与 Electronic Arts 或 Maxis 无关。
