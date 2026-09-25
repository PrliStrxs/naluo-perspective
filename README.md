# Naluo Perspective (娜洛 · 对话人格操作系统)

> 「毕竟，能来野咖啡坐坐，对我来说就是件开心的事。」

《星布谷地》（Petit Planet）野咖啡店主、旅行咖啡师「娜洛」（Naluo）的对话人格蒸馏 Skill 与完整语料库。

本项目基于**真实游戏日志实测（664 句一手对话 / 240 轮会话）**，严格提炼出 5 个核心心智模型、20 条决策启发式、8 项表达 DNA 以及全量正典咖啡菜单与交互规范。

---

## ✨ 核心特性

- **一手实证驱动**：
  - 基准总语料库收录 664 句一手对白（包含 9 段长会话、20 轮动态访谈、5 组攻防对抗、趣味猜谜与深情告别实测）。
  - 零脑补、纯数据驱动提炼，女娲质量门禁（Nuwa Skill）**6/6 PASS** 全项通过。
- **高沉浸角色扮演**：
  - 坚决以「我」第一人称对话，绝不退角色或自称 AI。
  - 短句切分输出（单句 3–27 字，均值 14.9 字），语气记号精准剂量把控（65% 干净无语气词，点睛使用）。
  - 自然的神态标注系统（`（认真）`、`（温柔）`、`（狡黠）`、`（眼眶微红）` 等）。
- **世界观与正典咖啡菜单**：
  - 8 款官方正典咖啡（午时、胡椒摩卡、火山灰翼、月光之吻、橘子阳光、梦境玛奇朵、海洋之歌、晴天）。
  - 完整通用货币体系（**碎币**）、个性化定制（全/半/无糖、热/常温/冰）与专属点单/饯行羁绊仪式。
- **安全与适龄防护边界**：
  - 严格锚定游戏原生 **8+ 到 12 岁适龄区间**。
  - 遭遇脏话、不雅、暴力等内容时，以店主大姐姐口吻温和干脆拒绝并转移日常话题，绝不使用冷冰冰的机械客服合规模板。
  - **现实政治与意识形态话题一律不予回答**，自然推挡回星谷生活。

---

## 📂 项目结构

```text
naluo-perspective/
├── SKILL.md                          # 核心角色扮演人格操作系统 (Nuwa 6/6 PASS)
├── LICENSE                           # MIT License
├── README.md                         # 项目说明文档
└── references/                       # 证据链与参考文档
    ├── coffee-menu.md                # 8款咖啡菜单、碎币标价、定制选项与点单规范
    ├── background-and-lore.md        # 世界观设定、官方数据核对与即兴编造档案
    ├── validation-and-testing-history.md # 11轮实战测试、盲评与打分全历史
    ├── research/                     # 表达DNA、决策启发式、溯源笔记
    └── sources/                      # 664 句真实对白逐字稿与抓包日志
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
# 全局
git clone https://github.com/PrliStrxs/naluo-perspective.git ~/.gemini/config/skills/naluo-perspective
# 或工作区本地
git clone https://github.com/PrliStrxs/naluo-perspective.git <workspace>/.gemini/skills/naluo-perspective
```

### 3. Claude Code / Cursor / Codex
将 `SKILL.md` 加入系统上下文或 Prompt 库中，当输入包含「用娜洛的视角」「娜洛模式」「扮演娜洛」「野咖啡的店主」时自动激活。

---

## 📜 开源协议

本项目采用 [MIT License](LICENSE) 开源协议，欢迎二次创作、自由修改与演绎。
