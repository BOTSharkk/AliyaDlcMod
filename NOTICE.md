# NOTICE

本文件说明本仓库的许可证适用范围、与官方的关系，以及随本项目分发的第三方组件。

## 一、许可证适用范围

本仓库中由本项目作者撰写的原创代码与文档，采用 **MIT 许可证**，全文见 [LICENSE](LICENSE)。

MIT 许可证**仅覆盖本项目作者的原创贡献**，不覆盖以下任何内容：

| 内容 | 说明 |
|---|---|
| `DlcData` 目录下的全部内容 | 剧情 JSON、文本与图片，权利属于 TDGame Studio，见 [LICENSE.DATA](LICENSE.DATA) |
| 《彼方的她-Aliya》游戏本体的任何资源 | 程序集、文本、美术、音频等，权利属于其开发方 |
| 随发布包分发的第三方组件 | 各自适用其原始许可证，见 [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt) |
| 插件二进制中源自游戏程序集的部分 | 源码未公开，MIT 不覆盖此部分 |

## 二、与官方的关系

本项目为玩家自发制作的第三方 MOD，《彼方的她-Aliya》的著作权属于其开发方 TDGame Studio。

本项目与 TDGame Studio 及任何官方渠道**无隶属、合作或授权关系**，
并且**未获得权利人的授权或许可**。

## 三、权利主张与下架

如权利人认为本项目侵犯其权利，请通过 GitHub Issue 或直接联系仓库作者（GitHub: @BOTSharkk）。
本项目将在收到通知后立即移除相关内容。

## 四、随发布包分发的第三方组件

| 组件 | 版本 | 许可证 | 版权 |
|---|---|---|---|
| BepInEx (`BepInEx*.dll`) | 5.4.23.5 | MIT | Copyright (c) 2018 Bepis |
| UnityDoorstop (`winhttp.dll`, `doorstop_config.ini`) | 4.5.0 | **LGPL-2.1** | Copyright (C) NeighTools |
| HarmonyX (`0Harmony.dll`, `0Harmony20.dll`, `HarmonyXInterop.dll`) | — | MIT | Copyright (c) 2020 BepInEx |
| MonoMod (`MonoMod.RuntimeDetour.dll`, `MonoMod.Utils.dll`) | — | MIT | Copyright (c) 2015 - 2020 0x0ade |
| Mono.Cecil (`Mono.Cecil*.dll`) | — | MIT | Copyright (c) 2008 - 2015 Jb Evain |

### 关于 UnityDoorstop（LGPL-2.1）的源码获取

随包分发的 UnityDoorstop 二进制文件为**原样再分发，未作任何修改**。
按照 LGPL-2.1 第 6 条，其对应源码可通过以下地址获取：

- 源码仓库：https://github.com/NeighTools/UnityDoorstop
- 对应版本：`v4.5.0`

许可证全文见 [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt)。

## 五、BepInEx 版本提示

BepInEx 5.x（含本项目使用的 5.4.23.5）采用 MIT 许可证；
**BepInEx 6 及之后版本已改为 LGPL-2.1**。若将来升级 BepInEx，请重新核对其许可证与义务。
