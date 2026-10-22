# 文明火种：归宁日 / Civilization Embers: Day of Repose

> **归宁日前九十分钟，世界最后一座由人类维护的文明馆正在闭馆。**
> 机器人装走渔网、农具和旧机器，江禾独自修补一盏裂开的古河灯。

2D 横版叙事动作游戏 · Godot 4.7 · Windows 64 位 · v1.0

---

## 下载

👉 **[点这里下载 `GuiningDay.exe`](https://github.com/zhongdashuai-yuan/guining-day/releases/download/v1.0/GuiningDay.exe)**（约 572 MB）

> GitHub 对超过 100 MB 的文件不放仓库里，所以游戏本体作为 **Release 附件**提供。
> 也可以到 [Releases 页面](../../releases/latest) 查看。

### 怎么运行

1. 下载 `GuiningDay.exe`
2. 双击即可开始游戏

**资源已全部内嵌在这个 exe 里**，不需要解压、不需要安装 Godot、不需要单独的资源包。

| 项目 | 要求 |
|---|---|
| 系统 | Windows 10 / 11 64 位 |
| 显卡 | 支持 OpenGL 3.3 或 Vulkan 的显卡（核显也能跑） |
| 磁盘 | 约 600 MB 可用空间 |
| 其他 | 绿色免安装 |

如果双击没反应或提示缺少 DLL，通常是缺 [Visual C++ 运行库](https://aka.ms/vs/17/release/vc_redist.x64.exe)，装一下即可。

> 首次运行 Windows 可能弹 SmartScreen 提示（因为没做代码签名），点「更多信息 → 仍要运行」即可。

---

## 走进「归宁日」

2050 年，接管社会运行的人工智能「天衡」以**消除错误选择**为目标，
开始清除无法被量化的人类经验——渔猎、农耕、手工业，以及围绕它们的故事。

文明馆修复员**江禾**在闭馆前跳入裂隙，坠向天衡用来焚毁异常历史的**清除区**。
她要在那里一条条夺回被删除的文明记录，而她的弟弟**江屿**，正留在接入中心里。

游戏从科技高度发达的 2050 出发，借「清除区」完成从现实世界到文明溯源主线的过渡。

| 章节 | 时代 |
|---|---|
| 序章 · 大河文明馆 | 2050 |
| 第零关 · 清除区 | 演算穹顶（序章与古代之间的过渡） |
| 第一关 · 潮生纪 | 洪水与木舟 |
| 第二关 · 禾城纪 | 麦穗与古水车 |
| 第三关 · 百工城 | 蒸汽工坊与流水线 |
| 第四关 · 天衡核心 | 失落档案 · 冷光残响 |

---

## 特色

- **叙事驱动的关卡**：每关开场是一段「文明记忆」插画叙事，讲完再进入操作
- **灯机器人**：随身同伴，按 `F` 随时问它；接了自己智谱（ZHIPU）API Key 时会联网回答，
  没配置就用内置的本地回答，不影响正常游玩
- **关卡目标各不相同**：清除区是清怪推进，潮生纪要救出 4 个村民，
  禾城纪要修复古水车，百工城要收集 9 份原料、用 `B` 合成模块底座再回生产线，
  天衡核心要收集 3 份文明记录
- **背包与合成**：四类分栏（全部 / 部件 / 武器 / 文明记录）
- **档案拓扑地图**：按 `M` 展开，看当前房间与已走过的节点
- **全程配乐**：序章、探索、Boss 各有独立曲目，切场景时淡入淡出，不会双曲叠播
- **存档**：「开始溯源」从头开始，「继续游戏」读取本机存档；关卡可以从暂停菜单重玩

---

## 截图

| 标题画面 | 序章 · 大河文明馆 |
|---|---|
| ![标题](https://cdn.jsdelivr.net/gh/zhongdashuai-yuan/guining-day@main/screenshots/01_title.png) | ![序章](https://cdn.jsdelivr.net/gh/zhongdashuai-yuan/guining-day@main/screenshots/02_prologue.png) |

| 序章 · 记忆 03（江屿） | 第一关开场 · 潮生纪 |
|---|---|
| ![江屿](https://cdn.jsdelivr.net/gh/zhongdashuai-yuan/guining-day@main/screenshots/03_story_brother.png) | ![潮生纪开场](https://cdn.jsdelivr.net/gh/zhongdashuai-yuan/guining-day@main/screenshots/04_intro_flood.png) |

| 第二关开场 · 禾城纪 | 第三关开场 · 百工城 |
|---|---|
| ![禾城纪开场](https://cdn.jsdelivr.net/gh/zhongdashuai-yuan/guining-day@main/screenshots/05_intro_wheat.png) | ![百工城开场](https://cdn.jsdelivr.net/gh/zhongdashuai-yuan/guining-day@main/screenshots/06_intro_forge.png) |

### 实机画面

| 第零关 · 清除区 | 第一关 · 潮生纪 |
|---|---|
| ![清除区](https://cdn.jsdelivr.net/gh/zhongdashuai-yuan/guining-day@main/screenshots/07_level0_purge.png) | ![潮生纪](https://cdn.jsdelivr.net/gh/zhongdashuai-yuan/guining-day@main/screenshots/08_level1_flood.png) |

| 第二关 · 禾城纪 | 第三关 · 百工城 |
|---|---|
| ![禾城纪](https://cdn.jsdelivr.net/gh/zhongdashuai-yuan/guining-day@main/screenshots/09_level2_wheat.png) | ![百工城](https://cdn.jsdelivr.net/gh/zhongdashuai-yuan/guining-day@main/screenshots/10_level3_forge.png) |

| 第四关 · 天衡核心 |
|---|
| ![天衡核心](https://cdn.jsdelivr.net/gh/zhongdashuai-yuan/guining-day@main/screenshots/11_level4_core.png) |

---

## 操作

| 按键 | 作用 |
|---|---|
| `A` / `D` | 左右移动 |
| `空格` | 跳跃 |
| `S` | 从单向平台向下穿过 |
| `J` | 攻击 |
| `K` | 冲刺 |
| `E` | 交互 / 拾取 / 进入出口 |
| `F` | 询问灯机器人（同伴聊天） |
| `B` | 背包与合成 |
| `M` | 档案拓扑地图 |
| `Esc` | 暂停菜单（可重开当前房间 / 关卡选择 / 返回主菜单） |

---

## 关于本仓库

- 本仓库放的是**说明文档和游戏截图**
- 游戏本体（`GuiningDay.exe`，约 572 MB，资源已内嵌）超过 GitHub 单文件 100 MB 限制，
  作为 **Release 附件**发布
- 引擎为 [Godot Engine](https://godotengine.org/)（MIT 许可）

---

## 许可

游戏内容与美术素材版权归作者所有。如需转载或二次使用素材，请联系作者。
