# Aliya DLC Mod

《彼方的她 aliya》DLC 剧情还原模组：将未完成的 DLC 剧情资源
（由 aliyadb 数据重建）重新恢复到可玩状态。

> **本项目为玩家自发制作的第三方 MOD，与官方制作组无关，未获得权利人的授权或许可。**
> 《彼方的她-Aliya》的著作权属于其开发方 TDGame Studio；
> 剧情文本与游戏资源的版权归原制作组所有。如权利人要求，本项目将立即删除。

## 安装

1. 下载最新 [Release] 压缩包
2. 解压到游戏根目录（`Aliya.exe` 所在目录），覆盖同路径文件
3. 启动游戏即可自动进入 DLC 剧情

**硬性要求：游戏安装路径不能含中文字符**

- `C:\steam\steamapps\common\Aliya` ✅
- `C:\蒸汽\steamapps\common\Aliya` ❌

## 特性

- 自动进入 DLC：启动进主界面后自动开始 DLC 剧情
- DLC 进度随游戏存档保存/读档恢复，无需重复推进
- 快捷键：游戏内按F9可开始 DLC 流程
  （若需关闭自动进入，在BepInEx\config中设置AutoEnterDLC=false，
  并在BepInEx\plugins目录放置.enter_dlc文件手动触发）

## 反馈

遇到问题请附带 `游戏目录\BepInEx\LogOutput.log` 一起提交 Issue。

## 本仓库包含什么

本仓库目前只包含文档与许可证文件。

插件本体 `AliyaDlcPlugin.dll` 以**二进制形式**在 Releases 中分发，**源码暂未公开**。
因此 MIT 许可证仅覆盖本仓库中由作者原创的文档与代码；
插件二进制中源自游戏程序集的部分、以及 DlcData 目录下的内容，均**不在** MIT 覆盖范围内，
详见 [NOTICE.md](NOTICE.md)。

## 许可证

| 内容 | 许可证 |
|---|---|
| 本项目作者的原创代码与文档 | MIT，全文见 [LICENSE](LICENSE) |
| `DlcData`（剧情 JSON / 文本 / 图片） | 非本项目所有，本项目不授予任何权利，见 [LICENSE.DATA](LICENSE.DATA) |
| 随包分发的第三方组件 | 各自的原始许可证，全文见 [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt) |

## 第三方组件

- **BepInEx** 5.4.23.5 —— MIT（注意：BepInEx 6 及以后版本已改为 LGPL-2.1）
- **winhttp.dll / doorstop** —— UnityDoorstop 4.5.0，**LGPL-2.1**（不是 MIT）
- **0Harmony / 0Harmony20 / HarmonyXInterop** —— HarmonyX，MIT
- **MonoMod / Mono.Cecil** —— MIT

各组件版权与许可证全文见 [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt)。
