# BORED WHISKY 小红书图文生成 Skill

为 **BORED WHISKY（年轻人的口袋威士忌）** 生成小红书图文内容，包括图片生成提示词（适配 GPT Image2 / Nano Banana Pro / Seedream5.0）和小红书文案（标题 + 正文 + 标签）。

---

## 功能特点

- **内置品牌 DNA**：口号、IP、规格、用户画像、使用场景全部内置
- **6+2 模板体系**：6 种结构化爆款模板 + 2 种自由创意模式
- **一问一答交互**：5 步流程，轻松生成专业级图文
- **双份输出**：图片提示词 + 小红书文案，一次搞定
- **AI 审核规避**：人物不露正脸，侧脸/背影/道具遮挡/景深虚化
- **开源字体**：所有图片文字使用开源免费可商用字体

---

## 安装方式

### 方法一：直接复制（通用）

1. 克隆或下载本仓库
2. 将 `bored-whisky-xhs` 目录复制到你的 AI 平台 skills 目录：
   ```
   cp -R bored-whisky-xhs ~/.trae/skills/
   ```
3. 重启 AI 平台即可使用

### 方法二：Git 子模块（推荐）

```bash
cd ~/.trae/skills/
git submodule add https://github.com/ifeihong/bored-whisky-xhs.git
```

---

## 使用方法

安装后，在对话中输入：

```
$bored-whisky-xhs
```

或直接描述需求：

```
用 bored-whisky-xhs 帮我做一篇露营主题的小红书图文
```

### 交互流程

1. **输入主题** — 今天想发什么内容？
2. **选择模式** — 结构化模板 / 自由创意 / 参考图复刻
3. **选择模板**（模式1）— 6 种爆款模板任选
4. **选择情绪** — 潮酷叛逆 / 精致松弛 / 幽默玩梗 / 温暖治愈 / 高级质感
5. **确认标题** — AI 生成 3 个候选标题，你选或自己写

### 输出内容

- **图片生成提示词**：可直接复制到 GPT Image2 / Nano Banana Pro / Seedream5.0
- **小红书文案**：标题 + 多行短句正文（600字左右，配丰富 emoji）+ 分层标签

---

## 文件结构

```
bored-whisky-xhs/
├── SKILL.md              # Skill 主体（核心逻辑）
├── agents/
│   └── openai.yaml       # OpenAI/Codex 展示配置
└── README.md             # 本文件
```

---

## 品牌信息（内置）

| 项目 | 内容 |
|------|------|
| 品牌名 | BORED WHISKY |
| 口号 | 年轻人的口袋威士忌 |
| IP | BAYC #480 无聊猿（穿西装的猿猴） |
| 规格 | 350ML / 200ML 小瓶装 |
| 定位 | 数字雅痞的社交图腾 |

---

## 适用平台

- GPT Image2
- Nano Banana Pro
- Seedream5.0
- 任何支持 Markdown Skill 的 AI 平台

---

## 贡献

欢迎提交 Issue 和 PR！

---

## License

MIT License — 自由使用、修改、分发。
