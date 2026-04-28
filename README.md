Waifu Academy 0.13.5 PC Gallery & Replay Unlock Patch with Replay UI quick_menu restoration.

Waifu Academy 0.13.5 PC 画廊与回放解锁补丁，并修复 Replay 回放模式下底部 quick_menu 操作按钮丢失的问题。

# Waifu Academy 0.13.5 Gallery Unlock Patch  
# Waifu Academy 0.13.5 画廊解锁补丁

## 简介 / Introduction

这是一个适用于 **Waifu Academy 0.13.5 PC** 的轻量级 Ren'Py 补丁。  
This is a lightweight Ren'Py patch for **Waifu Academy 0.13.5 PC**.

该补丁用于在全新存档或未完成流程的情况下解锁游戏内 Gallery / Replay 内容，并修复部分情况下进入 Replay 后底部操作按钮消失的问题。  
The patch unlocks in-game Gallery / Replay content on a fresh save or unfinished playthrough, and fixes the issue where the bottom quick menu buttons may disappear after entering Replay mode.

---

## 功能 / Features

- 解锁 Gallery / Replay 内容  
  Unlocks Gallery / Replay content

- 支持全新存档下直接访问画廊  
  Allows Gallery access even on a fresh save

- 修复 Replay 模式下底部按钮丢失的问题  
  Fixes missing bottom buttons in Replay mode

- 恢复 `quick_menu`，包括返回、历史、跳过、自动、保存、快速保存、快速读取、选项等按钮  
  Restores `quick_menu`, including Back, History, Skip, Auto, Save, Quick Save, Quick Load, Preferences, and related buttons

- 不修改原始游戏资源文件  
  Does not modify original game asset files

---

## 适用版本 / Supported Version

| 项目 / Item | 版本 / Version |
|---|---|
| Game / 游戏 | Waifu Academy 0.13.5 PC |
| Engine / 引擎 | Ren'Py 8.2.3 tested |
| Platform / 平台 | Windows PC tested |

其他版本未测试，不保证兼容。  
Other versions are not tested and compatibility is not guaranteed.

---

## 安装方法 / Installation

1. 下载本仓库中的补丁文件。  
   Download the patch file from this repository.

2. 将补丁文件放入游戏目录的 `game` 文件夹中。  
   Place the patch file into the game's `game` folder.

示例路径 / Example path:

```text
WaifuAcademy-0.13.5-pc/
├─ game/
│  ├─ gamewa_unlock_replay.rpy
│  ├─ gallery.rpy
│  ├─ screens.rpy
│  └─ ...
├─ renpy/
├─ lib/
└─ WaifuAcademy.exe
