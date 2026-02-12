<p align="center">
  <img src="https://img.shields.io/badge/v2.0-Production_Ready-4f46e5?style=for-the-badge" alt="Version"/>
  <img src="https://img.shields.io/badge/AI_Agents-18-059669?style=for-the-badge" alt="Agents"/>
  <img src="https://img.shields.io/badge/Video_Models-8-7c3aed?style=for-the-badge" alt="Models"/>
  <img src="https://img.shields.io/badge/Battle_Tested-30_Episodes-d97706?style=for-the-badge" alt="Episodes"/>
</p>

<h1 align="center">MagicBrush Engine<br/>神笔马良引擎</h1>

<h3 align="center">Premium AI Drama Production Studio v2.0<br/>精品漫剧中台</h3>

<p align="center">
  <strong>One sentence in, full drama out.</strong><br/>
  <strong>一句话开机，一部片落地。</strong>
</p>

<p align="center">
  <a href="#-get-started--立即获取"><img src="https://img.shields.io/badge/💰_Get_License-$1,888-e11d48?style=for-the-badge&labelColor=111" alt="Buy Now"/></a>
</p>

---

## What is MagicBrush Engine?

**MagicBrush Engine** is a production-grade AI drama creation system that runs entirely inside [Cursor IDE](https://cursor.sh). It orchestrates **18 specialized AI agents** to transform a single sentence into a fully produced animated drama — scripts, voice acting, storyboards, motion video, and final composition.

Built and battle-tested on a **30-episode commercial production**, this is not a toy demo. It's the engine behind real content.

**神笔马良引擎** 是一套运行在 Cursor IDE 中的工业级 AI 漫剧制作系统。18 个 AI Agent 协同工作，从一句话创意到成片输出，全流程自动化。基于 30 集商业项目实战打磨，不是演示品，而是真正跑通过的生产引擎。

---

## Why MagicBrush?

| | Traditional | Other AI Tools | **MagicBrush Engine** |
|---|---|---|---|
| Workflow | Manual, fragmented | Partial automation | **Full pipeline, 18 agents** |
| Script → Video | Days/weeks | Hours, manual steps | **Minutes, one command** |
| Consistency | Hard to maintain | Basic | **Asset-locked, QC-gated** |
| Cost Tracking | Guesswork | None | **Auto cost report per episode** |
| AI Review | None | None | **Gemini 6-dimension review** |
| Video Models | 1 model | 1-2 models | **8 models, auto-routing** |
| Scalability | Linear | Limited | **Batch mode, 60+ episodes** |
| Customization | Locked software | Limited API | **Open architecture, YAML-driven** |

---

## 🎬 The Pipeline — 9 Steps, Fully Automated

```
 ┌─────────────────────────────────────────────────────────────────┐
 │  "Turn this novel into a 30-episode AI drama, ancient style"   │
 └──────────────────────────────┬──────────────────────────────────┘
                                ▼
 ┌──── L0 ─────┐  ┌────────── L1 Script ──────────┐  ┌── L2 Assets ──┐
 │ 0. Init      │→│ 1. Outline  2. Script  3. QA   │→│ 4. Characters  │
 │ Style Anchor │  │    ↕ AI Taste Removal          │  │    Scenes      │
 └──────────────┘  └───────────────────────────────┘  │    Props       │
                                                       └───────┬───────┘
                                                               ▼
 ┌────────────────────── L3 Production ──────────────────────────┐
 │ 5. Storyboard → 6. Voice Acting → 7. Motion Video → 8. Compose│
 │    12-18 shots    Minimax TTS      8 AI models      Audio-driven│
 └──────────────────────────────┬────────────────────────────────┘
                                ▼
 ┌──── L4 Publish ──┐  ┌── L5 Cost ──┐  ┌──── L6 Review ────┐
 │ Cover + Subtitle  │  │ Auto Report │  │ Gemini AI Review   │
 │ Multi-platform    │  │ Per Episode │  │ 6-dim Video + Script│
 └───────────────────┘  └─────────────┘  └────────────────────┘
```

### Pipeline 全流程（中文）

| 步骤 | Agent | 产出 |
|------|-------|------|
| 0 | `mjzt-00-init` | 项目初始化、风格锚定、控制台 |
| 1 | `mjzt-01-outline` | 故事梗概、分集大纲、人物设定、世界观 |
| 2 | `mjzt-01-script` | 单集剧本（四段式结构、SMART场戏） |
| 3 | `mjzt-01-review` | P0/P1/P2 质检、AI 去味、Gate 审核 |
| 4 | `mjzt-02-assets` | 角色立绘、场景卡、道具卡、Gallery |
| 5 | `mjzt-03-storyboard` | 分镜表、静帧提示词、导演三帧法 |
| 6 | `mjzt-04-audio` | Voice Bible、TTS 多角色配音 |
| 7 | `mjzt-05-video` | AI 动镜（8 模型提示词模板） |
| 8 | `mjzt-06-compose` | 音频驱动合成、成片输出 |
| 9 | `mjzt-08-*` | 封面、字幕、多平台导出 |

---

## 🏗️ Architecture — 5 Layers + 4 Cross-Cutting Tracks

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  L0  Initialization     style.yaml · config.yaml · Dashboard
────────────────────────────────────────────────────────────────
  L1  Script Layer        Outline → Script → QA → AI De-taste
────────────────────────────────────────────────────────────────
  L2  Asset Layer         Characters · Scenes · Props · Gallery
────────────────────────────────────────────────────────────────
  L3  Production Layer    Storyboard → Audio → Motion → Compose
────────────────────────────────────────────────────────────────
  L4  Publishing Layer    Cover · Subtitle · Multi-platform Export
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  ┃ Dispatcher ┃ QA Engine ┃ Model Router ┃ Cost Tracker ┃
  ┃  调度中枢   ┃  质检引擎  ┃  模型路由     ┃  成本追踪    ┃
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## 🔥 Key Features

### 18 AI Agents · 18 个 AI Agent
Every step of drama production has a dedicated agent — from outline to final export. No gaps, no manual handoffs.

### 8 Video Model Support · 8 种动镜模型
Supports Doubao/Kling/Seedance/Wan/Sora2/Heluos and more. Auto-routing picks the best model per shot type.

### Battle-Tested · 30 集实战验证
Built from a real 30-episode commercial production. 7 production scripts hardened and integrated back into the engine.

### Auto Cost Tracking · 每集成本自动核算
After each episode, auto-generates a detailed cost breakdown: portraits, storyboard frames, TTS, motion clips, composition — every credit accounted for.

### AI Review with Gemini · Gemini AI 审片
Upload your final video → 6-dimension AI review (visuals, pacing, audio sync, transitions, character consistency, overall). Script review included with rewrite suggestions.

### Smart QA System · 三级质检体系
P0 (structural) / P1 (AI-taste detection) / P2 (drama-specific) quality gates. AI-taste removal uses Tencent Zhuque detection model.

### One-Sentence Dispatch · 一句话调度
Say `"Turn this novel into a 30-episode AI drama"` and the dispatcher orchestrates all 18 agents automatically.

### Batch Production · 批量生产模式
`"Batch produce episodes 1-10"` — parallel pipeline execution with per-episode progress tracking.

### Dashboard & Bot · 控制台 + AI 助手
Auto-generated project dashboard with full pipeline visualization. Built-in chatbot guides you through every step.

### YAML-Driven · YAML 驱动
All configuration, assets, and state stored in human-readable YAML. Full transparency, easy to modify and extend.

---

## 📊 Production Cost Estimate

| Item | Per Episode | Notes |
|------|------------|-------|
| Character Portraits | ~50 credits | 5-10 images via Jimeng |
| Storyboard Frames | ~100 credits | 12-18 frames via Seedream |
| TTS Voice Acting | ~20 credits | ~500 chars via Minimax |
| AI Motion Video | ~200 credits | 3-8 clips via Seedance |
| **Total** | **~370 credits** | **~$3-5 per episode** |

> At $3-5 per episode, a 30-episode drama costs **$90-150** in AI generation fees.

---

## 🖥️ How It Works — 3 Steps

### Step 1: Open in Cursor
Drag the engine folder into Cursor IDE. The dashboard opens automatically.

### Step 2: Talk to the Bot
Click the animated bot in the bottom-right corner. Say "New Project" or "Quick Start".

### Step 3: Paste & Go
Copy the command the bot gives you, paste into Cursor's chat, press Enter. 18 agents take it from there.

```
You: "Create a new ancient Chinese fantasy drama about a magic paintbrush"
Engine: → Init → Outline → Script → QA → Assets → Storyboard → Audio → Video → Compose → Done ✓
```

---

## 📦 What's Included

```
MagicBrush-Engine-v2.0/
├── .cursor/skills/          ← 18 AI Agent definitions
│   ├── mjzt-00-init/        Project initialization
│   ├── mjzt-01-outline/     Story outline & characters
│   ├── mjzt-01-script/      Script generation
│   ├── mjzt-01-review/      QA & AI de-taste
│   ├── mjzt-02-assets/      Visual asset pipeline
│   ├── mjzt-02-world/       World-building
│   ├── mjzt-03-scenes/      Scene segmentation
│   ├── mjzt-03-storyboard/  Storyboard & shot list
│   ├── mjzt-04-audio/       Voice Bible & TTS
│   ├── mjzt-05-video/       Motion video (8 models)
│   ├── mjzt-06-compose/     Final composition
│   ├── mjzt-08-cover/       Cover & poster
│   ├── mjzt-08-subtitle/    Subtitle timing
│   ├── mjzt-08-export/      Multi-platform export
│   ├── mjzt-dispatch/       Pipeline dispatcher
│   ├── mjzt-qa/             QA engine
│   ├── mjzt-models/         Model router
│   ├── mjzt-cost/           Cost tracker
│   └── mjzt-qa-gemini/      Gemini AI review
├── .cursor/rules/           ← Auto-linking rules
├── index.html               ← Engine dashboard
├── bot.js                   ← AI assistant chatbot
├── README.md                ← Quick start guide
└── Sample Project/          ← Working demo project
    ├── script/              Full script set
    ├── assets/              Character & scene assets
    ├── storyboard/          Shot lists & storyboards
    ├── audio/               Dubbing configuration
    ├── video/               Motion plans
    └── _views/              Visual preview pages
```

---

## 🎯 Who Is This For?

| Audience | Use Case |
|----------|----------|
| **Solo Creators** | Produce AI dramas independently, no team needed |
| **Content Studios** | Scale production with batch mode, 60+ episodes |
| **Agencies** | White-label engine for client projects |
| **Educators** | Teach AI video production with structured curriculum |
| **Developers** | Extend with custom agents, models, and workflows |

---

## 💰 Get Started · 立即获取

### MagicBrush Engine v2.0 — $1,888

**What you get:**
- Full engine source (18 AI Agents + scripts + templates)
- Sample project with complete production artifacts
- Dashboard + AI chatbot assistant
- 8 video model prompt templates
- Batch production mode
- Gemini AI review integration
- Auto cost tracking system
- Free updates for v2.x

**购买包含：**
- 完整引擎源码（18 个 AI Agent + 脚本 + 模板）
- 示范项目（含完整制作产物）
- 控制台 + AI 助手机器人
- 8 种动镜模型提示词模板
- 批量生产模式
- Gemini AI 审片集成
- 自动成本追踪系统
- v2.x 版本免费更新

<p align="center">
  <a href="https://github.com/FATIMA2025/MagicBrush-Engine/issues/new?title=Purchase%20License&body=I%20would%20like%20to%20purchase%20MagicBrush%20Engine%20v2.0."><img src="https://img.shields.io/badge/💰_Purchase_License-$1,888-e11d48?style=for-the-badge&labelColor=111" alt="Purchase"/></a>
</p>

> **Purchase:** Contact via [GitHub Issues](https://github.com/FATIMA2025/MagicBrush-Engine/issues/new?title=Purchase%20License&body=I%20would%20like%20to%20purchase%20MagicBrush%20Engine%20v2.0.) or email for payment link.
>
> **购买方式：** 通过 [GitHub Issues](https://github.com/FATIMA2025/MagicBrush-Engine/issues/new?title=购买授权&body=我想购买神笔马良引擎%20v2.0。) 或邮件联系获取付款链接。

---

## ❓ FAQ

**Q: Do I need coding skills?**
A: No. You interact with the engine using natural language in Cursor IDE. The bot guides you step by step.

**Q: What AI services do I need?**
A: The engine routes to multiple AI models (Jimeng, Seedream, Minimax, Kling, etc.) via API credits. Typical cost is $3-5 per episode.

**Q: Can I customize the style?**
A: Yes. Everything is driven by `style.yaml` — change the visual style, aspect ratio, target platform, and models with simple YAML edits.

**Q: Is this a SaaS subscription?**
A: No. This is a one-time purchase. You own the engine, run it locally, and can modify it freely.

**Q: Can I use it commercially?**
A: Yes. Single-seat commercial license included. Contact us for team/enterprise licensing.

**Q: 需要编程基础吗？**
A: 不需要。在 Cursor 里用自然语言对话即可，AI 机器人会引导你每一步操作。

**Q: 这是订阅制吗？**
A: 不是。一次购买，永久使用。引擎在本地运行，可自由修改和扩展。

---

## 📋 Requirements

- [Cursor IDE](https://cursor.sh) (latest version)
- Active Cursor Pro subscription (for AI agent execution)
- API credits for AI generation services (Jimeng/Seedream/Minimax etc.)

---

## 📜 License

Commercial license. Single-seat. See LICENSE file for details.

---

<p align="center">
  <strong>MagicBrush Engine · 神笔马良引擎</strong><br/>
  <em>"One sentence in, full drama out."</em><br/>
  <em>「一句话开机，一部片落地。」</em>
</p>

<p align="center">
  <sub>© 2025-2026 MagicBrush Studio. All rights reserved.</sub>
</p>
