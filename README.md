# AliyaDlcMod
修复aliyadb上的Aliya未完成dlc的mod到可玩状态
# Aliya DLC Mod

《彼方的她 aliya》DLC 剧情还原模组：将被砍掉的 DLC 剧情资源
（由 aliyadb 数据重建）重新修复为可玩状态。

> 本项目仅供学习与研究。与官方制作组无关，不隶属于任何官方渠道。
> 剧情文本与游戏资源的版权归原制作组所有，如权利方要求，本项目将立即删除。

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
- 快捷键：游戏内按 `F9` 可开始DLC流程
  （若需关闭自动进入，在 `BepInEx\config` 中设置 `AutoEnterDLC=false`，
   并在 `BepInEx\plugins` 目录放置 `.enter_dlc` 文件手动触发）

## 反馈

遇到问题请附带 `游戏目录\BepInEx\LogOutput.log` 一起提交 Issue。

## 第三方组件

- [BepInEx](https://github.com/BepInEx/BepInEx) （MIT）——插件框架
- `winhttp.dll` / doorstop 引导器 —— BepInEx 官方加载组件（MIT）
