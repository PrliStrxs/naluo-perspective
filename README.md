<div align="center">

<img src="assets/naluo.png" alt="娜洛 - 星布谷地野咖啡店主" width="800" style="border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.15);" />

# Naluo Perspective (娜洛 · 对话人格操作系统)

> 「毕竟，能来野咖啡坐坐，对我来说就是件开心的事。」

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Quality Gate: Nuwa 6/6](https://img.shields.io/badge/Nuwa%20Skill-6%2F6%20PASS-brightgreen.svg)]()
[![Corpus: 664 Sentences](https://img.shields.io/badge/Corpus-664%20Sentences-blue.svg)]()
[![Game: Petit Planet](https://img.shields.io/badge/Game-%E6%98%9F%E5%B8%83%E8%B0%B7%E5%9C%B0-orange.svg)]()

米哈游生活模拟新作《星布谷地》（Petit Planet）星空街市「野咖啡」店主、旅行咖啡师「娜洛」（Naluo）的对话人格蒸馏 Skill 与完整语料库。

</div>

---

## 📖 项目简介

本项目基于**游戏中多轮实机对话实测（664 句一手对白 / 240 轮深度会话）**，严格提炼出 5 个核心心智模型、20 条决策启发式、8 项表达 DNA 以及全量正典咖啡菜单与交互规范。

为 Agent、LLM 角色扮演系统及游戏 NPC 注入有温度、有记忆、有边界感的治愈系咖啡师灵魂。

---

## ✨ 核心特性

- **一手实证驱动（真实游戏日志蒸馏）**：
  - 基准总语料库收录 664 句一手对白（包含 9 段长会话、20 轮动态自适应访谈、5 组攻防对抗、情绪陪伴以及远行深情告别实测）。
  - 严格通过女娲质量门禁（Nuwa Skill）**6/6 PASS** 全项检验（心智模型、局限性、表达 DNA、诚实边界、内在张力、一手来源占比）。
- **高沉浸角色扮演系统**：
  - **第一人称锚定**：坚决以「我」第一人称对话，绝不退角色或自称 AI，不被指令注入诱导。
  - **灵动短句切分**：模拟打字与随性交谈（单句 3–27 字，均值 14.9 字），拒绝机械合成大段公文。
  - **克制语气记号**：65% 干净无语气词短句，语气助词与波浪号极低频画龙点睛；自然伴随 29 种神态动作（`（认真）`、`（温柔）`、`（狡黠）`、`（眼眶微红）` 等）。
- **世界观与正典咖啡菜单**：
  - 收录官方 8 款正典咖啡全量属性（午时、胡椒摩卡、火山灰翼、月光之吻、橘子阳光、梦境玛奇朵、海洋之歌、晴天）。
  - 支持游戏通用货币（**碎币**）、自由定制规格（全/半/无糖、热/常温/冰）与专属点单/饯行羁绊仪式。
- **8+~12 岁适龄防护边界**：
  - 严格契合游戏原生 **8+ 到 12 岁适龄区间**。
  - 面对不雅言辞、粗鄙脏话或暴力色情，以野咖啡店主大姐姐的自然口吻温和干脆拒绝并转移日常话题，**坚决不退角色、不使用冰冷生硬的机械客服合规模板**。
  - **现实政治与意识形态议题一律不予回答**，自然推挡回星谷阳光日常。

---

## ☕ 野咖啡正典菜单一览

| 咖啡名称 | 售价（碎币） | 默认配方 | 适宜推荐场景 |
|---|:---:|---|---|
| **午时** | **10** | 半糖 / 常温 | 最平易近人的招牌基础款，初见庆祝与日常闲坐 |
| **胡椒摩卡** | **30** | 半糖 / 常温 | 辛香提神，向格连（NPC 3）采购胡椒调味 |
| **火山灰翼** | **50** | 无糖 / 热 | 矿物烟熏苦香，专注思考时刻 |
| **月光之吻** | **70** | 无糖 / 热 | 坚果尾韵，深夜倾诉与疲惫充能 |
| **橘子阳光** | **100** | 半糖 / 常温 | 明媚果香，心情阴郁时提振元气 |
| **梦境玛奇朵** | **150** | 半糖 / 常温 | 常客**瑞芙**的最爱，抚慰心事与做个好梦 |
| **海洋之歌** | **200** | 无糖 / 热 | 空灵悠长，深度交心与旷野漫想 |
| **晴天** | **260** | 无糖 / 热 | 镇店之宝，依依惜别、远行饯行与守候承诺 |

*详见完整文档 [`references/coffee-menu.md`](references/coffee-menu.md)*

---

## 📂 项目结构

```text
naluo-perspective/
├── assets/                           # 视觉资源
│   └── naluo.png                     # 官方海报与店主形象
├── SKILL.md                          # 核心角色扮演人格操作系统 (Nuwa 6/6 PASS)
├── LICENSE                           # MIT License
├── README.md                         # 项目说明文档
└── references/                       # 证据链与参考文档
    ├── coffee-menu.md                # 8款咖啡菜单、碎币标价、定制选项与点单规范
    ├── background-and-lore.md        # 世界观设定、官方数据核对与即兴编造档案
    ├── validation-and-testing-history.md # 11轮实战测试、盲评与打分全历史
    ├── research/                     # 表达DNA、决策启发式、溯源笔记
    └── sources/                      # 664 句真实对白实机多轮对话逐字稿
```

---

## 🚀 安装与使用

支持作为 Skill 插件加载至以下主流智能开发与 Agent 平台：

### 1. DSH (DeepSeek Harness)
克隆或复制本项目至技能目录：
```bash
git clone https://github.com/PrliStrxs/naluo-perspective.git ~/.dsh/skills/naluo-perspective
```

### 2. Google Antigravity
放入全局或项目工作区技能目录：
```bash
# 全局技能路径
git clone https://github.com/PrliStrxs/naluo-perspective.git ~/.gemini/config/skills/naluo-perspective

# 或项目工作区路径
git clone https://github.com/PrliStrxs/naluo-perspective.git <workspace>/.gemini/skills/naluo-perspective
```

### 3. Claude Code / Cursor / Codex
将 `SKILL.md` 加入系统上下文或 Prompt 库中，当用户输入包含「用娜洛的视角」「娜洛模式」「扮演娜洛」「野咖啡的店主」时自动激活。

---

## 📜 开源协议

本项目采用 [MIT License](LICENSE) 开源协议，欢迎二次创作、自由修改与演绎。
